# 555-chaser-led-flower
This is my first PCB project for Hack Club's Stasis.

I used Kicad to create a schematic and route the PCB. I made a flower-shaped 555 LED Chaser board by following the Hack Club Stasis guide and adding my own customizations. 


3D view of the finished design on Kicad:
<img width="782" height="577" alt="Screenshot 2026-05-04 at 7 17 05 PM" src="https://github.com/user-attachments/assets/1611b436-83b9-4bb9-a554-78de18a3c6a5" />


## Expected Behavior

When powered with a 5V supply, the NE555 timer operates in astable mode, 
generating a continuous clock signal. The speed of the clock is controlled 
by turning the potentiometer (RV1), which changes the speed of the chasing 
light effect. The CD4017 counter sequences through the 10 outputs (LEDs) to 
light one LED at a time.


## Bill of Materials (BOM)

| Reference | Qty | Value | Footprint | Datasheet | Purchase Link | Price | Notes |
|-----------|-----|-------|-----------|-----------|---------------|-------|-------|
| C3 | 1 | 0.01 uF | Capacitor_THT:C_Disc_D7.5mm_W2.5mm_P5.00mm | - | [DigiKey](https://www.digikey.com/en/products/detail/kemet/C320C103K3G5TA/6656406) | $0.56 | |
| C4 | 1 | 1 uF | Capacitor_THT:CP_Radial_D5.0mm_P2.00mm | - | [DigiKey](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/860020672005/5727088) | $0.10 | |
| D1-D10 | 10 | LED | LED_THT:LED_D3.0mm | - | [DigiKey](https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/151031VS06000/4489988) | $0.17 | |
| J1 | 1 | Conn_01x02_Socket | Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical | - | [DigiKey](https://www.digikey.com/en/products/detail/te-connectivity-amp-connectors/215297-2/2055922) | $0.95 | |
| J2 | 1 | Conn_01x01_Socket | Connector_PinHeader_2.54mm:PinHeader_1x01_P2.54mm_Vertical | - | [DigiKey](https://www.digikey.com/en/products/detail/adam-tech/RS1-02-G/9832044) | $0.20 | Break off 1 pin from strip |
| R1 | 1 | 1kΩ | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal | - | [DigiKey](https://www.digikey.com/en/products/detail/te-connectivity-passive-product/YR1B1K0CC/2390772) | $0.84 | |
| R3 | 1 | 470Ω | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | - | [DigiKey](https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF14JT470R/1741440) | $0.10 | |
| RV1 | 1 | 50kΩ | Potentiometer_THT:Potentiometer_Vishay_T93YA_Vertical | - | [DigiKey](https://www.digikey.com/en/products/detail/vishay-sfernice/T93YA503KT20/1587723) | $1.85 | |
| U1 | 1 | NE555P | Package_DIP:DIP-8_W7.62mm | [Datasheet](http://www.ti.com/lit/ds/symlink/ne555.pdf) | [DigiKey](https://www.digikey.com/en/products/detail/texas-instruments/NE555P/277057) | $0.51 | |
| U2 | 1 | CD4017BE | custom_imports:N16 | [Datasheet](http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf) | [DigiKey](https://www.digikey.com/en/products/detail/texas-instruments/CD4017BE/67253) | $1.27 | |

**Estimated Total: ~$6.55** (excluding shipping)
