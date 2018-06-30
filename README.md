<img src='https://raw.githubusercontent.com/mikkokotila/farmism/master/farmism_logo.png' width=200px>

Farmism Sensor System is a low-cost, easy-to-deploy agrigultural sensor technology helping micro and small size farms to improve efficiency while reducing environmental impact. The entire system can be deployed for less than $50 with zero recurring cost and can be entirely solar powered within that cost.

## Where Can It Be Used

Farmism Sensor System can be deployed on the field or in greenhouse. 

## Benefits of Sensor Based Farming

- Increased yield 
- Reduced need for fertilizers
- Water conservation
- Reduced environmental footprint
- Improved crop experimentation
- Measure greenhouse designs
- Process automation

## Build 

- [Sensoring Instance](https://github.com/mikkokotila/farmism#sensoring-instance)
- [Router](https://github.com/mikkokotila/farmism#router)
- [Dashboard](https://github.com/mikkokotila/farmism#dashboard-client)

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

List of supported sensors can be found [here](https://www.letscontrolit.com/wiki/index.php/Devices).

## Router

For router we recommend GLi AR-150, but any router will work. If there is already router in use (e.g. internet or other home or community use), that router can be used as well.

## Dashboard Client

### Components 

There are two scenarios; where internet access is available and when there is no internet acccess. If internet access is available, any live server or cloud instance will do. Otherwise a Rasperry Pi ZeroW (connected to the router) would work. Again, if there is already a device such as a laptop for other uses, that will work too. 

NOTE: The dashboard device needs to be live 24/7.

Minimum requirement: 

- Rasperry Pi
- Small solar panel 
- Battery bank

### Software

- Node-Red
- Mosquitto 
- Mosquitto Spy

## Cost

The cost is a factor of four things: 

- Sensoring Instance at $12 to $35 (depending on the sensors) 
- Router at up to $25
- Dashboard Client at up to $10
- Miscellaneous costs at up to $20

The total cost would range between $20 to $100 depending on criterias that had been explained in the above sections.
