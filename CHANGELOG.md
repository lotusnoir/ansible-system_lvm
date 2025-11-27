# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-system_lvm/compare/3.1.0...3.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`5988cda`](https://github.com/lotusnoir/ansible-system_lvm/commit/5988cdad2935cc595feb04c58981669e569d52f3)

## [3.1.0](https://github.com/lotusnoir/ansible-system_lvm/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`9d9f81d`](https://github.com/lotusnoir/ansible-system_lvm/commit/9d9f81d3602b1826107c3056f3da216a9831ed3b)
- add oraclelinux10 support + lint and core fixes [`5ac3460`](https://github.com/lotusnoir/ansible-system_lvm/commit/5ac3460795d5909bb3744999c8e47b4e97391008)

## [3.0.0](https://github.com/lotusnoir/ansible-system_lvm/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`a3cb570`](https://github.com/lotusnoir/ansible-system_lvm/commit/a3cb570bd1dfbda9bae509d2f33187d9bd2a2562)
- update core, molecule + gitlab-ci [`67c784d`](https://github.com/lotusnoir/ansible-system_lvm/commit/67c784d66f76d1012be936d3f80eadca6eedda18)
- fix lint [`ea63c0d`](https://github.com/lotusnoir/ansible-system_lvm/commit/ea63c0d9f7cac599578dcde1711636681c1b94e4)
- fix molecule paralelism and little updates [`095e3a5`](https://github.com/lotusnoir/ansible-system_lvm/commit/095e3a5f0339060507e27f9fcf125ae57a784ec7)
- add support for ubuntu24 [`90586c4`](https://github.com/lotusnoir/ansible-system_lvm/commit/90586c4a2994ac480e494176acbf98de7ebeaeff)
- support swap change [`179fcc5`](https://github.com/lotusnoir/ansible-system_lvm/commit/179fcc574c93d58db7e98516b0d4ca20c12100ba)
- add version on molecule play image to maintain support on old release [`d6fb04d`](https://github.com/lotusnoir/ansible-system_lvm/commit/d6fb04df16dccd010512eaa087cbfab3181a4672)
- update molecule [`1e5a4ed`](https://github.com/lotusnoir/ansible-system_lvm/commit/1e5a4edf2d418faa39777eb75764cbbbdf0c7cd7)
- add redhat 9 to default supported distrib [`c185eba`](https://github.com/lotusnoir/ansible-system_lvm/commit/c185eba569b1e3e012067c9640ed78ec165e32e2)
- add redhat 8 to default supported distrib [`990a6f6`](https://github.com/lotusnoir/ansible-system_lvm/commit/990a6f676c2f45d1e435a30cb7933515c964afb8)

## [2.0.0](https://github.com/lotusnoir/ansible-system_lvm/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`5117d9c`](https://github.com/lotusnoir/ansible-system_lvm/commit/5117d9c567089e2b5c17bab0f2cf3d26a77e9938)
- update readme + precommit + include vars [`7c6415d`](https://github.com/lotusnoir/ansible-system_lvm/commit/7c6415d1606fb537433020dd19d7009d3a302966)
- change import tasks to include in order to support facts on name [`5f03cb7`](https://github.com/lotusnoir/ansible-system_lvm/commit/5f03cb77a4d4fbe8d71bf0fc1c39b1e7a5832841)

## [1.1.0](https://github.com/lotusnoir/ansible-system_lvm/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`b55434b`](https://github.com/lotusnoir/ansible-system_lvm/commit/b55434b928b371ec24acadedd450f31ee34d4beb)

## [1.0.0](https://github.com/lotusnoir/ansible-system_lvm/compare/0.2.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`fe72914`](https://github.com/lotusnoir/ansible-system_lvm/commit/fe729142fb73f3a69406fc8fc8592ef6b6449514)
- add precommit for lint [`ec02924`](https://github.com/lotusnoir/ansible-system_lvm/commit/ec029243698f1607de74b5ebb4d248215109e17c)
- fix checks [`1171ce9`](https://github.com/lotusnoir/ansible-system_lvm/commit/1171ce91b87cb08d9a0dd4e03d6529c46479bd79)
- add retry on package install for debian [`7b4f570`](https://github.com/lotusnoir/ansible-system_lvm/commit/7b4f570694548b4f289e1822323964844760e88b)
- add new molecule all scenario [`8a7185c`](https://github.com/lotusnoir/ansible-system_lvm/commit/8a7185cfb225b4ec3662340f6364c468ed89cba8)
- split distro for molecule tests on ci [`8fc4e57`](https://github.com/lotusnoir/ansible-system_lvm/commit/8fc4e57f482f49d5134e878e968d3fe3479bffe3)
- update checks and Readme [`a09e74a`](https://github.com/lotusnoir/ansible-system_lvm/commit/a09e74a9e16c9d644caa3e84b5f5c034cdf6f916)
- add molecule fix for ora9 [`92b41ba`](https://github.com/lotusnoir/ansible-system_lvm/commit/92b41ba76a382746462fb8a9f875c94c19de552c)
- update checks [`7b86ed1`](https://github.com/lotusnoir/ansible-system_lvm/commit/7b86ed149b3a15adb5271df4c7798a1234998220)
- refork mrlesmith role with personnal tasks and lint [`445efba`](https://github.com/lotusnoir/ansible-system_lvm/commit/445efba39f4e9521605506c97dd5e93c5e92c550)

## [0.2.0](https://github.com/lotusnoir/ansible-system_lvm/compare/0.1.0...0.2.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`cdf4478`](https://github.com/lotusnoir/ansible-system_lvm/commit/cdf4478000a9f3b7acddc4ca6c73a2bab199d91e)
- minor: add oracleLinux support + little fixes [`7220c8a`](https://github.com/lotusnoir/ansible-system_lvm/commit/7220c8aa2f385a7d49e95df73c4b6b76a651b3f1)
- fix: add missing galaxy id [`f37d647`](https://github.com/lotusnoir/ansible-system_lvm/commit/f37d64762df9b64f49633f43454129cb58f8b8ef)

## 0.1.0 - 2022-06-02

### Commits

- fix: remove unsupported centos8 + minor fixes [`1f6ff4a`](https://github.com/lotusnoir/ansible-system_lvm/commit/1f6ff4a08c607b4f6a7f8b0d6ef42d70df1c0419)
- fix: add proper rescan path for rhel7 [`c571fc4`](https://github.com/lotusnoir/ansible-system_lvm/commit/c571fc478f00da2437ce60e32f512507bd4051a6)
- initial commit [`edc4739`](https://github.com/lotusnoir/ansible-system_lvm/commit/edc47398ecc6e02901792e5e5752820f51f539ed)
