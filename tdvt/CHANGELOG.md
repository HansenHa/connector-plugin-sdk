# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

## [2.1.3] - 2019-12-30
- Add tests specific to Snowflake.

## [2.1.2] - 2019-12-05
- Fix a bug that broke the `run-file` command.

## [2.1.1] - 2019-12-04
### Added
- Include all relevant log files in the zip archive.
- Compress the log file zip archive. This relies on the zlib module which seems to usually be installed by default.
- More logging about test exclusions.
- Update handling of args.run_file to use Path
