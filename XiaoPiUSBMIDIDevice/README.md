# Xiao Pi USB MIDI Device

This is a USB MIDI IN/OUT IO board for the Raspberry Pi, based on a Seeed Studio XIAO SAMD21.

- Design notes: https://diyelectromusic.wordpress.com/2023/04/16/xiao-pi-usb-midi-device-pcb/
- Build and test notes: https://diyelectromusic.wordpress.com/2023/04/16/xiao-pi-usb-midi-device-pcb-part-2/

Bill of Materials:
- XIAO Pi USB MIDI Device PCB.
- 3x H11L1 optoisolator.
- 1x 1N914 or 1N4148 diode.
- 1x 10R resistor.
- 1x 33R resistor.
- 1x 220R resistor.
- 2x 270R resistor.
- 3x 470R resistor.
- 3x 100nF ceramic capacitor.
- 1x 2-pin tactile switch.
- Optional: 2x 5-pin DIN – pcb mounted (see PCB and photos for footprint).
- OR 2x TRS stereo sockets - pcb mounted (see PCB and photos for footprint).
- Optional: 3x 6-pin DIP chip socket.
- Optional: 2x 7-way "short profile" header sockets.
- Optional: 1x 2x2 10mm "spring loaded pogo-pin" header.
- 1x 3-way header pins.
- 40-way (20x2) RPi GPIO extended header socket.

Errata:
- 3V3 for the external MIDI circuit should be connected to the XIAO not the RPi.
- PCBs lists 250R and 10R resistors for the internal MIDI links, but should be a single 270R resistor.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
