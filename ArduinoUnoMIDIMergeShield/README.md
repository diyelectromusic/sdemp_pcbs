# Arduino Uno MIDI Merge Shield

A dual MIDI IN, single MIDI OUT shield for an Arduino Uno.  The board uses the hardware UART for IN and OUT and softare serial connected to D2 for the second IN.

- Design notes: https://diyelectromusic.wordpress.com/2022/06/13/arduino-uno-dual-merge-midi-shield-part-2/
- Build and test notes: https://diyelectromusic.wordpress.com/2022/07/06/arduino-uno-dual-merge-midi-shield-part-3/

Bill of Materials:
- MIDI merge PCB.
- Arduino Uno.
- 2x 6N138 optoisolators.
- 6x 220O resistors.
- 2x 4K7O resistors.
- 2x 1N914 diodes.
- 2x 100nF ceramic capacitors.
- 3x 5-pin DIN – pcb mounted (see PCB and photos for footprint).
- 2x 8-pin DIP chip sockets.
- Optional: 1x DPDT PCB mounted switch (see PCB and photos for footprint).
- OR: 2x 3-way header pins and two jumpers.
- Arduino headers: 1x 10-way; 2x 8-way; 1x 6-way “extended” or “stacked” headers (required for their extra height – see photos).

Errata:
- The footprint for the 6N138 8-pin DIP socket is too wide.  The blog shows a workaround.
- The MIDI disable switch needs a more helpful label.

If you like what you see, you can buy me a Ko-Fi - https://ko-fi.com/diyelectromusic

#  A Word of Caution!

Please note - I consider myself a novice at pcb design!

**Don't spend your own time and resources on any of these designs without knowing what you are doing.  They are not "off the shelf products" ready to go!**

Do not use this with expensive computer, audio, music or electronic equipment, it is for hobby use only.  For more details, see https://diyelectromusic.wordpress.com/

# License

All information is provided AS IS with no implied fit for purpose as detailed in the included MIT License.

All content and code (c) diyelectromusic (Kevin)
