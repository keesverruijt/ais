# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2020-04-26
### Added
- Support for type 5 messages
- Support for fragmented sentences

### Changed
- Top level interface now involves using an `AisParser` object
- Message parsing happens at the same time as NMEA sentence parsing, if enabled
- Updated Nom dependency to v5
- Replaced error-chain with thiserror

## [0.1.1] - 2020-04-18
### Added
- Link to documentation at https://docs.rs/ais

## [0.1.0] - 2020-04-18
### Added
- Initial release