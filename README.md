DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by Linux users at https://linux-hardware.org.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo hw-probe -all -upload

Total reports: 21330.

Contents
--------

1. [ About ](#about)
2. [ Devices ](#devices)
   * [ Cpu ](#cpu)
   * [ Memory ](#memory)
   * [ Battery ](#battery)

About
-----

The structure of the repository is the following:

    {COMPUTER TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}

    ( e.g. Notebook/Dell/XPS/XPS 15 9550/323DFD9291C0 )

Devices
-------

Top 250 most popular devices in each category.

Count  — number of computers with this device installed,
Probe  — latest probe ID of this device.

### Cpu

| MFG        | Name                           | GHz  | Count | Probe      |
|------------|--------------------------------|------|-------|------------|
| Intel      | Core i5-3210M                  | 2.50 | 203   | 632B661A7E |
| Intel      | Core i5-3230M                  | 2.60 | 142   | E67DFC255A |
| Intel      | Core 2 Duo E8400               | 3.00 | 138   | D232DBDCE3 |
| Intel      | Core i5-2450M                  | 2.50 | 132   | E2413CEA5D |
| Intel      | Pentium B960                   | 2.20 | 128   | 891002E8F2 |
| Intel      | Atom N450                      | 1.66 | 127   | 5D585B11E9 |
| Intel      | Core i5-2410M                  | 2.30 | 127   | 7F96DEDA8A |
| Intel      | Celeron N2840                  | 2.16 | 127   | A1D2E02773 |
| Intel      | Core i3-2350M                  | 2.30 | 125   | 6B25B8982D |
| AMD        | FX -6300 Six-Core              |      | 122   | 1F7F86ED9E |
| Intel      | Atom N270                      | 1.60 | 121   | E6CF3D7F11 |
| Intel      | Core i3-3110M                  | 2.40 | 119   | B9A4817612 |
| Intel      | Core i3-2120                   | 3.30 | 118   | 4BD42BC14C |
| AMD        | E-450 APU with Radeon HD Gr... |      | 117   | 8CCF84D124 |
| Intel      | Core i3-2310M                  | 2.10 | 111   | 8579BA1B16 |
| Intel      | Core 2 Quad Q6600              | 2.40 | 109   | 53C6C139DA |
| Intel      | Core i3 M 370                  | 2.40 | 106   | 8FAE94D181 |
| Intel      | Core i3 M 380                  | 2.53 | 106   | E6323014B6 |
| Intel      | Core 2 Duo E7500               | 2.93 | 104   | 3134315807 |
| Intel      | Core i5-2430M                  | 2.40 | 104   | 1B6DCB6A34 |
| AMD        | FX-8350 Eight-Core             |      | 100   | FEAA959521 |
| Intel      | Core i3-2100                   | 3.10 | 100   | EB9D0FE3F5 |
| Intel      | Atom N2600                     | 1.60 | 98    | ADF87DAC7F |
| Intel      | Core i5-4210U                  | 1.70 | 98    | 2A224752BA |
| AMD        | Athlon II X2 250               |      | 97    | 07BA810409 |
| Intel      | Pentium Dual-Core E5300        | 2.60 | 97    | 0E497514B2 |
| Intel      | Core i3-3220                   | 3.30 | 90    | 7D1A3490AA |
| Intel      | Core i5-3470                   | 3.20 | 88    | 2703EE0766 |
| Intel      | Core i5-2400                   | 3.10 | 86    | 66A5EA0BE5 |
| Intel      | Pentium 2020M                  | 2.40 | 86    | 908F38EB2A |
| Intel      | Core 2 Duo E6550               | 2.33 | 83    | 969A371A99 |
| Intel      | Atom N455                      | 1.66 | 83    | 7438532ADB |
| AMD        | FX-8320 Eight-Core             |      | 78    | 6A60A724F9 |
| Intel      | Atom N570                      | 1.66 | 77    | 0B64C1379E |
| Intel      | Core i3-2330M                  | 2.20 | 77    | 05F2682C5B |
| Intel      | Pentium Dual-Core T4500        | 2.30 | 76    | 0CEC12C495 |
| Intel      | Core i7-2670QM                 | 2.20 | 76    | 005450877A |
| Intel      | Pentium 4                      | 3.00 | 75    | B8D44517A1 |
| Intel      | Core i7-3770K                  | 3.50 | 74    | FB18F180A5 |
| Intel      | Core i5-7200U                  | 2.50 | 72    | F227611E1F |
| Intel      | Core i7-3770                   | 3.40 | 72    | 41F60D966A |
| Intel      | Pentium 4                      | 3.00 | 71    | 642FED58C5 |
| Intel      | Core i7-3630QM                 | 2.40 | 71    | 268D53A8B4 |
| AMD        | FX -4300 Quad-Core             |      | 69    | C79641FC9B |
| Intel      | Core i5-4460                   | 3.20 | 69    | 91C1AFF11E |
| Intel      | Core i3-3217U                  | 1.80 | 68    | 1CA46CE89B |
| AMD        | A10-4600M APU with Radeon H... |      | 67    | 45864F9C6B |
| Intel      | Core i3-3120M                  | 2.50 | 67    | 9A401175B3 |
| Intel      | Core i5-3337U                  | 1.80 | 66    | 8123FE2145 |
| Intel      | Core 2 Duo E4500               | 2.20 | 65    | 1ACC3BBABB |
| Intel      | Core i5-2520M                  | 2.50 | 65    | 28C0349E06 |
| Intel      | Core i5-4200U                  | 1.60 | 65    | 4E682AC524 |
| Intel      | Pentium Dual-Core E5700        | 3.00 | 64    | AD36B40663 |
| Intel      | Pentium Dual-Core T4300        | 2.10 | 64    | 73E5B46F66 |
| Intel      | Pentium P6200                  | 2.13 | 64    | 52035C5F01 |
| Intel      | Celeron N3050                  | 1.60 | 64    | 5762619036 |
| Intel      | Core i5-6200U                  | 2.30 | 64    | BEF9865EC7 |
| Intel      | Pentium M processor            | 1.20 | 63    | D5D7DAB02F |
| Intel      | Core i5 M 460                  | 2.53 | 61    | 84F06D63E2 |
| Intel      | Core i3-5005U                  | 2.00 | 61    | 9E9396445A |
| Intel      | Pentium Dual E2180             | 2.00 | 59    | A0BFCB3B91 |
| Intel      | Core i5-2500                   | 3.30 | 59    | 3D9E77AE8A |
| Intel      | Core i7-2600                   | 3.40 | 59    | D5C9D589F2 |
| Intel      | Pentium N3540                  | 2.16 | 59    | 7297A28A7F |
| AMD        | Phenom II X4 965               |      | 58    | F0FD8645E5 |
| Intel      | Pentium 4                      | 3.20 | 58    | 59817A0992 |
| Intel      | Core i7-2630QM                 | 2.00 | 58    | 1F578B22B4 |
| Intel      | Core i7-7700HQ                 | 2.80 | 57    | CB9F8EC46D |
| Intel      | Pentium Dual-Core E5400        | 2.70 | 57    | 1BDFB65A5B |
| Intel      | Pentium Dual-Core T4400        | 2.20 | 57    | 36F0A1FAAD |
| Intel      | Core i7-2600K                  | 3.40 | 57    | EC6555DA94 |
| AMD        | E-350                          |      | 56    | 5E3F89149F |
| Intel      | Core 2 Duo E8400               | 3.00 | 56    | 2893794AF3 |
| Intel      | Atom Z3735F                    | 1.33 | 56    | ED81FBB6E1 |
| Intel      | Celeron N2830                  | 2.16 | 56    | 903B641CA7 |
| Intel      | Core i5-5200U                  | 2.20 | 56    | 456A3DFFE5 |
| Intel      | Atom x5-Z8350                  | 1.44 | 56    | 4064B5A9F9 |
| Intel      | Core i5-8250U                  | 1.60 | 55    | 376C2CCA98 |
| Intel      | Core 2 Duo E8500               | 3.16 | 55    | E1D8ADF3C9 |
| Intel      | Core i5-2500K                  | 3.30 | 55    | 640C9F1AB7 |
| Intel      | Core i5-3570K                  | 3.40 | 55    | 0BFC90B6BA |
| AMD        | FX -4100 Quad-Core             |      | 54    | ABBA273D4F |
| AMD        | FX -6100 Six-Core              |      | 54    | 792BC1DD6F |
| AMD        | Athlon 64 X2 Dual Core 5200+   |      | 53    | F87C76BA83 |
| Intel      | Pentium Dual E2200             | 2.20 | 53    | D3B45DE297 |
| Intel      | Pentium Dual-Core T4200        | 2.00 | 53    | 571AB72073 |
| Intel      | Core i7-3610QM                 | 2.30 | 53    | 3EFE65FA87 |
| Intel      | Core i7-6700HQ                 | 2.60 | 53    | 7E4A6B2354 |
| Intel      | Core 2 Duo P8400               | 2.26 | 52    | 37B037257F |
| Intel      | Core i3-6006U                  | 2.00 | 52    | 3E47232411 |
| AMD        | Athlon 64 X2 Dual Core 6000+   |      | 51    | EE184BFE51 |
| AMD        | Phenom II X4 955               |      | 51    | 92145D937F |
| Intel      | Core i7-8550U                  | 1.80 | 51    | 5F7A70586E |
| Intel      | Core 2 Duo E6750               | 2.66 | 51    | 48709E5844 |
| Intel      | Atom D525                      | 1.80 | 51    | 682BC26535 |
| Intel      | Core i3 M 330                  | 2.13 | 51    | 3EBC919E62 |
| Intel      | Core i3 M 350                  | 2.27 | 51    | 838DE3CB18 |
| Intel      | Core i5-3317U                  | 1.70 | 51    | E3825A8890 |
| Intel      | Pentium Dual E2160             | 1.80 | 50    | FFC9B5ED4F |
| Intel      | Core 2 Duo E7200               | 2.53 | 50    | F8AE92B32F |
| Intel      | Pentium P6100                  | 2.00 | 50    | 86987CF1ED |
| Intel      | Core i5-3570                   | 3.40 | 50    | D3CBC50580 |
| Intel      | Core i3-4005U                  | 1.70 | 50    | 966882EE7D |
| Intel      | Celeron N3060                  | 1.60 | 50    | 11C32DDA05 |
| Intel      | Core i3-6100                   | 3.70 | 50    | BD6DC70775 |
| AMD        | Athlon II X4 640               |      | 49    | 28A9991FCB |
| Intel      | Pentium 4                      | 2.80 | 49    | D2C80DA520 |
| Intel      | Celeron E3400                  | 2.60 | 49    | B023115CE4 |
| Intel      | Core i5 M 480                  | 2.67 | 49    | 4C990A61B6 |
| Intel      | Core i5-4200M                  | 2.50 | 49    | DEDB8E43CB |
| Intel      | Pentium D                      | 3.20 | 48    | C6129C8C14 |
| Intel      | Core 2 Duo T5750               | 2.00 | 47    | 71B1D42943 |
| Intel      | Pentium G2020                  | 2.90 | 47    | 73CB5810A1 |
| Intel      | Celeron 2955U                  | 1.40 | 47    | C7C9017A3C |
| AMD        | Athlon II X2 240               |      | 46    | 2DE6892C13 |
| AMD        | E-300 APU with Radeon HD Gr... |      | 46    | F9F3745636 |
| Intel      | Celeron                        | 2.66 | 46    | 231DE8EA15 |
| Intel      | Celeron                        | 2.93 | 46    | 8219FBB532 |
| Intel      | Core 2 Quad Q8300              | 2.50 | 46    | BBFC5C83ED |
| Intel      | Pentium B950                   | 2.10 | 46    | 54ADC646D6 |
| Intel      | Core i3-3240                   | 3.40 | 46    | F2FF6FB037 |
| Intel      | Core i7-8750H                  | 2.20 | 45    | 9CA695A346 |
| Intel      | Core 2 Duo E7400               | 2.80 | 45    | 2FDD668590 |
| Intel      | Core i3-2370M                  | 2.40 | 45    | 69DE877AA2 |
| Intel      | Core i5-2320                   | 3.00 | 45    | 9FAB0B6F0B |
| Intel      | Celeron 1005M                  | 1.90 | 45    | 298DAC5F6C |
| Intel      | Core 2 Duo E4600               | 2.40 | 44    | 04AE7D50B4 |
| Intel      | Pentium G630                   | 2.70 | 44    | 11581C9025 |
| Intel      | Core i3-4130                   | 3.40 | 44    | 02CBA6FDA0 |
| Intel      | Core i7-4770                   | 3.40 | 44    | B687FAFEA4 |
| AMD        | C-60 APU with Radeon HD Gra... |      | 43    | 599BB74F20 |
| AMD        | A8-4500M APU with Radeon HD... |      | 43    | 92AE8C0F3B |
| Intel      | Pentium G620                   | 2.60 | 43    | 8871866F65 |
| Intel      | Core i7-4700MQ                 | 2.40 | 43    | 08F8DE28C7 |
| Intel      | Pentium Dual-Core E5200        | 2.50 | 42    | 758924E4F2 |
| Intel      | Core i5 750                    | 2.67 | 42    | 551193665F |
| Intel      | Core i3 550                    | 3.20 | 42    | 12256732C2 |
| Intel      | Celeron B800                   | 1.50 | 42    | 241AE2B69C |
| Intel      | Core i5-3450                   | 3.10 | 42    | 9EF947B594 |
| Intel      | Pentium 2117U                  | 1.80 | 42    | EFA97B65E3 |
| Intel      | Pentium G3220                  | 3.00 | 42    | 3859A17AD1 |
| AMD        | Athlon 64 X2 Dual Core 4000+   |      | 41    | B08E58BFEB |
| Intel      | Pentium D                      | 2.66 | 41    | 7B78886CE4 |
| Intel      | Celeron 900                    | 2.20 | 41    | A4A296B8BB |
| Intel      | Core 2 Duo T6600               | 2.20 | 41    | 167B3FD913 |
| Intel      | Core i5 760                    | 2.80 | 41    | 85F57C764C |
| Intel      | Core i5 M 430                  | 2.27 | 41    | 6C36A45E07 |
| Intel      | Celeron B820                   | 1.70 | 41    | F28D18F3E9 |
| Intel      | Core i5-2300                   | 2.80 | 41    | E971779389 |
| Intel      | Pentium B940                   | 2.00 | 41    | 877057DB38 |
| Intel      | Pentium G2030                  | 3.00 | 41    | 154C64D953 |
| Intel      | Core i5-4570                   | 3.20 | 41    | 1E5997F695 |
| AMD        | Athlon 64 X2 Dual Core 4200+   |      | 40    | 31EC690BE3 |
| Intel      | Core 2 6600                    | 2.40 | 40    | 7B106B9427 |
| Intel      | Celeron 540                    | 1.86 | 40    | 52B80877DA |
| Intel      | Pentium D                      | 3.40 | 39    | 0C62C4C191 |
| Intel      | Core 2 Duo E7300               | 2.66 | 39    | 3991181C75 |
| Intel      | Atom N2800                     | 1.86 | 39    | 4C67B55B77 |
| Intel      | Core i7-4790                   | 3.60 | 39    | 2272E1FA1D |
| AMD        | A6-6310 APU with AMD Radeon... |      | 38    | 00C22F3924 |
| Intel      | Core 2 Duo T7500               | 2.20 | 38    | E1C83EA9AE |
| Intel      | Core i3-7100                   | 3.90 | 38    | BD3CFBCE71 |
| Intel      | Core i5-2310                   | 2.90 | 38    | A1E970227D |
| Intel      | Core i5-3330                   | 3.00 | 38    | 0A593D376A |
| Intel      | Core i7-4500U                  | 1.80 | 38    | FA252F5949 |
| Intel      | Pentium N3700                  | 1.60 | 38    | 9964879FBE |
| Intel      | Pentium G4400                  | 3.30 | 38    | 0BF4CAF942 |
| Intel      | Core 2 Quad Q9300              | 2.50 | 37    | 36D3F979DC |
| Intel      | Core i3 540                    | 3.07 | 37    | B4F81E84C8 |
| Intel      | Celeron G530                   | 2.40 | 37    | B1C86BAC64 |
| Intel      | Core i3-4000M                  | 2.40 | 37    | 9EF7CE41C7 |
| Intel      | Core i5-4440                   | 3.10 | 37    | 1DBE9C51F6 |
| Intel      | Core i3-4010U                  | 1.70 | 37    | FDD61F096B |
| AMD        | Athlon 64 X2 Dual Core 5000+   |      | 36    | B4B7FB1E21 |
| AMD        | E1-1200 APU with Radeon HD ... |      | 36    | A312BDDCD7 |
| Intel      | Core 2 Duo T5550               | 1.83 | 36    | CC01255AAA |
| Intel      | Core i5-3320M                  | 2.60 | 36    | 0D769EAB0A |
| Intel      | Celeron G1840                  | 2.80 | 36    | 8AE6B6F651 |
| Intel      | Core i3-4030U                  | 1.90 | 36    | 1DEA266689 |
| Intel      | Core i3-6100U                  | 2.30 | 36    | 200C878097 |
| Intel      | Core 2 T7200                   | 2.00 | 35    | 19A4B7F9E2 |
| Intel      | Core i7-4770K                  | 3.50 | 35    | CC9738C393 |
| Intel      | Core i5-6500                   | 3.20 | 35    | E4A1AC8DFE |
| AMD        | Athlon 64 X2 Dual Core 4400+   |      | 34    | CD4ECC0B42 |
| AMD        | A4-3300M APU with Radeon HD... |      | 34    | 937DD869FC |
| AMD        | C-50                           |      | 34    | 377FEBC80C |
| Intel      | Celeron 430                    | 1.80 | 34    | 6154EA6AE1 |
| Intel      | Pentium N3710                  | 1.60 | 34    | 6458C4F07B |
| AMD        | A4-5000 APU with Radeon HD ... |      | 33    | 12801C9BDF |
| Intel      | Pentium 4                      | 3.20 | 33    | 5CED2505B9 |
| Intel      | Celeron M processor            | 1.50 | 33    | 48522ED650 |
| Intel      | Core i3 530                    | 2.93 | 33    | 7D62E5BC34 |
| Intel      | Celeron B815                   | 1.60 | 33    | FE2AB22987 |
| Intel      | Core i7-6500U                  | 2.50 | 33    | A586F57112 |
| AMD        | Athlon 64 X2 Dual Core 4800+   |      | 32    | 9B11B923A2 |
| AMD        | Athlon II X2 245               |      | 32    | E3128E9139 |
| AMD        | Athlon II P320 Dual-Core       |      | 32    | 1A24B89466 |
| AMD        | Athlon II X2 220               |      | 32    | E327FDD558 |
| AMD        | A6-4400M APU with Radeon HD... |      | 32    | 01D1980A2A |
| Intel      | Core i7-7500U                  | 2.70 | 32    | 67672EF038 |
| Intel      | Core 2 Duo T5800               | 2.00 | 32    | 77E3B20E26 |
| Intel      | Core 2 Duo P8700               | 2.53 | 32    | 530502BEDD |
| Intel      | Pentium B970                   | 2.30 | 32    | 2D672E25E0 |
| Intel      | Pentium G860                   | 3.00 | 32    | 4C163D8A71 |
| Intel      | Core i3-4170                   | 3.70 | 32    | 66D36BB608 |
| Intel      | Core i7-4710HQ                 | 2.50 | 32    | 3A17D38BDD |
| AMD        | Athlon II X2 215               |      | 31    | C9F702BE07 |
| AMD        | Athlon II P340 Dual-Core       |      | 31    | 33969DDCE8 |
| AMD        | Athlon II X2 270               |      | 31    | CC22922655 |
| Intel      | Celeron Dual-Core T3100        | 1.90 | 31    | A7EC10F5EE |
| Intel      | Pentium Dual-Core E5200        | 2.50 | 31    | F6B9026258 |
| Intel      | Pentium Dual-Core E6500        | 2.93 | 31    | 6DB0F0B43C |
| Intel      | Core 2 Duo T8100               | 2.10 | 31    | E5DE762918 |
| AMD        | Athlon 64 X2 Dual Core 5600+   |      | 30    | 5824A23FE2 |
| AMD        | E2-1800 APU with Radeon HD ... |      | 30    | 9E99F18B81 |
| Intel      | Pentium 4                      | 3.00 | 30    | 03B6DE378D |
| Intel      | Core 2 Duo T5250               | 1.50 | 30    | FAECBEFA9B |
| Intel      | Pentium Dual T2390             | 1.86 | 30    | BD8A19714A |
| Intel      | Atom 330                       | 1.60 | 30    | 1CADF5EB87 |
| Intel      | Core i5 M 520                  | 2.40 | 30    | 2AFD83B0D3 |
| Intel      | Pentium B980                   | 2.40 | 30    | 19CDBF743C |
| Intel      | Celeron 1000M                  | 1.80 | 30    | 2D8991FAAF |
| Intel      | Core i5-4670                   | 3.40 | 30    | F79161999A |
| Intel      | Core 2 Duo T7250               | 2.00 | 29    | E3B1F6D810 |
| Intel      | Core 2 T5500                   | 1.66 | 29    | 719BE91D02 |
| Intel      | Core 2 Quad Q8400              | 2.66 | 29    | FAC5E9FEFA |
| Intel      | Pentium Dual-Core E6600        | 3.06 | 29    | 60A3A2F64B |
| Intel      | Core i7-4790K                  | 4.00 | 29    | 7552A8CB4C |
| Intel      | Core i7-4510U                  | 2.00 | 29    | FD24FFF375 |
| Intel      | Core 2 4300                    | 1.80 | 28    | BF99369A01 |
| Intel      | Core i5-7400                   | 3.00 | 28    | 2048B1ECF6 |
| Intel      | Celeron Dual-Core T3000        | 1.80 | 28    | 370DCD58CC |
| Intel      | Celeron E3300                  | 2.50 | 28    | BFC8CAB47C |
| Intel      | Core 2 Quad Q9400              | 2.66 | 28    | F640B8A0CB |
| Intel      | Celeron B830                   | 1.80 | 28    | 923B4CD756 |
| Intel      | Core i7-3632QM                 | 2.20 | 28    | 5E69C5F864 |
| Intel      | Core i7-4700HQ                 | 2.40 | 28    | 2A3F7B30CC |
| AMD        | Athlon II X2 250               |      | 27    | 45F3041E55 |
| AMD        | A6-3400M APU with Radeon HD... |      | 27    | 2C903F36D0 |
| AMD        | A10-5750M APU with Radeon H... |      | 27    | FBC2F0A547 |
| AMD        | E1-2100 APU with Radeon HD ... |      | 27    | 7C8E8CFB76 |
| AMD        | E1-6010 APU with AMD Radeon... |      | 27    | 8B0DFDBE84 |
| Intel      | Celeron D 220                  | 1.20 | 27    | 9B7F075594 |
| Intel      | Atom N550                      | 1.50 | 27    | 75D4E1070C |
| Intel      | Core i5-3550                   | 3.30 | 27    | 435E64F300 |
| Intel      | Core i5-4670K                  | 3.40 | 27    | 3166CD0BE4 |
| Intel      | Core i7-6700                   | 3.40 | 27    | DA78DC8E90 |
| AMD        | Athlon 64 X2 Dual Core 4200+   |      | 26    | 4F9FB84CF3 |
| AMD        | Athlon 64 X2 Dual Core 3800+   |      | 26    | 0478804BE2 |
| AMD        | Phenom II X6 1055T             |      | 26    | C44B707FC4 |

### Memory

| MFG        | Name               | Size     | Type | MT/s | Count | Probe      |
|------------|--------------------|----------|------|------|-------|------------|
|            | Module DIMM        | 2048 MB  | DDR2 | 800  | 492   | 2FDD668590 |
|            | Module SDRAM       | 2048 MB  |      |      | 473   | F8AE92B32F |
|            | Module SDRAM       | 1024 MB  |      |      | 433   | 34021FD6BD |
|            | Module             | 2048 MB  |      | 800  | 413   | F6B9026258 |
|            | Module SODIMM      | 1024 MB  | DDR2 | 667  | 344   | EE184BFE51 |
|            | Module DIMM        | 2048 MB  | DDR2 | 667  | 344   | EE184BFE51 |
|            | Module             | 4096 MB  |      | 1333 | 333   | A9ED28807E |
|            | Module             | 2048 MB  |      | 1333 | 321   | 551193665F |
|            | Module DIMM        | 1024 MB  | DDR2 | 800  | 301   | 48709E5844 |
| Samsung    | M471B5273DH0-CH... | 4096 MB  | DDR3 | 1334 | 277   | E2413CEA5D |
|            | Module             | 1024 MB  | DDR2 |      | 239   | CD4ECC0B42 |
|            | Module             | 2048 MB  | DDR2 |      | 236   | A3C4D07088 |
|            | Module             | 1024 MB  |      | 800  | 232   | F6B9026258 |
| Samsung    | M471B5773CHS-CH... | 2048 MB  | DDR3 | 1334 | 197   | AB17752168 |
|            | Module SODIMM      | 4096 MB  | DDR3 | 1333 | 195   | 6A60A724F9 |
|            | Module             | 2048 MB  |      | 667  | 194   | E1D8ADF3C9 |
| Samsung    | M471B5173DB0-YK... | 4096 MB  | DDR3 | 1600 | 188   | FDD61F096B |
| Samsung    | M471B5273CH0-CH... | 4096 MB  | DDR3 | 1334 | 180   | 6F9734843A |
|            | Module SODIMM      | 2048 MB  | DDR3 | 1333 | 177   | 961DE73328 |
| Samsung    | M471B5773DH0-CH... | 2048 MB  | DDR3 | 1600 | 172   | 1B6DCB6A34 |
| Samsung    | M471B5273DH0-CK... | 4096 MB  | DDR3 | 1600 | 167   | BBA96B0372 |
|            | Module             | 1024 MB  |      | 667  | 160   | 6DB0F0B43C |
| Samsung    | M471B5173QH0-YK... | 4096 MB  | DDR3 | 1600 | 153   | 166081CE08 |
|            | Module SDRAM       | 512 MB   |      |      | 151   | 642FED58C5 |
|            | SODIMM             | 2048 MB  | DDR2 | 667  | 142   | A7EC10F5EE |
|            | Module             | 2048 MB  |      | 400  | 125   | 982ACF395B |
|            | Module             | 4096 MB  |      | 1600 | 121   | C79641FC9B |
| Elpida     | EBJ41UF8BCS0-DJ... | 4096 MB  | DDR3 | 1334 | 118   | 9E99F18B81 |
|            | Module             | 1024 MB  |      |      | 116   | 38155B66BB |
|            | Module DIMM        | 4096 MB  | DDR3 | 1600 | 116   | B801DD3F7D |
| Samsung    | M471B5173EB0-YK... | 4096 MB  | DDR3 | 1600 | 115   | 1CC2218397 |
|            | Module             | 1024 MB  | DDR2 | 333  | 112   | F87C76BA83 |
|            | Module             | 4096 MB  | DDR3 |      | 107   | 1CA46CE89B |
| Kingston   | KHX1600C9D3/4GX... | 4096 MB  | DDR3 | 2400 | 106   | 1DBE9C51F6 |
|            | SODIMM             | 1024 MB  | DDR2 | 667  | 105   | 86E2030E27 |
|            | Module DDR         | 1024 MB  |      |      | 104   | 54C92BF69C |
| SK Hynix   | HMT351S6CFR8C-P... | 4096 MB  | DDR3 | 1600 | 99    | 3F35BDC85A |
| Samsung    | M471B5673FH0-CH... | 2048 MB  | DDR3 | 1334 | 99    | 973B44CBCE |
| 48spaces   | 012345678901234... | 1024 MB  | DDR2 | 800  | 92    | 5D585B11E9 |
|            | Module DRAM        | 1024 MB  |      |      | 92    | BDD475BFCC |
| Nanya      | NT2GC64B88B0NS-... | 2048 MB  | DDR3 | 1334 | 89    | D023F50697 |
|            | Module             | 2048 MB  | DDR2 | 333  | 86    | 7D6812488D |
|            | Module DDR         | 2048 MB  |      | 1333 | 85    | 966D463C0C |
| Samsung    | M471B5773DH0-CK... | 2048 MB  | DDR3 | 1600 | 85    | 3F35BDC85A |
|            | Module             | 2048 MB  |      | 1066 | 84    | A2DBF52E17 |
|            | Module             | 4096 MB  |      | 400  | 84    | 666B4349AD |
|            | Module DIMM        | 512 MB   | DDR2 |      | 81    | 16BE592F4F |
| Samsung    | M471B5673FH0-CF... | 2048 MB  |      | 1067 | 81    | 8A6BBDF84F |
|            | SODIMM             | 2048 MB  | DDR2 | 800  | 81    | 6D19C3FD33 |
| Elpida     | EBJ40UG8BBU0-GN... | 4096 MB  | DDR3 | 1600 | 77    | 92AE8C0F3B |
| Elpida     | EBJ21UE8BFU0-DJ... | 2048 MB  | DDR3 | 1334 | 76    | 8579BA1B16 |
| Nanya      | NT4GC64B8HB0NS-... | 4096 MB  | DDR3 | 1334 | 72    | E5D8A02D92 |
| Kingston   | KHX1600C10D3/8G... | 8192 MB  | DDR3 | 1600 | 71    | 0C7ACF2C99 |
| SK Hynix   | HMT451S6BFR8A-P... | 4096 MB  | DDR3 | 1600 | 69    | 6D5DE9B567 |
|            | Module             | 2048 MB  | DDR2 | 400  | 69    | C44B707FC4 |
| SK Hynix   | HMT351S6CFR8C-H... | 4096 MB  | DDR3 | 1333 | 68    | 2A3F7B30CC |
|            | Module SODIMM      | 1024 MB  | DDR2 | 533  | 68    | 4E526BB85F |
|            | Module             | 2048 MB  |      |      | 68    | 1293120120 |
| SK Hynix   | HMT425S6AFR6A-P... | 2048 MB  | DDR3 | 1600 | 67    | F652C9DD47 |
| Kingston   | 99U5471-012.A00... | 4096 MB  | DDR3 | 1600 | 66    | 724F1F5F22 |
| Micron     | 16KTF51264HZ-1G... | 4096 MB  | DDR3 | 1600 | 66    | B9A4817612 |
|            | Module             | 512 MB   |      |      | 66    | 2E9805CB56 |
| SK Hynix   | HMT325S6BFR8C-H... | 2048 MB  | DDR3 | 1334 | 66    | 1ABB956626 |
| Samsung    | M471B2873FHS-CH... | 1024 MB  | DDR3 | 1334 | 64    | 333F038ACE |
| SK Hynix   | HMT351S6CFR8C-H... | 4096 MB  | DDR3 | 1334 | 64    | E6323014B6 |
| Nanya      | NT4GC64B8HG0NS-... | 4096 MB  | DDR3 | 1333 | 63    | 68C4019E33 |
| SK Hynix   | HMT325S6CFR8C-P... | 2048 MB  | DDR3 | 1600 | 62    | E3825A8890 |
| Kingston   | ACR256X64D3S133... | 2048 MB  | DDR3 | 1334 | 62    | 86987CF1ED |
| ELPIDA     | EBJ21UE8BDS0-DJ... | 2048 MB  | DDR3 | 1334 | 61    | 530502BEDD |
| Samsung    | M471B5173BH0-CK... | 4096 MB  | DDR3 | 1600 | 60    | 0F042024B4 |
|            | Module             | 1024 MB  |      | 400  | 59    | BD4727E558 |
| SK Hynix   | HMT351S6CFR8C-P... | 4096 MB  | DDR3 | 1600 | 58    | A6777FAE90 |
|            | Module DIMM        | 2048 MB  | DDR2 | 533  | 56    | B4C2FB4D5A |
|            | Module SDRAM       | 4096 MB  |      |      | 56    | 5F6E1A3B61 |
| Micron     | 8JSF25664HZ-1G4... | 2048 MB  | DDR3 | 1333 | 55    | D588CD38C2 |
|            | Module DDR         | 2048 MB  |      | 800  | 55    | C92DC5D0CF |
|            | Module DIMM        | 512 MB   | DDR2 | 667  | 55    | 3DD6E989DE |
| SK Hynix   | HMT451S6AFR8A-P... | 4096 MB  | DDR3 | 1600 | 54    | EF1164AACA |
| Ramaxel    | RMT3170EB68F9W1... | 4096 MB  | DDR3 | 1600 | 54    | 72424367AD |
| Kingston   | 99U5584-005.A00... | 4096 MB  | DDR3 | 1600 | 53    | C0B50F9AE1 |
| Micron     | 8KTF51264HZ-1G6... | 4096 MB  | DDR3 | 1600 | 53    | 9964879FBE |
| Ramaxel    | RMT3160ED58E9W1... | 4096 MB  | DDR3 | 1600 | 53    | 0DBBF3578B |
| Samsung    | M471A5244CB0-CR... | 4096 MB  | DDR4 | 2400 | 51    | 3E47232411 |
| Samsung    | M471B2873FHS-CF... | 1024 MB  | DDR3 | 1067 | 51    | C08F9590AD |
|            | Module             | 2048 MB  |      | 1600 | 50    | 2F8132A2A1 |
|            | Module             | 2048 MB  | DDR3 |      | 50    | 1C35FEA298 |
| Samsung    | M471B5273CH0-CK... | 4096 MB  | DDR3 | 1600 | 50    | 2AFD83B0D3 |
| A-DATA     | AD73I1C1674EV S... | 4096 MB  | DDR3 | 1334 | 48    | E12F2B72CE |
| SK Hynix   | HMT451S6BFR8A-P... | 4096 MB  | DDR3 | 1600 | 47    | D0D112CE5B |
| Kingston   | 99U5471-020.A00... | 4096 MB  | DDR3 | 1600 | 47    | 88E3DD8AEA |
| Ramaxel    | RMT3020EC58E9F1... | 4096 MB  | DDR3 | 4199 | 47    | 5E3F89149F |
| Samsung    | M471B1G73QH0-YK... | 8192 MB  | DDR3 | 1600 | 47    | AC96DD45F9 |
| Micron     | 16JSF51264HZ-1G... | 4096 MB  | DDR3 | 1334 | 46    | 05F2682C5B |
| Nanya      | NT2GC64B88G0NS-... | 2048 MB  | DDR3 | 1600 | 45    | F56243C8E5 |
|            | Module             | 4096 MB  |      | 667  | 45    | F0B3D3251C |
|            | Module SODIMM      | 8192 MB  | DDR3 | 1600 | 45    | 8C6609B568 |
|            | Module             | 4096 MB  |      | 1066 | 44    | 7C64EA2E6D |
| Samsung    | M4 70T5663QZ3-C... | 2048 MB  | DDR2 | 2048 | 44    | B2E125B932 |
| Samsung    | M471B1G73DB0-YK... | 8192 MB  | DDR3 | 1600 | 44    | 3A17D38BDD |
| SK Hynix   | HMT325S6BFR8C-H... | 2048 MB  | DDR3 | 1333 | 43    | 6B25B8982D |
| Kingston   | 99U5469-045.A00... | 4096 MB  | DDR3 | 1600 | 43    | CC7193A7B9 |
|            | Module             | 4096 MB  |      | 800  | 43    | 36F0A1FAAD |
| Samsung    | M471B5673EH1-CF... | 2048 MB  |      | 4199 | 43    | 370DCD58CC |
| SK Hynix   | HMA81GS6AFR8N-U... | 8192 MB  | DDR4 | 2400 | 43    | 90E9F8DFAD |
|            | Module DDR         | 2048 MB  |      |      | 42    | 92ACB586D2 |
| Ramaxel    | RMT3010EC58E8F1... | 2048 MB  | DDR3 | 1600 | 42    | 52B3890B69 |
| Samsung    | M471B5674QH0-YK... | 2048 MB  | DDR3 | 1600 | 42    | 2C903F36D0 |
| SK Hynix   | HYMP125S64CP8-S... | 2048 MB  |      | 975  | 42    | 4A19D0FF08 |
| SK Hynix   | HMT351S6BFR8C-H... | 4096 MB  | DDR3 | 1333 | 41    | 6439D633F9 |
| Kingston   | ACR16D3LS1KFG/4... | 4096 MB  | DDR3 | 1600 | 41    | 1DEA266689 |
|            | Module DDR         | 512 MB   |      |      | 41    | 03602DBEA6 |
| Nanya      | NT2GC64B8HC0NS-... | 2048 MB  | DDR3 | 1334 | 40    | D023F50697 |
| SK Hynix   | HMT351S6CFR8C-P... | 4096 MB  | DDR3 | 1600 | 40    | 891002E8F2 |
| SK Hynix   | HMT451S6MFR8C-P... | 4096 MB  | DDR3 | 1600 | 40    | 87FE751543 |
|            | Module             | 512 MB   |      | 667  | 39    | 6DB0F0B43C |
| Samsung    | M471A1K43CB1-CR... | 8192 MB  | DDR4 | 2667 | 39    | 04B0989528 |
|            | Module             | 1024 MB  | DDR2 | 266  | 38    | 0478804BE2 |
|            | Module DIMM        | 2048 MB  | DDR3 | 1600 | 38    | F3C86A9592 |
|            | Module DRAM        | 2048 MB  |      |      | 38    | 666CC686BC |
|            | Module SDRAM       | 256 MB   |      |      | 38    | 231DE8EA15 |
| Samsung    | M378B5273DH0-CH... | 4096 MB  | DDR3 | 2133 | 38    | C2DCE3184C |
| Samsung    | M378B5773CH0-CH... | 2048 MB  | DDR3 | 1867 | 38    | 66A5EA0BE5 |
| SK Hynix   | HMT325S6CFR8C-H... | 2048 MB  | DDR3 | 1334 | 38    | 726FFF24C9 |
|            | SODIMM             | 1024 MB  | DDR2 | 533  | 38    | 2BD735CBDF |
| Kingston   | ACR16D3LFS1KBG/... | 2048 MB  | DDR3 | 1600 | 37    | 0D73CB1291 |
| Kingston   | KHX1866C10D3/8G... | 8192 MB  |      | 2133 | 37    | E969E52D33 |
|            | Module             | 8192 MB  |      | 1333 | 37    | A9ED28807E |
|            | Module DIMM        | 8192 MB  | DDR3 | 1333 | 37    | 7CF6D970EC |
| Samsung    | M378B5673FH0-CH... | 2048 MB  | DDR3 | 1600 | 37    | C8CDE63BC8 |
| SK Hynix   | HMT351U6CFR8C-H... | 4096 MB  | DDR3 | 1600 | 36    | 8798B74A8F |
| Kingston   | ACR16D3LS1NGG/4... | 4096 MB  | DDR3 | 1600 | 36    | E67DFC255A |
|            | Module             | 4096 MB  |      |      | 36    | 41A0E2A118 |
| Samsung    | M471B5273EB0-CK... | 4096 MB  | DDR3 | 1600 | 36    | 7C8E8CFB76 |
| SK Hynix   | HMA851S6AFR6N-U... | 4096 MB  | DDR4 | 2667 | 36    | F3941C8871 |
| ELPIDA     | EBJ20UF8BCS0-DJ... | 2048 MB  | DDR3 | 1334 | 35    | 1476158702 |
| SK Hynix   | HMT351S6EFR8A-P... | 4096 MB  | DDR3 | 1600 | 35    | 4E682AC524 |
| Kingston   | KHX1866C10D3/4G... | 4096 MB  | DDR3 | 1866 | 35    | 92145D937F |
| Micron     | 8KTF25664HZ-1G6... | 2048 MB  | DDR3 | 1600 | 35    | 700E6ABAE1 |
|            | Module DIMM DDR    | 1024 MB  |      | 667  | 35    | A2E86EFF2D |
|            | Module SDRAM       | 2048 MB  |      | 800  | 35    | 72A18A259D |
| Samsung    | M378B5773DH0-CH... | 2048 MB  | DDR3 | 1333 | 35    | 9F42078526 |
| SK Hynix   | HMT351S6BFR8C-H... | 4096 MB  | DDR3 | 1334 | 35    | DDA2EC4D0E |
| A-DATA     | AD73I1C1674EV S... | 4096 MB  | DDR3 | 1334 | 34    | 0BFEB87324 |
|            | Module DDR         | 1024 MB  |      | 800  | 34    | CE5CCA6404 |
|            | Module SDRAM       | 1024 MB  |      | 667  | 34    | 1E807288A2 |
| SK Hynix   | HMT451S6AFR8A-P... | 4096 MB  | DDR3 | 1600 | 33    | 07CD36611F |
|            | Module             | 2048 MB  | DDR3 | 800  | 33    | AA7248927B |
|            | Module DDR         | 4096 MB  |      | 1333 | 33    | 05DC50AA11 |
|            | Module DRAM        | 512 MB   |      |      | 33    | BDD475BFCC |
| Samsung    | M471B1G73EB0-YK... | 8192 MB  | DDR3 | 1600 | 33    | 91BF899CC4 |
| Kingston   | KHX1600C10D3/8G... | 8192 MB  | DDR3 | 1600 | 32    | 680A34868A |
|            | Module             | 1024 MB  | DDR2 | 400  | 32    | C4135693FC |
| Ramaxel    | RMT3170ME68F9F1... | 4096 MB  | DDR3 | 1600 | 32    | E1D3B73A71 |
| ASint      | SSY3128M8-EDJEF... | 1024 MB  | DDR3 | 1333 | 31    | 6B25B8982D |
| Kingston   | 99U5474-028.A00... | 4096 MB  | DDR3 | 1333 | 31    | C76B2FB327 |
|            | Module DDR         | 1024 MB  |      | 400  | 31    | 27FC10C18A |
|            | Module SDRAM       | 1024 MB  |      | 533  | 31    | A4A45B8A8B |
|            | Module DIMM DDR    | 2048 MB  |      | 667  | 31    | A2E86EFF2D |
| Samsung    | M378B5273CH0-CH... | 4096 MB  | DDR3 | 1867 | 31    | 2703EE0766 |
| SK Hynix   | HMT451S6AFR8A-P... | 4096 MB  | DDR3 | 1600 | 31    | 4FC85D1C31 |
| ASint      | SSZ3128M8-EDJEF... | 2048 MB  | DDR3 | 1333 | 30    | DB1BD4EC31 |
| SK Hynix   | HMT351S6EFR8C-P... | 4096 MB  | DDR3 | 1600 | 30    | A82FAD253C |
| Kingston   | KHX1600C10D3/4G... | 4096 MB  | DDR3 | 1600 | 30    | 66D36BB608 |
| Samsung    | M4 70T5663EH3-C... | 2048 MB  | DDR2 | 2048 | 30    | 1F49A84F1F |
| ELPIDA     | EBJ21UE8BDS0-AE... | 2048 MB  | DDR3 | 1067 | 29    | 673B5CB9B0 |
| SK Hynix   | HMT425S6AFR6A-P... | 2048 MB  | DDR3 | 1600 | 29    | 1DEA266689 |
| Nanya      | NT4GC64B8HG0NS-... | 4096 MB  | DDR3 | 1600 | 29    | 4FB6C852BB |
|            | Module             | 1024 MB  |      | 1333 | 29    | EEEE376F38 |
| Samsung    | M471B5273CH0-YK... | 4096 MB  | DDR3 | 1600 | 29    | B53D815277 |
| Samsung    | M471B5773CHS-CF... | 2048 MB  | DDR3 | 1067 | 29    | 7AFC4FAAC2 |
| Crucial    | CT51264BF160B.C... | 4096 MB  | DDR3 | 1600 | 28    | 6F9734843A |
| SK Hynix   | HMT41GS6BFR8A-P... | 8192 MB  | DDR3 | 1600 | 28    | 73DB320B5F |
| Kingston   | 99U5469-041.A00... | 4096 MB  | DDR3 | 1600 | 28    | 908F38EB2A |
|            | Module             | 4096 MB  | DDR3 | 800  | 28    | B95A670155 |
| Crucial    | CT51264BA160B.C... | 4096 MB  | DDR3 | 1600 | 27    | 762D77E60F |
| Elpida     | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 27    | 9604BDACB2 |
| Micron     | 4ATF51264HZ-2G3... | 4096 MB  | DDR4 | 2400 | 27    | 5F12E9FED8 |
|            | Module             | 2048 MB  | DDR2 | 266  | 27    | BD61806194 |
| SK Hynix   | HMT325S6CFR8C-H... | 2048 MB  | DDR3 | 1333 | 26    | 68C4019E33 |
| Nanya      | M2S4G64CB8HG5N-... | 4096 MB  | DDR3 | 1334 | 26    | 3A6CB2F9EA |
|            | Module             | 1024 MB  |      | 66   | 26    | 3F25A03C59 |
| Elpida     | EBJ40UG8EFU0 SO... | 4096 MB  | DDR3 | 1600 | 25    | BEE231AA07 |
| SK Hynix   | HMT325S6CFR8C-P... | 2048 MB  | DDR3 |      | 25    | A321FB83E7 |
| Kingston   | 99U5428-018.A00... | 8192 MB  | DDR3 | 1600 | 25    | 456A3DFFE5 |
| Kingston   | 99U5469-046.A00... | 4096 MB  | DDR3 | 1333 | 25    | E03A8C0C89 |
| Kingston   | KHX1866C9D3/4GX... | 4096 MB  | DDR3 | 1867 | 25    | 56C7F5C529 |
| Micron     | 8KTF51264HZ-1G6... | 4096 MB  | DDR3 | 1600 | 25    | B62C50E352 |
|            | Module SDRAM       | 2048 MB  |      | 533  | 25    | 9643FFAA28 |
| Samsung    | M4 70T2953EZ3-C... | 1024 MB  |      | 667  | 25    | A17761D3F8 |
| Samsung    | Module SODIMM      | 1024 MB  | DDR2 | 533  | 25    | 77770402E0 |
| SK Hynix   | HMT351S6EFR8A-P... | 4096 MB  | DDR3 | 1600 | 25    | 3BD7C91ED1 |
| Corsair    | CMX8GX3M2A1600C... | 4096 MB  | DDR3 | 1600 | 24    | EC6555DA94 |
| Kingston   | 99U5428-063.A00... | 8192 MB  | DDR3 | 1600 | 24    | B9A4817612 |
|            | Module             | 256 MB   |      |      | 24    | 94E705D4A2 |
|            | Module             | 512 MB   | DDR2 | 333  | 24    | 753ED60051 |
| Samsung    | M471B5173BH0-YK... | 4096 MB  | DDR3 | 1600 | 24    | DEDB8E43CB |
| Samsung    | M471B5273CM0-CH... | 4096 MB  | DDR3 | 1333 | 24    | 6D637319C4 |
|            | SODIMM             | 1024 MB  | DDR2 | 800  | 24    | 6D19C3FD33 |
| Elpida     | EBJ40UG8EFU0-GN... | 4096 MB  | DDR3 | 1600 | 23    | 010241E3A2 |
| SK Hynix   | Module DIMM        | 4096 MB  | DDR3 | 1600 | 23    | 087F924E20 |
| SK Hynix   | Module DIMM        | 4096 MB  | DDR3 | 1066 | 23    | 4064B5A9F9 |
| Kingston   | KHX1600C9S3L/8G... | 8192 MB  | DDR3 | 1600 | 23    | E2B52AF1A5 |
| Micron     | 16JSF25664HZ-1G... | 2048 MB  | DDR3 | 1067 | 23    | BBA96B0372 |
| Micron     | 16KTF1G64HZ-1G6... | 8192 MB  | DDR3 | 1600 | 23    | E2EB1F026B |
| Micron     | MT8KTF51264HZ-1... | 4096 MB  | DDR3 | 1600 | 23    | EFA97B65E3 |
| Micron     | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 23    | 9CF06D20FA |
|            | Module             | 4096 MB  | DDR3 | 1066 | 23    | B7DB1F6D08 |
|            | Module             | 8192 MB  |      | 1600 | 23    | 792BC1DD6F |
| SHARETR... | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 23    | 10D1795169 |
| SK Hynix   | HMT112S6TFR8C-H... | 1024 MB  | DDR3 | 1333 | 23    | 239DB5D282 |
| SK Hynix   | HYMP512S64CP8-Y... | 1024 MB  | DDR2 | 667  | 23    | CF41AB5F1A |
|            | SODIMM             | 2048 MB  | DDR2 | 533  | 23    | F027D59B91 |
| A-DATA     | AM1L16BC2P1-B1F... | 2048 MB  | DDR3 | 1600 | 22    | 6479F7F12B |
| Corsair    | CMZ8GX3M2A1600C... | 4096 MB  | DDR3 | 1600 | 22    | EC6555DA94 |
| SK Hynix   | HMT351S6BFR8C-H... | 4096 MB  | DDR3 | 1333 | 22    | 937DD869FC |
| SK Hynix   | HMT351U6CFR8C-P... | 4096 MB  | DDR3 | 1800 | 22    | F0D35357D4 |
| SK Hynix   | HMT451S6MFR8C-P... | 4096 MB  | DDR3 | 1600 | 22    | DAB56079A8 |
| Kingston   | 99U5428-040.A01... | 4096 MB  | DDR3 | 1334 | 22    | 19D5DAD934 |
| Kingston   | 99U5428-046.A00... | 4096 MB  | DDR3 | 1334 | 22    | 3EFE65FA87 |
| Kingston   | ACR16D3LS1KNG/4... | 4096 MB  | DDR3 | 1600 | 22    | EA5E934FE8 |
| Kingston   | ACR256X64D3S13C... | 2048 MB  | DDR3 | 1334 | 22    | 8E79CDDBDA |
| SK Hynix   | HYMP112S64CP6-Y... | 1024 MB  |      | 667  | 22    | E5DE762918 |
| A-DATA     | AM1U16BC4P2-B19... | 4096 MB  | DDR3 | 1600 | 21    | 268D53A8B4 |
| SK Hynix   | HMT325S6BFR8C-H... | 2048 MB  | DDR3 | 1334 | 21    | 8A1811EA2D |
| SK Hynix   | HYMP125S64CP8-S... | 2048 MB  | DDR2 | 800  | 21    | AC65EDA96F |
|            | Module DIMM        | 2048 MB  | DDR3 | 1067 | 21    | DDE51ECD79 |
|            | Module SODIMM      | 4096 MB  | DDR3 | 1067 | 21    | 5DE102EE2E |
|            | Module DDR         | 512 MB   |      | 333  | 21    | D753273D7B |
| SK Hynix   | HMT41GS6AFR8A-P... | 8192 MB  | DDR3 | 1600 | 20    | 9C035C7658 |
| Kingston   | ACR256X64D3S133... | 2048 MB  | DDR3 | 1333 | 20    | DDDC5B738C |
| Nanya      | NT2GT64U8HD0BN-... | 2048 MB  | DDR2 | 800  | 20    | B95AF01C35 |
|            | Module             | 1024 MB  | DDR3 | 1333 | 20    | 8F9E198F6E |
|            | Module SDRAM       | 1024 MB  |      | 800  | 20    | 1BC2451FA9 |
|            | Module DIMM        | 512 MB   | DDR2 | 533  | 20    | 7C6281F09B |
| Ramaxel    | RMT3170EF68F9W1... | 4096 MB  | DDR3 | 1600 | 20    | E40C63AC8F |
| Ramaxel    | RMT3170MN68F9F1... | 4096 MB  | DDR3 | 1600 | 20    | 00C22F3924 |
| Samsung    | M4 70T2864QZ3-C... | 1024 MB  | DDR2 | 2048 | 20    | B2E125B932 |
| Toshiba    | 64T128020EDL2.5... | 2048 MB  |      | 1066 | 20    | A4A296B8BB |
| Kingston   | 9905471-001.A01... | 2048 MB  | DDR3 | 1600 | 19    | F2560038AF |
| Kingston   | KHX1600C9S3L/4G... | 4096 MB  | DDR3 | 1600 | 19    | 7C0CD24986 |
| Kingston   | KHX2133C11D3/4G... | 4096 MB  | DDR3 | 2133 | 19    | 927A46266A |
| Kingston   | KHX2400C11D3/4G... | 4096 MB  | DDR3 | 2400 | 19    | 0A4CDB301F |
| Kingston   | Module DIMM        | 2048 MB  | DDR2 | 800  | 19    | 758924E4F2 |
| Kingston   | 414352313238583... | 1024 MB  | DDR2 | 667  | 19    | F81C51DA3D |
|            | Module SDRAM       | 2048 MB  |      | 667  | 19    | 1E807288A2 |
|            | Module             | 512 MB   |      | 400  | 19    | 119DCF1A1D |
|            | Module             | 512 MB   |      | 66   | 19    | 5D3AF9A12C |
|            | Module DDR         | 512 MB   |      | 400  | 19    | B7CEC1644D |
| Samsung    | M471A1K43BB1-CR... | 8192 MB  | DDR4 | 2400 | 19    | C07258B9AB |
| Samsung    | M471A5244CB0-CT... | 4096 MB  | DDR4 | 2667 | 19    | 4CF82380D8 |

### Battery

| MFG        | Name          | Wh    | Type    | Count | Probe      |
|------------|---------------|-------|---------|-------|------------|
| Lenovo     | PABAS0241231  | 38.8  | Li-ion  | 234   | 00C22F3924 |
| Samsung    |               | 49    | Li-ion  | 224   | 3A996CF854 |
| Compal     | PABAS0241231  | 30.9  | Li-ion  | 198   | 0F042024B4 |
| SANYO      | Li_Ion_4000mA | 47.5  | Li-ion  | 150   | D023F50697 |
| ASUSTeK    | ASUS          | 50.1  | Li-ion  | 145   | 383A34EDD1 |
| Samsung    |               | 44    | Li-ion  | 117   | 5D585B11E9 |
| Notebook   | BAT           | 49    | Li-ion  | 106   | E2B52AF1A5 |
| SANYO      | AL10B31       | 48.8  | Li-ion  | 86    | 2612D462D9 |
| LG         | Li_Ion_4000mA | 47.5  | Li-ion  | 85    | 80ADE4BAB7 |
| Hewlett... | PABAS0241231  | 41.9  | Li-ion  | 82    | 0B84D724C8 |
| ASUSTeK    | X550A26       | 37.7  | Li-ion  | 72    | 6458C4F07B |
| PANASONIC  | Li_Ion_4000mA | 47.5  | Li-ion  | 72    | F28D18F3E9 |
| ASUSTek    | K52F-44       | 46.6  | Li-ion  | 71    | 52035C5F01 |
| Hewlett... | Primary       | 48    | Li-ion  | 69    | B1ED13A854 |
| Samsung    |               | 48    | Li-ion  | 68    | 86987CF1ED |
| ASUSTEK    | F82--22       | 46.2  | Li-ion  | 62    | 38190AD2E1 |
| SANYO      | PABAS0241231  | 55.9  | Li-ion  | 62    | E1D3B73A71 |
| SANYO      | GC86508SAT0   | 41.9  | Li-ion  | 60    | 5A52F8FD85 |
| SANYO      | PABAS024      | 85.4  | Li-ion  | 60    | 26DFFE047D |
| SANYO      | AS10D31       | 47.5  | Li-ion  | 58    | 690FFF1815 |
| LGC        | 45N1049       | 47.5  | Li-ion  | 55    | 65D329A2C6 |
| SANYO      | AL12A32       | 37    | Li-ion  | 54    | EB8B49B7B8 |
| Samsung    |               | 58    | Li-ion  | 52    | 6F9734843A |
| LG         | PABAS024      | 52.7  | Li-ion  | 48    | 7F96DEDA8A |
| Intel SR 1 | SR Real       | 22.1  | Li-ion  | 46    | AB6B2CF0E5 |
| LG         | PABAS0241231  | 53.3  | Li-ion  | 45    | 891002E8F2 |
| Sony       | VGP-BPS26     | 45.0  | Li-ion  | 43    | B56B7F6394 |
| ASUSTeK    | K55--44       | 47.9  | Li-ion  | 42    | 9A401175B3 |
| Hewlett... | Primary       | 42    | Li-ion  | 41    | 91BF899CC4 |
| Hewlett... | Primary       | 44    | Li-ion  | 41    | 8D460232A9 |
| Samsung    |               | 24    | Li-ion  | 41    | 359A01778D |
| ASUSTEK    | F3---24       | 51.2  | Li-ion  | 40    | 26F6983C58 |
| ASUSTek    | K53--52       | 57.2  | Li-ion  | 39    | 653D157E1A |
| ASUSTeK    | X550A30       | 44.6  | Li-ion  | 39    | A329AB5204 |
| Hewlett... | Primary       |       | Li-ion  | 38    | A17761D3F8 |
| Hewlett... | Primary       | 39    | Li-ion  | 37    | 2CE0B2FF35 |
| SIMPLO     | PABAS0241231  | 41.6  | Li-ion  | 37    | A295EE15E6 |
| ASUSTEK    | F5---22       | 47.3  | Li-ion  | 36    | 54C92BF69C |
| Sony       | Li_Ion_4000mA | 47.5  | Li-ion  | 36    | 07988069C9 |
| Hewlett... | 5600          | 62.1  | Li-ion  | 35    | EDC722485A |
| OEM        | standard      | 15.8  | Li-ion  | 34    | 100EB984CA |
| SANYO      | 45N1043       | 38.8  | Li-ion  | 34    | 2ACB72482B |
| SANYO      | GRAPE32       | 48.8  | Li-ion  | 34    | 77E3B20E26 |
| Hewlett... | Primary       | 45    | Li-ion  | 33    | 12D1FAA353 |
| SANYO      | L09S6Y02      | 38.8  | Li-ion  | 33    | 241AE2B69C |
| ASUSTeK    | X555-50       | 37.3  | Li-ion  | 32    | FDD61F096B |
| Hewlett... | Primary       | 40    | Li-ion  | 32    | A586F57112 |
| SANYO      | 0032334134... | 55.9  | Li-ion  | 32    | 1DEA266689 |
| ASUSTek    | K53--27       | 37.8  | Li-ion  | 31    | 55E49B0471 |
| ASUSTEK    | T12--22       | 720.8 | Li-ion  | 31    | 8D9FBEF758 |
| Hewlett... | Primary       | 46    | Li-ion  | 31    | E5DA00D166 |
| SANYO      | AL15A32       | 37    | Li-ion  | 30    | 6D1C781DE0 |
| ASUSTek    | X101CH        | 23.7  | Li-ion  | 29    | B6B9B50BF1 |
| SMP        | L09M6Y02      | 48.8  | Li-ion  | 29    | 678D443649 |
| TKBSS      | NS2P3SZMC4WR  | 48.4  | Li-ion  | 29    | 52592CBE1C |
|            | 47.52         | 48    | Li-ion  | 28    | 92F9AF7165 |
| ASUSTek    | 1015PE        | 56.9  | Li-ion  | 28    | 0B64C1379E |
| Lenovo     |               | 28    |         | 28    | C3DB42E6C3 |
| Hewlett... | Primary       | 41    | Li-ion  | 27    | 9246996D88 |
| Hewlett... | Primary       | 43    | Li-ion  | 27    | AC96DD45F9 |
| Hewlett... | Primary       | 55    | Li-ion  | 27    | AC65EDA96F |
| LGC        | AC14B8K       | 48.9  | Li-ion  | 27    | C5279AB6E4 |
| Samsung    | SR Real       | 43.0  | Li-ion  | 27    | 268D53A8B4 |
| ASUSTek    | M50--24       | 51.2  | Li-ion  | 26    | 37A9E829F4 |
| ASUSTeK    | N56--52       | 56.6  | Li-ion  | 26    | 024331191D |
| ASUSTeK    | X200-30       | 33.4  | Li-ion  | 26    | 9ED9651BBD |
| ASUSTeK    | X453-42       | 31.6  | Li-ion  | 26    | 4FB6C852BB |
|            | Battery       |       |         | 26    | 259A32BE33 |
| Hewlett... | Primary       | 38    | Li-ion  | 26    | CF41AB5F1A |
| Lenovo     |               | 32    |         | 26    | CC7193A7B9 |
| ASUSTeK    | K56--30       | 44.6  | Li-ion  | 25    | 469E04E0D5 |
| LGC        | L11L6Y01      | 43.6  | Li-ion  | 25    | ACACD85E54 |
| MSI        | BIF0_9        | 53.2  | Li-ion  | 25    | 1A1634FC24 |
| SMP        | bq20z451      | 63.1  | Li-ion  | 25    | 2458B122E5 |
| Samsung    |               | 45    | Li-ion  | 24    | 539459E889 |
| Sony       | PABAS024      | 52.7  | Li-ion  | 24    | 1D59A8F384 |
| ASUSTek    | PA3533U       | 51.4  | Li-ion  | 23    | 9A249DA8EE |
| LGC        | AC14B18J      | 36.7  | Li-ion  | 23    | A1D2E02773 |
| Hewlett... | Primary       | 36    | Li-ion  | 22    | 419900511F |
| Hewlett... | Primary       | 37    | Li-ion  | 22    | AB69AA73CD |
| Hewlett... | Primary       | 47    | Li-ion  | 22    | DDF30C670A |
| Hewlett... | Primary       | 89    | Li-ion  | 22    | 504BD53ED5 |
| SANYO      | AP13B3K       | 53.4  | Li-ion  | 22    | E0BC700445 |
| Hewlett... | Primary       | 49    | Li-ion  | 21    | 73E5B46F66 |
| Hewlett... | Primary       | 50    | Li-ion  | 21    | 3240076AA6 |
| SANYO      | AL10A31       | 24.4  | Li-ion  | 21    | 599BB74F20 |
| Sony       |               | 42    | Li-ion  | 21    | B5FB03D2E4 |
| Hewlett... | Primary       | 30    | Li-ion  | 20    | 76C5526BE8 |
| SANYO      | AS09A31       | 47.5  | Li-ion  | 20    | A9096F6AE6 |
| Sony       |               | 51    | Li-ion  | 20    | 1C35FEA298 |
|            | 48.84         | 49    | Li-ion  | 19    | D87F262565 |
| ASUSTeK    | K55--47       | 51.7  | Li-ion  | 19    | 55CEFCDC0B |
| ASUSTEK    | PA3533U       | 57.7  | Li-ion  | 19    | 0051F69751 |
| ASUSTek    | X401-44       | 47.5  | Li-ion  | 19    | 908F38EB2A |
| OEM        | AS10D31       | 48.4  | Li-ion  | 19    | 4A1964118D |
| Panasonic  | AS10D51       | 47.5  | Li-ion  | 19    | ACFD67A4EA |
| SANYO      | AS07B31       | 65.1  | Li-ion  | 19    | 884C33EE98 |
| SMP        | L16M2PB1      | 30    | Li-poly | 19    | 5A0A25C9FF |
| Sony       | CONIS41       | 48.8  | Li-ion  | 19    | 2589B300F1 |
|            | 48.6          | 49    | Li-ion  | 18    | 2DCF55334F |
| ASUSTeK    | X551-30       | 32.6  | Li-ion  | 18    | 5AD90522EC |
| Hewlett... | Primary       | 34    | Li-ion  | 18    | FBC2F0A547 |
| Hewlett... | Primary       | 35    | Li-ion  | 18    | 9BE61E9A2D |
| Lenovo     | BCL3100LiON   | 43.1  | Li-ion  | 18    | F9F3745636 |
| SANYO      | AS07A31       | 48.8  | Li-ion  | 18    | 3EBC919E62 |
| ASUSTeK    | X550E26       | 37.4  | Li-ion  | 17    | 7297A28A7F |
| DP         | bq20z451      | 95.0  | Li-ion  | 17    | 80ECBDE76E |
| Hewlett... | Primary       | 28    | Li-ion  | 17    | 5A84E64836 |
| Lenovo ... |               | 32    |         | 17    | 87D6FAC6F8 |
| Lenovo     | L11S6Y01      | 38.8  | Li-ion  | 17    | 5710B81F4D |
| SMP        | 45N1045       | 42.7  | Li-ion  | 17    | 368DCE09B7 |
| Toshiba    | PA3533U       | 56.1  | Li-ion  | 17    | 377FEBC80C |
| Acer       | Primary       | 44    | Li-ion  | 16    | F63B72DAC0 |
| Hewlett... | Primary       | 29    | Li-ion  | 16    | A96D39DDA2 |
| Hewlett... | Primary       | 31    | Li-ion  | 16    | BDDCB664D8 |
| Lenovo ... |               | 28    |         | 16    | 663BC4D39A |
| Lenovo     | LCFC          | 31.6  |         | 16    | 10DEE916FF |
| SIMPLO     | MWL32b        | 48.8  | Li-ion  | 16    | E07AB48C55 |
| Sony       | GC86503SY90   | 51.3  | Li-ion  | 16    | 719BE91D02 |
| ASUSTek    | M50--22       | 47.3  | Li-ion  | 15    | 69FF33D4E9 |
| ASUSTeK    | N550-40       | 60.4  | Li-ion  | 15    | 31F0B418F9 |
| ASUSTeK    | N750-62       | 69.4  | Li-ion  | 15    | 8E10CD5377 |
| Compal     | PABAS024      | 54.2  | Li-ion  | 15    | 877057DB38 |
| Hewlett... | Primary       | 32    | Li-ion  | 15    | 2D18EDEC4D |
| SIMPLO     | DELL 4DMNG31N | 66.6  | Li-ion  | 15    | 3935C68D79 |
| Simplo     | Li_Ion_4000mA | 48.8  | Li-ion  | 15    | F130F0DF5C |
| Toshiba    | PA3817U-1BRS  | 47.5  | Li-ion  | 15    | 57BAB28E56 |
|            |               | 47    | Li-ion  | 14    | 052EF081E3 |
| Compal     | PA3817U-1BRS  | 47.5  | Li-ion  | 14    | 0C917B1E8C |
| Hewlett... | 5100          | 55.0  |         | 14    | 831EAB83E8 |
| Hewlett... | Primary       | 27    | Li-ion  | 14    | E2EB1F026B |
| SANYO      | 45N1001       | 56.1  | Li-ion  | 14    | 4D1B987AAC |
| Sony       | VGP-BPS35A    | 42.3  | Li-ion  | 14    | 1CA46CE89B |
| ASUSTek    | N61--52       | 57.2  | Li-ion  | 13    | 6B772C892D |
| Hewlett... | Primary       | 22    | Li-ion  | 13    | 8F23861866 |
| PANASONIC  | AS16A5K       | 41.4  | Li-ion  | 13    | 9FBE4A663A |
| PANASONIC  | PABAS024      | 57.5  | Li-ion  | 13    | 13E3FEA8B4 |
| SANYO      | 45N1773       | 23.2  | Li-ion  | 13    | 4E682AC524 |
| SANYO      | L11S6Y01      | 41.9  | Li-ion  | 13    | ECF9D3F57B |
| SMP        | DELL GPM0365  | 97.0  | Li-ion  | 13    | 9CA695A346 |
| Sony       | AS10D41       | 47.5  | Li-ion  | 13    | B13B756085 |
| Toshiba    | PA3465U       | 65.1  | Li-ion  | 13    | 04FEFA3CE2 |
| ASUSTek    | 1001PX        | 46.4  | Li-ion  | 12    | DDBC734D1C |
| ASUSTek    | 1025C         | 56.1  | Li-ion  | 12    | F923747F5E |
| ASUSTek    | K53--26       | 39    | Li-ion  | 12    | 070E696863 |
| Hewlett... | Primary       | 16    | Li-ion  | 12    | F4B4B7905C |
| Hewlett... | Primary       | 23    | Li-ion  | 12    | D231B98589 |
| Hewlett... | Primary       | 33    | Li-ion  | 12    | 05F2682C5B |
| Hewlett... | Primary       | 54    | Li-ion  | 12    | 456A3DFFE5 |
| LGC        | 45N1127       | 23.4  | Li-ion  | 12    | 4E682AC524 |
| NEC        | PC-VP-BP77    | 86.5  | Li-ion  | 12    | 61E9D19C43 |
| Notebook   | BAT           | 77    | Li-ion  | 12    | FF0FE48329 |
| SANYO      | GARDA31       | 48.8  | Li-ion  | 12    | CD4578E8E4 |
| SANYO      | L10S6Y01      | 47.5  | Li-ion  | 12    | 17BE920F30 |
| Toshiba    | PA3534U       | 46.6  | Li-ion  | 12    | CE608A0D1E |
| Toshiba    | PA3534U-1BRS  | 46.6  | Li-ion  | 12    | E6C9D1B45A |
| 131-42-6E  | HS04041       | 42.0  | Li-ion  | 11    | 1CC2218397 |
| ASUSTek    | 1001PXD       | 23.7  | Li-ion  | 11    | CC9E23776C |
| ASUSTEK    | A8---24       | 51.2  | Li-ion  | 11    | FAECBEFA9B |
| ASUSTek    | N55--52       | 57.2  | Li-ion  | 11    | 1D32FC2BDA |
| ASUSTEK    | UL50-56       | 84    | Li-ion  | 11    | 6439D633F9 |
| ASUSTek    | X202-51       | 38.0  | Li-ion  | 11    | 5BB3C668C2 |
| ASUSTeK    | X551-26       | 37.4  | Li-ion  | 11    | EFA97B65E3 |
| CPT-COS    | L16C2PB2      | 30.6  | Li-poly | 11    | 15C78EBC5E |
| Hewlett... | Primary       | 26    | Li-ion  | 11    | 69CEE0DC90 |
| Hewlett... | Primary       | 5     | Li-ion  | 11    | 77770402E0 |
| Hewlett... | Primary       | 57    | Li-ion  | 11    | 240B48EAA4 |
| Notebook   | BAT           | 33    | Li-ion  | 11    | D4EAA0F0C1 |
| PANASONIC  | AS10B5E       | 64.8  | Li-ion  | 11    | 973B44CBCE |
| SANYO      | AC13C34       | 30.0  | Li-ion  | 11    | F08AFAA79D |
| SDI        | Dell          | 49    | Li-ion  | 11    | 44D4B713EC |
| TPS        | S10           | 36.5  | Li-ion  | 11    | 3E70A8DFF1 |
|            | 94.576        | 95    | Li-ion  | 10    | 71B1D42943 |
| ASUSTek    | 1215N         | 57.7  | Li-ion  | 10    | 1D126E3917 |
| ASUSTek    | UX32-65       | 48.2  | Li-ion  | 10    | E3825A8890 |
| ASUSTek    | X102-30       | 33.4  | Li-ion  | 10    | A7F7276E3D |
| ASUSTeK    | X402--38      | 38.0  | Li-ion  | 10    | 39FEC50B91 |
| Hewlett... | Primary       | 18    | Li-ion  | 10    | 6AF35F9DAD |
| Hewlett... | Primary       | 63    | Li-ion  | 10    | 18D94651FD |
| Hewlett... | Primary       | 73    | Li-ion  | 10    | 51BA7CEE66 |
| LGC        | 42T4911       | 56.1  | Li-ion  | 10    | D10B82AD22 |
| LION       |               | 48    |         | 10    | 4BBB490EBC |
| OEM        | AS10D51       | 48.4  | Li-ion  | 10    | 4A0A696E9A |
| PAC        | BAT           | 48    |         | 10    | 3E8051F49C |
| SMP-SDI2.8 | DELL FW1MN31  | 41.4  | Li-ion  | 10    | F85FEC55BB |
| Sony       |               | 52    | Li-ion  | 10    | 9E7981F839 |
| 111-83-72  | HS04041       | 39.5  | Li-ion  | 9     | 4FF0905A4F |
|            | 43.2          | 43    | Li-ion  | 9     | 1A72697C61 |
|            | 48.84         | 49    |         | 9     | CE35F353AC |
| ASUSTek    | K72J-44       | 48.4  | Li-ion  | 9     | E9B489DE35 |
| Compal     | Li_Ion_4000mA | 47.5  | Li-ion  | 9     | D138E04435 |
| Hewlett... | 4400          | 48.8  | Li-ion  | 9     | 45D2217223 |
| Hewlett... | Primary       | 14    | Li-ion  | 9     | 5FF106A10D |
| Hewlett... | Primary       | 24    | Li-ion  | 9     | C56EC0A2C5 |
| LG         | AS10D81       | 47.5  | Li-ion  | 9     | F56243C8E5 |
| LGC        | LNV-45N1      | 47.5  | Li-ion  | 9     | 8556FE8940 |
| LGC06      | L10L6Y01      | 48.8  | Li-ion  | 9     | 275850C827 |
| Notebook   | BAT           | 45    | Li-ion  | 9     | 072E0E1290 |
| Notebook   | BAT           | 62    | Li-ion  | 9     | 7716D0F2A1 |
| PAC        | PC-VP-WP93... | 47.5  |         | 9     | ACC8C72C7B |
| PANASONIC  | AS07B51       | 48.6  | Li-ion  | 9     | E6FF05AC01 |
| Samsung    |               | 38    | Li-ion  | 9     | 73EFFCB164 |
| SANYO      | AC14B13J      | 38.2  | Li-ion  | 9     | 5C330828A8 |
| SANYO      | AL12B32       | 37    | Li-ion  | 9     | 4D75D0FE0A |
| SANYO      | Chapala       | 71.0  | Li-ion  | 9     | 8028F0CCAE |
| SANYO      | NS2P3SZNJ4WR  | 48.7  | Li-ion  | 9     | 5781A29611 |
| SIMPLO     | AS10D73       | 48.8  | Li-ion  | 9     | 2DABFA1484 |
| SMP        | DELL VN3N047  | 41.4  | Li-ion  | 9     | A8122EF82D |
| SMP-SAN2.8 | DELL FW1MN41  | 41.4  | Li-ion  | 9     | CF2231949D |
| Sony       | AS09A41       | 48.8  | Li-ion  | 9     | 184B996E7B |
| Sony       |               | 63    | Li-ion  | 9     | 2A2BD0A648 |
| 13-54      | MO06062       | 55.5  | Li-ion  | 8     | A2443C2500 |
| ASUSTeK    | N551-52       | 56.1  | Li-ion  | 8     | F810A8999A |
| ASUSTeK    | TP50042       | 48.3  | Li-ion  | 8     | 4018847A8C |
| ASUSTek    | U31-58        | 81.2  | Li-ion  | 8     | A48BDA615E |
| ASUSTeK    | UX3-44        | 50.1  | Li-ion  | 8     | C370427F60 |
|            |               | 24    |         | 8     | 1AE3C738C0 |
|            |               |       | Li-ion  | 8     | 6479F7F12B |
|            |               | 16    | Li-ion  | 8     | 583681EEED |
| Hewlett... | Primary       | 11    | Li-ion  | 8     | 8B37127CB0 |
| Hewlett... | Primary       | 20    | Li-ion  | 8     | EA2A3A9DBB |
| Hewlett... | Primary       | 21    | Li-ion  | 8     | 54EA8BDC1D |
| Lenovo ... |               | 38    |         | 8     | 41499A9600 |
| Lenovo ... |               | 41    |         | 8     | 3A0F823175 |
| LGC        | 45N1011       | 86.5  | Li-ion  | 8     | 2064D92892 |
| LGC        | AC14A8L       | 52.4  | Li-ion  | 8     | F379C6ADAA |
| MSI        | PC-VP-BP77    | 55.0  | Li-ion  | 8     | 7B37D276D8 |
| Samsung    |               | 30    | Li-ion  | 8     | 706C37BC54 |
| SANYO      | 42T4791       | 47.5  | Li-ion  | 8     | 12347C1A1E |
| SANYO      | AL10C31       | 48.8  | Li-ion  | 8     | 37EFB54C3C |
| SMP        | LNV-L11M3P01  | 48.6  | Li-ion  | 8     | 553D2C16FB |
| 133-42-... | JC04041       | 42.4  | Li-ion  | 7     | 7E3B6FA95F |
|            |               | 47    | Li-ion  | 7     | 3CCBC58BF8 |
| Acer       | Primary       | 71    | Li-ion  | 7     | 109CDB17E1 |
| ASUSTek    | 1015B         | 56.1  | Li-ion  | 7     | 0453E7F33D |
| ASUSTek    | 1215B         | 56.1  | Li-ion  | 7     | 17B560680A |
| ASUSTEK    | A6-4224       | 69.9  | Li-ion  | 7     | C1DA7EE91F |
| ASUSTeK    |               |       | Li-ion  | 7     | 8E14B6278C |
| ASUSTeK    | X502--38      | 38.0  | Li-ion  | 7     | 2867D3E608 |
|            |               | 64    |         | 7     | 9B018C1776 |
|            |               | 28    | Li-ion  | 7     | 54908845C3 |
| Compal     | AS09A61       | 47.5  | Li-ion  | 7     | A7297EDA20 |
| DYNAPACK   | HB4593R1ECW   | 56.3  | Li-ion  | 7     | 5F7A70586E |
| Generic... | Internal      | 48.8  | Li-ion  | 7     | F2981C1775 |
| Hewlett... | Primary       | 1     | Li-ion  | 7     | 5725E675B6 |
| Hewlett... | Primary       | 51    | Li-ion  | 7     | D9CA1DBE13 |
| Hewlett... | Primary       | 56    | Li-ion  | 7     | E0DF895DC8 |
| Hewlett... | Primary       | 62    | Li-ion  | 7     | 4DADC69EFA |
| Hewlett... | Primary       | 8     | Li-ion  | 7     | 19D5DAD934 |
| Hewlett... |               | 36    | Li-ion  | 7     | F47ABA591C |

