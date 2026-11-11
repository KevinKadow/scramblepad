# scramblepad
Hook up an Arduino to a Scramblepad reader using Wiegand.

A video showing the device with this code can be found here:
https://www.youtube.com/watch?v=9B5HAuZfDEQ

The most commonly available "legacy" Scramblepads run on 5-16 VDC and used a proprietary Hirsch MATCH/MATCH2 protocol:
<img width="1024" height="654" alt="image" src="https://github.com/user-attachments/assets/9daa4397-99c7-4b41-9b8b-bea46144f95a" />

* DS37L ???
* DS47L lacks cardreader support
* "ScramblePad TS" model DS47L-SSP-TS is RS-HIRSCH protocol over RS-485
* "TS ScramblePad" models 8235 / 8236 will support Weigand

Generally older models support only 125kHz HID/Proxcards, newer devices may support 13.56MHz NFC.

For more details, see https://bikerglen.com/blog/the-scramblepad-hardware-and-protocol/
