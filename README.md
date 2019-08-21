# ESP32-CAM_TANK

This is fork of PepeTheFroggie's project [https://github.com/PepeTheFroggie/ESP32CAM_RCTANK],
a nice example of using ESP32 CAM (IP connected tank streaming wideo and serving its own controller web page.
It is good starting example demonstrating
- controlling two DC motors by 4 pins
- controlling servo
- controlling LED on the board
- web server

This fork aims to adds some clutter to the example to permit
- posting acquired dynamic IP address to DynamicDNS. This resolves the problem of finding IP address of your IOT gadget when your network WiFi gives you only dynamic address.  (not committed yet)
- enabling multiple WIFI credentials (not committed yet)
- indication of the connection by blinking LED


Esp32 controlling tracked vehicle while streaming video.
Serial console tells you where to connect. And use your own wifi credentials, not mine.

Wiring:
![esp32cam.jpg](esp32cam.jpg "Wiring")

Control:
![DSC02367.jpg](DSC02367.jpg "Control")

Build:
![DSC02365.jpg](DSC02365.jpg "Build")

Extern antenna:
![DSC02372.jpg](DSC02372.jpg "extant")

Video:
https://youtu.be/qUAGnk382mc
