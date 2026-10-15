## [1.0.3](https://github.com/Normaltic/ci-lab/compare/v1.0.2...v1.0.3) (2026-10-15)

### Bug Fixes

* recheck cancel R1 ([2fc6ccf](https://github.com/Normaltic/ci-lab/commit/2fc6ccf6382c622bf3d41e3ed725ee0cd95330af))
* recheck cancel R2 ([1c81b02](https://github.com/Normaltic/ci-lab/commit/1c81b0228afc48fa43d6054475aab513b439a8c9))
* T1 deploy failure notifies once ([6777b1c](https://github.com/Normaltic/ci-lab/commit/6777b1c6a2ab1267782adedb16ac718fea26211b))
* T1 deploy failure notifies once (retry) ([08dac1d](https://github.com/Normaltic/ci-lab/commit/08dac1d722c7a4be01913cc1971932c2a36bdc4b))
* T2 side-trigger failure does not notify ([f7b4cfe](https://github.com/Normaltic/ci-lab/commit/f7b4cfe6ef5d578a6bfd3ffc3e27f3d414d451e4))

### CI

* T1 notify scope back to deploy chain, skip stage lock on release commits ([4dab7e1](https://github.com/Normaltic/ci-lab/commit/4dab7e1ec7a6e678cbc8de1ffb1b470b4321a925))

## [1.0.3-rc.2](https://github.com/Normaltic/ci-lab/compare/v1.0.3-rc.1...v1.0.3-rc.2) (2026-10-15)

### Bug Fixes

* T2 side-trigger failure does not notify ([f7b4cfe](https://github.com/Normaltic/ci-lab/commit/f7b4cfe6ef5d578a6bfd3ffc3e27f3d414d451e4))

## [1.0.3-rc.1](https://github.com/Normaltic/ci-lab/compare/v1.0.2...v1.0.3-rc.1) (2026-10-15)

### Bug Fixes

* recheck cancel R1 ([2fc6ccf](https://github.com/Normaltic/ci-lab/commit/2fc6ccf6382c622bf3d41e3ed725ee0cd95330af))
* recheck cancel R2 ([1c81b02](https://github.com/Normaltic/ci-lab/commit/1c81b0228afc48fa43d6054475aab513b439a8c9))
* T1 deploy failure notifies once ([6777b1c](https://github.com/Normaltic/ci-lab/commit/6777b1c6a2ab1267782adedb16ac718fea26211b))
* T1 deploy failure notifies once (retry) ([08dac1d](https://github.com/Normaltic/ci-lab/commit/08dac1d722c7a4be01913cc1971932c2a36bdc4b))

### CI

* T1 notify scope back to deploy chain, skip stage lock on release commits ([4dab7e1](https://github.com/Normaltic/ci-lab/commit/4dab7e1ec7a6e678cbc8de1ffb1b470b4321a925))

## [1.0.2](https://github.com/Normaltic/ci-lab/compare/v1.0.1...v1.0.2) (2026-10-06)

### Bug Fixes

* deploy failure check ([22abc9e](https://github.com/Normaltic/ci-lab/commit/22abc9e88b9b569fce96d7c445d040ad27b3bde6))
* main verify failure (fallback unlock check) ([8d994f5](https://github.com/Normaltic/ci-lab/commit/8d994f544cf16d068bfb15a1a28d43a08f2cfd54))

## [1.0.1](https://github.com/Normaltic/ci-lab/compare/v1.0.0...v1.0.1) (2026-10-06)

### CI

* fix yaml scalar in artifact check ([1e3c32f](https://github.com/Normaltic/ci-lab/commit/1e3c32fac0fa42498125f94b4e6d0de2a126f7a9))
* unlock stage right after release, verify artifact and OIDC claims ([14d5249](https://github.com/Normaltic/ci-lab/commit/14d5249aac274bc88ffdd30e8ed9c73cd025b0fd))

## [1.0.1-rc.1](https://github.com/Normaltic/ci-lab/compare/v1.0.0...v1.0.1-rc.1) (2026-10-06)

### CI

* fix yaml scalar in artifact check ([1e3c32f](https://github.com/Normaltic/ci-lab/commit/1e3c32fac0fa42498125f94b4e6d0de2a126f7a9))
* unlock stage right after release, verify artifact and OIDC claims ([14d5249](https://github.com/Normaltic/ci-lab/commit/14d5249aac274bc88ffdd30e8ed9c73cd025b0fd))

## 1.0.0 (2026-10-05)

### Bug Fixes

* baseline A ([5fb7377](https://github.com/Normaltic/ci-lab/commit/5fb737776cc650de728037821a4efcbdf174bc45))
* baseline B ([9d99ba2](https://github.com/Normaltic/ci-lab/commit/9d99ba22b13b41917f080a6da3728d87d581e66d))
* scenario1 C ([cd24d4b](https://github.com/Normaltic/ci-lab/commit/cd24d4b9a47026123a0e65d69c4e44a36aa6565a))
* scenario2 E ([b8366ee](https://github.com/Normaltic/ci-lab/commit/b8366eeaf9fb9c2c7e8460755d9b07c94429db2f))
* scenario3 F ([891b315](https://github.com/Normaltic/ci-lab/commit/891b315b81a85b2aa37463e6c9631fe6307f48b2))
* scenario4 G (verify fails) ([1131dc8](https://github.com/Normaltic/ci-lab/commit/1131dc8782424f9a2710ca2f96b98556b1e746c9))

### CI

* hello diagnosis ([a582df0](https://github.com/Normaltic/ci-lab/commit/a582df074964b474bca77e665e9f85579ad0272b))
* make deploy stub duration configurable (scenario2 D) ([7eb003b](https://github.com/Normaltic/ci-lab/commit/7eb003bca51d78821ea161b7a32bfefb294343f4))
* split release into verify/publish with separate concurrency ([e90ae7f](https://github.com/Normaltic/ci-lab/commit/e90ae7fd175d4c01dfd8681f753df0cb04221442))

## [1.0.0-rc.4](https://github.com/Normaltic/ci-lab/compare/v1.0.0-rc.3...v1.0.0-rc.4) (2026-10-05)

### Bug Fixes

* scenario2 E ([b8366ee](https://github.com/Normaltic/ci-lab/commit/b8366eeaf9fb9c2c7e8460755d9b07c94429db2f))
* scenario3 F ([891b315](https://github.com/Normaltic/ci-lab/commit/891b315b81a85b2aa37463e6c9631fe6307f48b2))

## [1.0.0-rc.3](https://github.com/Normaltic/ci-lab/compare/v1.0.0-rc.2...v1.0.0-rc.3) (2026-10-05)

### CI

* make deploy stub duration configurable (scenario2 D) ([7eb003b](https://github.com/Normaltic/ci-lab/commit/7eb003bca51d78821ea161b7a32bfefb294343f4))

## [1.0.0-rc.2](https://github.com/Normaltic/ci-lab/compare/v1.0.0-rc.1...v1.0.0-rc.2) (2026-10-05)

### Bug Fixes

* scenario1 C ([cd24d4b](https://github.com/Normaltic/ci-lab/commit/cd24d4b9a47026123a0e65d69c4e44a36aa6565a))

### CI

* split release into verify/publish with separate concurrency ([e90ae7f](https://github.com/Normaltic/ci-lab/commit/e90ae7fd175d4c01dfd8681f753df0cb04221442))

## 1.0.0-rc.1 (2026-10-05)

### Bug Fixes

* baseline A ([5fb7377](https://github.com/Normaltic/ci-lab/commit/5fb737776cc650de728037821a4efcbdf174bc45))
* baseline B ([9d99ba2](https://github.com/Normaltic/ci-lab/commit/9d99ba22b13b41917f080a6da3728d87d581e66d))

### CI

* hello diagnosis ([a582df0](https://github.com/Normaltic/ci-lab/commit/a582df074964b474bca77e665e9f85579ad0272b))
