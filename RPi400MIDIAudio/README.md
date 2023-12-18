# Raspberry Pi 400 MIDI and Audio Module

This is a MIDI and I2S audio module for the Raspberry Pi 400.  It also includes optional additional elements to support the user interface controls for MiniDexed.

- Design notes: https://diyelectromusic.wordpress.com/2023/12/18/rpi-400-midi-and-audio-pcb-design/
- Build and test notes: 

Bill of Materials:
- Raspberry Pi 400 MIDI and Audio PCB.
MIDI Section:
- 1x H11L1.
- 1x 74HCT14.
- 5x 220R resistors.
- 1x 470R resistors.
- 2x 100nF ceramic capacitors.
- Either: 3x 5-pin, 180 degree PCB-mount DIN sockets (see photos for footprint).
- Or: 3x stereo TRS PCB-mount sockets (see photos for footprint).
- Optional: 6-way DIP socket; 14-way DIP socket.
- 1x 2×20-way right-angle GPIO header socket.
Audio/MiniDexed Section:
- 1x GY-PCM5102 DAC module.
- 1x SSD1306 32x128 OLED display (pin order: GND-VCC-SCL-SDA).
- 5x 10nF ceramic capacitors.
- 2x 100nF ceramic capacitors.
- 1x switched rotary encoder (see photos for footprint).
- 2x slim toggle pcb-mount button switches (see photos for footprint).
- Optional: 4-way header socket for SSD1306 display.

Errata:
- The silkscreen shows 5 "10p" capacitors.  These should be 10nF.
- If installed incorrectly (i.e. one pin out) in a RPi 400 it connects 5V to GND which will damage the RPi 400.
- When installed, it obscures the uSD card in a RPi 400.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
