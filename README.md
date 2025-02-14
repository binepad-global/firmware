# Firmware for the Binepad keyboards
**built on QMK, VIA or VIAL**

![](assets/img/binepad_logo.svg)

---

- Your product will ship with a working firmware.  Only use these if you're experiencing issues and only under the instruction of a Binepad support associate.
    - Please visit [Binepad.com](https://binepad.com) for contact details.
- There is no need to pull request to this repository. The content is generated and updated only when needed.
    - Not all products will be listed.
    - Firmware is periodically rebuilt from the latest QMK / VIA / VIAL source code and committed here, if not available elsewhere.

---

## Getting custom firmware on your keyboard

Firmware files are stored in this folder and will be the file with the `.bin` or `.uf2` file extension.  Each firmware will also have a changelog showing the release data in the files with the `.changelog.md` extension.

---

All firmware listed herein is build on one of 3 platforms, depending on the device:

| Platform | Website | Github repository | Configuration |
| --- | --- | --- | --- |
| QMK | [`qmk.fm`](https://qmk.fm/) | [`qmk/qmk_firmware`](https://github.com/qmk/qmk_firmware) | [`config.qmk.fm`](https://config.qmk.fm/#/binepad/bnr1/v1/LAYOUT_ortho_1x1)&nbsp;<sup>1</sup>
| VIA&nbsp;<sup>2</sup> | [`caniusevia.com`](https://www.caniusevia.com/) | [`the-via/qmk_userspace_via`](https://github.com/the-via/qmk_userspace_via) | [`usevia.app`](https://usevia.app)&nbsp;<sup>4</sup> |
| VIAL&nbsp;<sup>3</sup> | [`get.vial.today`](https://get.vial.today) | [`vial-kb/vial-qmk`](https://github.com/vial-kb/vial-qmk) | [`vial.rocks`](https://vial.rocks)&nbsp;<sup>4</sup> |

> 1. <small>QMK's configuration if for expert use only</small>
>    <br> :warning: <small>It only creates firmware binaries, and will break any dependencies with VIA or VIAL</small>
> 2. <small>VIA is a UI build around QMK and uses the QMK core code to compile custom firmware</small>
> 3. <small>VIAL is a fork of the original QMK and uses its own derivative code to compile custom firmware</small>
> 4. <small>These UI tools will require the Chrome browser, or browsers built on the Chromium platform</small>
>    <br> :warning: <small>Although both VIA and VIAL are derivatives of QMK they are not cross compatible</small>

## License and Source

- The licence for QMK (and its offspring) is [GNU GPL 2.0](./LICENSE.md)
- Source for these firmware is compiled from their respective repositories, and the Binepad Global QMK Custom Userspace located at [github.com/binepad-global/qmk_userspace_binepad](https://github.com/binepad-global/qmk_userspace_binepad)

## Facing issues?

If you encounter any issues or bugs while using the devices, please report them via our contacts listed on the [Binepad.com](https://binepad.com). This will help us to track down and resolve problems, and improve the experience for everyone.

---

Thank you :smile:
