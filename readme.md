# hkrkbd

![hkrkbd](imgur.com image replace me!)

*My hombrew version of the [crkbd](). It is a slim, 36 keyboard.*
*The case can be assambled without screws and can be easily handwired*

* Keyboard Maintainer: [Damian Moreno](https://github.com/D4Devil)
* Hardware Supported: *Designed and Tested with Pro Micro*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make hkrkbd:default

Flashing example for this keyboard:

    make hkrkbd:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
