# kermel-counter
This kermel counter will count kermels for kermits while running on ker power.

## Requirements
- Must count kermels
- Must distinguish between kermits
- Must be able to send kermelcount to aggregator
- Must run on ker power

## Setup

### Hardware Components
- GPS module 
- 2G network module 
- Computing module (arduino or rPi)
- Physical input to specify kermit (button array?)

### Software Components
- GPS logger (C#) ✧
- 2G Communication programme (C#) ✆
- Aggregation Server (Javascript)
- GPS->kermel calculator (Python)
- Front-end for insights into usage (Javascript)

### Data flow
1. System is turned on when Ker is turned on
2. User is selected
3. GPS logger tracks ker movement
4. 2G module sends GPS data to Aggregation Server 
