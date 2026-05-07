# 555-chaser-led-flower
This is my first PCB project for Hack Club's Stasis.

This was my first time using Kicad to create a schematic and route a PCB. I made a flower-shaped 555 LED Chaser board by following the Hack Club Stasis guide and adding my own customizations. 


3D view of the finished design on Kicad:
<img width="782" height="577" alt="Screenshot 2026-05-04 at 7 17 05 PM" src="https://github.com/user-attachments/assets/1611b436-83b9-4bb9-a554-78de18a3c6a5" />

BOM:
[555-chaser-led-flower .csv](https://github.com/user-attachments/files/27491953/555-chaser-led-flower.csv)
"Reference","Qty","Value","DNP","Exclude from BOM","Exclude from Board","Footprint","Datasheet"
"C3","1","0.01 uF","","","","Capacitor_THT:C_Disc_D7.5mm_W2.5mm_P5.00mm",""
"C4","1","1 uF","","","","Capacitor_THT:CP_Radial_D5.0mm_P2.00mm",""
"D1,D2,D3,D4,D5,D6,D7,D8,D9,D10","10","LED","","","","LED_THT:LED_D3.0mm",""
"J1","1","Conn_01x02_Socket","","","","Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical",""
"J2","1","Conn_01x01_Socket","","","","Connector_PinHeader_2.54mm:PinHeader_1x01_P2.54mm_Vertical",""
"R1","1","1k","","","","Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal",""
"R3","1","470","","","","Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal",""
"RV1","1","R_Potentiometer","","","","Potentiometer_THT:Potentiometer_Vishay_T93YA_Vertical",""
"U1","1","NE555P","","","","Package_DIP:DIP-8_W7.62mm","http://www.ti.com/lit/ds/symlink/ne555.pdf"
"U2","1","4017","","","","custom_imports:N16","http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf"
