## 6.5.0 (2025-04-23)

### ⚠ BREAKING CHANGES

- add experimental `sea` support and drop nodejs 16 support (#110)

### Features

- add `ignore` option to ignore files from build ([#68](https://github.com/grain/pkg/issues/68)) ([54ae1ee](https://github.com/grain/pkg/commit/54ae1eea4a7f227d7a7246c5c3d43cf4b025c921))
- add `no-native-build` option to skip native addons build ([4ed2ee4](https://github.com/grain/pkg/commit/4ed2ee42044b72cf9cebf4e4619bcd3de28d978e)), closes [#1319](https://github.com/grain/pkg/issues/1319)
- add experimental `sea` support and drop nodejs 16 support ([#110](https://github.com/grain/pkg/issues/110)) ([0145a94](https://github.com/grain/pkg/commit/0145a94abd731a839764c48422712d4c79c90404))
- add option to skip signature on macos ([#1878](https://github.com/grain/pkg/issues/1878)) ([edfdadb](https://github.com/grain/pkg/commit/edfdadbca6ddd9526dedcc81bd876d408aae825f))
- add simple type export ([#1557](https://github.com/grain/pkg/issues/1557)) ([53b23fb](https://github.com/grain/pkg/commit/53b23fb58d3a7da813f088069e4d076952e2bca2))
- allow to skip dictionaries patches with `--no-dict` option ([#1330](https://github.com/grain/pkg/issues/1330)) ([85ccec3](https://github.com/grain/pkg/commit/85ccec331bd81dcbc49916ba9862955e0e053ec6))
- bump @yao-pkg/pkg-fetch@3.5.13 with nodejs 22.9.0 ([#91](https://github.com/grain/pkg/issues/91)) ([6ed5665](https://github.com/grain/pkg/commit/6ed566564f87867812557ec453002c50a3dc6045))
- bump fetch 3.5.17 with node 22.11.0 support ([2aae943](https://github.com/grain/pkg/commit/2aae94355b55537c361aedc2f81223b2c847955f))
- bump fetch 3.5.19 with node v18.20.6, v20.18.2 and v22.13.1 ([9863769](https://github.com/grain/pkg/commit/986376963920c25114e826fef85057f877406f60))
- bump fetch 3.5.6 with MacOS arm64 support ([#7](https://github.com/grain/pkg/issues/7)) ([efee79c](https://github.com/grain/pkg/commit/efee79c6a67418dcdc4874b8851acd1d5d956391))
- bump fetch with node 22.10.0 and 20.18.0 support ([86d5f57](https://github.com/grain/pkg/commit/86d5f5797a2d579e79a6f1f185dac20515d7ca9b))
- bump fetch with Node v22.12.0 and v20.18.1 ([a8568a5](https://github.com/grain/pkg/commit/a8568a56d8c30f077f9add61e9c256764333b225))
- bump pkg-fetch@3.5.10 with node 20.17.0 and 18.20.4 support ([dda9032](https://github.com/grain/pkg/commit/dda90320fc05d9caf95124890915b1ff684685fb))
- bump pkg-fetch@3.5.11 with nodejs 22 support (by [@faulpeltz](https://github.com/faulpeltz)) ([1d8df70](https://github.com/grain/pkg/commit/1d8df70e21f159d970077d178014add773361c87))
- bump pkg-fetch@3.5.21 with node v18.20.8 and v22.14.0 ([1a381eb](https://github.com/grain/pkg/commit/1a381eba4255ff413dd8d13bdd609229a39258c3))
- bump pkg-fetch@3.5.5 ([#6](https://github.com/grain/pkg/issues/6)) ([99d3562](https://github.com/grain/pkg/commit/99d35621f006f06bc595672752b5b5a521b979a0))
- bump pkg-fetch@3.5.7 with node20 support ([efb585a](https://github.com/grain/pkg/commit/efb585a6cdd4cc2595e897ca9561997e3552a40e))
- **parser:** handle template literal without expressions ([#981](https://github.com/grain/pkg/issues/981)) ([79cca54](https://github.com/grain/pkg/commit/79cca5444ac46ecad4b12397ad90e632e5401fc1))
- pkg-fetch@3.5.8 with nodejs 18.19.0 and 20.11.0 support ([da8d530](https://github.com/grain/pkg/commit/da8d530b85891e18e95df5a93f87c33c2e8246a4))
- pkg-fetch@3.5.9 with nodejs 18.19.1 and 20.11.1 ([d6485df](https://github.com/grain/pkg/commit/d6485df9a0b065be450600785d3a5d52108fddb6))
- support for classPrivateProperties ([#891](https://github.com/grain/pkg/issues/891)) ([f085794](https://github.com/grain/pkg/commit/f085794089eec60a086b81313d6e4ecbdf8ab973))
- support node19 ([#1862](https://github.com/grain/pkg/issues/1862)) ([e388983](https://github.com/grain/pkg/commit/e38898355817df7af322c05a74b7d536a660bc12))
- use unofficial builds in SEA ([#126](https://github.com/grain/pkg/issues/126)) ([20e8dda](https://github.com/grain/pkg/commit/20e8ddaf2944867569b0f63d45d09c2f6abc9c11))

### Bug Fixes

- `bytecode` option is a boolean ([#1554](https://github.com/grain/pkg/issues/1554)) ([46b3aa5](https://github.com/grain/pkg/commit/46b3aa5831d5d788cd7f1c9b245d0d4b05cd6d92))
- add dictionary for thread-stream (Used by pino) ([#36](https://github.com/grain/pkg/issues/36)) ([b01d1ad](https://github.com/grain/pkg/commit/b01d1ad44cc1dc6a1f91c2d371e63ea20e49cbc6))
- add dictionary to mute 'compare' test ([80a1992](https://github.com/grain/pkg/commit/80a1992dfc89d4a4c7d66e12a7bae7077ca2ccb4))
- add force flag to codesign to avoid already signed error ([#1756](https://github.com/grain/pkg/issues/1756)) ([f19285d](https://github.com/grain/pkg/commit/f19285db72f4592110f49335923d9199da49a137))
- add missing arch to nativePrebuildInstall cache ([#9](https://github.com/grain/pkg/issues/9)) ([cd89e83](https://github.com/grain/pkg/commit/cd89e83586c301a2a31ff510023ee2667a1aae07))
- Add missing functions from restored fs.Stats ([#1923](https://github.com/grain/pkg/issues/1923)) ([e51efbe](https://github.com/grain/pkg/commit/e51efbe14ffd6d649420419cbd835146d1a7a612))
- allow copyFile and copyFileSync from snapshot ([#1484](https://github.com/grain/pkg/issues/1484)) ([72bc8b3](https://github.com/grain/pkg/commit/72bc8b36ba3e674f4818ac8d57881cd161c0e4d7))
- avoid endless loop when handling symlinks ([#109](https://github.com/grain/pkg/issues/109)) by [@q0rban](https://github.com/q0rban) ([#109](https://github.com/grain/pkg/issues/109)) ([e41355c](https://github.com/grain/pkg/commit/e41355c5de3ad8a2597e61c6708cefe065d5ab0d))
- bootstrap: fs readdir and readdirSync ([#1130](https://github.com/grain/pkg/issues/1130)/[#1299](https://github.com/grain/pkg/issues/1299)) ([#1495](https://github.com/grain/pkg/issues/1495)) ([5010411](https://github.com/grain/pkg/commit/501041159c3bca02ca8e702947acee8363ae9c88))
- **bootstrap:** prevent overriding existing node addon file ([#1611](https://github.com/grain/pkg/issues/1611)) ([f0c4e8c](https://github.com/grain/pkg/commit/f0c4e8cd113e761958ab387f4b0237f4d8797335)), closes [#1589](https://github.com/grain/pkg/issues/1589)
- bump pkg-fetch@3.5.12 with missing node22 macOS arm64 support ([4eea80c](https://github.com/grain/pkg/commit/4eea80c26d6eec8b7962392a7938048612f41673))
- catch babel parse errors ([#1324](https://github.com/grain/pkg/issues/1324)) ([ff2092c](https://github.com/grain/pkg/commit/ff2092c7bc5db1e69b947feabafd0ab0f2a9af1e))
- child_process commands throw when pkg app try to call itself ([#90](https://github.com/grain/pkg/issues/90)) ([e88d159](https://github.com/grain/pkg/commit/e88d15919fa16a8bba7991a165ebbf2336e13dce))
- correct promisification of fs.statfs in bootstrap.js ([6e150e9](https://github.com/grain/pkg/commit/6e150e95141c4ca55229087e2d6e2638e141458c))
- deprecated `_extend` in bootstrap.js ([#118](https://github.com/grain/pkg/issues/118)) ([4acb187](https://github.com/grain/pkg/commit/4acb1879343287204957ae2f5bf4790cd83451e5))
- diagnostic folder size and humanize size ([4f5b63c](https://github.com/grain/pkg/commit/4f5b63ca9ce9712da21348175cce54ae0322e254))
- dictionary for sqlite3 ([#40](https://github.com/grain/pkg/issues/40)) ([a3b18f8](https://github.com/grain/pkg/commit/a3b18f86968670a8f9978e7270ef89c2e7dabed1))
- do not overwrite temp .node files ([#1547](https://github.com/grain/pkg/issues/1547)) ([63eaeab](https://github.com/grain/pkg/commit/63eaeabb4c80344f242aac04d61cba9493f82549))
- follow exact SEA baking procedure for Mac ([#116](https://github.com/grain/pkg/issues/116)) ([d818a04](https://github.com/grain/pkg/commit/d818a043b20e55d381cc978220f1158e9059e160))
- improve `unlikelyJavascript` check ([7f0b492](https://github.com/grain/pkg/commit/7f0b492a175ca755dceb50660ecee11b40de641d))
- missing `fs/promises` patches to resolve `Not found` error ([#124](https://github.com/grain/pkg/issues/124)) ([93fed60](https://github.com/grain/pkg/commit/93fed60943fef354e0cefde58b72fa48eb8ff23e))
- missing entrypoint when launched from self-created child process ([#1949](https://github.com/grain/pkg/issues/1949)) ([73a03d1](https://github.com/grain/pkg/commit/73a03d1c27d879ff82a6d7b58c5f08c1da8a6a6b))
- navigate back to previous directory after SEA build ([#131](https://github.com/grain/pkg/issues/131)) ([1489e94](https://github.com/grain/pkg/commit/1489e946332f6cba69e4be5fe0b66e798b8a23ce))
- node18.19 broken binaries ([2e99185](https://github.com/grain/pkg/commit/2e99185317bbd6278fadeb9cca4741303c6fbfe0)), closes [#28](https://github.com/grain/pkg/issues/28)
- organization name ([165e9a1](https://github.com/grain/pkg/commit/165e9a1c3e1c3cf9f26e61b8975c28cc4b919b38))
- over extracting native modules with pnpm ([#14](https://github.com/grain/pkg/issues/14)) ([e435796](https://github.com/grain/pkg/commit/e43579620f3278fae1ac00b8db024912ca61a4c1))
- parsing of .cjs files as .js ([#8](https://github.com/grain/pkg/issues/8)) ([ecd064c](https://github.com/grain/pkg/commit/ecd064c9ddb15e69c44f09c7a8928d54c95c22f6))
- pass `--runtime napi` to `prebuild-install` when `binary.napi_versions` is set ([#38](https://github.com/grain/pkg/issues/38)) ([d47ee03](https://github.com/grain/pkg/commit/d47ee03f0ae58e53263e0fc8feae27748db4aab9))
- remove `is-core-module` dependency ([#77](https://github.com/grain/pkg/issues/77)) ([2f27414](https://github.com/grain/pkg/commit/2f27414d5dfa3e375118cac14932ab0d2ece92d7))
- run prebuild-install only if actually used by the package ([#83](https://github.com/grain/pkg/issues/83)) ([2a046e4](https://github.com/grain/pkg/commit/2a046e4be321e1c564744a161ec65b213baaa6ae))
- tests ([#34](https://github.com/grain/pkg/issues/34)) ([7472af7](https://github.com/grain/pkg/commit/7472af714d1766f6a4f62cfdfe038d3291b5cd72))
- tests using wrong `pkg-fetch` package ([8466f1d](https://github.com/grain/pkg/commit/8466f1d32eac15206c88f6c58d80e8179c0a68d5))
- **tests:** improve tests and add DEVELOPMENT.md docs ([#111](https://github.com/grain/pkg/issues/111)) ([717b963](https://github.com/grain/pkg/commit/717b9635b0f3a0a78072a9b925ed0cf2bd18103d))
- update resolve package to version 1.22.10 and add is-core-module dependency ([90af1c2](https://github.com/grain/pkg/commit/90af1c271a8ce71f37b5481373a387850d95863d)), closes [#138](https://github.com/grain/pkg/issues/138)
- upgrade tinyglobby ([#121](https://github.com/grain/pkg/issues/121)) ([d2d38f9](https://github.com/grain/pkg/commit/d2d38f92449a9698226df3fb498d2367921827de))
- use cache directory in users home instead of system-wide tmp dir ([#55](https://github.com/grain/pkg/issues/55)) ([a217727](https://github.com/grain/pkg/commit/a217727d71ba2490c0988077011595fe54d26711))
- wrong placeholder replaced in windows binary ([#86](https://github.com/grain/pkg/issues/86)) ([d9b28c3](https://github.com/grain/pkg/commit/d9b28c391bc7d94df2b95074b98ee43681c67b5a))
- wrong shas in pkg-fetch ([8c783f7](https://github.com/grain/pkg/commit/8c783f75a5c439cc96a82497cb5afad9e2c31b04))

### Test added

- add "node14" to fetch-all ([63f4ce0](https://github.com/grain/pkg/commit/63f4ce03f71f926521eb8f94dd49b24fb58190ed))
- add hybrid ESM test setup with libphonenumber-js ([#139](https://github.com/grain/pkg/issues/139)) ([3bd1ccf](https://github.com/grain/pkg/commit/3bd1ccfb9ec4e42078348c6ec7f473dd6871d03d))
- add macos multi arch test ([#113](https://github.com/grain/pkg/issues/113)) ([cd0095e](https://github.com/grain/pkg/commit/cd0095e7f7729f44e5ae0d47ff81b9cad65cea0a)), closes [#112](https://github.com/grain/pkg/issues/112)
- add tests for [#1191](https://github.com/grain/pkg/issues/1191) and [#1192](https://github.com/grain/pkg/issues/1192) ([bcec96c](https://github.com/grain/pkg/commit/bcec96cd95ebee70a2666344e0fb0e6a2e9f59e1))
- add unit test for [#775](https://github.com/grain/pkg/issues/775) ([#1118](https://github.com/grain/pkg/issues/1118)) ([94cdb69](https://github.com/grain/pkg/commit/94cdb69af57fa454e54ae9e8f33d9f428933d2ed))
- allow to run tests in parallel ([#115](https://github.com/grain/pkg/issues/115)) ([f564a33](https://github.com/grain/pkg/commit/f564a3360365776dcebf56be3f494b82ace58932))
- bump expected major to 5 ([#1145](https://github.com/grain/pkg/issues/1145)) ([1f05232](https://github.com/grain/pkg/commit/1f05232fdd1e3ff70ffc94b9d9c6b56b91b2d57a))
- fix verify pkg version test ([81bd04a](https://github.com/grain/pkg/commit/81bd04ae5be7826bf695033de8e80b21c9cb7beb))
- fs-runtime-layer: remove "birthtime" check ([7c72f3a](https://github.com/grain/pkg/commit/7c72f3a6a8dcffb5e727f8bbbbb25066f92a94a5))
- ignore pnpm test for node14 ([#1919](https://github.com/grain/pkg/issues/1919)) ([7255f64](https://github.com/grain/pkg/commit/7255f6470484774459e84375411e0d95b1711f4e))
- improve tests log output ([#114](https://github.com/grain/pkg/issues/114)) ([417cf78](https://github.com/grain/pkg/commit/417cf789036fabfbd446c48858aaa4eea571c5dd))
- rearrange and fix order ([e7e67aa](https://github.com/grain/pkg/commit/e7e67aa2c1a238d21a19e3f8f978ffd3ad49289c))
- test pnpm packages only on node >= 14.19 ([#1613](https://github.com/grain/pkg/issues/1613)) ([193b778](https://github.com/grain/pkg/commit/193b778b62cd15523225f25aff1648880ac16414))
- test with Node 16 ([655ee18](https://github.com/grain/pkg/commit/655ee183681c770cf1e5ff146604f43c09045590))
- test-50-bakery-4 for baking non-v8 options ([7ff6430](https://github.com/grain/pkg/commit/7ff64301cbe4f044d30c0db659663db03a5d57e7))
- update tesseract.js test for v4 ([#1864](https://github.com/grain/pkg/issues/1864)) ([265c00e](https://github.com/grain/pkg/commit/265c00e435d139c3d6d0cc50de60209ca7b1c9f9))

### Code refactoring

- remove `fs-extra` ([#102](https://github.com/grain/pkg/issues/102)) ([c726221](https://github.com/grain/pkg/commit/c726221de31843f3100f455c2402f394c9e8963d))
- replace `chalk` with `picocolors` ([#105](https://github.com/grain/pkg/issues/105)) ([cba291e](https://github.com/grain/pkg/commit/cba291e246bd9bc8c990a1da5f3652ebd38e2363))
- replace `globby` with `tinyglobby` ([#103](https://github.com/grain/pkg/issues/103)) ([99a2632](https://github.com/grain/pkg/commit/99a26329cbe408fd08f2a53cd49cf4744573aaa9))
- replace `minimatch` with `picomatch` ([#104](https://github.com/grain/pkg/issues/104)) ([1838100](https://github.com/grain/pkg/commit/183810066d308366729414d4138e6f7d85ee1b71))

### Chores

- add ci, stale workflows and dependabot ([#1074](https://github.com/grain/pkg/issues/1074)) ([31e8bf7](https://github.com/grain/pkg/commit/31e8bf7da05a884449e807438bfaf57ce71aeb29))
- add prettier check in linting step ([#1764](https://github.com/grain/pkg/issues/1764)) ([6efa7cf](https://github.com/grain/pkg/commit/6efa7cfbbac323a019680609c2c78bbf7b9fff0f))
- add release script ([#2](https://github.com/grain/pkg/issues/2)) ([6dd5e11](https://github.com/grain/pkg/commit/6dd5e11a954f7e51a6cc8181b3389fa5143b448e))
- add update dep workflow ([12d1872](https://github.com/grain/pkg/commit/12d18724461cc6d44fac792d164db26c033723bf))
- bump @yao-pkg/pkg-fetch@3.5.3 ([f43dd71](https://github.com/grain/pkg/commit/f43dd711b1791f4ef40d7734bfcf1c7a88d6ab04))
- bump deps and lint fix ([#1](https://github.com/grain/pkg/issues/1)) ([448c81a](https://github.com/grain/pkg/commit/448c81a4a2200d4cd2253046a19573e33a20b790))
- bump fetch to fix sha mismatch ([#4](https://github.com/grain/pkg/issues/4)) ([9d454e0](https://github.com/grain/pkg/commit/9d454e0078830b6b5e9fa3c118ba5f79f9d52e77))
- bump pkg-fetch to 3.5.2 ([#1914](https://github.com/grain/pkg/issues/1914)) ([76010f6](https://github.com/grain/pkg/commit/76010f66a4b178d0d517c9f30bd14f6bd0a4474f))
- bump prebuild-install@7.1.1 ([#1788](https://github.com/grain/pkg/issues/1788)) ([e3ac490](https://github.com/grain/pkg/commit/e3ac4902e9cb023f0ac2a596e21ff9166d2e268c))
- **chalk:** bump version ([#192](https://github.com/grain/pkg/issues/192)) ([a12159f](https://github.com/grain/pkg/commit/a12159f18b4d42ad77fcb6954f75e1a635959cd3))
- **ci:** drop nodejs 14 ([d234904](https://github.com/grain/pkg/commit/d2349045a7324088d6efd9ee778335cb467ae5b7))
- clean up obsolete eslint disable comments ([#1760](https://github.com/grain/pkg/issues/1760)) ([56135b5](https://github.com/grain/pkg/commit/56135b583b901d552e3780e749e79e70e71fd3ea))
- drop package-lock file uploaded by error ([ba407ef](https://github.com/grain/pkg/commit/ba407efef1d2e611d4c192b93295dcaa023fea79))
- fix build ([276651a](https://github.com/grain/pkg/commit/276651aaa38451c4ba67ea2e46c9bdea6547ee2d))
- fix npm pkg errors ([60950fa](https://github.com/grain/pkg/commit/60950facb3d6ebaa57e9ceb974f4c560b2a40958))
- fix package.json name ([3d011c1](https://github.com/grain/pkg/commit/3d011c1f037e8d5372906f08f8edb12163e0d6d5))
- fix workflow permissions ([c279732](https://github.com/grain/pkg/commit/c2797325e2e49d0cab3bf3e20e9f6171f76fd3e6))
- fix yarn.lock issues ([fa4f911](https://github.com/grain/pkg/commit/fa4f91110b93c805b931c720ed3e5e45a3c2b28f))
- make corruption test pass on macos ([#1890](https://github.com/grain/pkg/issues/1890)) ([8eef5ea](https://github.com/grain/pkg/commit/8eef5eace55a55c4095a719926156ec2d5166a53))
- make pkg-fetch dep static (temporarily). ([#1100](https://github.com/grain/pkg/issues/1100)) ([165fcd5](https://github.com/grain/pkg/commit/165fcd543d293fdb2ebff32ffbba38bfd107f47d))
- **package:** update acorn to version 4.0.4 ([#26](https://github.com/grain/pkg/issues/26)) ([1f6dc34](https://github.com/grain/pkg/commit/1f6dc347a118f2822bb2bc77e30f20d148fd1c1e))
- **package:** update babel-cli to version 6.18.0 ([#14](https://github.com/grain/pkg/issues/14)) ([96a86cf](https://github.com/grain/pkg/commit/96a86cf5e5673211564ed501304b6902ac13e785))
- **package:** update babel-eslint to version 7.1.0 ([#18](https://github.com/grain/pkg/issues/18)) ([aadc606](https://github.com/grain/pkg/commit/aadc6067aa2c4dc35316a6088cc2eb6a1235b5c8))
- **package:** update babel-eslint to version 7.1.1 ([#24](https://github.com/grain/pkg/issues/24)) ([76eb48f](https://github.com/grain/pkg/commit/76eb48f804d5d5cbca1fe1cf1a5987c851add136))
- **package:** update babel-preset-es2015 to version 6.18.0 ([#15](https://github.com/grain/pkg/issues/15)) ([5a8a05a](https://github.com/grain/pkg/commit/5a8a05accec9279b7fca480d08e8d1c856f45e83))
- **package:** update babel-register to version 6.16.3 ([f3930c9](https://github.com/grain/pkg/commit/f3930c9741e2a24d671332b61f1130c6269bbe5a))
- **package:** update babel-register to version 6.18.0 ([#16](https://github.com/grain/pkg/issues/16)) ([283f158](https://github.com/grain/pkg/commit/283f158079111f4be097aa61ac31a00c40d5e3cf))
- **package:** update babel-runtime to version 6.18.0 ([#17](https://github.com/grain/pkg/issues/17)) ([7f8a281](https://github.com/grain/pkg/commit/7f8a281ab75eaa7ba196f5d2079a6dbfd8fb8a61))
- **package:** update babel-runtime to version 6.20.0 ([#25](https://github.com/grain/pkg/issues/25)) ([590de8c](https://github.com/grain/pkg/commit/590de8cd9a05e514962e280d9d54e7398f869a2c))
- **package:** update dependencies ([e6cfbf7](https://github.com/grain/pkg/commit/e6cfbf7d9a7671e76652f041ecca3a84033a7409))
- **package:** update eslint-config-klopov to version 0.11.0 ([c7f36be](https://github.com/grain/pkg/commit/c7f36be5d89d868c008aa32ea8e7e22739d9dc79))
- **package:** update fs-promise to version 1.0.0 ([#20](https://github.com/grain/pkg/issues/20)) ([4488540](https://github.com/grain/pkg/commit/4488540f79514bc805299ce4b222b9b9d8dcca5b))
- **package:** update globby to version 6.1.0 ([#19](https://github.com/grain/pkg/issues/19)) ([32e0c1b](https://github.com/grain/pkg/commit/32e0c1b780320826afb6cf9493b1e4b1fa40adef))
- **package:** update pkg-fetch to version 1.5.0 ([8bdd785](https://github.com/grain/pkg/commit/8bdd785fda97fec99e5a08bfd25fa6c514e897cb))
- Prepare for Grain release ([65db5fb](https://github.com/grain/pkg/commit/65db5fbfe6a4b7840128ec1ff7870d8e8aec7d4d))
- remove eol nodejs in tests ([#1889](https://github.com/grain/pkg/issues/1889)) ([4fe0b4d](https://github.com/grain/pkg/commit/4fe0b4d3308624ebeed3283891ff9e4328c55a1c))
- remove node20 from ci ([15fe2dc](https://github.com/grain/pkg/commit/15fe2dcd2fa5e9eba51c44d62fcb6e0c6c482b39))
- remove unused dependencies ([#1769](https://github.com/grain/pkg/issues/1769)) ([c353cc9](https://github.com/grain/pkg/commit/c353cc9ce8afba97bb6f5c92f71384498835071b))
- remove unused entry ([#1766](https://github.com/grain/pkg/issues/1766)) ([39e9985](https://github.com/grain/pkg/commit/39e99859fe2fd33fb59c4a75318389b477c1a443))
- replace deprecated String.prototype.substr() ([#1560](https://github.com/grain/pkg/issues/1560)) ([edfcc7b](https://github.com/grain/pkg/commit/edfcc7b139d667d6be0e46f4101e917ca9c154bd))
- separate individual test scripts ([#1759](https://github.com/grain/pkg/issues/1759)) ([332c7d9](https://github.com/grain/pkg/commit/332c7d971a6a8f918f6d24470557f2dcb1de5abf))
- unpin dependencies ([#106](https://github.com/grain/pkg/issues/106)) ([ea94b03](https://github.com/grain/pkg/commit/ea94b03bad08254e741d028617e5581d6a34f48b))
- update GitHub Actions to use checkout@v4 and setup-node@v4 ([e1f8f41](https://github.com/grain/pkg/commit/e1f8f41913bc80c627709c0d68c8d268c5032f13))
- Update to pkg-fetch 3.6.1 ([284cb90](https://github.com/grain/pkg/commit/284cb90cdfc489e76245216549a3b49309b1c646))
- update vscode settings ([bf490a0](https://github.com/grain/pkg/commit/bf490a08907d0d075548d0feb06135a750c2a365))
- upgrade actions runners ([#1767](https://github.com/grain/pkg/issues/1767)) ([614c02a](https://github.com/grain/pkg/commit/614c02a06830e0a4a898e6cf4eb35dbbf6110af3))
- use `@types/babel__generator` package ([#1755](https://github.com/grain/pkg/issues/1755)) ([b8deba4](https://github.com/grain/pkg/commit/b8deba40c0c9dced29e5c15aaefe575285e716d6))

### Documentation

- explain how to execute binary from snapshot ([db7f2c5](https://github.com/grain/pkg/commit/db7f2c5ede385db7c29b7d17cf7fa605b44e9a9e))
- explain how to use custom binaries ([18ed3cf](https://github.com/grain/pkg/commit/18ed3cfd1e79108de534d0c10e7172c9d9a89765))
- fix install command ([3e63d90](https://github.com/grain/pkg/commit/3e63d90e453ee51134aec956524d3389506f8959))
- MAKE_JOB_COUNT and PKG_IGNORE_TAG env var ([#1053](https://github.com/grain/pkg/issues/1053)) ([7a9257a](https://github.com/grain/pkg/commit/7a9257ac91efaddc90c558173af1a6bec5da6cdd))
- update env vars ([406c451](https://github.com/grain/pkg/commit/406c451c325df42334870c3e70db46d8db333d0d))
- update README.md ([0238e3c](https://github.com/grain/pkg/commit/0238e3c91d76087dda93c81081650a6192dfda50))

## [6.4.0](https://github.com/yao-pkg/pkg/compare/v6.3.2...v6.4.0) (2025-04-08)

### Features

- bump pkg-fetch@3.5.21 with node v18.20.8 and v22.14.0 ([1a381eb](https://github.com/yao-pkg/pkg/commit/1a381eba4255ff413dd8d13bdd609229a39258c3))

### Documentation

- update README.md ([0238e3c](https://github.com/yao-pkg/pkg/commit/0238e3c91d76087dda93c81081650a6192dfda50))

## [6.3.2](https://github.com/yao-pkg/pkg/compare/v6.3.1...v6.3.2) (2025-03-03)

### Bug Fixes

- update resolve package to version 1.22.10 and add is-core-module dependency ([90af1c2](https://github.com/yao-pkg/pkg/commit/90af1c271a8ce71f37b5481373a387850d95863d)), closes [#138](https://github.com/yao-pkg/pkg/issues/138)

### Test added

- add hybrid ESM test setup with libphonenumber-js ([#139](https://github.com/yao-pkg/pkg/issues/139)) ([3bd1ccf](https://github.com/yao-pkg/pkg/commit/3bd1ccfb9ec4e42078348c6ec7f473dd6871d03d))

## [6.3.1](https://github.com/yao-pkg/pkg/compare/v6.3.0...v6.3.1) (2025-02-18)

### Bug Fixes

- correct promisification of fs.statfs in bootstrap.js ([6e150e9](https://github.com/yao-pkg/pkg/commit/6e150e95141c4ca55229087e2d6e2638e141458c))
- upgrade tinyglobby ([#121](https://github.com/yao-pkg/pkg/issues/121)) ([d2d38f9](https://github.com/yao-pkg/pkg/commit/d2d38f92449a9698226df3fb498d2367921827de))

### Chores

- update GitHub Actions to use checkout@v4 and setup-node@v4 ([e1f8f41](https://github.com/yao-pkg/pkg/commit/e1f8f41913bc80c627709c0d68c8d268c5032f13))

## [6.3.0](https://github.com/yao-pkg/pkg/compare/v6.2.0...v6.3.0) (2025-01-30)

### Features

- bump fetch 3.5.19 with node v18.20.6, v20.18.2 and v22.13.1 ([9863769](https://github.com/yao-pkg/pkg/commit/986376963920c25114e826fef85057f877406f60))

## [6.2.0](https://github.com/yao-pkg/pkg/compare/v6.1.1...v6.2.0) (2024-12-28)

### Features

- bump fetch with Node v22.12.0 and v20.18.1 ([a8568a5](https://github.com/yao-pkg/pkg/commit/a8568a56d8c30f077f9add61e9c256764333b225))
- use unofficial builds in SEA ([#126](https://github.com/yao-pkg/pkg/issues/126)) ([20e8dda](https://github.com/yao-pkg/pkg/commit/20e8ddaf2944867569b0f63d45d09c2f6abc9c11))

### Bug Fixes

- navigate back to previous directory after SEA build ([#131](https://github.com/yao-pkg/pkg/issues/131)) ([1489e94](https://github.com/yao-pkg/pkg/commit/1489e946332f6cba69e4be5fe0b66e798b8a23ce))

## [6.1.1](https://github.com/yao-pkg/pkg/compare/v6.1.0...v6.1.1) (2024-11-13)

### Bug Fixes

- missing `fs/promises` patches to resolve `Not found` error ([#124](https://github.com/yao-pkg/pkg/issues/124)) ([93fed60](https://github.com/yao-pkg/pkg/commit/93fed60943fef354e0cefde58b72fa48eb8ff23e))

## [6.1.0](https://github.com/yao-pkg/pkg/compare/v6.0.1...v6.1.0) (2024-11-04)

### Features

- bump fetch 3.5.17 with node 22.11.0 support ([2aae943](https://github.com/yao-pkg/pkg/commit/2aae94355b55537c361aedc2f81223b2c847955f))

### Chores

- fix yarn.lock issues ([fa4f911](https://github.com/yao-pkg/pkg/commit/fa4f91110b93c805b931c720ed3e5e45a3c2b28f))

## [6.0.1](https://github.com/yao-pkg/pkg/compare/v6.0.0...v6.0.1) (2024-11-04)

### Bug Fixes

- avoid endless loop when handling symlinks ([#109](https://github.com/yao-pkg/pkg/issues/109)) by [@q0rban](https://github.com/q0rban) ([#109](https://github.com/yao-pkg/pkg/issues/109)) ([e41355c](https://github.com/yao-pkg/pkg/commit/e41355c5de3ad8a2597e61c6708cefe065d5ab0d))
- deprecated `_extend` in bootstrap.js ([#118](https://github.com/yao-pkg/pkg/issues/118)) ([4acb187](https://github.com/yao-pkg/pkg/commit/4acb1879343287204957ae2f5bf4790cd83451e5))
- follow exact SEA baking procedure for Mac ([#116](https://github.com/yao-pkg/pkg/issues/116)) ([d818a04](https://github.com/yao-pkg/pkg/commit/d818a043b20e55d381cc978220f1158e9059e160))

### Test added

- fix verify pkg version test ([81bd04a](https://github.com/yao-pkg/pkg/commit/81bd04ae5be7826bf695033de8e80b21c9cb7beb))

## [6.0.0](https://github.com/yao-pkg/pkg/compare/v5.16.1...v6.0.0) (2024-10-24)

### ⚠ BREAKING CHANGES

- add experimental `sea` support and drop nodejs 16 support (#110)

### Features

- add experimental `sea` support and drop nodejs 16 support ([#110](https://github.com/yao-pkg/pkg/issues/110)) ([0145a94](https://github.com/yao-pkg/pkg/commit/0145a94abd731a839764c48422712d4c79c90404))

### Bug Fixes

- **tests:** improve tests and add DEVELOPMENT.md docs ([#111](https://github.com/yao-pkg/pkg/issues/111)) ([717b963](https://github.com/yao-pkg/pkg/commit/717b9635b0f3a0a78072a9b925ed0cf2bd18103d))

### Test added

- add macos multi arch test ([#113](https://github.com/yao-pkg/pkg/issues/113)) ([cd0095e](https://github.com/yao-pkg/pkg/commit/cd0095e7f7729f44e5ae0d47ff81b9cad65cea0a)), closes [#112](https://github.com/yao-pkg/pkg/issues/112)
- allow to run tests in parallel ([#115](https://github.com/yao-pkg/pkg/issues/115)) ([f564a33](https://github.com/yao-pkg/pkg/commit/f564a3360365776dcebf56be3f494b82ace58932))
- improve tests log output ([#114](https://github.com/yao-pkg/pkg/issues/114)) ([417cf78](https://github.com/yao-pkg/pkg/commit/417cf789036fabfbd446c48858aaa4eea571c5dd))

## [5.16.1](https://github.com/yao-pkg/pkg/compare/v5.16.0...v5.16.1) (2024-10-21)

### Bug Fixes

- wrong shas in pkg-fetch ([8c783f7](https://github.com/yao-pkg/pkg/commit/8c783f75a5c439cc96a82497cb5afad9e2c31b04))

## [5.16.0](https://github.com/yao-pkg/pkg/compare/v5.15.0...v5.16.0) (2024-10-20)

### Features

- bump fetch with node 22.10.0 and 20.18.0 support ([86d5f57](https://github.com/yao-pkg/pkg/commit/86d5f5797a2d579e79a6f1f185dac20515d7ca9b))

### Code refactoring

- remove `fs-extra` ([#102](https://github.com/yao-pkg/pkg/issues/102)) ([c726221](https://github.com/yao-pkg/pkg/commit/c726221de31843f3100f455c2402f394c9e8963d))
- replace `chalk` with `picocolors` ([#105](https://github.com/yao-pkg/pkg/issues/105)) ([cba291e](https://github.com/yao-pkg/pkg/commit/cba291e246bd9bc8c990a1da5f3652ebd38e2363))
- replace `globby` with `tinyglobby` ([#103](https://github.com/yao-pkg/pkg/issues/103)) ([99a2632](https://github.com/yao-pkg/pkg/commit/99a26329cbe408fd08f2a53cd49cf4744573aaa9))
- replace `minimatch` with `picomatch` ([#104](https://github.com/yao-pkg/pkg/issues/104)) ([1838100](https://github.com/yao-pkg/pkg/commit/183810066d308366729414d4138e6f7d85ee1b71))

### Chores

- unpin dependencies ([#106](https://github.com/yao-pkg/pkg/issues/106)) ([ea94b03](https://github.com/yao-pkg/pkg/commit/ea94b03bad08254e741d028617e5581d6a34f48b))

### Documentation

- explain how to execute binary from snapshot ([db7f2c5](https://github.com/yao-pkg/pkg/commit/db7f2c5ede385db7c29b7d17cf7fa605b44e9a9e))
- explain how to use custom binaries ([18ed3cf](https://github.com/yao-pkg/pkg/commit/18ed3cfd1e79108de534d0c10e7172c9d9a89765))

## [5.15.0](https://github.com/yao-pkg/pkg/compare/v5.14.2...v5.15.0) (2024-09-20)

### Features

- bump @yao-pkg/pkg-fetch@3.5.13 with nodejs 22.9.0 ([#91](https://github.com/yao-pkg/pkg/issues/91)) ([6ed5665](https://github.com/yao-pkg/pkg/commit/6ed566564f87867812557ec453002c50a3dc6045))

## [5.14.2](https://github.com/yao-pkg/pkg/compare/v5.14.1...v5.14.2) (2024-09-17)

### Bug Fixes

- child_process commands throw when pkg app try to call itself ([#90](https://github.com/yao-pkg/pkg/issues/90)) ([e88d159](https://github.com/yao-pkg/pkg/commit/e88d15919fa16a8bba7991a165ebbf2336e13dce))

## [5.14.1](https://github.com/yao-pkg/pkg/compare/v5.14.0...v5.14.1) (2024-09-17)

### Bug Fixes

- bump pkg-fetch@3.5.12 with missing node22 macOS arm64 support ([4eea80c](https://github.com/yao-pkg/pkg/commit/4eea80c26d6eec8b7962392a7938048612f41673))

## [5.14.0](https://github.com/yao-pkg/pkg/compare/v5.13.0...v5.14.0) (2024-09-10)

### Features

- bump pkg-fetch@3.5.11 with nodejs 22 support (by [@faulpeltz](https://github.com/faulpeltz)) ([1d8df70](https://github.com/yao-pkg/pkg/commit/1d8df70e21f159d970077d178014add773361c87))

## [5.13.0](https://github.com/yao-pkg/pkg/compare/v5.12.1...v5.13.0) (2024-09-06)

### Features

- bump pkg-fetch@3.5.10 with node 20.17.0 and 18.20.4 support ([dda9032](https://github.com/yao-pkg/pkg/commit/dda90320fc05d9caf95124890915b1ff684685fb))

### Bug Fixes

- wrong placeholder replaced in windows binary ([#86](https://github.com/yao-pkg/pkg/issues/86)) ([d9b28c3](https://github.com/yao-pkg/pkg/commit/d9b28c391bc7d94df2b95074b98ee43681c67b5a))

## [5.12.1](https://github.com/yao-pkg/pkg/compare/v5.12.0...v5.12.1) (2024-08-14)

### Bug Fixes

- remove `is-core-module` dependency ([#77](https://github.com/yao-pkg/pkg/issues/77)) ([2f27414](https://github.com/yao-pkg/pkg/commit/2f27414d5dfa3e375118cac14932ab0d2ece92d7))
- run prebuild-install only if actually used by the package ([#83](https://github.com/yao-pkg/pkg/issues/83)) ([2a046e4](https://github.com/yao-pkg/pkg/commit/2a046e4be321e1c564744a161ec65b213baaa6ae))

### Chores

- drop package-lock file uploaded by error ([ba407ef](https://github.com/yao-pkg/pkg/commit/ba407efef1d2e611d4c192b93295dcaa023fea79))

## [5.12.0](https://github.com/yao-pkg/pkg/compare/v5.11.5...v5.12.0) (2024-06-10)

### Features

- add `ignore` option to ignore files from build ([#68](https://github.com/yao-pkg/pkg/issues/68)) ([54ae1ee](https://github.com/yao-pkg/pkg/commit/54ae1eea4a7f227d7a7246c5c3d43cf4b025c921))

### Bug Fixes

- use cache directory in users home instead of system-wide tmp dir ([#55](https://github.com/yao-pkg/pkg/issues/55)) ([a217727](https://github.com/yao-pkg/pkg/commit/a217727d71ba2490c0988077011595fe54d26711))

### Chores

- fix build ([276651a](https://github.com/yao-pkg/pkg/commit/276651aaa38451c4ba67ea2e46c9bdea6547ee2d))

## [5.11.5](https://github.com/yao-pkg/pkg/compare/v5.11.4...v5.11.5) (2024-03-13)

### Bug Fixes

- add dictionary for thread-stream (Used by pino) ([#36](https://github.com/yao-pkg/pkg/issues/36)) ([b01d1ad](https://github.com/yao-pkg/pkg/commit/b01d1ad44cc1dc6a1f91c2d371e63ea20e49cbc6))
- dictionary for sqlite3 ([#40](https://github.com/yao-pkg/pkg/issues/40)) ([a3b18f8](https://github.com/yao-pkg/pkg/commit/a3b18f86968670a8f9978e7270ef89c2e7dabed1))
- pass `--runtime napi` to `prebuild-install` when `binary.napi_versions` is set ([#38](https://github.com/yao-pkg/pkg/issues/38)) ([d47ee03](https://github.com/yao-pkg/pkg/commit/d47ee03f0ae58e53263e0fc8feae27748db4aab9))

### Chores

- add update dep workflow ([12d1872](https://github.com/yao-pkg/pkg/commit/12d18724461cc6d44fac792d164db26c033723bf))
- fix workflow permissions ([c279732](https://github.com/yao-pkg/pkg/commit/c2797325e2e49d0cab3bf3e20e9f6171f76fd3e6))

## [5.11.4](https://github.com/yao-pkg/pkg/compare/v5.11.3...v5.11.4) (2024-02-16)

### Features

- pkg-fetch@3.5.9 with nodejs 18.19.1 and 20.11.1 ([d6485df](https://github.com/yao-pkg/pkg/commit/d6485df9a0b065be450600785d3a5d52108fddb6))

### Bug Fixes

- tests ([#34](https://github.com/yao-pkg/pkg/issues/34)) ([7472af7](https://github.com/yao-pkg/pkg/commit/7472af714d1766f6a4f62cfdfe038d3291b5cd72))

## [5.11.3](https://github.com/yao-pkg/pkg/compare/v5.11.2...v5.11.3) (2024-02-12)

### Bug Fixes

- node18.19 broken binaries ([2e99185](https://github.com/yao-pkg/pkg/commit/2e99185317bbd6278fadeb9cca4741303c6fbfe0)), closes [#28](https://github.com/yao-pkg/pkg/issues/28)

## [5.11.2](https://github.com/yao-pkg/pkg/compare/v5.11.1...v5.11.2) (2024-02-06)

### Features

- pkg-fetch@3.5.8 with nodejs 18.19.0 and 20.11.0 support ([da8d530](https://github.com/yao-pkg/pkg/commit/da8d530b85891e18e95df5a93f87c33c2e8246a4))

## [5.11.1](https://github.com/yao-pkg/pkg/compare/v5.11.0...v5.11.1) (2024-01-03)

### Bug Fixes

- add missing arch to nativePrebuildInstall cache ([#9](https://github.com/yao-pkg/pkg/issues/9)) ([cd89e83](https://github.com/yao-pkg/pkg/commit/cd89e83586c301a2a31ff510023ee2667a1aae07))
- over extracting native modules with pnpm ([#14](https://github.com/yao-pkg/pkg/issues/14)) ([e435796](https://github.com/yao-pkg/pkg/commit/e43579620f3278fae1ac00b8db024912ca61a4c1))

## [5.11.0](https://github.com/yao-pkg/pkg/compare/v5.10.0...v5.11.0) (2023-12-05)

### Features

- bump pkg-fetch@3.5.7 with node20 support ([efb585a](https://github.com/yao-pkg/pkg/commit/efb585a6cdd4cc2595e897ca9561997e3552a40e))

### Bug Fixes

- parsing of .cjs files as .js ([#8](https://github.com/yao-pkg/pkg/issues/8)) ([ecd064c](https://github.com/yao-pkg/pkg/commit/ecd064c9ddb15e69c44f09c7a8928d54c95c22f6))

### Chores

- update vscode settings ([bf490a0](https://github.com/yao-pkg/pkg/commit/bf490a08907d0d075548d0feb06135a750c2a365))

## [5.10.0](https://github.com/yao-pkg/pkg/compare/v5.9.2...v5.10.0) (2023-10-28)

### Features

- bump fetch 3.5.6 with MacOS arm64 support ([#7](https://github.com/yao-pkg/pkg/issues/7)) ([efee79c](https://github.com/yao-pkg/pkg/commit/efee79c6a67418dcdc4874b8851acd1d5d956391))

## [5.9.2](https://github.com/yao-pkg/pkg/compare/v5.9.1...v5.9.2) (2023-10-17)

### Features

- bump pkg-fetch@3.5.5 ([#6](https://github.com/yao-pkg/pkg/issues/6)) ([99d3562](https://github.com/yao-pkg/pkg/commit/99d35621f006f06bc595672752b5b5a521b979a0))

### Documentation

- update env vars ([406c451](https://github.com/yao-pkg/pkg/commit/406c451c325df42334870c3e70db46d8db333d0d))

## [5.9.1](https://github.com/yao-pkg/pkg/compare/v5.9.0...v5.9.1) (2023-10-05)

### Bug Fixes

- tests using wrong `pkg-fetch` package ([8466f1d](https://github.com/yao-pkg/pkg/commit/8466f1d32eac15206c88f6c58d80e8179c0a68d5))

### Chores

- bump fetch to fix sha mismatch ([#4](https://github.com/yao-pkg/pkg/issues/4)) ([9d454e0](https://github.com/yao-pkg/pkg/commit/9d454e0078830b6b5e9fa3c118ba5f79f9d52e77))

## [5.9.0](https://github.com/yao-pkg/pkg/compare/v5.8.1...v5.9.0) (2023-10-04)

### Features

- add option to skip signature on macos ([#1878](https://github.com/yao-pkg/pkg/issues/1878)) ([edfdadb](https://github.com/yao-pkg/pkg/commit/edfdadbca6ddd9526dedcc81bd876d408aae825f))
- support node19 ([#1862](https://github.com/yao-pkg/pkg/issues/1862)) ([e388983](https://github.com/yao-pkg/pkg/commit/e38898355817df7af322c05a74b7d536a660bc12))

### Bug Fixes

- Add missing functions from restored fs.Stats ([#1923](https://github.com/yao-pkg/pkg/issues/1923)) ([e51efbe](https://github.com/yao-pkg/pkg/commit/e51efbe14ffd6d649420419cbd835146d1a7a612))
- diagnostic folder size and humanize size ([4f5b63c](https://github.com/yao-pkg/pkg/commit/4f5b63ca9ce9712da21348175cce54ae0322e254))
- missing entrypoint when launched from self-created child process ([#1949](https://github.com/yao-pkg/pkg/issues/1949)) ([73a03d1](https://github.com/yao-pkg/pkg/commit/73a03d1c27d879ff82a6d7b58c5f08c1da8a6a6b))
- organization name ([165e9a1](https://github.com/yao-pkg/pkg/commit/165e9a1c3e1c3cf9f26e61b8975c28cc4b919b38))

### Test added

- ignore pnpm test for node14 ([#1919](https://github.com/yao-pkg/pkg/issues/1919)) ([7255f64](https://github.com/yao-pkg/pkg/commit/7255f6470484774459e84375411e0d95b1711f4e))
- update tesseract.js test for v4 ([#1864](https://github.com/yao-pkg/pkg/issues/1864)) ([265c00e](https://github.com/yao-pkg/pkg/commit/265c00e435d139c3d6d0cc50de60209ca7b1c9f9))

### Chores

- add release script ([#2](https://github.com/yao-pkg/pkg/issues/2)) ([6dd5e11](https://github.com/yao-pkg/pkg/commit/6dd5e11a954f7e51a6cc8181b3389fa5143b448e))
- bump @yao-pkg/pkg-fetch@3.5.3 ([f43dd71](https://github.com/yao-pkg/pkg/commit/f43dd711b1791f4ef40d7734bfcf1c7a88d6ab04))
- bump deps and lint fix ([#1](https://github.com/yao-pkg/pkg/issues/1)) ([448c81a](https://github.com/yao-pkg/pkg/commit/448c81a4a2200d4cd2253046a19573e33a20b790))
- bump pkg-fetch to 3.5.2 ([#1914](https://github.com/yao-pkg/pkg/issues/1914)) ([76010f6](https://github.com/yao-pkg/pkg/commit/76010f66a4b178d0d517c9f30bd14f6bd0a4474f))
- **ci:** drop nodejs 14 ([d234904](https://github.com/yao-pkg/pkg/commit/d2349045a7324088d6efd9ee778335cb467ae5b7))
- fix npm pkg errors ([60950fa](https://github.com/yao-pkg/pkg/commit/60950facb3d6ebaa57e9ceb974f4c560b2a40958))
- fix package.json name ([3d011c1](https://github.com/yao-pkg/pkg/commit/3d011c1f037e8d5372906f08f8edb12163e0d6d5))
- make corruption test pass on macos ([#1890](https://github.com/yao-pkg/pkg/issues/1890)) ([8eef5ea](https://github.com/yao-pkg/pkg/commit/8eef5eace55a55c4095a719926156ec2d5166a53))
- remove eol nodejs in tests ([#1889](https://github.com/yao-pkg/pkg/issues/1889)) ([4fe0b4d](https://github.com/yao-pkg/pkg/commit/4fe0b4d3308624ebeed3283891ff9e4328c55a1c))
- remove node20 from ci ([15fe2dc](https://github.com/yao-pkg/pkg/commit/15fe2dcd2fa5e9eba51c44d62fcb6e0c6c482b39))
- remove unused dependencies ([#1769](https://github.com/yao-pkg/pkg/issues/1769)) ([c353cc9](https://github.com/yao-pkg/pkg/commit/c353cc9ce8afba97bb6f5c92f71384498835071b))

### Documentation

- fix install command ([3e63d90](https://github.com/yao-pkg/pkg/commit/3e63d90e453ee51134aec956524d3389506f8959))
