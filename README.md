 Maple_BME_CC_Sensor
BME680 Bosch-Sensortec-BSEC Implementation for MapleMini-Board with STM32F103RCBT6-Controller (ARM-M3)
Using Watterott.com Breakoutboard. (Bluedot also possible.) 

Using these libraries:

OLED-I2C-Lib: https://github.com/greiman/SSD1306Ascii
BME680: see @ Bosch-Sensortec
RFM69CW for RF-Transmission to LaCrosseGateway (FHEM, ESP8266) see:
https://forum.fhem.de/index.php/topic,43672.msg355938.html#msg355938

See some presets to arduino linker environment and configuration:
https://wolfgangklenk.wordpress.com/2017/11/05/indoor-air-quality-iaq-measurement-with-bosch-bme680-and-stm32f103c8t6/
or here: https://github.com/BoschSensortec/BME680_driver/issues/6


Some future improvements and todo's: I2C transfer speed increase for SSD1306 OLED-display 128x64.



