# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format laid out [here](https://github.com/sensu-plugins/community/blob/master/HOW_WE_CHANGELOG.md)

## [Unreleased]

## [2.0.0] - 2018-04-28
### Breaking Changes
- bumped dependency of `sensu-plugin` to 2.x you can read about it  [here](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#v145---2017-03-07) (@majormoses)

## [1.0.0] - 2018-01-31
### Security
- updated rubocop dependency to `~> 0.51.0` per: https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-8418. (@majormoses)

### Breaking Changes
- removed < ruby 2.1 support which was pulled as part of security updates (@majormoses)

### Changed
- appeased the cops (@majormoses)

### Added
- Add testing for Ruby 2.4.1

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-bigpanda/compare/2.0.0...HEAD
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-bigpanda/compare/1.0.0...2.0.0
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-bigpanda/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/sensu-plugins/sensu-plugins-bigpanda/compare/5e3b6c5bb931d7ced3fcad579589ab1f5c88c2c9...0.1.0
