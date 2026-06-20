# DevBoard

DevBoard, It is an STM32 based development board, It is an high power STM32 development board! 


<img width="420" height="595" alt="ZINE" src="https://github.com/user-attachments/assets/d72fe2c5-3e3e-4f53-8e38-7c262f3a5c7e" />


## What is this project?
DevBoard is an development board based on the STM32F722RET6 which is a high power performance chip from ST electronics.



## How do we use DevBoard?
- Connect the USB-C and flash your own firmware via any IDE.
- OR u can use ST-LINK but u have to SOLDER the stlink wires.



## Reason for building
Well in Nepal looking at my case i needed a powerful microcontroller that could be used with Drone softwares such as PX4, Betaflight, Inav.
For autonomus control. 
And the ones i find in Nepal the STM32 are te Bluepill and these are very slow and un reliable and isnt really supported by most softwares!.




## CAD
<img width="1920" height="692" alt="DEv v1" src="https://github.com/user-attachments/assets/d7c45005-959e-4da4-bd6b-89974e0964e0" />


## Circuit Diagram
<img width="795" height="562" alt="image" src="https://github.com/user-attachments/assets/47461171-756a-44b7-a8a8-b73be0b9367f" />


## PCB
<img width="770" height="433" alt="Screenshot 2026-06-20 232807" src="https://github.com/user-attachments/assets/a67770fa-4f64-4d26-b714-ae7b515e6145" />
<img width="845" height="417" alt="Screenshot 2026-06-20 232811" src="https://github.com/user-attachments/assets/f40f5a4e-5bf4-4b62-9722-5a54e6b1296d" />
<img width="341" height="152" alt="image" src="https://github.com/user-attachments/assets/bca2120b-6288-44fb-af27-16a577621edc" />


## PCB 3D
<img width="816" height="680" alt="Screenshot 2026-06-20 234739" src="https://github.com/user-attachments/assets/9b35dae6-9bc8-47e7-b4e6-b3b8b057d63e" />
<img width="1115" height="571" alt="Screenshot 2026-06-20 232908" src="https://github.com/user-attachments/assets/f4dad3f3-4cd4-4870-b96f-43ace0aa3bd0" />
<img width="302" height="562" alt="Screenshot 2026-06-20 222140" src="https://github.com/user-attachments/assets/b0cb1c2e-7c3b-49eb-a0e9-4d1cb65294aa" />
<img width="1215" height="626" alt="Screenshot 2026-06-20 222225" src="https://github.com/user-attachments/assets/748808f2-f255-4ae9-bdab-a818d959a152" />
<img width="1920" height="692" alt="DEv v1" src="https://github.com/user-attachments/assets/fae4c7a5-61fe-4444-89b4-7837478cd8bf" />
<img width="1920" height="692" alt="ad749f71-0021-4121-8342-0f9e04707818" src="https://github.com/user-attachments/assets/879b8d83-663d-4011-906d-9d3b714aa4ea" />


