## 0.4.0 - [13.04.2022]

### Added

- Add `purple_lints` as a package linter.
- Add `StreamBlocObserverConfig`, `StreamBlocObserverLocation` and static `StreamBlocObserver.config` variable, thus adding the static variable option for global injection of the `StreamBlocObserver`.
- Add Setter for the `StreamBlocObserver.current` variable.
- Add `const` constructor to the `StreamBlocObserver`.

### Changed

- Bump `bloc` dependency.

### Fixed

- Fix annotations for implemented and inherited methods.
- Fix documentation member references.
- Import `StreamBlocMapper`.

## 0.3.1 - [13.02.2022]

- Fixed `StreamBlocObserver`'s `StreamBlocObserver.current` getter.
- Dropped minimum package version constraint to `2.12.0`.

## 0.3.0 - [06.02.2022]

- Added `transformSourceEvents`.

## 0.2.1 - [04.02.2022]

- Fixed imports.

## 0.2.0 - [04.02.2022]

- Events stream is made broadcast.
- Package exports include the `bloc` package.
- Fixed meta dependency, bumping it to the latest version.
- Added missing `on...` arguments to `BlocLifecycleMixin`'s methods.
- `StreamBlocObserver`'s methods expect interfaces.
- Added missing documentation. The package is now 100% documented.

## 0.1.0 - [06.01.2022]

- Initial version.
