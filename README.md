# 8bit8asterd
Firmware for the 8-Bit 8asterd (8B8) by Semiotic Sounds
email: greg@semioticsounds.com

V2.2 -- Added:
 * Drum Polyphony
 * Slow attack envelopes on channels 3 and 4
 * Altered drum sounds (808 bass and clave)
 * Arduino Reset function on MIDI KillAll message
 * Better voice distribution methodology

Upload firmware to the 8B8 via microUSB -- the process is identical to any upload process over Arduino IDE.

1. Download [Arduino IDE](https://www.arduino.cc/en/software) for your OS. Plug in your 8B8 to the computer.
2. Go to Tools > Board > Arduino AVR Boards and choose "Arduino Leonardo". If this board is not listed, go to "Board Manager" and type it in to download the library.
3. Go to Tools > Port and choose the port to which the Arduino Leonardo is attached.
4. Go to File > Open and find the 8B8 firmware ".ino" file provided here.
5. Click the Upload Arrow on the top left of the Arduino IDE screen to upload, it should only take a few seconds.
6. Enjoy!
