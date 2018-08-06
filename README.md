# mp3sensor

mp3 chip with some sensors


#Programming exmpale
PS C:\Users\master\Downloads> .\avrdude.exe -c usbasp -p t13 -U flash:w:D:\atmel_projects\attiny13ablink\attiny13ablink\
Debug\attiny13ablink.hex:i

avrdude.exe: warning: cannot set sck period. please check for usbasp firmware update.
avrdude.exe: AVR device initialized and ready to accept instructions

Reading | ################################################## | 100% 0.02s

avrdude.exe: Device signature = 0x1e9007 (probably t13)
avrdude.exe: NOTE: "flash" memory has been specified, an erase cycle will be performed
             To disable this feature, specify the -D option.
avrdude.exe: erasing chip
avrdude.exe: warning: cannot set sck period. please check for usbasp firmware update.
avrdude.exe: reading input file "D:\atmel_projects\attiny13ablink\attiny13ablink\Debug\attiny13ablink.hex"
avrdude.exe: writing flash (1014 bytes):

Writing | ################################################## | 100% 0.95s

avrdude.exe: 1014 bytes of flash written
avrdude.exe: verifying flash memory against D:\atmel_projects\attiny13ablink\attiny13ablink\Debug\attiny13ablink.hex:
avrdude.exe: load data flash data from input file D:\atmel_projects\attiny13ablink\attiny13ablink\Debug\attiny13ablink.hex:
avrdude.exe: input file D:\atmel_projects\attiny13ablink\attiny13ablink\Debug\attiny13ablink.hex contains 1014 bytes
avrdude.exe: reading on-chip flash data:

Reading | ################################################## | 100% 0.77s

avrdude.exe: verifying ...
avrdude.exe: 1014 bytes of flash verified

avrdude.exe: safemode: Fuses OK (E:FF, H:FF, L:6A)

avrdude.exe done.  Thank you.
