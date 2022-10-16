# Raspberry Pi Zynthian IO Board

This is a design for an IO board PCB for a Raspberry Pi Zynthian Synth module. It is specifically designed to be used with a Waveshare 4inch HDMI Resistive Touch Display.  It supports connections for four rotary encoders, a PCM5102 DAC and MIDI IN, OUT, THRU.

- Design notes: https://diyelectromusic.wordpress.com/2022/09/25/zynthian-revisited-part-3/
- Build and test notes: 

Bill of Materials (for the IO board, not a complete Zynthian):
- Zynthian IO Board PCB
- 1x 40-way extended GPIO header
- 1x GY-PCM1502 module
- 1x H11L1 optoisolator
- 1x 74HCT14 hex inverter (must be HCT version, not the HC version)
- 2x 220O resistors
- 1x 470O resistor
- 1x 9N419 or 1N4148 signal diode
- 12x 10nF ceramic capacitors
- 3x 100nF ceramic capacitors
- 1x 6-way DIP socket
- 1x 14-way DIP socket
- pin headers - either straight or right angle

Errata:
- There is an additional connection required on the rear of the PCB to connect two ground zones together.  See the build notes for details.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
