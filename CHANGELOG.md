# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [0.2.2](https://github.com/csshugs/FluidMS/compare/0.1.1...0.2.2) (2020-05-18)


### ⚠ BREAKING CHANGES

* run `npx rimraf node_modules/ && npm install` to
definitely install the correct dependencies on your machine
* the name of the `$ms` argument for the
`fluidms-font-size()` mixin has changed to `$font-size` to make
it more natural to use if a custom font-size is used.
* rename `$FLUIDMS-GLOBAL-CONFIG` to `$FLUIDMS-CONFIG`
as the uppercase notation already indicates its global scope.

build: make npm script platform-agnostic

as the `rm` command is a bash command, this will not work in
default Windows environments. adding the `rimraf` npm package,
we make it platform-independent.

docs: correct mixin docs

provide correct mixin documentation for the sassdoc output.

### Features

* add commit linting ([27e309e](https://github.com/csshugs/FluidMS/commit/27e309ebc00f902eaecce16b0c39598d139680a8))
* add feature flag for baseline grid ([#2](https://github.com/csshugs/FluidMS/issues/2)) ([45f2b2b](https://github.com/csshugs/FluidMS/commit/45f2b2b70df2b15cd68d00cedee012cf06aa6934))
* add line-height ratio ([#18](https://github.com/csshugs/FluidMS/issues/18)) ([ba469b3](https://github.com/csshugs/FluidMS/commit/ba469b3e26d6bdabbc083dc078343679a0d77a4b))
* add sassdoc integration ([7152506](https://github.com/csshugs/FluidMS/commit/71525063fbb0a9ded8397fbd65ed05e8b7093f2f))
* allow custom font-sizes ([b438492](https://github.com/csshugs/FluidMS/commit/b43849253364b5337e2eac8b983cfc1f3893323e))
* make config adjustable ([#27](https://github.com/csshugs/FluidMS/issues/27)) ([7f6681a](https://github.com/csshugs/FluidMS/commit/7f6681a752a1a4f4f80d8b808d32ca942b322767))
* stop shrinking of small type on larger viewports ([#21](https://github.com/csshugs/FluidMS/issues/21)) ([4ae74f1](https://github.com/csshugs/FluidMS/commit/4ae74f1c224a408f32d53b67d0a538150e0e386e))


### Bug Fixes

* use correct punctuation ([f98a4fa](https://github.com/csshugs/FluidMS/commit/f98a4fac9265818716d293d4bb307d5bb3e192e8))
* webserver not serving `index.html` on baseUrl ([#13](https://github.com/csshugs/FluidMS/issues/13)) ([d374247](https://github.com/csshugs/FluidMS/commit/d374247aa4f46296e16c18804afc67457c1744f1))
* **docs:** update sassdoc examples with new `ms()` function ([b06df1e](https://github.com/csshugs/FluidMS/commit/b06df1e17c3bc569dee9cdfba763afe4c88d4046))


* provide automatic changelog generation ([#7](https://github.com/csshugs/FluidMS/issues/7)) ([e6a3be6](https://github.com/csshugs/FluidMS/commit/e6a3be6e88574ee784122814aedd6591b9586180))


### Documentation

* enhance contributing guidelines ([50273b4](https://github.com/csshugs/FluidMS/commit/50273b470f606f417fb5308cbd6fd29a1b58b3e6))

### [0.2.1](https://github.com/csshugs/FluidMS/compare/0.1.1...0.2.1) (2020-05-04)


### Refactor

* comply with official else-if notation ([41de11a](https://github.com/csshugs/FluidMS/commit/41de11a1e39433e71e175759d9eb0727777883a9))

## [0.2.0](https://github.com/csshugs/FluidMS/compare/0.1.1...0.2.0) (2020-02-03)


### ⚠ BREAKING CHANGES

* the name of the `$ms` argument for the
`fluidms-font-size()` mixin has changed to `$font-size` to make
it more natural to use if a custom font-size is used.
* rename `$FLUIDMS-GLOBAL-CONFIG` to `$FLUIDMS-CONFIG`
as the uppercase notation already indicates its global scope.


### Bug Fixes

* use correct punctuation ([f98a4fa](https://github.com/csshugs/FluidMS/commit/f98a4fa))
* webserver not serving `index.html` on baseUrl ([#13](https://github.com/csshugs/FluidMS/issues/13)) ([d374247](https://github.com/csshugs/FluidMS/commit/d374247))


### Documentation

* enhance contributing guidelines ([50273b4](https://github.com/csshugs/FluidMS/commit/50273b4))
* provide automatic changelog generation ([#7](https://github.com/csshugs/FluidMS/issues/7)) ([e6a3be6](https://github.com/csshugs/FluidMS/commit/e6a3be6))
* add sassdoc integration ([7152506](https://github.com/csshugs/FluidMS/commit/7152506))


### Features

* add feature flag for baseline grid ([#2](https://github.com/csshugs/FluidMS/issues/2)) ([45f2b2b](https://github.com/csshugs/FluidMS/commit/45f2b2b))
* add line-height ratio ([#18](https://github.com/csshugs/FluidMS/issues/18)) ([ba469b3](https://github.com/csshugs/FluidMS/commit/ba469b3))
* allow custom font-sizes ([b438492](https://github.com/csshugs/FluidMS/commit/b438492))
* stop shrinking of small type on larger viewports ([#21](https://github.com/csshugs/FluidMS/issues/21)) ([4ae74f1](https://github.com/csshugs/FluidMS/commit/4ae74f1))
