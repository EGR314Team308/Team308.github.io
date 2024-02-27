# Component Selection
Major component selection was completed by researching different options, optaining necessary details from reviews and datasheets.  The top three options were evaluated and based on the user needs and the project parameters, the best one was selected for order.
## **Humidity Sensors**
Option 1 
1649-SHT40-AD1B-R2CT-ND:
Sensor Humidity 100RH SMD, $2.58/each
Pros:  I2C, Low power, SM, Low price, 0~100% Humidity range
Cons:  6 sec response time, +-1.8% RH Accuracy
Option 2
1649-SHT45-AD1B-R3TR-ND:
Sensor Humidity 100RH SMD, $7.18/each
Pros: I2C, Low power, SM, 0~100% Humidity range
Cons: 6 sec response time, +-1.5% RH Accuracy, $5.38 more for a 0.3% accuracy difference
Option 3
497-15382-2-ND:
Sensor Humidity 100RH SMD, $5.36/each
  
Pros: I2C, SPI, Very Low power, SM, 0~100% Humidity range, 6 sec response time, +-4.5% RH Accuracy
Cons:  Poor price to performance
Option 4
296-HDC3021DEHRTR-ND:
Sensor Humidity 100RH SMD, $5.61/each
Pros:  I2C, Very Low power, SM, 0~100% Humidity range, +-0.5% RH Accuracy
Cons:  4 sec response time, More than double the price of option 1
### **Chosen part is Option 4**
296-HDC3021DEHRTR-ND provides the best price to performance, with a higher accuracy than all of the other selected options. Although it is more expensive than option 1, when compared to similarly priced models it has much greater performance with a very low response time. It also meets the surface mount and I2C requirements.
## **Temperature Sensors**
Option 1
TC74A4-3.3VCTCT-ND: Temperature Sensor, $1.15/each
Pros:  It is already in Peralta Lab,  Inexpensive, The range of temperature is good
Cons:  It is very small which is hard for soldering, The datasheet does not have a circuit with it
Option 2
568-4768-1-ND: Temperature Sensor, $0.91/each
Pros:  Cheapest option,  Extensive datasheet, Has the biggest width to help with soldering
Cons: Has 8 pins compared to the others, Has the highest voltage supply
Option 3
DS1775R+T&RCT-ND: Temperature Sensor, $3.21/each
Pros:  Has the most features, High Resolution, Is a combination of the other options
Cons:  Does not say how large it is, Most expensive
### **Chosen part is Option 1**
TC74A4-3.3VCTCT-ND is the best because of the capabilities and amount available. It has all the features that are needed to measure temperature in a greenhouse. There are also many in stock along with there many in the Peralta Lab. It is also inexpensive with the only main problem being it is very small.
## **Switching Power Regulator**
Option 1
LM2575S-3.3/NOPB
Buck Switching Regulator IC Positive Fixed 3.3V, $4.76/each
  
Pros: High efficiency, 5 pin, Heat sink, 7-40 V DC Input, 3.3V output
Cons: 1 A output
Option 2
AP64350SP-13:
Buck Switching Regulator IC Positive Adjustable Output 3.5A, $1.58/each
  
Pros:  High efficiency, 3.8 to 40 V input, UVLO, OVP, Price, Easy to solder
Cons:  3.5 A output, Adjustable .8 to 39 V output, 8 pin
Option 3
TPS560430X3FDBVR:
Buck Switching Regulator IC Positive PWM 3.3V, $1.07/each
  
