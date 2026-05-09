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
        <td>Footprint</td>
        <td>Datasheet</td>
        <td>Purchase Link</td>
        <td>Price</td>
        <td>Notes</td>
        
    </tr>
    <tr>
        <td>C3</td>
        <td>1</td>
        <td>0.01 uF</td>
        <td>Capacitor_THT:C_Disc_D7.5mm_W2.5mm_P5.00mm</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/kemet/C320C103K3G5TA/6656406</td>
        <td>$0.56</td>
        <td></td>
    </tr>
    <tr>
        <td>C4</td>
        <td>1</td>
        <td>1 uF</td>
        <td>Capacitor_THT:CP_Radial_D5.0mm_P2.00mm</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/860020672005/5727088</td>
        <td>$0.10</td>
        <td></td>
    </tr>
    <tr>
        <td>D1,D2,D3,D4,D5,D6,D7,D8,D9,D10</td>
        <td>10</td>
        <td>LED</td>
        <td>LED_THT:LED_D3.0mm</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/151031VS06000/4489988</td>
        <td>$0.17</td>
        <td>x10</td>
    </tr>
    <tr>
        <td>J1</td>
        <td>1</td>
        <td>Conn_01x02_Socket</td>
        <td>Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/te-connectivity-amp-connectors/215297-2/2055922</td>
        <td>$0.95</td>
        <td></td>
    </tr>
    <tr>
        <td>J2</td>
        <td>1</td>
        <td>Conn_01x01_Socket</td>
        <td>Connector_PinHeader_2.54mm:PinHeader_1x01_P2.54mm_Vertical</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/adam-tech/RS1-02-G/9832044</td>
        <td>$0.20</td>
        <td>Break off 1 pin from strip</td>
    </tr>
    <tr>
        <td>R1</td>
        <td>1</td>
        <td>1k</td>
        <td>Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/te-connectivity-passive-product/YR1B1K0CC/2390772</td>
        <td>$0.84</td>
        <td></td>
    </tr>
    <tr>
        <td>R3</td>
        <td>1</td>
        <td>470</td>
        <td>Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF14JT470R/1741440</td>
        <td>$0.10</td>
        <td></td>
    </tr>
    <tr>
        <td>RV1</td>
        <td>1</td>
        <td>50k</td>
        <td>Potentiometer_THT:Potentiometer_Vishay_T93YA_Vertical</td>
        <td></td>
        <td>https://www.digikey.com/en/products/detail/vishay-sfernice/T93YA503KT20/1587723</td>
        <td>$1.85</td>
        <td></td>
    </tr>
    <tr>
        <td>U1</td>
        <td>1</td>
        <td>NE555P</td>
        <td>Package_DIP:DIP-8_W7.62mm</td>
        <td>http://www.ti.com/lit/ds/symlink/ne555.pdf</td>
        <td>https://www.digikey.com/en/products/detail/texas-instruments/NE555P/277057</td>
        <td>$0.51</td>
        <td></td>
    </tr>
    <tr>
        <td>U2</td>
        <td>1</td>
        <td>4017</td>
        <td>custom_imports:N16</td>
        <td>http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf</td>
        <td>https://www.digikey.com/en/products/detail/texas-instruments/CD4017BE/67253</td>
        <td>$1.27</td>
        <td></td>
    </tr>
</table>
