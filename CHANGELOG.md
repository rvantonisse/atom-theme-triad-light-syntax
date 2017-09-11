# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

---

## [0.2.1] - 2017-09-11

### Added

- Added styling for dashed wrap-guide

### Changed

- Editor styles
  - Changed max-height for line-number to line-number within gutter.line-numbers (Caused multiline selection in git-line to look like one)

- Javascript syntax
  - Changed color for keyword.control.flow to @lime



---

## [0.2.0] - 2017-09-10

### Added

- CHANGELOG
- styles
  - base
    - Added styles for .invalid, .illegal, .support, .brace/bracket syntax
  - editor
    - Added (better) git support / readabillity in gutter by coloring line numbers as well

### Changed

- Gutter / line numbers are brighter, removed opacity.
- Selection color
- Fold marker shows a textual hint in code, added double bottom border on folded line-numbers.
- Gutter(-container) has a right border.

---

## [0.1.0] - 2017-03-27

Initial release
