# DIY_pulse_oximeter
Hello! I made this project just as a way to make medical equipment with cheaper components(while retaining quality of the measurements)

# Description
The device uses MAX30102 to measure pulse and SpO2, and the microcontroller is Atmega328p(like the one on arduino nano). I am planning to use a 64x32 0.49" OLED screen to display info, and I also integrated a MCP73831 charging circuit for the battery(planning to use 250mAh tiny li-po), and CH340C for quickly writing firmware. It also used DW01A for over-discharge protection, with FS8205A responsible for cutting off power. And finally, AP2112K-3.3TRG1 supplies 3.3V stable current from the battery.

# Schematic
<img width="1141" height="788" alt="2026-09-02_22-06-37" src="https://github.com/user-attachments/assets/667af7b6-1908-4232-9215-c6c142b2fbf6" />


# PCB
This is the current layout(in 3D):

<img width="643" height="352" alt="2026-09-02_21-58-32" src="https://github.com/user-attachments/assets/29d8b389-49c1-4e59-b5f7-2ed58197821d" />
<img width="615" height="338" alt="2026-09-01_19-17-58" src="https://github.com/user-attachments/assets/0b7b6dd4-0d0d-4683-91b3-22244a230b2f" />

# BOM
|Name                                  |Price                   |
|--------------------------------------|------------------------|
|Bare PCBs 5pcs                        |5$                      |
|PCB Assembly for 5pcs                 |36$                     |
|Shipping(Fedex, the only cheap option)|0$(First order discount)|
|Total                                 |41$                     |
