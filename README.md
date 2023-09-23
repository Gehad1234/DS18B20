# DS18B20 one of semicolon startup IOT projects (My startup)
### Description

This Arduino project is a simple temperature sensor data logger using the DS18B20 digital temperature sensor. It reads temperature data from the sensor and logs it to the Serial Monitor in both Celsius (ºC) and Fahrenheit (ºF) at regular intervals. The project utilizes the OneWire and DallasTemperature libraries to interface with the DS18B20 sensor.

### Components

- **DS18B20 Digital Temperature Sensor**: The project uses the DS18B20 sensor to measure temperature. It is a digital sensor that communicates over a one-wire interface.

### Libraries Used

- **OneWire Library**: The OneWire library is used to communicate with OneWire devices like the DS18B20 temperature sensor.

- **DallasTemperature Library**: The DallasTemperature library is used to interface with the DS18B20 sensor and retrieve temperature readings.

### Setup

1. Connect the DS18B20 sensor to the Arduino board:
   - Connect the sensor's VCC pin to 5V.
   - Connect the sensor's GND pin to GND.
   - Connect the sensor's DATA pin to a digital pin (in this project, it's connected to digital pin 4).

2. Upload the provided Arduino sketch to your Arduino board using the Arduino IDE.

3. Open the Serial Monitor at a baud rate of 115200 to view the temperature data.

### Usage

Once the project is set up and the Arduino is powered on, it will continuously read temperature data from the DS18B20 sensor and display it in both Celsius and Fahrenheit on the Serial Monitor. The delay between readings is set to 5 seconds (adjustable in the code).

### Contributing

Feel free to modify and extend this project to suit your specific needs. You can enhance it by adding features like data logging to an SD card or sending temperature data to a remote server for further analysis. Contributions and improvements are welcome!

### License

This project is open-source and available under an open-source license (mention the specific license used). Please refer to the LICENSE.md file for more details.

### Author

Gehad Abdellah 

### Acknowledgments

Special thanks to the authors and contributors of the OneWire and DallasTemperature libraries for their work in making this project possible.
