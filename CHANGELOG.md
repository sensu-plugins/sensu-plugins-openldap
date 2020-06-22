# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]

## [2.0.0] - 2020-06-22
### Breaking Changes
- Update minimum required ruby version to 2.3. Drop unsupported ruby versions.
- Bump `sensu-plugin` dependency to `~> 4.0`

### Added
- Bonsai asset support
- Ruby 2.4.1 testing

### Changed
- Updated bundler dependency to '~> 2.1'
- Updated rubocop dependency to '~> 0.85.1'
- Updated net-ldap dependency to '0.16.2'
- Remediated rubocop issues
- Updated rake dependency to '~> 13.0'

### [1.0.1]
 - Fix #3 : metrics-ldap.rb Error Cannot connect to (@roumano)

## [1.0.0] - 2017-01-17
### Added
- check-syncrepl.rb: Add `--ca-certificate`, `--certificate` and `--encryption` options (@moriyoshi)
- Ruby 2.3.0 support (@eheydrick)

### Removed
- Ruby < 2.1 support (@eheydrick)

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-03
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-05-21
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-openldap/compare/2.0.0...HEAD
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-openldap/compare/1.0.1...2.0.0
[1.0.1]: https://github.com/sensu-plugins/sensu-plugins-openldap/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-openldap/compare/0.0.3...1.0.0
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-openldap/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-openldap/compare/0.0.1...0.0.2
