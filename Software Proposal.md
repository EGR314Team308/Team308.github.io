# Software Proposal

The functionality of the software diagram to satisfy the users needs is to have the motor move a flap that opens up based on the temperature and humidity and closes when the temperature and humidity stablilizes. This also fulfills the product requirements as there are sensors detecting different weather conditions and changing based upon those conditions and interrupts. The teams design and decision making was to optimize the grow of plants in a greenhouse and to show temperature and humidity to the user.

## UML Diagram
![Team 308 Software_Proposal drawio](https://github.com/EGR314Team308/Team308.github.io/assets/156870072/b109a130-3144-4e48-9d28-1e2053f7633e)

Figure 16: Software Proposal

## Functions: 
### - Compare Data
Inputs: Data from internal and external sensors (uint_8)

Function: Determines if greenhouse is not in optimal state

Outputs: Change (Boolean)

### - Proccess Data
Inputs: Data from internal and external sensors (uint_8), Change (Boolean)

Function: Determines what type of change is needed for the greenhouse to reach optimal state

Outputs: Change parameters (FLoat)

### - Update Motors
Inputs: Change parameters (FLoat)

Function: Rotates motors based on change parameters

Outputs: (Void)
