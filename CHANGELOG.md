# Changelog for personnummer.js

## 1.0.1

Added some additional keywords to package.json and cleaned `README.md`

## 1.1.0

-   Added type to personnummer.validate(). It can either be `personnummer` or `samordningsnummer`.
-   Removed optimised `validate` and `normalise` functions since benchmarking showed little to no difference.
-   Added `parseCIN`, `normaliseCIN`, and `validateCIN`.
-   Updated `README` to account for updates.

## 2.0.0

Rewrite to TypeScript. Change of license to MIT.

A lot of API breaking changes. Constants such as `gender`, `errors`, and `personal number types` are now caps, ex. `male` => `MALE`.
