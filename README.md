# ESP8266_artnet_wlan_config_v0.1

Wlan Artnet Node for NeoPixel LED stripe
with Webserver for the Wlan setup
1. install the required libs on your IDE
2. change numLeds (Number of LEDs) at line 27
3. change dataPin (ESP Pin) at line 29
4. change Universe at line 34
5. flash on your ESP8266
6. connect to the ESP hotspot
   -> insert the ssid and pw from your router

if you want to know that your Node recive a message
you can activate the debug section between
line 105 and 130 -> if a message receive then it will be
printed at the serial monitor.
