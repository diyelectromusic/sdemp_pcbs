# Raspberry Pi MiniDexed IO Module (HD44780 Version)

This is an IO module for MiniDexed running on a Raspberry Pi.  It provides a 16x2 HD44780 based LCD display, GY-PCM5102 module DAC, a serial MIDI IN, OUT and THRU ports and a rotary encoder and optional buttons as an interface.

- Design notes: https://diyelectromusic.wordpress.com/2022/07/28/minidexed-raspberry-pi-io-board/
- Build and test notes: https://diyelectromusic.wordpress.com/2022/08/16/minidexed-raspberry-pi-io-board-part-3/

Bill of Materials:
- Raspberry Pi MiniDexed IO Module (HD44780 Version) PCB.
- Raspberry Pi V3 or V4.
- 1x H11L1 optoisolator.
- 1x 74HCT14 hex inverter.
- 1x GY-PCM5102 DAC module.
- 1x 16x2 HD44780 LCD (not the I2C version).
- 5x 220O resistor.
- 1x 4K7O resistor.
- 1x 1N914 or 1N4148 diode.
- 3x 100nF ceramic capacitors.
- 5x 10nF ceramic capacitors.
- 1x 100uF 16V electrolytic capacitor.
- 1x Switched rotary encoder (see PCB and photos for footprint).
- 3x 5-pin DIN – pcb mounted (see PCB and photos for footprint).
- 1x 6-pin DIP chip socket.
- 1x 14-pin DIP chip socket.
- 1x 2x20 way extended GPIO header socket.
- 1x 16-way header socket (optional).
- 1x 6-way header socket (optional).
- header pins (optional).

Errata:
- The PCB shows "5x 10pF" capacitors, but they should be 5x 10nF.
- The buttons are labelled "Home" and "Select" but actually are more useful is configured for "home" and "back" functions.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
