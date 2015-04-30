This code project combines the Arduino SdFat library with low-level IDE access routine to allow a IDE hard drive to be interfaced to an Arduino Mega.  The Mega is required as 24 digital pins are required to implement the necessary portion of the IDE interface.

This project is based on the excellent IDE information and implementation found at http://www.pjrc.com/tech/8051/ide/index.html, which is based on Peter Faasse's excellent write-up on IDE.

No additional hardware is required unless a drive activity LED is required.  I directly connected the Arduino pins via jumper wires to a standard IDE ribbon cable attached to the test drive.  I used a small breaboard for the drive activity LED and Vcc/GND busses.