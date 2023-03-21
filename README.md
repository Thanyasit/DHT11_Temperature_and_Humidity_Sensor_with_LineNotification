# DHT11_Temperature_and_Humidity_Sensor_with_LineNotification
This project uses the DHT11 temperature and humidity sensor to monitor the environment and sends notifications via Line.<br><b>2022</b>
<h2>Requirements</h2>

- DHT11 temperature and humidity sensor<br>
- ESP32/ESP8266 or other compatible microcontroller<br>
- LINE account and LINE Notify token<br>
<h2>Getting Started</h2>

1.Connect the DHT11 to your microcontroller.<br>
2.Modify the <b>SSID</b> and <b>LINE_TOKEN</b> variables in the code to match your Wi-Fi SSID and LINE Notify token.<br>
3.Flash the code to your microcontroller.<br>
4.Power on your microcontroller.<br>

<h2>How it Works</h2>
The microcontroller reads the temperature and humidity data from the DHT11 sensor, computes the heat index, and sends notifications via Line Notify. The notifications include the current temperature, humidity, and heat index.

<h2>Troubleshooting</h2>

- If you're not receiving notifications, check your LINE Notify token and Wi-Fi connection.<br>
- If the DHT11 sensor fails to read, the program will return an error message in the serial monitor.<br>

<h2>License</h2>

This code is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
