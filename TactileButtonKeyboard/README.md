# Tactile Button Keyboard

This is a tactile button music keyboard which supports a ROWS/COLS style interface; an on-board Arduino Nano; or a 74HC138 interface.

- Design notes: https://diyelectromusic.wordpress.com/2023/03/04/tactile-button-keyboard-pcb/
- Build and test notes: https://diyelectromusic.wordpress.com/2023/03/05/tactile-button-keyboard-pcb-part-2/

Bill of Materials:
- Tactile Button Keyboard PCB
- 12 or 13x tactile buttons.
- 12 or 13x 1N914 or 1N4148 signal diodes.
- Optional: 2x 15-way pin header sockets (for the Arduino Nano).
- If a 74HC138 is to be used, then the following are required.  But note that in the current version of the PCB this DOES NOT WORK without patching!
-- Optional: 1x 74HC138.
-- Optional: 1x 100nF ceramic capacitor (for the 74HC138).
-- Optional: 1x 16-way DIP socket (for the 74HC138).
- Pin headers.

Errata:
- The connections to the 74HC138 EN pins are backwards, meaning this DOES NOT WORK without patching.
- The diodes are also the wrong way round to support use with the 74HC138 regardless.
- The HC138 outputs are wired up back to front.
- The ROWS and COLS indications do not match the terminology used with the Arduino Keypad Library if the diodes are reversed.

Basically trying to use the board with the HC138 is a mess.  Sorry about that.  See design and build notes for details of the whole sorry mess! But using it with an Arduino directly isn't too bad!

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
