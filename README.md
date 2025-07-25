# DIY Guitar Pedals

>This project aims to create a DIY friendly and Mod-able version of  the iconic Boss DS-1 and Big Muff Pi.

Modern guitar pedals such as the DS-1 and Big Muff Pi are **super expensive**!! and the new pedals that are being produced all have SMD components which make it harder to mod and repair. I always wanted to get a DS-1 but its price tag really put me off, so I did a bit of research and found a really good circuit analysis of the DS-1 on [ElectroSmash's Website](https://www.electrosmash.com/boss-ds1-analysis) and decided to create my own [DS-1](https://github.com/Outdatedcandy92/DistortionPedal) and it was really rewarding project and the results were also very good. 
Since my DS-1 Version 1 had really good results, I decided to design an even upgraded version of it which fixes problems in version 1, In addition to that I also created a PCB for the Big Muff Pi.


*DS-1 PCB*
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a1b9ffed037abc444fab042f3a4400229bf7e716_20250719_181108.jpg)

*Big Muff PCB*
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/b887e65a5c83b1924912c39876ea5a3a81818b0c_20250724_190411.jpg)





---

### DS-1

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/07179d3eb6becedfd4422e3f37c7bbf639a91378_20250724_191526.jpg)

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/6a99e1329f183502c543c42b5df1cb17409506b6_ds1.png)


![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/3d219760d81d5efcf9fcf327b9fafe8f66519aa1_image.png)

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/511560b9d5453f81d7b74e594aad4638ee63918d_image.png)



### Big Muff Pi

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/c8888a778247295a8d9f700a7b3baabe5e21d7f1_20250724_184247.jpg)

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/0820a318a2f2bb218df37eedc8cd1c87d29187c7_biog_uff.png)

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/05b99e2e0fc89bf58a42a6900fe9a9d7fbce08e7_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/bc20b4729c0d75fe8eeb1c3f438d2b05c71886d9_image.png)

### 3PDT Breakout Board (Optional)

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/36c04b03d0087f0b28dd7b724f5a0eb13d02dab8_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1a48bbef241dc3614f1828e7ed46d372c192b498_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/8c04008457cc388ee2a8fc55e68111c0a25c3e6b_image.png)


  ---
## BOM

More detailed BOM with parts lists is under the `src` folder 

### DS-1 Components
| **Reference**              | **Value / Part Number**           |
| -------------------------- | --------------------------------- |
| C1, C3                     | 47n                               |
| C2, C8, C9                 | 0.47µF                            |
| C4                         | 250pF                             |
| C5                         | 68n                               |
| C7                         | 100pF                             |
| C10                        | 0.01µF                            |
| C11                        | 0.022µF                           |
| C12                        | 0.1µF                             |
| C13                        | 0.047µF                           |
| C14                        | 1µF                               |
| C15                        | 47µF                              |
| C23                        | 100µF                             |
| D1                         | 1N4004                            |
| D4, D5, D8                 | D1N4148                           |
| Q1, Q2, Q3                 | 2SC2240                           |
| R1, R22                    | 1K                                |
| R2, R7                     | 470K                              |
| R3, R8, R18, R21, R24, R25 | 10K                               |
| R4, R5, R10, R11, R23      | 100K                              |
| R9                         | 22Ω                               |
| R13                        | 4.7K                              |
| R14, R15                   | 2.2K                              |
| R16, R17                   | 6.8K                              |
| R19, R20                   | 1M                                |
| R39                        | 47K                               |
| U1                         | NJM3404A (M5223AL, BA728N equiv.) |
| VR1, VR2                   | 100KB                             |
| VR3                        | 20KB                              |
| J1, J2                     | 6.35mm Jacks                      |
|                            |                                   |


### Big Muff Pi

| **Component Type**       | **Value / Part Number**                           | **Designators**                     |
|--------------------------|---------------------------------------------------|-------------------------------------|
| NPN Transistors          | BC239 or 2N5088, 2N5089, BC549C, SE4010, 2N5210   | Q1, Q2, Q3, Q4                      |
| Silicon Diodes           | 1N914 or 1N4148                                   | D1, D2, D3, D4                      |
| Potentiometers (Lin)     | 100K                                              | Sustain, Tone, Volume              |
| Resistors                | 10K                                               | R13, R19, R18, R11, R12            |
| Resistors                | 100K                                              | R20, R16, R3                       |
| Resistors                | 470K                                              | R9, R17, R15                       |
| Resistors                | 39K                                               | R2, R8                             |
| Resistors                | 150                                               | R21, R10                           |
| Resistors                | 15K                                               | R6                                 |
| Resistor                 | 47K                                               | R14                                |
| Resistor                 | 100                                               | R22                                |
| Resistor                 | 3.3K                                              | R4                                 |
| Resistor                 | 1K                                                | R23                                |
| Resistor                 | 22K                                               | R5                                 |
| Capacitors               | 1µF                                               | C1, C4, C6, C7                     |
| Capacitors               | 100nF                                             | C5, C13, C3, C2                    |
| Capacitors               | 470pF                                             | C10, C11, C12                      |
| Capacitor                | 4nF                                               | C9                                 |
| Capacitor                | 10nF                                              | C8                                 |









#### Credits

[ElectroSmash Boss DS-1 Analysis](https://www.electrosmash.com/boss-ds1-analysis)
[ElectroSmash Big Muff Pi Analysis](https://www.electrosmash.com/big-muff-pi-analysis)



  

