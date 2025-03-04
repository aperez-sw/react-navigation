# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [7.0.0-alpha.2](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@7.0.0-alpha.1...@react-navigation/material-top-tabs@7.0.0-alpha.2) (2023-06-22)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [7.0.0-alpha.1](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@7.0.0-alpha.0...@react-navigation/material-top-tabs@7.0.0-alpha.1) (2023-03-01)

### Bug Fixes

* fix paths in sourcemap files ([368e069](https://github.com/react-navigation/react-navigation/commit/368e0691b9fb07d4b1cbe71cfe4c2f40512f93ad)) - by @satya164

### Features

* add ability to customize the fonts with the theme ([#11243](https://github.com/react-navigation/react-navigation/issues/11243)) ([1cd6836](https://github.com/react-navigation/react-navigation/commit/1cd6836f1d10bcdf7f96d9e4b9f7de0ddea9391f)) - by @satya164

# [7.0.0-alpha.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.3.1...@react-navigation/material-top-tabs@7.0.0-alpha.0) (2023-02-17)

### Code Refactoring

* move tab-view to direct dependency of material-top-tabs ([2bd585b](https://github.com/react-navigation/react-navigation/commit/2bd585b8055995daaacc20a3304d0a4e9ec70f44)) - by @satya164

### Features

* allow users to pass `android_ripple` config in TabView ([#11203](https://github.com/react-navigation/react-navigation/issues/11203)) ([15939d8](https://github.com/react-navigation/react-navigation/commit/15939d82cd7d77d2a75a870279d08cb18c7f9919)), closes [#11198](https://github.com/react-navigation/react-navigation/issues/11198) - by @okwasniewski
* expose tabBarGap option in material top tabs ([#11038](https://github.com/react-navigation/react-navigation/issues/11038)) ([29818a8](https://github.com/react-navigation/react-navigation/commit/29818a80d5086e0702b352e68996a4384eb997e3)) - by @mlecoq
* expose the original label in children prop for custom label functions in tab navigators ([a6fd49f](https://github.com/react-navigation/react-navigation/commit/a6fd49f9af9353cf5fd5364feafcbeea25c3ff7f)) - by @satya164

### BREAKING CHANGES

* This change will simplify installation of material-top-tabs, but that means user's version won't be used anymore. If users need to force specific version, they can use yarn's `resolutions` or npm's `overrides` feature.

## [6.3.1](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.3.0...@react-navigation/material-top-tabs@6.3.1) (2022-11-21)

### Bug Fixes

* add accessibility props to NativeStack screens ([#11022](https://github.com/react-navigation/react-navigation/issues/11022)) ([3ab05af](https://github.com/react-navigation/react-navigation/commit/3ab05afeb6412b8e5566270442ac14a463136620))

# [6.3.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.2.4...@react-navigation/material-top-tabs@6.3.0) (2022-10-11)

### Features

* expose animationEnabled in material top tabs ([d1bd31f](https://github.com/react-navigation/react-navigation/commit/d1bd31f11b1a40a319e7fb6e3fee074edd059349))

## [6.2.4](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.2.2...@react-navigation/material-top-tabs@6.2.4) (2022-09-16)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [6.2.3](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.2.2...@react-navigation/material-top-tabs@6.2.3) (2022-08-24)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [6.2.2](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.2.1...@react-navigation/material-top-tabs@6.2.2) (2022-07-05)

### Bug Fixes

* ensure same @types/react version in repo ([#10663](https://github.com/react-navigation/react-navigation/issues/10663)) ([e662465](https://github.com/react-navigation/react-navigation/commit/e6624653fbbd931158dbebd17142abf9637205b6)), closes [#10655](https://github.com/react-navigation/react-navigation/issues/10655)

## [6.2.1](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.2.0...@react-navigation/material-top-tabs@6.2.1) (2022-04-01)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.2.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.1.1...@react-navigation/material-top-tabs@6.2.0) (2022-04-01)

### Features

* add an ID prop to navigators ([4e4935a](https://github.com/react-navigation/react-navigation/commit/4e4935ac2584bc1a00209609cc026fa73e12c10a))

## [6.1.1](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.1.0...@react-navigation/material-top-tabs@6.1.1) (2022-02-02)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.1.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.6...@react-navigation/material-top-tabs@6.1.0) (2022-01-29)

### Features

* **native-stack:** export NativeStackView to support custom routers on native-stack ([#10260](https://github.com/react-navigation/react-navigation/issues/10260)) ([7b761f1](https://github.com/react-navigation/react-navigation/commit/7b761f1cc069ca68b96b5155be726024a345346f))

## [6.0.6](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.5...@react-navigation/material-top-tabs@6.0.6) (2021-10-12)

### Bug Fixes

* move [@ts-expect-error](https://github.com/ts-expect-error) to body to avoid issue in type definitions ([0a08688](https://github.com/react-navigation/react-navigation/commit/0a0868862c9d6ae77055c66938a764306d391b44))

## [6.0.5](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.4...@react-navigation/material-top-tabs@6.0.5) (2021-10-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [6.0.4](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.3...@react-navigation/material-top-tabs@6.0.4) (2021-09-26)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [6.0.3](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.2...@react-navigation/material-top-tabs@6.0.3) (2021-09-26)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [6.0.2](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.1...@react-navigation/material-top-tabs@6.0.2) (2021-08-07)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [6.0.1](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0...@react-navigation/material-top-tabs@6.0.1) (2021-08-03)

### Bug Fixes

* preserve params when switching tabs. fixes [#9782](https://github.com/react-navigation/react-navigation/issues/9782) ([98fa233](https://github.com/react-navigation/react-navigation/commit/98fa2330146457045c01af820c6d8e8cb955f9d1))

# [6.0.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.18...@react-navigation/material-top-tabs@6.0.0) (2021-08-01)

### Features

* add tabBarBadge and tabBarIndicator options for material top tabs ([fdb3ede](https://github.com/react-navigation/react-navigation/commit/fdb3ede3e0eb1e43c4be30c810663880e2f5467c))
* move some props to screenOptions in material top tabs ([5bfc396](https://github.com/react-navigation/react-navigation/commit/5bfc39668bb5dce8bd872e5ff87f4b3fd683cf62))

# [6.0.0-next.18](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.17...@react-navigation/material-top-tabs@6.0.0-next.18) (2021-07-16)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.17](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.16...@react-navigation/material-top-tabs@6.0.0-next.17) (2021-07-16)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.16](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.14...@react-navigation/material-top-tabs@6.0.0-next.16) (2021-07-01)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.15](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.14...@react-navigation/material-top-tabs@6.0.0-next.15) (2021-06-10)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.14](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.13...@react-navigation/material-top-tabs@6.0.0-next.14) (2021-05-29)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.13](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.12...@react-navigation/material-top-tabs@6.0.0-next.13) (2021-05-29)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.12](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.11...@react-navigation/material-top-tabs@6.0.0-next.12) (2021-05-27)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.11](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.10...@react-navigation/material-top-tabs@6.0.0-next.11) (2021-05-26)

### Features

* add screenListeners prop on navigators similar to screenOptions ([cde44a5](https://github.com/react-navigation/react-navigation/commit/cde44a5785444a121aa08f94af9f8fe4fc89910a))

# [6.0.0-next.10](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.9...@react-navigation/material-top-tabs@6.0.0-next.10) (2021-05-23)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.9](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.8...@react-navigation/material-top-tabs@6.0.0-next.9) (2021-05-16)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.8](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.7...@react-navigation/material-top-tabs@6.0.0-next.8) (2021-05-10)

### Bug Fixes

* add a deprecation warning for mode prop in stack ([a6e4981](https://github.com/react-navigation/react-navigation/commit/a6e498170f59648190fa5513e273ca523e56c5d5))

### Features

* return a NavigationContent component from useNavigationBuilder ([1179d56](https://github.com/react-navigation/react-navigation/commit/1179d56c5008270753feef41acdc1dbd2191efcf))

# [6.0.0-next.7](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.6...@react-navigation/material-top-tabs@6.0.0-next.7) (2021-05-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.6](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.5...@react-navigation/material-top-tabs@6.0.0-next.6) (2021-05-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.5](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.4...@react-navigation/material-top-tabs@6.0.0-next.5) (2021-05-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.4](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.3...@react-navigation/material-top-tabs@6.0.0-next.4) (2021-05-01)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.3](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.2...@react-navigation/material-top-tabs@6.0.0-next.3) (2021-04-08)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.2](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0-next.1...@react-navigation/material-top-tabs@6.0.0-next.2) (2021-04-08)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [6.0.0-next.1](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@6.0.0...@react-navigation/material-top-tabs@6.0.0-next.1) (2021-03-10)

### Bug Fixes

* fix peer dep versions ([72f90b5](https://github.com/react-navigation/react-navigation/commit/72f90b50d27eda1315bb750beca8a36f26dafe17))

# [6.0.0-next.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.9...@react-navigation/material-top-tabs@6.0.0-next.0) (2021-03-09)

### Bug Fixes

* add missing helper types in descriptors ([21a1154](https://github.com/react-navigation/react-navigation/commit/21a11543bf41c4559c2570d5accc0bbb3b67eb8d))

### Features

* move lazy to options for material-top-tabs ([cfd1c9b](https://github.com/react-navigation/react-navigation/commit/cfd1c9b6efb528c7737fb68766873f9c564196d7))
* upgrade to latest react-native-tab-view using ViewPager ([2261001](https://github.com/react-navigation/react-navigation/commit/22610014b3b1e649b368a63fd021362235ee585d))

### BREAKING CHANGES

* The lazy prop now can be configured per screen instead of for the whole navigator. To keep previous behavior, you can specify it in screenOptions

## [5.3.9](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.8...@react-navigation/material-top-tabs@5.3.9) (2020-11-10)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.8](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.7...@react-navigation/material-top-tabs@5.3.8) (2020-11-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.7](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.6...@react-navigation/material-top-tabs@5.3.7) (2020-11-08)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.6](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.5...@react-navigation/material-top-tabs@5.3.6) (2020-11-04)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.5](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.4...@react-navigation/material-top-tabs@5.3.5) (2020-11-04)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.4](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.3...@react-navigation/material-top-tabs@5.3.4) (2020-11-03)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.3](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.2...@react-navigation/material-top-tabs@5.3.3) (2020-11-03)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.2](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.1...@react-navigation/material-top-tabs@5.3.2) (2020-10-30)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.3.1](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.3.0...@react-navigation/material-top-tabs@5.3.1) (2020-10-28)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.3.0](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.19...@react-navigation/material-top-tabs@5.3.0) (2020-10-24)

### Features

* improve types for navigation state ([#8980](https://github.com/react-navigation/react-navigation/issues/8980)) ([7dc2f58](https://github.com/react-navigation/react-navigation/commit/7dc2f5832e371473f3263c01ab39824eb9e2057d))
* update helper types to have navigator specific methods ([f51086e](https://github.com/react-navigation/react-navigation/commit/f51086edea42f2382dac8c6914aac8574132114b))

## [5.2.19](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.18...@react-navigation/material-top-tabs@5.2.19) (2020-10-07)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.18](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.17...@react-navigation/material-top-tabs@5.2.18) (2020-09-28)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.17](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.16...@react-navigation/material-top-tabs@5.2.17) (2020-09-22)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.16](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.15...@react-navigation/material-top-tabs@5.2.16) (2020-08-04)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.15](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.14...@react-navigation/material-top-tabs@5.2.15) (2020-07-28)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.14](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.13...@react-navigation/material-top-tabs@5.2.14) (2020-07-19)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.13](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.12...@react-navigation/material-top-tabs@5.2.13) (2020-07-10)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.12](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.11...@react-navigation/material-top-tabs@5.2.12) (2020-06-25)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.11](https://github.com/react-navigation/react-navigation/compare/@react-navigation/material-top-tabs@5.2.10...@react-navigation/material-top-tabs@5.2.11) (2020-06-24)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.10](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.9...@react-navigation/material-top-tabs@5.2.10) (2020-06-06)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.9](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.8...@react-navigation/material-top-tabs@5.2.9) (2020-05-27)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.8](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.7...@react-navigation/material-top-tabs@5.2.8) (2020-05-23)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.7](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.6...@react-navigation/material-top-tabs@5.2.7) (2020-05-20)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.6](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.5...@react-navigation/material-top-tabs@5.2.6) (2020-05-20)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.5](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.4...@react-navigation/material-top-tabs@5.2.5) (2020-05-16)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.4](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.3...@react-navigation/material-top-tabs@5.2.4) (2020-05-14)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.3](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.2...@react-navigation/material-top-tabs@5.2.3) (2020-05-14)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.2](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.1...@react-navigation/material-top-tabs@5.2.2) (2020-05-10)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.2.1](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.2.0...@react-navigation/material-top-tabs@5.2.1) (2020-05-08)

### Bug Fixes

* fix building typescript definitions. closes [#8216](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/issues/8216) ([47a1229](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/47a12298378747edd2d22e54dc1c8677f98c49b4))

# [5.2.0](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.15...@react-navigation/material-top-tabs@5.2.0) (2020-05-08)

### Features

* add generic type aliases for screen props ([bea14aa](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/bea14aa26fd5cbfebc7973733c5cf1f44fd323aa)), closes [#7971](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/issues/7971)

## [5.1.15](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.14...@react-navigation/material-top-tabs@5.1.15) (2020-05-05)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.14](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.13...@react-navigation/material-top-tabs@5.1.14) (2020-05-01)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.13](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.12...@react-navigation/material-top-tabs@5.1.13) (2020-05-01)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.12](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.11...@react-navigation/material-top-tabs@5.1.12) (2020-04-30)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.11](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.10...@react-navigation/material-top-tabs@5.1.11) (2020-04-30)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.10](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.9...@react-navigation/material-top-tabs@5.1.10) (2020-04-27)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.9](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.8...@react-navigation/material-top-tabs@5.1.9) (2020-04-17)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.8](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.7...@react-navigation/material-top-tabs@5.1.8) (2020-04-08)

### Bug Fixes

* mark type exports for all packages ([b71de6c](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/b71de6cc799143f1d0e8a0cfcc34f0a2381f9840))

## [5.1.7](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.6...@react-navigation/material-top-tabs@5.1.7) (2020-03-30)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.6](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.5...@react-navigation/material-top-tabs@5.1.6) (2020-03-23)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.5](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.4...@react-navigation/material-top-tabs@5.1.5) (2020-03-22)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.4](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.3...@react-navigation/material-top-tabs@5.1.4) (2020-03-19)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.3](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.2...@react-navigation/material-top-tabs@5.1.3) (2020-03-17)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.2](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.1...@react-navigation/material-top-tabs@5.1.2) (2020-03-16)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.1.1](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.1.0...@react-navigation/material-top-tabs@5.1.1) (2020-03-03)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.1.0](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.7...@react-navigation/material-top-tabs@5.1.0) (2020-02-26)

### Features

* add ability add listeners with listeners prop ([1624108](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/162410843c4f175ae107756de1c3af04d1d47aa7)), closes [#6756](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/issues/6756)

## [5.0.7](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.6...@react-navigation/material-top-tabs@5.0.7) (2020-02-21)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.0.6](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.5...@react-navigation/material-top-tabs@5.0.6) (2020-02-19)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.0.5](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.4...@react-navigation/material-top-tabs@5.0.5) (2020-02-14)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.0.4](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.3...@react-navigation/material-top-tabs@5.0.4) (2020-02-14)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.0.3](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.2...@react-navigation/material-top-tabs@5.0.3) (2020-02-12)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.0.2](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.1...@react-navigation/material-top-tabs@5.0.2) (2020-02-11)

**Note:** Version bump only for package @react-navigation/material-top-tabs

## [5.0.1](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.41...@react-navigation/material-top-tabs@5.0.1) (2020-02-10)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.41](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.40...@react-navigation/material-top-tabs@5.0.0-alpha.41) (2020-02-04)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.40](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.39...@react-navigation/material-top-tabs@5.0.0-alpha.40) (2020-02-04)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.39](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.38...@react-navigation/material-top-tabs@5.0.0-alpha.39) (2020-02-03)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.38](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.35...@react-navigation/material-top-tabs@5.0.0-alpha.38) (2020-02-02)

### Bug Fixes

* add licenses ([0c159db](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/0c159db4c9bc85e83b5cfe6819ab2562669a4d8f))
* wrap navigators in gesture handler root ([41a5e1a](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/41a5e1a385aa5180abc3992a4c67077c37b998b9))

# [5.0.0-alpha.36](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.35...@react-navigation/material-top-tabs@5.0.0-alpha.36) (2020-02-02)

### Bug Fixes

* add licenses ([0c159db](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/0c159db4c9bc85e83b5cfe6819ab2562669a4d8f))

# [5.0.0-alpha.35](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.34...@react-navigation/material-top-tabs@5.0.0-alpha.35) (2020-01-24)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.34](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.33...@react-navigation/material-top-tabs@5.0.0-alpha.34) (2020-01-23)

### Features

* let the navigator specify if default can be prevented ([da67e13](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/da67e134d2157201360427d3c10da24f24cae7aa))

# [5.0.0-alpha.33](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.32...@react-navigation/material-top-tabs@5.0.0-alpha.33) (2020-01-14)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.32](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.31...@react-navigation/material-top-tabs@5.0.0-alpha.32) (2020-01-13)

### Bug Fixes

* make sure paths aren't aliased when building definitions ([65a5dac](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/commit/65a5dac2bf887f4ba081ab15bd4c9870bb15697f)), closes [#265](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/issues/265)

# [5.0.0-alpha.31](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.30...@react-navigation/material-top-tabs@5.0.0-alpha.31) (2020-01-13)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.30](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.29...@react-navigation/material-top-tabs@5.0.0-alpha.30) (2020-01-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.29](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.27...@react-navigation/material-top-tabs@5.0.0-alpha.29) (2020-01-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.28](https://github.com/react-navigation/react-navigation/tree/main/packages/material-top-tabs/compare/@react-navigation/material-top-tabs@5.0.0-alpha.27...@react-navigation/material-top-tabs@5.0.0-alpha.28) (2020-01-09)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.27](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.26...@react-navigation/material-top-tabs@5.0.0-alpha.27) (2020-01-05)

### Features

* add support for pager component ([dcc5f99](https://github.com/react-navigation/navigation-ex/commit/dcc5f99ecd495ad1903c9e99884e0d4e9b3994f1))

# [5.0.0-alpha.26](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.25...@react-navigation/material-top-tabs@5.0.0-alpha.26) (2020-01-01)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.25](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.24...@react-navigation/material-top-tabs@5.0.0-alpha.25) (2019-12-19)

### Bug Fixes

* fix backgroundColor in sceneContainerStyle overriden by theme ([ebd145a](https://github.com/react-navigation/navigation-ex/commit/ebd145a09d80f119070a14a8d4940b5757b5e7fb)), closes [#215](https://github.com/react-navigation/navigation-ex/issues/215)

# [5.0.0-alpha.24](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.23...@react-navigation/material-top-tabs@5.0.0-alpha.24) (2019-12-16)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.23](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.22...@react-navigation/material-top-tabs@5.0.0-alpha.23) (2019-12-14)

### Features

* add custom theme support ([#211](https://github.com/react-navigation/navigation-ex/issues/211)) ([00fc616](https://github.com/react-navigation/navigation-ex/commit/00fc616de0572bade8aa85052cdc8290360b1d7f))

# [5.0.0-alpha.22](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.21...@react-navigation/material-top-tabs@5.0.0-alpha.22) (2019-12-11)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.21](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.20...@react-navigation/material-top-tabs@5.0.0-alpha.21) (2019-12-10)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.20](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.19...@react-navigation/material-top-tabs@5.0.0-alpha.20) (2019-12-07)

### Features

* export underlying views used to build navigators ([#191](https://github.com/react-navigation/navigation-ex/issues/191)) ([d618ab3](https://github.com/react-navigation/navigation-ex/commit/d618ab382ecc5eccbcd5faa89e76f9ed2d75f405))

# [5.0.0-alpha.19](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.18...@react-navigation/material-top-tabs@5.0.0-alpha.19) (2019-11-20)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.18](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.17...@react-navigation/material-top-tabs@5.0.0-alpha.18) (2019-11-17)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.17](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.16...@react-navigation/material-top-tabs@5.0.0-alpha.17) (2019-11-10)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.16](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.15...@react-navigation/material-top-tabs@5.0.0-alpha.16) (2019-11-08)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.15](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.14...@react-navigation/material-top-tabs@5.0.0-alpha.15) (2019-11-04)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.14](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.13...@react-navigation/material-top-tabs@5.0.0-alpha.14) (2019-10-30)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.13](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.12...@react-navigation/material-top-tabs@5.0.0-alpha.13) (2019-10-29)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.12](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.11...@react-navigation/material-top-tabs@5.0.0-alpha.12) (2019-10-15)

### Features

* initial version of native stack ([#102](https://github.com/react-navigation/navigation-ex/issues/102)) ([ba3f718](https://github.com/react-navigation/navigation-ex/commit/ba3f718))

# [5.0.0-alpha.11](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.10...@react-navigation/material-top-tabs@5.0.0-alpha.11) (2019-10-06)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.10](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.9...@react-navigation/material-top-tabs@5.0.0-alpha.10) (2019-10-03)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.9](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.8...@react-navigation/material-top-tabs@5.0.0-alpha.9) (2019-10-03)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.8](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.7...@react-navigation/material-top-tabs@5.0.0-alpha.8) (2019-09-27)

### Features

* export some more type aliases ([8b78d61](https://github.com/react-navigation/navigation-ex/commit/8b78d61))

# [5.0.0-alpha.7](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.6...@react-navigation/material-top-tabs@5.0.0-alpha.7) (2019-08-31)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.6](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.5...@react-navigation/material-top-tabs@5.0.0-alpha.6) (2019-08-29)

### Bug Fixes

* allow making params optional. fixes [#80](https://github.com/react-navigation/navigation-ex/issues/80) ([a9d4813](https://github.com/react-navigation/navigation-ex/commit/a9d4813))

# [5.0.0-alpha.5](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.4...@react-navigation/material-top-tabs@5.0.0-alpha.5) (2019-08-28)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# [5.0.0-alpha.4](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.3...@react-navigation/material-top-tabs@5.0.0-alpha.4) (2019-08-27)

### Features

* add hook to scroll to top on tab press ([9e1104c](https://github.com/react-navigation/navigation-ex/commit/9e1104c))

# [5.0.0-alpha.3](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.2...@react-navigation/material-top-tabs@5.0.0-alpha.3) (2019-08-22)

### Bug Fixes

* fix path to typescript definitions ([f182315](https://github.com/react-navigation/navigation-ex/commit/f182315))

# [5.0.0-alpha.2](https://github.com/react-navigation/navigation-ex/compare/@react-navigation/material-top-tabs@5.0.0-alpha.1...@react-navigation/material-top-tabs@5.0.0-alpha.2) (2019-08-22)

**Note:** Version bump only for package @react-navigation/material-top-tabs

# 5.0.0-alpha.1 (2019-08-21)

### Bug Fixes

* fix peer deps and add git urls ([6b4fc74](https://github.com/react-navigation/navigation-ex/commit/6b4fc74))

### Features

* add a simple stack and material tabs integration ([#39](https://github.com/react-navigation/navigation-ex/issues/39)) ([e0bee10](https://github.com/react-navigation/navigation-ex/commit/e0bee10))
* add integration for paper's bottom navigation ([f3b6d1f](https://github.com/react-navigation/navigation-ex/commit/f3b6d1f))
* integrate reanimated based stack ([#42](https://github.com/react-navigation/navigation-ex/issues/42)) ([dcf57c0](https://github.com/react-navigation/navigation-ex/commit/dcf57c0))
