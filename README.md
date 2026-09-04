# DIY_pulse_oximeter
Hello! I made this project just as a way to make medical equipment with cheaper components(while retaining quality of the measurements)

# Description
The device uses MAX30102 to measure pulse and SpO2, and the microcontroller is Atmega328p(like the one on arduino nano). I am planning to use a 64x32 0.49" OLED screen to display info, and I also integrated a MCP73831 charging circuit for the battery(planning to use 250mAh tiny li-po), and CH340C for quickly writing firmware. It also used DW01A for over-discharge protection, with FS8205A responsible for cutting off power. And finally, AP2112K-3.3TRG1 supplies 3.3V stable current from the battery.

About assembling the PCB, I am going to order from Aivon(cuz JLCPCB doesn't offer PCBA in my country)

# Schematic
<img width="1141" height="788" alt="2026-09-02_22-06-37" src="https://github.com/user-attachments/assets/667af7b6-1908-4232-9215-c6c142b2fbf6" />


# PCB
This is the current layout(in 3D):

<img width="615" height="285" alt="2026-09-04_22-53-39" src="https://github.com/user-attachments/assets/a550907d-b60f-4943-b519-95813fd49cdf" />
<img width="606" height="289" alt="2026-09-04_22-53-52" src="https://github.com/user-attachments/assets/e4866ce1-fdce-402e-a688-44be6c4e3c7b" />

# BOM
|Name                                                                  |Price                   |
|----------------------------------------------------------------------|------------------------|
|Bare PCBs 5pcs                                                        |5$                      |
|PCB Assembly for 5pcs                                                 |36$                     |
|Shipping(Fedex, the only cheap option)                                |0$(First order discount)|
|0.49" 64x32 OLED screen(https://ali.click/3mfuk1f, including shipping)|2.68$                   |
|Total                                                                 |43.68$                  |
