# domotic

Control the electronic devices on your house using Arduino, a JAVA Web Server and JavaScript!


Specifically we settled in being able to control the lights on 5 rooms and 1 fan. We added some voice commands to gamble with, keep in mind that the HTML5 Speech Recognition API is pretty raw atm.

This project makes use of:
* Arduino Uno board*: https://www.arduino.cc/
* 8x White LEDs, in 5 pins
* 5x 330 ohm Resistor
* A USB Fan (5V)
* Some cable
* A carefully handcrafted model to put everything on
* Breakoutjs: https://github.com/soundanalogous/Breakout


This proyect had focus on showing what's feasible in the field of IoT, Domotic and Home Automation. But more importantly, it serves as a fundation to what can be done in those fields.
Also keep in mind that this was done with very little resources on purpose, so that it can be easily replicated and further developed. The later which we strongly encourage.

The fun part here is that we are using JavaScript, which is a language well known by web developers, to interact with Arduino.

Pro tip, you can use relays to control 100-240v.


![alt tag](http://labs.fgilio.com/mozilla/domotic/pic1.jpg)

\*In the picture you can see that there's a WiFi Shield attached on the Arduino, but it was not in use.
