# Changelog

All notable changes to the "QuoteWithMarker" package will be documented in this file.

## [1.0.4]

### Fixed

- Command works again on Sublime Text’s default Python 3.3 plugin host: marker dates use `datetime.now().date()` instead of `astimezone()` on a naive datetime ([#1](https://github.com/dennykorsukewitz/Sublime-QuoteWithMarker/issues/1)).

## [1.0.3]

### Fixed

- Empty caret no longer splits text (`continue` instead of invalid `next`); quotes the full line when nothing is selected ([#1](https://github.com/dennykorsukewitz/Sublime-QuoteWithMarker/issues/1)).

### Changed

- Marker date placeholders (`${year}`, `${month}`, `${day}`) use the local timezone (regression on Python 3.3 fixed in 1.0.4).

## [1.0.2]

### Changed

- Updated README.md and settings.
- Updated package structure [generator-sublime-package](https://github.com/dennykorsukewitz/generator-sublime-package).

## [1.0.1]

### Added

- Keymaps.

### Changed

- Updated Main menu and README.md.

## [1.0.0]

### Added

- Initial release of QuoteWithMarker package.
- Automatic quoting with custom markers via keyboard shortcut.
- Placeholders for the `quote_code_marker` setting: `${year}`, `${month}`, `${day}`.
