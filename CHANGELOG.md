# Changelog

## [10.0.6](https://github.com/chgl/recruit-release-test/compare/v10.0.5...v10.0.6) (2023-01-06)


### CI/CD

* fix release ([d0ad6a9](https://github.com/chgl/recruit-release-test/commit/d0ad6a9729a8b86ad427b36b6329ab38229df1a7))

## [10.0.5](https://github.com/chgl/recruit-release-test/compare/v10.0.4...v10.0.5) (2023-01-06)


### CI/CD

* possibly fixed helm chart download ([55f1fb9](https://github.com/chgl/recruit-release-test/commit/55f1fb9eecad695e2df2ac34fdcf059d44fa0445))

## [10.0.4](https://github.com/chgl/recruit-release-test/compare/v10.0.3...v10.0.4) (2023-01-06)


### CI/CD

* fix k8s workflow call ([2f33272](https://github.com/chgl/recruit-release-test/commit/2f3327289a506c472ff831f6d5d4889d93fd6ae8))
* fix needs names ([c864caa](https://github.com/chgl/recruit-release-test/commit/c864caa5dfc802c89cef648a739681679649e4ba))

## [10.0.3](https://github.com/chgl/recruit-release-test/compare/v10.0.2...v10.0.3) (2023-01-06)


### Bug Fixes

* list jwt error ([f54c06d](https://github.com/chgl/recruit-release-test/commit/f54c06df8be7dd1c82221299b412769e01b01f85))


### CI/CD

* updated curl and renamed helm integration test ([30960dc](https://github.com/chgl/recruit-release-test/commit/30960dcf02b2a3b8944e036c7144382a012a93b2))

## [10.0.2](https://github.com/chgl/recruit-release-test/compare/v10.0.1...v10.0.2) (2023-01-06)


### Build

* fix container created at label to 1970-01-01T00:00:00Z ([bb8e2aa](https://github.com/chgl/recruit-release-test/commit/bb8e2aa6e551da2230ea1219ecc30ed8a1c14027))


### CI/CD

* fix compose installation test ([4298cf9](https://github.com/chgl/recruit-release-test/commit/4298cf91a0e9880f8fc2be28d1a90c223bf3312e))

## [10.0.1](https://github.com/chgl/recruit-release-test/compare/v10.0.0...v10.0.1) (2023-01-06)


### CI/CD

* run release on releases created ([078f27f](https://github.com/chgl/recruit-release-test/commit/078f27f6a507d8192664a8a2cf8a06572eb7ea6d))

## [10.0.0](https://github.com/chgl/recruit-release-test/compare/v9.16.0...v10.0.0) (2023-01-06)


### ⚠ BREAKING CHANGES

* moved application code to monorepo (#1)

### Features

* moved application code to monorepo ([#1](https://github.com/chgl/recruit-release-test/issues/1)) ([768afd3](https://github.com/chgl/recruit-release-test/commit/768afd3f5f3965b745a08180793ebfb36f83c5f3))


### CI/CD

* added chart values to release-please config ([97e97ac](https://github.com/chgl/recruit-release-test/commit/97e97acb3016bd51cb76da21e1480f1788c4ffa1))
* fix build workflow push ([cd1dc96](https://github.com/chgl/recruit-release-test/commit/cd1dc96b451a8159ce506beb0aab3dcf82e570bb))
* fix container structure test to be repo-invariant ([8ad9fe8](https://github.com/chgl/recruit-release-test/commit/8ad9fe82efb5e2e7a1a9def7c1fb1b0625146832))
* fix container test on nn-PR ([5c70ef2](https://github.com/chgl/recruit-release-test/commit/5c70ef23a8008c352259835e7a45c8273bc2a2b2))
* fix image name and pulling for container test ([dcd320e](https://github.com/chgl/recruit-release-test/commit/dcd320ec53bfd296ab501bdba696a74e890059c9))
* fix integration test image loading ([47ab525](https://github.com/chgl/recruit-release-test/commit/47ab5251c8784fd05b38cbe31a4040557fa187bd))
* fix permissions ([fab931e](https://github.com/chgl/recruit-release-test/commit/fab931e2d6803b3359004b3f79325bdf64944722))
* fix trivy vuln attestation ([7e34e0d](https://github.com/chgl/recruit-release-test/commit/7e34e0dcc0aa55c356f01401fef5ae7df14c3311))
* fix write permissions for packages ([aaa7a12](https://github.com/chgl/recruit-release-test/commit/aaa7a129ab2b70db7fd2df6923d9834cf0386bf0))
* fixed build permissions ([77727c2](https://github.com/chgl/recruit-release-test/commit/77727c20e1f5bf10ebeea2aca7f92384371cd758))
* fourth attempt fixing permissions ([1834b9a](https://github.com/chgl/recruit-release-test/commit/1834b9a67ef005933d4abd290131b3faba10b9c6))
* run gradle wrapper on master push ([18fbcce](https://github.com/chgl/recruit-release-test/commit/18fbccecfb26f293dea77b130d9d30968eba8f74))
* second attempt fixing permissions ([7c4ae0e](https://github.com/chgl/recruit-release-test/commit/7c4ae0eab6fbf6660ce4654732ef47cb00ed1261))
* third attempt at fixing permissions ([4d602d0](https://github.com/chgl/recruit-release-test/commit/4d602d007ea7a41ccd0bb04742d5e6647fe02a0b))
