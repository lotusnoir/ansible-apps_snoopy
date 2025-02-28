# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.0](https://github.com/lotusnoir/ansible-apps_snoopy/compare/2.0.0...2.1.0) - 2025-01-16

### Commits

- add support for ubuntu24 [`0bec4eb`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/0bec4eba0cc4eb07a3c346a3ec33e3939f62bb71)
- add version on molecule play image to maintain support on old release [`87f5d20`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/87f5d207ec3a991328c67e3d12f8e0b5799a23cc)
- remove support for debian10 / ubuntu18 / redhat8 [`5c17108`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/5c17108e7e7be489a9b311f56e30d0c95e1039d5)
- update molecule [`5a9d103`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/5a9d103a4f24dd75c776542f3ef58505e62fff1f)
- add redhat 9 to default supported distrib [`dedea6c`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/dedea6cea9a2c648d046b102d0e36208880dc1db)
- add redhat 8 to default supported distrib [`3f942cf`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/3f942cf75cefbbdf159ed8e063b13ecd0ab8aaa0)
- sort testing distrib to avoid random changes [`6209e84`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/6209e8407cf5a0fc8cf0ce5a8ac54d69bc222ca3)
- update pre-commit and lint fix [`c511011`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/c511011086ce6e3259340054b6c1b7e46834edb5)
- remove duplicate signing key tasks [`01ee4ac`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/01ee4ac27353a3a919a37f4ce9cada432b8a73a7)
- remove support for rhel7 and docker dind on gitlab [`6d7f603`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/6d7f603d6c4de8ef4947b3bd1b48b773e83f7227)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_snoopy/compare/1.1.0...2.0.0) - 2023-09-27

### Commits

- remove install script in order to be able to select version and clean [`9d0c1cb`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/9d0c1cb1d9862de8fd86191983c06a4a20b906a3)
- update vars [`2719e56`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/2719e5685a212a4710602ac4017aef60a1a0a1ef)
- fix path vars for rhel7 [`170ad88`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/170ad881fa4c1b417058ba339637e95f8eb0e0ae)
- fix debian12 support [`ba77718`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/ba77718adc0779740addb8f17fdd531d7b575cf0)

## [1.1.0](https://github.com/lotusnoir/ansible-apps_snoopy/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`404a1d0`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/404a1d0b6d8765634dd667149253719b9e8b226e)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_snoopy/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`5306b47`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/5306b47429bd5f6ec38d38f03d4a2f42320a7655)
- add precommit for lint [`90d0ece`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/90d0ece3e0712bab99462bcf293e0c399ab2c305)
- fix checks [`0da0f11`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/0da0f113bd1b98e06db359b87aac4ef95a5535ff)
- add new molecule all scenario [`1888105`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/188810553b7a9a2da1315f31d2630eb927835030)
- split distro for molecule tests on ci [`975f215`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/975f2155bc185c0c9cb81f89d538aa269b1cf324)
- update checks and Readme [`6890ddf`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/6890ddf5e7e77e6f73275efbcc9e1eae71623e56)
- fix molecule ora9 [`fde7fd5`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/fde7fd53b36a64ae3726d945a60c980626af5c04)
- add vars + remove compile pkgs [`776dd9f`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/776dd9fb5cc5f18264c0189b5c3b0e9645f1a419)
- fix checks [`aa97564`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/aa97564789fe28fcc5d12a1367a2f07c03f15bb6)
- add compatibility v2.5.0 [`46ad156`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/46ad15685f3f2fc7f509883e670acbca8a89c2e3)

## [0.3.0](https://github.com/lotusnoir/ansible-apps_snoopy/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`46122df`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/46122dfe7eec47ae987916aa1c25edb59f7a9d61)
- minor: add oracleLinux support + little fixes [`ad28e3f`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/ad28e3f2713a1147da4982cb999a2f3ec37bbfd1)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_snoopy/compare/0.1.0...0.2.0) - 2022-06-01

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`6ca4326`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/6ca43265a804a33e2db17b5351ba2640d3c040df)
- fix: remove unsupported centos8 + minor fixes [`4addfa6`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/4addfa625a8377d7d17dd8d3b65f6bf8aa6ee199)

## 0.1.0 - 2021-11-18

### Commits

- fix: add role name on molecule container names to avoid concurrent conflict on runners [`55c897d`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/55c897d37315a7c8eb0b3b2f09010cff8fc332e1)
- minor: add changelog + automatic files checks [`01eb474`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/01eb474506cc1af9c9a3801d8bd387996fc3f9b2)
- initial commit [`ce74a90`](https://github.com/lotusnoir/ansible-apps_snoopy/commit/ce74a906197be0c6af71e563fd502950262e2e41)
