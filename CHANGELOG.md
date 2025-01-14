# Element Relations Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## 1.2.5 - 2022-02-04
### Fixed
- Better fix for [#6](https://github.com/internetztube/craft-element-relations/issues/6) Safely dropping foreign keys and index on `siteId` and `markup` columns.

## 1.2.4 - 2022-02-02
### Fixed
- Fixed [#6](https://github.com/internetztube/craft-element-relations/issues/6).

## 1.2.3 - 2022-01-07
### Added
- Added support for LinkIt.

## 1.2.2 - 2022-01-06
### Fixed
- Fix purging of custom fields on User Elements.

## 1.2.1 - 2022-01-06
### Added
- Added Support for Redactor.

### Updated
- Improved Cache Invalidation.

## 1.2.0 - 2022-01-04
### Updated
- Update caching logic.

### Fixed
- There is now always a hint when an element is used in another site.

## 1.1.3 - 2021-12-28
### Fixed
- Add csrf token to utilities form.

## 1.1.2 - 2021-12-28
### Added
- Added Utility Page for Cache Refresh

## 1.1.1 - 2021-12-28
### Fixed
- Database Migrations

## 1.1.0 - 2021-12-28
### Added
- Added caching system and new table to store data and speed up repeated fetches. Big thanks to [@gbowne](https://github.com/gbowne-quickbase) for the implementation! #3

## 1.0.6 - 2021-11-18
### Added
- Added support for Profile Photos.

### Fixed
- Fixed bug that occurred on prefixed SEOmatic fields.
- SEOmatic and Profile Photo check now only occur when element is an Asset. -> Performance

## 1.0.5 - 2021-11-13
### Fixed
- Fixed bug that occurred on Craft CMS installations with table prefixes. Thank you @gbowne-quickbase! #1

## 1.0.4 - 2021-10-25
### Added
- Added support for SEOmatic.

## 1.0.3 - 2021-10-25
### Fixed
- Removed translation methods in field edit view..

## 1.0.2 - 2021-10-25
### Added
- Show element relations of other sites, when there are none in the current site.
- Improved frontend performance by delaying the requests by 100ms.

## 1.0.1 - 2021-10-23
### Fixed
- Fixed composer.lock

## 1.0.0 - 2021-10-23
### Added
- Initial release
