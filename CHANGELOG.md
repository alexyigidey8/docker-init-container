# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
[markdownlint](https://dlaa.me/markdownlint/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.6.0] - 2020-11-02

### Added in 1.6.0

- Support for `SENZING_ENGINE_CONFIGURATION_JSON`

## [1.5.11] - 2020-10-30

### Fixed in 1.5.11

- Fixed references to `libmysqlclient.so.21.1.20`

## [1.5.10] - 2020-10-23

### Changed in 1.5.10

- Accommodate changes in Senzing 2.3.0.  Optional processing of `G2Project.ini`

## [1.5.9] - 2020-09-28

### Changed in 1.5.9

- Replacing SENZING_INIT_CONTAINER_SLEEP with SENZING_DELAY_IN_SECONDS to be consistent with other Senzing images
- Automatically downloading and installing Senzing postgresql governor if no governor exists.

## [1.5.8] - 2020-09-15

### Changed in 1.5.8

- Changed permissions on db2dsdriver.cfg to 755 (from 750)

## [1.5.7] - 2020-09-02

### Changed in 1.5.7

- Fixed issue with MS SQL port specification

## [1.5.6] - 2020-07-23

### Changed in 1.5.6

- Update to senzing/senzing-base:1.5.2

## [1.5.5] - 2020-07-07

### Changed in 1.5.5

- Update to senzing/senzing-base:1.5.1
- Add logging information.

## [1.5.4] - 2020-05-11

### Changed in 1.5.4

- Changed the detection of existing paths.

## [1.5.3] - 2020-04-27

### Changed in 1.5.3

- Add support for PostgreSQL ODBC.

## [1.5.2] - 2020-04-22

### Changed in 1.5.2

- Adjust for changes in Senzing SDK.
  - Return codes have been removed in favor of Exceptions.

## [1.5.1] - 2020-04-22

### Changed in 1.5.1

- Improved documentation
- Support for `SENZING_ENGINE_CONFIGURATION_JSON`
- Improved logging

## [1.5.0] - 2020-01-29

### Changed in 1.5.0

- Update to senzing/senzing-base:1.4.0

## [1.4.2] - 2020-01-27

### Added in 1.4.2

- Copy `G2C.db` to `G2C_LIBFEAT.db` and `G2C_RES.db`

## [1.4.1] - 2019-11-27

### Added in 1.4.1

- init-container.py subcommands:  initialize-files, initialize-database
- No change to docker image behavior.

## [1.4.0] - 2019-11-13

### Added in 1.4.0

- Add support for MSSQL database.
- Update to senzing/senzing-base:1.3.0

## [1.3.3] - 2019-11-06

### Fixed in 1.3.3

- Support non-root commandline invocation.

## [1.3.2] - 2019-11-02

### Fixed in 1.3.2

- Cast string as int in `os.chown()` call.

## [1.3.1] - 2019-10-22

### Changed in 1.3.1

- Incorporate changes for Senzing 1.12.0

## [1.3.0] - 2019-08-31

### Changed in 1.3.0

- Is now a `non-root`, immutable container.

## [1.2.1] - 2019-08-19

### Changed in 1.2.1

- Adapted to new Senzing API server initialization

## [1.2.0] - 2019-08-05

### Changed in 1.2.0

- RPM based installation

## [1.1.0] - 2019-07-23

### Added in 1.1.0

- Database support
  - PostgreSQL
  - MySQL
  - Db2
  - SQLite
