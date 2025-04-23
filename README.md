# Circuit Troubleshooting and Consultancy
#### Client Name: Bryan Holloway

## Project Requirements
The primary task is troubleshooting the existing circuit and share ideas for fixing. The complete details are shared below:

The client has a PCB design that uses an STM32 MCU. There is a separate PCB with two Opto electrical reflective sensors. The old design used BPR-301 sensor. In the new variant of the design, the sensor was replaced with OPB733TR that seemed identical. The client was able to get U1 to work on the new PCB, but U2 just does not seem to work.

### Current tests
1. Tried the old sensor and confirmed the connector on the PCB is working
2. Checked wiring end-to-end from edge connector to the pins on the new sensors.
 
Everything is wired identically. There are no shorts or connection issues and everything has been triple checked. The only possibility of problem is that wiring 2 sensors together with the OPB733TR is different then how it was for the BPR-301 for some reason.
