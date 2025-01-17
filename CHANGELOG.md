# Change Log
All notable changed to this project will be documented in this file.

## [1.1.82] - 18.05.2022
### Added
### Changed
### Fixed
- Fixed string length check into SetStringAt [#28](https://github.com/fbarresi/Sharp7/issues/28)

## [1.1.81] - 18.05.2022
### Added
### Changed
### Fixed
- Removed obsolete SetBitAt  [#27](https://github.com/fbarresi/Sharp7/issues/27)

## [1.1.80] - 18.05.2022
### Added
### Changed
### Fixed
- Fixed casting in GetIntAt [#29](https://github.com/fbarresi/Sharp7/issues/29)

## [1.1.79] - 09.02.2021
### Added
- Constant for no errors `S7Consts.ResultOK`
### Changed
### Fixed

## [1.1.78] - 04.02.2021
### Added
- Property `PLCIpAddress`
- Overload of `ToString` for S7Client
- Property `Name` as constructor param in S7Client
### Changed
### Fixed


## [1.1.75] - 03.09.2020
### Added
### Changed
- CHANGELOG.md
- README.md
### Fixed
- [#18](https://github.com/fbarresi/Sharp7/issues/18)
	- New overloaded extension method signatures for SetBitAt
	- Removed not necessary casting to short for GetIntAt
	- Added overloads for S7 `Time_Of_Day` functions
	- Added more tests
	- made old methods obsolete

## [1.1.71] - 14.08.2020
### Added
- CHANGELOG.md
### Changed
- README.md
- Referenced changelog into nuget release notes
### Fixed

## [1.1.69] - 11.06.2020
### Added
### Changed
- README.md
### Fixed

## [1.1.68] - 11.06.2020
### Added
- Added enums and methods overloads for S7Wordlength and S7Area (#11)
### Changed
- README.md
- Changed properties to expression body solution wide
- Changed S7 calls to extension methods
- Usage of overloaded methods with enums instead of constants
### Fixed
- Check connection on socket close
- Null propagation on disconnect method
- Soved usage ob obsolete constants

## [1.1.63] - 06.05.2020
### Added
### Changed
### Fixed
- style and security enhancement

## [1.1.62] - 06.05.2020
### Added
### Changed
### Fixed
- Unused exception handling

## [1.1.61] - 06.05.2020
### Added
### Changed
### Fixed
- Usage of Timeouts from [philfontaine/Sharp7@fb01cc0](https://github.com/philfontaine/Sharp7@fb01cc0)

## [1.1.60] - 06.05.2020
### Added
### Changed
### Fixed
- connection check into overload of SendPacket (#8)

## [1.1.59] - 06.05.2020
### Added
- Added unit tests
### Changed
- Created extension methods from S7
### Fixed
- Fixed naming rules

## [1.0.50] - 17.11.2019
### Added
### Changed
- README.md
### Fixed

## [1.0.49] - 17.11.2019
### Added
### Changed
- README.md
### Fixed

## [1.0.48] - 17.11.2019
### Added
### Changed
- README.md
### Fixed

## [1.0.25] - 02.04.2019
### Added
- Added nuget package description
### Changed
### Fixed

## [1.0.22] - 17.01.2019
### Added
- Added debug symbols to Nuget
### Changed
### Fixed

## [1.0.18] - 21.11.2018
### Added
### Changed
- Migrate solution to project SDK (#2)
### Fixed

## [1.0.0] - 21.01.2018
### Added
- imported initial project from source forge
### Changed
### Fixed