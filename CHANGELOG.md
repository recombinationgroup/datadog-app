# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.4.0] - 2022-08-29

### Changed

- Upgrade upstream chart from version 2.35.6 to 2.37.6

## [2.3.1] - 2022-06-29

### Fixed

- Configure host CA path by default.

## [2.3.0] - 2022-06-28

### Changed

- Upgrade upstream chart from version 2.30.19 to 2.35.6
- Set tlsVerify = true by default

## [2.2.1] - 2022-05-13

### Added

- Push helm chart to OCI registry.

## [2.2.0] - 2022-03-29

### Fixed

- Remove SE Linux support to work on latest Flatcar versions (disabled SE linux by default).

## [2.1.0] - 2021-08-26

### Updated

- Upstream sync 2.1.0 which follows upstream version [2.20.1](https://github.com/giantswarm/datadog-app/blob/master/helm/datadog/CHANGELOG.md)

## [2.0.0] - 2021-04-16

### Added

- Initial release 2.0.0 which follows upstream version 2.10.13

[Unreleased]: https://github.com/giantswarm/datadog-app/compare/v2.4.0...HEAD
[2.4.0]: https://github.com/giantswarm/datadog-app/compare/v2.3.1...v2.4.0
[2.3.1]: https://github.com/giantswarm/datadog-app/compare/v2.3.0...v2.3.1
[2.3.0]: https://github.com/giantswarm/datadog-app/compare/v2.2.1...v2.3.0
[2.2.1]: https://github.com/giantswarm/datadog-app/compare/v2.2.0...v2.2.1
[2.2.0]: https://github.com/giantswarm/datadog-app/compare/v2.1.0...v2.2.0
[2.1.0]: https://github.com/giantswarm/datadog-app/compare/v2.0.0...v2.1.0
[2.0.0]: https://github.com/giantswarm/datadog-app/releases/tag/v2.0.0
