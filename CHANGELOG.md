# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.1] - 2019-02-27
## Fixed
- Bug that was caused by using the `fire` method on the Event Dispatcher of the menu builder

## [2.0.0] - 2019-02-27
## Changed
- Update to newest stable Laravel release - 5.8

## [1.4.0] - 2019-02-25
## Changed
- Updated icon naming in config to adhere to newest FontAwesome naming

## [1.3.1] - 2019-02-22
## Changed
- Updated CoreUI to latest version

## [1.3.0] - 2019-02-22
## Added
- Menu filter to easily integrate Laravel's Gate functionality via the `coreui.php` config file
## Fixed
- Bug that caused `make:coreui` command to push views to the wrong folder, resulting in an exception

## [1.2.3] - 2019-02-20
## Nothing
This tag actually references tag 1.2.2

## [1.2.2] - 2019-02-20
## Changed
- Updated README with cool badges
- Updated composer.json with correct package description

## [1.2.1] - 2019-02-20
## Changed
- Updated FontAwesome and Bootstrap to latest version

## [1.2.0] - 2019-02-11
## Added
- Localization and i18n for Dutch and English

## [1.1.1] - 2019-02-06
## Fixed
- Bug that caused the views to be exported to the wrong folders

## [1.1.0] - 2019-02-04
## Changed
- Updated FontAwesome and Popper.js to latest versions

## [1.0.5] - 2019-01-29
## Fixed
- A bug that caused to logo to overflow in the the main content upon minimizing the navbar

## Added
- An option for a mini logo that is rendered when the navbar is minimized

## [1.0.4] - 2019-01-28
## Fixed
- A bug where the logout button would always be rendered, leading to a hard exception if the user didn't create an authentication system

## [1.0.3] - 2019-01-14
### Fixed
- Updated a typo in README that could cause the templates to not be inherited

## [1.0.2] - 2019-01-14
### Added
- This changelog

## [1.0.1] - 2019-01-14
### Fixed
- Unclosed `<p>` tag in the master template
- Renamed the `content` section of the README to `body` so it's actually correct

## 1.0.0 - 2019-01-14
### Added
- First version of package
