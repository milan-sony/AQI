# AQI - Air Quality Index Monitor

AQI - The Air Quality Index Monitoring is build with ESP8266 &amp; MQ135 Sensor. Here we monitor the air quality on 0.96" I2C OLED Display and Thingspeak Server

## Pin Connections

#### MQ135 Sensor

- Analog input pin to A0 of NodeMCU
- VCC to Vin of NodeMCU 
- GND to GND of NodeMCU 

#### 0.96″ OLED Display is an I2C Module so,

- SDA to D2 of NodeMCU 
- SCL to D1 of NodeMCU 
- VCC to 3v3 of NodeMCU
- GND to GND of NodeMCU

> The value is Measured in Parts-per-million (abbreviated ppm), this is the ratio of one gas to another. For example, 1,000ppm of CO means that if you could count a million gas molecules, 1,000 of them would be of carbon monoxide and 999,000 molecules would be some other gases.
