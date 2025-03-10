# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

### [0.7.13](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.12...@endo/compartment-mapper@0.7.13) (2022-09-27)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.7.12](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.11...@endo/compartment-mapper@0.7.12) (2022-09-14)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.7.11](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.10...@endo/compartment-mapper@0.7.11) (2022-08-26)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.7.10](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.9...@endo/compartment-mapper@0.7.10) (2022-08-26)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.7.9](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.8...@endo/compartment-mapper@0.7.9) (2022-08-25)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.7.8](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.7...@endo/compartment-mapper@0.7.8) (2022-08-23)


### Bug Fixes

* **compartment-mapper:** avoid mislabeling cjs files as esm based on type field ([5a6a501](https://github.com/endojs/endo/commit/5a6a501f14f53170d047f847fee7d08674e72f23))



### [0.7.7](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.6...@endo/compartment-mapper@0.7.7) (2022-06-28)


### Features

* **compartment-mapper:** dancing skeleton require.resolve implementation ([ba1de8e](https://github.com/endojs/endo/commit/ba1de8e6f6225a9e16bd19fb2a4ec77badf457f5))
* **compartment-mapper:** implement passing values in import.meta.url ([d6294f6](https://github.com/endojs/endo/commit/d6294f6832f978eaa7af94fee4496d76bd35a927))
* **compartment-mapper:** implement require.resolve as an external configuration item ([45054de](https://github.com/endojs/endo/commit/45054dec37971da253773dbb91debddd0f56d0d6))
* **compartment-mapper:** move require.resolve implementation to readPowers ([e841f74](https://github.com/endojs/endo/commit/e841f74ad508061c2661963ae2876669be966f32))
* add the foundations for support of import.meta ([36f6449](https://github.com/endojs/endo/commit/36f644998c21f6333268707555b97938ff0fff08))
* call importMetaHook on instantiation if import.meta uttered by module ([23e8c40](https://github.com/endojs/endo/commit/23e8c405e0be823c728f8af1a6db9607e21f2f74))


### Bug Fixes

* **compartment-mapper:** adapt require.resolve assertion to Windows also ([58e1064](https://github.com/endojs/endo/commit/58e10642f4f099d7b8132f20ff59a85ed6a9443c))
* **compartment-mapper:** importMeta always an empty object in bundler ([e9f809a](https://github.com/endojs/endo/commit/e9f809a0e3242421d9c32388f2bc885eb8d9510e))
* rename meta to importMeta, fix detection to detect import.meta not import.meta.something ([c61a862](https://github.com/endojs/endo/commit/c61a862c9f4354f0e6d86d8c8efaa826840a6efd))



### [0.7.6](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.5...@endo/compartment-mapper@0.7.6) (2022-06-11)


### Features

* **compartment-mapper:** Archives retain compartments only for retained modules ([ee2e6e1](https://github.com/endojs/endo/commit/ee2e6e1d415d6cd5795030a978650f71fcc80cbb))
* **compartment-mapper:** Support text and bytes asset module types ([acc828c](https://github.com/endojs/endo/commit/acc828cf74308b7cdcf000f7492a53e3135bdfd3))
* **compartment-mapper:** Thread diagnostic name more thorougly ([d546823](https://github.com/endojs/endo/commit/d54682363790dcd9123b135d8784ffc75508fec0))
* **compartment-mapper:** Use package.json files in nested folders of a package when determining module type ([4b1c6f4](https://github.com/endojs/endo/commit/4b1c6f4575f2b3ad24a0b4bb3a68a59a4d0dc6d9))


### Bug Fixes

* **compartment-mapper:** Package exports may be absolute ([5a8a893](https://github.com/endojs/endo/commit/5a8a893b9f9d4375661fae597c158a0bbf258785))
* **compartment-mapper:** provide correct values for __dirname __filename for cjs compatibility ([#1155](https://github.com/endojs/endo/issues/1155)) ([43fdf69](https://github.com/endojs/endo/commit/43fdf69f0de91fbb4e48c66199067a2fbc6738aa))
* **compartment-mapper:** relativize all exports from package.json - undo the change allowing reexports of dependencies by just stating them in package.json "exports" field ([ceb1790](https://github.com/endojs/endo/commit/ceb17903e1926fb38ee72cdd26a332efde9d12b8))
* **compartment-mapper:** Stabilize hashes in face of layout changes ([75a5db4](https://github.com/endojs/endo/commit/75a5db489f495d286bbd8c5932e4db2b57c136b5)), closes [#919](https://github.com/endojs/endo/issues/919)



### [0.7.5](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.4...@endo/compartment-mapper@0.7.5) (2022-04-15)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.7.4](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.3...@endo/compartment-mapper@0.7.4) (2022-04-14)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.7.3](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.2...@endo/compartment-mapper@0.7.3) (2022-04-13)


### Bug Fixes

* Revert dud release ([c8a7101](https://github.com/endojs/endo/commit/c8a71017d8d7af10a97909c9da9c5c7e59aed939))



### [0.7.2](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.1...@endo/compartment-mapper@0.7.2) (2022-04-12)


### Features

* **compartment-mapper:** defer import errors based on parser support declaration ([cf074aa](https://github.com/endojs/endo/commit/cf074aab007a3af16ad7ac25b6dc1bd119d6d1b7))
* **compartment-mapper:** proper default export implementation for cjs with import and require compatibility ([30cbaa8](https://github.com/endojs/endo/commit/30cbaa8cb79b906742a9f5c1854b22fe506b0575))
* **compartment-mapper:** support for defineProperty on exports with getters ([4764487](https://github.com/endojs/endo/commit/4764487f149a9af225128cec75d557e35d20bf60))


### Bug Fixes

* **compartment-mapper:** add support for alternatives in exports defnitions ([#1134](https://github.com/endojs/endo/issues/1134)) ([6663f25](https://github.com/endojs/endo/commit/6663f255de7a514aac0f0081eaa99de880298f73))
* **compartment-mapper:** Avoid some property override pitfalls ([b4efabe](https://github.com/endojs/endo/commit/b4efabee1d13b13af782ae4442daac4691c721b4))
* **compartment-mapper:** Fix "module" property in package.json ([68395a2](https://github.com/endojs/endo/commit/68395a2b071856dd0dfdf0a1c7c3d57082d7803e))
* **compartment-mapper:** handle passing and reading exports reference ([#1142](https://github.com/endojs/endo/issues/1142)) ([3b7584a](https://github.com/endojs/endo/commit/3b7584a9bf6b3ba5b4e3f839c230cd07f022d33e))
* **compartment-mapper:** propagate parse-cjs changes to parse-pre-cjs, remove async from execute in parse-pre-cjs ([8ac94b8](https://github.com/endojs/endo/commit/8ac94b85a11539155929569a86882a05fc146ad3))
* **compartment-mapper:** Remove stale note ([85a4eb8](https://github.com/endojs/endo/commit/85a4eb81f65dbe4ba746014fad41ab86d1f70167))
* **compartment-mapper:** there's more benefit to keeping __esModule flag than not  ([#1145](https://github.com/endojs/endo/issues/1145)) ([c769447](https://github.com/endojs/endo/commit/c76944794ebbe9e0ec0c8896e5ae9cce2fb17cb3))
* **endo:** Ensure conditions include default, import, and endo ([1361abd](https://github.com/endojs/endo/commit/1361abd8c732596d192ecef6a039eda98b4ee563))
* **ses:** avoid cache corruption when execute() throws ([1d9c17b](https://github.com/endojs/endo/commit/1d9c17b4c4a5ed1450cddd996bd948dd59c80bf6))



### [0.7.1](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.7.0...@endo/compartment-mapper@0.7.1) (2022-03-07)

**Note:** Version bump only for package @endo/compartment-mapper





## [0.7.0](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.7...@endo/compartment-mapper@0.7.0) (2022-03-02)


### ⚠ BREAKING CHANGES

* **compartment-mapper:** * Previously, `loadArchive` and `parseArchive`, when given a `computeSha512`, would accept just about any archive. Hash integrity checks for any used module occurred only after a request to import them. With this new version, all archives must use every file they contain and must pass hash integrity checks during the load or parse phase.  Consequently, if an archive requires any built-in modules ("exits"), these must be mentioned with the `modules` option to `loadArchive` or `parseArchive`, as an object whose keys are the names of the expected modules.

### Features

* **compartment-mapper:** Add makeAndHashArchive ([ffbe0d5](https://github.com/endojs/endo/commit/ffbe0d5b7ddb4c4e8de08ecc0735f2140b62e3a4))
* **compartment-mapper:** Pre-load for archive integrity checks ([3c28ddc](https://github.com/endojs/endo/commit/3c28ddc336d2acac4dde5cdf32a27c33c713bc00)), closes [#3859](https://github.com/endojs/endo/issues/3859)



### [0.6.7](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.6...@endo/compartment-mapper@0.6.7) (2022-02-20)


### Features

* **compartment-mapper:** parseArchive return hash ([1306c7d](https://github.com/endojs/endo/commit/1306c7d95b2a90b18217829dac368e1089793366))
* **compartment-mapper:** Validate compartment maps ([4204058](https://github.com/endojs/endo/commit/4204058428a6fcb04b68fd0151fd5955c94ae80a))



### [0.6.6](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.5...@endo/compartment-mapper@0.6.6) (2022-02-18)


### Bug Fixes

* Address TypeScript recommendations ([2d1e1e0](https://github.com/endojs/endo/commit/2d1e1e0bdd385a514315be908c33b8f8eb157295))
* Make jsconfigs less brittle ([861ca32](https://github.com/endojs/endo/commit/861ca32a72f0a48410fd93b1cbaaad9139590659))
* Make sure lint:type runs correctly in CI ([a520419](https://github.com/endojs/endo/commit/a52041931e72cb7b7e3e21dde39c099cc9f262b0))
* Unify TS version to ~4.2 ([5fb173c](https://github.com/endojs/endo/commit/5fb173c05c9427dca5adfe66298c004780e8b86c))
* **compartment-mapper:** change how parse-cjs.js treats exports to align with behavior of cjs in Node.js; make execute synchronous ([d1eb363](https://github.com/endojs/endo/commit/d1eb36326d487c61d111dc1edea446b1a5e0cfce))



### [0.6.5](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.4...@endo/compartment-mapper@0.6.5) (2022-01-31)


### Bug Fixes

* **compartment-mapper:** Needless genericity considered harmful ([#1026](https://github.com/endojs/endo/issues/1026)) ([77e3d91](https://github.com/endojs/endo/commit/77e3d91364782dbd293c5dbc64f6ef29942369f0))



### [0.6.4](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.3...@endo/compartment-mapper@0.6.4) (2022-01-27)


### Bug Fixes

* Publish all materials consistently ([#1021](https://github.com/endojs/endo/issues/1021)) ([a2c74d9](https://github.com/endojs/endo/commit/a2c74d9de68a325761d62e1b2187a117ef884571))



### [0.6.3](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.2...@endo/compartment-mapper@0.6.3) (2022-01-25)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.6.2](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.1...@endo/compartment-mapper@0.6.2) (2022-01-23)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.6.1](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.6.0...@endo/compartment-mapper@0.6.1) (2021-12-14)

**Note:** Version bump only for package @endo/compartment-mapper





## [0.6.0](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.5.6...@endo/compartment-mapper@0.6.0) (2021-12-08)


### Features

* **compartment-mapper:** Thread url into power makers for Windows support ([fedcc8c](https://github.com/endojs/endo/commit/fedcc8c2b1204a76af3ff8211ea7033411c657f8))


### Bug Fixes

* Avoid eslint globs for Windows ([4b4f3cc](https://github.com/endojs/endo/commit/4b4f3ccaf3f5e8d53faefb4264db343dd603bf80))
* **compartment-mapper:** prettier bundle code, with some reduction ([dc9ccaa](https://github.com/endojs/endo/commit/dc9ccaae184d6346d11d90df46a2ed46c3ad3480))
* **static-module-record:** cleaner Babel codegen ([6e22569](https://github.com/endojs/endo/commit/6e22569b0c3f56e9f78d59943235b97ba0429921))



### [0.5.6](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.5.5...@endo/compartment-mapper@0.5.6) (2021-11-16)


### Features

* **compartment-mapper:** Add hooks for sourceURL ([#932](https://github.com/endojs/endo/issues/932)) ([a7b42ae](https://github.com/endojs/endo/commit/a7b42ae2388b232f7daa099495ba11f385010fd1))
* **compartment-mapper:** Archive source URL suffixes ([#930](https://github.com/endojs/endo/issues/930)) ([0dfb83e](https://github.com/endojs/endo/commit/0dfb83ebc9221d15475aabe430645f5ac5d17e71))



### [0.5.5](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.5.4...@endo/compartment-mapper@0.5.5) (2021-11-02)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.5.4](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.5.3...@endo/compartment-mapper@0.5.4) (2021-10-15)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.5.3](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.5.2...@endo/compartment-mapper@0.5.3) (2021-09-18)


### Bug Fixes

* **compartment-mapper:** Reduce pre-cjs dependence on URL ([#894](https://github.com/endojs/endo/issues/894)) ([b9f6dc0](https://github.com/endojs/endo/commit/b9f6dc07f249cb47866f623728faf0b74d509fd2))



### [0.5.2](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.5.1...@endo/compartment-mapper@0.5.2) (2021-08-14)

**Note:** Version bump only for package @endo/compartment-mapper





### [0.5.1](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.5.0...@endo/compartment-mapper@0.5.1) (2021-08-13)


### Features

* **compartment-mapper:** Support reflexive imports ([#861](https://github.com/endojs/endo/issues/861)) ([09e5485](https://github.com/endojs/endo/commit/09e548558d14d6a7bff17c3b2df686122218d345))



## [0.5.0](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.4.1...@endo/compartment-mapper@0.5.0) (2021-07-22)


### ⚠ BREAKING CHANGES

* Update preamble for SES StaticModuleRecord

### Features

* **compartment-mapper:** Consistent hashing ([fba461f](https://github.com/endojs/endo/commit/fba461f2786e1f9569c1bfb839e03d45cee7d2a6))


### Bug Fixes

* Update preamble for SES StaticModuleRecord ([790ed01](https://github.com/endojs/endo/commit/790ed01f0aa73ff2d232e69c9323ee0bb448c2b0))
* **compartment-map:** Restore test fixture maker and support for exit modules from archives ([0ccc277](https://github.com/endojs/endo/commit/0ccc277e2083d89aaf97f70a0900fe6692a4ee45))
* **compartment-mapper:** Adjust bundle calling convention for preamble ([5a43a8e](https://github.com/endojs/endo/commit/5a43a8ea8759a223f2dedf88a1ea7b1e276b81e3))



### [0.4.1](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.4.0...@endo/compartment-mapper@0.4.1) (2021-06-20)


### Bug Fixes

* **compartment-mapper:** Export types properly ([54be905](https://github.com/endojs/endo/commit/54be905895e9ebdae69b7542f6c4d7ff3660c2ea))
* **compartment-mapper:** Propagate explicit types ([289c906](https://github.com/endojs/endo/commit/289c906173a450d608f816ab83e702435ad80057))



## [0.4.0](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.3.2...@endo/compartment-mapper@0.4.0) (2021-06-16)


### ⚠ BREAKING CHANGES

* **compartment-mapper:** Required exits on archives

### Features

* **compartment-mapper:** Developer dependencies ([44f86cd](https://github.com/endojs/endo/commit/44f86cd6788b8f6bdc5492619866995ede73488b))
* **compartment-mapper:** Required exits on archives ([f5e6378](https://github.com/endojs/endo/commit/f5e6378f4c4dc2c017d3c94544a3e22d762ade27))


### Bug Fixes

* **compartment-mapper:** Missing node-powers from published files ([277fd47](https://github.com/endojs/endo/commit/277fd47e359ee90d31a521fadbac90a4853649f4))



### [0.3.2](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.3.1...@endo/compartment-mapper@0.3.2) (2021-06-14)


### Features

* **compartment-mapper:** Add actionable hint to linker error ([4dbe87b](https://github.com/endojs/endo/commit/4dbe87b40007d5ce9a084b4cf94ac254d9bd9e7a))
* **compartment-mapper:** Add Node.js power adapter ([fd16355](https://github.com/endojs/endo/commit/fd1635517ce8260d3dc2766c2c39a599f58f9a0c))
* **compartment-mapper:** Follow symbolic links ([ae553a4](https://github.com/endojs/endo/commit/ae553a469800f548975b0e1ba5bb2c63455a87f4))



### [0.3.1](https://github.com/endojs/endo/compare/@endo/compartment-mapper@0.3.0...@endo/compartment-mapper@0.3.1) (2021-06-06)

**Note:** Version bump only for package @endo/compartment-mapper





## 0.3.0 (2021-06-02)


### ⚠ BREAKING CHANGES

* **compartment-mapper:** No longer supports direct use from CommonJS
* **static-module-record:** Emphasize RESM/NESM compatibility over CJS/UMD
* **compartment-mapper:** Lean on RESM/NESM interoperability
* **compartment-mapper:** Rearrange entry point modules
* **compartment-mapper:** Cleanly separate StaticModuleRecord dependency (#698)
* **compartment-mapper:** Refresh zip fixture
* **compartment-mapper:** Temporarily disable CommonJS
* **compartment-mapper:** Rename endowments to globals
* **compartment-mapper:** Import options bags and thread transforms

### Features

* **compartment-mapper:** Add module transforms ([#625](https://github.com/endojs/endo/issues/625)) ([0a0fc02](https://github.com/endojs/endo/commit/0a0fc02c400ebf68dfdf942354c548db6a6058f7))
* **compartment-mapper:** Blanket in TypeScript definitions ([f850ed8](https://github.com/endojs/endo/commit/f850ed87fcdf943a1e347ffbe218144bee4151e8))
* **compartment-mapper:** Improve archive parser errors ([c5887d8](https://github.com/endojs/endo/commit/c5887d8c13406b9da64c5537e87b3cf29ca8893e))
* **compartment-mapper:** Introduce rudimentary bundler ([2bcddb1](https://github.com/endojs/endo/commit/2bcddb10845183074dbf5c709d9a70dadbce6dcb))
* **compartment-mapper:** Pivot to CommonJS lexical analyzer ([e68a991](https://github.com/endojs/endo/commit/e68a991a54843a447cdd2c31a390e87192a36d04))
* **compartment-mapper:** Precompiled ESM ([eb2fcc4](https://github.com/endojs/endo/commit/eb2fcc40fb5a51a433488ac111bd62bbed3655b0)), closes [#673](https://github.com/endojs/endo/issues/673)
* **compartment-mapper:** Reenable CommonJS ([e76d95e](https://github.com/endojs/endo/commit/e76d95efd7aaa367c64d4e63e0983bb47f754832))
* **compartment-mapper:** Thread compartment constructor ([f3248f2](https://github.com/endojs/endo/commit/f3248f27dc61f568f7f1a5ea61e35e04fa6887ea))
* **compartment-mapper:** Thread global lexicals ([f92379a](https://github.com/endojs/endo/commit/f92379a4bb45ff4ef5b64eea998d5d5323a3434e))
* **compartment-mapper:** Update packaging for RESM/NESM bridge and reorg under [@endo](https://github.com/endo) ([5b7c24e](https://github.com/endojs/endo/commit/5b7c24e1a473b5aa9e1397f6ca338bea8ed82984))
* **endo:** Freeze all global objects ([#631](https://github.com/endojs/endo/issues/631)) ([83b5db4](https://github.com/endojs/endo/commit/83b5db4a2b64fcf1cb8927698e0d5942439eec27))
* **ses:** Allow import and eval methods ([#669](https://github.com/endojs/endo/issues/669)) ([505a7d7](https://github.com/endojs/endo/commit/505a7d7149c36825a00c9fe3795d0f1588035dde))


### Bug Fixes

* Regularize format of NEWS.md ([0ec29b3](https://github.com/endojs/endo/commit/0ec29b34a18b17cc6b90e5a46575e634714e978e))
* **compartment-mapper:** Deterministic archives ([577cdd8](https://github.com/endojs/endo/commit/577cdd81daa56ccffe4dbed4470f76077eeb3d71))
* **compartment-mapper:** Different tack to evade SES import censor ([#513](https://github.com/endojs/endo/issues/513)) ([5df2c0e](https://github.com/endojs/endo/commit/5df2c0e2c185ee71d1ebfd3b2e01e84ebfcf6c56))
* **compartment-mapper:** Dodge named reexport as bug in tests ([ad8c661](https://github.com/endojs/endo/commit/ad8c6618887ecf1d96522b1370094bde1c87f5f0))
* **compartment-mapper:** Elide source URL from archived MJS ([ecc65b5](https://github.com/endojs/endo/commit/ecc65b51243f942771a11e253e1192004c2301f7))
* **compartment-mapper:** Generate strict bundle ([c1e3a90](https://github.com/endojs/endo/commit/c1e3a908f4a220edc179104b88f2ea8ad375bdfb))
* **compartment-mapper:** Remove extraneous internal exports ([d8eb6ac](https://github.com/endojs/endo/commit/d8eb6ac09936d03772e1ccd3ed9f7dd23e460d6a))
* **compartment-mapper:** Restore named reexport as bug in tests ([2de06f3](https://github.com/endojs/endo/commit/2de06f38946c25c72152980bd055a9e9759bfb43))
* **compartment-mapper:** Switch from Syrup to JSON ([0d80376](https://github.com/endojs/endo/commit/0d80376fcf4dfc804a406d9d3e6e65dc900cbf08))
* **compartment-mapper:** Withdraw UMD Rollup ([#469](https://github.com/endojs/endo/issues/469)) ([9118807](https://github.com/endojs/endo/commit/911880719822f35362844ce32e56f93a26cd5c02))
* **static-module-record:** Emphasize RESM/NESM compatibility over CJS/UMD ([dcff87e](https://github.com/endojs/endo/commit/dcff87e6f1164d664dd31dfefb323fbbac0a8dd1))
* Realign TS, JS, and package names ([#686](https://github.com/endojs/endo/issues/686)) ([439e0ff](https://github.com/endojs/endo/commit/439e0fff1fd214eec91486ded8b3d36a5eb4b801))
* **compartment-mapper:** Work around dynamic import censoring ([#512](https://github.com/endojs/endo/issues/512)) ([b82398b](https://github.com/endojs/endo/commit/b82398b55eb714b8fe59c06aaec74ddf9b78dda7))
* Fully thread __shimTransforms__ through Compartment Mapper and SES ([#509](https://github.com/endojs/endo/issues/509)) ([0f199ef](https://github.com/endojs/endo/commit/0f199ef088353ec09b29e37aefcfa26a89a6c582))
* **compartment-mapper:** Temporarily disable CommonJS ([8d7fb04](https://github.com/endojs/endo/commit/8d7fb04f18acf49e22850576dded8bf7b7045548))


### Tests

* **compartment-mapper:** Refresh zip fixture ([691ca31](https://github.com/endojs/endo/commit/691ca3126d7fbc2122c1575c3d564643df569b4c))


### Code Refactoring

* **compartment-mapper:** Cleanly separate StaticModuleRecord dependency ([#698](https://github.com/endojs/endo/issues/698)) ([0b28902](https://github.com/endojs/endo/commit/0b289021eee1256c05ceb4d83318165cb6288844))
* **compartment-mapper:** Import options bags and thread transforms ([3aa9ed9](https://github.com/endojs/endo/commit/3aa9ed9dcf259ffba853c9fd53564e874113ab4a))
* **compartment-mapper:** Lean on RESM/NESM interoperability ([eb1753e](https://github.com/endojs/endo/commit/eb1753e1d28df423be6de9c70bceb6e8a1e171a1))
* **compartment-mapper:** Rearrange entry point modules ([f87dc14](https://github.com/endojs/endo/commit/f87dc14e030ed9e8d47be92ff2faa5b5bec46914))
* **compartment-mapper:** Rename endowments to globals ([a7e8a2e](https://github.com/endojs/endo/commit/a7e8a2ea734651100a4d3dfd703932b354f5d386))
