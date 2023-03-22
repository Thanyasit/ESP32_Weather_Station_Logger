# ESP32 Weather Station Logger
<h2>Description</h2>
This is a simple Arduino sketch for collecting data from a BME280 sensor, a PMS5003 particle sensor, and a UV sensor. The collected data is printed over serial in CSV format. The sketch was written in C++ and has been tested on an Arduino Uno.<br>
<b>2020</b>

<h2>Prerequisites</h2>
Before using this program, make sure you have the following libraries installed:<br><br>

- Wire.h - included with Arduino IDE<br> 
- SPI.h - included with Arduino IDE<br> 
- Adafruit_Sensor.h - install from the Arduino Library Manager<br> 
- Adafruit_BME280.h - install from the Arduino Library Manager<br> 
- PMS.h - install from the Arduino Library Manager<br> 

<h2>Usage</h2>
1. Connect the BME280, PMS5003, and UV sensor to the appropriate pins on the Arduino board.<br> 
2. Upload the sketch to the Arduino board using the Arduino IDE.<br> 
3. Open the Serial Monitor in the Arduino IDE or a serial terminal of your choice.<br> 
4. The collected data will be printed over serial in CSV format.<br> 

## Example

[Excel auto graph](https://www.youtube.com/watch?v=n86BISk9gv4)

<p align="center">
<img src="https://user-images.githubusercontent.com/77733903/226975402-227af41a-ae52-4a85-bd28-a144e16e5bfe.jpg" width="300">
</p>

<h2>License</h2>

This code is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
