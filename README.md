# semantic-release-action/rust

[![Build Status]](https://github.com/semantic-release-action/rust/actions/workflows/host_release.yml)

[build status]: https://github.com/semantic-release-action/rust/actions/workflows/host_release.yml/badge.svg?event=push

This repository contains _extremely opinionated_ reusable GitHub Actions workflows providing CI and CD for Rust projects.

This GitHub Action is intended to reduce duplication among very rigidly organized projects.
These are not general-purpose workflows.
You may find that they work for you and your development workflows out of the box, or they may not.

Continuous deployments brought to you by [semantic-release].

[semantic-release]: https://github.com/semantic-release/semantic-release

## CI

Continuous integration is provided by `.github/workflows/ci.yml`.

CI runs Rust tests on an `ubuntu-latest` [runner].

[runner]: https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners#supported-runners-and-hardware-resources

### Use

```yaml
---
name: CI

on:
  pull_request:

jobs:
  test:
    uses: semantic-release-action/rust/.github/workflows/ci.yml@v5
```

### Inputs

| Input Parameter | Default  | Description                                            |
| :-------------: | :------: | ------------------------------------------------------ |
|    toolchain    | `stable` | Rust toolchain specification. [Details](#toolchain)    |
|   submodules    | `false`  | Whether to checkout submodules. [Details](#submodules) |

#### toolchain

Specify a Rust [toolchain].

[toolchain]: https://rust-lang.github.io/rustup/concepts/toolchains.html#toolchain-specification

#### submodules

Whether to checkout submodules. Use `true` to checkout submodules or `recursive` to recursively checkout submodules.
This option is passed verbatim to [actions/checkout], see its documentation for more details.

[actions/checkout]: https://github.com/actions/checkout

## Release binary

Continuous deployments for Rust binaries are provided by `.github/workflows/release-binary.yml`.

Each deploy:

- publishes your crate to crates.io

  This provides compatibility with [cargo binstall].

- creates or updates git tags

  Tags are of the format `v1.2.3`, `v1.2`, and `v1`.

- uploads precompiled release binaries to the associated GitHub Release

- updates a CHANGELOG.md in your git repository

  This produces a commit (currently not gpg signed).

[cargo binstall]: https://github.com/cargo-bins/cargo-binstall

### Use

```yaml
---
name: Release

on:
  push:
    branches:
      - master
      - next
      - next-major
      - beta
      - alpha
      - "[0-9]+.[0-9]+.x"
      - "[0-9]+.x"

jobs:
  release:
    uses: semantic-release-action/rust/.github/workflows/release-binary.yml@v5
    with:
      # Optional: GitHub App authentication for pushing to protected branches
      github_app_id: ${{ vars.SEMANTIC_RELEASE_GITHUB_APP_ID }}
    secrets:
      cargo-registry-token: ${{ secrets.CARGO_REGISTRY_TOKEN }}
      # Optional, but must be specified with github_app_id input is set
      github_app_private_key: ${{ secrets.SEMANTIC_RELEASE_GITHUB_PRIVATE_KEY }}
```

### Inputs

|        Input Parameter         |    Default    | Description                                                                                       |
| :----------------------------: | :-----------: | ------------------------------------------------------------------------------------------------- |
|            targets             | all supported | Whitelist of compilation targets to upload GitHub release binaries for. [Details](#targets)       |
|           toolchain            |   `stable`    | Rust toolchain specification. [Details](#toolchain)                                               |
| disable-semantic-release-cargo |    `false`    | Disable [semantic-release-cargo] in your release flow. [Details](#disable-semantic-release-cargo) |
|  disable-semantic-release-git  |    `false`    | Disable [@semantic-release/git] in your release flow. [Details](#disable-semantic-release-git)    |
|           submodules           |    `false`    | Whether to checkout submodules. [Details](#submodules)                                            |
|         github_app_id          |               | GitHub App ID for authentication to protected branches. [Details](#github-app-authentication)     |

#### targets

Whitelist of compilation targets to upload GitHub release binaries for. Must be a subset of supported targets:

- aarch64-apple-darwin
- aarch64-unknown-linux-gnu
- aarch64-unknown-linux-musl
- i686-unknown-linux-gnu
- i686-unknown-linux-musl
- x86_64-apple-darwin
- x86_64-unknown-linux-gnu
- x86_64-unknown-linux-musl

Separate each target with whitespace:

```yaml
jobs:
  release:
    uses: semantic-release-action/rust/.github/workflows/release-binary.yml@v5
    with:
      targets: |
        aarch64-apple-darwin
        x86_64-apple-darwin
        x86_64-unknown-linux-musl
    secrets:
      cargo-registry-token: ${{ secrets.CARGO_REGISTRY_TOKEN }}
```

#### disable-semantic-release-cargo

Runtime option controlling the use of [semantic-release-cargo].
Set to `true` to prevent semantic-release from publishing your crate to the configured cargo registry.

[semantic-release-cargo]: https://github.com/semantic-release-cargo/semantic-release-cargo

#### disable-semantic-release-git

Runtime option controlling the use of [@semantic-release/git].
Set to `true` to prevent semantic-release from pushing artifacts to your repository.
This may be required with certain repository settings, for example when requiring signed commits.

[@semantic-release/git]: https://github.com/semantic-release/git

### Secrets

|         Secret         | Required | Description                                                   |
| :--------------------: | :------: | ------------------------------------------------------------- |
|  cargo-registry-token  |  false   | Cargo registry API token. [Details](#cargo-registry-token)    |
| github_app_private_key |  false   | GitHub App private key. [Details](#github-app-authentication) |

#### cargo-registry-token

API token with write permission for publishing your crate to your target registry.

#### GitHub App Authentication

GitHub App authentication can be used to allow semantic-release to push to protected branches. This is particularly useful when you have branch protection rules enabled with required status checks.

When both `github_app_id` input and `github_app_private_key` secret are provided, the workflow will use GitHub App authentication instead of the default GITHUB_TOKEN.

To use GitHub App authentication:

1. Create a GitHub App with the following permissions:

   - Repository contents: Read & write
   - Metadata: Read-only
   - Commit statuses: Read & write

2. Install the app on your repository

3. Generate a private key for your app and store it as a secret in your repository

4. Update your workflow to include the app credentials:

```yaml
jobs:
  release:
    uses: semantic-release-action/rust/.github/workflows/release-binary.yml@v5
    with:
      toolchain: stable
      github_app_id: ${{ secrets.SEMANTIC_RELEASE_GITHUB_APP_ID }}
    secrets:
      cargo-registry-token: ${{ secrets.CARGO_REGISTRY_TOKEN }}
      github_app_private_key: ${{ secrets.SEMANTIC_RELEASE_GITHUB_APP_PRIVATE_KEY }}
```

If you provide only one of the two required parameters (`github_app_id` input or `github_app_private_key` secret), the workflow will fail with an error message.

## Release library

Continuous deployments for Rust libraries are provided by `.github/workflows/release-library.yml`.

Each deploy:

- publishes your crate to crates.io

  This provides compatibility with [cargo binstall].

- updates a CHANGELOG.md in your git repository

  This produces a commit (currently not gpg signed).

### Use

```yaml
---
name: Release

on:
  push:
    branches:
      - master
      - next
      - next-major
      - beta
      - alpha
      - "[0-9]+.[0-9]+.x"
      - "[0-9]+.x"

jobs:
  release:
    uses: semantic-release-action/rust/.github/workflows/release-library.yml@v5
    with:
      # Optional: GitHub App authentication for pushing to protected branches
      github_app_id: ${{ vars.SEMANTIC_RELEASE_GITHUB_APP_ID }}
    secrets:
      cargo-registry-token: ${{ secrets.CARGO_REGISTRY_TOKEN }}
      # Optional, but must be specified with github_app_id input is set
      github_app_private_key: ${{ secrets.SEMANTIC_RELEASE_GITHUB_PRIVATE_KEY }}
```

### Inputs

|        Input Parameter         | Default  | Description                                                                                       |
| :----------------------------: | :------: | ------------------------------------------------------------------------------------------------- |
|           toolchain            | `stable` | Rust toolchain specification. [Details](#toolchain)                                               |
| disable-semantic-release-cargo | `false`  | Disable [semantic-release-cargo] in your release flow. [Details](#disable-semantic-release-cargo) |
|  disable-semantic-release-git  | `false`  | Disable [@semantic-release/git] in your release flow. [Details](#disable-semantic-release-git)    |
|           submodules           | `false`  | Whether to checkout submodules. [Details](#submodules)                                            |
|         github_app_id          |          | GitHub App ID for authentication to protected branches. [Details](#github-app-authentication)     |

### Secrets

|         Secret         | Required | Description                                                   |
| :--------------------: | :------: | ------------------------------------------------------------- |
|  cargo-registry-token  |  false   | Cargo registry API token. [Details](#cargo-registry-token)    |
| github_app_private_key |  false   | GitHub App private key. [Details](#github-app-authentication) |
