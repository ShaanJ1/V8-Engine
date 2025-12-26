# V8 Engine
A working 3D printed V8 engine powered by a DC motor with controllable speeds up to 1000RPM.

### Note:
Make sure to lubricate all moving parts to prevent damage to your 3D print. This project was made assuming that this will be printed in ABS or another heat-resistant material. If you are using a material like PLA, note that the friction at high speeds may cause the print to melt or warp itself.

### Showcase
*Coming soon...*

# Bill of Materials (BOM)

| **Item Name**                | **URL**                                                                                                                   | **Price** | **Quantity** | **Use**                         |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------- | --------: | -----------: | ------------------------------- |
| 12V Battery                  | [Amazon](https://a.co/d/iR5ZKYJ)                                                                                          |    $33.38 |            1 | Power Source                    |
| DC Motor                     | [AliExpress](https://www.aliexpress.com/item/1005008221484428.html)                                                       |    $17.89 |            1 | Spinning Engine                 |
| Silicone Grease              | [AliExpress](https://www.aliexpress.com/item/1005008374157659.html)                                                       |     $3.65 |            1 | Lubricant for moving parts      |
| Heat Shrink                  | [AliExpress](https://www.aliexpress.com/item/1005008146302901.html)                                                       |     $3.62 |            1 | For exposed soldered wires      |
| 3D Print (Shipping)          | -                                                                                                                         |    $10.00 |            1 | 3D Print Shipping Costs         |
| PCB                          | [JLCPCB](https://jlcpcb.com/)                                                                                             |     $4.78 |            1 | Main Controller                 |
| M3 10mm Set Screws           | [AliExpress](https://www.aliexpress.com/item/4001081433504.html)                                                          |     $2.79 |            1 | Main Assembly + Flywheel Screws |
| M4 6mm Screws                | [AliExpress](https://www.aliexpress.com/item/1005001785690381.html)                                                       |     $2.76 |            1 | Motor Mounting Screws           |
| M4 16mm Set Screws           | [AliExpress](https://www.aliexpress.com/item/1005008512534705.html)                                                       |     $4.69 |            1 | Connecting Rod Screws           |
| M8 25mm Screws               | [AliExpress](https://www.aliexpress.com/item/1005006090579821.html)                                                       |     $4.07 |            1 | Output Gear Holder              |
| 5x8 Shaft Coupler            | [AliExpress](https://www.aliexpress.com/item/1005006305848755.html)                                                       |     $6.91 |            1 | Motor to Gear Coupler           |
| 608ZZ Bearing                | [AliExpress](https://www.aliexpress.com/item/1005010525419357.html)                                                       |     $4.35 |            1 | Spins output gear               |
| 18 AWG Wires (2 ft)          | [DigiKey](https://www.digikey.ca/en/products/detail/te-connectivity-aerospace-defense-and-marine/FLHTC0311-18-0/6061732)  |     $4.00 |         2 ft | Wiring                          |
| 100µF Electrolytic Capacitor | [DigiKey](https://www.digikey.ca/en/products/detail/w%C3%BCrth-elektronik/860020473008/5727062)                           |     $0.19 |            1 | Decoupling                      |
| 0.1µF 0805 Ceramic Capacitor | [DigiKey](https://www.digikey.ca/en/products/detail/kemet/C0805F104K1RACAUTO/26735352)                                    |     $0.33 |            1 | Decoupling                      |
| MBR2045CT                    | [DigiKey](https://www.digikey.ca/en/products/detail/smc-diode-solutions/MBR2045CT/6022134)                                |     $1.97 |            1 | Motor Flywheeling Diode         |
| SS14                         | [DigiKey](https://www.digikey.ca/en/products/detail/taiwan-semiconductor-corporation/SS14/7369347)                        |     $0.68 |            2 | Diodes                          |
| Green LED                    | [DigiKey](https://www.digikey.ca/en/products/detail/w-rth-elektronik/151051VS04000/4490015)                               |     $0.38 |            1 | ON LED                          |
| 1206 Fuse 7A 32V             | [DigiKey](https://www.digikey.ca/en/products/detail/schurter-inc/3413-0326-22/2644167)                                    |     $2.34 |            3 | Circuit Protection              |
| 1x2 Terminal Block           | [DigiKey](https://www.digikey.ca/en/products/detail/te-connectivity-amp-connectors/282837-2/2187973)                      |     $2.20 |            2 | Power Input, Motor Power        |
| IRFZ44                       | [DigiKey](https://www.digikey.ca/en/products/detail/infineon-technologies/IRFZ44NPBF/811772)                              |     $2.10 |            1 | N Channel MOSFET                |
| MMBT2222A                    | [DigiKey](https://www.digikey.ca/en/products/detail/shenzhen-slkormicro-semicon-co-ltd/MMBT2222A/25880370)                |     $0.30 |            2 | NPN transistor                  |
| IRF9540N                     | [DigiKey](https://www.digikey.ca/en/products/detail/infineon-technologies/IRF9540NPBF/812088)                             |     $2.89 |            1 | P Channel MOSFET                |
| 1K 0402 Resistor             | [DigiKey](https://www.digikey.ca/en/products/detail/panasonic-electronic-components/ERJ-2RKF1001X/79729)                  |     $0.44 |           10 | Resistors                       |
| 1K 0603 Resistor             | [DigiKey](https://www.digikey.ca/en/products/detail/stackpole-electronics-inc/RMCF0603FT1K00/1761077)                     |     $0.11 |           10 | Resistors                       |
| 4.7K 0402 Resistor           | [DigiKey](https://www.digikey.ca/en/products/detail/yageo/RC0402FR-074K7L/2827563)                                        |     $0.16 |           10 | LED Resistors                   |
| 10K 0402 Resistor            | [DigiKey](https://www.digikey.ca/en/products/detail/yageo/RC0402JR-0710KL/726418)                                         |     $0.10 |           10 | Resistors                       |
| 10K 0603 Resistor            | [DigiKey](https://www.digikey.ca/en/products/detail/yageo/RC0603FR-0710KL/726880)                                         |     $0.10 |           10 | Resistors                       |
| NE555P                       | [DigiKey](https://www.digikey.ca/en/products/detail/texas-instruments/NE555P/277057)                                      |     $0.81 |            1 | 555 Timer for PWM               |
| AOD4185                      | [DigiKey](https://www.digikey.ca/en/products/detail/alpha-omega-semiconductor-inc/AOD4185/2353887)                        |     $1.82 |            1 | Circuit Protection              |
| 0805 LED                     | [DigiKey](https://www.digikey.ca/en/products/detail/w%C3%BCrth-elektronik/150080GS75000/4489915)                          |     $0.30 |            1 | Onboard LED                     |
| 10K Potentiometer            | [DigiKey](https://www.digikey.ca/en/products/detail/bourns-inc/PDB181-K425K-103B/3820304)                          |     $1.94 |            1 | Speed Adjuster                     |
| PushButton                   | [DigiKey](https://www.digikey.ca/en/products/detail/same-sky-formerly-cui-devices-/TS02-66-55-BK-160-LCR-D/15634374)                          |     $0.32 |            1 | Start/Stop Buttons                     |


**Total (CAD):** $123.18

**Total (USD):** $90.08

### Images
Schematic
<img width="2107" height="1206" alt="image" src="https://github.com/user-attachments/assets/e98dd742-79cd-4182-885e-2e9d86933b96" />

PCB
<img width="1500" height="1201" alt="image" src="https://github.com/user-attachments/assets/7a629bf2-5dbc-4d0b-abe5-f0e4bd81cc6a" />

Main Assembly
<img width="1314" height="941" alt="image" src="https://github.com/user-attachments/assets/c42e38e0-44ee-457e-b465-f9be519409f8" />
<img width="980" height="628" alt="image" src="https://github.com/user-attachments/assets/2c69d82e-7112-4388-83aa-768e9fc16ac8" />
<img width="894" height="559" alt="image" src="https://github.com/user-attachments/assets/7d61513d-e72d-472a-a1db-2fa70523e607" />
<img width="993" height="862" alt="image" src="https://github.com/user-attachments/assets/6ba71128-bd8d-4e46-899e-72b0b8f8cfb3" />
