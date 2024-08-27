# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 18.1.0 (2024-08-23)


### Features

* add support for backend only / multiple frontend applications [#154](https://github.com/bennymeg/nx-electron/issues/154), [#170](https://github.com/bennymeg/nx-electron/issues/170) ([dff1926](https://github.com/bennymeg/nx-electron/commit/dff1926622b0a96794778c2450bc7b97e6ebcc96))
* added build executor extra metadata option [#224](https://github.com/bennymeg/nx-electron/issues/224) ([bda9d67](https://github.com/bennymeg/nx-electron/commit/bda9d6771cb0250bb4ecff307eb3527f5e33a4a7))
* added compatibility layer ([0a15d54](https://github.com/bennymeg/nx-electron/commit/0a15d543df83005b900a06ffe2d5afed59f4c5b7))
* added extraProjects option [#154](https://github.com/bennymeg/nx-electron/issues/154) ([3d70e28](https://github.com/bennymeg/nx-electron/commit/3d70e2864b206a917b4af0cceae220a52e0c51da))
* added multi package json support [#88](https://github.com/bennymeg/nx-electron/issues/88) ([997df2a](https://github.com/bennymeg/nx-electron/commit/997df2acd1c2eeb8c1c785e1d3709d368ccad62c))
* added multi preload scripts support as per [#118](https://github.com/bennymeg/nx-electron/issues/118) ([6b28c6a](https://github.com/bennymeg/nx-electron/commit/6b28c6ab8f4a79541d02b4cbb5e8b5accfd3b3dd))
* added multi preload scripts support as per [#118](https://github.com/bennymeg/nx-electron/issues/118) ([16f9b9d](https://github.com/bennymeg/nx-electron/commit/16f9b9ded8bf95790677cc99aff5fa7ba1b79845))
* added multiple preload scripts support [#155](https://github.com/bennymeg/nx-electron/issues/155) ([1adc422](https://github.com/bennymeg/nx-electron/commit/1adc4223e764acf2f40884b25c795c897f8d5057))
* de-coupled [@angular-devkit](https://github.com/angular-devkit) from executors ([f5998b6](https://github.com/bennymeg/nx-electron/commit/f5998b691f7f27570c4a336d6718a100b1515904))
* de-coupled [@angular-devkit](https://github.com/angular-devkit) from generators ([86e0448](https://github.com/bennymeg/nx-electron/commit/86e0448d4bedcca240762b01319022c11e6c0a79))
* defined schematics and builders entry point [#128](https://github.com/bennymeg/nx-electron/issues/128) ([83525b0](https://github.com/bennymeg/nx-electron/commit/83525b08a6b9b2f346a5186c90b096556d2a425b))
* do not generate package json while serving ([209702f](https://github.com/bennymeg/nx-electron/commit/209702f799933507ecda6b635dbcedf86fe82c98))
* dont minimize node modules ([78f0fbc](https://github.com/bennymeg/nx-electron/commit/78f0fbc5c41b344dd4023181b41da2af15282544))
* initial de-coupling of [@angular-devkit](https://github.com/angular-devkit) from tests ([d210d4a](https://github.com/bennymeg/nx-electron/commit/d210d4a1e2a7b7378b3c2ebd265cbedb556112da))
* make front project optional [#170](https://github.com/bennymeg/nx-electron/issues/170) ([884181d](https://github.com/bennymeg/nx-electron/commit/884181d8dbf0c08750d338a4ae09d26fd4609b2d))
* migrate generate package json ([b0d839f](https://github.com/bennymeg/nx-electron/commit/b0d839f467037169d9e66599cd7dfefaecfc000a))
* migrate to nx v14 ([1ed6a1b](https://github.com/bennymeg/nx-electron/commit/1ed6a1b645185d5ec261845ed0cc8032aac7ab9d))
* migrate to v17 ([ac2d6d5](https://github.com/bennymeg/nx-electron/commit/ac2d6d59db6f978a6b70789389e20e43454d05d5))
* migrate to v18 ([dc491ea](https://github.com/bennymeg/nx-electron/commit/dc491ea90fbca2564551f2d0732fa03545f2263b))
* migrate to webpack 5 ([b531057](https://github.com/bennymeg/nx-electron/commit/b531057865de6ba5636d8a0913048302a7c2deeb))
* migrated from jshint to eslint ([a7297ff](https://github.com/bennymeg/nx-electron/commit/a7297ff866729566f41d57bafbe01f0085a9dbda))
* **package:** add option for overriding make options file ([adb8bb9](https://github.com/bennymeg/nx-electron/commit/adb8bb9567fafda4d949d9c588f6c05fc1884d45))
* **package:** add option for overriding make options file ([d569054](https://github.com/bennymeg/nx-electron/commit/d5690549194e64ff4929ad231b4ce153df8e971d))
* **package:** add option for overriding maker options file [#151](https://github.com/bennymeg/nx-electron/issues/151) ([198c22c](https://github.com/bennymeg/nx-electron/commit/198c22c82d19043ade793f6c0dc058c7ff98a50c))
* removed angular-devkit dependencies ([974eae2](https://github.com/bennymeg/nx-electron/commit/974eae24bc34994dc2efc0d77703212dab80e08c))
* resolve maker added file path [#169](https://github.com/bennymeg/nx-electron/issues/169) ([1506470](https://github.com/bennymeg/nx-electron/commit/1506470cd380afe5ebcef9f3e35fbdd7531859b4))
* **serve:** added rederer debugging port option [#136](https://github.com/bennymeg/nx-electron/issues/136) ([8958f32](https://github.com/bennymeg/nx-electron/commit/8958f32e060743ac77cab63bad3c45ded1e6265f))
* v12 ([f420430](https://github.com/bennymeg/nx-electron/commit/f420430759273c46e65ec05630d81eb23adfdc2d))


### Bug Fixes

*  relative path of main.preload [#277](https://github.com/bennymeg/nx-electron/issues/277) ([9e9a6db](https://github.com/bennymeg/nx-electron/commit/9e9a6db858473d1bd984fdc7ec9664794e4a9c45))
* add targets to the packaging options [#125](https://github.com/bennymeg/nx-electron/issues/125) ([cf70be6](https://github.com/bennymeg/nx-electron/commit/cf70be6361836ace667ea5f75960c27ece403869))
* added missing dependencies [#146](https://github.com/bennymeg/nx-electron/issues/146), [#166](https://github.com/bennymeg/nx-electron/issues/166) ([d37a7bd](https://github.com/bennymeg/nx-electron/commit/d37a7bd9256591819772b0c01fe231c02eda406e))
* allow optional assets in build config ([27a4a90](https://github.com/bennymeg/nx-electron/commit/27a4a90f66789ecdbdfedce54c6914488a0264f5))
* app init asset folder generation ([bbe1661](https://github.com/bennymeg/nx-electron/commit/bbe1661234b9e971ea6c2b13c44a4f81208819ba))
* app init asset folder generation ([4acace3](https://github.com/bennymeg/nx-electron/commit/4acace3b86764beb2c1312a7e8bb8a57cbf5a033))
* app init asset folder generation (2) ([801f653](https://github.com/bennymeg/nx-electron/commit/801f653f1b3bf8e627de393b59ef72d457fcfbc6))
* build script path ([f89a13b](https://github.com/bennymeg/nx-electron/commit/f89a13b586e16b5d3aec4b913494e4e7dd1b0232))
* bump version ([56ec734](https://github.com/bennymeg/nx-electron/commit/56ec734fd854de6c8e9a7b5b59051081e341c4c8))
* deps audit ([22d8d00](https://github.com/bennymeg/nx-electron/commit/22d8d00dff56dc105c4a7657310e41a441e29b3a))
* electron MessageBoxOptionsc type error ([1ffacd9](https://github.com/bennymeg/nx-electron/commit/1ffacd9e48d79ddadacbc3586c674e88be13606b))
* empty maker option path ([d659149](https://github.com/bennymeg/nx-electron/commit/d659149d9cefd9c6c15c429b15d26f69842091fa))
* esm import [#288](https://github.com/bennymeg/nx-electron/issues/288) ([ca61447](https://github.com/bennymeg/nx-electron/commit/ca614479436a41ccda253fa2dd83c3b4121068a3))
* **executors:** nx16 issues ([99761fd](https://github.com/bennymeg/nx-electron/commit/99761fd5dede44b12dcd9fcf575c395b7c37750e))
* fixed build script ([d88fd0c](https://github.com/bennymeg/nx-electron/commit/d88fd0c3ab02bf9f9d2f47f2a4cdea52b4e059ff))
* fixed build script ([8a82b4c](https://github.com/bennymeg/nx-electron/commit/8a82b4ce8b75849f3dcf5f12c505fb0f69d2a635))
* generate package json ([581d9f2](https://github.com/bennymeg/nx-electron/commit/581d9f27d57c390f3571e377678c0736f1ba065e))
* generator specs ([0a27d1e](https://github.com/bennymeg/nx-electron/commit/0a27d1ece5c18fa577511e805cacbfee425391b3))
* **generator:** resolve type issue in update events template ([8541981](https://github.com/bennymeg/nx-electron/commit/854198182b3e76f817c51beb1260ba3dc2eae61d))
* migration ([130865f](https://github.com/bennymeg/nx-electron/commit/130865f2693467097ede468e21604639159b8f36))
* moved global package.json down in hierarchy [#167](https://github.com/bennymeg/nx-electron/issues/167) ([7a72016](https://github.com/bennymeg/nx-electron/commit/7a720167d81128f0ed5e4d9a5afc767711259099))
* nx16 issues ([014a29a](https://github.com/bennymeg/nx-electron/commit/014a29a0216c849fda5637faaa0b17a89ece4f48))
* nx17 issues ([80b6dad](https://github.com/bennymeg/nx-electron/commit/80b6dada9e207fa98df794039a8868df4ae6b4e7))
* nx17 issues ([e896a75](https://github.com/bennymeg/nx-electron/commit/e896a757c6b53e5e9718ab137cc5aac6166cc831))
* old migration ([bb377e9](https://github.com/bennymeg/nx-electron/commit/bb377e97216f953a80f7bbfed48aa115824795ed))
* output file names ([e03a5c8](https://github.com/bennymeg/nx-electron/commit/e03a5c85264f963d3c2e23ac733c0aa1b4562be4))
* package projects files list [#154](https://github.com/bennymeg/nx-electron/issues/154), [#170](https://github.com/bennymeg/nx-electron/issues/170) ([41f3676](https://github.com/bennymeg/nx-electron/commit/41f36760471cc8aa8f3061e52c4a493d2e1a7aba))
* packager returns promise instead of observable [#135](https://github.com/bennymeg/nx-electron/issues/135) ([753997a](https://github.com/bennymeg/nx-electron/commit/753997a36a73083c6b76ff20cdcd4145f9a4094e))
* preload file regex pattern as per [#121](https://github.com/bennymeg/nx-electron/issues/121) ([b9a7da8](https://github.com/bennymeg/nx-electron/commit/b9a7da8f8a5de15ec0dd9e83a414e4fa7214aa47))
* preload file regex pattern as per [#121](https://github.com/bennymeg/nx-electron/issues/121) ([285f196](https://github.com/bennymeg/nx-electron/commit/285f19657c93bba45e2a2876b5465fbbb68e0ddf))
* readme typo ([c443e4e](https://github.com/bennymeg/nx-electron/commit/c443e4eab2641d3cd46834be4322e32c11515de1))
* readme typo ([9b323c8](https://github.com/bennymeg/nx-electron/commit/9b323c87dce36324cc42c85ab15d0622b7ce7f71))
* readTsConfig import ([7929a84](https://github.com/bennymeg/nx-electron/commit/7929a849b69627c9864157459543caeaf8cd19e8))
* relative preload script build ([d641c17](https://github.com/bennymeg/nx-electron/commit/d641c17967f6848a37be7347745d185bb7f83108))
* remove file extension from preload webpack entry ([b23abba](https://github.com/bennymeg/nx-electron/commit/b23abba69b43dfaa302dcdeeaa3f3282d3afa304))
* removed unused dependencies from v13 ([ab450d8](https://github.com/bennymeg/nx-electron/commit/ab450d886cca21089712f7b738233a55333aa376))
* revert adding targets packaging options [#125](https://github.com/bennymeg/nx-electron/issues/125) ([5beb469](https://github.com/bennymeg/nx-electron/commit/5beb469ae5c92716fe4cb3fde4fdd31c953a5d8f))
* schema $id field ([40e58f1](https://github.com/bennymeg/nx-electron/commit/40e58f17f3d60523fc485bc62587526b181b563a))
* switch packager default source back to apps ([7f9f740](https://github.com/bennymeg/nx-electron/commit/7f9f74079b7cd45d0b83c0033d66acdb762c8a4c))
* tao appRoot deprecation ([e51bbc3](https://github.com/bennymeg/nx-electron/commit/e51bbc34db233e31bf0894dc05b87d9d9ca6f783))
* temporarly added angular-devkit ([6abd615](https://github.com/bennymeg/nx-electron/commit/6abd61509031ca7f22b28a5e49a7b9446718d89c))
* **tsconfig:** updates extends to nx default ([43d78e5](https://github.com/bennymeg/nx-electron/commit/43d78e576ab227c444bfb9356873b826b03b8e8c))
* update post install script instead of overwriting it. closes [#97](https://github.com/bennymeg/nx-electron/issues/97) ([de69c98](https://github.com/bennymeg/nx-electron/commit/de69c986598a8f8e7147d16db1a03bdeb7460095))
* update post install script instead of overwriting it. closes [#97](https://github.com/bennymeg/nx-electron/issues/97) ([b3a8846](https://github.com/bennymeg/nx-electron/commit/b3a8846425058a0a9ed6fbf6d8e8ce6bad2f75b0))
* updated installed dependecies versions [#66](https://github.com/bennymeg/nx-electron/issues/66) ([6c61541](https://github.com/bennymeg/nx-electron/commit/6c61541a0407905832e26965ce328c338116beaa))
* updated path delimeters for consistency ([5e90a9f](https://github.com/bennymeg/nx-electron/commit/5e90a9fb23c329440d200f3ecfd95572575bacb4))

### [14.0.2](https://github.com/bennymeg/nx-electron/compare/v14.0.0...v14.0.2) (2023-02-01)


### Bug Fixes

* removed unused dependencies from v13 ([ab450d8](https://github.com/bennymeg/nx-electron/commit/ab450d886cca21089712f7b738233a55333aa376))

## [14.0.0](https://github.com/bennymeg/nx-electron/compare/v13.2.3...v14.0.0) (2023-02-01)


### Features

* add support for backend only / multiple frontend applications [#154](https://github.com/bennymeg/nx-electron/issues/154), [#170](https://github.com/bennymeg/nx-electron/issues/170) ([dff1926](https://github.com/bennymeg/nx-electron/commit/dff1926622b0a96794778c2450bc7b97e6ebcc96))
* added extraProjects option [#154](https://github.com/bennymeg/nx-electron/issues/154) ([3d70e28](https://github.com/bennymeg/nx-electron/commit/3d70e2864b206a917b4af0cceae220a52e0c51da))
* dont minimize node modules ([78f0fbc](https://github.com/bennymeg/nx-electron/commit/78f0fbc5c41b344dd4023181b41da2af15282544))
* make front project optional [#170](https://github.com/bennymeg/nx-electron/issues/170) ([884181d](https://github.com/bennymeg/nx-electron/commit/884181d8dbf0c08750d338a4ae09d26fd4609b2d))
* migrate to nx v14 ([1ed6a1b](https://github.com/bennymeg/nx-electron/commit/1ed6a1b645185d5ec261845ed0cc8032aac7ab9d))


### Bug Fixes

* package projects files list [#154](https://github.com/bennymeg/nx-electron/issues/154), [#170](https://github.com/bennymeg/nx-electron/issues/170) ([41f3676](https://github.com/bennymeg/nx-electron/commit/41f36760471cc8aa8f3061e52c4a493d2e1a7aba))
* tao appRoot deprecation ([e51bbc3](https://github.com/bennymeg/nx-electron/commit/e51bbc34db233e31bf0894dc05b87d9d9ca6f783))

### [13.2.3](https://github.com/bennymeg/nx-electron/compare/v13.2.2...v13.2.3) (2023-01-08)

### [13.2.2](https://github.com/bennymeg/nx-electron/compare/v13.2.1...v13.2.2) (2023-01-08)


### Bug Fixes

* build script path ([f89a13b](https://github.com/bennymeg/nx-electron/commit/f89a13b586e16b5d3aec4b913494e4e7dd1b0232))

### [13.2.1](https://github.com/bennymeg/nx-electron/compare/v13.2.0...v13.2.1) (2022-06-01)

## [13.2.0](https://github.com/bennymeg/nx-electron/compare/v13.1.0...v13.2.0) (2022-06-01)


### Features

* resolve maker added file path [#169](https://github.com/bennymeg/nx-electron/issues/169) ([1506470](https://github.com/bennymeg/nx-electron/commit/1506470cd380afe5ebcef9f3e35fbdd7531859b4))


### Bug Fixes

* added missing dependencies [#146](https://github.com/bennymeg/nx-electron/issues/146), [#166](https://github.com/bennymeg/nx-electron/issues/166) ([d37a7bd](https://github.com/bennymeg/nx-electron/commit/d37a7bd9256591819772b0c01fe231c02eda406e))
* moved global package.json down in hierarchy [#167](https://github.com/bennymeg/nx-electron/issues/167) ([7a72016](https://github.com/bennymeg/nx-electron/commit/7a720167d81128f0ed5e4d9a5afc767711259099))

## [13.1.0](https://github.com/bennymeg/nx-electron/compare/v12.1.0...v13.1.0) (2022-05-16)


### Features

* added multiple preload scripts support [#155](https://github.com/bennymeg/nx-electron/issues/155) ([1adc422](https://github.com/bennymeg/nx-electron/commit/1adc4223e764acf2f40884b25c795c897f8d5057))
* do not generate package json while serving ([209702f](https://github.com/bennymeg/nx-electron/commit/209702f799933507ecda6b635dbcedf86fe82c98))
* migrate generate package json ([b0d839f](https://github.com/bennymeg/nx-electron/commit/b0d839f467037169d9e66599cd7dfefaecfc000a))
* **package:** add option for overriding maker options file [#151](https://github.com/bennymeg/nx-electron/issues/151) ([198c22c](https://github.com/bennymeg/nx-electron/commit/198c22c82d19043ade793f6c0dc058c7ff98a50c))
* **serve:** added rederer debugging port option [#136](https://github.com/bennymeg/nx-electron/issues/136) ([8958f32](https://github.com/bennymeg/nx-electron/commit/8958f32e060743ac77cab63bad3c45ded1e6265f))


### Bug Fixes

* app init asset folder generation ([bbe1661](https://github.com/bennymeg/nx-electron/commit/bbe1661234b9e971ea6c2b13c44a4f81208819ba))
* app init asset folder generation ([4acace3](https://github.com/bennymeg/nx-electron/commit/4acace3b86764beb2c1312a7e8bb8a57cbf5a033))
* app init asset folder generation (2) ([801f653](https://github.com/bennymeg/nx-electron/commit/801f653f1b3bf8e627de393b59ef72d457fcfbc6))
* deps audit ([22d8d00](https://github.com/bennymeg/nx-electron/commit/22d8d00dff56dc105c4a7657310e41a441e29b3a))
* empty maker option path ([d659149](https://github.com/bennymeg/nx-electron/commit/d659149d9cefd9c6c15c429b15d26f69842091fa))
* remove file extension from preload webpack entry ([b23abba](https://github.com/bennymeg/nx-electron/commit/b23abba69b43dfaa302dcdeeaa3f3282d3afa304))
* temporarly added angular-devkit ([6abd615](https://github.com/bennymeg/nx-electron/commit/6abd61509031ca7f22b28a5e49a7b9446718d89c))
* updated path delimeters for consistency ([5e90a9f](https://github.com/bennymeg/nx-electron/commit/5e90a9fb23c329440d200f3ecfd95572575bacb4))

## [12.1.0](https://github.com/bennymeg/nx-electron/compare/v12.0.0-beta.0...v12.1.0) (2022-02-04)


### Features

* defined schematics and builders entry point [#128](https://github.com/bennymeg/nx-electron/issues/128) ([83525b0](https://github.com/bennymeg/nx-electron/commit/83525b08a6b9b2f346a5186c90b096556d2a425b))
* v12 ([f420430](https://github.com/bennymeg/nx-electron/commit/f420430759273c46e65ec05630d81eb23adfdc2d))


### Bug Fixes

* add targets to the packaging options [#125](https://github.com/bennymeg/nx-electron/issues/125) ([cf70be6](https://github.com/bennymeg/nx-electron/commit/cf70be6361836ace667ea5f75960c27ece403869))
* bump version ([56ec734](https://github.com/bennymeg/nx-electron/commit/56ec734fd854de6c8e9a7b5b59051081e341c4c8))
* packager returns promise instead of observable [#135](https://github.com/bennymeg/nx-electron/issues/135) ([753997a](https://github.com/bennymeg/nx-electron/commit/753997a36a73083c6b76ff20cdcd4145f9a4094e))
* revert adding targets packaging options [#125](https://github.com/bennymeg/nx-electron/issues/125) ([5beb469](https://github.com/bennymeg/nx-electron/commit/5beb469ae5c92716fe4cb3fde4fdd31c953a5d8f))

## [12.0.0](https://github.com/bennymeg/nx-electron/compare/v11.4.1...v12.0.0) (2021-11-24)


### Features

* added compatibility layer ([0a15d54](https://github.com/bennymeg/nx-electron/commit/0a15d543df83005b900a06ffe2d5afed59f4c5b7))
* added multi package json support [#88](https://github.com/bennymeg/nx-electron/issues/88) ([997df2a](https://github.com/bennymeg/nx-electron/commit/997df2acd1c2eeb8c1c785e1d3709d368ccad62c))
* added multi preload scripts support as per [#118](https://github.com/bennymeg/nx-electron/issues/118) ([6b28c6a](https://github.com/bennymeg/nx-electron/commit/6b28c6ab8f4a79541d02b4cbb5e8b5accfd3b3dd))
* de-coupled [@angular-devkit](https://github.com/angular-devkit) from executors ([f5998b6](https://github.com/bennymeg/nx-electron/commit/f5998b691f7f27570c4a336d6718a100b1515904))
* de-coupled [@angular-devkit](https://github.com/angular-devkit) from generators ([86e0448](https://github.com/bennymeg/nx-electron/commit/86e0448d4bedcca240762b01319022c11e6c0a79))
* initial de-coupling of [@angular-devkit](https://github.com/angular-devkit) from tests ([d210d4a](https://github.com/bennymeg/nx-electron/commit/d210d4a1e2a7b7378b3c2ebd265cbedb556112da))
* **package:** add option for overriding make options file ([adb8bb9](https://github.com/bennymeg/nx-electron/commit/adb8bb9567fafda4d949d9c588f6c05fc1884d45))
* removed angular-devkit dependencies ([974eae2](https://github.com/bennymeg/nx-electron/commit/974eae24bc34994dc2efc0d77703212dab80e08c))


### Bug Fixes

* fixed build script ([d88fd0c](https://github.com/bennymeg/nx-electron/commit/d88fd0c3ab02bf9f9d2f47f2a4cdea52b4e059ff))
* fixed build script ([8a82b4c](https://github.com/bennymeg/nx-electron/commit/8a82b4ce8b75849f3dcf5f12c505fb0f69d2a635))
* migration ([130865f](https://github.com/bennymeg/nx-electron/commit/130865f2693467097ede468e21604639159b8f36))
* preload file regex pattern as per [#121](https://github.com/bennymeg/nx-electron/issues/121) ([b9a7da8](https://github.com/bennymeg/nx-electron/commit/b9a7da8f8a5de15ec0dd9e83a414e4fa7214aa47))
* schema $id field ([40e58f1](https://github.com/bennymeg/nx-electron/commit/40e58f17f3d60523fc485bc62587526b181b563a))
* update post install script instead of overwriting it. closes [#97](https://github.com/bennymeg/nx-electron/issues/97) ([de69c98](https://github.com/bennymeg/nx-electron/commit/de69c986598a8f8e7147d16db1a03bdeb7460095))
