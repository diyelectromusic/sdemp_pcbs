# Raspberry Pi Pico MIDI Splitter (TTL)

This provides a eight-OUT MIDI splitter based on the Raspberry Pi Pico.  The eight OUT TX ports are linked to PIO serial ports.  UART 0 is linked to additional MIDI IN and OUT ports.  The eight TX ports are designed to connect directly to the 5V RX input of another microcontroller.  Do not use with a 3V3 microcontroller unless it is 5V tolerant.

- Design notes: https://diyelectromusic.wordpress.com/2022/09/25/raspberry-pi-pico-midi-splitter-ttl/
- Build and test notes: https://diyelectromusic.wordpress.com/2022/10/17/raspberry-pi-pico-midi-splitter-ttl-part-2/

Bill of Materials:
- Pico MIDI Spliitter TTL PCB.
- Raspberry Pi Pico.
- 1x H11L1 optoisolator.
- 3x 74HCT14 hex inverters.
- 3x 220R resistor.
- 1x 470R resistor.
- 1x 1N914 or 1N4148 diodes.
- 4x 100nF ceramic capacitor.
- 2x 5-pin DIN – pcb mounted (see PCB and photos for footprint).
- Optional: 1x 6-pin DIP chip socket.
- Optional: 3x 14-pin DIP chip sockets.
- Optional: Raspberry Pi Pico headers: 2x 20-way sockets.
- Pin headers

Errata:
- None.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/pcbs/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
