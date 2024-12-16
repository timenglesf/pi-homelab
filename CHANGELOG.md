# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.4.1](https://github.com/timenglesf/pi-homelab/compare/v0.4.0...v0.4.1) (2024-12-16)


### Bug Fixes

* update yaml syntax error ([d0b9068](https://github.com/timenglesf/pi-homelab/commit/d0b906803df8cbf459067ffaa6d22c20bc054290))

## [0.4.0](https://github.com/timenglesf/pi-homelab/compare/v0.3.0...v0.4.0) (2024-12-16)


### Features

* **mb-intake:** add cloudflare integration ([00adf23](https://github.com/timenglesf/pi-homelab/commit/00adf2311c0385a88dd7c8e0d83c5b899294832c))


### Bug Fixes

* upgrade deployment image due to incorrect run directory ([e364e10](https://github.com/timenglesf/pi-homelab/commit/e364e109413f3e48626845c30a1a36dcf90f9b57))

## [0.3.0](https://github.com/timenglesf/pi-homelab/compare/v0.2.0...v0.3.0) (2024-12-16)


### Features

* add ingress resource for linkding ([f4073f4](https://github.com/timenglesf/pi-homelab/commit/f4073f409c720d3e4dbae468c678a4d94524ed65))
* add mb-intake deployment and kustomization ([f1bf104](https://github.com/timenglesf/pi-homelab/commit/f1bf10414778a22e28081d537574f18ceb530d9f))
* **linkding:** add node affinity to deployment ([d592b06](https://github.com/timenglesf/pi-homelab/commit/d592b067fcb3465061751ab0fc3eb445370ad68a))
* **linkding:** temporarily comment out cloudflare.yaml to close cloudflare tunnels ([391feed](https://github.com/timenglesf/pi-homelab/commit/391feed67e107aa0bc9f0b990820cb1e73dbcb4c))
* **linkding:** update node selector and add PV ([4a41f30](https://github.com/timenglesf/pi-homelab/commit/4a41f30561d8ecea22e18bbab54a92521361fc8f))


### Bug Fixes

* add storageClassName ([f91465b](https://github.com/timenglesf/pi-homelab/commit/f91465b6070073d854944825ca075c7eee693843))
* add web entry point annotation to linkding ingress ([cb3a7a4](https://github.com/timenglesf/pi-homelab/commit/cb3a7a40386ebfcdf1b813fe1e7fa2eed4bf1dcd))
* convert storage back to PVC ([5f93dfe](https://github.com/timenglesf/pi-homelab/commit/5f93dfef894bb58656bf2f41a42993c5cc00390d))
* remove node affinity for linkding deployment ([a732db8](https://github.com/timenglesf/pi-homelab/commit/a732db8a2ec50b5f0686f0be1b4ee5f5b0dd09eb))
* Removed redundant CHANGELOG.md from monitoring/controllers/base ([c6076ec](https://github.com/timenglesf/pi-homelab/commit/c6076ecd099c3ff3de1597c62183bd2197171473))
* uncomment cloudflare.yaml from apps/staging/linkding/kustomization ([c34e490](https://github.com/timenglesf/pi-homelab/commit/c34e490198ab334c20d2bde3ff6420b4de8771ad))

## [0.2.0](https://github.com/timenglesf/pi-homelab/compare/v0.1.2...v0.2.0) (2024-12-12)

### Features

- add kube-prometheus-stack to cluster ([5ba3c5d](https://github.com/timenglesf/pi-homelab/commit/5ba3c5d62ada3e7ef179d8597d7adfc0e84886ec))
- add SOPS decryption ([428a9b3](https://github.com/timenglesf/pi-homelab/commit/428a9b3195023bdc9bfb2746945853148f46fc01))
- add test secret ([c1bb558](https://github.com/timenglesf/pi-homelab/commit/c1bb558a5300f0fcfa5cfd80035d730227ad3df1))
- **linkding:** add cloudflare and linkding login secret ([6f35123](https://github.com/timenglesf/pi-homelab/commit/6f351237f80816486bb9f7929ad68155b48cbf37))

### Bug Fixes

- comment out unused yaml break in monitoring.yaml ([c067705](https://github.com/timenglesf/pi-homelab/commit/c0677055a4f88e755cb6cf23277ce46436dad42b))

### [0.1.2](https://github.com/timenglesf/pi-homelab/compare/v0.1.1...v0.1.2) (2024-12-11)

### Features

- **linkding:** add cloudflare deployment config ([0774d53](https://github.com/timenglesf/pi-homelab/commit/0774d53be63864592ba3c240c9d8d6eca8af4308))
- **linkding:** add security context to deployment ([e9e60a5](https://github.com/timenglesf/pi-homelab/commit/e9e60a53cb436bcf71f9240cdcbbb3fca62a2b94))
- **linkding:** add service configuration ([8135792](https://github.com/timenglesf/pi-homelab/commit/8135792a0acf6b73770a0ffe5bc3b767a36cc93b))

### 0.1.1 (2024-12-05)

### Features

- deploy linkding ([af2c354](https://github.com/timenglesf/pi-homelab/commit/af2c3545607533dfcf5b5a75d7f198eac9ee5b11))
- **linkding:** add persistent storage configuration ([110994a](https://github.com/timenglesf/pi-homelab/commit/110994a810922e6ded10538a1b72cc90e1ae6171))

### Bug Fixes

- correct apiVersion in apps/base/linkding/kustomization.yaml ([fe36edb](https://github.com/timenglesf/pi-homelab/commit/fe36edb0db40dfd446b2ee7af0aa9d9545dc88cc))

## 0.1.0 (2024-12-05)

### Features

- deploy linkding ([af2c354](https://github.com/timenglesf/pi-homelab/commit/af2c3545607533dfcf5b5a75d7f198eac9ee5b11))
- **linkding:** add persistent storage configuration ([110994a](https://github.com/timenglesf/pi-homelab/commit/110994a810922e6ded10538a1b72cc90e1ae6171))

### Bug Fixes

- correct apiVersion in apps/base/linkding/kustomization.yaml ([fe36edb](https://github.com/timenglesf/pi-homelab/commit/fe36edb0db40dfd446b2ee7af0aa9d9545dc88cc))

### [0.0.2](https://github.com/timenglesf/pi-homelab/compare/v0.0.1...v0.0.2) (2024-12-05)

### Bug Fixes

- **linkding:** update apiVersion in apps/base/linkding/kustomization.yaml ([a8f134b](https://github.com/timenglesf/pi-homelab/commit/a8f134b448195d85db7392a7a2203018fa8d819c))

### 0.0.1 (2024-12-05)

### Features

- deploy linkding ([af2c354](https://github.com/timenglesf/pi-homelab/commit/af2c3545607533dfcf5b5a75d7f198eac9ee5b11))

### Bug Fixes

- correct apiVersion in apps/base/linkding/kustomization.yaml ([fe36edb](https://github.com/timenglesf/pi-homelab/commit/fe36edb0db40dfd446b2ee7af0aa9d9545dc88cc))
- **kustomization:** correct apiVersion to v1beta1 ([bccf3e8](https://github.com/timenglesf/pi-homelab/commit/bccf3e862438c2dc56534c7b2ed22dd578f1a9ae))
