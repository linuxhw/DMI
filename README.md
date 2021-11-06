DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by Linux users at https://linux-hardware.org.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 67147.

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

| MFG        | Name                             | GHz  | Count | Probe      |
|------------|----------------------------------|------|-------|------------|
| Intel      | 11th Gen Core i5-1135G7          | 2.40 | 770   | DA5E2F59CC |
| Intel      | Core i5-8250U                    | 1.60 | 674   | 8272A05168 |
| Intel      | Core i7-8550U                    | 1.80 | 641   | 08D287D2E2 |
| Intel      | Core i5-7200U                    | 2.50 | 544   | 9C8BB9558A |
| Intel      | Core i7-8750H                    | 2.20 | 453   | 2C6C86B1FB |
| Intel      | Core i7-9750H                    | 2.60 | 446   | 58E43F0514 |
| Intel      | Core i5-3210M                    | 2.50 | 433   | 783D081B5A |
| AMD        | Ryzen 5 3600 6-Core              |      | 428   | DF8AB9EFFB |
| Intel      | Core i7-10510U                   | 1.80 | 416   | A35AAAEB6D |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 403   | 1310B8ABF4 |
| Intel      | Core i7-7700HQ                   | 2.80 | 399   | EDD545A455 |
| Intel      | Core i5-6200U                    | 2.30 | 373   | 1069B24865 |
| Intel      | Core i7-8565U                    | 1.80 | 368   | A01E524A66 |
| Intel      | Core i7-7500U                    | 2.70 | 365   | C74129A618 |
| AMD        | Ryzen 7 3700X 8-Core             |      | 357   | 93DE1508CB |
| Intel      | Core i5-2520M                    | 2.50 | 330   | 96BD4FE29A |
| Intel      | Celeron N2840                    | 2.16 | 323   | 8C4669BE5C |
| Intel      | Core i5-10210U                   | 1.60 | 319   | BA8F31C45F |
| Intel      | Core 2 Duo E8400                 | 3.00 | 319   | AADCA45789 |
| Intel      | Core i5-3230M                    | 2.60 | 315   | 4639F065C8 |
| Intel      | Core i5-3470                     | 3.20 | 310   | C2D53C8118 |
| Intel      | Core i5-8265U                    | 1.60 | 292   | 5A60912D9F |
| AMD        | FX -6300 Six-Core                |      | 289   | 1161AF8368 |
| Intel      | Core i5-5200U                    | 2.20 | 286   | 0D89B6423C |
| Intel      | Core i5-2450M                    | 2.50 | 282   | 85A514F622 |
| Intel      | Core i5-2410M                    | 2.30 | 281   | 7EAEAE034C |
| Intel      | Core i5-4210U                    | 1.70 | 270   | DBF0FD04C3 |
| AMD        | FX-8350 Eight-Core               |      | 269   | 044227E4BA |
| Intel      | Core i3-2120                     | 3.30 | 269   | D6237E9949 |
| Intel      | Core i7-3770                     | 3.40 | 265   | D397A37935 |
| Intel      | Atom x5-Z8350                    | 1.44 | 264   | 091F7C8FAE |
| Intel      | Core i7-8565U                    | 1.80 | 262   | 111B26A250 |
| Intel      | Core i5-3320M                    | 2.60 | 258   | EC8AF5F350 |
| AMD        | Ryzen 5 2600 Six-Core            |      | 254   | 6546164DC0 |
| Intel      | Core i3-2350M                    | 2.30 | 246   | F5112DBF47 |
| Intel      | Core i5-2400                     | 3.10 | 246   | FF8EC660B8 |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 242   | 1719B2DC9D |
| Intel      | Core i3-3110M                    | 2.40 | 240   | 60A030AED3 |
| Intel      | Core i7-6700HQ                   | 2.60 | 239   | CFA4E16D46 |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 235   | F05671884B |
| AMD        | Ryzen 9 3900X 12-Core            |      | 234   | 2AB4CA2F07 |
| Intel      | Core 2 Duo E7500                 | 2.93 | 234   | C64672A543 |
| Intel      | Core i3-2100                     | 3.10 | 230   | 6978CD209F |
| Intel      | Core 2 Quad Q6600                | 2.40 | 226   | 77C4005BD9 |
| Intel      | Core i5-8265U                    | 1.60 | 223   | 55A32EF8DC |
| Intel      | Core i3-2310M                    | 2.10 | 223   | B96D5D5FDC |
| Intel      | Atom N270                        | 1.60 | 218   | 24833C6A59 |
| Intel      | Core i5-2430M                    | 2.40 | 218   | A610876405 |
| Intel      | Core i3-5005U                    | 2.00 | 216   | A5F750922A |
| Intel      | Core i7-10750H                   | 2.60 | 215   | 32F01CCAAB |
| Intel      | Pentium B960                     | 2.20 | 213   | CB2F8C100B |
| Intel      | Core i3-3220                     | 3.30 | 212   | 6CEE757CF0 |
| Intel      | Core i5-4200U                    | 1.60 | 212   | 1014243935 |
| Intel      | Core i3 M 370                    | 2.40 | 211   | DEC993FE87 |
| AMD        | Ryzen 5 4500U with Radeon Gra... |      | 210   | 8948989999 |
| Intel      | Core i3-6006U                    | 2.00 | 210   | 2BF6813AD9 |
| Intel      | Core i5-1035G1                   | 1.00 | 206   | 7125C6F5DD |
| Intel      | Core i7-2600                     | 3.40 | 203   | D19235C3D0 |
| Intel      | Core i5-6300U                    | 2.40 | 202   | 436E9BF227 |
| Intel      | Atom N450                        | 1.66 | 201   | 09B8FC981C |
| Intel      | Core i7-6500U                    | 2.50 | 201   | 9B5832381A |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 200   | 1E059DB869 |
| Intel      | Core i3 M 380                    | 2.53 | 193   | 6547CDED19 |
| Intel      | Core i7-4790                     | 3.60 | 193   | 287D0004F3 |
| Intel      | Core i7-1065G7                   | 1.30 | 192   | 138EC046F1 |
| AMD        | Ryzen 5 2500U with Radeon Veg... |      | 187   | 31B241368B |
| Intel      | Celeron N3060                    | 1.60 | 187   | B9D36307A5 |
| AMD        | E-450 APU with Radeon HD Grap... |      | 184   | AF980DC491 |
| Intel      | Core i5-4460                     | 3.20 | 182   | E9CD437617 |
| Intel      | Core i7-2670QM                   | 2.20 | 179   | C9D463149F |
| Intel      | Core i7-3630QM                   | 2.40 | 177   | 95C381CCD9 |
| Intel      | Core i5-5300U                    | 2.30 | 169   | A7CC3183F2 |
| Intel      | Core i7-6700K                    | 4.00 | 169   | AEA7D9561E |
| Intel      | Core i5-5250U                    | 1.60 | 168   | 5B47E8EFCB |
| AMD        | Athlon II X2 250                 |      | 163   | 0F23350175 |
| Intel      | Pentium Dual-Core E5300          | 2.60 | 163   | 1157C2A82C |
| Intel      | Core i5-6500                     | 3.20 | 163   | 77006702F8 |
| Intel      | Core i5-8300H                    | 2.30 | 161   | D55AC505B9 |
| Intel      | Core i7-8650U                    | 1.90 | 160   | 92DCB677F7 |
| Intel      | Core i5-4570                     | 3.20 | 160   | 2253D95E90 |
| Intel      | Core i5-4300U                    | 1.90 | 160   | E2559AC29A |
| Intel      | Core i3-3217U                    | 1.80 | 157   | 831FFF897A |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 155   | C7798BA8D3 |
| Intel      | Atom N455                        | 1.66 | 155   | F696958F46 |
| AMD        | Ryzen 5 1600 Six-Core            |      | 153   | 854B629E99 |
| Intel      | Core i3-2330M                    | 2.20 | 151   | 8A74691BA9 |
| Intel      | Core i7-4770                     | 3.40 | 151   | D4C089BC2F |
| Intel      | Core i7-5500U                    | 2.40 | 151   | 545EB61311 |
| Intel      | Celeron N3350                    | 1.10 | 151   | 6121781D85 |
| AMD        | Ryzen 7 PRO 4750U with Radeon... |      | 149   | 273A5FF27D |
| Intel      | Pentium Dual-Core T4500          | 2.30 | 148   | C8F8ADC564 |
| Intel      | Core i7-3770K                    | 3.50 | 147   | 68530FD616 |
| AMD        | Ryzen 7 3700U with Radeon Veg... |      | 146   | C62BB4ADC9 |
| Intel      | Core i7-6700                     | 3.40 | 146   | 6AD4929A33 |
| Intel      | Core i5-3337U                    | 1.80 | 144   | 58CC91ABA3 |
| Intel      | Core i7-4790K                    | 4.00 | 144   | 5CA8BBD80D |
| Intel      | Core i5-2500K                    | 3.30 | 143   | AB9C12AF26 |
| Intel      | Core i7-2630QM                   | 2.00 | 142   | 997A879973 |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 141   | 437D5A964E |
| Intel      | Pentium 2020M                    | 2.40 | 141   | 5CEAD11297 |
| Intel      | Celeron N3050                    | 1.60 | 140   | DF9E8736C9 |
| Intel      | Atom N2600                       | 1.60 | 139   | A83E302ABA |
| Intel      | Core i3-4005U                    | 1.70 | 138   | 0862DC626B |
| Intel      | Core 2 Duo E6550                 | 2.33 | 137   | B62359FCB1 |
| Intel      | Core i3-3120M                    | 2.50 | 136   | 779684E41D |
| AMD        | FX-8320 Eight-Core               |      | 135   | 5DE7270820 |
| Intel      | Core i7-4700MQ                   | 2.40 | 135   | A817ED896E |
| Intel      | Core i7-8665U                    | 1.90 | 134   | 6A14ED2D5E |
| Intel      | Core i7-6600U                    | 2.60 | 131   | FDC6203A6E |
| AMD        | FX -4300 Quad-Core               |      | 130   | B42BC6EE49 |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 130   | F20F2BFC32 |
| Intel      | Core i5-2500                     | 3.30 | 130   | 9F4091C7EE |
| Intel      | Core i7-2600K                    | 3.40 | 130   | ECAEB257A3 |
| Intel      | Core i5-3570K                    | 3.40 | 129   | BF66E1D281 |
| Intel      | Core i7-4510U                    | 2.00 | 128   | B2CDA34B7E |
| Intel      | Core i5-7400                     | 3.00 | 126   | 95F6633EA0 |
| Intel      | Core i5-3570                     | 3.40 | 126   | F17F22EFDC |
| Intel      | Core i5-4590                     | 3.30 | 126   | 639A06485D |
| Intel      | Pentium Dual-Core E5700          | 3.00 | 125   | 22FD625209 |
| Intel      | Core i7-8700                     | 3.20 | 123   | 667289D1B9 |
| Intel      | Core i7-8700K                    | 3.70 | 123   | 05766074D7 |
| Intel      | Core i5 M 460                    | 2.53 | 123   | 2AF79BA873 |
| Intel      | Core i5-4200M                    | 2.50 | 123   | CD55B73689 |
| Intel      | Core i5-8400                     | 2.80 | 121   | CDD35D634D |
| Intel      | Pentium Dual-Core T4300          | 2.10 | 121   | AA058ED867 |
| Intel      | Core i3-6100                     | 3.70 | 121   | C3479871D7 |
| Intel      | Core i7-7700K                    | 4.20 | 120   | F3A274A366 |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 119   | 4574E23B8D |
| Intel      | Core i7-3610QM                   | 2.30 | 119   | AAF9EFF6BD |
| Intel      | Pentium Dual-Core T4400          | 2.20 | 118   | 3BFB2E5E7B |
| Intel      | Atom Z3735F                      | 1.33 | 118   | DE0A5F2925 |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 117   | 83E53328A7 |
| Intel      | Core i3 M 350                    | 2.27 | 117   | C3F92D48E5 |
| Intel      | Pentium N3540                    | 2.16 | 117   | 8F1DD3CE3A |
| Intel      | Core i5-3317U                    | 1.70 | 117   | 94471889B0 |
| Intel      | Core 2 Duo P8600                 | 2.40 | 116   | 80E0B6AF9E |
| Intel      | Core 2 Duo P8400                 | 2.26 | 116   | 8C2D9E608C |
| AMD        | E-350                            |      | 115   | 71753D9A10 |
| Intel      | Core i5-9300H                    | 2.40 | 115   | FB676E6E3F |
| Intel      | Core i5 M 520                    | 2.40 | 115   | 4A54D7FD48 |
| Intel      | Core i5-7300HQ                   | 2.50 | 114   | 1B93E3C1C9 |
| Intel      | Core i5 M 480                    | 2.67 | 113   | 557421F62E |
| Intel      | Celeron 2955U                    | 1.40 | 113   | 5515480ED0 |
| Intel      | Pentium Dual-Core T4200          | 2.00 | 112   | C0FAA178A2 |
| AMD        | Phenom II X4 955                 |      | 111   | 5E80D808A1 |
| AMD        | Phenom II X4 965                 |      | 111   | 3D18262D97 |
| Intel      | Pentium M processor              | 1.20 | 111   | 61FEA93E97 |
| Intel      | Core i3-4130                     | 3.40 | 111   | AECD71AC63 |
| Intel      | Pentium 4                        | 3.00 | 109   | BB7E656AE8 |
| Intel      | Core i7-4500U                    | 1.80 | 109   | 4BAEB2CAFC |
| Intel      | Celeron N4000                    | 1.10 | 108   | 75C78480D2 |
| Intel      | Core i3-6100U                    | 2.30 | 108   | 60B294879D |
| Intel      | Core 2 Duo E4500                 | 2.20 | 106   | E77852D5C2 |
| Intel      | Core i3-7100                     | 3.90 | 106   | 7E7D21D8AE |
| Intel      | Pentium N3700                    | 1.60 | 106   | 707F27E3E8 |
| AMD        | Ryzen 5 3600X 6-Core             |      | 105   | 9A707E937A |
| Intel      | Pentium P6200                    | 2.13 | 105   | 0D72CF73AC |
| Intel      | Core i7-4600U                    | 2.10 | 105   | FC5E995432 |
| Intel      | Core i5-6400                     | 2.70 | 105   | 783EEAAA01 |
| AMD        | Ryzen 5 5600X 6-Core             |      | 104   | BD63D5E0CB |
| Intel      | Atom N570                        | 1.66 | 104   | 1D2C227997 |
| Intel      | Core i3 M 330                    | 2.13 | 104   | 0BC832BD49 |
| Intel      | Celeron N2830                    | 2.16 | 104   | E6F3F8F6EE |
| AMD        | Ryzen 5 4600H with Radeon Gra... |      | 103   | F581CF8319 |
| Intel      | Core i3-7100U                    | 2.40 | 103   | C9153E029E |
| Intel      | Core i7-7700                     | 3.60 | 103   | FBAA649304 |
| Intel      | Pentium 4                        | 3.20 | 102   | 7E4E158B65 |
| AMD        | Ryzen 5 2600X Six-Core           |      | 101   | 666C41EB03 |
| Intel      | Pentium G630                     | 2.70 | 101   | C4DF2D99FF |
| AMD        | E-300 APU with Radeon HD Grap... |      | 100   | 60D72BDCE7 |
| Intel      | Core 2 Duo E8500                 | 3.16 | 100   | F493A9D83B |
| Intel      | Pentium N3710                    | 1.60 | 100   | 0BA26CCC72 |
| Intel      | Pentium P6100                    | 2.00 | 99    | 6450BA7397 |
| Intel      | Core i3-3240                     | 3.40 | 99    | ECFCF772FB |
| Intel      | Core i3 550                      | 3.20 | 98    | 2FB08CCC03 |
| AMD        | Ryzen 7 3800X 8-Core             |      | 97    | AAC1293B60 |
| Intel      | Core 2 Duo E8400                 | 3.00 | 97    | B0AE6E12C3 |
| AMD        | FX -6100 Six-Core                |      | 96    | 83A2D81E1C |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 95    | EE0FEEEAB4 |
| Intel      | Pentium Dual-Core E5400          | 2.70 | 95    | FFB75356EF |
| Intel      | Atom D525                        | 1.80 | 95    | C7C31F9BCF |
| Intel      | Core i5 750                      | 2.67 | 95    | B14C0E8DD2 |
| Intel      | Core i5-2540M                    | 2.60 | 95    | 3405536413 |
| Intel      | Core i5 M 430                    | 2.27 | 94    | 3861FCE83E |
| Intel      | Core i7-4770K                    | 3.50 | 94    | 6BB186C28B |
| AMD        | A10-4600M APU with Radeon HD ... |      | 93    | 7332DA68EC |
| Intel      | Pentium 4                        | 3.00 | 93    | DC8736B161 |
| Intel      | Core i3-2370M                    | 2.40 | 93    | 923479D039 |
| Intel      | Core i5-4440                     | 3.10 | 93    | 90659E6A34 |
| Intel      | Pentium G4400                    | 3.30 | 93    | 51862605EF |
| Intel      | Core 2 Duo P8700                 | 2.53 | 92    | 22BD0169BD |
| Intel      | Core i7-3632QM                   | 2.20 | 92    | D7E853A51C |
| Intel      | Pentium Dual E2180               | 2.00 | 91    | 5B7FAF1CC6 |
| Intel      | Core i7-10710U                   | 1.10 | 91    | 8ADD857C1A |
| Intel      | Core i5 M 560                    | 2.67 | 91    | BA51FC9216 |
| Intel      | Core i5-3330                     | 3.00 | 91    | FAC95138DC |
| Intel      | Core i3-4160                     | 3.60 | 91    | 54507E44FD |
| Intel      | Core 2 Duo T7500                 | 2.20 | 90    | 34FC60E37E |
| Intel      | Core i3-4030U                    | 1.90 | 90    | 8D5A256374 |
| AMD        | A8-7410 APU with AMD Radeon R... |      | 89    | 65B33599F0 |
| Intel      | Core i3-8100                     | 3.60 | 89    | 79E6EF3655 |
| Intel      | Core 2 Duo T6600                 | 2.20 | 89    | B9D6CE69B0 |
| Intel      | Core 2 Quad Q8300                | 2.50 | 89    | EAA60F7610 |
| AMD        | Athlon II X4 640                 |      | 88    | 07942589AE |
| AMD        | FX -4100 Quad-Core               |      | 88    | 588CEFB67B |
| Intel      | Core 2 Duo E7400                 | 2.80 | 88    | 987E142046 |
| Intel      | Core i7-4710HQ                   | 2.50 | 88    | 739623468A |
| Intel      | Core i5-2320                     | 3.00 | 87    | 8CA4E25242 |
| Intel      | Celeron 1000M                    | 1.80 | 87    | 0790E099FA |
| AMD        | Ryzen 5 3550H with Radeon Veg... |      | 86    | 9B0872B3D4 |
| Intel      | Core i7-3520M                    | 2.90 | 86    | F37394899F |
| AMD        | C-60 APU with Radeon HD Graphics |      | 85    | 95653B7969 |
| Intel      | Pentium G3220                    | 3.00 | 85    | D7C89A5F6A |
| Intel      | Core i7-5600U                    | 2.60 | 85    | FFB40F821B |
| AMD        | A6-6310 APU with AMD Radeon R... |      | 84    | 0B2EC748F2 |
| Intel      | Core i5-2300                     | 2.80 | 84    | 679674342A |
| Intel      | Pentium B950                     | 2.10 | 84    | 70CB0EACD3 |
| Intel      | Pentium Silver N5000             | 1.10 | 83    | D08EFA2EF3 |
| Intel      | Core 2 Duo E6750                 | 2.66 | 83    | 37766217AE |
| Intel      | Core i5-6600K                    | 3.50 | 83    | 9C608040D6 |
| Intel      | Core i3-8130U                    | 2.20 | 82    | AF67B942EC |
| Intel      | Core i5 760                      | 2.80 | 82    | 85E49E67CA |
| AMD        | Ryzen 7 1700X Eight-Core         |      | 81    | 2E4C1C4527 |
| AMD        | Ryzen 9 3950X 16-Core            |      | 81    | 161865EDB0 |
| AMD        | Ryzen 3 3200U with Radeon Veg... |      | 81    | 8DB63E7A74 |
| Intel      | Core 2 Duo T7250                 | 2.00 | 81    | B6302B710D |
| Intel      | Pentium Dual E2200               | 2.20 | 81    | 35D876D2DC |
| Intel      | Core 2 T7200                     | 2.00 | 81    | E402A0B407 |
| Intel      | Core i5-7500                     | 3.40 | 81    | E221C43AF2 |
| Intel      | Celeron E3400                    | 2.60 | 81    | 555BB7179C |
| Intel      | Pentium D                        | 3.20 | 80    | 692C125EA1 |
| Intel      | Pentium G620                     | 2.60 | 80    | 1005EC2531 |
| Intel      | Core 2 Duo T5750                 | 2.00 | 79    | 89842BEC44 |
| Intel      | Core i3 540                      | 3.07 | 79    | 02DFFBFEA8 |
| Intel      | Atom x5-Z8300                    | 1.44 | 79    | C17C589AF5 |
| Intel      | Core i5-8350U                    | 1.70 | 78    | 4EFDBAEEA5 |
| Intel      | Pentium Dual E2160               | 1.80 | 78    | 4E574A8988 |
| Intel      | Core i7 Q 720                    | 1.60 | 78    | 13796B8E87 |
| Intel      | Core i5-3450                     | 3.10 | 78    | FAF35CB112 |
| AMD        | Athlon 64 X2 Dual Core 6000+     |      | 77    | C31D447213 |
| Intel      | Core i7-2620M                    | 2.70 | 77    | E72B8E6BA0 |
| Intel      | Core i3-4170                     | 3.70 | 77    | 3AEEEBEB96 |
| Intel      | Core i5-4670K                    | 3.40 | 77    | F6DE3176E5 |
| Intel      | Core i3-4010U                    | 1.70 | 77    | DC154FE7C0 |
| AMD        | E1-1200 APU with Radeon HD Gr... |      | 76    | 553A61003F |
| Intel      | Core i7-8850H                    | 2.60 | 76    | C625F457A9 |
| AMD        | A8-4500M APU with Radeon HD G... |      | 75    | 261221A1DA |
| Intel      | Core 2 Duo E7300                 | 2.66 | 75    | F00A0A0903 |
| Intel      | Core i3-4000M                    | 2.40 | 75    | 532FD196D0 |
| AMD        | Ryzen 5 1600X Six-Core           |      | 74    | F17090E5D2 |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Probe      |
|------------|------------------------------|----------|------|------|-------|------------|
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 662   | 045B2CD511 |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 606   | 70EE05A53E |
|            | Module DIMM SDRAM            | 2048 MB  |      |      | 591   | 28E9F5E95F |
| Samsung    | M471A5244CB0-CTD SODIMM      | 4096 MB  | DDR4 | 3266 | 560   | F1941A09E5 |
|            | Module DIMM                  | 2048 MB  |      | 800  | 546   | 45661425FF |
| SK Hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2667 | 538   | 66255CA7B5 |
|            | Module DIMM                  | 4096 MB  |      | 1333 | 537   | 5E80D808A1 |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 534   | DBF0FD04C3 |
|            | Module DIMM                  | 2048 MB  |      | 1333 | 496   | 37ADE7DACF |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 488   | 50B1B1A6C5 |
|            | Module DIMM SDRAM            | 1024 MB  |      |      | 480   | 3A064BDF05 |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4096 MB  | DDR3 | 1334 | 461   | 90895AAB86 |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4096 MB  | DDR4 | 2667 | 425   | C9153E029E |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 391   | A7CC3183F2 |
|            | Module DIMM                  | 1024 MB  | DDR2 | 800  | 365   | B978BE9281 |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2048 MB  | DDR3 | 4199 | 344   | F442DF91A1 |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 337   | 707F27E3E8 |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1600 | 337   | 045B2CD511 |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 336   | DBBFDA6004 |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 336   | 69A252CCD6 |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8192 MB  | DDR4 | 2667 | 324   | 9C8BB9558A |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 304   | A120083D3C |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8192 MB  | DDR4 | 2667 | 298   | 2A2CFDB7D4 |
|            | Module DIMM                  | 1024 MB  |      | 800  | 287   | 0614D7CBFC |
|            | Module DIMM                  | 1024 MB  | DDR2 | 667  | 286   | A6574237D6 |
|            | Module SODIMM                | 2048 MB  | DDR2 |      | 284   | 06C3B56836 |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1333 | 282   | 7A6881C4BE |
|            | Module DIMM                  | 2048 MB  | DDR2 | 667  | 265   | A6574237D6 |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 262   | 2DB4EBB6EF |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 259   | FFB40F821B |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8192 MB  | DDR4 | 2667 | 252   | A01E524A66 |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8 GB     | DDR3 | 2667 | 248   | FB61A77E5C |
|            | Module SODIMM                | 1024 MB  | DDR2 |      | 241   | 57043D09FE |
| SK Hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2667 | 235   | F3511CB0AA |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4096 MB  | DDR3 | 2400 | 234   | BF66E1D281 |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 231   | 8D45D9544E |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 229   | 3CDC08297E |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3600 | 226   | 667289D1B9 |
| SK Hynix   | HMT41GS6BFR8A-PB SODIMM      | 8192 MB  | DDR3 | 1600 | 225   | 22A87CB141 |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4096 MB  | DDR3 | 1334 | 221   | C6E87F1FB7 |
|            | Module SODIMM                | 1024 MB  | DDR2 | 667  | 221   | EE90608B54 |
|            | Module SODIMM                | 4096 MB  | DDR3 |      | 219   | 1D79ED8874 |
| SK Hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 213   | 2C6C86B1FB |
| Samsung    | M471B5673FH0-CH9 SODIMM      | 2048 MB  | DDR3 | 1334 | 210   | 1427EBFFB0 |
|            | Module DIMM                  | 2048 MB  |      | 667  | 209   | F00A0A0903 |
| SK Hynix   | HMA81GS6JJR8N-VK SODIMM      | 8192 MB  | DDR4 | 2667 | 200   | 22728E37FE |
|            | 123456789012345678 SODIMM    | 2048 MB  | DDR3 | 2400 | 198   | CAB2BCC5EE |
|            | Module DIMM                  | 4096 MB  |      | 1600 | 198   | BC7ED68945 |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 198   | 6EE47924BD |
|            | Module DIMM                  | 1024 MB  |      | 667  | 196   | F00A0A0903 |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8192 MB  | DDR3 | 1600 | 191   | 127B977658 |
| Kingston   | KHX1600C10D3/8G DIMM         | 8192 MB  |      | 1867 | 190   | 0420EDF711 |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     | DDR3 | 1334 | 189   | 387EE22BC4 |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 185   | 18F27D1F5C |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3466 | 183   | 64E97DEBA6 |
| SK Hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 183   | 0AD916110D |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4096 MB  | DDR3 | 1600 | 181   | C4C890F06A |
|            | Module DIMM                  | 2048 MB  | DDR3 | 1333 | 180   | 7A6881C4BE |
|            | Module DIMM                  | 2048 MB  |      | 400  | 174   | 45661425FF |
| Micron     | 8ATF1G64HZ-2G6E1 SODIMM      | 8192 MB  | DDR4 | 2667 | 167   | D55AC505B9 |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 167   | 0279A35638 |
|            | Module DIMM SDRAM            | 512 MB   |      |      | 166   | 608CB84FBB |
|            | Module DIMM                  | 1024 MB  |      |      | 162   | ED7C7AB87D |
| SK Hynix   | HMA41GS6AFR8N-TF SODIMM      | 8192 MB  | DDR4 | 2667 | 159   | 64F2D60B7E |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 155   | 60D72BDCE7 |
| SK Hynix   | H9CCNNNCLGALAR-NVD Row Of... | 8192 MB  |      | 2133 | 149   | 8956FEE2F3 |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     |      | 1867 | 145   | 1161AF8368 |
| Micron     | 4ATF51264HZ-2G3B1 SODIMM     | 4096 MB  | DDR4 | 2400 | 141   | 06114B7EB7 |
| Nanya      | NT4GC64B8HB0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 141   | 1217A94F61 |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1600 | 140   | 33D5096A54 |
| Micron     | 8ATF1G64HZ-3G2J1 SODIMM      | 8 GB     | DDR4 | 3200 | 139   | DA5E2F59CC |
| SK Hynix   | HMT351S6EFR8A-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 138   | E1E44B58F3 |
|            | Module DIMM DDR              | 2048 MB  |      | 1333 | 138   | 85E49E67CA |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 136   | 32F01CCAAB |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16384 MB | DDR4 | 2667 | 135   | 2AD271E81F |
| Samsung    | M471B5273CH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 135   | F37394899F |
| 48spaces   | 0123456789012345678901234... | 2048 MB  | DDR2 | 667  | 134   | D66EBD7A47 |
| Samsung    | M471B5773DH0-CK0 SODIMM      | 2 GB     | DDR3 | 1600 | 133   | 13D221E327 |
| SK Hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 132   | 33CEC7AE6F |
| SK Hynix   | HMT325S6BFR8C-H9 SODIMM      | 2048 MB  | DDR3 | 1600 | 132   | 5B2D90A434 |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 3200 | 129   | 24974BE67E |
| SK Hynix   | HMA82GS6JJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 128   | DEA3395C5A |
|            | Module SODIMM                | 2048 MB  | DDR2 | 800  | 126   | C8F8ADC564 |
| Elpida     | EBJ40UG8BBU0-GN-F SODIMM     | 4 GB     | DDR3 | 1600 | 125   | 562BD81383 |
|            | Module DIMM                  | 4096 MB  |      | 400  | 125   | F365061248 |
| Kingston   | 99U5584-005.A00LF DIMM       | 4096 MB  | DDR3 | 1600 | 124   | A223391BC0 |
|            | Module DIMM                  | 2048 MB  |      | 1066 | 124   | 4C78E0CB2B |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8192 MB  | DDR4 | 3200 | 124   | F5385D6B10 |
| Samsung    | M471B5674QH0-YK0 SODIMM      | 2 GB     | DDR3 | 1600 | 124   | D04BD787B3 |
| Micron     | 16JSF51264HZ-1G4D1 SODIMM    | 4096 MB  |      | 1334 | 123   | 15CE74DCD6 |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1333 | 123   | 3871A3C4FC |
| SK Hynix   | HYMP125S64CP8-S6 SODIMM      | 2 GB     | DDR2 | 975  | 122   | C0FAA178A2 |
|            | Module SODIMM DDR            | 1024 MB  |      |      | 121   | 61FEA93E97 |
|            | Module DIMM                  | 1024 MB  | DDR2 |      | 121   | D8875918AC |
| Elpida     | EBJ21UE8BFU0-DJ-F SODIMM     | 2 GB     | DDR3 | 1334 | 120   | D7893B2025 |
| Samsung    | M471A2K43DB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 120   | 3517455DF5 |
| SK Hynix   | HMT351S6CFR8C-H9 SODIMM      | 4096 MB  | DDR3 | 1334 | 119   | F5112DBF47 |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8192 MB  | DDR3 | 1600 | 118   | 00E8B6E3FD |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 117   | 3CDDE1061C |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 116   | 2F027FCBC2 |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 3200 | 116   | 27E29303BC |
|            | Module DIMM                  | 1024 MB  | DDR2 | 333  | 116   | 0A4D7FB95D |
|            | Module SODIMM DRAM           | 1024 MB  |      |      | 116   | 392BE37A79 |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 115   | D520F23D4E |
| Kingston   | KHX2400C15/8G DIMM           | 8192 MB  | DDR4 | 2933 | 115   | C408319996 |
| Nanya      | NT4GC64B8HG0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 115   | 4BEA60D049 |
| Micron     | 8JSF25664HZ-1G4D1 SODIMM     | 2 GB     | DDR3 | 1334 | 114   | E92D8556E9 |
|            | Module SODIMM SDRAM          | 2048 MB  |      |      | 114   | B8C2DF18DB |
| Kingston   | 99U5471-012.A00LF DIMM       | 4096 MB  | DDR3 | 1600 | 113   | 6CEE757CF0 |
| SK Hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2667 | 112   | 4EFDBAEEA5 |
| ELPIDA     | EBJ21UE8BDS0-DJ-F SODIMM     | 2 GB     | DDR3 | 1334 | 110   | 11329DED30 |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8 GB     | DDR3 | 1600 | 110   | 070723F36C |
| SK Hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 1600 | 109   | BBED87466A |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 109   | DD20DE340C |
|            | Module DIMM                  | 2048 MB  | DDR2 |      | 108   | 13134022DF |
| Ramaxel    | RMT3160ED58E9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 108   | 986BA47618 |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4096 MB  | DDR3 | 1600 | 108   | DD513D338C |
| SK Hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1800 | 107   | F17F22EFDC |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8192 MB  | DDR4 | 3533 | 107   | A33E68304F |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4096 MB  | DDR4 | 3200 | 106   | 0071FAABAC |
|            | Module DIMM SDRAM            | 4096 MB  |      |      | 106   | 1B80FF1B5A |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1600 | 106   | B62359FCB1 |
| Kingston   | KHX1600C10D3/4G DIMM         | 4096 MB  | DDR3 | 1866 | 105   | 5E6E002DD7 |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8 GB     | DDR4 | 3200 | 105   | 8D45D9544E |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16384 MB | DDR4 | 3600 | 104   | 27B0A66CEB |
|            | Module SODIMM                | 2048 MB  | DDR3 |      | 104   | FFAE60B13A |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 104   | 7F8E6D2DA9 |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8 GB     | DDR4 | 3200 | 103   | 93EC7F3964 |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 103   | C4C890F06A |
| SK Hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 102   | 9AACCAF459 |
| SK Hynix   | HMT41GS6AFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 102   | B4C3816A33 |
| Samsung    | M471B2873FHS-CH9 SODIMM      | 1024 MB  | DDR3 | 1334 | 102   | F696958F46 |
| SK Hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 101   | 905FCE5118 |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3400 | 100   | FBD2076EEE |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 100   | 1B9BEEAF2D |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4096 MB  | DDR3 | 2133 | 100   | F7EE091AE1 |
| SK Hynix   | HMT325S6CFR8C-PB SODIMM      | 2 GB     | DDR3 | 1600 | 99    | 91787044C1 |
| Kingston   | 99U5471-020.A00LF DIMM       | 4096 MB  | DDR3 | 1600 | 99    | 9F4091C7EE |
| Kingston   | ACR256X64D3S1333C9 SODIMM    | 2 GB     | DDR3 | 1334 | 99    | 387EE22BC4 |
|            | Module DIMM                  | 2048 MB  | DDR2 | 333  | 98    | 0A4D7FB95D |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1333 | 98    | F5112DBF47 |
|            | Module DIMM                  | 4 GB     |      | 1333 | 98    | 6CA4F46D1B |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8192 MB  | DDR4 | 2133 | 98    | B67458A3DA |
| Samsung    | M471B5273EB0-CK0 SODIMM      | 4096 MB  | DDR3 | 4199 | 98    | D5CF70DB0C |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2 GB     | DDR3 | 4199 | 98    | D9521929DA |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 97    | 3BD9604AE7 |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 97    | A89ECD0B5F |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 96    | A2AEE507A3 |
| Micron     | MT52L1G32D4PG-093 Row Of ... | 8 GB     |      | 2133 | 96    | 68C01947C9 |
| Ramaxel    | RMT3170EB68F9W1600 SODIMM    | 4096 MB  | DDR3 | 1600 | 96    | D064F3DA02 |
| SK Hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 96    | 744799A3C4 |
| SK Hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 95    | 0C3651AF28 |
|            | Module SODIMM SDRAM          | 1024 MB  |      |      | 95    | FFB279A366 |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1867 | 95    | B62359FCB1 |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1600 | 93    | B976BAC417 |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 93    | 8C2D9E608C |
|            | Module DIMM                  | 2048 MB  |      |      | 92    | 3D26775340 |
| SK Hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 92    | 69B1B6E13E |
| SK Hynix   | HMT325S6BFR8C-H9 SODIMM      | 2048 MB  | DDR3 | 1333 | 91    | 3405536413 |
| SK Hynix   | HMT351S6EFR8C-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 90    | EAF1BB2C45 |
| Ramaxel    | RMSA3270ME86H9F-2666 SODIMM  | 4 GB     | DDR4 | 2667 | 90    | 3B7BF6FDEB |
| Samsung    | M4 70T5663QZ3-CF7 SODIMM     | 2048 MB  | DDR2 | 2048 | 90    | CE99148B7C |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8192 MB  | DDR3 | 1600 | 89    | 88785336BA |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1333 | 89    | 68530FD616 |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2048 MB  | DDR3 | 1333 | 89    | 27E84ACA95 |
| Samsung    | M471A5244BB0-CRC SODIMM      | 4096 MB  | DDR4 | 2667 | 89    | 75C78480D2 |
| Samsung    | Module SODIMM                | 16384 MB | DDR4 | 2667 | 89    | A814284F0B |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1600 | 87    | E693A453B1 |
| Kingston   | KHX1866C10D3/4G DIMM         | 8 GB     | DDR3 | 1866 | 86    | C401DCDEB5 |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 86    | A1F9398A77 |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 86    | 905FCE5118 |
| A-DATA     | AD73I1C1674EV SODIMM         | 4096 MB  | DDR3 | 1334 | 84    | 2173E84F13 |
| Kingston   | ACR16D3LS1KFG/4G SODIMM      | 4 GB     | DDR3 | 1600 | 84    | 0B2EC748F2 |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 84    | FBA59C709D |
|            | Module SODIMM                | 512 MB   | DDR2 |      | 83    | 1517AC0D45 |
|            | Module DIMM                  | 4096 MB  |      | 667  | 82    | 9268BDA6A2 |
|            | Module DIMM                  | 8192 MB  |      | 1333 | 82    | 6616FE6BB8 |
| SK Hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 82    | 889499B855 |
|            | Module DIMM                  | 512 MB   |      |      | 81    | D2B8571B71 |
| Samsung    | M471A5244CB0-CTD Row Of C... | 4 GB     | DDR4 | 2667 | 81    | 6F6E5DAF18 |
|            | Module DIMM DDR              | 2048 MB  |      | 800  | 80    | 7FD3BA10D1 |
|            | Module DIMM                  | 2 GB     |      | 800  | 80    | 4C574D3F41 |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 80    | CE2C332B33 |
|            | Module DIMM                  | 4096 MB  |      | 1066 | 80    | 43C0756BA6 |
| SK Hynix   | HMA851S6JJR6N-VK SODIMM      | 4096 MB  | DDR4 | 2667 | 79    | 2A54689FB3 |
| Samsung    | M4 70T5663EH3-CF7 SODIMM     | 2 GB     | DDR2 |      | 78    | E84CD86EB0 |
| Samsung    | M471A1K43BB1-CTD SODIMM      | 8192 MB  | DDR4 | 2667 | 78    | A01E524A66 |
| Samsung    | M471A2G44AM0-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 78    | 273A5FF27D |
| Nanya      | NT4GC64B8HG0NS-DI SODIMM     | 4 GB     | DDR3 | 1600 | 77    | 13D221E327 |
|            | Module DIMM                  | 2048 MB  | DDR2 | 400  | 77    | C96A2AA7A8 |
| Samsung    | M471B2873FHS-CF8 SODIMM      | 1024 MB  | DDR3 | 1067 | 77    | 18F27D1F5C |
| Ramaxel    | RMT3170ME68F9F1600 SODIMM    | 4096 MB  | DDR3 | 1600 | 76    | 58CC91ABA3 |
| Kingston   | KHX1600C10D3/8GX DIMM        | 8192 MB  | DDR3 | 1600 | 75    | 9E2D96B5B6 |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1600 | 75    | 6121781D85 |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4096 MB  | DDR3 | 1600 | 75    | D4C089BC2F |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 75    | 2F027FCBC2 |
| Ramaxel    | RMT3020EC58E9F1333 SODIMM    | 4 GB     | DDR3 | 4199 | 74    | 6074680FBA |
|            | 123456789012345678 DIMM      | 1 GB     | DDR3 | 2400 | 73    | C87DFAAC1F |
|            | Module DIMM                  | 1024 MB  |      | 400  | 73    | 7BCB8565D4 |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 72    | 235E8C9537 |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4 GB     | DDR3 | 1600 | 72    | 858657E291 |
|            | Module SODIMM                | 2048 MB  |      | 800  | 72    | 3BBEC8B8FD |
| Samsung    | M471B5173BH0-YK0 SODIMM      | 4096 MB  | DDR3 | 1600 | 72    | 553A61003F |
| Samsung    | M471B5273CH0-YK0 SODIMM      | 4096 MB  | DDR3 | 1600 | 72    | E07ABB010E |
| Crucial    | CT51264BA160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 71    | CFDD30C7C7 |
| SK Hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 71    | B754C74B11 |
| Kingston   | 99U5428-063.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 71    | 7332DA68EC |
|            | Module SODIMM DRAM           | 2048 MB  |      |      | 71    | 8AE1EA1D6B |
| SK Hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 71    | BB444038CF |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 70    | 3A14292469 |
| Micron     | 8ATF1G64HZ-2G3B1 SODIMM      | 8 GB     | DDR4 | 2400 | 70    | 84CEEEACF1 |
|            | Module DIMM DDR              | 4096 MB  |      | 1333 | 70    | 8A6B85A2D2 |
| Samsung    | K4EBE304EB-EGCG Row Of Ch... | 8 GB     |      | 2133 | 70    | 2B4A1A20D9 |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4096 MB  | DDR3 | 1866 | 70    | 0D05812341 |
| A-DATA     | AD73I1C1674EV SODIMM         | 4 GB     | DDR3 | 1334 | 69    | D8167A915B |
| Kingston   | KHX3200C16D4/16GX DIMM       | 16384 MB | DDR4 | 3600 | 69    | 1E61CC1252 |
| Samsung    | Module SODIMM                | 8192 MB  | DDR4 | 2133 | 69    | 436E9BF227 |
| SK Hynix   | HMT351U6CFR8C-H9 DIMM        | 4096 MB  | DDR3 | 1600 | 68    | E4CB18707B |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 68    | BCC27223CC |
| Samsung    | Module Row Of Chips LPDDR3   | 8192 MB  |      | 2133 | 68    | 2A1930C4E4 |
| Corsair    | CMK16GX4M2A2666C16 DIMM      | 8 GB     | DDR4 | 3200 | 67    | 84EF17B3A6 |
| Kingston   | 99U5474-028.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 67    | 69DA26C946 |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4096 MB  | DDR4 | 2133 | 67    | 6D2D97674C |
| SK Hynix   | HMT451U6AFR8C-PB DIMM        | 4096 MB  | DDR3 | 1600 | 66    | 6CEE757CF0 |
| Kingston   | KHX2666C15S4/16G SODIMM      | 16 GB    | DDR4 | 2667 | 66    | FBE1D68B82 |
| Nanya      | NT2GC64B88G0NS-CG SODIMM     | 2 GB     | DDR3 | 1600 | 66    | 3518FEB297 |
| SK Hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 66    | 3A0E961B45 |
| SK Hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2400 | 65    | 99FC59557A |
| Kingston   | ACR16D3LFS1KBG/2G SODIMM     | 2 GB     | DDR3 | 1600 | 65    | 216D1DA088 |
| Micron     | 16JSF25664HZ-1G1F1 SODIMM    | 2048 MB  | DDR3 | 1067 | 65    | 610E2BA453 |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 65    | D342F4E0A4 |
|            | Module DIMM                  | 512 MB   | DDR2 | 667  | 65    | 585BFD5E2A |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4096 MB  | DDR3 | 1867 | 65    | 625A58F05C |
| Samsung    | Module SODIMM                | 2 GB     | DDR3 | 1600 | 65    | 5B47E8EFCB |
| SK Hynix   | HMA851S6JJR6N-VK SODIMM      | 4096 MB  | DDR4 | 2667 | 64    | 28930B356E |
|            | Module SODIMM                | 1024 MB  | DDR2 | 533  | 64    | 3A627AAB0A |
|            | Module SODIMM                | 2048 MB  |      | 667  | 64    | 1A2D7BC306 |
| SK Hynix   | HMT41GS6BFR8A-PB SODIMM      | 8192 MB  | DDR3 | 1600 | 64    | D2E08434A9 |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 63    | 588CEFB67B |
| SK Hynix   | HMA851S6CJR6N-VK Row Of C... | 4 GB     | DDR4 | 2667 | 62    | 1310B8ABF4 |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 62    | A72AAD9B00 |
| Kingston   | KHX2133C14/8G DIMM           | 8 GB     | DDR4 | 2400 | 61    | 77006702F8 |
| Elpida     | Module SODIMM                | 4096 MB  | DDR3 | 1600 | 60    | 23B984DCC7 |
| Ramaxel    | RMT3010EC58E8F1333 SODIMM    | 2 GB     | DDR3 | 1600 | 60    | 5038083B91 |
| Corsair    | CMX8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1800 | 59    | D04DAE2A56 |
| Crucial    | CT8G4SFS824A.M8FE SODIMM     | 8 GB     | DDR4 | 2667 | 59    | CAD3A5EB69 |
| Kingston   | KHX2400C14S4/16G SODIMM      | 16 GB    | DDR4 | 2667 | 59    | 9403539ACC |
|            | Module DIMM                  | 2 GB     |      | 1333 | 59    | 02DFFBFEA8 |
| SK Hynix   | HMT451S6MFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 59    | D74C10F41F |
| Nanya      | NT2GC64B8HC0NS-CG SODIMM     | 2048 MB  | DDR3 | 1334 | 58    | D4BCC9A744 |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe      |
|------------|----------------|-------|---------|-------|------------|
| ASUSTek    | ASUS           | 33.2  | Li-ion  | 1280  | 32F01CCAAB |
| Hewlett... | PABAS0241231   | 41.0  | Li-ion  | 633   | 5F67B298AB |
| Compal     | PABAS0241231   | 57.7  | Li-ion  | 624   | 75C78480D2 |
| Lenovo     | PABAS0241231   | 45.0  | Li-ion  | 555   | 5154E96ABE |
| Samsung    |                | 49    | Li-ion  | 382   | A83E302ABA |
| SMP        | bq20z451       | 71.8  | Li-ion  | 324   | 6E17FB6EA4 |
| MSI        | BIF0_9         | 53.2  | Li-ion  | 288   | 4BF23FF82D |
| SANYO      | Li_Ion_4000mA  | 48.8  | Li-ion  | 262   | 1217A94F61 |
| Hewlett... | Primary        | 48    | Li-ion  | 243   | E84CD86EB0 |
| SMP        | DELL GPM0365   | 97.0  | Li-ion  | 235   | E68FF3079C |
| Hewlett... | Primary        | 45    | Li-ion  | 233   | 87B3274937 |
| Intel SR 1 | SR Real        | 57.7  |         | 232   | 6121781D85 |
| OEM        | standard       | 32.6  | Li-ion  | 224   | B198944AD7 |
| Hewlett... | Primary        | 40    | Li-ion  | 178   | 1719B2DC9D |
| Hewlett... | Primary        | 44    | Li-ion  | 177   | 1069B24865 |
| LG         | PABAS0241231   | 48.9  | Li-ion  | 176   | 3D54291DE2 |
| Samsung    | SR Real        | 43.1  | Li-ion  | 174   | 95C381CCD9 |
| Samsung    |                | 44    | Li-ion  | 165   | 6BB3A162B5 |
| Notebook   | BAT            | 49    | Li-ion  | 164   | A6732AB721 |
| Hewlett... | Primary        | 42    | Li-ion  | 159   | 0071FAABAC |
| SANYO      | 45N1773        | 23.2  | Li-ion  | 147   | 92FB8505AA |
| ASUSTek    | X550A26        | 38.0  | Li-ion  | 145   | 50B1B1A6C5 |
| DP         | bq20z451       | 74.9  | Li-ion  | 142   | ECC4515014 |
| ASUSTek    | A32-K55        | 64.4  | Li-ion  | 139   | 22728E37FE |
| Hewlett... | Primary        | 41    | Li-ion  | 138   | A0A111A38E |
| Hewlett... | Primary        | 39    | Li-ion  | 131   | B754C74B11 |
| SANYO      | AL10B31        | 48.8  | Li-ion  | 129   | E12C8838C3 |
| Hewlett... | Primary        | 43    | Li-ion  | 127   | 65EC913842 |
| SMP        | L16M2PB1       | 30.0  | Li-poly | 127   | 8948989999 |
| SANYO      | PABAS0241231   | 28.5  | Li-ion  | 126   | 8C4669BE5C |
| LGC        | 45N1127        | 23.5  | Li-ion  | 122   | 92FB8505AA |
| Hewlett... | Primary        | 38    | Li-ion  | 121   | 9347A8D008 |
| PANASONIC  | Li_Ion_4000mA  | 47.5  | Li-ion  | 120   | D74C10F41F |
| SANYO      | AL12A32        | 37.0  | Li-ion  | 118   | 7302DC6BE1 |
| LG         | Li_Ion_4000mA  | 47.5  | Li-ion  | 114   | D2A5CA4ACA |
| Hewlett... | Primary        | 46    | Li-ion  | 112   | 46392181D6 |
| SIMPLO     | PABAS0241231   | 35.0  | Li-ion  | 111   | BF5D74D554 |
| Hewlett... | Primary        | 36    | Li-ion  | 105   | 5BB4E443F9 |
| ASUSTek    | K52F-44        | 48.4  | Li-ion  | 103   | 0D72CF73AC |
| Hewlett... | Primary        | 50    | Li-ion  | 102   | A814284F0B |
| SMP        | DELL G8VCF6C   | 52.0  | Li-poly | 102   | 8956FEE2F3 |
| SANYO      | AL15A32        | 37.0  | Li-ion  | 99    | 216D1DA088 |
| SANYO      | AS10D31        | 47.5  | Li-ion  | 99    | 1427EBFFB0 |
| ASUSTek    | F82--22        | 48.4  | Li-ion  | 98    | DBBFDA6004 |
| Hewlett... | Primary        | 49    | Li-ion  | 98    | 69FC64DF8B |
| Samsung    |                | 48    | Li-ion  | 96    | 103EDB36D2 |
|            | Battery        |       |         | 94    | D70E2B74D0 |
| SANYO      | 45N1775        | 23.2  | Li-ion  | 93    | 0151EADF78 |
| SANYO      | GC86508SAT0    | 73.3  | Li-ion  | 93    | 64B6992B74 |
| Hewlett... | Primary        | 37    | Li-ion  | 91    | A7CC3183F2 |
| Hewlett... | Primary        | 53    | Li-ion  | 90    | 713C29AA23 |
| SANYO      | PABAS024       | 38.9  | Li-ion  | 89    | A0FF38D606 |
| PANASONIC  | AP16M5J        | 37.0  | Li-ion  | 88    | E8B00FA29B |
| Hewlett... | Primary        |       | Li-ion  | 87    | 1E89CEC8EB |
| LGC        | 45N1049        | 40.4  | Li-ion  | 87    | 231E5AFD60 |
| ASUSTek    | X550A30        | 31.7  | Li-ion  | 85    | BBED87466A |
| SMP        | DELL Y3F7Y6B   | 42.0  | Li-ion  | 85    | BEB9349C6E |
| LGC        | AC14B8K        | 48.9  | Li-ion  | 83    | 55A32EF8DC |
| Notebook   | BAT            | 62    | Li-ion  | 83    | EC41EEB7C0 |
| SANYO      | 00323341343... | 559.4 | Li-ion  | 83    | B967DF63CE |
| Sony       | VGP-BPS26      | 45.0  | Li-ion  | 83    | 11EF4D4BAF |
| Hewlett... | Primary        | 56    | Li-ion  | 80    | 3F5DD495D5 |
| CPT-COS    | L16C2PB2       | 30.6  | Li-poly | 79    | 2BF6813AD9 |
| Hewlett... | Primary        | 47    | Li-ion  | 79    | CECD552E89 |
| LGC        | L16L2PB2       | 30.0  | Li-poly | 79    | 374E69046B |
| Hewlett... | Primary        | 35    | Li-ion  | 76    | B67C01F6E2 |
| Sony       | 45N1111        | 23.2  | Li-poly | 76    | C8F2959FDC |
| TKBSS      | NS2P3SZMC4WR   | 48.4  | Li-ion  | 76    | 37B87B5C45 |
| Samsung    |                | 58    | Li-ion  | 74    | 70CB0EACD3 |
| LG         | PABAS024       | 40.0  | Li-ion  | 73    | B16CB4D0DC |
| PANASONIC  | AS16A5K        | 41.4  | Li-ion  | 73    | A03FC24624 |
| ASUSTek    | K55--44        | 49.5  | Li-ion  | 72    | 953078DDF4 |
| Hewlett... | Primary        | 55    | Li-ion  | 71    | EC02A5333B |
|            | 47.52          | 48    | Li-ion  | 70    | 087FC97D07 |
| Hewlett... | Primary        | 32    | Li-ion  | 68    | B703149715 |
| Hewlett... | Primary        | 28    | Li-ion  | 67    | 1014243935 |
| Hewlett... | Primary        | 34    | Li-ion  | 67    | 7AA667BA1A |
| ASUSTek    | X555-50        | 37.3  | Li-ion  | 65    | A08DA25590 |
| LG         | 004B3842343... | 48.9  | Li-ion  | 65    | AF67B942EC |
| ASUSTek    | K53--52        | 57.2  | Li-ion  | 64    | C98E6E26CE |
| Hewlett... | Primary        | 30    | Li-ion  | 63    | 27D7E6D461 |
| LGC        | 5B10W139       | 50.5  | Li-poly | 63    | 273A5FF27D |
| SMP        | L16M2PB2       | 35.0  | Li-poly | 62    | FF8C85568E |
| LGC        | AC14B18J       | 36.7  | Li-ion  | 61    | 8F1DD3CE3A |
| SANYO      | GRAPE32        | 44.4  | Li-ion  | 59    | 1889E6A3BA |
| Sony       | Li_Ion_4000mA  | 47.5  | Li-ion  | 59    | 2B132C74B6 |
| ASUSTek    | F3---24        | 51.3  | Li-ion  | 58    | 843C7A8519 |
| LGC        | AP18C8K        | 48.0  | Li-ion  | 58    | 1E4856A770 |
| Hewlett... | 5600           | 62.2  |         | 56    | 045B2CD511 |
| Lenovo     | BASE-BAT       | 30.0  | Li-poly | 56    | 8735C1E718 |
| LGC        | 45N1113        | 23.5  | Li-ion  | 56    | E02C35310A |
| SANYO      | 45N1001        | 47.5  | Li-ion  | 56    | B36A94241D |
| SMP        | 01AV447        | 45.7  | Li-poly | 56    | BA847BC0C4 |
| Hewlett... | Primary        | 29    | Li-ion  | 55    | F66BA65DC8 |
| ASUSTek    | N56--52        | 57.2  | Li-ion  | 54    | 7332DA68EC |
| Celxpert   | 01AV448        | 45.7  | Li-poly | 54    | 204598F27D |
| Hewlett... | Primary        | 89    | Li-ion  | 54    | 1410381A3D |
| SMP        | DELL TP1GT61   | 60.0  | Li-poly | 54    | 8BB0307157 |
| ASUSTek    | F5---22        | 47.3  | Li-ion  | 53    | CD0276A1E8 |
| Hewlett... | Primary        | 31    | Li-ion  | 53    | 0646FC1739 |
| SMP        | 01AV421        | 24.0  | Li-poly | 53    | EA23D24F90 |
| ASUSTek    | UX31-35        | 50.6  | Li-ion  | 51    | 62CE68EDEF |
| Lenovo ... |                | 28    |         | 51    | 60E3FE1197 |
| LGC        | AP18E8M        | 57.5  | Li-ion  | 51    | F581CF8319 |
| Notebook   | BAT            | 48    | Li-ion  | 51    | 435743B201 |
| SANYO      | 45N1043        | 38.9  | Li-ion  | 51    | 779684E41D |
| Sony       |                | 42    | Li-ion  | 51    | 2AF79BA873 |
| ASUSTek    | K53--27        | 37.8  | Li-ion  | 50    | 3C199F4247 |
| CPT-COS    | L17C4PB0       | 45.5  | Li-poly | 50    | 8272A05168 |
| Hewlett... | Primary        | 27    | Li-ion  | 50    | 1A6FF4210F |
| Samsung    |                | 24    | Li-ion  | 50    | EB98AC12A4 |
| SANYO      | L09S6Y02       | 38.9  | Li-ion  | 50    | F305E4AB46 |
| Notebook   | BAT            | 53    | Li-ion  | 49    | 1BB63BE9B2 |
| SMP        | DELL VN3N047   | 41.4  | Li-ion  | 49    | 2C2761E770 |
| Hewlett... | Primary        | 41    | Li-ion  | 48    | A56C0A6B4D |
| Lenovo     |                | 28    |         | 47    | 4E11B29D08 |
|            | 48.6           | 49    | Li-ion  | 46    | 070723F36C |
| ASUSTek    | X453-42        | 29.4  | Li-ion  | 46    | 4A70424B2F |
| LGC        | 45N1025        | 62.2  | Li-ion  | 46    | 2139D7269B |
| Simplo     | SDI ICR18650   | 48.2  | Li-ion  | 46    | 8A5F05E4C1 |
| ASUSTek    | 1015PE         | 23.8  | Li-ion  | 45    | 051265DF6E |
| CPT-COS    | L14C3P6        | 36.6  | Li-ion  | 45    | CB421B796B |
| DYNAPACK   | HB4593R1ECW    | 56.3  | Li-ion  | 45    | 68C01947C9 |
| SMP        | DELL 70N2F95   | 84.3  | Li-poly | 45    | 58ADBD547F |
| LGC        | 02DL004        | 51.0  | Li-poly | 44    | 127874B25B |
|            | 48.84          | 49    | Li-ion  | 43    | 498E89971E |
| LGC        | LNV-45N1       | 47.5  | Li-ion  | 43    | C7D8DC11CA |
| Hewlett... | Primary        | 33    | Li-ion  | 42    | 193B294617 |
| SMP        | L19M4PC0       | 60.0  | Li-poly | 42    | 214D892F21 |
| ASUSTek    | K55--47        | 51.7  | Li-ion  | 41    | 5163F83320 |
| CPT-COS    | L16C2PB1       | 35.3  | Li-poly | 41    | FF57DE0FFA |
| Hewlett... | Primary        | 51    | Li-ion  | 41    | E6643F7ED1 |
| LGC        | 01AV445        | 45.0  | Li-poly | 41    | D1CDBD537E |
| LGC        | L16L2PB3       | 35.0  | Li-poly | 41    | 87D959803D |
| Notebook   | BAT            | 60    | Li-ion  | 41    | E60CDC9748 |
| Panasonic  | AS10D51        | 47.5  | Li-ion  | 41    | 8A74691BA9 |
| Sony       |                | 51    | Li-ion  | 41    | DBFD29F616 |
| ASUSTek    | T12--22        | 47.3  | Li-ion  | 40    | AC8D412B54 |
| LGC        | 45N1011        | 86.6  | Li-ion  | 40    | B0087EF7C8 |
| OEM        | FX50442        | 48.0  | Li-ion  | 40    | 456B686D28 |
| SMP        | 01AV430        | 57.0  | Li-poly | 40    | B063890F08 |
| SMP        | 02DL005        | 51.0  | Li-poly | 40    | 3A2547FB3C |
| Sunwoda-H  | HB4692Z9ECW-41 | 55.2  | Li-ion  | 40    | EB4D7C93C0 |
| TPS        | S10            | 44.4  | Li-ion  | 40    | C74129A618 |
| ASUSTek    | K56--30        | 44.2  | Li-ion  | 39    | 1A44FC7E8F |
| Celxpert   | L19C3PD6       | 52.5  | Li-poly | 39    | F07B9B77F5 |
| Hewlett... | Primary        | 24    | Li-ion  | 39    | D098305F2A |
| Hewlett... | Primary        | 54    | Li-ion  | 39    | A5331A4D5E |
| ASUSTek    | M50--24        | 51.3  | Li-ion  | 38    | C9D463149F |
| Hewlett... | Primary        | 57    | Li-ion  | 38    | 95D389BFE5 |
| Hewlett... | Primary        | 42    | Li-ion  | 38    | 984D3D9933 |
| SANYO      | 01AV405        | 26.3  | Li-ion  | 38    | 11539DC528 |
| SANYO      | AP13B3K        | 53.4  | Li-ion  | 38    | 17710EBD6D |
| SMP        | DELL VM73283   | 42.0  | Li-poly | 38    | 0A8AA1439F |
| ASUSTek    | N550-40        | 60.5  | Li-ion  | 37    | 5369ACA258 |
| Hewlett... | Primary        | 26    | Li-ion  | 37    | 45BA0657F1 |
| Hewlett... | Primary        | 52    | Li-ion  | 37    | 18F27D1F5C |
| Lenovo ... |                | 38    |         | 37    | 3CDDE1061C |
| LGC        | L11L6Y01       | 40.4  | Li-ion  | 37    | 661F69EB29 |
| LGC        | L17L2PF1       | 30.0  | Li-poly | 37    | EA290C0520 |
| SANYO      | AS07A31        | 48.8  | Li-ion  | 37    | 95CF81718F |
| SMP        | 00NY493        | 90.0  | Li-poly | 37    | F45B082C14 |
| SMP        | L14M3P24       | 45.0  | Li-poly | 37    | CFA4E16D46 |
| Sony       | PABAS024       | 52.7  | Li-ion  | 37    | A98AA9041E |
| ASUSTek    | X101CH         | 28.1  | Li-ion  | 36    | FCA7DBD9FE |
| ASUSTek    | X200-30        | 28.9  | Li-ion  | 36    | D8057F1C4D |
| Celxpert   | 01AV424        | 24.1  | Li-poly | 36    | EA23D24F90 |
| Notebook   | BAT            | 45    | Li-ion  | 36    | 4BAEB2CAFC |
| OEM        | AS10D31        | 48.4  | Li-ion  | 36    | 9371836E3E |
| SMP        | 5B10W138       | 45.7  | Li-poly | 36    | 1221048E12 |
| SMP        | DELL DM3WC64   | 60.0  | Li-poly | 36    | E4D0ECB120 |
| SMP        | L09M6Y02       | 46.4  | Li-ion  | 36    | 6074680FBA |
| Sunwoda    | 5B10W13935     | 46.0  | Li-poly | 36    | 1EC4861E97 |
| SUNWODA    | R15B01W        | 60.0  | Li-ion  | 36    | 6EE47924BD |
|            |                | 38    | Li-ion  | 35    | 0CB09F59A9 |
| Compal     | PA3817U-1BRS   | 48.6  | Li-ion  | 35    | DE29066B72 |
| LGC        | 42T4911        | 56.2  | Li-ion  | 35    | 3947636B4D |
| Samsung    |                | 45    | Li-ion  | 35    | 0396EAC317 |
| SANYO      | 42T4799        | 86.6  | Li-ion  | 35    | 90895AAB86 |
| SMP        | L17M3PG2       | 57.0  | Li-poly | 35    | 167DF4C15E |
| Toshiba    | PABAS0241231   | 96.5  | Li-ion  | 35    | CBE7430492 |
| ASUSTek    | X550E26        | 37.4  | Li-ion  | 34    | 7A7899C096 |
| Hewlett... | Primary        | 40    | Li-ion  | 34    | D14FE5657A |
| LGC        | 01AV490        | 23.9  | Li-poly | 34    | 227465CF98 |
| SANYO      | AL10A31        | 24.4  | Li-ion  | 34    | C3DB5ACB34 |
| SANYO      | AS07B31        | 48.8  | Li-ion  | 34    | 97C667E3C0 |
| SMP        | 00HW023        | 23.5  | Li-poly | 34    | A567978A3C |
| Notebook   | BAT            | 35    | Li-ion  | 33    | 6089EEE99C |
| SANYO      | 00HW022        | 23.5  | Li-poly | 33    | 6D2D97674C |
| SANYO      | 42T4791        | 51.3  | Li-ion  | 33    | 387EE22BC4 |
| Simplo     | BASE-BAT       | 39.9  | Li-poly | 33    | A52209C9F2 |
| SMP        | 45N1045        | 42.8  | Li-ion  | 33    | 7ED2650105 |
| SMP        | 5B10W13933     | 46.0  | Li-poly | 33    | BEEA39044C |
| ASUSTek    | PA3533U        | 50.8  | Li-ion  | 32    | E6A17619D6 |
| Lenovo     | LCFC           |       |         | 32    | A34F4E81C4 |
| LGC        | 01AV489        | 23.9  | Li-poly | 32    | 80FB4514C5 |
| Razer      | Blade          | 80.2  |         | 32    | 744799A3C4 |
| SANYO      | AS09A31        | 47.5  | Li-ion  | 32    | 85C9DD8233 |
| SMP        | L17M3PG1       | 52.5  | Li-poly | 32    | 2AD271E81F |
| Celxpert   | 5B10X026       | 45.0  | Li-poly | 31    | CEC5669039 |
| LGC        | 02DL007        | 50.5  | Li-poly | 31    | A01E524A66 |
| PANASONIC  | AP19B5L        | 53.0  | Li-ion  | 31    | 3D398D4B58 |
| SANYO      | 45N1023        | 73.3  | Li-ion  | 31    | A120083D3C |
| Sony       | VGP-BPS35A     | 42.3  | Li-ion  | 31    | 1D79ED8874 |
| Hewlett... | Primary        | 22    | Li-ion  | 30    | 3C24201057 |
| Lenovo     |                | 32    |         | 30    | 3D5411B3F0 |
| LGC        | 01AV494        | 57.0  | Li-poly | 30    | D8DB7F3FBD |
| LGC        | 45N1005        | 56.2  | Li-ion  | 30    | 5CE9661292 |
| LGC        | 45N1738        | 71.1  | Li-ion  | 30    | E02C35310A |
| PANASONIC  | AS16B5J        | 62.2  | Li-ion  | 30    | 97A2A90138 |
| SANYO      | 42T4763        | 56.2  | Li-ion  | 30    | 4AFF5A6A0C |
| SANYO      | AC14B13J       | 37.7  | Li-ion  | 30    | 2A96C0566A |
| SIMPLO     | MWL32b         | 47.5  | Li-ion  | 30    | C33F99576F |
| SMP        | DELL GD1JP65   | 68.0  | Li-poly | 30    | F2FB6B98EA |
| Hewlett... | 4400           | 47.5  |         | 29    | DFCCB89900 |
| Hewlett... | 5100           | 55.1  |         | 29    | 7A13EB86C2 |
| Hewlett... | Primary        | 5     | Li-ion  | 29    | 62284DF376 |
| LGC        | 5B10W138       | 45.0  | Li-poly | 29    | A35AAAEB6D |
| LGC        | AC14A8L        | 52.5  | Li-ion  | 29    | F2C465DCBE |
| Samsung... | DELL P8TC727   | 48.8  | Li-ion  | 29    | B046A9DFE3 |
| SMP        | 01AV446        | 45.3  | Li-poly | 29    | 52BA950565 |
| SMP        | 5B10W139       | 57.0  | Li-poly | 29    | 9BA5143844 |
| SMP        | 5B10W13931     | 51.0  | Li-poly | 29    | 2A1930C4E4 |
| Toshiba    | PA3817U-1BRS   | 47.5  | Li-ion  | 29    | 14A96B5CEC |
| Compal     | PABAS024       | 48.8  | Li-ion  | 28    | F5112DBF47 |
| DYNAPACK   | HB4593J6ECW    | 41.2  | Li-ion  | 28    | C62BB4ADC9 |
| Hewlett... | Primary        | 18    | Li-ion  | 28    | B409334E94 |
| LGC        | 45N1147        | 56.2  | Li-ion  | 28    | E1E44B58F3 |
| Simplo     | Li_Ion_4000mA  | 48.8  | Li-ion  | 28    | FA287E0453 |
| SMP        | 02DL008        | 50.5  | Li-poly | 28    | FBE1D68B82 |
| Toshiba    | PA3533U        | 57.7  | Li-ion  | 28    | B884D58259 |
| ASUSTek    | PA3533U        | 56.2  | Li-ion  | 27    | AF980DC491 |
| Celxpert   | 5B10W138       | 45.7  | Li-poly | 27    | 85C8487CA5 |
| SMP        | 01AV452        | 24.0  | Li-poly | 27    | C13569FCA7 |
| SMP        | DELL VM73297   | 42.0  | Li-poly | 27    | 1ABAE7ECBD |
|            |                |       | Li-ion  | 26    | BF8ABDFB09 |
| GLK MRD    |  Li-ion        |       | Li-ion  | 26    | E4FB415516 |
| Hewlett... | Primary        | 23    | Li-ion  | 26    | 9185255B98 |
| LGC        | 01AV492        | 71.1  | Li-ion  | 26    | D2C417C68B |
| LGC        | 45N1735        | 47.5  | Li-ion  | 26    | 55689E67B3 |
| Sunwoda    | 5B10X025       | 45.0  | Li-poly | 26    | BE67E01A7D |
|            | PABAS0241231   | 51.6  | Li-ion  | 25    | CF3C570B7A |
| Celxpert   | 01AY969        | 80.4  | Li-poly | 25    | 5459662EC3 |
| Lenovo ... |                | 32    |         | 25    | B37415E3C3 |
| Lenovo     | L11S6Y01       | 38.9  | Li-ion  | 25    | 2A59A10BB7 |
| SANYO      | 45N1777        | 71.3  | Li-ion  | 25    | D7F1B3F27E |
| SANYO      | LNV-45N1       | 47.5  | Li-ion  | 25    | B64E2C4A07 |
| SMP        | DELL MKD6223   | 62.2  | Li-ion  | 25    | 39348A932E |
| Toshiba    | PA3534U        | 44.4  | Li-ion  | 25    | 371CF70DA6 |
| 333-1C-... | KC04053XL      | 50.9  | Li-ion  | 24    | 0E50BEA137 |

