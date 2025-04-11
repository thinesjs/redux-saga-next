# @redux-saga/delay-p

## 1.3.0

### Minor Changes

- [`80681f8`](https://github.com/thinesjs/redux-saga-next/commit/80681f8bba412e2d255c2af7c5079b9af130546a) Thanks [@thinesjs](https://github.com/thinesjs)! - changes

### Patch Changes

- Updated dependencies [[`80681f8`](https://github.com/thinesjs/redux-saga-next/commit/80681f8bba412e2d255c2af7c5079b9af130546a)]:
  - @redux-saga/symbols@1.2.0

## 1.2.1

### Patch Changes

- [#2324](https://github.com/redux-saga/redux-saga/pull/2324) [`2466c79`](https://github.com/redux-saga/redux-saga/commit/2466c798a5f56a5015e61c8fdf0ef8f2a6a852a4) Thanks [@neurosnap](https://github.com/neurosnap)! - Add LICENSE file

- Updated dependencies [[`2466c79`](https://github.com/redux-saga/redux-saga/commit/2466c798a5f56a5015e61c8fdf0ef8f2a6a852a4)]:
  - @redux-saga/symbols@1.1.3

## 1.2.0

### Minor Changes

- [#2308](https://github.com/redux-saga/redux-saga/pull/2308) [`8207e33`](https://github.com/redux-saga/redux-saga/commit/8207e33) Thanks [@Andarist](https://github.com/Andarist), [@neurosnap](https://github.com/neurosnap)! - `exports` field has been added to the `package.json` manifest. It limits what files can be imported from a package but we've tried our best to allow importing all the files that were considered to be a part of the public API.

  This should fix the compatibility with Node.js ESM support.

### Patch Changes

- [#2293](https://github.com/redux-saga/redux-saga/pull/2293) [`2d2214e`](https://github.com/redux-saga/redux-saga/commit/2d2214e9ca8949892c0a7a23ceef39fa32d13939) Thanks [@neurosnap](https://github.com/neurosnap)! - Fixed an issue with arguments that exceed the maximum value for the internally-used `setTimeout`. Previously it could overflow based on the input that was too big and thus a timeout could resolve immediately.
