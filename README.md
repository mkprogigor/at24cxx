# at24cxx
Lightweight and short library for I2C memory chip AT24Cxx for Arduino (in development).

...

Function => **bool begin(_i2c_addr)**<BR>

Function => **byte read(uint16_t _lv_mem_addr)**<BR>

Function => **bool write(uint16_t _lv_mem_addr, uint8_t data)**<BR>

Function => **bool read_arr(uint16_t _lv_mem_addr, uint16_t _lv_size_dim, char* _lv_dim)**<BR>

Function => **bool write_arr(uint16_t _lv_mem_addr, uint16_t _lv_size_dim, char* _lv_dim)**<BR>



    
    
    
    

Functions don't use of delay, don't foget make 10ms delay ! afre write comman.
It should do it manually for benefits of using FreeRTOS.

I used oficial datasheet ATMEL 2-Wire Serial EEPROM 32K (4096 x 8), 64K (8192 x 8) for making this lib:<BR>
<BR>

