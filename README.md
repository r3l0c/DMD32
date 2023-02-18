# Fast DMD32 
A library for driving the Freetronics 512 pixel dot matrix LED display "DMD", a 32 x 16 layout using ESP32.

This library is a fork of the [(DMD32)](https://github.com/Qudor-Engineer/DMD32) what was fork of original one [(DMD)](https://github.com/freetronics/DMD) modified to support ESP32 (currently it is only working on ESP32).
This version have optimized SPI transfer to achieve more than 2x times the speed at same clock. Allowing to increase refresh rate with multiple display modules. 

The connection between ESP32 and DMD display shown in the image below:






![](https://github.com/MiyukiDark/DMD32/blob/main/connection.png)



Miyuki
