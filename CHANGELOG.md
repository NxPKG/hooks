# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.8.1](https://github.com/nxpkg/hooks/compare/v0.8.0...v0.8.1) (2023-02-10)


### Bug Fixes

* **hooks:** Add toJSON to hook context ([#108](https://github.com/nxpkg/hooks/issues/108)) ([03e5883](https://github.com/nxpkg/hooks/commit/03e588344fb54066b8a3b178ca114d5925432745))





# [0.8.0](https://github.com/nxpkg/hooks/compare/v0.7.6...v0.8.0) (2023-02-07)


### Bug Fixes

* **hooks:** Update context.error in error hooks ([#107](https://github.com/nxpkg/hooks/issues/107)) ([d148869](https://github.com/nxpkg/hooks/commit/d148869c4f41e700e92e0d7e14a19b63690c4521))


### Features

* **hooks:** Performance improvement ([#106](https://github.com/nxpkg/hooks/issues/106)) ([c14d07c](https://github.com/nxpkg/hooks/commit/c14d07c0cb4674056c6aadb14dd6f808399a95a3))





## [0.7.6](https://github.com/nxpkg/hooks/compare/v0.7.5...v0.7.6) (2022-12-08)


### Bug Fixes

* restore `context.type` ([#104](https://github.com/nxpkg/hooks/issues/104)) ([1d934ae](https://github.com/nxpkg/hooks/commit/1d934aee85276b4585268dcaf4e6360d7b1137dc))





## [0.7.5](https://github.com/nxpkg/hooks/compare/v0.7.4...v0.7.5) (2022-06-04)


### Bug Fixes

* **hooks:** Ensure that all error hooks are run ([#103](https://github.com/nxpkg/hooks/issues/103)) ([bbd1979](https://github.com/nxpkg/hooks/commit/bbd1979a1854441def03581bc248b11bb5fb1b2d))
* **hooks:** Update regular hook order as suggested in [#97](https://github.com/nxpkg/hooks/issues/97) ([9b758fc](https://github.com/nxpkg/hooks/commit/9b758fc6e498c3f4f9a85da47974c6c2244d588e))





## [0.7.4](https://github.com/nxpkg/hooks/compare/v0.7.3...v0.7.4) (2022-04-27)


### Bug Fixes

* **hooks:** Allow hooks on functions that have properties ([#102](https://github.com/nxpkg/hooks/issues/102)) ([eee7880](https://github.com/nxpkg/hooks/commit/eee7880918769c7dbcd2b48853fea0148dc23951))





## [0.7.3](https://github.com/nxpkg/hooks/compare/v0.7.2...v0.7.3) (2022-02-05)


### Bug Fixes

* **build:** Update DNT build system to fix Webpack builds ([#99](https://github.com/nxpkg/hooks/issues/99)) ([7b7033b](https://github.com/nxpkg/hooks/commit/7b7033b76c1f678352fff96a4873a88405c6ec76))





## [0.7.2](https://github.com/nxpkg/hooks/compare/v0.7.1...v0.7.2) (2021-11-20)


### Bug Fixes

* Use proper Deno location ([c70b070](https://github.com/nxpkg/hooks/commit/c70b0706d6e2910cdfc6cf9f9dc71b63ed605fc7))





## [0.7.1](https://github.com/nxpkg/hooks/compare/v0.7.0...v0.7.1) (2021-11-20)


### Bug Fixes

* Update Deno package location ([b2ae6eb](https://github.com/nxpkg/hooks/commit/b2ae6eb4785052c0004d721163751321295c3207))





# [0.7.0](https://github.com/nxpkg/hooks/compare/v0.6.5...v0.7.0) (2021-11-19)


### Features

* Add support for regular before, after and error hooks ([#92](https://github.com/nxpkg/hooks/issues/92)) ([8e4328f](https://github.com/nxpkg/hooks/commit/8e4328f0b6963305e81d64ce0a06dbfab56e594a))
* Move development and publishing to Deno ([#93](https://github.com/nxpkg/hooks/issues/93)) ([c2a1b0b](https://github.com/nxpkg/hooks/commit/c2a1b0b03a4ba320df90d054c0b2fedbc382d6fe))






## [0.6.5](https://github.com/nxpkg/hooks/compare/v0.6.4...v0.6.5) (2021-04-20)


### Bug Fixes

* **typescript:** Tighten up TypeScript settings to be ECMAScript and Deno compatible ([#81](https://github.com/nxpkg/hooks/issues/81)) ([28fe875](https://github.com/nxpkg/hooks/commit/28fe8758b4764981473830db4a0013dd1beca489))





## [0.6.4](https://github.com/nxpkg/hooks/compare/v0.6.3...v0.6.4) (2021-04-11)


### Bug Fixes

* allow to hooks a function without middleware ([#77](https://github.com/nxpkg/hooks/issues/77)) ([38b44c3](https://github.com/nxpkg/hooks/commit/38b44c3ba1bd7753cdb81492b517e4fd3a6af50e))
* conserve fn.length and fn.name ([#79](https://github.com/nxpkg/hooks/issues/79)) ([d9bc9af](https://github.com/nxpkg/hooks/commit/d9bc9af689f15398168ce4493fcfb23af0f3ef05))





## [0.6.3](https://github.com/nxpkg/hooks/compare/v0.6.2...v0.6.3) (2021-03-31)


### Bug Fixes

* **hooks:** Add Deno tests and build, CI and fix build ([#73](https://github.com/nxpkg/hooks/issues/73)) ([44787cd](https://github.com/nxpkg/hooks/commit/44787cd2106c6d1ff4fe8bc5d59362e14427c468))





## [0.6.2](https://github.com/nxpkg/hooks/compare/v0.6.1...v0.6.2) (2021-02-08)


### Bug Fixes

* **hooks:** Allow to set context.result to undefined ([#70](https://github.com/nxpkg/hooks/issues/70)) ([7b5807f](https://github.com/nxpkg/hooks/commit/7b5807f8a31b0e4859eaabdbcc8b49fc3b544548))





## [0.6.1](https://github.com/nxpkg/hooks/compare/v0.6.0...v0.6.1) (2020-12-11)


### Bug Fixes

* **hooks:** fix some errors for nxpkg integration ([#67](https://github.com/nxpkg/hooks/issues/67)) ([fcfc0ca](https://github.com/nxpkg/hooks/commit/fcfc0ca6423a8062959d41f34e673f81d3c006dd))
* **hooks:** Remove redundant method call ([#65](https://github.com/nxpkg/hooks/issues/65)) ([4ff10a9](https://github.com/nxpkg/hooks/commit/4ff10a9935682276b8ca3ffb699275b627230dfa))
* **hooks:** Stricter condition ([#64](https://github.com/nxpkg/hooks/issues/64)) ([6de77a1](https://github.com/nxpkg/hooks/commit/6de77a1afcbee4867b7e464be0b556a8dc9656e3))





# [0.6.0](https://github.com/nxpkg/hooks/compare/v0.5.0...v0.6.0) (2020-11-12)


### Features

* **hooks:** Revert refactoring into separate hooks (PR [#37](https://github.com/nxpkg/hooks/issues/37)) ([#57](https://github.com/nxpkg/hooks/issues/57)) ([56a44be](https://github.com/nxpkg/hooks/commit/56a44beb3388873f7bef12ac640f115beffceb95))





# [0.5.0](https://github.com/nxpkg/hooks/compare/v0.5.0-alpha.0...v0.5.0) (2020-06-01)


### Features

* **hooks:** Finalize default initializer functionality ([#35](https://github.com/nxpkg/hooks/issues/35)) ([d380d76](https://github.com/nxpkg/hooks/commit/d380d76891b28160c992438bfb3f28493eacddc4))
* **hooks:** Refactor .params, .props and .defaults into hooks ([#37](https://github.com/nxpkg/hooks/issues/37)) ([9b13b7d](https://github.com/nxpkg/hooks/commit/9b13b7de6b708a2152927335aae25dd320b4cfeb))
* **typescript:** Improve type indexes for stricter object and class hooks ([699f2fd](https://github.com/nxpkg/hooks/commit/699f2fd973eb72c0d7c3aefff7b230a7a8a2918a))





# [0.5.0-alpha.0](https://github.com/nxpkg/hooks/compare/v0.4.0-alpha.0...v0.5.0-alpha.0) (2020-04-05)

**Note:** Version bump only for package @nxpkg/hooks





# [0.4.0-alpha.0](https://github.com/nxpkg/hooks/compare/v0.3.1...v0.4.0-alpha.0) (2020-02-19)


### Bug Fixes

* conserve props from original method ([#19](https://github.com/nxpkg/hooks/issues/19)) ([9a77e81](https://github.com/nxpkg/hooks/commit/9a77e81a8b0912a8d3275a2d18e19616d4e4d37e))
* remove walkOriginal ([df1f7ff](https://github.com/nxpkg/hooks/commit/df1f7ffa73ea087d487582efa3c8c7f5be992ab9))
* Update withParams ([#16](https://github.com/nxpkg/hooks/issues/16)) ([b89d044](https://github.com/nxpkg/hooks/commit/b89d0443680d1a30f0875d1b817ddf9ad6220ffe))
* use collector of each .original ([#17](https://github.com/nxpkg/hooks/issues/17)) ([33fd2cb](https://github.com/nxpkg/hooks/commit/33fd2cb3a66301e76be6e83c5a7d6248434c7fd0))


### Features

* add setMiddleware ([#18](https://github.com/nxpkg/hooks/issues/18)) ([7d0113d](https://github.com/nxpkg/hooks/commit/7d0113d4e6c972983e6384ff892cb5ca8c70365c))
* Chainable configuration ([#23](https://github.com/nxpkg/hooks/issues/23)) ([c534827](https://github.com/nxpkg/hooks/commit/c534827d539faab885f84d035e2edb912770759f))





## [0.3.1](https://github.com/nxpkg/hooks/compare/v0.3.0...v0.3.1) (2020-01-29)


### Bug Fixes

* Fix dependency entries ([4a15e74](https://github.com/nxpkg/hooks/commit/4a15e74f83247833edf7de8ea26b908115a5ab7a))





# [0.3.0](https://github.com/nxpkg/hooks/compare/v0.2.0...v0.3.0) (2020-01-29)


### Features

* Allow multiple context initializers ([#12](https://github.com/nxpkg/hooks/issues/12)) ([a556272](https://github.com/nxpkg/hooks/commit/a556272f535c7d2a25bcbc12d8473cdaefaf8c56))





# [0.2.0](https://github.com/nxpkg/hooks/compare/v0.1.0...v0.2.0) (2020-01-14)


### Bug Fixes

* Add tests for fn.original and update documentation ([#5](https://github.com/nxpkg/hooks/issues/5)) ([f4c1955](https://github.com/nxpkg/hooks/commit/f4c195512c2f24d4d9abb68d39275f2287574162))


### Features

* Add browser build ([#8](https://github.com/nxpkg/hooks/issues/8)) ([d6162ca](https://github.com/nxpkg/hooks/commit/d6162caccabe43c468df9360f7f03362ad36c41d))
* Add build script and publish a version for Deno ([#6](https://github.com/nxpkg/hooks/issues/6)) ([f2b5697](https://github.com/nxpkg/hooks/commit/f2b56972fa2ef21799bc6e531644ef9e751bd25b))
* Refactoring to pass an option object to initialize hooks more explicitly ([#7](https://github.com/nxpkg/hooks/issues/7)) ([8f2453f](https://github.com/nxpkg/hooks/commit/8f2453f3e230f6c17989f244cc3dc8126a895eeb))





# 0.1.0 (2020-01-05)


### Features

* Finalize functionality for initial release of @nxpkg/hooks package ([#1](https://github.com/nxpkg/hooks/issues/1)) ([edab7a1](https://github.com/nxpkg/hooks/commit/edab7a1d24b2f25f59af01aad1275ea74dee3879))
