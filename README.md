# atmega8_2s_severino
Arduino Severino's Enchanced Bootloader 

Problem: 
If you use the official Arduino NG/older's Bootloader, and run ASCIITable sketch, you will need 10 seconds to receive serial data from Arduino. Using this hex file as a bootloader, you will get a faster response (around 2 seconds).

Reference for Board: http://arduino.cc/en/Main/ArduinoBoardSerialSingleSided3
Reference Bootlaoder: http://www.ngcoders.com/downloads/arduino-atmega8-bootloader-2-second-autoreset
        by Vikas Patial

Hardware Requirements:
  - Programmer (I use DFRduino UNO v2.0)
  - System Minimum for ATmega8 (Using an Arduino board to program an ATmega, 
                                with external crystal and associate capacitors)

Software Requirements:
  - Arduino (I use Arduino Enhanced Version, tweaks and little improvements by Erwin Reid)
            http://forum.arduino.cc/index.php?topic=118440.0
  - winAVR to erase and upload the bootloader.
