# [5.0.0-beta.1](https://github.com/semantic-release-action/rust/compare/v4.5.0-beta.3...v5.0.0-beta.1) (2023-09-17)


* chore!: drop support for specifying `test-command` ([11d9061](https://github.com/semantic-release-action/rust/commit/11d906168e271496ca26d22521f74c70e79bb2b5))


### BREAKING CHANGES

* drop support for specifying `test-command`

# [4.5.0-beta.3](https://github.com/semantic-release-action/rust/compare/v4.5.0-beta.2...v4.5.0-beta.3) (2023-09-16)


### Bug Fixes

* add checkout ([e1fbdce](https://github.com/semantic-release-action/rust/commit/e1fbdce1ab115773f3ccff614ad46bc9860b8f85))

# [4.5.0-beta.2](https://github.com/semantic-release-action/rust/compare/v4.5.0-beta.1...v4.5.0-beta.2) (2023-09-16)


### Bug Fixes

* fix shell syntax ([ab93f39](https://github.com/semantic-release-action/rust/commit/ab93f39b95543e44b2d89df1fd138c87d5ed287c))

# [4.5.0-beta.1](https://github.com/semantic-release-action/rust/compare/v4.4.46...v4.5.0-beta.1) (2023-09-16)


### Features

* support multiple binaries ([841cc68](https://github.com/semantic-release-action/rust/commit/841cc686a56005005e8f5b7505ac6b42048f231c)), closes [#13](https://github.com/semantic-release-action/rust/issues/13) [#31](https://github.com/semantic-release-action/rust/issues/31)

## [4.4.46](https://github.com/semantic-release-action/rust/compare/v4.4.45...v4.4.46) (2023-09-16)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.1.2 ([6f95317](https://github.com/semantic-release-action/rust/commit/6f9531787e5c8e3360ede45f2826253fdd980089))

## [4.4.45](https://github.com/semantic-release-action/rust/compare/v4.4.44...v4.4.45) (2023-09-15)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.11 ([58a80a2](https://github.com/semantic-release-action/rust/commit/58a80a2c64409108645a3911a8d53d272de74961))

## [4.4.44](https://github.com/semantic-release-action/rust/compare/v4.4.43...v4.4.44) (2023-09-14)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.10 ([e561d1e](https://github.com/semantic-release-action/rust/commit/e561d1e575ef3ad5b7f2322c92886a22cf5687df))

## [4.4.43](https://github.com/semantic-release-action/rust/compare/v4.4.42...v4.4.43) (2023-09-12)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.7 ([f957afc](https://github.com/semantic-release-action/rust/commit/f957afca040109e89c167eac5a4bf93d6b489f76))

## [4.4.42](https://github.com/semantic-release-action/rust/compare/v4.4.41...v4.4.42) (2023-09-11)


### Bug Fixes

* disable the semantic-release-cargo plugin correctly ([7986e76](https://github.com/semantic-release-action/rust/commit/7986e76e0ae0af663e84a72a99b92f1bd38df293))

## [4.4.41](https://github.com/semantic-release-action/rust/compare/v4.4.40...v4.4.41) (2023-09-11)


### Bug Fixes

* **jq:** modify in-place ([c1f00cb](https://github.com/semantic-release-action/rust/commit/c1f00cbbb1eb8f9a0f6d8852950d8c54f355748b))

## [4.4.40](https://github.com/semantic-release-action/rust/compare/v4.4.39...v4.4.40) (2023-09-10)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.6 ([2785326](https://github.com/semantic-release-action/rust/commit/27853263504b9331b1c941df367c1658138387fd))

## [4.4.39](https://github.com/semantic-release-action/rust/compare/v4.4.38...v4.4.39) (2023-09-10)


### Bug Fixes

* remove debug prints ([6ef095a](https://github.com/semantic-release-action/rust/commit/6ef095a7b7937ccb6a3ecfc997ab10dd0712aba0))

## [4.4.38](https://github.com/semantic-release-action/rust/compare/v4.4.37...v4.4.38) (2023-09-10)


### Bug Fixes

* add missing argument ([61a257d](https://github.com/semantic-release-action/rust/commit/61a257d0e716373570977b56b0d094b520984aed))

## [4.4.37](https://github.com/semantic-release-action/rust/compare/v4.4.36...v4.4.37) (2023-09-10)


### Bug Fixes

* correct jq program to modify in-place ([1fe8ee9](https://github.com/semantic-release-action/rust/commit/1fe8ee9c90257dad64d1f6c01f2b472e5a7570d2))

## [4.4.36](https://github.com/semantic-release-action/rust/compare/v4.4.35...v4.4.36) (2023-09-10)


### Bug Fixes

* add debug information ([7059472](https://github.com/semantic-release-action/rust/commit/70594721708c8d86cc93c53d95e9ee1f5c689303))

## [4.4.35](https://github.com/semantic-release-action/rust/compare/v4.4.34...v4.4.35) (2023-09-10)


### Bug Fixes

* add missing shell property ([c816026](https://github.com/semantic-release-action/rust/commit/c816026a47f39f430c236671cbed44bd1ea645e0))

## [4.4.34](https://github.com/semantic-release-action/rust/compare/v4.4.33...v4.4.34) (2023-09-10)


### Bug Fixes

* form JSON from whitelist of selected assets properly ([0a01014](https://github.com/semantic-release-action/rust/commit/0a01014d4be095fa2049f312349d0bc05e0658fe))

## [4.4.33](https://github.com/semantic-release-action/rust/compare/v4.4.32...v4.4.33) (2023-09-09)


### Performance Improvements

* use jq to modify semantic-release manifest ([dab05bc](https://github.com/semantic-release-action/rust/commit/dab05bc0ac51dffdf0ec8d9403e1b0cc42fd86d2))

## [4.4.32](https://github.com/semantic-release-action/rust/compare/v4.4.31...v4.4.32) (2023-09-09)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.5 ([e1b156e](https://github.com/semantic-release-action/rust/commit/e1b156edbb37c4f5bf9158743a1b2e2c78e53c20))

## [4.4.31](https://github.com/semantic-release-action/rust/compare/v4.4.30...v4.4.31) (2023-09-09)


### Performance Improvements

* use jq to modify semantic-release manifest ([1372408](https://github.com/semantic-release-action/rust/commit/1372408106534a141e8e1fbcb8a2425dd8774057))

## [4.4.30](https://github.com/semantic-release-action/rust/compare/v4.4.29...v4.4.30) (2023-09-08)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.4 ([ea558fe](https://github.com/semantic-release-action/rust/commit/ea558fe1db0db4cd44a94591a6b5fd345b551984))

## [4.4.29](https://github.com/semantic-release-action/rust/compare/v4.4.28...v4.4.29) (2023-09-03)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.3 ([64d7b31](https://github.com/semantic-release-action/rust/commit/64d7b319399e5f8e58517d9f48f5acafba971326))

## [4.4.28](https://github.com/semantic-release-action/rust/compare/v4.4.27...v4.4.28) (2023-09-02)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.2 ([927062f](https://github.com/semantic-release-action/rust/commit/927062f338adb9dcabe3cf7ca75349626edab992))

## [4.4.27](https://github.com/semantic-release-action/rust/compare/v4.4.26...v4.4.27) (2023-08-31)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.2.1 ([50c13e1](https://github.com/semantic-release-action/rust/commit/50c13e17dfa990a29c31f023f9a6292377697623))

## [4.4.26](https://github.com/semantic-release-action/rust/compare/v4.4.25...v4.4.26) (2023-08-30)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.131 ([e9d3924](https://github.com/semantic-release-action/rust/commit/e9d392430a8088a0f2f17b4aceb244f0f6f34171))

## [4.4.25](https://github.com/semantic-release-action/rust/compare/v4.4.24...v4.4.25) (2023-08-25)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.1.1 ([18f7bee](https://github.com/semantic-release-action/rust/commit/18f7beefdaad7376c27c72426703fa4faccd1735))

## [4.4.24](https://github.com/semantic-release-action/rust/compare/v4.4.23...v4.4.24) (2023-08-24)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.1.0 ([5dde722](https://github.com/semantic-release-action/rust/commit/5dde72297d10482fef13d30eaa83b79e56efb92c))

## [4.4.23](https://github.com/semantic-release-action/rust/compare/v4.4.22...v4.4.23) (2023-08-20)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.9 ([8e2788d](https://github.com/semantic-release-action/rust/commit/8e2788dc6f3847e834906683d4ede9fc3b3b8be2))

## [4.4.22](https://github.com/semantic-release-action/rust/compare/v4.4.21...v4.4.22) (2023-07-22)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.125 ([3c9b030](https://github.com/semantic-release-action/rust/commit/3c9b030390759d8e7a3dcb416acfa7a1cd08e021))

## [4.4.21](https://github.com/semantic-release-action/rust/compare/v4.4.20...v4.4.21) (2023-07-20)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.123 ([6465fbb](https://github.com/semantic-release-action/rust/commit/6465fbb06389e8251d3e9a9563ba2e21519c6559))

## [4.4.20](https://github.com/semantic-release-action/rust/compare/v4.4.19...v4.4.20) (2023-07-19)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.121 ([e3ea41c](https://github.com/semantic-release-action/rust/commit/e3ea41c42b6d7442316be6e345a552ba0f1f9749))

## [4.4.19](https://github.com/semantic-release-action/rust/compare/v4.4.18...v4.4.19) (2023-07-16)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.119 ([a95ee02](https://github.com/semantic-release-action/rust/commit/a95ee0237253645736f6e83b71647163be6907d4))

## [4.4.18](https://github.com/semantic-release-action/rust/compare/v4.4.17...v4.4.18) (2023-07-15)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.117 ([e888c9e](https://github.com/semantic-release-action/rust/commit/e888c9edc8659381bb34c8d97257ac3fe0730846))

## [4.4.17](https://github.com/semantic-release-action/rust/compare/v4.4.16...v4.4.17) (2023-07-14)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.115 ([473d397](https://github.com/semantic-release-action/rust/commit/473d397a864fade097366cac1a2fab6dfc81f6a8))

## [4.4.16](https://github.com/semantic-release-action/rust/compare/v4.4.15...v4.4.16) (2023-07-12)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.114 ([4965b27](https://github.com/semantic-release-action/rust/commit/4965b2786b2af8be0cb4758d7cd01ea205ba14c0))

## [4.4.15](https://github.com/semantic-release-action/rust/compare/v4.4.14...v4.4.15) (2023-07-11)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.113 ([4e2a83a](https://github.com/semantic-release-action/rust/commit/4e2a83a43d99e7ab71d60a9ade991858bd494ca2))

## [4.4.14](https://github.com/semantic-release-action/rust/compare/v4.4.13...v4.4.14) (2023-07-10)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.112 ([4c1d5b3](https://github.com/semantic-release-action/rust/commit/4c1d5b352ef23f20aab44536aab300b6e4f9121e))

## [4.4.13](https://github.com/semantic-release-action/rust/compare/v4.4.12...v4.4.13) (2023-07-09)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.111 ([1eff347](https://github.com/semantic-release-action/rust/commit/1eff3470d74b96b8cac6171b947c80b017b3f148))

## [4.4.12](https://github.com/semantic-release-action/rust/compare/v4.4.11...v4.4.12) (2023-07-08)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.110 ([ed5ae38](https://github.com/semantic-release-action/rust/commit/ed5ae381cf6dcd5133911da7648071f34c3288a4))

## [4.4.11](https://github.com/semantic-release-action/rust/compare/v4.4.10...v4.4.11) (2023-07-07)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.109 ([3850c21](https://github.com/semantic-release-action/rust/commit/3850c218ab19b228587ff0d946577f4ef498afdf))

## [4.4.10](https://github.com/semantic-release-action/rust/compare/v4.4.9...v4.4.10) (2023-07-06)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.108 ([30368af](https://github.com/semantic-release-action/rust/commit/30368afb0691978d721044fb7b16a76e2a542f8d))

## [4.4.9](https://github.com/semantic-release-action/rust/compare/v4.4.8...v4.4.9) (2023-07-06)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.106 ([fff7c04](https://github.com/semantic-release-action/rust/commit/fff7c042b18e9778293cb133a6daa313366689ec))

## [4.4.8](https://github.com/semantic-release-action/rust/compare/v4.4.7...v4.4.8) (2023-07-05)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.7 ([053414d](https://github.com/semantic-release-action/rust/commit/053414d4a0e5928e4e71f4b67d4f21adb554d61e))

## [4.4.7](https://github.com/semantic-release-action/rust/compare/v4.4.6...v4.4.7) (2023-07-05)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.104 ([94a182e](https://github.com/semantic-release-action/rust/commit/94a182e0e6263e4829f77ccff6763beba4886a3d))

## [4.4.6](https://github.com/semantic-release-action/rust/compare/v4.4.5...v4.4.6) (2023-07-01)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.102 ([b4935f7](https://github.com/semantic-release-action/rust/commit/b4935f7bfd60c1b360cd4292e725caa56a85ad76))
* **deps:** update dependency semantic-release to v21.0.6 ([955691e](https://github.com/semantic-release-action/rust/commit/955691e6a05b3f1c01824b2a13dba15b9d22c5bc))

## [4.4.5](https://github.com/semantic-release-action/rust/compare/v4.4.4...v4.4.5) (2023-07-01)


### Bug Fixes

* do not pass --locked to cargo commands for library crates ([26e1542](https://github.com/semantic-release-action/rust/commit/26e15424a71201e51ae22f79796f8d1cdd44665b))

## [4.4.4](https://github.com/semantic-release-action/rust/compare/v4.4.3...v4.4.4) (2023-06-03)


### Bug Fixes

* **deps:** update dependency semantic-release-major-tag to v0.3.2 ([2bfd934](https://github.com/semantic-release-action/rust/commit/2bfd9340bb6b1e488afd5e36aaae783b67199dc4))

## [4.4.3](https://github.com/semantic-release-action/rust/compare/v4.4.2...v4.4.3) (2023-05-13)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.78 ([1336db0](https://github.com/semantic-release-action/rust/commit/1336db0be256f1d51bbc5221c310feea08691937))

## [4.4.2](https://github.com/semantic-release-action/rust/compare/v4.4.1...v4.4.2) (2023-05-13)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.2 ([34c8a71](https://github.com/semantic-release-action/rust/commit/34c8a71c5810c59c7d9d41c9382a15969f184c09))

## [4.4.1](https://github.com/semantic-release-action/rust/compare/v4.4.0...v4.4.1) (2023-05-13)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.70 ([3feaf92](https://github.com/semantic-release-action/rust/commit/3feaf92b1e052414512368e35f963be749139d0d))

# [4.4.0](https://github.com/semantic-release-action/rust/compare/v4.3.4...v4.4.0) (2023-05-13)


### Features

* support `disable-semantic-release-cargo` in library release workflow ([a2ad523](https://github.com/semantic-release-action/rust/commit/a2ad523058c87a76ecbcfce74968647f44bd4acc))

## [4.3.4](https://github.com/semantic-release-action/rust/compare/v4.3.3...v4.3.4) (2023-05-03)


### Bug Fixes

* use more accurate step names ([c75e23c](https://github.com/semantic-release-action/rust/commit/c75e23c3554eff200160ab29f3249dac5ebe602c))

## [4.3.3](https://github.com/semantic-release-action/rust/compare/v4.3.2...v4.3.3) (2023-05-03)


### Bug Fixes

* use inputs.toolchain instead of hardcoded value ([be4a183](https://github.com/semantic-release-action/rust/commit/be4a18397dcb8894de07aa8e066e382074ef105f))

## [4.3.2](https://github.com/semantic-release-action/rust/compare/v4.3.1...v4.3.2) (2023-05-02)


### Bug Fixes

* add step name describing what's being performed ([ae4119b](https://github.com/semantic-release-action/rust/commit/ae4119be152b795e641543920be408a85c1ca353))

## [4.3.1](https://github.com/semantic-release-action/rust/compare/v4.3.0...v4.3.1) (2023-04-22)


### Bug Fixes

* do not use cargo --locked in library release workflow ([edccf72](https://github.com/semantic-release-action/rust/commit/edccf723b30faa0182063140e97b0e5d79fc84d4))

# [4.3.0](https://github.com/semantic-release-action/rust/compare/v4.2.15...v4.3.0) (2023-04-19)


### Features

* add support for checking out submodules ([836593b](https://github.com/semantic-release-action/rust/commit/836593bc081200f03c6528510074e55ee7a91545))

## [4.2.15](https://github.com/semantic-release-action/rust/compare/v4.2.14...v4.2.15) (2023-04-12)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.1 ([a132eaa](https://github.com/semantic-release-action/rust/commit/a132eaa6b2bd1dfff4faf5f169923d97e1402f89))

## [4.2.14](https://github.com/semantic-release-action/rust/compare/v4.2.13...v4.2.14) (2023-04-11)


### Bug Fixes

* use consistent ordering of arguments ([b359012](https://github.com/semantic-release-action/rust/commit/b3590129a538ce15353688c6b5195a878c776648))

## [4.2.13](https://github.com/semantic-release-action/rust/compare/v4.2.12...v4.2.13) (2023-04-10)


### Bug Fixes

* specify arguments in consistent order ([fe01a44](https://github.com/semantic-release-action/rust/commit/fe01a44284235ea7ceeca9eae4e2fc83d2d0b3d1))

## [4.2.12](https://github.com/semantic-release-action/rust/compare/v4.2.11...v4.2.12) (2023-03-31)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.61 ([d81e7c5](https://github.com/semantic-release-action/rust/commit/d81e7c5e36395fc5291493b9ab24fa1163fc03ff))

## [4.2.11](https://github.com/semantic-release-action/rust/compare/v4.2.10...v4.2.11) (2023-03-26)


### Bug Fixes

* remove redundant words from step name ([407493b](https://github.com/semantic-release-action/rust/commit/407493bc77e52e5b63d81a8fb80aa4eb0d31c466))

## [4.2.10](https://github.com/semantic-release-action/rust/compare/v4.2.9...v4.2.10) (2023-03-25)


### Bug Fixes

* **deps:** update dependency @semantic-release/changelog to v6.0.3 ([0b62cb6](https://github.com/semantic-release-action/rust/commit/0b62cb65f167f0051ffb847c4776cfd569b0a948))

## [4.2.9](https://github.com/semantic-release-action/rust/compare/v4.2.8...v4.2.9) (2023-03-25)


### Bug Fixes

* rename job from Cargo test to Test ([ece2e34](https://github.com/semantic-release-action/rust/commit/ece2e3425676199247767984965aa443a188c766))

## [4.2.8](https://github.com/semantic-release-action/rust/compare/v4.2.7...v4.2.8) (2023-03-25)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.57 ([f852ab6](https://github.com/semantic-release-action/rust/commit/f852ab69ef44229d9a3465caaba58c5f0c7b931a))

## [4.2.7](https://github.com/semantic-release-action/rust/compare/v4.2.6...v4.2.7) (2023-03-25)


### Bug Fixes

* **deps:** update dependency semantic-release to v21 ([0c1fb4b](https://github.com/semantic-release-action/rust/commit/0c1fb4b5de6fddd8db68cbb56eeaa5c80daf5ca4))

## [4.2.6](https://github.com/semantic-release-action/rust/compare/v4.2.5...v4.2.6) (2023-03-18)


### Bug Fixes

* **deps:** update dependency semantic-release to v20.1.3 ([743250a](https://github.com/semantic-release-action/rust/commit/743250a3fe8cca97a7826bad0dd1f18906a8191b))

## [4.2.5](https://github.com/semantic-release-action/rust/compare/v4.2.4...v4.2.5) (2023-03-12)


### Bug Fixes

* use Swatinem/rust-cache for caching ([21dbb34](https://github.com/semantic-release-action/rust/commit/21dbb34872fc7516ad90aba6bd276651bbe80ccd))

## [4.2.4](https://github.com/semantic-release-action/rust/compare/v4.2.3...v4.2.4) (2023-03-12)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.38 ([81b1bbe](https://github.com/semantic-release-action/rust/commit/81b1bbe9bdff2516b269cead02a079f064c9cc75))

## [4.2.3](https://github.com/semantic-release-action/rust/compare/v4.2.2...v4.2.3) (2023-03-12)


### Bug Fixes

* use proper order of arguments ([cd5db2d](https://github.com/semantic-release-action/rust/commit/cd5db2db66e3bcbff980478b7c2ddbc2e6612f81))

## [4.2.2](https://github.com/semantic-release-action/rust/compare/v4.2.1...v4.2.2) (2023-03-12)


### Bug Fixes

* do not apply `--locked` if user has not specified it ([006cd6f](https://github.com/semantic-release-action/rust/commit/006cd6fecb3f2582e4803ca353979e0f8a3612a4))

## [4.2.1](https://github.com/semantic-release-action/rust/compare/v4.2.0...v4.2.1) (2023-03-12)


### Bug Fixes

* split compilation and testing in fewer cases ([616db04](https://github.com/semantic-release-action/rust/commit/616db049f5b42f19332d5d7cc67b14f304231d2a))

# [4.2.0](https://github.com/semantic-release-action/rust/compare/v4.1.10...v4.2.0) (2023-03-12)


### Bug Fixes

* pass `--locked` to `cargo test` ([b0e45ce](https://github.com/semantic-release-action/rust/commit/b0e45ced75c975f68e0687243cde6555d573a4c4))
* pass `--nocapture` to `cargo test` ([02ce796](https://github.com/semantic-release-action/rust/commit/02ce7967a165704bef0cae3744213f65d2c9e123))


### Features

* separate compilation and testing ([714425e](https://github.com/semantic-release-action/rust/commit/714425e3dcbc53a373c3b4111c4a9558f353535f))

## [4.1.10](https://github.com/semantic-release-action/rust/compare/v4.1.9...v4.1.10) (2023-03-09)


### Bug Fixes

* use clearer step name ([ee73f0b](https://github.com/semantic-release-action/rust/commit/ee73f0b9792951892887743fe667c78c5849f58a))

## [4.1.9](https://github.com/semantic-release-action/rust/compare/v4.1.8...v4.1.9) (2023-03-06)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.33 ([e24a6b1](https://github.com/semantic-release-action/rust/commit/e24a6b1b85ddae36f05456e15e1c6efe81d6ddb2))

## [4.1.8](https://github.com/semantic-release-action/rust/compare/v4.1.7...v4.1.8) (2023-03-04)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.32 ([49a33b7](https://github.com/semantic-release-action/rust/commit/49a33b7155442319b5e83b0d7f7630d937ebc9c7))

## [4.1.7](https://github.com/semantic-release-action/rust/compare/v4.1.6...v4.1.7) (2023-03-02)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.31 ([1001c0c](https://github.com/semantic-release-action/rust/commit/1001c0c5594ea151acf44fa852c856e4d09f1eca))

## [4.1.6](https://github.com/semantic-release-action/rust/compare/v4.1.5...v4.1.6) (2023-03-02)


### Bug Fixes

* **deps:** update dependency semantic-release to v20.1.1 ([159cdda](https://github.com/semantic-release-action/rust/commit/159cddab748528f9b05e7a81390855ae6b696568))

## [4.1.5](https://github.com/semantic-release-action/rust/compare/v4.1.4...v4.1.5) (2023-03-02)


### Bug Fixes

* **deps:** update dependency semantic-release-major-tag to v0.3.0 ([fe88763](https://github.com/semantic-release-action/rust/commit/fe88763ba79687da46e64b05576550aec010c78d))

## [4.1.4](https://github.com/semantic-release-action/rust/compare/v4.1.3...v4.1.4) (2023-03-01)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.30 ([3947fc6](https://github.com/semantic-release-action/rust/commit/3947fc6aae910d4b9fd2621624db2ebe88aaab86))

## [4.1.3](https://github.com/semantic-release-action/rust/compare/v4.1.2...v4.1.3) (2023-02-13)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.25 ([f1da2db](https://github.com/semantic-release-action/rust/commit/f1da2db183a3f810478ec7ec101fe363ca1c0dbb))

## [4.1.2](https://github.com/semantic-release-action/rust/compare/v4.1.1...v4.1.2) (2023-02-12)


### Bug Fixes

* **deps:** upgrade semantic-release-action/next-release-version to v3 ([ecbb58a](https://github.com/semantic-release-action/rust/commit/ecbb58a6a23a96b92f8fee28e16eb710dc409ad4))

## [4.1.1](https://github.com/semantic-release-action/rust/compare/v4.1.0...v4.1.1) (2023-02-07)


### Bug Fixes

* do not require cargo-registry-token to be specified ([097ccad](https://github.com/semantic-release-action/rust/commit/097ccad6921d2661a7c92520976f709572740d4d))

# [4.1.0](https://github.com/semantic-release-action/rust/compare/v4.0.14...v4.1.0) (2023-02-05)


### Bug Fixes

* add debug logs ([eda9b91](https://github.com/semantic-release-action/rust/commit/eda9b919026b88ea7685d4265d26ea47da0bdd43))
* skip matrix configuration when possible ([19455f2](https://github.com/semantic-release-action/rust/commit/19455f2cb6e6ee15b183604b9f36255ba6be5667))
* use correct variable name ([c1d8895](https://github.com/semantic-release-action/rust/commit/c1d889505c8fdb541cf3553d2403382fed9ddc45))
* use single line string in step output ([ee65603](https://github.com/semantic-release-action/rust/commit/ee6560395c59b22aa8153147bf2b67d11e519644))


### Features

* **release-binary:** support whitelist of compilation targets ([fb84a2f](https://github.com/semantic-release-action/rust/commit/fb84a2fa1d05fbf663cb5266f90eddd9427f110f)), closes [#15](https://github.com/semantic-release-action/rust/issues/15)

# [4.1.0-beta.5](https://github.com/semantic-release-action/rust/compare/v4.1.0-beta.4...v4.1.0-beta.5) (2023-02-05)


### Bug Fixes

* skip matrix configuration when possible ([19455f2](https://github.com/semantic-release-action/rust/commit/19455f2cb6e6ee15b183604b9f36255ba6be5667))

# [4.1.0-beta.4](https://github.com/semantic-release-action/rust/compare/v4.1.0-beta.3...v4.1.0-beta.4) (2023-02-05)


### Bug Fixes

* use single line string in step output ([ee65603](https://github.com/semantic-release-action/rust/commit/ee6560395c59b22aa8153147bf2b67d11e519644))

# [4.1.0-beta.3](https://github.com/semantic-release-action/rust/compare/v4.1.0-beta.2...v4.1.0-beta.3) (2023-02-05)


### Bug Fixes

* use correct variable name ([c1d8895](https://github.com/semantic-release-action/rust/commit/c1d889505c8fdb541cf3553d2403382fed9ddc45))

# [4.1.0-beta.2](https://github.com/semantic-release-action/rust/compare/v4.1.0-beta.1...v4.1.0-beta.2) (2023-02-05)


### Bug Fixes

* add debug logs ([eda9b91](https://github.com/semantic-release-action/rust/commit/eda9b919026b88ea7685d4265d26ea47da0bdd43))

# [4.1.0-beta.1](https://github.com/semantic-release-action/rust/compare/v4.0.14...v4.1.0-beta.1) (2023-02-05)


### Features

* **release-binary:** support whitelist of compilation targets ([fb84a2f](https://github.com/semantic-release-action/rust/commit/fb84a2fa1d05fbf663cb5266f90eddd9427f110f)), closes [#15](https://github.com/semantic-release-action/rust/issues/15)

## [4.0.14](https://github.com/semantic-release-action/rust/compare/v4.0.13...v4.0.14) (2023-02-04)


### Bug Fixes

* correctly select binary name from crates with a binary and library ([14e1af1](https://github.com/semantic-release-action/rust/commit/14e1af1da2ebf12b01c4a712f1f1df650cbfba92))

## [4.0.13](https://github.com/semantic-release-action/rust/compare/v4.0.12...v4.0.13) (2023-01-26)


### Bug Fixes

* **deps:** update dependency @semantic-release-cargo/semantic-release-cargo to v2.1.8 ([82335ef](https://github.com/semantic-release-action/rust/commit/82335ef72b8d0825487ba109d06721cd3dbaebe0))
* **deps:** update dependency semantic-release to v20.1.0 ([b373808](https://github.com/semantic-release-action/rust/commit/b373808f9063df100deb94abbda2607a69daab67))

## [4.0.12](https://github.com/semantic-release-action/rust/compare/v4.0.11...v4.0.12) (2023-01-23)


### Bug Fixes

* fix glob ([eaaa792](https://github.com/semantic-release-action/rust/commit/eaaa792d20c3b6cf4d5f7e32e6c269fea4261863))

## [4.0.11](https://github.com/semantic-release-action/rust/compare/v4.0.10...v4.0.11) (2023-01-23)


### Bug Fixes

* do not publish cross-compiled release binaries to cargo registry ([ac98cca](https://github.com/semantic-release-action/rust/commit/ac98cca4169954fa5e1cbd61a668393e42f53360))
* list the files cargo is publishing to cargo registry ([0ba7c0b](https://github.com/semantic-release-action/rust/commit/0ba7c0b8702937e420507c5b11e37acb20e85af7))

## [4.0.10](https://github.com/semantic-release-action/rust/compare/v4.0.9...v4.0.10) (2023-01-16)


### Bug Fixes

* correct typo in expression ([065803f](https://github.com/semantic-release-action/rust/commit/065803f80d50693eb0b20ebe41aa42eb62d78b51))

## [4.0.9](https://github.com/semantic-release-action/rust/compare/v4.0.8...v4.0.9) (2023-01-16)


### Bug Fixes

* thread inputs properly ([ebca30f](https://github.com/semantic-release-action/rust/commit/ebca30f53331883638f227735e52e9880cf9edc4))

## [4.0.8](https://github.com/semantic-release-action/rust/compare/v4.0.7...v4.0.8) (2023-01-16)


### Bug Fixes

* correct action syntax ([2e4be3f](https://github.com/semantic-release-action/rust/commit/2e4be3ffca0982c6e7868b7cb7f624ddb5bd41ef))

## [4.0.7](https://github.com/semantic-release-action/rust/compare/v4.0.6...v4.0.7) (2023-01-16)


### Bug Fixes

* always bump version in cargo manifest ([9bf5005](https://github.com/semantic-release-action/rust/commit/9bf500589e7f333aa4ccda6c8a61ece5617013b7)), closes [#9](https://github.com/semantic-release-action/rust/issues/9)

## [4.0.6](https://github.com/semantic-release-action/rust/compare/v4.0.5...v4.0.6) (2023-01-16)


### Bug Fixes

* treat inputs as strings ([b634610](https://github.com/semantic-release-action/rust/commit/b6346101718a104e5ebe42a02d126b8f8abecece))

## [4.0.5](https://github.com/semantic-release-action/rust/compare/v4.0.4...v4.0.5) (2023-01-16)


### Bug Fixes

* **deps:** update self-reference to latest ([fae17a1](https://github.com/semantic-release-action/rust/commit/fae17a125cac8270c781f6695594a6f3da7efa97))

## [4.0.4](https://github.com/semantic-release-action/rust/compare/v4.0.3...v4.0.4) (2023-01-16)


### Bug Fixes

* share data between steps correctly ([c8eaeb6](https://github.com/semantic-release-action/rust/commit/c8eaeb678a1ec0f622a55677be84cc5c0d7741fb))

## [4.0.3](https://github.com/semantic-release-action/rust/compare/v4.0.2...v4.0.3) (2023-01-16)


### Bug Fixes

* share output properly between jobs ([dbbf6d4](https://github.com/semantic-release-action/rust/commit/dbbf6d45a5d4e83b291d3cdac5d4b4ceeb143691))

## [4.0.2](https://github.com/semantic-release-action/rust/compare/v4.0.1...v4.0.2) (2023-01-16)


### Bug Fixes

* update action invocation ([52d7def](https://github.com/semantic-release-action/rust/commit/52d7def9a277610363cc1679d8e110097f63c539))

## [4.0.1](https://github.com/semantic-release-action/rust/compare/v4.0.0...v4.0.1) (2023-01-16)


### Bug Fixes

* use next-release-version v2 ([2c442d2](https://github.com/semantic-release-action/rust/commit/2c442d211773d7c711c5a0b7bc912b04f3807468))

# [4.0.0](https://github.com/semantic-release-action/rust/compare/v3.1.1...v4.0.0) (2023-01-16)


* fix!: opt out of flags by default ([4a8f145](https://github.com/semantic-release-action/rust/commit/4a8f1450e4d809e55d70ad6a68dce9b904d4990d))


### BREAKING CHANGES

* negate runtime flags to control semantic-release

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
