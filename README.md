# Temp_noti_line
This project uses the DHT11 temperature and humidity sensor to monitor the environment and sends notifications via Line.

<h2>Requirements</h2>
- DHT11 temperature and humidity sensor
- ESP32/ESP8266 or other compatible microcontroller
- LINE account and LINE Notify token
<h2>Getting Started</h2>
1.Connect the DHT11 to your microcontroller.
2.Modify the <b>SSID</b> and <b>LINE_TOKEN</b> variables in the code to match your Wi-Fi SSID and LINE Notify token.
3.Flash the code to your microcontroller.
4.Power on your microcontroller.

<h2>How it Works</h2>
The microcontroller reads the temperature and humidity data from the DHT11 sensor, computes the heat index, and sends notifications via Line Notify. The notifications include the current temperature, humidity, and heat index.

<h2>Troubleshooting</h2>
- If you're not receiving notifications, check your LINE Notify token and Wi-Fi connection.
- If the DHT11 sensor fails to read, the program will return an error message in the serial monitor.

<h2>License</h2>
This code is licensed under the MIT License. See the LICENSE file for details.
