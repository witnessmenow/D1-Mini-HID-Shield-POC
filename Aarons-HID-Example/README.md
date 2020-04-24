# Aarons HID example

This is the code that Aaron went through in [this video](https://www.youtube.com/watch?v=cSYMe4xyGeo).
[![YoutubeVideo](https://img.youtube.com/vi/cSYMe4xyGeo/0.jpg)](https://www.youtube.com/watch?v=cSYMe4xyGeo)

This example has two LEDs and two touch inputs.

LED on P3.0 -- Blink every 40ms
LED on P3.1 -- Bound to NUM Lock of your keyboard (will light when numlock is on)

Touch input on TIN2 -- Enter bootloader mode
Touch input on TIN3 -- Type out a message

# To run this example

- Download Aaron's One Click Compiler project: https://github.com/atc1441/CH55xOneClickCompiler
- Copy the `SDCC\bin` folder into the `SDCC` folder of this project.
- If you haven't already, use [Zadig](https://zadig.akeo.ie/) to install the libusb-win32 driver while the CH552 is in bootloader mode
- Put the CH552 into bootloader mode and double click `compile.bat`
