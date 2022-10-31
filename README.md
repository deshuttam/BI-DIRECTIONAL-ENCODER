# DESIGN OF BI-DIRECTIONAL ENCODER

By Uttam Deshpande et. al.,

** Introduction
Multiple tools of the CNC machines are used in metal finishing jobs, and tool turret is the device to control the selection of those multiple tools. We have designed an cost effective and alternative encoder for tool turret. We designed the encoder using basic gates. K-Map technique is applied to design the logical expression. In next task full circuit was built on PCB board and checked for required truth table. Main task was to select the sensor and arrangement of sensors for detecting the position of shaft. After arrangement of sensors full circuit is checked for different input patterns.

*** Implementation
The Encoder is constructed with Digital logic gate IC’s and magnetic sensors with proper arrangement and after completion if circuit it is placed inside a turret for its application as shown in the fig.

![image](https://user-images.githubusercontent.com/107185323/199084549-d4a6f665-cbc3-40f5-add8-aadb2e40e061.png)

Sensor Arrangement:
For Detecting the position of shaft the sensor arrangement is done as shown in figure. Sensors(Reed switch) are placed 90 degrees apart from each other. Magnet is attached to disc. • When shaft rotates along with that disc rotates and whichever sensor is near to the magnet becomes on.


![image](https://user-images.githubusercontent.com/107185323/199084717-aecd20bf-5abf-4291-8262-c55e7a3eb3db.png)





