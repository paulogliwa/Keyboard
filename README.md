# Keyboard
Vault for my mechanical keyboards ideas and resources.

## Resources for keyboard building
#### Links:
* Creating layout and look ([Keyboard Layout Editor](http://www.keyboard-layout-editor.com))
* Wiring and pinout matrix creator with firmware builder ([Keyboard Firmware Builder](https://kbfirmware.com))
* Official QMK configurator that has some useful features ([QMK Configurator](https://config.qmk.fm))
* QMK keycode reference([QMK Documentation](https://docs.qmk.fm/#/keycodes))
* Backplate generator (creates backplate model/blueprint) ([Plate & Case Builder](http://builder.swillkb.com/))

## Compact Keyboard
#### Idea:
Something that will fit on every desk, is portable (if I want to work somewhere else that day) and versatile.
####

## Software workflow with Arduino
* Map pinout, wirigin and keys in kbfirmware and build the .hex file
* Load the .hex file in QMK Toolbox and check "Auto flash" option
* Connect the keyboard to usb and press RESET key (if mapped) or short RST and GND (if reset is not mapped)
* software should flash to the Arduino board and the keyboard is ready to use

## Other stuff
* https://brianlee.blog/2018/11/23/guide-keyboard-construction-explained/
