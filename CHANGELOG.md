# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0-prerelease.6] - 2025-05-11

### Fixed
- Fixed logic for specifc versions that don't exist.

## [1.2.0-prerelease.5] - 2025-04-28

### Changed
- Updated installer to create launcher script to direct to active version.
- Updated installer to backup and update .bashrc.

### Fixed
- Fixed version-release.yml timing issue when creating .tar.gz.

## [1.2.0-prerelease.1] - 2025-04-27

### Added
- Added installer.

## [1.1.0] - 2025-04-27

### Added
- Added theme prompt preview to --list.

## [1.1.0-prerelease.1] - 2025-04-22

### Added
- Added support for glob filters for --list, allowing *, ? wildcards.

## [1.0.0] - 2025-04-20

### Added
- Added support for git branch ahead/behind numbers.

### Changed
- Theme file extension changed to .theme.
- *_STATUS variables renamed to COMMAND_STATUS_*.

### Fixed
- Fallback logic when activating a theme.
- Resolved issues with theme validation when invalid themes are present.

## [0.1.0-alpha.N] - 2025-04-19

### Added
- Initial pre-releases.
- Basic theme support and prompt customization.
- Documentation for usage and options: help, list themes, activate theme, stop.
- Automated creation of GitHub release when the version changes in VERSION.
