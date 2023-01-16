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
    uses: semantic-release-action/rust/.github/workflows/ci.yml@v3
```

### Inputs

| Input Parameter |   Default    | Description                                                                            |
| :-------------: | :----------: | -------------------------------------------------------------------------------------- |
|    toolchain    |   `stable`   | Rust toolchain specification. [Details](#toolchain)                                    |
|  test-command   | `cargo test` | Shell command used to provide confidence in proposed changes. [Details](#test-command) |

#### toolchain

Specify a Rust [toolchain].

[toolchain]: https://rust-lang.github.io/rustup/concepts/toolchains.html#toolchain-specification

#### test-command

The shell command used to provide confidence in the proposed changes.
Defaults to `cargo test`, but you can override this to `cargo check` or anything else.

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

### Limitations

This workflow currently only supports releasing a single binary.
To release library crates, use the [release-library workflow].

[release-library workflow]: #release-library

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
    uses: semantic-release-action/rust/.github/workflows/release-binary.yml@v3
    secrets:
      cargo-registry-token: ${{ secrets.CARGO_REGISTRY_TOKEN }}
```

### Inputs

|       Input Parameter       | Required |   Default    | Description                                                                               |
| :-------------------------: | :------: | :----------: | ----------------------------------------------------------------------------------------- |
|          toolchain          |  false   |   `stable`   | Rust toolchain specification. [Details](#toolchain)                                       |
|        test-command         |  false   | `cargo test` | Shell command used to provide confidence in proposed changes. [Details](#test-command)    |
| enable-semantic-release-git |  false   |    `true`    | Use [@semantic-release/git] in your release flow. [Details](#enable-semantic-release-git) |

#### enable-semantic-release-git

Runtime option controlling the use of [@semantic-release/git].
Set to `false` to prevent semantic-release from pushing artifacts to your repository.
This may be required with certain repository settings, for example when requiring signed commits.

[@semantic-release/git]: https://github.com/semantic-release/git

### Secrets

|        Secret        | Required | Description                                               |
| :------------------: | :------: | --------------------------------------------------------- |
| cargo-registry-token |   true   | Cargo registry API token [Details](#cargo-registry-token) |

#### cargo-registry-token

API token with write permission for publishing your crate to your target registry.

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
    uses: semantic-release-action/rust/.github/workflows/release-library.yml@v3
    secrets:
      cargo-registry-token: ${{ secrets.CARGO_REGISTRY_TOKEN }}
```

### Inputs

|       Input Parameter       | Required |   Default    | Description                                                                               |
| :-------------------------: | :------: | :----------: | ----------------------------------------------------------------------------------------- |
|          toolchain          |  false   |   `stable`   | Rust toolchain specification. [Details](#toolchain)                                       |
|        test-command         |  false   | `cargo test` | Shell command used to provide confidence in proposed changes. [Details](#test-command)    |
| enable-semantic-release-git |  false   |    `true`    | Use [@semantic-release/git] in your release flow. [Details](#enable-semantic-release-git) |

### Secrets

|        Secret        | Required | Description                                               |
| :------------------: | :------: | --------------------------------------------------------- |
| cargo-registry-token |   true   | Cargo registry API token [Details](#cargo-registry-token) |
