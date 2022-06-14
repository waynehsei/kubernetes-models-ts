# Change Log

## 3.1.0

### Minor Changes

- [#75](https://github.com/tommy351/kubernetes-models-ts/pull/75) [`929ff88`](https://github.com/tommy351/kubernetes-models-ts/commit/929ff88dd0187cdf83e78317ad733b3f81de194a) Thanks [@tommy351](https://github.com/tommy351)! - Update CRDs to cert-manager v1.8.0.

## 3.0.2

### Patch Changes

- Updated dependencies [[`6e51206`](https://github.com/tommy351/kubernetes-models-ts/commit/6e512067557a938db902a88c18595fc7c76e9b37)]:
  - @kubernetes-models/apimachinery@0.2.0

## 3.0.1

### Patch Changes

- Updated dependencies []:
  - @kubernetes-models/apimachinery@0.1.0

## 3.0.0

### Major Changes

- [#66](https://github.com/tommy351/kubernetes-models-ts/pull/66) [`51cbc2b`](https://github.com/tommy351/kubernetes-models-ts/commit/51cbc2ba30ac417ee788f6a536a544191aadf69a) Thanks [@tommy351](https://github.com/tommy351)! - Use the new `@kubernetes-models/apimachinery` package.

### Minor Changes

- [#68](https://github.com/tommy351/kubernetes-models-ts/pull/68) [`8b610d0`](https://github.com/tommy351/kubernetes-models-ts/commit/8b610d0130aebf48f9fb08bc9f6790f77281b4a9) Thanks [@tommy351](https://github.com/tommy351)! - All models with `apiVersion` and `kind` properties now come with a new static method `is`, which returns `true` when the input value contains the same `apiVersion` and `kind` with the model.

  This function implements TypeScript type guard, which is very useful for narrowing down types.

  Please noted that this function only checks `apiVersion` and `kind`, other properties may still be invalid.

  Below is an example of the type guard function.

  ```ts
  import { Pod } from "kubernetes-models/v1/Pod";

  if (Pod.is(value)) {
    // value is a Pod.
  }
  ```

### Patch Changes

- Updated dependencies [[`2b18c6b`](https://github.com/tommy351/kubernetes-models-ts/commit/2b18c6bcbfe1a414beabda00a6f1332449b2e748), [`04197d2`](https://github.com/tommy351/kubernetes-models-ts/commit/04197d23d5bc951b24a7e225f8d3070511861811), [`8b610d0`](https://github.com/tommy351/kubernetes-models-ts/commit/8b610d0130aebf48f9fb08bc9f6790f77281b4a9), [`e904810`](https://github.com/tommy351/kubernetes-models-ts/commit/e9048102c03569c19fc648ebff42b48e950dbc5c)]:
  - @kubernetes-models/base@3.0.0
  - @kubernetes-models/apimachinery@0.1.0

## 2.0.2

### Patch Changes

- Updated dependencies [[`0ddc606`](https://github.com/tommy351/kubernetes-models-ts/commit/0ddc606c531e1dbc06b2ddf102b9eeabd8bacea7)]:
  - kubernetes-models@2.0.2

## 2.0.1

### Patch Changes

- [`7c9d122`](https://github.com/tommy351/kubernetes-models-ts/commit/7c9d122689a55b644eb87b1661eb63c412302440) Thanks [@tommy351](https://github.com/tommy351)! - Rename extension of CommonJS files from `.cjs` to `.js`. (Revert [a9a3c18](https://github.com/tommy351/kubernetes-models-ts/commit/a9a3c189111b1f4c6975f1c53cde69e724c6f35b))

- Updated dependencies [[`7c9d122`](https://github.com/tommy351/kubernetes-models-ts/commit/7c9d122689a55b644eb87b1661eb63c412302440)]:
  - @kubernetes-models/base@2.0.1
  - kubernetes-models@2.0.1
  - @kubernetes-models/validate@2.0.1

## 2.0.0

### Major Changes

- [`f77a5c1`](https://github.com/tommy351/kubernetes-models-ts/commit/f77a5c154b093aaaccdb74ce309076f9dedf3cc9) Thanks [@tommy351](https://github.com/tommy351)! - Drop support of Node.js 10.

### Minor Changes

- [`930cc42`](https://github.com/tommy351/kubernetes-models-ts/commit/930cc4283562264d460d892205236df9ddd5b49e) Thanks [@tommy351](https://github.com/tommy351)! - Update to cert-manager v1.4.3.

### Patch Changes

- [`a9a3c18`](https://github.com/tommy351/kubernetes-models-ts/commit/a9a3c189111b1f4c6975f1c53cde69e724c6f35b) Thanks [@tommy351](https://github.com/tommy351)! - Rename extension of CommonJS files from `.js` to `.cjs`.

- Updated dependencies [[`7c1c04d`](https://github.com/tommy351/kubernetes-models-ts/commit/7c1c04dc0472a05d29bfd02a54855beb2bcb17db), [`0af92ab`](https://github.com/tommy351/kubernetes-models-ts/commit/0af92ab6320db857280c766f2a11bcefff1e0043), [`a9a3c18`](https://github.com/tommy351/kubernetes-models-ts/commit/a9a3c189111b1f4c6975f1c53cde69e724c6f35b), [`f77a5c1`](https://github.com/tommy351/kubernetes-models-ts/commit/f77a5c154b093aaaccdb74ce309076f9dedf3cc9)]:
  - @kubernetes-models/validate@2.0.0
  - kubernetes-models@2.0.0
  - @kubernetes-models/base@2.0.0

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.5.8](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.7...@kubernetes-models/cert-manager@1.5.8) (2021-05-30)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.5.7](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.6...@kubernetes-models/cert-manager@1.5.7) (2021-05-30)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.5.6](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.5...@kubernetes-models/cert-manager@1.5.6) (2021-05-20)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.5.5](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.4...@kubernetes-models/cert-manager@1.5.5) (2021-05-20)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.5.4](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.3...@kubernetes-models/cert-manager@1.5.4) (2021-04-14)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.5.3](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.2...@kubernetes-models/cert-manager@1.5.3) (2021-04-14)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.5.2](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.1...@kubernetes-models/cert-manager@1.5.2) (2021-03-03)

### Bug Fixes

- Fix Node.js 10 support ([3cffdf0](https://github.com/tommy351/kubernetes-models-ts/commit/3cffdf0d0a0efc24fcc959d20c8bca657385488f))

## [1.5.1](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.5.0...@kubernetes-models/cert-manager@1.5.1) (2021-03-03)

**Note:** Version bump only for package @kubernetes-models/cert-manager

# [1.5.0](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.4.2...@kubernetes-models/cert-manager@1.5.0) (2021-03-03)

### Features

- Rename extension of ESM files as ".mjs" ([025ac24](https://github.com/tommy351/kubernetes-models-ts/commit/025ac24948a07f2d48cc3fe4d3b6329749bc5c3a))

## [1.4.2](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.4.1...@kubernetes-models/cert-manager@1.4.2) (2021-02-28)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.4.1](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.4.0...@kubernetes-models/cert-manager@1.4.1) (2021-02-28)

**Note:** Version bump only for package @kubernetes-models/cert-manager

# [1.4.0](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.3.1...@kubernetes-models/cert-manager@1.4.0) (2021-02-27)

### Features

- **export-map:** Add more options to generate command ([8558dae](https://github.com/tommy351/kubernetes-models-ts/commit/8558daedd09894c2098fa16dfd103858aeb40d5a))

## [1.3.1](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.3.0...@kubernetes-models/cert-manager@1.3.1) (2021-02-27)

**Note:** Version bump only for package @kubernetes-models/cert-manager

# [1.3.0](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.2.0...@kubernetes-models/cert-manager@1.3.0) (2021-02-27)

### Features

- **crd-generate:** Generate aliases ([e16e6fe](https://github.com/tommy351/kubernetes-models-ts/commit/e16e6fe8736e95cfc48dcfe4ab2f244ac33bb380))
- **export-map:** Generate export map ([067b4e3](https://github.com/tommy351/kubernetes-models-ts/commit/067b4e303c0f662e113fc2ee65e8edf36a86c958))

# [1.2.0](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.1.0...@kubernetes-models/cert-manager@1.2.0) (2021-02-22)

### Features

- **cert-manager:** Update to cert-manager v1.2.0 ([a200971](https://github.com/tommy351/kubernetes-models-ts/commit/a200971e3f51d3faa072c98456734aec797cee81))

# [1.1.0](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.0.3...@kubernetes-models/cert-manager@1.1.0) (2021-02-07)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.0.3](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.0.2...@kubernetes-models/cert-manager@1.0.3) (2021-01-08)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.0.2](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.0.1...@kubernetes-models/cert-manager@1.0.2) (2020-12-15)

**Note:** Version bump only for package @kubernetes-models/cert-manager

## [1.0.1](https://github.com/tommy351/kubernetes-models-ts/compare/@kubernetes-models/cert-manager@1.0.1...@kubernetes-models/cert-manager@1.0.1) (2020-11-17)

## 1.0.1 (2020-10-16)

# 1.0.0 (2020-10-13)

### chore

- **deps:** Upgrade deps ([618d20b](https://github.com/tommy351/kubernetes-models-ts/commit/618d20b202ed91ee43814aa69e08a84f21d8ae1b))

### Features

- **cert-manager:** Upgrade to 1.0.3 ([b49e752](https://github.com/tommy351/kubernetes-models-ts/commit/b49e752bddc7c2badabd7053f218b0383aefb6ad))

### BREAKING CHANGES

- **deps:** Drop support for Node.js 8

## 0.2.2 (2020-07-21)

## 0.2.1 (2020-05-27)

# 0.2.0 (2020-05-03)

### Bug Fixes

- **cert-manager:** Fix tests ([e3c4682](https://github.com/tommy351/kubernetes-models-ts/commit/e3c4682aba0952ac6fab0cb604b75cf76f7986b3))

### Features

- **cert-manager:** Build legacy CRDs ([f697b6c](https://github.com/tommy351/kubernetes-models-ts/commit/f697b6ce395a7bc52738c8ee5d5fa2e413de777b))
- **cert-manager:** Update to v0.14.3 ([daced3e](https://github.com/tommy351/kubernetes-models-ts/commit/daced3ef1b0b16548c007cc1316774fce61a560e))

## 0.1.1 (2019-10-14)

# 0.1.0 (2019-09-01)

### Features

- Generate CRD ([bbd4930](https://github.com/tommy351/kubernetes-models-ts/commit/bbd4930d54650175261a62a5317dc9e6909dc147))
- Set metadata in CRD ([6ee2946](https://github.com/tommy351/kubernetes-models-ts/commit/6ee29461188a7a76f3e68da79d6beed6c033d917))