# 555-chaser-led-flower
This is my first PCB project for Hack Club's Stasis.

I used Kicad to create a schematic and route the PCB. I made a flower-shaped 555 LED Chaser board by following the Hack Club Stasis guide and adding my own customizations. 


3D view of the finished design on Kicad:
<img width="782" height="577" alt="Screenshot 2026-05-04 at 7 17 05 PM" src="https://github.com/user-attachments/assets/1611b436-83b9-4bb9-a554-78de18a3c6a5" />

BOM:
<table>
    <tr>
        <td>Reference</td>
        <td>Qty</td>
        <td>Value</td>
        <td>DNP</td>
        <td>Exclude from BOM</td>
        <td>Exclude from Board</td>
        <td>Footprint</td>
        <td>Datasheet</td>
    </tr>
    <tr>
        <td>C3</td>
        <td>1</td>
        <td>0.01 uF</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Capacitor_THT:C_Disc_D7.5mm_W2.5mm_P5.00mm</td>
        <td></td>
    </tr>
    <tr>
        <td>C4</td>
        <td>1</td>
        <td>1 uF</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Capacitor_THT:CP_Radial_D5.0mm_P2.00mm</td>
        <td></td>
    </tr>
    <tr>
        <td>D1,D2,D3,D4,D5,D6,D7,D8,D9,D10</td>
        <td>10</td>
        <td>LED</td>
        <td></td>
        <td></td>
        <td></td>
        <td>LED_THT:LED_D3.0mm</td>
        <td></td>
    </tr>
    <tr>
        <td>J1</td>
        <td>1</td>
        <td>Conn_01x02_Socket</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical</td>
        <td></td>
    </tr>
    <tr>
        <td>J2</td>
        <td>1</td>
        <td>Conn_01x01_Socket</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Connector_PinHeader_2.54mm:PinHeader_1x01_P2.54mm_Vertical</td>
        <td></td>
    </tr>
    <tr>
        <td>R1</td>
        <td>1</td>
        <td>1k</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal</td>
        <td></td>
    </tr>
    <tr>
        <td>R3</td>
        <td>1</td>
        <td>470</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal</td>
        <td></td>
    </tr>
    <tr>
        <td>RV1</td>
        <td>1</td>
        <td>R_Potentiometer</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Potentiometer_THT:Potentiometer_Vishay_T93YA_Vertical</td>
        <td></td>
    </tr>
    <tr>
        <td>U1</td>
        <td>1</td>
        <td>NE555P</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Package_DIP:DIP-8_W7.62mm</td>
        <td>http://www.ti.com/lit/ds/symlink/ne555.pdf</td>
    </tr>
    <tr>
        <td>U2</td>
        <td>1</td>
        <td>4017</td>
        <td></td>
        <td></td>
        <td></td>
        <td>custom_imports:N16</td>
        <td>http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf</td>
    </tr>
</table>
