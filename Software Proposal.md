# Software Proposal

## UML Diagram
![Team 308 Software_Proposal drawio](https://github.com/EGR314Team308/Team308.github.io/assets/157086096/88f05964-5251-4b15-bc62-fe221542b1b4)

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
