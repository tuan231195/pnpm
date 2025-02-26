# @pnpm/modules-yaml

## 9.0.2

### Patch Changes

- Updated dependencies [724c5abd8]
  - @pnpm/types@7.2.0

## 9.0.1

### Patch Changes

- Updated dependencies [97c64bae4]
  - @pnpm/types@7.1.0

## 9.0.0

### Major Changes

- 97b986fbc: Node.js 10 support is dropped. At least Node.js 12.17 is required for the package to work.
- 78470a32d: New required option added to the modules meta object: `prunedAt`. `prunedAt` is the stringified UTC date when the virtual store was last cleared.

### Patch Changes

- Updated dependencies [97b986fbc]
  - @pnpm/types@7.0.0

## 8.0.6

### Patch Changes

- Updated dependencies [9ad8c27bf]
  - @pnpm/types@6.4.0

## 8.0.5

### Patch Changes

- 09492b7b4: Update write-file-atomic to v3.

## 8.0.4

### Patch Changes

- Updated dependencies [b5d694e7f]
  - @pnpm/types@6.3.1

## 8.0.3

### Patch Changes

- Updated dependencies [d54043ee4]
  - @pnpm/types@6.3.0

## 8.0.2

### Patch Changes

- a2ef8084f: Use the same versions of dependencies across the pnpm monorepo.

## 8.0.1

### Patch Changes

- Updated dependencies [db17f6f7b]
  - @pnpm/types@6.2.0

## 8.0.0

### Major Changes

- 71a8c8ce3: Breaking changes to the `node_modules/.modules.yaml` file:
  - `hoistedAliases` replaced with `hoistedDependencies`.
  - `shamefullyHoist` replaced with `publicHoistPattern`.

### Patch Changes

- Updated dependencies [71a8c8ce3]
  - @pnpm/types@6.1.0

## 7.0.0

### Major Changes

- 3f73eaf0c: Rename `store` to `storeDir` in `node_modules/.modules.yaml`.
- 802d145fc: Remove `independent-leaves` support.

### Patch Changes

- Updated dependencies [da091c711]
  - @pnpm/types@6.0.0

## 7.0.0-alpha.0

### Major Changes

- 3f73eaf0: Rename `store` to `storeDir` in `node_modules/.modules.yaml`.

### Patch Changes

- Updated dependencies [da091c71]
  - @pnpm/types@6.0.0-alpha.0

## 6.0.2

### Patch Changes

- 907c63a48: Dependencies updated.
