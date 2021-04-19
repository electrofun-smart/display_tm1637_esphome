# display_tm1637_esphome
Display TM1637 controlled by ESP8266 with ESPHome and MQTT showing subscribers count and other info

https://youtu.be/27JZEky0h1Q

In the video above I explore the 7 segment display type TM1637 controlled by ESP8266 flashed with ESPHome.io firmware. This 4 digit display is simple and  can be very useful and show a lot of information!

For instance, it can be a digital clock or a countdown timer.
Or
Used to show temperature 
Or humidity
Or even the number of subscribers in your Youtube channel

This project shows all these information given as example and a simple web user interface to control the countdown timer and what to show.

All you need for this project is a ESP8266 (I used Wemos D1 type, but can be any type), wires and of course the display TM1637. 
The rest of the project is just software and configuration. 

I used the firmware ESPHome as it has support (implemented library) for display TM1637 and I was willing to try this firmware for the first time.
 
This project also requires a MQTT broker like Mosquitto or a subscription to any MQTT broker service. 

I also used Node-RED in this project to read APIs from Youtube and from Weather service and to push data via MQTT to ESP8266 and to have a simple web interface to control the display. What I did with Node-RED can be done in other ways, but I found it easier to use Node-RED.

For Youtube API on Node-RED check this video:
https://www.youtube.com/watch?v=ZYInAIBIPXU

For Weather API Service:
https://www.visualcrossing.com/weather-api
(You just need to create your account and the free version is enough for this project)
