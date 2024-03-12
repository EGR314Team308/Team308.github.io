---
title: Home
---

# Team 308: Home

## Mobile Weather Station

Team Members: Gabriel Sandys, Shawn Meris, Hengjui Chang, Matt Olpin

3/11/2024

Arizona State University, EGR 314, Spring, 2024, Dr. Nichols

## Table of Contents

+ [Team Organization](https://egr314team308.github.io/Team308.github.io/#team-organization) <br>
+ [User Needs, Benchmarking, and Requirements](https://egr314team308.github.io/Team308.github.io/#user-needs-benchmarking-and-requirements) <br>
+ [Design Ideation](https://egr314team308.github.io/Team308.github.io/#design-ideation) <br>
+ [Presentation 1](https://egr314team308.github.io/Team308.github.io/#presentation-1) <br>
+ [Selected Design](https://egr314team308.github.io/Team308.github.io/#selected-design) <br>
+ [Block Diagram](https://egr314team308.github.io/Team308.github.io/#block-diagram) <br>
+ [Component Selection](https://egr314team308.github.io/Team308.github.io/#component-selection) <br>
+ [Microcontroller Selection](https://egr314team308.github.io/Team308.github.io/#microcontroller-selection) <br>
+ [Hardware Proposal](https://egr314team308.github.io/Team308.github.io/#hardware-proposal) <br>
+ [Software Proposal](https://egr314team308.github.io/Team308.github.io/#software-proposal) <br>

## Introduction

Global warming has been on the rise for the past few years. There are many environmentalists concerned about where the world is going and where it will be in the future. There are many different products out there on the market that can measure temperature, humidity, atmospheric pressure and wind speed. The team would like to create more reliable and efficient products to track the environment.

## Team Organization

Team 308 was made to create a weather station that measures different environmental conditions. The team first talked about the team charter and team goals to see how each member wanted the team to both perform in the project and what the project should entail. The team goals listed below were created in a team meeting where every member had input into the teams ultimate goals. 

### Team Goals

Our project will provide consistent, reliable, and accurate sensor input. <br>
The project will have a real-life application that would have a significant impact for users. <br>
Further our passion and knowledge in working with microcontrollers. <br>
Motorized components in the project will work consistently to produce useful results. <br>
The project will be able to fulfill all safety and project requirements. <br>

### Product Mission Statement

The product mission statement listed below was talked about during a team meeting that satisfies both the project that the team wants to build and fulfills the project requirements.

The product will be reliable and work accurately to determine environmental conditions and use that data to determine and execute actions that are impactful for our project.

Below is the link to the Appendix A: Team Organization <br>

[Link to Appendix A: Team Organization](Appendix A Team Organization.md) <br>

## User Needs, Benchmarking, and Requirements

The team started the user needs process by finding and writing down 5 different products that relate to a mobile weather station. The purpose of this was to see the good and bad reviews that were on these products in order to either implement or provide aspects that the device did not. This allows the team to see the user needs in the available market. Below in the link are the 5 products or Voice of the Customer Benchmarking that the team chose.

### Organize

The team organized the 100 user needs below based on the latent and explicit to see the main problems with current products. This allowed the teams to combine and split the user needs into 5 different catagories. The 5 categories are Sensors, Usability/Software, Safety/Maintenance, Information/Hardware and Power. The team assigned weight to important user needs based on team discussion this is shown by the ranking of 1 star, 2 star or 3 star ranking.

![image](https://github.com/EGR314Team308/Team308.github.io/assets/157086096/d057af81-daf7-46ec-8098-991f4a8fe516)

Figure 1: 100 User Needs Jamboard

![SensorS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/7ed352bd-7ddd-4663-8783-e719bf49d40c)
Figure 2: Sensors Jamboard

![UseS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/38159989-68a0-45eb-9d27-aed1d7bf1b9c)
Figure 3: Usability/Software Jamboard

![SafeS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/50b7bb8d-cb4f-4ccf-97fa-c50198d12d7c)
Figure 4: Safety/Maintenance Jamboard

![InfoS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/f407e896-4518-45e7-a39c-7e42977d22e5)
Figure 5: Information/Hardware Jamboard

![PowerS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/9521df59-0865-4408-9f0f-95a5ad3fce73)
Figure 6: Power Jamboard

### Develop Requirements

The team converted the user needs into specifications by deciding which user needs are the most important and how the team can provide the necesities that users need. The design of the product by the team will incorporate the aspects of both the user needs and the product requirements.
Below is the link to the User Needs, Benchmarking, and Requirements page.

### Aspects

#### 1. Hardware / Product Design
- The device should have high-quality materials.
- The device should be small and compact for the user to move around with ease.
- The sensors (humidity, light, temperature, etc.) within the device should be easy to use and work.
- The device should be weather resistant.
- The device should have a battery that is both sufficient and sustainable.
- The device should be able to have good data storage.
- The device should be durable and usable for at least one person.

#### 2. Software / Functionality
- The device should be able to monitor data.
- The device should have a data processing algorithm.
- The device should control an actuator based on data.
- The device should provide feedback to the user.
- The device should be able to handle being constantly used.

#### 3. Interactivity & User Experience
- The device should allow users to download/view data.
- The device should guide users through the product.
- The device should allow users to activate different inputs.

#### 4. Customization
- The device should allow users to monitor specific patterns.
- The device should allow users to customize parts of its appearance.
- The device should be able to be used by people of all ages.

#### 5. Manufacturing
- The device should use surface-mounted components.
- The device can have 3D printed housing.
- The device can use metal for structural integrity.
- The device should be designed using ECAD software (Cadence).
- The device should be built so that repairs, modifications, and replacements can be made without rebuilding the device.

#### 6. Safety
- The device should have no exposed wiring.
- All actuators should be clearly labeled and be in a safe operating environment.
- The device should have clear instructions for safe use.
- The device should not have sharp or rough edges.
- Charging the battery should be able to be done without the risk of electric shock.

[Link to User Needs, Benchmarking, and Requirements](User Needs, Benchmarking, and Requirements.md) <br>

## Design Ideation

The team cam together during class and outside of class during the weekly meeting to generate ideas first on a list that would later be transfered over to a Jamboard. Each member wrote down the ideas they initially had about the project and then the group decided to talk through the rest to reach 100 ideas. Shawn and Matt were the primary members that wrote down the ideas and the group as a whole talked about and shared ideas. The brainstorming that worked was just adding ideas the group all had and talking through ideas. There were no brainstorming types that did not work because the group accepted all ideas and all the brainstorming technics used worked. Below is the Jamboard made by the team.

### Generate Ideas

![Ideas](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/5c7a3ca1-7c59-413b-8403-54374099224a)
Figure 7: 100 Ideas

### Sort, Rank, and Group Design Concepts

The process for organizing and ranking ideas was seeing if there were any patterns between the 100 ideas and separating them in 3 different groups. The three groups were separated into Locations, Environment Control and Use Cases. The team ranked the ideas from 1 star to 3 stars based on the user needs above and if they cover the project and product requirements. The three groups are shown below along with the ranks of each one on a Jamboard.

![LocS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/c0e80970-fd57-44a6-a57f-758874c510bb)
Figure 8: Locations Jamboard

![EvS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/ad9b3e16-2b7d-4a38-ab31-2a93f41d54ea)
Figure 9: Environment Control Jamboard

![UseCS](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/d04d554e-668d-4da3-9fcb-4c047128d505)
Figure 10: Use Cases Jamboard

### Create three product concept sketches

Gabriel created the Greenhouse Regulation System in Blender, Roy created the Mars Weather Station in Solidworks and Matt made the Wind Farm Weather Station. Below are Team 308s product concept sketches.

#### Greenhouse Regulation System
The goal of the Greenhouse Regulation System would be to effectively cultivate the ideal environment for growing plants within the greenhouse. The current design would feature the ability to track internal and external data and identify what needs to be done to adjust the current environment within the greenhouse. This could include opening and closing greenhouse doors, dispersing water, etc. Solar panels would be placed directly above to help with power consumption, and a screen would be placed on the front to monitor data.

![Green](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/0ff56bb9-99ef-44c9-9b0d-c12f9e677db1)

Figure 11: Greenhouse Regulation System

#### Mars Weather Station

The Mars Weather Station is a robotic vehicle designed for exploring the surface and monitoring atmospheric conditions. The rover is equipped with sensors to study and report on weather patterns, temperature variations, atmospheric pressure, humidity, and wind speed on Mars.

![Mars](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/da56910c-823f-4eec-80ae-6116fd7e4e59)

Figure 12: Mars Weather Station

#### Wind Farm Weather Station

Turbines on wind farms need to be slowed and shut down when there is too much wind, icy conditions, or if there are birds or other animals flying through the area.  

The weather station design below will detect these conditions and control the turbine by adjusting the direction of the turbine using a yaw drive to slow the turbine and braking and slowing by applying pressure to the shaft with a brake pin and stopping by inserting the pin into the axle shaft if lockout is needed.

![Wind](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/0b655a87-bd64-420e-8cf7-cdd9fc9b08e8)

Figure 13: Wind Farm Weather Station

[Link to Design Ideation](Design Ideation.md) <br>

## Presentation 1

<iframe width="560" height="315" src="https://www.youtube.com/embed/JfoxrEyEsB8?si=He0aE4M31bQOCldq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

[Link to Presentation 1](Presentation 1.md) <br>

## Selected Design

The team decided to pick the Greenhouse Regulation System because it looked the most practical and fun to make. The team did combine good ideas from the design ideation to make the final selected design with keeping in mind location, environment control and use cases. The team believes they selected the best design for the users needs. The ultimate decision was made by a vote of which design to pick where the vote was unanimous for the Greenhouse Regulation System. The selected design deviates slightly as there will not be an LCD screen on the front to track the temperature and humidity. There will be instead two PCB boards back to back displaying both the temperature inside and outside the greenhouse.

![Green](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/0ff56bb9-99ef-44c9-9b0d-c12f9e677db1)

Figure 14: Greenhouse Regulation System

[Link to Selected Design](Selected Design.md) <br>

## Block Diagram

[Link to Block Diagram](Block Diagram.md) <br>

## Component Selection

The decision making process for creating this section was to find components that would work for the project and lay them out in a document to see which is the best fit for the project. The selected components meet the product requirements with having 2 serial sensors in temperature and humidity, an actuator which is the motor driver and motor along with a microcontroller, power supply and switching power regulator.

The power budget was used to estimate the power needs of the greenhouse to see and make sure the greenhouse can be used for a sustainable amount of time. The power budget allows the team to be within the safety margin and run the greenhouse for at least an hour. The power budget is below in the appendix link at the bottom of the component selection.

### Humidity Sensor

| Solution                                                                                | Pros                                                           | Cons                                                       |
|-----------------------------------------------------------------------------------------|----------------------------------------------------------------|------------------------------------------------------------|
| Option 4 296-HDC3021DEHRTR-ND Sensor Humidity 100RH SMD $5.61/each Link to product    | I2C Very Low power SM 0~100% Humidity range +-0.5% RH Accuracy | 4 sec response time More than double the price of option 1 |

Choice: Option 4: 296-HDC3021DEHRTR-ND
Sensor Humidity 100RH SMD

Rationale: Option 4 provides the best price to performance, with a higher accuracy than all of the other selected options. Although it is more expensive than option 1, when compared to similarly priced models it has much greater performance with a very low response time. It also meets the surface mount and I2C requirements.

### Temperature Sensor

| Solution                                                                     | Pros                                                                      | Cons                                                                                       |
|------------------------------------------------------------------------------|---------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| # Option 1 TC74A4-3.3VCTCT-ND Temperature Sensor $1.15/each Link to product  | It is already in Peralta Lab Inexpensive The range of temperature is good | It is very small which is hard for soldering The datasheet does not have a circuit with it |

Choice: Option 1: TC74A4-3.3VCTCT-ND Temperature Sensor

Rationale: Option 1 is possibly the best because of the capabilities and amount available. It has all the features that are needed to measure temperature in a greenhouse. There are also many in stock along with there many in the Peralta Lab. It is also inexpensive with the only main problem being it is very small.

### Switching Power Regulator

| Solution                                                                                                           | Pros                                                                  | Cons                                      |
|--------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|-------------------------------------------|
| # Option 2 AP64350SP-13 Buck Switching Regulator IC Positive Adjustable Output 3.5A  $1.58/each Link to product    | High efficiency 8 pin 3.8 to 40 V input UVLO OVP Price Easy to solder | 3.5 A output Adjustable .8 to 39 V output |

Choice: Option 2: AP64350SP-1 Buck Switching Regulator IC Positive Adjustable Output 3.5A 

Rationale:  Option 2 is the best choice as it has over voltage and under voltage protection, it has higher output current, and it has a low cost.  It is adjustable which makes it more versatile if possibly more difficult to configure. If needed a 3.3V output version could be found to make configuration easier.  AP63203WU-7 is an example with 2A output.

### Power Supply

| Solution                                                                | Pros                               | Cons               |
|-------------------------------------------------------------------------|------------------------------------|--------------------|
| # Option 1 AC/DC WALL MOUNT ADAPTER 12V 48W $18.19/each Link to product | 12V 4A Price No recharging needed. | Requires AC outlet |

Choice: Option 1:   AC/DC WALL MOUNT ADAPTER 12V 48W

Rationale:  Option 1 is the best choice since it provides the needed power without having to be recharged.  Our application is not mobile, so providing power from an outlet makes sense.  It is also the most cost effective.

### Motor Driver

| Solution                                                                                     | Pros                                                           | Cons         |
|----------------------------------------------------------------------------------------------|----------------------------------------------------------------|--------------|
| # Option 2 MP6513LGJ-Z Bipolar Motor Driver Power Mosfet TSOT-23-6 $0.9/each Link to product | 2.5V-5.5V PWM Cheapest Thermal shutdown Overcurrent protection | 600mA output |

Choice: Option 2 MP6513LGJ-Z, Bipolar Motor Driver Power Mosfet TSOT-23-6

Rationale: It is the cheapest option out of the three, but it also has other functions. It has thermal shutdown, undervoltage lockout, overvoltage protection and overheat protection. Option 3 is also a good option but the voltage is too high.

### Motor

| Solution                                                                 | Pros                                      | Cons                                         |
|--------------------------------------------------------------------------|-------------------------------------------|----------------------------------------------|
| # Option 1 2790-HC385MG-301-ND Brushed Motor $6.45/each Link to product  | 24 V 18000 RPM Wide operating temperature | Small and compact Datasheet is not available |

Choice: Option 1 2790-HC385MG-301-ND Brushed Motor

Rationale: Option 1 is both the cheapest and highest voltage and rotations per minute. It is large and shows all features like operating temperature. There are motors in Peralta Lab which could also be used.

[Link to Component Selection](Component Selection.md) <br>

## Microcontroller Selection

[Link to Microcontroller Selection](Microcontroller Selection.md) <br>

## Hardware Proposal

The functionality of the schematic satisfies the users needs and product requirements as it reads both temperature and humidity for the user to see the difference between inside the greenhouse and outside for optimal weather conditions. The motor will be connected to a door which will open and close depending on the temperature and humidity. The motor will open to let in air for the greehouse to return back to the desired conditions. All the subsystems will have 2 of each for the inside and outside. The microcontroller will control all the subsystems which is programmed by the snap programmer connection. The switching power regulator helps to transfer it from 12 V to 3.3 V which will run throughout the entire system. The ESP32 WiFi Module helps to transmit WiFi to and from the microcontroller. There will also be limit switches all throughout the system. The team's bill of materials is below in the appendix.

![Hardware Proposal](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/c069c3e0-4f03-43ae-8449-d32ab3c549e0)
Figure 15: Hardware Proposal

[Link to Hardware Proposal](Hardware Proposal.md) <br>

## Software Proposal

[Link to Software Proposal](Software Proposal.md) <br>