Pros:  6 pin, 4 to 36 V input, 3.3 V output, Price, Easy to solder
Cons:  600mA, No heatsink
### **Chosen part is Option 2**
AP64350SP-1 Buck Switching Regulator is the best choice as it has over voltage and under voltage protection, it has higher output current, and it has a low cost.  It is adjustable which makes it more versatile if possibly more difficult to configure. If needed a 3.3V output version could be found to make configuration easier.  AP63203WU-7 is an example with 2A output.
## **Power Supply**
Option 1
L6R48-120:  AC/DC WALL MOUNT ADAPTER 12V 48W , $18.19/each
Pros:  12V, 4A, Price, No recharging needed
Cons: Requires AC outlet
Option 2
PC5-12F1:
BATTERY LEAD ACID 12V 5AH, $28.25/each
Pros: 12V,  5AH, 3.54" L x 2.76" W x 3.98" H, Lead Acid, Price
Cons:  20 hr discharge rate, 1.6 kg
Option 3
PCLFP10-12.8F2:
BATTERY LITHIUM 12.8V 10AH, $127.16/each
Link to product
  
12V
10AH
3.54" L x 2.76" W x 3.98" H
10 Amp output
1.6 kg
Price
Lithium
5.94" L x 3.86" W x 3.74" H

### **Chosen part is Option 2**


L6R48-120:  AC/DC WALL MOUNT ADAPTER is the best choice since it provides the needed power without having to be recharged.  Our application is not mobile, so providing power from an outlet makes sense.  It is also the most cost effective.

## **Motor Driver**

Option 1

ZXBM5210-S-13:
Motor Driver Power Mosfet PWM 8-SO, $1.5/each

Pros: 3V-18V, PWM, Fully integrated, control and power stage

Option 2

MP6513LGJ-Z:
Bipolar Motor Driver Power Mosfet TSOT-23-6, $0.9/each

Pros: 2.5V-5.5V, PWM, Cheapest, Thermal shutdown, Overcurrent protection

Cons: 600mA output


Option 3

A4953ELJTR-T:
IC Motor Driver 8V-40V 8SOIC, $1.82/each

Pros: DMOS, PWM, 8V-40V, Fully integrated, control and power stage, Overcurrent protection

Cons: Highest price out of the three, 2A output

### **Chosen part is Option 2**
Choice: Option 2 MP6513LGJ-Z, Bipolar Motor Driver Power Mosfet TSOT-23-6

MP6513LGJ-Z, Bipolar Motor Driver Power Mosfet TSOT-23-6 is the cheapest option out of the three, but it also has other functions. It has thermal shutdown, undervoltage lockout, overvoltage protection and overheat protection. Option 3 is also a good option but the voltage is too high.



## **Motor**


Option 1

2790-HC385MG-301-ND: Brushed Motor, $6.45/each

Pros: 24 V,  18000 RPM, Wide operating temperature

Cons: Small and compact, Datasheet is not available

Option 2

1568-ROB-15277-ND: Brushed Motor, $6.88/each

Pros: 1.6 W, Large, Large gear reduction

Cons: Not an extensive datasheet, Low RPM


Option 3

2183-998-ND: Brushed Motor, $19.95/each

Pros: High current flow, Extensive datasheet, Quick connect

Cons: Low voltage, Small and compact


### **Chosen part is Option 1**

2790-HC385MG-301-ND Brushed Motor is both the cheapest and highest voltage and rotations per minute. It is large and shows all features like operating temperature. There are motors in Peralta Lab which could also be used.## Power Budget
## Power Budget

