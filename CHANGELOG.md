# Changelog

All notable changes are documented here.
Format follows keepachangelog.com, versions are semver-ish.

## [0.3.4] - 2026-06-03

### Fixed
- edge case when the input list is empty
- unicode names broke the output table

### Changed
- faster directory walking, fewer syscalls

## [0.2.0] - 2026-05-20

### Added
- real rate limiting: sliding windows on requests/min and tokens/min

## [0.1.0] - 2026-06-08

### Added
- real rate limiting: sliding windows on requests/min and tokens/min
