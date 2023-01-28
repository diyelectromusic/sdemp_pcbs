# MiniDexed Pico TX816 - IO Board

This is the IO board for a TX816 style interface for MiniDexed running on a Raspberry Pi 3 or 4.

- Design notes: https://diyelectromusic.wordpress.com/2023/01/22/minidexed-tx816-part-2-pcb-design/
- Build and test notes: https://diyelectromusic.wordpress.com/2023/01/28/minidexed-tx816-part-4b-pcb-build-guide-io-board/

Bill of Materials:
- MiniDexed TX816 IO Board PCB
- 74HC595
- MAX7219
- Resistors: 8x1K, 1x50K
- Ceramic capacitors: 4x10nF, 2x100nF
- Electrolytic capacitor: 1x 10uF
- 8x LEDs (I used "lighthouse" or "tower" design - see photos)
- 4x 12mm tactile switches with 12x12mm key caps
- 4x two-digit, 7-segment displays with decimal point (20 pin variants - see photos)
- 4x 10K pcb mount potentiometers (see discussion on potentiomers below!)
- DIP sockets: 1x16-way, 1x24-way - Optional but highly recommended
- Pin header socket: 1x 20-way

Note: For the completed project, two of the IO boards, one of the Interface boards and a panel will be required.

Errata:
- The potentiometers are wired backwards.  This means "full zero" is fully clockwise and will need to be corrected in software.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
