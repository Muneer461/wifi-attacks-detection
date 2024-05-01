<h1>WiFi Deauthentication Detection using ESP8266</h1>
<p>This project aims to demonstrate the detection of WiFi deauthentication attacks utilizing an ESP8266 board. A WiFi deauthentication attack is a form of denial-of-service attack capable of disconnecting any device from a WiFi network by sending falsified deauthentication frames. While primarily intended for testing and educational purposes, it's important to recognize its potential for malicious exploitation.</p>
<p>The implementation utilizes an ESP8266 board with NodeMCU firmware, offering programmability through the Arduino IDE. Equipped with an LED, the board illuminates in varying colors to indicate the type of deauthentication frame detected. Additionally, it can relay information to either a serial monitor or a web server, enhancing its versatility and utility.</p>
<div style="text-align:center;">
  <img src="https://protosupplies.com/wp-content/uploads/2018/07/ESP8266-NodeMCU-V1.0-ESP-12E-WiFi-Module.jpg" width="300" height="200">
  <img src="https://iotdesignpro.com/sites/default/files/main-image/ESP8266-based-Webserver-to-Control-LED-from-Webpage.jpg">
  <img src="https://cdn.shortpixel.ai/spai/q_lossy+ret_img/https://i2.wp.com/www.electroniclinic.com/wp-content/uploads/2020/06/NodeMCU_PWM_Pins.png?w=1281&ssl=1" width="300" height="200">
</div>
<h2>Requirements</h2>
<ul>
  <li>Sample Video: <a href="https://www.youtube.com/watch?v=Xz7QQ-xyBqk&t=144s">https://www.youtube.com/watch?v=Xz7QQ-xyBqk&t=144s</a></li>
  <li>Follow the instructions provided in the video while modifying the code as instructed, ensuring to update the WiFi username and password. Compile the code using the Arduino IDE and upload it to the ESP8266 module.</li>
  <li>ESP8266 MCU Node: <a href="https://arduino.esp8266.com/stable/package_esp8266com_index.json">https://arduino.esp8266.com/stable/package_esp8266com_index.json</a></li>
  <li>USB Cable</li>
  <li>Arduino Software: <a href="https://downloads.arduino.cc/arduino-ide/arduino-ide_2.3.2_Windows_64bit.exe">https://downloads.arduino.cc/arduino-ide/arduino-ide_2.3.2_Windows_64bit.exe</a></li>
  <li>Breadboard</li>
</ul>
<p>Ensure the ESP8266 module is securely placed on the breadboard and establish a connection between pin D5 and ground. This connection will activate the LED onboard, providing visual indication upon detection of any attacks on the specified WiFi network.</p>
<h3>Disclaimer</h3>
<p>This project serves as a proof of concept for testing and educational purposes exclusively. Neither the ESP8266 nor its associated SDK were developed or intended for such applications. Consequently, bugs and unintended consequences may arise. It is imperative to restrict usage to one's own networks and devices.</p>
<p>Prior to utilization, it is advised to review the legal regulations applicable in your region. We hereby absolve ourselves of any responsibility for the usage and consequences of this program.</p>
