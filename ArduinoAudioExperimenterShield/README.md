# Arduino Audio Experimenters Shield

A shield for an Arduino Uno, that provides MIDI IN/OUT, a R2R ladder, PWM output and connections for a MCP4725 DAC module.

- Design notes: https://diyelectromusic.wordpress.com/2022/11/01/arduino-audio-experimenter-shield-pcb/
- Build and test notes: https://diyelectromusic.wordpress.com/2022/11/17/arduino-audio-experimenter-shield-pcb-part-2/

Bill of Materials:
- Arduino Audio Experimenter Shield PCB.
- 2x 2-way header pins.
- 3x 3-way header pins
- 5x Jumpers.
- Arduino headers: pins or sockets, but note that extended headers will be required for a "USB B socket" Uno.

MIDI Section:
- 1x 6N138 optoisolator.
- 4x 220R resistors.
- 1x 4K7 resistor.
- 1x 1N914 or 1N4148 diode.
- 1x 100nF ceramic capacitor.
- 2x 5-pin DIN – pcb mounted (see PCB and photos for footprint).
- Optional: 1x 8-pin DIP chip socket.

R2R Section:
- 7x 10K resistors.
- 9x 20K resistors.

PWM Section:
- 1x 75R resistor.
- 1x 270R resistor.
- 1x 68nF ceramic capacitor.
- 1x 10uF electrolytic or non-polar capacitor.

DAC Section:
- MCP4725 DAC module with pinout: OUT-GND-SCL-SDA-VCC-GND
- Optional: 1x 6-way pin header socket.

Errata:
- The pinout for the DAC header is the wrong way round for mounting the DAC with "pins underneath".  See the build guide for details.
- The DAC has no audio filtering or coupling, so the audio jack has a 0-5V PWM signal as output.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
