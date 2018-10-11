# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

### Changed
- Updated serialized_precision PHP setting, to help with JSON encoded/decoded float values. 

## [v1.8.0] - 2018-08-11
### Changed
- Bumped up Alpine version to 3.7
- Bumped up PHP version to 7.1.20
- Bumped up Nginx version to 1.12.2-r3

## [v1.7.5] - 2018-06-16
### Changed
- Expose environment to the php-fpm process as a default

### Fixed
- Double wrapping bash condition

## [v1.7.4] - 2018-05-30
### Changed
- Bumped up PHP version to 7.1.18

### Fixed
- Non-empty if condition in entrypoint

## [v1.7.3] - 2018-04-07
### Added
- PHP intl extension

### Changed
- Bumped up PHP version to 7.1.16

### Fixed
- Don't run supervisord in subshell to receive kill signals

## [v1.7.2] - 2018-02-27
### Changed
- Bumped up PHP version to 7.1.14

## [v1.7.1] - 2017-12-31
### Changed
- Bumped up PHP version to 7.1.12

## [v1.7.0] - 2017-11-19
### Changed
- Bumped up PHP version to 7.1.11

## [v1.6.0] - 2017-09-17
### Changed
- Bumped up PHP version to 7.1.9

## [v1.5.1] - 2017-08-02
### Added
- Nginx now listens on port 80

## [v1.5.0] - 2017-06-20
### Changed
- Bumped up Alpine version to 3.5
- Replaced OpenSSL with LibreSSL
- Bumped up PHP version to 7.1.6
- Bumped up Nginx version to 1.10.3

## [v1.4.1] - 2017-06-19
### Changed
- Including MySQLi support

## [v1.4.0] - 2017-03-25
### Changed
- Bumped up PHP version to 7.1.3

## [v1.3.2] - 2016-12-27
### Changed
- Bumped up PHP version to 7.0.14

## [v1.3.1] - 2016-12-04
### Changed
- Use ```#``` as the sed delimiter to avoid conflict with folder path environment variables
- Exclude the ```vendor``` folder when templating variables

## [v1.3.0] - 2016-11-26
### Changed
- Bumped up PHP version to 7.0.13
- Php-fpm now logs to stdout / stderr

### Fixed
- Logging to stdout and stderr for nginx and php-fpm

## [v1.2.0] - 2016-10-08
### Changed
- Bump PHP version to 7.0.11

### Added
- Support for inclusion of custom supervisord config files

## [v1.1.0] - 2016-07-20
### Changed
- Bump PHP version to 7.0.8

## [v1.0.0] - 2016-06-12
### Added
- Initial tag

[Unreleased]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.8.0...master
[v1.8.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.7.5...v1.8.0
[v1.7.5]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.7.4...v1.7.5
[v1.7.4]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.7.3...v1.7.4
[v1.7.3]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.7.2...v1.7.3
[v1.7.2]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.7.1...v1.7.2
[v1.7.1]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.7.0...v1.7.1
[v1.7.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.6.0...v1.7.0
[v1.6.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.5.1...v1.6.0
[v1.5.1]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.5.0...v1.5.1
[v1.5.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.4.1...v1.5.0
[v1.4.1]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.4.0...v1.4.1
[v1.4.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.3.2...v1.4.0
[v1.3.2]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.3.1...v1.3.2
[v1.3.1]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.3.0...v1.3.1
[v1.3.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.2.0...v1.3.0
[v1.2.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.1.0...v1.2.0
[v1.1.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/compare/v1.0.0...v1.1.0
[v1.0.0]: https://gitlab.com/boxedcode/alpine-nginx-php-fpm/tags/v1.0.0