# farmism
sensor based farming

## Benefits of Sensor Based Farming

- Increased yield 
- Reduced need for fertilizers
- Water conservation
- Reduced environmental footprint
- Improved crop experimentation
- Measure greenhouse designs
- Process automation

## Build 

- Sensoring Instance
- Router
- Dashboard

### Sensoring Instance

#### Components 

- ESP8266 Module 
- Battery
- Small solar panel 
- Casing
- Wires, resistors, LDO regulators
- Sensors

#### Sensors

- Sunlight (minutes)
- Rainfall (mm) 
- Temperature
- Air Pressure
- Humidity
- CO2 
- Ultrasonic
- Water Flow Rate
- Lightning and Thunder Sensor 
- Wind speed and direction
- UV Index

## Router

For router we recommend GLi AR-150, but any router will work. If there is already router in use (e.g. internet or other home or community use), that router can be used as well.

## Dashboard

### Components 

There are two scenarios; where internet access is available and when there is no internet acccess. If internet access is available, any live server or cloud instance will do. Otherwise a Rasperry Pi ZeroW (connected to the router) would work. Again, if there is already a device such as a laptop for other uses, that will work too. 

NOTE: The dashboard device needs to be live 24/7.

### Software

- Node-Red
- Mosquitto 



## Cost

The cost associated with setting up a single farmism instance is between $12 and $25, depending on the number of sensors included.


D
Misc components like wires, resistors, LDO regulators - $2-4

In general you can do A + (one or more from B) + C + D 

So with the just temperature/pressure/humidity, we see a cost of around $2 + $3 + $5-8 + $2-4 = $12-$25



### Sensor board

- Node-MCU or ESP8266 board

You might want to start with BME280 breakout module as your first sensor.

### Router 

- GLi AR-150 or similar 

If you want to push data to the internet, the router needs to be. 

### Broker 

- Rasperry Pi or similar

Mosquito needs to run on this device. 

