# Block Diagram

![Team 308 Block Diagram](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/9df75bfa-bb54-413f-95c1-f48b2de0cf36)

## Member Contributions:

## Matt Olpin:
- Microcontroller And Switching Regulator:
  Controls and allocates resources throughout the system, upon being programmed will filter data input from the sensors and output commands to the motor. The switching regulator ensures proper power is being distributed correctly throughout the system.

## Gabriel Sandys:
- Humidity sensor:
  Recieves data from inside and outside the greenhouse related to humidity, which is sent to the microcontroller in tandum with data from the temperature sensor to interpret the data for motor output.

## Shawn Meris:
- Temperature sensor:
  Recieves data from inside and outside the greenhouse related to temperature, which is sent to the microcontroller in tandum with data from the humidity sensor to interpret the data for motor output.

## Roy Chang:
- Motor:
  After the microcontroller recieves the data from both sensors it will calculate the systems best course of action and send output data to the motor to allow the system to open and close doors for optimum plant growth.
