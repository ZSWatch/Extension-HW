# Changelog

## [Unreleased]

### Added

- Test points for 1V8_PA, 1V8_HR, and VSYS (#11).
- Silkscreen arrow to indicate mounting orientation (#11).
- Add `fill_zones: true` to preflight (#5)
- Add revision string to copper (#7)

### Changed

- Change VLED capacitor to 10 V type (#3)

### Fixed

- Several production issues (#8, #9, #10)
- Restore test-point references and preserve their silkscreen labels as separate text (#6).
- Refill copper zones after combining the capacitor and test-point layout changes (#6).
- Select the release variant before choosing KiBot checks and tolerate missing temporary files during CI cleanup (#6).
- Make Pages deployment opt-in through `DEPLOY_PAGES=true` and grant its required permissions (#6).

## [1.0.0] - 2026-02-20

**Added:**

Initial release

[Unreleased]: https://github.com/ZSWatch/Extension-HW/compare/1.0.0...HEAD

[1.0.0]: https://github.com/ZSWatch/Extension-HW/compare/19edb2ccb776ce736e881af2e758c1c79f8923ef...1.0.0
