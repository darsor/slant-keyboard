# Slant Keyboard

![slant_photo](https://github.com/darsor/slant-keyboard/assets/15043521/6a184f74-8002-43c4-b63e-0521ffbc0788)

I liked the idea of the Corne or Sweep keyboards, but I didn't like the microcontroller hanging on the side. So I designed my own with a small 7.5 degree tent (Slant), making enough room for a nice!nano and a larger 350 mAh battery to go underneath the PCB.

The case is custom designed and printed. I used Onshape to CAD the entire design, which really helped everything work together on the first try. You can find the onshape model [here](https://cad.onshape.com/documents/52d8c97deb1f4fedd7779345/w/a823d43323299a2b5f12e80a/e/73bc7d91904b86f6c9de98d1).

PCB and key placement were aided by Ergogen, which simplified things quite a bit. Kicad was used for the layout and routing.

This repository contains:
* ergopad/: screenshots from ergopad to help fit the physical key placement to my hand
* kicad_project/: the PCB files
* parts/: a digikey parts list
* zmk-config/: the ZMK firmware files, including keymap
