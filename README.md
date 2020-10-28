# Micro-Console
 An Arduboy clone.  I can't think of a witty name.

# Background
This started as a simple project to throw together a PCB with some buttons and an OLED display on which my kids could learn programming and be entertained.  While googling my way to get started I discovered, of course, something like this has already been done and it's called the Arduboy.  It comes with a huge library of games, several community-driven spin-offs, and ports to different MCUs.  There's also the Gamebuino and a bunch of one-off creations enthusiasts have developed but we're going to stick with the Arduboy design here.  Why give up such a huge library of existing software and the community support?

# Design
The Arduboy is based on the ATmega32u4.  For this project I use the Arduino Micro with the ATmega32u4 onboard.  I'd prefer to use my beloved Wemos D1 mini but I'd rather not use or maintain a ported library, nor do I care to work around the limited IO of the D1 mini.  When the time comes to add Internet access to this device, I will add some form of the ESP8266 with its own library that can co-exist with the Arduboy's library.  Also planned for a future iteration of this board is the SPI memory device to store multiple software downloads.

# Credit
Naturally, credit is owed to Kevin Bates for instigating the whole Arduboy endeavor.
