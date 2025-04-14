# Changelog

All notable changes to this project will be documented in this file.


## [2025.04.14]

### Changed

- Split the **Win**dows and **mac**OS variants of the firmware.
    - The only difference between the two is the encoder **detent** sensitivity.  The OS' seem to treat these differently.  A latter update will re-merge these with OS detection functionality.

## [2025.03.12]

### Added

- Reinstated the corrected per-key-RGB animation.

### Changed

- Default per-key animation colors are now a rainbow.


## [2025.02.17]

### Removed

- ***Temporary*** removal of the per-key-RGB animation until VIA supports the new RGB-Matrix keycodes.


## [2025.02.15]

### Changed

- Added a workaround for the VIA App not supporting RGB matrix keycodes issue, now maps legacy keys to new keys.


## [2025.02.14]

### Changed

- Fixed an issue when using the per-key-RGB animation color settings in the VIA App, the keymap gets overwritten.  Only affected users using the per-key-RGB animation.


## [2024.05.13]

### Changed

- Changed encoder resolution from default of 4 to 2


## [2024.02.01]

### Added

- Added BNK9 to the QMK upstream repo


---

[2025.04.14]: https://github.com/binepad-global/qmk_userspace_binepad/commit/3a5c9e69da04aea31b8e2ca6cc6355859a5b8627
[2025.03.12]: https://github.com/binepad-global/qmk_userspace_binepad/commit/11a459c0ba7c44574afdfaea09284f56537595b8
[2025.02.17]: https://github.com/binepad-global/qmk_userspace_binepad/commit/66c6b2e84956dd063cf064dee02bebdd8a709abf
[2025.02.15]: https://github.com/binepad-global/qmk_userspace_binepad/commit/5023432d924c4d9dc1a60472b500af16ae7a375c
[2025.02.14]: https://github.com/binepad-global/qmk_userspace_binepad/commit/22463f4598f7315c1df5dd0abf1cc0f2079cd45a
[2024.05.13]: https://github.com/qmk/qmk_firmware/pull/23707
[2024.02.01]: https://github.com/qmk/qmk_firmware/pull/22831
