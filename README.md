# SmartAC
A smart AC controller implemented with esp8266 and raspberry pi

# How to run
 - First install platformio dependencies from [here](http://docs.platformio.org/en/latest/installation.html) 
 - For Actuator and Thermometer
    - `cd Actuator`
    - `make`
    - `make upload`
    - `cd ..`
    - `cd Thermometer`
    - `make`
    - `make upload`
 - For the server
    - `cd Server`
    - `python server.py [-h] [--verbose] [-ip IP] [-port PORT]`'
    
# Wiring
 - Thermometer
   ![Thermometer](Thermomter.png)

# The setup of the actuator
![](20170603_165503.jpeg)
 
