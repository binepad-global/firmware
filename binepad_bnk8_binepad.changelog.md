# Changelog

All notable changes to this project will be documented in this file.

## [2025.02.14]

### Changed

- Fixed an issue with the 4th and 6th key color being swapped when editing in the VIA App, the per-key-RGB animation in VIA.
- Fixed an issue when using the per-key-RGB animation color settings the keymap gets overwritten.  Only affected users using the per-key-RGB animation.

### Known Issues

- QMK RGB settings keys are not supported in VIA at the time of this release.  You will see hex keycodes instead.  This is an issue with the VIA App and has been reported [#302](https://github.com/the-via/app/issues/302).

    - **Workaround:** Use VIA's "Any" key and type in the correct hex codes:  

        | Code | Function |
        |---|---|
        | `0x7840` | QK_RGB_MATRIX_ON |
        | `0x7841` | QK_RGB_MATRIX_OFF |
        | `0x7842` | QK_RGB_MATRIX_TOGGLE |
        | `0x7843` | QK_RGB_MATRIX_MODE_NEXT |
        | `0x7844` | QK_RGB_MATRIX_MODE_PREVIOUS |
        | `0x7845` | QK_RGB_MATRIX_HUE_UP |
        | `0x7846` | QK_RGB_MATRIX_HUE_DOWN |
        | `0x7847` | QK_RGB_MATRIX_SATURATION_UP |
        | `0x7848` | QK_RGB_MATRIX_SATURATION_DOWN |
        | `0x7849` | QK_RGB_MATRIX_VALUE_UP |
        | `0x784A` | QK_RGB_MATRIX_VALUE_DOWN |
        | `0x784B` | QK_RGB_MATRIX_SPEED_UP |
        | `0x784C` | QK_RGB_MATRIX_SPEED_DOWN |

---

[2025.02.14]: https://github.com/binepad-global/qmk_userspace_binepad/commit/22463f4598f7315c1df5dd0abf1cc0f2079cd45a
