# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [0.2.0](https://github.com/csshugs/FluidMS/compare/0.1.1...0.2.0) (2020-02-03)


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

### Bug Fixes

* use correct punctuation ([f98a4fa](https://github.com/csshugs/FluidMS/commit/f98a4fa))
* webserver not serving `index.html` on baseUrl ([#13](https://github.com/csshugs/FluidMS/issues/13)) ([d374247](https://github.com/csshugs/FluidMS/commit/d374247))


### Documentation

* enhance contributing guidelines ([50273b4](https://github.com/csshugs/FluidMS/commit/50273b4))


* provide automatic changelog generation ([#7](https://github.com/csshugs/FluidMS/issues/7)) ([e6a3be6](https://github.com/csshugs/FluidMS/commit/e6a3be6))


### Features

* add commit linting ([27e309e](https://github.com/csshugs/FluidMS/commit/27e309e))
* add feature flag for baseline grid ([#2](https://github.com/csshugs/FluidMS/issues/2)) ([45f2b2b](https://github.com/csshugs/FluidMS/commit/45f2b2b))
* add line-height ratio ([#18](https://github.com/csshugs/FluidMS/issues/18)) ([ba469b3](https://github.com/csshugs/FluidMS/commit/ba469b3))
* add sassdoc integration ([7152506](https://github.com/csshugs/FluidMS/commit/7152506))
* allow custom font-sizes ([b438492](https://github.com/csshugs/FluidMS/commit/b438492))
* stop shrinking of small type on larger viewports ([#21](https://github.com/csshugs/FluidMS/issues/21)) ([4ae74f1](https://github.com/csshugs/FluidMS/commit/4ae74f1))
