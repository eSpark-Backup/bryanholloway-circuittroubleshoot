# Circuit Troubleshooting and Consultancy
#### Client Name: Bryan Holloway

## Project Requirements
The primary task is troubleshooting the existing circuit and share ideas for fixing. The complete details are shared below and schematic is pushed in docs folder:

The client has a PCB design that uses an STM32 MCU. There is a separate PCB with two Opto electrical reflective sensors. The old design used BPR-301 sensor. In the new variant of the design, the sensor was replaced with OPB733TR that seemed identical. The client was able to get U1 to work on the new PCB, but U2 just does not seem to work.

### Current tests
1. Tried the old sensor and confirmed the connector on the PCB is working
2. Checked wiring end-to-end from edge connector to the pins on the new sensors.
 
Everything is wired identically. There are no shorts or connection issues and everything has been triple checked. The only possibility of problem is that wiring 2 sensors together with the OPB733TR is different then how it was for the BPR-301 for some reason.

### Wiring Information
#### Picture 01
![image](https://github.com/user-attachments/assets/5fcfd90d-7273-401a-8703-f396b23aae66)

#### Picture 02
![image](https://github.com/user-attachments/assets/ef255618-11e1-4cb2-b319-b8acc55d9bf0)

#### Picture 03
![image](https://github.com/user-attachments/assets/84369127-a7bf-4eb8-9192-ee36476dad90)

#### Picture 04
![image](https://github.com/user-attachments/assets/2bcdc7cf-0747-4ab5-932c-5297c1a7c966)


