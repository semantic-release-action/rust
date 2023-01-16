## [3.1.1](https://github.com/semantic-release-action/rust/compare/v3.1.0...v3.1.1) (2023-01-16)


### Bug Fixes

* fix typo in conditional logic ([6a5e8a3](https://github.com/semantic-release-action/rust/commit/6a5e8a34f4d1cdcaf09ca1e9bbe77bf24e72ac9d))

# [3.1.0](https://github.com/semantic-release-action/rust/compare/v3.0.0...v3.1.0) (2023-01-16)


### Features

* create input to opt out of cargo publish for binaries ([8b0e2aa](https://github.com/semantic-release-action/rust/commit/8b0e2aaa6727bfccace65da284e0de20d2f0fbac)), closes [#8](https://github.com/semantic-release-action/rust/issues/8)

# [3.0.0](https://github.com/semantic-release-action/rust/compare/v2.1.8...v3.0.0) (2023-01-16)


* feat!: automatically detect binary name ([b7ffa1f](https://github.com/semantic-release-action/rust/commit/b7ffa1f66693f92ceb59d627abdc971729eb2387)), closes [#6](https://github.com/semantic-release-action/rust/issues/6)


### BREAKING CHANGES

* The binary-release workflow no longer accepts
binary-name. This is automatically detected from the cargo manifest.

## [2.1.8](https://github.com/semantic-release-action/rust/compare/v2.1.7...v2.1.8) (2023-01-16)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.0.30 ([4a96e9e](https://github.com/semantic-release-action/rust/commit/4a96e9e70af7e67f7b72c84f30b6fa593faf4982))

## [2.1.7](https://github.com/semantic-release-action/rust/compare/v2.1.6...v2.1.7) (2023-01-14)


### Bug Fixes

* **ci:** invoke reusable workflow correctly ([ddeaf93](https://github.com/semantic-release-action/rust/commit/ddeaf93b8b3c75116e02e7425b112d1bac7cd9a5))
* **ci:** update semantic-release-action/github-actions to v4 ([cd0d6eb](https://github.com/semantic-release-action/rust/commit/cd0d6eb13e8b6dca517c51ee88fd26848b228d2e))

## [2.1.6](https://github.com/semantic-release-action/rust/compare/v2.1.5...v2.1.6) (2023-01-14)


### Bug Fixes

* update repository metadata ([767e482](https://github.com/semantic-release-action/rust/commit/767e482ff16c5fcf5a6851f2aefc9be6b713a061)), closes [#7](https://github.com/semantic-release-action/rust/issues/7)

## [2.1.5](https://github.com/semantic-release-action/rust/compare/v2.1.4...v2.1.5) (2023-01-14)


### Bug Fixes

* **deps:** migrate to semantic-release-action/next-release-version ([8ef03f1](https://github.com/semantic-release-action/rust/commit/8ef03f1f523610e5d372430294bc560eba337136))

## [2.1.4](https://github.com/semantic-release-action/rust/compare/v2.1.3...v2.1.4) (2023-01-14)


### Bug Fixes

* **deps:** migrate to semantic-release-action/next-release-version ([51ebb77](https://github.com/semantic-release-action/rust/commit/51ebb77c9f2770d4a6fa08a9c347e923163dfa1f))

## [2.1.3](https://github.com/semantic-release-action/rust/compare/v2.1.2...v2.1.3) (2023-01-14)


### Bug Fixes

* **deps:** migrate to semantic-release-action/github-actions ([6dfb790](https://github.com/semantic-release-action/rust/commit/6dfb790c28ae3eff9351edcb046e44a9c552de76))

## [2.1.2](https://github.com/semantic-release-action/rust/compare/v2.1.1...v2.1.2) (2023-01-12)


### Bug Fixes

* **deps:** upgrade install-github-release-binary to v2 ([2c85ed8](https://github.com/semantic-release-action/rust/commit/2c85ed8c6cbcaa8b1846a97f005d0f11316d3a3f))

## [2.1.1](https://github.com/semantic-release-action/rust/compare/v2.1.0...v2.1.1) (2023-01-11)


### Bug Fixes

* write semantic-release manifest after edit ([aecf4d4](https://github.com/semantic-release-action/rust/commit/aecf4d4c658bfb0028dbb0e24e6dd4295176d606))

# [2.1.0](https://github.com/semantic-release-action/rust/compare/v2.0.18...v2.1.0) (2023-01-11)


### Features

* add input to control committing artifacts ([bd5f033](https://github.com/semantic-release-action/rust/commit/bd5f033008d77dbb122dcdea9c0017035fddc8c1))

## [2.0.18](https://github.com/semantic-release-action/rust/compare/v2.0.17...v2.0.18) (2023-01-10)


### Bug Fixes

* cache the right node_modules directory ([2617a6b](https://github.com/semantic-release-action/rust/commit/2617a6beaa589b2df4ababb7e5cda0b3b0f82e30))

## [2.0.17](https://github.com/semantic-release-action/rust/compare/v2.0.16...v2.0.17) (2023-01-10)


### Bug Fixes

* use consistent output style ([b59a0cf](https://github.com/semantic-release-action/rust/commit/b59a0cf86f88c53e4f925a291475da9e028150cd))

## [2.0.16](https://github.com/semantic-release-action/rust/compare/v2.0.15...v2.0.16) (2023-01-10)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.0.24 ([54953ec](https://github.com/semantic-release-action/rust/commit/54953ec89b71e97a086e23d5dc83ce7dc8536f2d))

## [2.0.15](https://github.com/semantic-release-action/rust/compare/v2.0.14...v2.0.15) (2023-01-09)


### Bug Fixes

* do not prematurely cache npm information ([35f3d07](https://github.com/semantic-release-action/rust/commit/35f3d07058bd7243b30760cb3c8eff640bdd4c22))

## [2.0.14](https://github.com/semantic-release-action/rust/compare/v2.0.13...v2.0.14) (2023-01-09)


### Bug Fixes

* use scratch directory for temporary work ([3768183](https://github.com/semantic-release-action/rust/commit/376818375e5e7bcef74d2a2393a93d397e053650))

## [2.0.13](https://github.com/semantic-release-action/rust/compare/v2.0.12...v2.0.13) (2023-01-09)


### Bug Fixes

* remove extra colon from NODE_PATH ([0f22c8d](https://github.com/semantic-release-action/rust/commit/0f22c8dc201b8681ca427217a2220036db9f6979))

## [2.0.12](https://github.com/semantic-release-action/rust/compare/v2.0.11...v2.0.12) (2023-01-09)


### Bug Fixes

* inline variable expansion ([885b4e4](https://github.com/semantic-release-action/rust/commit/885b4e45492b63c0b057d9f4f36d721aecf98622))

## [2.0.11](https://github.com/semantic-release-action/rust/compare/v2.0.10...v2.0.11) (2023-01-09)


### Bug Fixes

* remove premature caching ([d3780b9](https://github.com/semantic-release-action/rust/commit/d3780b901c432c097917df0d9541251ec9d2bcc3))

## [2.0.10](https://github.com/semantic-release-action/rust/compare/v2.0.9...v2.0.10) (2023-01-09)


### Bug Fixes

* inline variable not ready to expand ([2dcea9d](https://github.com/semantic-release-action/rust/commit/2dcea9d94eba64bc160081eec2c89fa0accb1428))

## [2.0.9](https://github.com/semantic-release-action/rust/compare/v2.0.8...v2.0.9) (2023-01-09)


### Bug Fixes

* resolve logical bug ([784609a](https://github.com/semantic-release-action/rust/commit/784609afe790aa183ece2dd291fee6098e4053ed))

## [2.0.8](https://github.com/semantic-release-action/rust/compare/v2.0.7...v2.0.8) (2023-01-09)


### Bug Fixes

* create directory before writing file ([edf21e8](https://github.com/semantic-release-action/rust/commit/edf21e822e73b7b055088ff03cf241aa6dd3a55e))

## [2.0.7](https://github.com/semantic-release-action/rust/compare/v2.0.6...v2.0.7) (2023-01-09)


### Bug Fixes

* use valid bash syntax ([637528c](https://github.com/semantic-release-action/rust/commit/637528cfbbcc47377e5c32db406867df1560991d))

## [2.0.6](https://github.com/semantic-release-action/rust/compare/v2.0.5...v2.0.6) (2023-01-09)


### Bug Fixes

* use valid syntax ([bc7cb2e](https://github.com/semantic-release-action/rust/commit/bc7cb2e0524b86321075f45c65a6dc85f32882f7))

## [2.0.5](https://github.com/semantic-release-action/rust/compare/v2.0.4...v2.0.5) (2023-01-09)


### Bug Fixes

* do not use host repository as working directory ([ed81db7](https://github.com/semantic-release-action/rust/commit/ed81db72d7931014526dd818fbf97b9db5321edf))

## [2.0.4](https://github.com/semantic-release-action/rust/compare/v2.0.3...v2.0.4) (2023-01-09)


### Bug Fixes

* do not commit rust-action npm package manifest to repository ([3bb46e9](https://github.com/semantic-release-action/rust/commit/3bb46e97a227bbbcf12cce37624587a66d924883))

## [2.0.3](https://github.com/semantic-release-action/rust/compare/v2.0.2...v2.0.3) (2023-01-09)


### Bug Fixes

* correct typo in package manifest ([cecb2d7](https://github.com/semantic-release-action/rust/commit/cecb2d7cc06c7df33d53fb5b987a9b3598825e87))

## [2.0.2](https://github.com/semantic-release-action/rust/compare/v2.0.1...v2.0.2) (2023-01-09)


### Bug Fixes

* skip unnecessary semantic-release config processing ([fe9894a](https://github.com/semantic-release-action/rust/commit/fe9894a9283ab5445e16236bee43d3e0c4068cf8))

## [2.0.1](https://github.com/semantic-release-action/rust/compare/v2.0.0...v2.0.1) (2023-01-09)


### Bug Fixes

* specify shell ([f98cb8b](https://github.com/semantic-release-action/rust/commit/f98cb8bfec258240e3db4f06b6c9546959855402))

# [2.0.0](https://github.com/semantic-release-action/rust/compare/v1.3.5...v2.0.0) (2023-01-09)


* feat!: support releasing Rust libraries ([3abf0f8](https://github.com/semantic-release-action/rust/commit/3abf0f8d4f131f2e466ceec53d975b0476491414))


### BREAKING CHANGES

* release.yml workflow renamed to release-binary.yml

## [1.3.5](https://github.com/semantic-release-action/rust/compare/v1.3.4...v1.3.5) (2023-01-08)


### Bug Fixes

* **docs:** add readme ([5450fc5](https://github.com/semantic-release-action/rust/commit/5450fc5495da0a44fb0b86396685e167822b79af))

## [1.3.4](https://github.com/semantic-release-action/rust/compare/v1.3.3...v1.3.4) (2023-01-08)


### Bug Fixes

* **ci:** add ref to action invokation ([dc2da1b](https://github.com/semantic-release-action/rust/commit/dc2da1b18541091f7659f9b21af4f055893fb50d))

## [1.3.3](https://github.com/semantic-release-action/rust/compare/v1.3.2...v1.3.3) (2023-01-08)


### Bug Fixes

* **ci:** use faster method to install semantic-release-cargo ([1ca8c15](https://github.com/semantic-release-action/rust/commit/1ca8c155a4c436bcf2243b4d4038421155c5f2a9))

## [1.3.2](https://github.com/semantic-release-action/rust/compare/v1.3.1...v1.3.2) (2023-01-08)


### Bug Fixes

* **deps:** update dependency semantic-release to v20.0.2 ([a62707f](https://github.com/semantic-release-action/rust/commit/a62707f41b869e1a2a499130983d3163d3cd7baf))

## [1.3.1](https://github.com/semantic-release-action/rust/compare/v1.3.0...v1.3.1) (2023-01-08)


### Bug Fixes

* **ci:** use faster install method ([e54e68c](https://github.com/semantic-release-action/rust/commit/e54e68cf28924e873ecc8775cc51e26b387febb6))

# [1.3.0](https://github.com/semantic-release-action/rust/compare/v1.2.11...v1.3.0) (2023-01-07)


### Features

* add semantic-release-major-tag ([910ab73](https://github.com/semantic-release-action/rust/commit/910ab73a8da7c7198c67532e39451e33a4838945))

## [1.2.11](https://github.com/semantic-release-action/rust/compare/v1.2.10...v1.2.11) (2023-01-07)


### Bug Fixes

* move semantic-release deps to prod deps ([d98af11](https://github.com/semantic-release-action/rust/commit/d98af114f5ea7af26fb2cca4a6b248b97818313b))

## [1.2.10](https://github.com/semantic-release-action/rust/compare/v1.2.9...v1.2.10) (2023-01-07)


### Bug Fixes

* rename checksums file SHA256SUMS ([e9a6c41](https://github.com/semantic-release-action/rust/commit/e9a6c41f64148b7021e9403944f90e11cd1cccfa))


### Reverts

* Revert "fix: remove target suffix from binary name" ([8424747](https://github.com/semantic-release-action/rust/commit/84247476da6a5b12b7f66e85fe13ae8e946feea4))
* Revert "fix: rename checksums file" ([62f1390](https://github.com/semantic-release-action/rust/commit/62f1390dca50a64fddd80112eedd615d37ec9f73))

## [1.2.9](https://github.com/semantic-release-action/rust/compare/v1.2.8...v1.2.9) (2023-01-07)


### Bug Fixes

* rename checksums file ([e9e3fbd](https://github.com/semantic-release-action/rust/commit/e9e3fbd49a6126f5dac48ce39f581e8736974381))

## [1.2.8](https://github.com/semantic-release-action/rust/compare/v1.2.7...v1.2.8) (2023-01-07)


### Bug Fixes

* remove target suffix from binary name ([abdb48d](https://github.com/semantic-release-action/rust/commit/abdb48d367fc0b811bc69476f6621bb86d1a442c))

## [1.2.7](https://github.com/semantic-release-action/rust/compare/v1.2.6...v1.2.7) (2023-01-07)


### Bug Fixes

* reference release assets by correct path ([a4c5daf](https://github.com/semantic-release-action/rust/commit/a4c5dafe91eec55c6d2e2d293ca67594cda2fb44))

## [1.2.6](https://github.com/semantic-release-action/rust/compare/v1.2.5...v1.2.6) (2023-01-07)


### Bug Fixes

* install rust toolchain before using taiki-e/install-action ([42a991e](https://github.com/semantic-release-action/rust/commit/42a991e79430abed2790c871b87ff7623336cf57))

## [1.2.5](https://github.com/semantic-release-action/rust/compare/v1.2.4...v1.2.5) (2023-01-07)


### Bug Fixes

* plumb toolchain through to action ([dca3160](https://github.com/semantic-release-action/rust/commit/dca3160dd23d96a1cb636cf41c9fae86d60618d2))

## [1.2.4](https://github.com/semantic-release-action/rust/compare/v1.2.3...v1.2.4) (2023-01-07)


### Bug Fixes

* recurse into nested artifact directories ([38014c0](https://github.com/semantic-release-action/rust/commit/38014c057be59f158a5405eeed2a732a847c8f60))

## [1.2.3](https://github.com/semantic-release-action/rust/compare/v1.2.2...v1.2.3) (2023-01-07)


### Bug Fixes

* pass binary-name through to action ([55ced26](https://github.com/semantic-release-action/rust/commit/55ced26d190b69a38cb60bb041b72f4dede94a03))

## [1.2.2](https://github.com/semantic-release-action/rust/compare/v1.2.1...v1.2.2) (2023-01-07)


### Bug Fixes

* use path that exists ([d28b102](https://github.com/semantic-release-action/rust/commit/d28b1023c8c4dd33a6548b6c834c34093c914bae))

## [1.2.1](https://github.com/semantic-release-action/rust/compare/v1.2.0...v1.2.1) (2023-01-07)


### Bug Fixes

* alphabetize UI by target ([c4ff96b](https://github.com/semantic-release-action/rust/commit/c4ff96bb8e310f968078c28b12941965fdfe53cb))
* pass cargo-registry-token to release action ([73df727](https://github.com/semantic-release-action/rust/commit/73df7278acbb6c8907605532c2a73ad34fab1f39))

# [1.2.0](https://github.com/semantic-release-action/rust/compare/v1.1.2...v1.2.0) (2023-01-07)


### Bug Fixes

* correct typo ([1cc18fa](https://github.com/semantic-release-action/rust/commit/1cc18fa2e37ad3795b996b491ed5280c4a8062bb))


### Features

* encapsulate semantic-release configuration ([fa1c307](https://github.com/semantic-release-action/rust/commit/fa1c3072ae7fb19e7ea799d91a7729a1058aa973))

## [1.1.2](https://github.com/semantic-release-action/rust/compare/v1.1.1...v1.1.2) (2023-01-07)


### Bug Fixes

* rename secret to kebab case ([4e96a10](https://github.com/semantic-release-action/rust/commit/4e96a10066873ee60e17a4a4eefdb6036323f8c0))

## [1.1.1](https://github.com/semantic-release-action/rust/compare/v1.1.0...v1.1.1) (2023-01-07)


### Bug Fixes

* default command to cargo test ([732da09](https://github.com/semantic-release-action/rust/commit/732da0954565dbe5669ceed3261cc185f791c691))

# [1.1.0](https://github.com/semantic-release-action/rust/compare/v1.0.5...v1.1.0) (2023-01-07)


### Features

* add release workflow ([60ad162](https://github.com/semantic-release-action/rust/commit/60ad1622e23bf1b03ed5c0bf453c2e96a0f17f99))

## [1.0.5](https://github.com/semantic-release-action/rust/compare/v1.0.4...v1.0.5) (2023-01-07)


### Bug Fixes

* rename file ([4d74f96](https://github.com/semantic-release-action/rust/commit/4d74f967775571e4cbedb2d13dfb8949e182c2fa))

## [1.0.4](https://github.com/semantic-release-action/rust/compare/v1.0.3...v1.0.4) (2023-01-07)


### Bug Fixes

* Revert "fix: remove unsupported syntax" ([9c9c162](https://github.com/semantic-release-action/rust/commit/9c9c16264f149d3c9133c282e2ca87dd781434f4))

## [1.0.3](https://github.com/semantic-release-action/rust/compare/v1.0.2...v1.0.3) (2023-01-07)


### Bug Fixes

* move reusable workflow under .github/workflows ([f305572](https://github.com/semantic-release-action/rust/commit/f30557294aea311a1efed590952581fb8ca70ed4))

## [1.0.2](https://github.com/semantic-release-action/rust/compare/v1.0.1...v1.0.2) (2023-01-06)


### Bug Fixes

* remove unsupported syntax ([e74cbd1](https://github.com/semantic-release-action/rust/commit/e74cbd15422715b23fd1738b1544de52500795aa))

## [1.0.1](https://github.com/semantic-release-action/rust/compare/v1.0.0...v1.0.1) (2023-01-06)


### Bug Fixes

* use workflow_call event type ([fe76b7f](https://github.com/semantic-release-action/rust/commit/fe76b7fb0ff2f6cffa10811424df9712c3708d35))

# 1.0.0 (2023-01-06)


### Features

* add ci workflow ([29c6296](https://github.com/semantic-release-action/rust/commit/29c629683e3940f5daa3ffe4d040d11d25a4b9f9))
