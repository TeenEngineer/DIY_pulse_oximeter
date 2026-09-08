# DIY_pulse_oximeter
Hello! I made this project just as a way to make medical equipment with cheaper components(while retaining quality of the measurements)

# Description
The device uses MAX30102 to measure pulse and SpO2, and the microcontroller is Atmega328p(like the one on arduino nano). I am planning to use a 64x32 0.49" OLED screen to display info, and I also integrated a MCP73831 charging circuit for the battery(planning to use 250mAh tiny li-po), and CH340C for quickly writing firmware. It also used DW01A for over-discharge protection, with FS8205A responsible for cutting off power. And finally, AP2112K-3.3TRG1 supplies 3.3V stable current from the battery.

About assembling the PCB, I am going to order from Aivon(cuz JLCPCB doesn't offer PCBA in my country)

# Schematic, PCB
You can view the schematic and PCB layout **[here](https://kicanvas.org/?repo=https://github.com/TeenEngineer/DIY_pulse_oximeter)**
**OR**
Here is a schematic
<img width="1146" height="792" alt="2026-09-06_19-49-08" src="https://github.com/user-attachments/assets/b32bd15c-fe72-4bb7-82fc-7e517e7aac4a" />

# PCB
This is the current layout(in 3D):

<img width="610" height="285" alt="2026-09-06_19-50-29" src="https://github.com/user-attachments/assets/a0161581-898f-4a24-b154-9a96d93d44e1" />
<img width="615" height="285" alt="2026-09-06_19-50-55" src="https://github.com/user-attachments/assets/e320389b-9c57-4734-9f95-51a8844683de" />

# BOM
|Name                                                                  |Price                   |
|----------------------------------------------------------------------|------------------------|
|Bare PCBs 5pcs                                                        |5$                      |
|PCB Assembly for 5pcs                                                 |36$                     |
|Shipping(Fedex, the only cheap option)                                |0$(First order discount)|
|0.49" 64x32 OLED screen(https://ali.click/3mfuk1f, including shipping)|2.68$                   |
|Total                                                                 |44$(in case price of oled goes up                |
