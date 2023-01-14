# Changelog

## [11.0.0](https://github.com/chgl/recruit-release-test/compare/v10.0.1...v11.0.0) (2023-01-14)


### ⚠ BREAKING CHANGES

* moved source code to monorepo (#34)
* updated docker-compose deployment (#7)
* updated docker-compose deployment

### Features

* added traefik to docker compose deployment ([#3](https://github.com/chgl/recruit-release-test/issues/3)) ([b4855fe](https://github.com/chgl/recruit-release-test/commit/b4855fe76800ea03fa8551c3fb31e4d12960f3c6))
* moved source code to monorepo ([#34](https://github.com/chgl/recruit-release-test/issues/34)) ([6005389](https://github.com/chgl/recruit-release-test/commit/6005389ead1129a22acb7dc8d69c11fdf838e8e8))
* pin container image digest in compose ([#5](https://github.com/chgl/recruit-release-test/issues/5)) ([02f966c](https://github.com/chgl/recruit-release-test/commit/02f966c6e157d4f2cf339a4ebfa3cdab9d2bf6b5))
* run using read-only root fs in compose by default ([c33ab33](https://github.com/chgl/recruit-release-test/commit/c33ab3325aaee4b38793515437be027295488461))
* updated docker-compose deployment ([0882970](https://github.com/chgl/recruit-release-test/commit/088297033a9b412c0f8d6770f6ea17360d042432))
* updated docker-compose deployment ([#7](https://github.com/chgl/recruit-release-test/issues/7)) ([0d62fa8](https://github.com/chgl/recruit-release-test/commit/0d62fa810225890a21c40c027d5b8014580d1388))


### Bug Fixes

* added mem limits to all staging containers ([086ceb0](https://github.com/chgl/recruit-release-test/commit/086ceb07903932ff0f00a47cb4b9e2585212cda5))
* config prefix for fhir server validation setting ([c2af51f](https://github.com/chgl/recruit-release-test/commit/c2af51f0a16c1cc125eda4d2795ccdaf7fbce06f))
* **docker-compose:** keycloak to work when accessed as host.docker.internal ([#12](https://github.com/chgl/recruit-release-test/issues/12)) ([87e2798](https://github.com/chgl/recruit-release-test/commit/87e2798cc7a3605763588ccbf210930b3e5722da))
* rm unused PGHOST env var ([c985c4a](https://github.com/chgl/recruit-release-test/commit/c985c4adcc5a5c3e0436a92057724f3cc46b257b))


### Documentation

* added config for k8s distributed tracing deployment ([#33](https://github.com/chgl/recruit-release-test/issues/33)) ([9b98398](https://github.com/chgl/recruit-release-test/commit/9b98398c18dac2c4f389d44720d68bdc99e80963))
* added info on istio integration ([a84b1c1](https://github.com/chgl/recruit-release-test/commit/a84b1c14cd05c6cdffa7317c6c229bbbb0ca6977))
* added logo to be used for helm chart ([25f6a41](https://github.com/chgl/recruit-release-test/commit/25f6a41d87ff33b477914a99599c305808ac70c6))
* added note on FHIR subscription requirements ([7cad4dc](https://github.com/chgl/recruit-release-test/commit/7cad4dcd02bc037c573ab418d104e2b9ea8aa84a))
* added section on resource requirements ([02460f6](https://github.com/chgl/recruit-release-test/commit/02460f641ab40e8facf4d010bbc61567ed049ed5))
* added wip FHIR IG ([#4](https://github.com/chgl/recruit-release-test/issues/4)) ([e58aeaa](https://github.com/chgl/recruit-release-test/commit/e58aeaa5ec906ad3f122a0ceabd316620d22a715))
* cleared up standalone installation ([6a03f29](https://github.com/chgl/recruit-release-test/commit/6a03f297ceaa12bfeedf53a41cc25e87cf16120d))
* completed site metadata ([#6](https://github.com/chgl/recruit-release-test/issues/6)) ([818c3d2](https://github.com/chgl/recruit-release-test/commit/818c3d29707410ceedd734ada6e29529c32ec574))
* described de-pseudonymization and cnpg-based ha pg cluster config ([#39](https://github.com/chgl/recruit-release-test/issues/39)) ([f1537b4](https://github.com/chgl/recruit-release-test/commit/f1537b40131993955db2fd46bbdb3b3c12e5c6c8))
* enable init job only in command not values ([#11](https://github.com/chgl/recruit-release-test/issues/11)) ([0456992](https://github.com/chgl/recruit-release-test/commit/0456992701b05eddc7105305439f97ec5b738927))
* enable scraping fhir server in sample network policy ([d3642df](https://github.com/chgl/recruit-release-test/commit/d3642df17b336ad64bdece25ca8fec0847a5b005))
* first version of the documentation ([c5fd151](https://github.com/chgl/recruit-release-test/commit/c5fd1517d2dac548eacda22c3ba2874e25d86149))
* fixed comments in sample network policies ([0d2d6fd](https://github.com/chgl/recruit-release-test/commit/0d2d6fd1781b49c3a039fdc33457e4285906cdb6))
* fixed netpol metrics port names ([44e4a1f](https://github.com/chgl/recruit-release-test/commit/44e4a1f357d7e3b5f8a43b35d013a6daebda797b))
* fixed staging default options ([3b92995](https://github.com/chgl/recruit-release-test/commit/3b929953c22b8a2620fc9a062c18a14ac3704804))
* made links bold for better visibility ([99f7a9b](https://github.com/chgl/recruit-release-test/commit/99f7a9bed68bb561aa5b9b9004cb40b9e01588b9))
* reworded based on vale suggestions ([99ff3e6](https://github.com/chgl/recruit-release-test/commit/99ff3e67376418a772e329a32bfeee50435ba86f))
* update on max secure deployment ([#24](https://github.com/chgl/recruit-release-test/issues/24)) ([a84e38f](https://github.com/chgl/recruit-release-test/commit/a84e38f640be3c62bd834418b9346b53817c1d7c))
* updated component diagram ([ae39f26](https://github.com/chgl/recruit-release-test/commit/ae39f260081f9b2d5efa0801eee4bc8d7f06568d))
* updated docker-compose section with info on downloading from releases ([9766900](https://github.com/chgl/recruit-release-test/commit/976690097ea483ea64f3013d7eb23e1f2b2fd585))
* updated k8s docs with usage of the new `ohdsi.loadCohortDefinitionsJob` ([#30](https://github.com/chgl/recruit-release-test/issues/30)) ([f68b09b](https://github.com/chgl/recruit-release-test/commit/f68b09be367ea075b62dbcb35c4d9890ba7b7d28))
* use less compression for logo ([88c83db](https://github.com/chgl/recruit-release-test/commit/88c83db0a8d86ca6288f9fac754f8649009ba69f))


### CI/CD

* added (disabled) release wf on push to master ([82eca9f](https://github.com/chgl/recruit-release-test/commit/82eca9ff1f046f0382f2d961f45267b01d349a09))
* added helm linting workflow ([#48](https://github.com/chgl/recruit-release-test/issues/48)) ([fcdd266](https://github.com/chgl/recruit-release-test/commit/fcdd266113d1f879d5c50a08d18a7a02952f5b28))
* added scorecards workflow ([#37](https://github.com/chgl/recruit-release-test/issues/37)) ([7d03c97](https://github.com/chgl/recruit-release-test/commit/7d03c976ad6ae020c79c504cd09d83982ba95672))
* added wait timeout to recruit helm install ([370dd6e](https://github.com/chgl/recruit-release-test/commit/370dd6e70b69ae9442828195fc48c5f43be90a92))
* disabled docker-compose again since the size of the omopdb causes the workflow to crash ([fc125d1](https://github.com/chgl/recruit-release-test/commit/fc125d1f67366a7db68c67a52be3f575a5a9a492))
* enable docs publishing ([#8](https://github.com/chgl/recruit-release-test/issues/8)) ([9358b49](https://github.com/chgl/recruit-release-test/commit/9358b498c3aec3b6e87c59898cddd481bd4cc4ed))
* fix attestation name ([eeeae2f](https://github.com/chgl/recruit-release-test/commit/eeeae2fd55d8671e92f40031cd1aa0e0c7ae19b0))
* fix slsa workflow ([443cc6f](https://github.com/chgl/recruit-release-test/commit/443cc6f633973460df3b5c19a4fcda83ba649151))
* fixed helm dependency update and possibly ci permissions ([#49](https://github.com/chgl/recruit-release-test/issues/49)) ([6e73191](https://github.com/chgl/recruit-release-test/commit/6e7319154eb9f4e7b0530fb9189dd9ef572ce8ac))
* named smoke test tasks ([ffcf76b](https://github.com/chgl/recruit-release-test/commit/ffcf76b26aecbe5fbcdc2b5b1762bf8fff8a87b9))
* re-enable deployment test for docker compose ([#2](https://github.com/chgl/recruit-release-test/issues/2)) ([9cdbbda](https://github.com/chgl/recruit-release-test/commit/9cdbbda74bba9695389326fe992fa3a6b28e3f45))
* updated workflow actions to latest ([27b042e](https://github.com/chgl/recruit-release-test/commit/27b042efcf8a1706290438f109b071aac1aaf838))


### Miscellaneous Chores

* added megalinter and updated arch diagram ([#22](https://github.com/chgl/recruit-release-test/issues/22)) ([b84e47e](https://github.com/chgl/recruit-release-test/commit/b84e47e72f63d4265c70a6f15b271328d7987b65))
* added pinGitHubActionDigests to renovate config ([0f02c27](https://github.com/chgl/recruit-release-test/commit/0f02c279d78063a6b29402186c6fd5cd01108d52))
* **deps:** pin slsa-framework/slsa-github-generator action to bdd89e6 ([#35](https://github.com/chgl/recruit-release-test/issues/35)) ([184b532](https://github.com/chgl/recruit-release-test/commit/184b532a72285b75b7465a12aa448f8efc6ee86e))
* **deps:** update actions/checkout digest to 755da8c ([15495a9](https://github.com/chgl/recruit-release-test/commit/15495a92b6950aa27973de2d4c1c11ed8703582b))
* **deps:** update actions/checkout digest to 93ea575 ([ee7ce31](https://github.com/chgl/recruit-release-test/commit/ee7ce318c42a76b2854411d6d48d3b75bec9cc8c))
* **deps:** update actions/setup-python action to v4.1.0 ([f7a760f](https://github.com/chgl/recruit-release-test/commit/f7a760f3fcd93397420df40f1ab254d14754ba47))
* **deps:** update actions/upload-artifact digest to 83fd05a ([79af8ff](https://github.com/chgl/recruit-release-test/commit/79af8ffee481c9ba75cb95778b31c79a426d8101))
* **deps:** update all non-major dependencies ([e4ffe59](https://github.com/chgl/recruit-release-test/commit/e4ffe595554df258e7d1b77451635ce1f5881d4e))
* **deps:** update all non-major dependencies ([78f7f15](https://github.com/chgl/recruit-release-test/commit/78f7f157a91db3d3a6eed20ef9a1ac778445a03d))
* **deps:** update all non-major dependencies ([1403082](https://github.com/chgl/recruit-release-test/commit/1403082059c3ae0b247f247b985f0e132abfd392))
* **deps:** update all non-major dependencies ([b0c2a03](https://github.com/chgl/recruit-release-test/commit/b0c2a034fd4121d14760f8c713cf821f85297ebf))
* **deps:** update all non-major dependencies ([62804ab](https://github.com/chgl/recruit-release-test/commit/62804ab711b78727a17f4dc89d43e820125836cc))
* **deps:** update all non-major dependencies ([e0fb779](https://github.com/chgl/recruit-release-test/commit/e0fb77960d366a410b9fe3097289b1aeaf9d329a))
* **deps:** update all non-major dependencies ([8d312b1](https://github.com/chgl/recruit-release-test/commit/8d312b185be3a1d8a973fedf76fc7194bf0d93c1))
* **deps:** update dependency certifi to v2022.12.7 [security] ([bd58732](https://github.com/chgl/recruit-release-test/commit/bd587322a65572b3c2ef85171804055860251c7d))
* **deps:** update dependency docker.io/library/traefik to v2.8.1 ([c2dd50d](https://github.com/chgl/recruit-release-test/commit/c2dd50da2a1b0a4b769ee99a38958b5368ce85f8))
* **deps:** update dependency ghcr.io/miracum/recruit/list to v2.15.5 ([42b300c](https://github.com/chgl/recruit-release-test/commit/42b300cd4b77ecc669b8923984757153d9d5fbd9))
* **deps:** update docker.io/library/postgres digest to 0137ad8 ([3b7b9bd](https://github.com/chgl/recruit-release-test/commit/3b7b9bd85f45bc5d0ee6934cbfb35739dd4b9ac6))
* **deps:** update docker.io/library/postgres digest to 3e2eba0 ([e762614](https://github.com/chgl/recruit-release-test/commit/e762614c69623c6018f64f226da15ac7854cfebe))
* **deps:** update docker.io/library/traefik digest to 1212133 ([a261334](https://github.com/chgl/recruit-release-test/commit/a2613344472f90742892cb468c6cb601fecb8870))
* **deps:** update docker.io/library/traefik digest to 4e52a5e ([5121974](https://github.com/chgl/recruit-release-test/commit/51219742150d3a219ec3d73acf9626c3f595e15e))
* **deps:** update docker.io/library/traefik:v2.8.1 docker digest to 29eb2d5 ([8f2f0c7](https://github.com/chgl/recruit-release-test/commit/8f2f0c713e7d84dacf306decf7857f8da460f091))
* don't pin slsa-github-generator digest ([68c270d](https://github.com/chgl/recruit-release-test/commit/68c270dfc89a574ae22f7a7aaf6ecdc45ef6628a))
* fixed list cve and disabled automerge ([#47](https://github.com/chgl/recruit-release-test/issues/47)) ([a437045](https://github.com/chgl/recruit-release-test/commit/a437045f23156fdb89701f621ab5bcea5f31625a))
* generate SBOMs images with in-toto provenance for releases ([#26](https://github.com/chgl/recruit-release-test/issues/26)) ([8333644](https://github.com/chgl/recruit-release-test/commit/8333644e74020c007dfc2ca676e648a32274bce1))
* include version tag in compose deployment bundle ([#10](https://github.com/chgl/recruit-release-test/issues/10)) ([d5ce5f8](https://github.com/chgl/recruit-release-test/commit/d5ce5f8d832ba72669ab7f280f385b77f71f4357))
* release 10.0.0 ([#45](https://github.com/chgl/recruit-release-test/issues/45)) ([c15f09c](https://github.com/chgl/recruit-release-test/commit/c15f09c09d5367fcf3433370b18b22e4a3a23e44))
* release 10.0.1 ([#50](https://github.com/chgl/recruit-release-test/issues/50)) ([f4ff570](https://github.com/chgl/recruit-release-test/commit/f4ff570a40e580daf6a86c3b9096af0ae247d6c4))
* **renovate:** correct package name for ignoring postgres ([5cc2275](https://github.com/chgl/recruit-release-test/commit/5cc227583ff2b9546314a4a7786de6e8eba43d89))
* **renovate:** correctly escaped matchPackagePatterns config ([#29](https://github.com/chgl/recruit-release-test/issues/29)) ([bb2c9d6](https://github.com/chgl/recruit-release-test/commit/bb2c9d60d3d6218e79c2c3807d4db111ca215572))
* **renovate:** update recruit packages daily, gh actions monthly, and the rest weekly ([f43a397](https://github.com/chgl/recruit-release-test/commit/f43a39788d64f64d6a677ed3a39a89b6861b05ad))
* revised recruIT k8s logo to include name ([2efe0cd](https://github.com/chgl/recruit-release-test/commit/2efe0cd58ae07e4d7743b30c7ecf8a6ee2cf33f0))
* updated compose WebAPI & ATLAS to latest ([151b70b](https://github.com/chgl/recruit-release-test/commit/151b70bf81f7526e79a12a8ae76c3be261ae4710))
* updated renovate config to use pinGitHubActionDigests ([ec920a5](https://github.com/chgl/recruit-release-test/commit/ec920a575dde5cc17216b488d253a7378fe3c1a7))

## [10.0.1](https://github.com/miracum/recruit/compare/v10.0.0...v10.0.1) (2023-01-14)


### CI/CD

* fixed helm dependency update and possibly ci permissions ([#49](https://github.com/miracum/recruit/issues/49)) ([6e73191](https://github.com/miracum/recruit/commit/6e7319154eb9f4e7b0530fb9189dd9ef572ce8ac))

## [10.0.0](https://github.com/miracum/recruit/compare/v9.16.0...v10.0.0) (2023-01-14)


### ⚠ BREAKING CHANGES

* moved source code to monorepo (#34)

### Features

* moved source code to monorepo ([#34](https://github.com/miracum/recruit/issues/34)) ([6005389](https://github.com/miracum/recruit/commit/6005389ead1129a22acb7dc8d69c11fdf838e8e8))


### Miscellaneous Chores

* **deps:** update dependency certifi to v2022.12.7 [security] ([bd58732](https://github.com/miracum/recruit/commit/bd587322a65572b3c2ef85171804055860251c7d))
* fixed list cve and disabled automerge ([#47](https://github.com/miracum/recruit/issues/47)) ([a437045](https://github.com/miracum/recruit/commit/a437045f23156fdb89701f621ab5bcea5f31625a))


### CI/CD

* added helm linting workflow ([#48](https://github.com/miracum/recruit/issues/48)) ([fcdd266](https://github.com/miracum/recruit/commit/fcdd266113d1f879d5c50a08d18a7a02952f5b28))
