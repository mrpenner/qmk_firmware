# atreoid_328

A keyboard based on the Atreus, powered by an Atmega328 microcontroller.

* Keyboard Maintainer: [Mark Penner](https://codeberg.org/mrp/)

A keyboard based on the [Atreus](http://atreus.technomancy.us) ([Atreus repo](https://gitlab.com/technomancy/atreus)), powered by an Atmega328 microcontroller. It uses the 44 key layout of the [Keyboardio Atreus](https://shop.keyboard.io/products/keyboardio-atreus), rather than the 42 key original.

Make example for this keyboard (after setting up your build environment):

    make atreoid_328:default

Flashing example for this keyboard:

    make atreoid_328:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the boot button (below the MCU) and plug in the keyboard
* **Physical reset button**: Briefly press the reset button (above the MCU)
