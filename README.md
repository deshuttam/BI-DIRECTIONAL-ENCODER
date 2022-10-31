# DESIGN OF BI-DIRECTIONAL ENCODER

By Uttam Deshpande et. al.,

## Introduction
Multiple tools of the CNC machines are used in metal finishing jobs, and tool turret is the device to control the selection of those multiple tools. We have designed an cost effective and alternative encoder for tool turret. We designed the encoder using basic gates. K-Map technique is applied to design the logical expression. In next task full circuit was built on PCB board and checked for required truth table. Main task was to select the sensor and arrangement of sensors for detecting the position of shaft. After arrangement of sensors full circuit is checked for different input patterns.

![image](https://user-images.githubusercontent.com/107185323/199084549-d4a6f665-cbc3-40f5-add8-aadb2e40e061.png)


### Design
Based on sensing of sensors unique input pattern is generated.Input and output pattern is shown in below truth table.

![image](https://user-images.githubusercontent.com/107185323/199085148-1bcbeb51-d22d-4020-a657-7744fe0441c7.png)

![image](https://user-images.githubusercontent.com/107185323/199085228-daeb2999-0940-4eb9-bc6b-e1a3e9ea3067.png)

### Implementation
The Encoder is constructed with Digital logic gate IC’s and magnetic sensors with proper arrangement and after completion if circuit it is placed inside a turret for its application as shown in the fig.


### Sensor Arrangement
For Detecting the position of shaft the sensor arrangement is done as shown in figure. Sensors(Reed switch) are placed 90 degrees apart from each other. Magnet is attached to disc. When shaft rotates along with that disc rotates and whichever sensor is near to the magnet becomes on.

![image](https://user-images.githubusercontent.com/107185323/199084717-aecd20bf-5abf-4291-8262-c55e7a3eb3db.png)

### Complete Design
This is the complete circuit of Bidirectional encoder designed as per the logic. Here S1, S2, S3, and S4 are magnetic reed switch sensors which are arranged 
90 degrees apart from each other in a cylinder through which the position of the shaft can be read. The sensor output which is 24 volts is stepped down to 5 volts by voltage divider circuit. Output of voltage divider is given as input to the basic gate circuit designed as per the expressions obtained from K-Map. For every unique input pattern the basic gate circuit generates an unique output pattern of 6 bits as per the truth table (table). The 5 volts output from basic gate circuit is stepped up to 24 volts by optocoupler circuit. This pattern decides, which tool is to be used.


![image](https://user-images.githubusercontent.com/107185323/199085581-983350c5-202a-45a6-b9ad-10735f98175f.png)




