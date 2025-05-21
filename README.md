# at24cxx
Lightweight and short library for I2C memory chip AT24Cxx for Arduino (in development).

...

Function => **bool begin(_i2c_addr)**<BR>

Functions don't use of delay, it should do it manually for benefits of using FreeRTOS.
Or usuing CPU resources for checkking results. Max measuring time takes about 200 mS, but You can check it.

I used oficial datasheet ATMEL 2-Wire Serial EEPROM 32K (4096 x 8), 64K (8192 x 8) for making this lib:<BR>
<BR>

