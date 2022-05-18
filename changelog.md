# Changelog

This is a fork of <https://steamcommunity.com/sharedfiles/filedetails/?id=2790047923> with changes to max range. Original author explicitly allows this as per the following quote:

Racher  [author] 14 May @ 3:56pm 
@Junrall I prepped the code for block size dependant configable range limit
however I don't want to write and maintain an editable config system at this time.

You can modify the mod and use your own version of it with your range limits:
(copy mod folder from Steam/steamapps/workshop/content to Roaming/SpaceEngineers/Mods
and modify Data/Scripts/OreDetectorReforged/Config.cs)


## [2.0.4] - 2022-05-16
### Fixed
- Skip invalid material on (Planet 26)

## [2.0.3] - 2022-05-15
### Fixed
- Ore index overflow with AwwScrap

## [2.0.2] - 2022-05-14
### Fixed
- Union settings when using multiple ore detectors
- Remove markers when none is active
- Increase whitelist size to 128bit
- Config refactor

## [2.0.1] - 2022-05-10
### Fixed
- Fix multiplayer disconnect ModStorage KeyNotFound

## [2.0.0] - 2022-05-08
### Added
- Use planet generation _mat.png
- Nearest neighbor search, infinite range
- OreDetector block terminal: range, period, whitelist, count, color
- ProgrammableBlock API: "ReforgedDetectN"
### Removed
- Persistent GPS signals (config, colors)
- Fancy voxel-walk (how the next close voxel was selected when the current was mined)
- Voxelhand support
- Meteorite support
- HandDrill support
- Client side PB calculation

## [1.0.1] - 2022-04-06
### Fixed
- Fixed a terminal property server/client issue

## [1.0.0] - 2022-04-05
### Added
- Initial version