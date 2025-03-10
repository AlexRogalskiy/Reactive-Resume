# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [3.2.5](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.2.4...v3.2.5) (2022-03-16)


### Features

* **i18n:** add danish, polish and turkish locales to i18n ([97e9432](https://github.com/AmruthPillai/Reactive-Resume/commit/97e9432d6bd887e666a3443fbfde9a92cef53965))


### Bug Fixes

* **client/templates:** fix text veering off of artboard in most templates ([b2f1fb3](https://github.com/AmruthPillai/Reactive-Resume/commit/b2f1fb3a5502988a49c5cd3e496d9d165f5c1792)), closes [#702](https://github.com/AmruthPillai/Reactive-Resume/issues/702)

### [3.2.4](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.2.3...v3.2.4) (2022-03-14)

### [3.2.3](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.2.2...v3.2.3) (2022-03-14)


### Features

* **client/import:** implement import json from reactive resume v2 ([42408ce](https://github.com/AmruthPillai/Reactive-Resume/commit/42408ce8c5ce55904854f9f6e0481889a01edfb8))

### [3.2.2](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.2.1...v3.2.2) (2022-03-14)


### Bug Fixes

* **client/skills:** make skill level optional ([02e396b](https://github.com/AmruthPillai/Reactive-Resume/commit/02e396bfdbf07ae75661f1e7e4e55060cacee7d0))

### [3.2.1](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.2.0...v3.2.1) (2022-03-14)


### Features

* **i18n:** add Chinese (Simplified) language to locales ([549363b](https://github.com/AmruthPillai/Reactive-Resume/commit/549363bbe5bdd781699dea9506bd4baedf5740d1))


### Bug Fixes

* **client/basics:** fix issue with overlapping photo filters on safari/webkit/iOS ([e6bda68](https://github.com/AmruthPillai/Reactive-Resume/commit/e6bda688ac3ba1c04e82721add92e755ea5386c3))
* **docker:** fix docker-compose for production grade deployments ([57f7edc](https://github.com/AmruthPillai/Reactive-Resume/commit/57f7edc13432a038c907afc6cb74b5182a9b2333))

## [3.2.0](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.1.4...v3.2.0) (2022-03-14)


### Features

* **i18n:** add Bengali, Italian and other languages ([21931bc](https://github.com/AmruthPillai/Reactive-Resume/commit/21931bc324b5e2440baaaaa2e52a93b4f2c766f8))


### Bug Fixes

* **app:** fix issue with external link redirection in android app ([b18120b](https://github.com/AmruthPillai/Reactive-Resume/commit/b18120b3f7223981e28c0441a6b7725787186edb))
* **client:** fix issue with react-query cache ([ed75a85](https://github.com/AmruthPillai/Reactive-Resume/commit/ed75a858279047dfd43152e041c1a09a625417f5))

### [3.1.4](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.1.3...v3.1.4) (2022-03-12)


### Bug Fixes

* **client:** exported pdf did not contain "Present" keyword with translations ([cf670af](https://github.com/AmruthPillai/Reactive-Resume/commit/cf670af4035dc9b462cf5b1aad06ca089cf1d40c))
* **client:** fix issues raised through lgtm alerts ([dfccb31](https://github.com/AmruthPillai/Reactive-Resume/commit/dfccb3130f889934d31196226be3d33e772f323b))

### [3.1.3](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.1.2...v3.1.3) (2022-03-12)


### Bug Fixes

* **server:** reform url for pdf generation and download ([6d55f91](https://github.com/AmruthPillai/Reactive-Resume/commit/6d55f917eab3cb2f5f3a90c5a18f03b625d60021)), closes [#661](https://github.com/AmruthPillai/Reactive-Resume/issues/661)

### [3.1.2](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.1.1...v3.1.2) (2022-03-12)


### CI

* **docker:**: include traefik routing and proxy to ensure server connections pass in local ([11cb066](https://github.com/AmruthPillai/Reactive-Resume/commit/11cb066573c6917857b79c028b97fcda1acaf90a))

### [3.1.1](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.1.0...v3.1.1) (2022-03-12)


### Features

* **client:** add product hunt announcement banner ([b515fc3](https://github.com/AmruthPillai/Reactive-Resume/commit/b515fc36e7f282db92e8eb509b6c5004a944fa95))

## [3.1.0](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.0.0...v3.1.0) (2022-03-12)


### Features

* **client:** add "spanish (es)" language to i18n locales ([bf167f8](https://github.com/AmruthPillai/Reactive-Resume/commit/bf167f81a3659677dada55856f5eaf0fc469e697))
* **client:** add mm/yyyy date option to date format options ([82bf44d](https://github.com/AmruthPillai/Reactive-Resume/commit/82bf44daa24422156779e9b38d3dc695176eaa09)), closes [#656](https://github.com/AmruthPillai/Reactive-Resume/issues/656)
* **client:** add sitemap generation to next app ([2cbc582](https://github.com/AmruthPillai/Reactive-Resume/commit/2cbc582a12b72b3012246022d4b518ed657d4c08))
* **client:** disable "Toggle Page Orientation" when there's only one page on the artboard ([01da1a0](https://github.com/AmruthPillai/Reactive-Resume/commit/01da1a06b802f1063a41d7a9a682e76b1daf9461)), closes [#655](https://github.com/AmruthPillai/Reactive-Resume/issues/655)


### Bug Fixes

* **client:** remove hard-coded "keywords:" in certain templates ([dda42b4](https://github.com/AmruthPillai/Reactive-Resume/commit/dda42b4c6b3bc359ac4f2bb91ca8118ddc84ec07)), closes [#650](https://github.com/AmruthPillai/Reactive-Resume/issues/650)
* **client:** show "present" string if end date is not entered, also add to i18n locales ([b5cd6c4](https://github.com/AmruthPillai/Reactive-Resume/commit/b5cd6c412b5b6b6ca7bb43c3801762de451f06b4)), closes [#653](https://github.com/AmruthPillai/Reactive-Resume/issues/653)
* **server:** photo uploads not working, fix save location and returned url ([799f208](https://github.com/AmruthPillai/Reactive-Resume/commit/799f20823e6d97a1ff0ba2c45c61d56304d0fa58)), closes [#658](https://github.com/AmruthPillai/Reactive-Resume/issues/658)

## [3.0.0](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.0.0-beta.6...v3.0.0) (2022-03-11)


### Features

* **lang**: add German, Kannada and Tamil languages to the app ([3a524f9](https://github.com/AmruthPillai/Reactive-Resume/commit/3a524f9c9c7a0e446491265b2242ad3dfeae188c))
* **docs:** add docusaurus workspace, initial setup of docs ([dc4aa0b](https://github.com/AmruthPillai/Reactive-Resume/commit/dc4aa0b496096bd59c45426bfcea6ba7db5f5c01))

## [3.0.0-beta.6](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.0.0-beta.5...v3.0.0-beta.6) (2022-03-11)

### Features

* **lang:** add language switcher on the landing page, in the footer ([8bc7d25](https://github.com/AmruthPillai/Reactive-Resume/commit/8bc7d2599ef6af7a07bfbe886c43844152b0d9f7))

### Bug Fixes

* **i18n:** add missing translation keys, update lang/locale logic ([7d8828a](https://github.com/AmruthPillai/Reactive-Resume/commit/7d8828a358d653bb162877a64c75028eb82678cd))
* **webkit:** fix issue with webkit not supporting .at() ([2654cba](https://github.com/AmruthPillai/Reactive-Resume/commit/2654cba039eb73d33257c36fa90a52cabc9fda96))

## [3.0.0-beta.5](https://github.com/AmruthPillai/Reactive-Resume/compare/v3.0.0-beta.4...v3.0.0-beta.5) (2022-03-10)

### Bug Fixes

* **app:** fix issue with using swipelayout ([972e8b1](https://github.com/AmruthPillai/Reactive-Resume/commit/972e8b1bcf9ad44d8915bf23d189711672937bc0))
