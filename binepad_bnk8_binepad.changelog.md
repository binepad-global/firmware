# Changelog

All notable changes to this project will be documented in this file.


## [2025.04.15]

### Changed
- Re-built firmware with a custom encoder implementation.
    - **Detent** sensitivity is set to 2 for Windows and Linux, and 4 for Apple platforms.
    - Firmware attempts to auto-detect OS, but if fails will revert to Windows setting of 2.
    - If unit is connected to a USB-hub it may fail detection.


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

- Fixed an issue with the 4th and 6th key color being swapped when editing in the VIA App, the per-key-RGB animation in VIA.
- Fixed an issue when using the per-key-RGB animation color settings the keymap gets overwritten.  Only affected users using the per-key-RGB animation.


## [2025.12.05]

### Added

- Added BNK8 to QMK upstream repo


---

[2025.04.15]: https://github.com/binepad-global/qmk_userspace_binepad/commit/fb1f49ece3b036adee2f9a0186151c65b251cc6b
[2025.03.12]: https://github.com/binepad-global/qmk_userspace_binepad/commit/11a459c0ba7c44574afdfaea09284f56537595b8
[2025.02.17]: https://github.com/binepad-global/qmk_userspace_binepad/commit/66c6b2e84956dd063cf064dee02bebdd8a709abf
[2025.02.15]: https://github.com/binepad-global/qmk_userspace_binepad/commit/5023432d924c4d9dc1a60472b500af16ae7a375c
[2025.02.14]: https://github.com/binepad-global/qmk_userspace_binepad/commit/22463f4598f7315c1df5dd0abf1cc0f2079cd45a
[2025.12.05]: https://github.com/qmk/qmk_firmware/pull/24598