| All Major Components                                                                                                                                                                                                                                                                                                                                                                                               | Component Name                                               | Part Number      | Supply (V)<br>Voltage<br>Range | #              | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- | ------------------------------ | -------------- | ----------------------------------- | ------------------------ | ---- |
| 12V DC motors                                                                                                                                                                                                                                                                                                                                                                                                      | GEARMOTOR 140 RPM 6-24V                                      | ROB-15277        | 6-24                           | 2              | 1300                                | 2600                     | mA   |
| Motor controller                                                                                                                                                                                                                                                                                                                                                                                                   | IC HALF BRIDGE DRIVER 6A 12DSO                               | IFX9201SGAUMA1   | 0-36                           | 2              | 13                                  | 26                       | mA   |
| Temperature sensors                                                                                                                                                                                                                                                                                                                                                                                                | SENSOR DIGITAL -40C-125C SOT23-5                             | TC74A4-3.3VCTTR  | 2.7-5.5                        | 2              | 0.35                                | 0.7                      | mA   |
| Humidity sensors                                                                                                                                                                                                                                                                                                                                                                                                   | 0.5% RH DIGITAL HUMIDITY SENSOR                              | HDC3021DEHR      | 1.6-5.5                        | 2              | 0.17                                | 0.34                     | mA   |
| Microcontroller                                                                                                                                                                                                                                                                                                                                                                                                    | IC MCU 8BIT 7KB FLASH 28SOIC                                 | PIC16F15354-E/SO | 2.3-5.5                        | 1              | 32                                  | 32                       | mA   |
| Limit switches                                                                                                                                                                                                                                                                                                                                                                                                     | SWITCH SNAP ACTION SPDT 3A 125V                              | SS0750303F050P1A | 0-125                          | 2              | 1                                   | 2                        | mA   |
| Red LED's                                                                                                                                                                                                                                                                                                                                                                                                          | LED RED CLEAR 1206 SMD                                       | LTST-C150KRKT    | 2-2.4                          | 2              | 25                                  | 50                       | mA   |
| Blue LED's                                                                                                                                                                                                                                                                                                                                                                                                         | LED BLUE CLEAR 1206 SMD                                      | LTST-C150TBKT    | 2.8-3.8                        | 2              | 25                                  | 50                       | mA   |
| Schottky diode                                                                                                                                                                                                                                                                                                                                                                                                     | DIODE SCHOTTKY 40V 1A SOD123FL                               | DSS14U           | 0-40                           | 1              | 44                                  | 44                       | mA   |
| WIFI module                                                                                                                                                                                                                                                                                                                                                                                                        | ESP32 DEVKIT V1 WIRELESS WIFI                                | ESP32 DEVKIT V1  | 3-3.6                          | 1              | 500                                 | 500                      | mA   |
| +12V Power Rail                                                                                                                                                                                                                                                                                                                                                                                                    | Component Name                                               | Part Number      | Supply(V)<br>Voltage<br>Range  | #              | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| 12V DC motors                                                                                                                                                                                                                                                                                                                                                                                                      | GEARMOTOR 140 RPM 6-24V                                      | ROB-15277        | 6-24                           | 2              | 1300                                | 2600                     | mA   |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |                                |                |                                     |                          |      |
|                       |                  |                                |                |                                                                                                                                                                                                                                                                                                                       | Subtotal                                                     | 2600             | mA                             |
|                                                                                                                                                                                                                                                     |                  |                                |                |                                                                                         | Safety Margin                                                | 20%              |                                |
|                       |                  |                                |                |                                                                                                                                                                                                                                                                                                                       | Total Current Required on +12V Rail                          | 3120             | mA                             |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |                                |                |                                     |                          |      |
| Wall AC Adaptor-12V                                                                                                                                                                                                                                                                                                                                                                                                | AC/DC WALL MOUNT ADAPTER 12V 48W                             | L6R48-120        | 12                             | 1              | 4000                                | 4000                     | mA   |
|                                                                                                                                                                                                                                                     |                  |                                |                |                                                                                         | Total Remaining Current Available on +12V Rail               | 880              | mA                             |
| +3.3V Power Rail                                                                                                                                                                                                                                                                                                                                                                                                   | Component Name                                               | Part Number      | Supply(V)<br>Voltage<br>Range  | #              | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| Motor controller                                                                                                                                                                                                                                                                                                                                                                                                   | IC HALF BRIDGE DRIVER 6A 12DSO                               | IFX9201SGAUMA1   | 0-36                           | 2              | 13                                  | 26                       | mA   |
| Temperature sensors                                                                                                                                                                                                                                                                                                                                                                                                | SENSOR DIGITAL -40C-125C SOT23-5                             | TC74A4-3.3VCTTR  | 2.7-5.5                        | 2              | 0.35                                | 0.7                      | mA   |
| Humidity sensors                                                                                                                                                                                                                                                                                                                                                                                                   | 0.5% RH DIGITAL HUMIDITY SENSOR                              | HDC3021DEHR      | 1.6-5.5                        | 2              | 0.17                                | 0.34                     | mA   |
| Microcontroller                                                                                                                                                                                                                                                                                                                                                                                                    | IC MCU 8BIT 7KB FLASH 28SOIC                                 | PIC16F15354-E/SO | 2.3-5.5                        | 1              | 32                                  | 32                       | mA   |
| Limit switches                                                                                                                                                                                                                                                                                                                                                                                                     | SWITCH SNAP ACTION SPDT 3A 125V                              | SS0750303F050P1A | 0-125                          | 2              | 1                                   | 2                        | mA   |
| Red LED's                                                                                                                                                                                                                                                                                                                                                                                                          | LED RED CLEAR 1206 SMD                                       | LTST-C150KRKT    | 2-2.4                          | 2              | 25                                  | 50                       | mA   |
| Blue LED's                                                                                                                                                                                                                                                                                                                                                                                                         | LED BLUE CLEAR 1206 SMD                                      | LTST-C150TBKT    | 2.8-3.8                        | 2              | 25                                  | 50                       | mA   |
| Schottky diode                                                                                                                                                                                                                                                                                                                                                                                                     | DIODE SCHOTTKY 40V 1A SOD123FL                               | DSS14U           | 0-40                           | 1              | 44                                  | 44                       | mA   |
| WIFI module                                                                                                                                                                                                                                                                                                                                                                                                        | ESP32 DEVKIT V1 WIRELESS WIFI                                | ESP32 DEVKIT V1  | 3-3.6                          | 1              | 500                                 | 500                      | mA   |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |                                |                |                                     |                          |      |
|                       |                  |                                |                |                                                                                                                                                                                                                                                                                                                       | Subtotal                                                     | 705.04           | mA                             | 
|                       |                  |                                |                |                                                                                                                                                                                                                                                                                                                       | Safety Margin                                                | 20%              |                                |
|                       |                  |                                |                |                                                                                                                                                                                                                                                                                                                       | Total Current Required on +5V Rail                           | 846.048          | mA                             |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |                                |                |                                     |                          |      |
| Switching Power Regulator                                                                                                                                                                                                                                                                                                                                                                                          | IC REG BUCK 3.3V 1A D2PAK-5                                  | LM2575D2T-3.3R4G | 0-40                           | 1              | 1000                                | 1000                     | mA   |
|                       |                  |                                |                |                                                                                                                                                                                                                                                                                                                       | Total Remaining Current Available on +5V Rail                | 153.952          | mA                             |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |
| External Power Source 1                                                                                                                                                                                                                                                                                                                                                                                            | Component Name                                               | Part Number      | Supply<br>Voltage<br>Range     | Output Voltage | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| Wall AC Adaptor-12V                                                                                                                                                                                                                                                                                                                                                                                                | AC/DC WALL MOUNT ADAPTER 12V 48W                             | L6R48-120        | 12                             | 1              | 4000                                | 4000                     | mA   |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |                                |                |                                     |                          |      |
| Power Rails Connected to External Power Source 1                                                                                                                                                                                                                                                                                                                                                                   | Wall AC Adaptor-12V                                          | L6R48-120        | 12                             | 1              | 3120                                | 3120                     | mA   |
|                       |IC REG BUCK 3.3V 1A D2PAK-5                                                                                                                                                                                                                                                                                                                                                                  | LM7805                                                       | 0-40             | 1                              | 846.048        | 846.048                             | mA                       |
|                                                                                                                                                                                                                                                     |                  |                                |                 |                                                                                        | Total Remaining Current Available on External Power Source 1 | 33.952           | mA                             |









  