# BOM
| #                       | Designator                                      | Footprint                  | Value / Description       | Manufacturer Part     | LCSC #    | Qty | Unit (USD) | LCSC Link                                          |
|-------------------------|-------------------------------------------------|----------------------------|---------------------------|-----------------------|-----------|-----|------------|----------------------------------------------------|
| 3                       | C21                                             | C0402                      | 4.7uF                     | GRM155R61A475KEAAD    | C77004    | 1   | $0.020     | https://www.lcsc.com/product-detail/C77004.html    |
| 4                       | C11,C12                                         | C0402                      | 10nF                      | 0402B103K500NT        | C1524     | 2   | $0.003     | https://www.lcsc.com/product-detail/C1524.html     |
| 5                       | C14                                             | C0603                      | 1uF                       | CL10A105KB8NNNC       | C15849    | 1   | $0.011     | https://www.lcsc.com/product-detail/C15849.html    |
| 6                       | C3,C4                                           | C0603                      | 6.8pF                     | 6.8pF                 | C15720    | 2   | $0.010     | https://www.lcsc.com/product-detail/C15720.html    |
| 7                       | C1                                              | C0603                      | 20pF                      | CL10C200JB8NNNC       | C1648     | 1   | $0.010     | https://www.lcsc.com/product-detail/C1648.html     |
| 8                       | C5,C6,C7,C8,C9,C10,C13,C15,C20,C22,C23,C24      | C0603                      | 100nF                     | CC0603KRX7R9BB104     | C14663    | 12  | $0.011     | https://www.lcsc.com/product-detail/C14663.html    |
| 9                       | X1                                              | CRYSTAL-SMD_4P-L3.2-W2.5   | 25MHz                     | X322525MOB4SI         | C9006     | 1   | $0.350     | https://www.lcsc.com/product-detail/C9006.html     |
| 10                      | H1,H2                                           | HDR-TH_20P-P2.54-V-M       | 20-Pin Header  2.54mm  x2 | PH2.54-1X20P-H25      | C42431804 | 2   | $0.100     | https://www.lcsc.com/product-detail/C42431804.html |
| 11                      | L2                                              | IND-SMD_L4.0-W4.0          | 2.2uH Inductor            | SMNR4020-2.2UH        | C135262   | 1   | $0.150     | https://www.lcsc.com/product-detail/C135262.html   |
| 12                      | U2                                              | LED-SMD_4P-L1.6-W0.8       | RGB LED  APHF1608         | APHF1608LSEEQBDZGKC   | C3019171  | 1   | $0.200     | https://www.lcsc.com/product-detail/C3019171.html  |
| 13                      | U1                                              | LQFP-64_L10.0-W10.0-P0.50  | STM32F722RET6  MCU        | STM32F722RET6         | C118207   | 1   | $4.500     | https://www.lcsc.com/product-detail/C118207.html   |
| 2                       | R7,R8,R9,R13,R14,R15                            | R0603                      | 50 ohm                    |                       |           | 6   | $0.010     | —                                                  |
| 14                      | X2                                              | OSC-SMD_2P-L1.6-W1.0       | 32.768kHz Crystal         | ABS05-32.768kHz-T     | C179633   | 1   | $0.250     | https://www.lcsc.com/product-detail/C179633.html   |
| 15                      | R5,R6                                           | R0603                      | 4.7k ohm                  | 0603WAF4701T5E        | C23162    | 2   | $0.010     | https://www.lcsc.com/product-detail/C23162.html    |
| 16                      | R1,R2,R3,R4,R10,R11,R12,R16,R17,R21,R22,R23,R24 | R0603                      | 10k ohm                   | RC0603FR-0710KL       | C98220    | 13  | $0.010     | https://www.lcsc.com/product-detail/C98220.html    |
| 17                      | R20                                             | R0603                      | 22.1k ohm                 | RMC060322.1K1%N       | C269476   | 1   | $0.010     | https://www.lcsc.com/product-detail/C269476.html   |
| 18                      | R18,R19                                         | R0603                      | 100k ohm                  | 0603WAF1003T5E        | C25803    | 2   | $0.010     | https://www.lcsc.com/product-detail/C25803.html    |
| 1                       | C2                                              | C0603                      | 3.9pF                     |                       |           | 1   | $0.010     | —                                                  |
| 19                      | D1                                              | SOD-123_L2.8-W1.8          | 1N4148W Diode             | 1N4148W               | C176288   | 1   | $0.020     | https://www.lcsc.com/product-detail/C176288.html   |
| 20                      | U5                                              | SOT-23-6_L2.9-W1.6         | LMR51430 Buck Reg         | LMR51430XDDCR         | C5185863  | 1   | $0.850     | https://www.lcsc.com/product-detail/C5185863.html  |
| 21                      | SW1,SW2                                         | SW-SMD_L3.9-W3.0           | Tactile Switch  x2        | TS-1088-AR02016       | C720477   | 2   | $0.100     | https://www.lcsc.com/product-detail/C720477.html   |
| 22                      | CARD1                                           | TF-SMD_TF-PUSH             | MicroSD  TF Push-Push     | TF PUSH               | C393941   | 1   | $0.190     | https://www.lcsc.com/product-detail/C393941.html   |
| 23                      | USB1                                            | USB-C-SMD_TYPE-C-16PIN-2MD | USB-C 16Pin Receptacle    | TYPE-C 16PIN 2MD(073) | C2765186  | 1   | $0.070     | https://www.lcsc.com/product-detail/C2765186.html  |
| 24                      | U4                                              | WSON-8_L8.0-W6.10          | W25Q256 Flash  256Mbit    | W25Q256JVEIQ          | C97522    | 1   | $0.850     | https://www.lcsc.com/product-detail/C97522.html    |
|                         |                                                 |                            |                           |                       |           |     |            |                                                    |
| TOTAL  —  58 components |                                                 |                            |                           |                       |           |     | $8.28      |                                                    |
