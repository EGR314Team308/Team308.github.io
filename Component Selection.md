# Component Selection

Major component selection was completed by researching different options, optaining necessary details from reviews and datasheets.  The top three options were evaluated and based on the user needs and the project parameters, the best one was selected for order.

## **Humidity Sensors**

Option 1 

1649-SHT40-AD1B-R2CT-ND:
Sensor Humidity 100RH SMD, $2.58/each

Pros:  I2C, Low power, SM, Low price, 0-100% Humidity range

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

HIH6030-021-001:
Sensor Humidity/Temp 3.3V I2C 4.5% SMD, $13.43/each

Pros:  I2C, long term stability, easiest to solder

Cons:  +-4.5% RH Accuracy, expensive

### **Chosen part is Option 4**

![humidity sensor](https://raw.githubusercontent.com/EGR314Team308/Team308.github.io/main/HIH6030-021-001.JPG)

HIH6030-021-001 has all of the options needed and is the only one that can reasonably be hand-soldered.  Unfortunately it is the most expensive option.

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

![temp sensor](https://raw.githubusercontent.com/EGR314Team308/Team308.github.io/main/temp%20sensor.JPG)

TC74A4-3.3VCTCT-ND is the best because of the capabilities and amount available. It has all the features that are needed to measure temperature in a greenhouse. There are also many in stock along with there many in the Peralta Lab. It is also inexpensive with the only main problem being it is very small.

## **Switching Power Regulator**

Option 1

LM2575S-3.3/NOPB:
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

### **Chosen part is Option 1**

![power regulator](https://raw.githubusercontent.com/EGR314Team308/Team308.github.io/main/power_regulator.JPG)

LM2575S-3.3/NOPB Buck Switching Regulator IC Positive Fixed 3.3V is the best choice since it has higher output current. It supplies the needed  3.3V output with a simple provide circuit using few components.

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

Pros:  12V, 10AH, 3.54" L x 2.76" W x 3.98" H, 10 Amp output

Cons:  1.6 kg, Price, Lithium, 

### **Chosen part is Option 2**

![AC adaptor](https://raw.githubusercontent.com/EGR314Team308/Team308.github.io/main/AC_adaptor.JPG)

L6R48-120:  AC/DC WALL MOUNT ADAPTER is the best choice since it provides the needed power without having to be recharged.  Our application is not mobile, so providing power from an outlet makes sense.  It is also the most cost effective.

## **Motor Driver**

Option 1

ZXBM5210-S-13:
Motor Driver Power Mosfet PWM 8-SO, $1.5/each

Pros: 3V-18V, PWM, Fully integrated, control and power stage

Option 2

IFX9201SGAUMA1:
IC Half Bridge Driver 6A 12DSO, $3.9/each

Pros: 3.3V, SPI, Cheapest, VS Undervoltage shutdown, Overcurrent protection,

Cons: Highest price


Option 3

A4953ELJTR-T:
IC Motor Driver 8V-40V 8SOIC, $1.82/each

Pros: DMOS, PWM, 8V-40V, Fully integrated, control and power stage, Overcurrent protection

Cons: Second price out of the three, 2A output

### **Chosen part is Option 2**

![motor driver](https://raw.githubusercontent.com/EGR314Team308/Team308.github.io/main/motor%20driver.JPG)

IFX9201SGAUMA1 is the one we use in class, it's the most familiar one although it is the most expensive out of the three, but it also has other functions. It has thermal shutdown, under-voltage lockout, overvoltage protection and overheat protection. Option 3 is also a good option but the voltage is too high.


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

![motor](https://raw.githubusercontent.com/EGR314Team308/Team308.github.io/main/Motor.JPG)


2790-HC385MG-301-ND Brushed Motor is both the cheapest and highest voltage and rotations per minute. It is large and shows all features like operating temperature. There are motors in Peralta Lab which could also be used.## Power Budget

# Power Budget

| All Major Components                             | Component Name                                               | Part Number      | Supply (V)<br>Voltage<br>Range | #              | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| ------------------------------------------------ | ------------------------------------------------------------ | ---------------- | ------------------------------ | -------------- | ----------------------------------- | ------------------------ | ---- |
| 12V DC motors                                    | GEARMOTOR 140 RPM 6-24V                                      | ROB-15277        | 6-24                           | 1              | 1300                                | 1300                     | mA   |
| Motor controller                                 | IC HALF BRIDGE DRIVER 6A 12DSO                               | IFX9201SGAUMA1   | 0-36                           | 1              | 13                                  | 13                       | mA   |
| Temperature sensors                              | SENSOR DIGITAL -40C-125C SOT23-5                             | TC74A4-3.3VCTTR  | 2.7-5.5                        | 2              | 0.35                                | 0.7                      | mA   |
| Humidity sensors                                 | 4.5% RH DIGITAL HUMIDITY SENSOR                              | HIH6030-021-001  | 2.3-5.5                        | 2              | 0.17                                | 1                        | mA   |
| Microcontroller                                  | IC MCU 8BIT 7KB FLASH 28SOIC                                 | PIC16F15354-E/SO | 2.3-5.5                        | 1              | 32                                  | 32                       | mA   |
| Limit switches                                   | SWITCH SNAP ACTION SPDT 3A 125V                              | SS0750303F050P1A | 0-125                          | 2              | 1                                   | 2                        | mA   |
| Red LED's                                        | LED RED CLEAR 1206 SMD                                       | LTST-C150KRKT    | 2-2.4                          | 2              | 25                                  | 50                       | mA   |
| Green LED's                                      | LED GREEN CLEAR 1206 SMD                                     | LTST-C150TKGT    | 2-2.4                          | 5              | 25                                  | 125                      | mA   |
| Schottky diode                                   | DIODE SCHOTTKY 40V 1A SOD123FL                               | DSS14U           | 0-40                           | 1              | 44                                  | 44                       | mA   |
| WIFI module                                      | ESP32 DEVKIT V1 WIRELESS WIFI                                | ESP32 DEVKIT V1  | 3-3.6                          | 1              | 500                                 | 500                      | mA   |
| +12V Power Rail                                  | Component Name                                               | Part Number      | Supply(V)<br>Voltage<br>Range  | #              | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| 12V DC motors                                    | GEARMOTOR 140 RPM 6-24V                                      | ROB-15277        | 6-24                           | 1              | 1300                                | 1300                     | mA   |
|                                                  |                                                              |                  |                                |                |                                     |                          |      |
|        ||||                                      | Subtotal                                                     | 1300             | mA                             |
|        ||||                                      | Safety Margin                                                | 25%              |                                |
|        ||||                                      | Total Current Required on +12V Rail                          | 1625             | mA                             |
|                                                  |                                                              |                  |                                |                |                                     |                          |      |
| Wall AC Adaptor-12V                              | AC/DC WALL MOUNT ADAPTER 12V 48W                             | L6R48-120        | 12                             | 1              | 4000                                | 4000                     | mA   |
|         ||||                                     | Total Remaining Current Available on +12V Rail               | 2375             | mA                             |
| +3.3V Power Rail                                 | Component Name                                               | Part Number      | Supply(V)<br>Voltage<br>Range  | #              | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| Motor controller                                 | IC HALF BRIDGE DRIVER 6A 12DSO                               | IFX9201SGAUMA1   | 0-36                           | 1              | 13                                  | 13                       | mA   |
| Temperature sensors                              | SENSOR DIGITAL -40C-125C SOT23-5                             | TC74A4-3.3VCTTR  | 2.7-5.5                        | 2              | 0.35                                | 0.7                      | mA   |
| Humidity sensors                                 | 4.5% RH DIGITAL HUMIDITY SENSOR                              | HIH6030-021-001  | 2.3-5.5                        | 2              | 1                                   | 2                        | mA   |
| Microcontroller                                  | IC MCU 8BIT 7KB FLASH 28SOIC                                 | PIC16F15354-E/SO | 2.3-5.5                        | 1              | 32                                  | 32                       | mA   |
| Limit switches                                   | SWITCH SNAP ACTION SPDT 3A 125V                              | SS0750303F050P1A | 0-125                          | 2              | 1                                   | 2                        | mA   |
| Red LED's                                        | LED RED CLEAR 1206 SMD                                       | LTST-C150KRKT    | 2-2.4                          | 2              | 25                                  | 50                       | mA   |
| Green LED's                                      | LED GREEN CLEAR 1206 SMD                                     | LTST-C150TGKT    | 2-2.4                          | 5              | 25                                  | 125                      | mA   |
| Schottky diode                                   | DIODE SCHOTTKY 40V 1A SOD123FL                               | DSS14U           | 0-40                           | 1              | 44                                  | 44                       | mA   |
| WIFI module                                      | ESP32 DEVKIT V1 WIRELESS WIFI                                | ESP32 DEVKIT V1  | 3-3.6                          | 1              | 500                                 | 500                      | mA   |
|                                                  |                                                              |                  |                                |                |                                     |                          |      |
|        ||||                                      | Subtotal                                                     | 768.7            | mA                             |
|         ||||                                     | Safety Margin                                                | 25%              |                                |
|         ||||                                     | Total Current Required on +5V Rail                           | 960.875          | mA                             |
|                                                  |                                                              |                  |                                |                |                                     |                          |      |
| Switching Power Regulator                        | IC REG BUCK 3.3V 1A D2PAK-5                                  | LM2575D2T-3.3R4G | 0-40                           | 1              | 1000                                | 1000                     | mA   |
|        |                          |      |       ||Total Remaining Current Available on +5V Rail                | 39.125           | mA                             |
|                                                  |
| External Power Source 1                          | Component Name                                               | Part Number      | Supply<br>Voltage<br>Range     | Output Voltage | Absolute<br>Maximum<br>Current (mA) | Total<br>Current<br>(mA) | Unit |
| Wall AC Adaptor-12V                              | AC/DC WALL MOUNT ADAPTER 12V 48W                             | L6R48-120        | 12                             | 1              | 4000                                | 4000                     | mA   |
|                                                  |                                                              |                  |                                |                |                                     |                          |      |
| Power Rails Connected to External Power Source 1 | Wall AC Adaptor-12V                                          | L6R48-120        | 12                             | 1              | 1625                                | 1625                     | mA   |
| IC REG BUCK 3.3V 1A D2PAK-5                      | LM7805                                                       | 0-40             | 1                              | 960.875        | 960.875                             | mA                       |
|        |                          |      |       || Total Remaining Current Available on External Power Source 1 | 1414.125         | mA                             |




  





