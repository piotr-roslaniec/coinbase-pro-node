### 2.3.0 (2020-05-13)

##### Chores

- **deps:**
  - yarn upgrade --latest [ci skip](<[636f9520](https://github.com/bennyn/coinbase-pro-node/commit/636f952092f38418bdd0f047ea64187856a860af)>)
  - bump ws from 7.2.5 to 7.3.0 ([#169](https://github.com/bennyn/coinbase-pro-node/pull/169)) ([dd5d71fa](https://github.com/bennyn/coinbase-pro-node/commit/dd5d71fa280b8ad7df8f6e6a3ae5932889e5d41a))
- **deps-dev:**
  - bump @typescript-eslint/parser from 2.30.0 to 2.31.0 ([#170](https://github.com/bennyn/coinbase-pro-node/pull/170)) ([df08dbe9](https://github.com/bennyn/coinbase-pro-node/commit/df08dbe90876866a21c5d8f012f3244ad97a8126))
  - bump @typescript-eslint/eslint-plugin ([#168](https://github.com/bennyn/coinbase-pro-node/pull/168)) ([886a8507](https://github.com/bennyn/coinbase-pro-node/commit/886a8507e8b444e9b286ffd0b98b90060aca53b8))
  - bump @typescript-eslint/eslint-plugin ([#163](https://github.com/bennyn/coinbase-pro-node/pull/163)) ([a41d0bbb](https://github.com/bennyn/coinbase-pro-node/commit/a41d0bbb721f66d77e0adf1ccb2d8721d9e5565c))
  - bump ts-node from 8.9.1 to 8.10.1 ([#165](https://github.com/bennyn/coinbase-pro-node/pull/165)) ([4b77d9cc](https://github.com/bennyn/coinbase-pro-node/commit/4b77d9ccd92f4519bdb243d0af414c2fc49b93e8))
  - bump lint-staged from 10.1.7 to 10.2.2 ([#164](https://github.com/bennyn/coinbase-pro-node/pull/164)) ([0bc564c7](https://github.com/bennyn/coinbase-pro-node/commit/0bc564c75cc49929793b9a52f48ba08de529dd4f))
  - bump @typescript-eslint/parser from 2.29.0 to 2.30.0 ([#162](https://github.com/bennyn/coinbase-pro-node/pull/162)) ([55527436](https://github.com/bennyn/coinbase-pro-node/commit/55527436e1f942929ec55d1b09439779d023f332))

##### Documentation Changes

- Explain demo scripts ([#167](https://github.com/bennyn/coinbase-pro-node/pull/167)) ([86fe9a68](https://github.com/bennyn/coinbase-pro-node/commit/86fe9a683a9d0ff478ba46d96f13ebea878a4895))

##### New Features

- Withdraw funds to a crypto address ([#171](https://github.com/bennyn/coinbase-pro-node/pull/171)) ([a3c36e7b](https://github.com/bennyn/coinbase-pro-node/commit/a3c36e7bc0e03d47a104158622862a80fbc75237))
- Extend candle info with base, counter and size ([#166](https://github.com/bennyn/coinbase-pro-node/pull/166)) ([ea0f8cc3](https://github.com/bennyn/coinbase-pro-node/commit/ea0f8cc348d0e9f084fd87894f5c0c59a3fb6a84))

#### 2.2.2 (2020-04-29)

##### Refactors

- Use arbitrary-precision when estimating fees ([#161](https://github.com/bennyn/coinbase-pro-node/pull/161)) ([9613ec12](https://github.com/bennyn/coinbase-pro-node/commit/9613ec1253423f4558609a541505bef7c8486bbe))

#### 2.2.1 (2020-04-28)

##### Chores

- **deps-dev:**
  - bump typedoc from 0.17.4 to 0.17.6 ([#156](https://github.com/bennyn/coinbase-pro-node/pull/156)) ([159b3fd7](https://github.com/bennyn/coinbase-pro-node/commit/159b3fd7f1eb8b899a849f22d3b235d44d9d5c81))
  - bump @typescript-eslint/parser from 2.28.0 to 2.29.0 ([#153](https://github.com/bennyn/coinbase-pro-node/pull/153)) ([90f4c453](https://github.com/bennyn/coinbase-pro-node/commit/90f4c453202b2507b90161e7dd1a2c7b0fbd0559))
  - bump lint-staged from 10.1.6 to 10.1.7 ([#157](https://github.com/bennyn/coinbase-pro-node/pull/157)) ([8242be91](https://github.com/bennyn/coinbase-pro-node/commit/8242be9191bdeea4405d7316de87e46f3234dfab))
  - bump prettier from 2.0.4 to 2.0.5 ([#158](https://github.com/bennyn/coinbase-pro-node/pull/158)) ([9f358997](https://github.com/bennyn/coinbase-pro-node/commit/9f35899738e80b578d16b6558eb4dce0e4a8d34b))
  - bump eslint-config-prettier from 6.10.1 to 6.11.0 ([#152](https://github.com/bennyn/coinbase-pro-node/pull/152)) ([b5e42cd6](https://github.com/bennyn/coinbase-pro-node/commit/b5e42cd6321bee4adebeda22ed11eab0eb23d938))
  - bump @typescript-eslint/eslint-plugin ([#151](https://github.com/bennyn/coinbase-pro-node/pull/151)) ([ca845f9b](https://github.com/bennyn/coinbase-pro-node/commit/ca845f9be2c564be277c0900ecfc46261e2ecd93))
  - bump ts-node from 8.8.2 to 8.9.1 ([#150](https://github.com/bennyn/coinbase-pro-node/pull/150)) ([305e4b63](https://github.com/bennyn/coinbase-pro-node/commit/305e4b631c2ce3afa14faf346efde659f2b7091c))
- **deps:**
  - bump ws from 7.2.3 to 7.2.5 ([#155](https://github.com/bennyn/coinbase-pro-node/pull/155)) ([f38c7fbc](https://github.com/bennyn/coinbase-pro-node/commit/f38c7fbc530c26cf108dc5c5f79b3b7be2b836c6))
  - bump axios-retry from 3.1.5 to 3.1.8 ([#154](https://github.com/bennyn/coinbase-pro-node/pull/154)) ([fa5b2005](https://github.com/bennyn/coinbase-pro-node/commit/fa5b200536de793a06aeb73e56b8959d6551030f))

##### Bug Fixes

- Use correct symbol when watching candles ([ea71b0cc](https://github.com/bennyn/coinbase-pro-node/commit/ea71b0cc7709defd3f067401c67743036490a72d))

##### Refactors

- Prefer Node.js typings ([#160](https://github.com/bennyn/coinbase-pro-node/pull/160)) ([bc233b88](https://github.com/bennyn/coinbase-pro-node/commit/bc233b8839e8c88be6b3b311e6eb3a634b6e7e5d))

### 2.2.0 (2020-04-27)

##### Chores

- Sort keys in interfaces ([#147](https://github.com/bennyn/coinbase-pro-node/pull/147)) ([f9758ba9](https://github.com/bennyn/coinbase-pro-node/commit/f9758ba9e87b66c081b3c641679196ab4d06f7af))

##### Documentation Changes

- Fix relative API url in sidebar ([b1af82bc](https://github.com/bennyn/coinbase-pro-node/commit/b1af82bca1651ecb0333ab630577fb41046d502c))
- Document public API ([17d06a95](https://github.com/bennyn/coinbase-pro-node/commit/17d06a9511930e90e59a007c8e2a400f5b1369f6))

##### New Features

- Estimate fees ([#148](https://github.com/bennyn/coinbase-pro-node/pull/148)) ([9b11493b](https://github.com/bennyn/coinbase-pro-node/commit/9b11493b2252cf949ee470c526e411b3cdb12248))
- Unsubscribe entirely from a WebSocket channel ([#145](https://github.com/bennyn/coinbase-pro-node/pull/145)) ([f2569f07](https://github.com/bennyn/coinbase-pro-node/commit/f2569f07fc439df1f5c2cfcf982c6ca6eba1f2dc))
- List Coinbase accounts ([#144](https://github.com/bennyn/coinbase-pro-node/pull/144)) ([309baa36](https://github.com/bennyn/coinbase-pro-node/commit/309baa3606ddbca05b9630e504b9ea1bbe2ed4e3))
- List known currencies ([#143](https://github.com/bennyn/coinbase-pro-node/pull/143)) ([1f12bc1f](https://github.com/bennyn/coinbase-pro-node/commit/1f12bc1f233cb11b2942dec2c2d63e5352b852af))

##### Refactors

- Use barrel exports ([#149](https://github.com/bennyn/coinbase-pro-node/pull/149)) ([734ebaf0](https://github.com/bennyn/coinbase-pro-node/commit/734ebaf0e669958d6669cb73165f1fb42bb52ac5))

### 2.1.0 (2020-04-25)

##### Chores

- Use shorter names for test clients ([56f302db](https://github.com/bennyn/coinbase-pro-node/commit/56f302dbc0e74501bf162523e32a8277accda508))
- Move demos into separate directory ([#140](https://github.com/bennyn/coinbase-pro-node/pull/140)) ([f5c526d5](https://github.com/bennyn/coinbase-pro-node/commit/f5c526d5db888c9cfdf195ec5d17a4eb3939f8c4))

##### Documentation Changes

- Link demo scripts ([773469f1](https://github.com/bennyn/coinbase-pro-node/commit/773469f15be0ce5560cd975027626a1012465cef))
- Link dependents ([9f257763](https://github.com/bennyn/coinbase-pro-node/commit/9f2577638e8c2dc526f5917e7b304b58d54ab90b))
- Use relative paths for HTML pages ([3530cec1](https://github.com/bennyn/coinbase-pro-node/commit/3530cec19bd8d2cef7287ff219c8e53f09834fe5))

##### New Features

- Authenticate when subscribing to WebSocket feed ([#142](https://github.com/bennyn/coinbase-pro-node/pull/142)) ([17e2ad59](https://github.com/bennyn/coinbase-pro-node/commit/17e2ad59dd589816d9c940d0c615ef2088d137bc))
- Emit WebSocket message errors ([#141](https://github.com/bennyn/coinbase-pro-node/pull/141)) ([031f4d76](https://github.com/bennyn/coinbase-pro-node/commit/031f4d76caa3b10a049f129903044a24b9f0f8bf))

##### Tests

- Load environment variables in demo scripts ([80f70be9](https://github.com/bennyn/coinbase-pro-node/commit/80f70be9d20fefa6f232062cacf3464f7f3b5b1c))
- Use subscription update events in WebSocket tests ([a04aa138](https://github.com/bennyn/coinbase-pro-node/commit/a04aa1387a767f10a991747e927716eba0a62841))

## 2.0.0 (2020-04-24)

##### Documentation Changes

- Use absolute url ([d3cad314](https://github.com/bennyn/coinbase-pro-node/commit/d3cad31442c7e0dcebc10c54664eaea358b60bfe))

##### New Features

- Support pagination ([#138](https://github.com/bennyn/coinbase-pro-node/pull/138)) ([0446a2ab](https://github.com/bennyn/coinbase-pro-node/commit/0446a2ab32784f3c1014d7e51fbd2052d5cb68b3))

##### Bug Fixes

- Use correct sandbox API key in demo ([fd741230](https://github.com/bennyn/coinbase-pro-node/commit/fd74123060102dc2e918da48aa2e095684349071))

#### 1.8.3 (2020-04-20)

##### Chores

- **deps:**
  - bump axios-retry from 3.1.2 to 3.1.5 ([#135](https://github.com/bennyn/coinbase-pro-node/pull/135)) ([13375497](https://github.com/bennyn/coinbase-pro-node/commit/1337549775717c96b1e90fc959f6fea7983dc8d5))
  - bump @types/ws from 7.2.3 to 7.2.4 ([#132](https://github.com/bennyn/coinbase-pro-node/pull/132)) ([744e11b2](https://github.com/bennyn/coinbase-pro-node/commit/744e11b231b338c61055d77c0b95e69ccf8fb577))
- **deps-dev:**
  - bump @typescript-eslint/parser from 2.27.0 to 2.28.0 ([#133](https://github.com/bennyn/coinbase-pro-node/pull/133)) ([1e55d343](https://github.com/bennyn/coinbase-pro-node/commit/1e55d343eaa5ad096ac304be3883fbc77ad858ec))
  - bump lint-staged from 10.1.3 to 10.1.6 ([#130](https://github.com/bennyn/coinbase-pro-node/pull/130)) ([f3d1b921](https://github.com/bennyn/coinbase-pro-node/commit/f3d1b9210b64c3c51e43d8678c1c7cc31b755c0f))
  - bump @typescript-eslint/eslint-plugin ([#129](https://github.com/bennyn/coinbase-pro-node/pull/129)) ([a8b689c5](https://github.com/bennyn/coinbase-pro-node/commit/a8b689c5fdbbe0a4082a6be1caa1edbc160882b8))

##### Documentation Changes

- Update homepage url ([d721a409](https://github.com/bennyn/coinbase-pro-node/commit/d721a40979403bccd62c1f55552e66e35cf10623))
- Serve all content over HTTPS ([48c253c0](https://github.com/bennyn/coinbase-pro-node/commit/48c253c098b00c2809a3b1bca047ff5459cfcb8a))

##### New Features

- Add utility to generate previous timestamp ([#136](https://github.com/bennyn/coinbase-pro-node/pull/136)) ([9fa65b96](https://github.com/bennyn/coinbase-pro-node/commit/9fa65b96101c2b5da7be9e46ea1819c256c07489))
- Add utility to generate next timestamp ([#134](https://github.com/bennyn/coinbase-pro-node/pull/134)) ([850d5377](https://github.com/bennyn/coinbase-pro-node/commit/850d5377cfab0f0aff7e71f50949a48bfddfeb3a))

##### Refactors

- Require timestamp of last candle when watching candles ([#137](https://github.com/bennyn/coinbase-pro-node/pull/137)) ([cbf2d9b0](https://github.com/bennyn/coinbase-pro-node/commit/cbf2d9b05937a98ab7c0ea8c91ef32dfe40f932f))

#### 1.8.2 (2020-04-18)

##### Chores

- **deps-dev:**
  - bump prettier from 2.0.3 to 2.0.4 ([#125](https://github.com/bennyn/coinbase-pro-node/pull/125)) ([1f2cc157](https://github.com/bennyn/coinbase-pro-node/commit/1f2cc15778dab1648065e8c33994f20d9d3a654c))
  - bump @typescript-eslint/parser from 2.26.0 to 2.27.0 ([#127](https://github.com/bennyn/coinbase-pro-node/pull/127)) ([afdb5825](https://github.com/bennyn/coinbase-pro-node/commit/afdb582508d5f13222232d473c45a61f64900e05))
  - bump husky from 4.2.3 to 4.2.5 ([#126](https://github.com/bennyn/coinbase-pro-node/pull/126)) ([ddd31e01](https://github.com/bennyn/coinbase-pro-node/commit/ddd31e01145d301adecfda60e00d1e9db1fc5b08))
  - bump @typescript-eslint/eslint-plugin ([#124](https://github.com/bennyn/coinbase-pro-node/pull/124)) ([3be59b4c](https://github.com/bennyn/coinbase-pro-node/commit/3be59b4c7b18f3562db8383ee96c6f4333f81116))
  - bump lint-staged from 10.1.2 to 10.1.3 ([#123](https://github.com/bennyn/coinbase-pro-node/pull/123)) ([2a5dd2f0](https://github.com/bennyn/coinbase-pro-node/commit/2a5dd2f0ee38c853b0e8c74cb3477cf797ee575c))
  - bump eslint-plugin-prettier from 3.1.2 to 3.1.3 ([#122](https://github.com/bennyn/coinbase-pro-node/pull/122)) ([c7570e53](https://github.com/bennyn/coinbase-pro-node/commit/c7570e53e419b0296e2a1bca7d899be02c62a48f))

##### Bug Fixes

- Throw error on duplicate candle watching ([#128](https://github.com/bennyn/coinbase-pro-node/pull/128)) ([8dd239ba](https://github.com/bennyn/coinbase-pro-node/commit/8dd239ba3ca024002683866243cbb356f8e8ddef))

#### 1.8.1 (2020-04-11)

##### New Features

- Add candle interval mappings ([#121](https://github.com/bennyn/coinbase-pro-node/pull/121)) ([82c6e41f](https://github.com/bennyn/coinbase-pro-node/commit/82c6e41f5e58d0f691d88cbe0e7997c2dd823aac))

### 1.8.0 (2020-04-11)

##### Chores

- **deps-dev:**
  - bump prettier from 2.0.2 to 2.0.3 ([#119](https://github.com/bennyn/coinbase-pro-node/pull/119)) ([3f6238eb](https://github.com/bennyn/coinbase-pro-node/commit/3f6238eb3850158c46418cfc6f85fc165cf5b735))
  - bump lint-staged from 10.0.10 to 10.1.2 ([#117](https://github.com/bennyn/coinbase-pro-node/pull/117)) ([515223d3](https://github.com/bennyn/coinbase-pro-node/commit/515223d37ee46620e08ff7517dbeb937b113c7ec))
  - bump @typescript-eslint/eslint-plugin ([#118](https://github.com/bennyn/coinbase-pro-node/pull/118)) ([3d3655da](https://github.com/bennyn/coinbase-pro-node/commit/3d3655da2c7833fcb5066ea32f1518d75539ef7c))
  - bump ts-node from 8.8.1 to 8.8.2 ([#116](https://github.com/bennyn/coinbase-pro-node/pull/116)) ([4dbbe066](https://github.com/bennyn/coinbase-pro-node/commit/4dbbe066e19dde6b876efcad4cec131b9923d0b9))
  - bump nyc from 15.0.0 to 15.0.1 ([#115](https://github.com/bennyn/coinbase-pro-node/pull/115)) ([0b2f9a35](https://github.com/bennyn/coinbase-pro-node/commit/0b2f9a35c115b9014b6a524250280e957d83e632))
  - bump typedoc from 0.17.3 to 0.17.4 ([#114](https://github.com/bennyn/coinbase-pro-node/pull/114)) ([7e74808a](https://github.com/bennyn/coinbase-pro-node/commit/7e74808a11cda716e0d6198646f35c249ecf4c60))
  - bump @typescript-eslint/parser from 2.25.0 to 2.26.0 ([#113](https://github.com/bennyn/coinbase-pro-node/pull/113)) ([137c9532](https://github.com/bennyn/coinbase-pro-node/commit/137c9532883bedb099e250a4f5f5156416940220))

##### Refactors

- Define opening time in candles ([#120](https://github.com/bennyn/coinbase-pro-node/pull/120)) ([1268bc91](https://github.com/bennyn/coinbase-pro-node/commit/1268bc91b1376e25012cf036bce4734e1896a184))

#### 1.7.1 (2020-04-05)

##### Documentation Changes

- Add documentation site generator ([#112](https://github.com/bennyn/coinbase-pro-node/pull/112)) ([9c3356d1](https://github.com/bennyn/coinbase-pro-node/commit/9c3356d10922a0d543649312c6424175e04e4438))

### 1.7.0 (2020-04-05)

##### New Features

- Watch candles ([#111](https://github.com/bennyn/coinbase-pro-node/pull/111)) ([2a30f9c5](https://github.com/bennyn/coinbase-pro-node/commit/2a30f9c5481d78c42cf1701d4e0d1328f09d1084))

#### 1.6.1 (2020-04-04)

##### Documentation Changes

- Add contribution example ([c08c424e](https://github.com/bennyn/coinbase-pro-node/commit/c08c424e401bb7a0a8aea59e1765f51f5a553a01))

##### New Features

- Add WebSocket event for subscription updates ([#110](https://github.com/bennyn/coinbase-pro-node/pull/110)) ([4915c515](https://github.com/bennyn/coinbase-pro-node/commit/4915c5159cbabd331b837cf33259932acc78edf8))
- Get current fees ([#109](https://github.com/bennyn/coinbase-pro-node/pull/109)) ([9920c2f4](https://github.com/bennyn/coinbase-pro-node/commit/9920c2f4343985c349b68e2a47d7fe2c42e23e34))

##### Bug Fixes

- Correct type of fill price ([4a80aa27](https://github.com/bennyn/coinbase-pro-node/commit/4a80aa275432824ec52d59a3947ed3359ff301f9))

### 1.6.0 (2020-03-31)

##### Chores

- **deps-dev:** bump lint-staged from 10.0.9 to 10.0.10 ([#104](https://github.com/bennyn/coinbase-pro-node/pull/104)) ([3fdb6e64](https://github.com/bennyn/coinbase-pro-node/commit/3fdb6e6448056e5146b1b65ba0362b1faba3e4bb))

##### New Features

- Accept custom WebSocket reconnect options ([#106](https://github.com/bennyn/coinbase-pro-node/pull/106)) ([75032291](https://github.com/bennyn/coinbase-pro-node/commit/75032291e4997d733b75e9561e29f1a27aa2e7be))

#### 1.5.1 (2020-03-30)

##### Chores

- **deps:** Remove unused sub-dependencies ([a2a97b39](https://github.com/bennyn/coinbase-pro-node/commit/a2a97b395cd748a6e5bbc9f11f2dd72549eb0839))

##### New Features

- Improve rate limiting to fetch candles ([#103](https://github.com/bennyn/coinbase-pro-node/pull/103)) ([23e83556](https://github.com/bennyn/coinbase-pro-node/commit/23e83556b8a8f80a0879f059255bf62700b5a772))

##### Refactors

- Unify persistence of interceptors ([2da51762](https://github.com/bennyn/coinbase-pro-node/commit/2da51762b4628e548dadafc376e7ea68845013e0))
- Rename demo script ([a9d944ae](https://github.com/bennyn/coinbase-pro-node/commit/a9d944ae8257b529d694fb670e5fa7477d6dab52))

### 1.5.0 (2020-03-27)

##### Documentation Changes

- Document self verification ([7dc106b2](https://github.com/bennyn/coinbase-pro-node/commit/7dc106b26270b517c642f652356f31493dd55a5d))

##### New Features

- Emit WebSocket errors ([#101](https://github.com/bennyn/coinbase-pro-node/pull/101)) ([d3b6e3b7](https://github.com/bennyn/coinbase-pro-node/commit/d3b6e3b7d8b835d21cae6304c0031f4dd5aaf1c6))

#### 1.4.2 (2020-03-26)

##### Chores

- Reduce Prettier output ([bc2bbcd5](https://github.com/bennyn/coinbase-pro-node/commit/bc2bbcd5a4ca67c11b673732ff85deb55e26d843))
- **deps:**
  - yarn upgrade --latest ([28a0f92b](https://github.com/bennyn/coinbase-pro-node/commit/28a0f92b2650f0eee51657f8bc31502a3e27d636))
  - yarn upgrade --latest ([19b769b5](https://github.com/bennyn/coinbase-pro-node/commit/19b769b5e564a6aef12d00dabb3c5203362b30e7))

##### Documentation Changes

- Mention sandbox implications ([71d4bf9d](https://github.com/bennyn/coinbase-pro-node/commit/71d4bf9daf9aa361bf202a1e139060c5169a80b3))

##### New Features

- Batch historic rates requests to bypass time range errors ([#96](https://github.com/bennyn/coinbase-pro-node/pull/96)) ([b41a6e21](https://github.com/bennyn/coinbase-pro-node/commit/b41a6e21906a2569256cda733701573cb75ce19f))

##### Bug Fixes

- Don't fetch candle starting at end time ([#99](https://github.com/bennyn/coinbase-pro-node/pull/99)) ([26c70962](https://github.com/bennyn/coinbase-pro-node/commit/26c70962bfa8c1a8b8498fcb745378c4255b91ca))

#### 1.4.1 (2020-03-22)

##### Documentation Changes

- Add TypeDoc setup ([#95](https://github.com/bennyn/coinbase-pro-node/pull/95)) ([2db970d3](https://github.com/bennyn/coinbase-pro-node/commit/2db970d3ebbf81d2cf0e8fd5424a32aa68a14134))

##### Bug Fixes

- Convert candlestick times to milliseconds ([#94](https://github.com/bennyn/coinbase-pro-node/pull/94)) ([35a66dfd](https://github.com/bennyn/coinbase-pro-node/commit/35a66dfd04d6c63934d43923f638cc46d47ed8e0))

### 1.4.0 (2020-03-20)

##### Chores

- **deps:**
  - yarn upgrade --latest ([d0a54c90](https://github.com/bennyn/coinbase-pro-node/commit/d0a54c9005479bf0e4c993682c26db705d693f6b))
  - bump ws from 7.2.2 to 7.2.3 ([#90](https://github.com/bennyn/coinbase-pro-node/pull/90)) ([ca6d5197](https://github.com/bennyn/coinbase-pro-node/commit/ca6d51972a539eb24e2102d952e3e0956511b644))
  - [security] bump acorn from 7.1.0 to 7.1.1 ([#86](https://github.com/bennyn/coinbase-pro-node/pull/86)) ([4972a37f](https://github.com/bennyn/coinbase-pro-node/commit/4972a37fd9de1ae36f113e7411af07fcaa6ac292))
  - bump ws from 7.2.1 to 7.2.2 ([#79](https://github.com/bennyn/coinbase-pro-node/pull/79)) ([e21e0f1a](https://github.com/bennyn/coinbase-pro-node/commit/e21e0f1a0cd086339a90bfe73c0ff46d221665dd))
- **deps-dev:**
  - bump @typescript-eslint/parser from 2.22.0 to 2.23.0 ([#88](https://github.com/bennyn/coinbase-pro-node/pull/88)) ([3d1ce013](https://github.com/bennyn/coinbase-pro-node/commit/3d1ce01358524314f61776f9feaf105ca74a1f01))
  - bump @types/jasmine from 3.5.8 to 3.5.9 ([#89](https://github.com/bennyn/coinbase-pro-node/pull/89)) ([43e560d8](https://github.com/bennyn/coinbase-pro-node/commit/43e560d8b8e3cd76e889818de82d33247fac6686))
  - bump @typescript-eslint/eslint-plugin ([#87](https://github.com/bennyn/coinbase-pro-node/pull/87)) ([d723038b](https://github.com/bennyn/coinbase-pro-node/commit/d723038bcfdeee1e5c1095f746dfe77c81d4abb4))
  - bump @typescript-eslint/eslint-plugin ([#82](https://github.com/bennyn/coinbase-pro-node/pull/82)) ([89939eae](https://github.com/bennyn/coinbase-pro-node/commit/89939eae12d0a60c07045f993b67d689c6d3b733))
  - bump cross-env from 7.0.0 to 7.0.2 ([#80](https://github.com/bennyn/coinbase-pro-node/pull/80)) ([b06f8ca5](https://github.com/bennyn/coinbase-pro-node/commit/b06f8ca5577d04145f030827599ef1bbc0ca2a43))
  - bump @types/jasmine from 3.5.7 to 3.5.8 ([#83](https://github.com/bennyn/coinbase-pro-node/pull/83)) ([3e2e91f9](https://github.com/bennyn/coinbase-pro-node/commit/3e2e91f994f01025956090acd81380b8a3aab2d9))
  - bump @typescript-eslint/parser from 2.21.0 to 2.22.0 ([#81](https://github.com/bennyn/coinbase-pro-node/pull/81)) ([bc0e96a3](https://github.com/bennyn/coinbase-pro-node/commit/bc0e96a35f3e56ed7749a0e9bca5fa332aec3639))

##### Documentation Changes

- Describe WebSocket channel subscription ([#85](https://github.com/bennyn/coinbase-pro-node/pull/85)) ([cf92123a](https://github.com/bennyn/coinbase-pro-node/commit/cf92123aa9a75ecebbb101317d90e0395a8cccc6))

##### New Features

- Subscribe to multiple WebSocket channels at once ([#92](https://github.com/bennyn/coinbase-pro-node/pull/92)) ([ae9db0ae](https://github.com/bennyn/coinbase-pro-node/commit/ae9db0ae0bdfdd5bcf2b27cf088b5d5e8ff4e7f4))
- Emit all WebSocket messages with one generic event ([#91](https://github.com/bennyn/coinbase-pro-node/pull/91)) ([8d9979c4](https://github.com/bennyn/coinbase-pro-node/commit/8d9979c4bf72cdd29ee4031071bdfa8db1840068))

### 1.3.0 (2020-03-02)

##### Chores

- **deps-dev:**
  - bump @types/jasmine from 3.5.6 to 3.5.7 ([#76](https://github.com/bennyn/coinbase-pro-node/pull/76)) ([7fdbdeef](https://github.com/bennyn/coinbase-pro-node/commit/7fdbdeefced1c3e8b126a5abd42425df160358f2))
  - bump lint-staged from 10.0.7 to 10.0.8 ([#73](https://github.com/bennyn/coinbase-pro-node/pull/73)) ([4a3daa8f](https://github.com/bennyn/coinbase-pro-node/commit/4a3daa8f6a79034d9479fae6e288f0f97f4dd6f5))
  - bump @typescript-eslint/eslint-plugin ([#72](https://github.com/bennyn/coinbase-pro-node/pull/72)) ([163b10be](https://github.com/bennyn/coinbase-pro-node/commit/163b10be8982b528e204941403c556ecb21b68ae))
  - bump @typescript-eslint/parser from 2.20.0 to 2.21.0 ([#74](https://github.com/bennyn/coinbase-pro-node/pull/74)) ([9e887104](https://github.com/bennyn/coinbase-pro-node/commit/9e887104ab742638319629b66c1cd4e4d87fa514))
  - bump nock from 12.0.1 to 12.0.2 ([#75](https://github.com/bennyn/coinbase-pro-node/pull/75)) ([14a88455](https://github.com/bennyn/coinbase-pro-node/commit/14a88455a8f1b27fb48fb392273a9e5396700ccc))
  - bump typescript from 3.8.2 to 3.8.3 ([#71](https://github.com/bennyn/coinbase-pro-node/pull/71)) ([5f3ae007](https://github.com/bennyn/coinbase-pro-node/commit/5f3ae0071640b5c41f4eeabee0f7b1ecd5282b0c))
- **deps:** bump @types/ws from 7.2.1 to 7.2.2 ([#77](https://github.com/bennyn/coinbase-pro-node/pull/77)) ([b0393780](https://github.com/bennyn/coinbase-pro-node/commit/b03937801f0e4e9503bfa479b5ae81957b6451b6))
- Report errors on unused parameters ([a64f8fd2](https://github.com/bennyn/coinbase-pro-node/commit/a64f8fd260953e5cd239eceabe6db00fe21efabe))

##### Documentation Changes

- Document account resources ([#78](https://github.com/bennyn/coinbase-pro-node/pull/78)) ([ba32406f](https://github.com/bennyn/coinbase-pro-node/commit/ba32406f460ea0d8af9d90b292ee92d91eaa911e))
- Document product resources ([#68](https://github.com/bennyn/coinbase-pro-node/pull/68)) ([e7df8204](https://github.com/bennyn/coinbase-pro-node/commit/e7df820414806ee5a6f17f792be594903554cbf5))

##### New Features

- Add automatic request throttling for rate limits ([#70](https://github.com/bennyn/coinbase-pro-node/pull/70)) ([a07260c0](https://github.com/bennyn/coinbase-pro-node/commit/a07260c0d347d7bf470cf821832090578ea837f2))
- Add utility to determine candle buckets ([#69](https://github.com/bennyn/coinbase-pro-node/pull/69)) ([1e5f9237](https://github.com/bennyn/coinbase-pro-node/commit/1e5f9237cb86248be94cf4148b7fee5b6d4c82ca))

### 1.2.0 (2020-02-24)

##### Chores

- **deps-dev:**
  - bump @typescript-eslint/parser from 2.19.2 to 2.20.0 ([#61](https://github.com/bennyn/coinbase-pro-node/pull/61)) ([c2594b8e](https://github.com/bennyn/coinbase-pro-node/commit/c2594b8ee7f19363f7547c7081a4f909b1ee7a4f))
  - bump @typescript-eslint/eslint-plugin ([#64](https://github.com/bennyn/coinbase-pro-node/pull/64)) ([17db6bdf](https://github.com/bennyn/coinbase-pro-node/commit/17db6bdf4cf814281d94ba6ec85b9c1e5578c9b7))
  - bump nock from 12.0.0 to 12.0.1 ([#65](https://github.com/bennyn/coinbase-pro-node/pull/65)) ([73af81b9](https://github.com/bennyn/coinbase-pro-node/commit/73af81b9fd23287132e7281fcccc68fb1f6de791))
  - bump @types/jasmine from 3.5.4 to 3.5.6 ([#63](https://github.com/bennyn/coinbase-pro-node/pull/63)) ([950390f1](https://github.com/bennyn/coinbase-pro-node/commit/950390f15d6188535a22af097e7c7e0439872576))
  - bump typescript from 3.7.5 to 3.8.2 ([#62](https://github.com/bennyn/coinbase-pro-node/pull/62)) ([e3262249](https://github.com/bennyn/coinbase-pro-node/commit/e32622497ea19d2486eb326eea839b00adaa2fec))

##### New Features

- Export type for "matches" channel from WebSocket ([#67](https://github.com/bennyn/coinbase-pro-node/pull/67)) ([b84de740](https://github.com/bennyn/coinbase-pro-node/commit/b84de7404fd0f7c2c14c26ee47571b5f971dc373))
- Export type for ticker message from WebSocket ([#66](https://github.com/bennyn/coinbase-pro-node/pull/66)) ([5329ff6b](https://github.com/bennyn/coinbase-pro-node/commit/5329ff6b48c1e3581d8e5dc609a2b079914f5a8b))

### 1.1.0 (2020-02-21)

##### Chores

- Always do releases from master branch ([291c854c](https://github.com/bennyn/coinbase-pro-node/commit/291c854c54a86b2e09263ad2b3ececf251b79e3c))

##### Documentation Changes

- updated CHANGELOG.md ([22b66cf0](https://github.com/bennyn/coinbase-pro-node/commit/22b66cf0eea3b77aa9ac851b9f54bb419110cd57))

##### New Features

- Export WebSocket response types ([#60](https://github.com/bennyn/coinbase-pro-node/pull/60)) ([ad4c985e](https://github.com/bennyn/coinbase-pro-node/commit/ad4c985efb4ec1e02e35042c18d4cacf195ce001))

##### Refactors

- Set public access modifiers by default ([#59](https://github.com/bennyn/coinbase-pro-node/pull/59)) ([9cb1ba86](https://github.com/bennyn/coinbase-pro-node/commit/9cb1ba86d02f7c4b773c19d35f92ffde9fa21739))

### 1.1.0 (2020-02-21)

##### Chores

- Always do releases from master branch ([291c854c](https://github.com/bennyn/coinbase-pro-node/commit/291c854c54a86b2e09263ad2b3ececf251b79e3c))

##### New Features

- Export WebSocket response types ([#60](https://github.com/bennyn/coinbase-pro-node/pull/60)) ([ad4c985e](https://github.com/bennyn/coinbase-pro-node/commit/ad4c985efb4ec1e02e35042c18d4cacf195ce001))

##### Refactors

- Set public access modifiers by default ([#59](https://github.com/bennyn/coinbase-pro-node/pull/59)) ([9cb1ba86](https://github.com/bennyn/coinbase-pro-node/commit/9cb1ba86d02f7c4b773c19d35f92ffde9fa21739))

#### 1.0.1 (2020-02-20)

##### Bug Fixes

- `EventEmitter` constructor function type in `WebSocketClient` ([#57](https://github.com/bennyn/coinbase-pro-node/pull/57)) ([bd1a358c](https://github.com/bennyn/coinbase-pro-node/commit/bd1a358c12f18ff09500e549f36c4962fc39b702))

## 1.0.0 (2020-02-20)

##### New Features

- Export response types ([#56](https://github.com/bennyn/coinbase-pro-node/pull/56)) ([7fff578c](https://github.com/bennyn/coinbase-pro-node/commit/7fff578cf7e757c7bc408d56fc4414239b12f87c))

#### 0.11.2 (2020-02-18)

##### Chores

- Publish tests ([d751ba23](https://github.com/bennyn/coinbase-pro-node/commit/d751ba23422e1b48dd2cd0f76bbbc9f9f87e1ac0))

#### 0.11.1 (2020-02-18)

##### Chores

- Remove start script from publication ([#55](https://github.com/bennyn/coinbase-pro-node/pull/55)) ([a480e769](https://github.com/bennyn/coinbase-pro-node/commit/a480e76937a8ffd10296f8b4f1dc51190608426a))
- Adjust badge url to be found with "node-detect-readme-badges" ([b6eb427c](https://github.com/bennyn/coinbase-pro-node/commit/b6eb427c7b151bd76fa2ca764e9530a72cb73230))

### 0.11.0 (2020-02-18)

##### Chores

- Adjust line endings ([#53](https://github.com/bennyn/coinbase-pro-node/pull/53)) ([b51086d1](https://github.com/bennyn/coinbase-pro-node/commit/b51086d18a5ff63831c7828265a9c7b33dc7f979))
- Add custom homepage ([63c63f03](https://github.com/bennyn/coinbase-pro-node/commit/63c63f039c70e9f397455fbac478c76de00e6604))
- Adjust badge urls to be found with "node-detect-readme-badges" ([2f38a459](https://github.com/bennyn/coinbase-pro-node/commit/2f38a459bdd5061b37a4c06fc964d0f42df9dcb8))
- Add EditorConfig ([9ed33222](https://github.com/bennyn/coinbase-pro-node/commit/9ed3322278a7779c0f4560b471d80bc233d65a22))

##### New Features

- Expose WebSocket channels for "status" and "user" ([#54](https://github.com/bennyn/coinbase-pro-node/pull/54)) ([f922ab81](https://github.com/bennyn/coinbase-pro-node/commit/f922ab81bdf3e5e7305e71e485b4c03b4abe3eed))

### 0.10.0 (2020-02-17)

##### Chores

- **deps-dev:**
  - bump @typescript-eslint/parser from 2.19.0 to 2.19.2 ([#51](https://github.com/bennyn/coinbase-pro-node/pull/51)) ([5b6e55bb](https://github.com/bennyn/coinbase-pro-node/commit/5b6e55bb5346e4a6d006b861bec4da49904fed29))
  - bump @typescript-eslint/eslint-plugin ([#50](https://github.com/bennyn/coinbase-pro-node/pull/50)) ([785c0aca](https://github.com/bennyn/coinbase-pro-node/commit/785c0acad62d23a2b7ddca822e2e9db7df677f9e))
  - bump nock from 11.7.2 to 12.0.0 ([#48](https://github.com/bennyn/coinbase-pro-node/pull/48)) ([c6473912](https://github.com/bennyn/coinbase-pro-node/commit/c64739129f9f5923c7756f750f68a06c3816a34a))
  - bump @types/jasmine from 3.5.3 to 3.5.4 ([#49](https://github.com/bennyn/coinbase-pro-node/pull/49)) ([7807ffdb](https://github.com/bennyn/coinbase-pro-node/commit/7807ffdbb09219ba0047960e75baae6f8fe19855))
  - bump husky from 4.2.1 to 4.2.3 ([#47](https://github.com/bennyn/coinbase-pro-node/pull/47)) ([8383c695](https://github.com/bennyn/coinbase-pro-node/commit/8383c6954f6b80c8790908771cba2051bd2be410))

##### New Features

- Get Trades ([#52](https://github.com/bennyn/coinbase-pro-node/pull/52)) ([722fab5d](https://github.com/bennyn/coinbase-pro-node/commit/722fab5d303d8e3d0a7af896b0d72393fcaf0b33))

##### Bug Fixes

- Correct return type for order book depth of level 3 ([#46](https://github.com/bennyn/coinbase-pro-node/pull/46)) ([695afb94](https://github.com/bennyn/coinbase-pro-node/commit/695afb94fd5f85ea2d8ef56ee86880693fc7f3fd))

#### 0.9.5 (2020-02-11)

##### Chores

- Upload coverage reports to Codecov ([#44](https://github.com/bennyn/coinbase-pro-node/pull/44)) ([593e2c6a](https://github.com/bennyn/coinbase-pro-node/commit/593e2c6afc1d88eb9b0f0e23c434924e1f7eefdf))
- Don't publish test directory ([81c367db](https://github.com/bennyn/coinbase-pro-node/commit/81c367db10577be807542d23268dbf7aeb7b5014))
- **deps-dev:**
  - bump @types/jasmine from 3.5.2 to 3.5.3 ([#41](https://github.com/bennyn/coinbase-pro-node/pull/41)) ([4b2246d5](https://github.com/bennyn/coinbase-pro-node/commit/4b2246d52b9e3bdcadea58fcd8c7082eaa8d6c0c))
  - bump @typescript-eslint/parser from 2.18.0 to 2.19.0 ([#43](https://github.com/bennyn/coinbase-pro-node/pull/43)) ([83274d16](https://github.com/bennyn/coinbase-pro-node/commit/83274d1639c09ea39b971b443b941c82b28a967e))
  - bump rimraf from 3.0.1 to 3.0.2 ([#42](https://github.com/bennyn/coinbase-pro-node/pull/42)) ([4db51e45](https://github.com/bennyn/coinbase-pro-node/commit/4db51e45442444c338da85efbd9b7f3629e56012))
  - bump @typescript-eslint/eslint-plugin ([#39](https://github.com/bennyn/coinbase-pro-node/pull/39)) ([eceed887](https://github.com/bennyn/coinbase-pro-node/commit/eceed8878bd9d4c7edfbe2562558333e69f41eea))
- **deps:** bump reconnecting-websocket from 4.3.0 to 4.4.0 ([#40](https://github.com/bennyn/coinbase-pro-node/pull/40)) ([69b16258](https://github.com/bennyn/coinbase-pro-node/commit/69b16258d0a05b2fc3f305edd56e734e5c132c93))

##### Documentation Changes

- Update example titles ([d3856360](https://github.com/bennyn/coinbase-pro-node/commit/d38563607cb6166aabb4a2456fd6c2b6831eb243))
- Add badges ([8f1f05c4](https://github.com/bennyn/coinbase-pro-node/commit/8f1f05c4da9b718675732ff57e1aac6d1ed0f2b4))

##### New Features

- Get Product Order Book ([#45](https://github.com/bennyn/coinbase-pro-node/pull/45)) ([976b2a79](https://github.com/bennyn/coinbase-pro-node/commit/976b2a797508e2b313d2b01632e90068f3d08b75))

#### 0.9.4 (2020-02-09)

##### New Features

- Add profile / portfolio resource ([#38](https://github.com/bennyn/coinbase-pro-node/pull/38)) ([452af03a](https://github.com/bennyn/coinbase-pro-node/commit/452af03aa2d2f6c923c46688ee4891568aa0c413))

##### Refactors

- Export common types ([13a9bef8](https://github.com/bennyn/coinbase-pro-node/commit/13a9bef8220a3db71a5f3f0c88a4003355a9539e))

#### 0.9.3 (2020-02-09)

##### Chores

- Lint staged TypeScript files ([1da88850](https://github.com/bennyn/coinbase-pro-node/commit/1da88850433bea75e0ca8e8b50757aa2f305b0d5))

##### Refactors

- Add `useSandbox` to `ClientAuthentication` ([#37](https://github.com/bennyn/coinbase-pro-node/pull/37)) ([72e9b556](https://github.com/bennyn/coinbase-pro-node/commit/72e9b5565abe9efc88a15b687814b9f20ad2aa9e))

##### Tests

- Check types on test run ([10754003](https://github.com/bennyn/coinbase-pro-node/commit/10754003bf57f39511c141627534136c7d6ac5fb))

#### 0.9.2 (2020-02-05)

##### New Features

- Request trailing volume ([#29](https://github.com/bennyn/coinbase-pro-node/pull/29)) ([8a150fec](https://github.com/bennyn/coinbase-pro-node/commit/8a150fecb7d32b7b7cd39a8109985f665aaee26e))

### 0.9.0 (2020-01-26)

##### New Features

- List recent fills ([#18](https://github.com/bennyn/coinbase-pro-node/pull/18)) ([1d8edc30](https://github.com/bennyn/coinbase-pro-node/commit/1d8edc3009d4d9be3d2abba69954ea2642bbea6b))
