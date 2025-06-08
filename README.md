# DIY Guitar Pedals

>This project aims to create a DIY friendly and Mod-able version of  the iconic Boss DS-1 and Big Muff Pi.

Modern guitar pedals such as the DS-1 and Big Muff Pi are **super expensive**!! and the new pedals that are being produced all have SMD components which make it harder to mod and repair. I always wanted to get a DS-1 but its price tag really put me off, so I did a bit of research and found a really good circuit analysis of the DS-1 on [ElectroSmash's Website](https://www.electrosmash.com/boss-ds1-analysis) and decided to create my own [DS-1](https://github.com/Outdatedcandy92/DistortionPedal) and it was really rewarding project and the results were also very good. 
Since my DS-1 Version 1 had really good results, I decided to design an even upgraded version of it which fixes problems in version 1, In addition to that I also created a PCB for the Big Muff Pi.

  

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/7b425f8a721e7ffceada9d0cbc3adf055dcdea6a_125b_enclosure_v3a.png)


---

### DS-1

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/c9ca7fba437b5069672eba95f0e7a570b8b201e4_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/dc215ea83623df06ef8fe4def6dccc4c3c3fbf99_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/b2c504c2172b0a271f5ab44e659a56ee54b96f07_image.png)


### Big Muff Pi

![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/af90758d33a06b96d81334904c10ca93e55e96d0_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e0cc2ae4d1cc200cf90539164067dece34212204_image.png)
![img](https://hc-cdn.hel1.your-objectstorage.com/s/v3/160f2cf9e0e6de5ff6342c3ffaebcda90857dcd8_image.png)

  ---
## BOM

More detailed BOM with parts lists is under the `src` folder 

#### DS-1 Analysis
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



  

