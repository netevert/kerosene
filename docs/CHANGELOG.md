# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Changed
- Updated documentation to reflect version increment and year
- Updated README to include installation instructions

### Fixed
- Recompiled distribution installer and zipped folder to fix msvcr dll missing error
- Fixed formatting in CHANGELOG file and typos across all files

## [1.0.0] - 2017-02-05
### Added
- CHANGELOG file to keep track of software changes
- Flight data editing facility

### Changed
- Migrated data storage system from shelve object persistence to SQLite 
- Updated README and project documentation.

### Removed
- Flight data recording, processing and storage using shelve object persistence
