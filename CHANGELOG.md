# Changelog

## 0.1.0-alpha.2 (2025-11-26)

Full Changelog: [v0.1.0-alpha.1...v0.1.0-alpha.2](https://github.com/alexarena/todo-ninja-typescript/compare/v0.1.0-alpha.1...v0.1.0-alpha.2)

### Features

* **api:** manual updates ([4df7a02](https://github.com/alexarena/todo-ninja-typescript/commit/4df7a02d10924f833f812962cd5f873f6045ea3d))
* **api:** manual updates ([42363c4](https://github.com/alexarena/todo-ninja-typescript/commit/42363c4c879f4838f4f82571f1a1290a03aaf0bf))
* **api:** update via SDK Studio ([d0f200b](https://github.com/alexarena/todo-ninja-typescript/commit/d0f200b6e9c48dc42be3cdf141ec4e881f689dde))
* **api:** update via SDK Studio ([5573d7e](https://github.com/alexarena/todo-ninja-typescript/commit/5573d7e831f9f3c6998ac06a523f954dcdaa8835))
* **api:** update via SDK Studio ([2a01875](https://github.com/alexarena/todo-ninja-typescript/commit/2a01875db93616760d9e44efc33983556c518766))
* **api:** update via SDK Studio ([74f6f2c](https://github.com/alexarena/todo-ninja-typescript/commit/74f6f2c4e2efde95cbcde37692e58bef1d634458))
* **client:** add support for endpoint-specific base URLs ([c640138](https://github.com/alexarena/todo-ninja-typescript/commit/c6401386f1bc8b78225109b23b0b48ea0b625205))
* **mcp:** implement support for binary responses ([fd29733](https://github.com/alexarena/todo-ninja-typescript/commit/fd297334cfa3ff2a5ea35c30044e93c2ff983e40))
* **mcp:** include http information in tools ([dabf58a](https://github.com/alexarena/todo-ninja-typescript/commit/dabf58af063a973f819475af7f66a7e8714ce72c))
* **mcp:** set X-Stainless-MCP header ([568e636](https://github.com/alexarena/todo-ninja-typescript/commit/568e636664e78165381723725169ca7ce6eda63b))
* **mcp:** support filtering tool results by a jq expression ([ae2f98f](https://github.com/alexarena/todo-ninja-typescript/commit/ae2f98f7477738e2ecdef1e0d6faeb903d6f3bd7))


### Bug Fixes

* **ci:** release-doctor — report correct token name ([8f5e154](https://github.com/alexarena/todo-ninja-typescript/commit/8f5e154a673e28ee32a3b691edf1d92c3c492fae))
* **client:** explicitly copy fetch in withOptions ([c7d77cf](https://github.com/alexarena/todo-ninja-typescript/commit/c7d77cfbaf824de412f9f6d392d7adadb8a1a5ce))
* **client:** get fetchOptions type more reliably ([cb4e952](https://github.com/alexarena/todo-ninja-typescript/commit/cb4e95222abc41df1ce080749ec718b4ddf25986))
* compat with more runtimes ([a16619d](https://github.com/alexarena/todo-ninja-typescript/commit/a16619da51c772fd0a160e3f08d34aa0deeecc41))
* **mcp:** define `.well-known/oauth-protected-resource` ([2ea159b](https://github.com/alexarena/todo-ninja-typescript/commit/2ea159b8dff9e66fa1adc645196fa53a34fa9a85))
* **mcp:** fix cursor schema transformation issue with recursive references ([5b8c8df](https://github.com/alexarena/todo-ninja-typescript/commit/5b8c8dfbb579121470f1948b183f25f82e33e8c9))
* **mcp:** include description in dynamic tool search ([1fbaf1e](https://github.com/alexarena/todo-ninja-typescript/commit/1fbaf1ec406a2ffd6ad55d9528c52817c96f989d))
* **mcp:** relax input type for asTextContextResult ([6337ec0](https://github.com/alexarena/todo-ninja-typescript/commit/6337ec0c8150a8667e433c85b26323707d043cc3))
* **mcp:** use correct character set in cloudflare worker name ([5c91668](https://github.com/alexarena/todo-ninja-typescript/commit/5c91668259d285b9657b53ccb6af0ca6c398b81e))
* publish script — handle NPM errors correctly ([cf40bc6](https://github.com/alexarena/todo-ninja-typescript/commit/cf40bc681a2189741884e9a7e961cc663fcf196b))


### Chores

* add docs to RequestOptions type ([f4d083a](https://github.com/alexarena/todo-ninja-typescript/commit/f4d083a8364f98a7ce5111537a76d50fd29c5279))
* adjust eslint.config.mjs ignore pattern ([f551fe8](https://github.com/alexarena/todo-ninja-typescript/commit/f551fe8aed35a2ccdbfbc0741a66bf1979ff6540))
* avoid type error in certain environments ([5a45af2](https://github.com/alexarena/todo-ninja-typescript/commit/5a45af2eaee4d2b0d9861a5e99a55174a7f2e3bc))
* **ci:** enable for pull requests ([fdd2122](https://github.com/alexarena/todo-ninja-typescript/commit/fdd2122bfbc0ad460395708a489997fcf28bee29))
* **ci:** only run for pushes and fork pull requests ([491125d](https://github.com/alexarena/todo-ninja-typescript/commit/491125d9c8b2f1e2fc916cc2a537e1e3836a7582))
* **client:** improve path param validation ([d4431c5](https://github.com/alexarena/todo-ninja-typescript/commit/d4431c5b6a4a569117247b31049d7115da0583d7))
* **client:** refactor imports ([4f224bf](https://github.com/alexarena/todo-ninja-typescript/commit/4f224bf53fe88165ec251eb874e9cb7f3234875f))
* configure new SDK language ([761f899](https://github.com/alexarena/todo-ninja-typescript/commit/761f89958655c568f3ea29aba25009027cb3dc6a))
* configure new SDK language ([60205c5](https://github.com/alexarena/todo-ninja-typescript/commit/60205c56a87ba5d673ba6e76a86969ffea69e136))
* configure new SDK language ([717c250](https://github.com/alexarena/todo-ninja-typescript/commit/717c250add1f2e6cde160f016b2286fc94f445ed))
* configure new SDK language ([e5bdf36](https://github.com/alexarena/todo-ninja-typescript/commit/e5bdf362addfc0e775a6d5218964f8c9f4e14fbd))
* **deps:** bump eslint-plugin-prettier ([04de430](https://github.com/alexarena/todo-ninja-typescript/commit/04de43057533183d866c52124acc53650ed373f1))
* **docs:** grammar improvements ([a71b878](https://github.com/alexarena/todo-ninja-typescript/commit/a71b87829952e80029d102d01ea89c4e47821d19))
* **docs:** use top-level-await in example snippets ([a12a7bc](https://github.com/alexarena/todo-ninja-typescript/commit/a12a7bce3bbfaf0b0db1a05e2aeaabd7a837cd5d))
* improve publish-npm script --latest tag logic ([86597ea](https://github.com/alexarena/todo-ninja-typescript/commit/86597ea232047ce241da318d86c46937880c69dc))
* **internal:** add pure annotations, make base APIResource abstract ([8172765](https://github.com/alexarena/todo-ninja-typescript/commit/8172765e2f643cdf46ef318a2838028b37df21b7))
* **internal:** codegen related update ([70c260c](https://github.com/alexarena/todo-ninja-typescript/commit/70c260cf84457a3239625df6ef81941d416600fd))
* **internal:** codegen related update ([aeebf75](https://github.com/alexarena/todo-ninja-typescript/commit/aeebf750568f34709eed54ccbca517282ce8b7d1))
* **internal:** codegen related update ([c840da7](https://github.com/alexarena/todo-ninja-typescript/commit/c840da7f834044f3b8a9a3baf603899b08233d12))
* **internal:** codegen related update ([f546e66](https://github.com/alexarena/todo-ninja-typescript/commit/f546e667eb65d808f0c431bbde30f7912e64836e))
* **internal:** codegen related update ([cce658d](https://github.com/alexarena/todo-ninja-typescript/commit/cce658dc9c873410f941ed14eedd63adbc27cd38))
* **internal:** codegen related update ([1ed4a5e](https://github.com/alexarena/todo-ninja-typescript/commit/1ed4a5ea4ff63a75d2d816aa663f830cdc2cbb41))
* **internal:** codegen related update ([6000281](https://github.com/alexarena/todo-ninja-typescript/commit/600028174432c6807bab7659c7dcbd59d88c73eb))
* **internal:** codegen related update ([f8a36c1](https://github.com/alexarena/todo-ninja-typescript/commit/f8a36c131d469ce825e6e237514eed4a88c4c2b5))
* **internal:** codegen related update ([c1bf4c5](https://github.com/alexarena/todo-ninja-typescript/commit/c1bf4c5a6a7a55cb2d36e6e25606916323fa251f))
* **internal:** codegen related update ([f7ac4ff](https://github.com/alexarena/todo-ninja-typescript/commit/f7ac4ff4f9d46dd53d80b15375a9b58d961c9966))
* **internal:** codegen related update ([38e1341](https://github.com/alexarena/todo-ninja-typescript/commit/38e134120cede7d4a75e018a1ddcce3bb13ee22c))
* **internal:** codegen related update ([fbc50d2](https://github.com/alexarena/todo-ninja-typescript/commit/fbc50d2089b9565f06506374a6e8507e38f0477c))
* **internal:** fix readablestream types in node 20 ([bc2e29e](https://github.com/alexarena/todo-ninja-typescript/commit/bc2e29e4715f836e2caf217e915c4655a85f563e))
* **internal:** update jest config ([64b3bd2](https://github.com/alexarena/todo-ninja-typescript/commit/64b3bd2f567a6d170cd9d37d2140b8c0818de90b))
* make some internal functions async ([0c0ebb3](https://github.com/alexarena/todo-ninja-typescript/commit/0c0ebb363e6564902f7b4110039c6099244fe141))
* **mcp:** remove duplicate assignment ([63cb56e](https://github.com/alexarena/todo-ninja-typescript/commit/63cb56e07036f2d5d9f0a3bacc1139168c7f427c))
* **readme:** update badges ([9756a4d](https://github.com/alexarena/todo-ninja-typescript/commit/9756a4d72d94318f3bcf84d4d8a7b2f376faf529))
* **readme:** use better example snippet for undocumented params ([f7754b6](https://github.com/alexarena/todo-ninja-typescript/commit/f7754b61ac2898a824ce6650a018b3f32a805db9))
* update SDK settings ([f2b785a](https://github.com/alexarena/todo-ninja-typescript/commit/f2b785a7039955a512c2121a567e1c62734d909f))


### Documentation

* **mcp:** correct instructions for adding to claude web ([4792713](https://github.com/alexarena/todo-ninja-typescript/commit/479271374f08c55daec15ff1481081ff92df2692))

## 0.1.0-alpha.1 (2025-05-14)

Full Changelog: [v0.0.1-alpha.0...v0.1.0-alpha.1](https://github.com/alexarena/todo-ninja-typescript/compare/v0.0.1-alpha.0...v0.1.0-alpha.1)

### Features

* **api:** update via SDK Studio ([3c5dd83](https://github.com/alexarena/todo-ninja-typescript/commit/3c5dd8369243beaed1d92ebfa4f1eef10c76e2f4))
* **api:** update via SDK Studio ([e8f26c4](https://github.com/alexarena/todo-ninja-typescript/commit/e8f26c46f064303025c8cc7adc39a2ff92ab67b6))
* **api:** update via SDK Studio ([e97a6c0](https://github.com/alexarena/todo-ninja-typescript/commit/e97a6c0863786d31063582bb86f5e0fd9fd24b10))
* **api:** update via SDK Studio ([1181cc5](https://github.com/alexarena/todo-ninja-typescript/commit/1181cc5669952ba68be162c421f11277c29d859b))
* **api:** update via SDK Studio ([bbb8a36](https://github.com/alexarena/todo-ninja-typescript/commit/bbb8a36709fcfa09dfb2a19012c6d0a5897a1d18))
* **api:** update via SDK Studio ([0657605](https://github.com/alexarena/todo-ninja-typescript/commit/065760593ba8b2aeae8d7f3f8bc6c4f1d3bbad56))
* **api:** update via SDK Studio ([0c44137](https://github.com/alexarena/todo-ninja-typescript/commit/0c441372eb95bb567553cf956fcffe1cd6db14d7))
* **api:** update via SDK Studio ([3a3bbae](https://github.com/alexarena/todo-ninja-typescript/commit/3a3bbaeae08834bf24304c11fb97168da1a1361a))
* **api:** update via SDK Studio ([ea76c78](https://github.com/alexarena/todo-ninja-typescript/commit/ea76c788adc191677ff0eb757d153ff1418c15af))
* **api:** update via SDK Studio ([8a33a7e](https://github.com/alexarena/todo-ninja-typescript/commit/8a33a7e9a235f65da4ff8cfc7df61e21338377a1))
* **api:** update via SDK Studio ([28c3781](https://github.com/alexarena/todo-ninja-typescript/commit/28c3781f24ec80b25fa0b9e22fe270f54a57f800))
* **client:** add withOptions helper ([9a1d333](https://github.com/alexarena/todo-ninja-typescript/commit/9a1d333980406ec2658e0b6f6540a39a1fc12890))


### Bug Fixes

* **client:** always overwrite when merging headers ([9de60a5](https://github.com/alexarena/todo-ninja-typescript/commit/9de60a560d0518aff9fc2dc1928751834b68496c))
* **internal:** fix file uploads in node 18 jest ([606b10d](https://github.com/alexarena/todo-ninja-typescript/commit/606b10da85d1451ea4b52a54d7baa79549ca4dc9))


### Chores

* **ci:** add timeout thresholds for CI jobs ([e16b516](https://github.com/alexarena/todo-ninja-typescript/commit/e16b5160880f45923d71449f4fc951f5b97353b9))
* **ci:** only use depot for staging repos ([9af8516](https://github.com/alexarena/todo-ninja-typescript/commit/9af851665ce2037ea2514c8628a8325e9a018f99))
* **client:** drop support for EOL node versions ([cc8f094](https://github.com/alexarena/todo-ninja-typescript/commit/cc8f09402f7b4ff2cad900fb8446bd8323e3ec88))
* **client:** minor internal fixes ([2fbadd4](https://github.com/alexarena/todo-ninja-typescript/commit/2fbadd4f9599f6458bfbefd0eb8e2dfb7222153a))
* configure new SDK language ([248b342](https://github.com/alexarena/todo-ninja-typescript/commit/248b342e2b7bc95bec1c7e625dac8ca09f93b587))
* **internal:** codegen related update ([65a3a2b](https://github.com/alexarena/todo-ninja-typescript/commit/65a3a2b2d10517e7b189673189fce25f06fc8cc9))
* **internal:** codegen related update ([bfd55c5](https://github.com/alexarena/todo-ninja-typescript/commit/bfd55c56371328811b37253b59f00041bf09d150))
* **internal:** reduce CI branch coverage ([973ef13](https://github.com/alexarena/todo-ninja-typescript/commit/973ef139df2a4cd2944b7e4bfed57d7507bfa787))
* **internal:** refactor utils ([7b8d7e9](https://github.com/alexarena/todo-ninja-typescript/commit/7b8d7e998c19588173d39135b01ff06cf1e3436e))
* **package:** remove engines ([040310a](https://github.com/alexarena/todo-ninja-typescript/commit/040310aed3206e1a8dd1d7688d85153d804809f8))
* **perf:** faster base64 decoding ([bfb9085](https://github.com/alexarena/todo-ninja-typescript/commit/bfb90850c3871c7c6b4df64ba093a8fc3ffe2020))
* update SDK settings ([77c4605](https://github.com/alexarena/todo-ninja-typescript/commit/77c4605b560db82d870de44849efcecdd952691f))
* update SDK settings ([ab18d30](https://github.com/alexarena/todo-ninja-typescript/commit/ab18d307b55ec3446c38fc6886b60f81ab17e786))


### Documentation

* add examples to tsdocs ([98801c1](https://github.com/alexarena/todo-ninja-typescript/commit/98801c1514c7392e3411bddb0bc308849fd66b49))
* align README.md with company style ([8f73d53](https://github.com/alexarena/todo-ninja-typescript/commit/8f73d53701b38911a47fcefada66ef1999d7e5c4))
* **readme:** fix typo ([26ee7f5](https://github.com/alexarena/todo-ninja-typescript/commit/26ee7f5836e2ba41a0b7b916d4a81f2823ac716d))
