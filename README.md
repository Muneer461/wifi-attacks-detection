<h1>WiFi Deauthentication Detection using ESP8266</h1>
<p>This project shows how to detect WiFi deauthentication attacks using an ESP8266 board. A WiFi deauthentication attack is a type of denial-of-service attack that can disconnect any device from a WiFi network by sending fake deauthentication frames. This can be used for testing and educational purposes, but also for malicious attacks.</p>
<p>This project uses an ESP8266 board with NodeMCU firmware, which can be programmed using Arduino IDE. The board has a LED that will light up in different colors depending on the type of deauthentication frame detected. The board can also send the information to a serial monitor or a web server.</p>
<img src="https://protosupplies.com/wp-content/uploads/2018/07/ESP8266-NodeMCU-V1.0-ESP-12E-WiFi-Module.jpg" width="300" height="200">
<img src="https://iotdesignpro.com/sites/default/files/main-image/ESP8266-based-Webserver-to-Control-LED-from-Webpage.jpg">
<img src="https://cdn.shortpixel.ai/spai/q_lossy+ret_img/https://i2.wp.com/www.electroniclinic.com/wp-content/uploads/2020/06/NodeMCU_PWM_Pins.png?w=1281&ssl=1" width="300" height="200">
<h2>Requirements</h2>
<p>Here's what you'll need:</p>
<ul>
  <li>ESP8266 MCU node: https://arduino.esp8266.com/stable/package_esp8266com_index.json</li>
  <li>USB cable</li>
  <li>Arduino software: https://downloads.arduino.cc/arduino-ide/arduino-ide_2.3.2_Windows_64bit.exe</li>
  <li>Breadboard</li>
</ul>
<p>Keep the ESP8266 module in the breadboard and connect pin D5 to ground. It will light up the LED on the board when any attack happens on the given WiFi.</p>
<h3>Disclaimer</h3>
<p>This project is a proof of concept for testing and educational purposes only. Neither the ESP8266 nor its SDK was meant or built for such purposes. Bugs can occur! Use it only against your own networks and devices!</p>
<p>Please check the legal regulations in your country before using it. We don't take any responsibility for what you do with this program.</p>
