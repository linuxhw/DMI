DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by Linux users at https://linux-hardware.org.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 113504.

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

Count  - number of computers with this device installed,
Report - link to DMI report.

### Cpu

| MFG        | Name                             | GHz  | Count | Report |
|------------|----------------------------------|------|-------|--------|
| Intel      | 11th Gen Core i5-1135G7          | 2.40 | 3055  | [11F61137DC15](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15>) |
| Intel      | Core i5-8250U                    | 1.60 | 1091  | [FC89A5E51EAE](<Notebook/Dell/Latitude/Latitude 5290/FC89A5E51EAE>) |
| Intel      | Core i7-8550U                    | 1.80 | 1016  | [12325A990B32](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G5/12325A990B32>) |
| Intel      | Core i5-7200U                    | 2.50 | 894   | [9911083B00F9](<Notebook/Hewlett-Packard/ProBook/ProBook 440 G4/9911083B00F9>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 785   | [57EFD5B4322B](<Desktop/ASRock/B450M/B450M Steel Legend/57EFD5B4322B>) |
| Intel      | 12th Gen Core i7-12700H          |      | 779   | [37910A3DDDFF](<Notebook/Dell/Inspiron/Inspiron 16 Plus 7620/37910A3DDDFF>) |
| Intel      | Core i7-10510U                   | 1.80 | 724   | [1BD4FAC2B4C3](<Notebook/Dell/Inspiron/Inspiron 5391/1BD4FAC2B4C3>) |
| Intel      | Core i7-9750H                    | 2.60 | 706   | [5F4D0AB0905E](<Notebook/Lenovo/Legion/Legion Y540-15IRH 81SX/5F4D0AB0905E>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 695   | [26116FF2B2E2](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/26116FF2B2E2>) |
| Intel      | Core i5-10210U                   | 1.60 | 686   | [5AA0FDDE192E](<Notebook/HUAWEI/NBLB-WAX9/NBLB-WAX9N/5AA0FDDE192E>) |
| Intel      | Core i7-8750H                    | 2.20 | 676   | [753782FFE946](<Notebook/Acer/Aspire/Aspire A715-72G/753782FFE946>) |
| Intel      | Core i5-3210M                    | 2.50 | 639   | [540AF9B46C29](<Notebook/Samsung Electronics/350V5/350V5C-351V5C-3540VC-3440VC/540AF9B46C29>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 627   | [124C8A1B9995](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-K/124C8A1B9995>) |
| Intel      | Core i5-6200U                    | 2.30 | 626   | [4BEE0CAA54AA](<Notebook/Hewlett-Packard/250/250 G5 Notebook PC/4BEE0CAA54AA>) |
| Intel      | Core i7-7700HQ                   | 2.80 | 608   | [B18B674EE141](<Notebook/Dell/Precision/Precision 7720/B18B674EE141>) |
| Intel      | 11th Gen Core i7-11850H          | 2.50 | 566   | [1D6F35E22C18](<Notebook/Avell High Performance/A65/A65 MOB/1D6F35E22C18>) |
| Intel      | Core i7-7500U                    | 2.70 | 553   | [CC79FDC974C7](<Notebook/TUXEDO/N24/N24_25BU/CC79FDC974C7>) |
| Intel      | Core i5-8265U                    | 1.60 | 521   | [6214F3DFC9AB](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/6214F3DFC9AB>) |
| Intel      | Core i7-8565U                    | 1.80 | 507   | [1EC55A488EF5](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X432FA_S432FA/1EC55A488EF5>) |
| Intel      | Core i5-2520M                    | 2.50 | 502   | [8854B2161F24](<Notebook/Lenovo/ThinkPad/ThinkPad T420s 4174W2X/8854B2161F24>) |
| Intel      | Celeron N2840                    | 2.16 | 502   | [A3B42A7B6114](<Notebook/ASUSTek Computer/X200/X200MA/A3B42A7B6114>) |
| Intel      | Core i5-3470                     | 3.20 | 501   | [791575E45E29](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92P 3227BD2/791575E45E29>) |
| Intel      | Core i7-10750H                   | 2.60 | 500   | [674D96FDF457](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus M15 GU502LW_GU502LW/674D96FDF457>) |
| Intel      | Core i5-5200U                    | 2.20 | 480   | [287C0142E54D](<Notebook/ASUSTek Computer/X555/X555LJ/287C0142E54D>) |
| Intel      | Core i5-3320M                    | 2.60 | 466   | [E2A51E4B633B](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8470p/E2A51E4B633B>) |
| Intel      | Core i5-3230M                    | 2.60 | 459   | [E86AA98876D7](<Notebook/Notebook/W250/W250EGQ-W270EGQ/E86AA98876D7>) |
| AMD        | Ryzen 5 5500U with Radeon Gra... |      | 448   | [89AC4AB12668](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/89AC4AB12668>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 442   | [C86078D39B1D](<Desktop/Intel/DP43TF/DP43TF AAE34878-403/C86078D39B1D>) |
| Intel      | Core i7-3770                     | 3.40 | 434   | [69D8B31022D1](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V DELUXE/69D8B31022D1>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 424   | [0E4430B16F5F](<Desktop/Gigabyte Technology/B450/B450 AORUS M/0E4430B16F5F>) |
| Intel      | Atom x5-Z8350                    | 1.44 | 421   | [B000C4859752](<Notebook/Beelink/BT3/BT3 PRO/B000C4859752>) |
| Intel      | Core i5-6300U                    | 2.40 | 421   | [060101A7B46D](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 460 20ELS0FJ01/060101A7B46D>) |
| Intel      | Core i7-8565U                    | 1.80 | 415   | [2E8FC5060A14](<Notebook/Lenovo/ThinkBook/ThinkBook 13s-IWL 20R9/2E8FC5060A14>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 414   | [CF04095B1306](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 2 20T60029RT/CF04095B1306>) |
| Intel      | Core i5-4210U                    | 1.70 | 414   | [3BE7A14EC8D5](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/3BE7A14EC8D5>) |
| Intel      | Core i5-2400                     | 3.10 | 412   | [0FF37B6BAA24](<Desktop/Others/Others/Others/0FF37B6BAA24>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 409   | [D88E08C3A7A1](<Notebook/TerraQue/W65/W65_W67RB/D88E08C3A7A1>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 397   | [B9B57A731D44](<Notebook/Dell/G5/G5 5505/B9B57A731D44>) |
| Intel      | Core i5-1035G1                   | 1.00 | 396   | [83C5E1166CAF](<Tablet/Microsoft/Surface/Surface Laptop Go/83C5E1166CAF>) |
| AMD        | FX -6300 Six-Core                |      | 390   | [6BAC82210FE1](<Desktop/ASRock/970M/970M Pro3/6BAC82210FE1>) |
| Intel      | Core i3-2120                     | 3.30 | 390   | [D7591CF7C8EA](<Desktop/Dell/OptiPlex/OptiPlex 7010/D7591CF7C8EA>) |
| AMD        | Ryzen 7 5700U with Radeon Gra... |      | 388   | [EEC49B509995](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ee1xxx/EEC49B509995>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 388   | [D1E7CA404339](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339>) |
| Intel      | Core i5-2410M                    | 2.30 | 386   | [31E6EFD8D207](<Notebook/Toshiba/Satellite/Satellite L755/31E6EFD8D207>) |
| Intel      | Core 2 Duo P7450                 | 2.13 | 383   | [122635676299](<Notebook/Sony/VPCCW1/VPCCW1S1E/122635676299>) |
| AMD        | Ryzen 5 4500U with Radeon Gra... |      | 382   | [CF2DAC92FEBB](<Notebook/Hewlett-Packard/ProBook/ProBook 445 G7/CF2DAC92FEBB>) |
| AMD        | FX-8350 Eight-Core               |      | 380   | [4209CEC662D2](<Desktop/Gigabyte Technology/970/970A-DS3P/4209CEC662D2>) |
| Intel      | 11th Gen Core i7-11700           | 2.50 | 380   | [AA0705BC8FAC](<Desktop/Gigabyte Technology/Z590/Z590 AORUS ULTRA/AA0705BC8FAC>) |
| Intel      | Core i5-2450M                    | 2.50 | 380   | [E81BF21D4D94](<Notebook/Sony/VPCZ23/VPCZ23Q9R/E81BF21D4D94>) |
| AMD        | Ryzen 7 5800H with Radeon Gra... |      | 379   | [2BE152EEFFDD](<Notebook/Lenovo/Legion/Legion 5 15ACH6 82JW/2BE152EEFFDD>) |
| Intel      | Core i7-1065G7                   | 1.30 | 367   | [6D5F5C296418](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14IIL05 81X1/6D5F5C296418>) |
| Intel      | 12th Gen Core i9-12900K          |      | 358   | [46556BD3958D](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z690-A GAMING WIFI D4/46556BD3958D>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 356   | [9B3E9D48669C](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/9B3E9D48669C>) |
| Intel      | Celeron N3060                    | 1.60 | 354   | [2EDB83247697](<Notebook/Hewlett-Packard/Notebook/Notebook/2EDB83247697>) |
| Intel      | Core i7-4790                     | 3.60 | 351   | [D2A83135503F](<Desktop/Dell/OptiPlex/OptiPlex 9020/D2A83135503F>) |
| Intel      | Core i5-8265U                    | 1.60 | 350   | [6AF4025C842E](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da1xxx/6AF4025C842E>) |
| Intel      | Core i5-4200U                    | 1.60 | 344   | [E5D25577EBCB](<Notebook/Packard Bell/EasyNote/EasyNote TE69HW/E5D25577EBCB>) |
| Intel      | Core i3-3110M                    | 2.40 | 337   | [F963F60499C1](<Notebook/Dell/Inspiron/Inspiron 3520/F963F60499C1>) |
| Intel      | Core i3-6006U                    | 2.00 | 335   | [AD011DB09D1C](<Notebook/Lenovo/E31-80/E31-80 80MX/AD011DB09D1C>) |
| Intel      | Pentium Silver N6000             | 1.10 | 332   | [53CF20A09429](<Desktop/AZW/MINI/MINI S/53CF20A09429>) |
| Intel      | Core i7-6500U                    | 2.50 | 329   | [9654B0B310BA](<Desktop/Others/Others/Others/9654B0B310BA>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 325   | [656BCFA44494](<Desktop/Intel/DG43GT/DG43GT AAE62768-300/656BCFA44494>) |
| Intel      | Core i3-5005U                    | 2.00 | 323   | [8DFB23283FCD](<Notebook/Hewlett-Packard/Notebook/Notebook/8DFB23283FCD>) |
| Intel      | Core i3-3220                     | 3.30 | 319   | [43C25A9EA8C2](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/43C25A9EA8C2>) |
| Intel      | Core i3-2350M                    | 2.30 | 317   | [5E803907CCF8](<Notebook/ASUSTek Computer/K54/K54HR/5E803907CCF8>) |
| Intel      | Core i3-2100                     | 3.10 | 315   | [A77DA1060A8E](<Desktop/Foxconn/H61/H61MXV-H67MXV/A77DA1060A8E>) |
| Intel      | Core i7-2600                     | 3.40 | 310   | [6827F97BCD6A](<Desktop/Intel/H/H61/6827F97BCD6A>) |
| Intel      | Core i5-2430M                    | 2.40 | 308   | [CEDFE32C9D52](<Notebook/Dell/Inspiron/Inspiron N5110/CEDFE32C9D52>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 307   | [3D488BD047B1](<Desktop/ASUSTek Computer/P5KPL-AM/P5KPL-AM SE/3D488BD047B1>) |
| Intel      | Celeron N3350                    | 1.10 | 304   | [6BA806AD85DC](<Notebook/Alcor Digital/Snugbook/Snugbook N1431/6BA806AD85DC>) |
| Intel      | Celeron N4020                    | 1.10 | 302   | [F85ED92E93ED](<Notebook/GPU Company/GWTC116/GWTC116-2/F85ED92E93ED>) |
| AMD        | Ryzen 5 5600X 6-Core             |      | 299   | [405CEAE381D2](<Desktop/ASRock/B450M/B450M Steel Legend/405CEAE381D2>) |
| Intel      | Core i3-2310M                    | 2.10 | 297   | [69A81B6CB108](<Notebook/ASUSTek Computer/K73/K73E/69A81B6CB108>) |
| Intel      | Core i5-6500                     | 3.20 | 297   | [18BE455764D5](<Desktop/ASUSTek Computer/Z170I/Z170I PRO GAMING/18BE455764D5>) |
| Intel      | Core i5-5300U                    | 2.30 | 292   | [9DC8CA3DF416](<Notebook/Dell/Latitude/Latitude E7450/9DC8CA3DF416>) |
| Intel      | Core i5-4460                     | 3.20 | 290   | [DF723B4B77B5](<Desktop/MSI/MS/MS-7816/DF723B4B77B5>) |
| Intel      | Core i3 M 370                    | 2.40 | 282   | [66FE7E8D7F44](<Notebook/Hewlett-Packard/630/630/66FE7E8D7F44>) |
| Intel      | Core i5-4570                     | 3.20 | 277   | [E9FD17DAA8B2](<Desktop/Dell/OptiPlex/OptiPlex 9020/E9FD17DAA8B2>) |
| Intel      | Core i7-8650U                    | 1.90 | 275   | [71FFDA7F373E](<Notebook/Dell/Latitude/Latitude 7490/71FFDA7F373E>) |
| Intel      | Core i5-8300H                    | 2.30 | 272   | [C47E2769EDB1](<Notebook/Lenovo/Legion/Legion Y7000 81FW/C47E2769EDB1>) |
| AMD        | Ryzen 5 4600H with Radeon Gra... |      | 270   | [5D8ED7ADD7DF](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/5D8ED7ADD7DF>) |
| Intel      | 12th Gen Core i5-1235U           |      | 270   | [61779DC30678](<Notebook/Hewlett-Packard/Laptop/Laptop 17-cn2xxx/61779DC30678>) |
| AMD        | Ryzen 5 2500U with Radeon Veg... |      | 265   | [BF440AD92075](<Notebook/ASUSTek Computer/VivoBook_ASUS/VivoBook_ASUS Laptop X505ZA_R504ZA/BF440AD92075>) |
| Intel      | Atom N270                        | 1.60 | 265   | [7B8FCF2DC8DB](<Notebook/Lenovo/4068/4068AGJ/7B8FCF2DC8DB>) |
| Intel      | Core i7-6700K                    | 4.00 | 265   | [55EAA5F4B3CF](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 3/55EAA5F4B3CF>) |
| Intel      | Core i3 M 380                    | 2.53 | 264   | [E0C11E2DCE11](<Notebook/Dell/Inspiron/Inspiron N5010/E0C11E2DCE11>) |
| Intel      | Pentium B960                     | 2.20 | 259   | [D928F6851B7B](<Notebook/Itautec/Infoway/Infoway w7535/D928F6851B7B>) |
| Intel      | Core i7-6700                     | 3.40 | 259   | [BC9CF352F91A](<Desktop/ASUSTek Computer/Z170/Z170-P/BC9CF352F91A>) |
| Intel      | Core i5-4300U                    | 1.90 | 256   | [BE159E2FFF98](<Notebook/Lenovo/ThinkPad/ThinkPad T440 20B7A0CYFR/BE159E2FFF98>) |
| Intel      | Core i7-3630QM                   | 2.40 | 255   | [9ECF6B177836](<Notebook/Samsung Electronics/350V5/350V5C-351V5C-3540VC-3440VC/9ECF6B177836>) |
| Intel      | Core i7-2670QM                   | 2.20 | 249   | [48C48CE24154](<Notebook/Others/Others/Others/48C48CE24154>) |
| AMD        | Ryzen 5 5600G with Radeon Gra... |      | 248   | [BD5F281A2678](<Desktop/Gigabyte Technology/B550M/B550M DS3H/BD5F281A2678>) |
| Intel      | Core i7-4770                     | 3.40 | 248   | [02BF18B75E6E](<Desktop/Gigabyte Technology/Z97/Z97P-D3/02BF18B75E6E>) |
| AMD        | Ryzen 5 1600 Six-Core            |      | 246   | [0A9E01FDC5FC](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC>) |
| Intel      | Core i7-6600U                    | 2.60 | 246   | [1DBF19E30974](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 260 20FES1L60R/1DBF19E30974>) |
| AMD        | Ryzen 7 3700U with Radeon Veg... |      | 244   | [44E71F2A11E6](<Notebook/GPU Company/GWNR/GWNR71517/44E71F2A11E6>) |
| Intel      | Atom N450                        | 1.66 | 241   | [587F03DC9979](<Notebook/ASUSTek Computer/1001/1001PX/587F03DC9979>) |
| Intel      | Core i5-4590                     | 3.30 | 240   | [EF1772B991DB](<Desktop/Dell/OptiPlex/OptiPlex 9020/EF1772B991DB>) |
| Intel      | Core i7-5500U                    | 2.40 | 238   | [26098637A976](<Notebook/Hewlett-Packard/Others/Others/26098637A976>) |
| AMD        | E-450 APU with Radeon HD Grap... |      | 237   | [6B8DE2BAD9FB](<Notebook/ASUSTek Computer/K53/K53BR/6B8DE2BAD9FB>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 237   | [271CDE20E3D3](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/271CDE20E3D3>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 234   | [68D04878595E](<Desktop/CMS Computers/7200/7200-5413A/68D04878595E>) |
| AMD        | Ryzen 7 PRO 4750U with Radeon... |      | 233   | [282395B9AD24](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y1001HTX/282395B9AD24>) |
| Intel      | Core i7-8700                     | 3.20 | 233   | [6EDAE1870B25](<Desktop/ASRock/B360M/B360M IB-R1/6EDAE1870B25>) |
| Intel      | Core i7-4790K                    | 4.00 | 230   | [55E374A7ECC4](<Desktop/ASUSTek Computer/All/All Series/55E374A7ECC4>) |
| Intel      | Core i3-3217U                    | 1.80 | 229   | [61709C060715](<Notebook/ASUSTek Computer/X202/X202E/61709C060715>) |
| Intel      | Core i5-7400                     | 3.00 | 222   | [1EEFF6255E0E](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p5xx/1EEFF6255E0E>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 219   | [8CED5CE61807](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-E GAMING/8CED5CE61807>) |
| Intel      | Core i5-8400                     | 2.80 | 216   | [CE18A432A8EF](<Desktop/Medion/MD3410/MD34100-2543/CE18A432A8EF>) |
| Intel      | Core i3-4005U                    | 1.70 | 215   | [7BA22E7981CD](<Notebook/Lenovo/G50-80/G50-80 80L0/7BA22E7981CD>) |
| Intel      | Core i5-8350U                    | 1.70 | 213   | [12A57ACC2E26](<Notebook/Hewlett-Packard/EliteBook/EliteBook 830 G5/12A57ACC2E26>) |
| Intel      | Celeron N4000                    | 1.10 | 212   | [96DF0C529E2C](<Mini Pc/Hewlett-Packard/t430/t430 Thin Client/96DF0C529E2C>) |
| Intel      | Celeron N3050                    | 1.60 | 211   | [409B91849443](<Notebook/Hewlett-Packard/15/15 Notebook PC/409B91849443>) |
| Intel      | Core i5-3570K                    | 3.40 | 209   | [0B0B26A1FB63](<Desktop/Gigabyte Technology/Z77/Z77-DS3H/0B0B26A1FB63>) |
| Intel      | Core i7-3770K                    | 3.50 | 209   | [3DCC04D7FE29](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LE/3DCC04D7FE29>) |
| Intel      | Core i7-8665U                    | 1.90 | 208   | [AECCF9C01BD8](<Mini Pc/Intel Client Systems/NUC8/NUC8v7PNH/AECCF9C01BD8>) |
| Intel      | Core i3-2330M                    | 2.20 | 207   | [BA1DF2DADB62](<Notebook/ASUSTek Computer/K73/K73SJ/BA1DF2DADB62>) |
| Intel      | Core i7-8700K                    | 3.70 | 206   | [94E45CAB4EE0](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/94E45CAB4EE0>) |
| Intel      | Core i7-7700K                    | 4.20 | 205   | [C1DFDE9A944B](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/C1DFDE9A944B>) |
| Intel      | Core i5-5250U                    | 1.60 | 205   | [DAC4653A934F](<Notebook/Apple/MacBookAir7/MacBookAir7,2/DAC4653A934F>) |
| Intel      | Core i7-7700                     | 3.60 | 204   | [D03AB5FF3F68](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G3 SFF/D03AB5FF3F68>) |
| Intel      | Pentium Dual-Core T4500          | 2.30 | 203   | [678FA81C1F08](<Notebook/eMachines/E/E725/678FA81C1F08>) |
| Intel      | Core i5-3337U                    | 1.80 | 203   | [2F3EAFFD46E4](<Notebook/Lenovo/IdeaPad/IdeaPad U510 20191/2F3EAFFD46E4>) |
| AMD        | Ryzen 5 5600H with Radeon Gra... |      | 199   | [168A3EC1E1EA](<Notebook/Hewlett-Packard/Victus/Victus by Laptop 16-e0xxx/168A3EC1E1EA>) |
| Intel      | Core i3-6100                     | 3.70 | 197   | [30F694CCEC2B](<Desktop/MSI/MS/MS-7996/30F694CCEC2B>) |
| AMD        | Athlon II X2 250                 |      | 196   | [FA6847F222B5](<Desktop/Biostar/A780/A780L3C/FA6847F222B5>) |
| AMD        | FX-8320 Eight-Core               |      | 196   | [C38537745C61](<Desktop/ASUSTek Computer/M5A97/M5A97 EVO R2.0/C38537745C61>) |
| Intel      | Core i5-3570                     | 3.40 | 196   | [DED037CCA348](<Desktop/Intel/B/B75/DED037CCA348>) |
| Intel      | Pentium Dual-Core E5300          | 2.60 | 195   | [56CDA0F2FEEF](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Small Form Factor/56CDA0F2FEEF>) |
| Intel      | Core i3-4130                     | 3.40 | 195   | [3D7A5792365C](<Desktop/ASUSTek Computer/All/All Series/3D7A5792365C>) |
| Intel      | Core i5-10300H                   | 2.50 | 194   | [1876F7CE86CD](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming F15 FX506LI_FX566LI/1876F7CE86CD>) |
| Intel      | Core i7-4510U                    | 2.00 | 194   | [03EEFC9685DF](<Notebook/Lenovo/G50-70/G50-70 20351/03EEFC9685DF>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 193   | [348836DC6639](<Desktop/Gigabyte Technology/B450/B450 AORUS ELITE/348836DC6639>) |
| Intel      | Core i3-7100U                    | 2.40 | 191   | [0F893A98C637](<Notebook/Acer/Aspire/Aspire E5-576/0F893A98C637>) |
| Intel      | Atom N455                        | 1.66 | 191   | [58B5AF505AA0](<Desktop/Intel/WADE-8076/WADE-8076-ST-WMS/58B5AF505AA0>) |
| Intel      | Core i5-2500K                    | 3.30 | 191   | [B80153BC8F95](<Desktop/Gigabyte Technology/H61/H61M-D2H-USB3/B80153BC8F95>) |
| Intel      | Core i5-9300H                    | 2.40 | 190   | [1AC2A4AA7A96](<Notebook/Lenovo/Legion/Legion Y540-15IRH-PG0 81SY/1AC2A4AA7A96>) |
| Intel      | Core i7-2630QM                   | 2.00 | 190   | [7713EE2713FC](<Notebook/Acer/Aspire/Aspire 5750G/7713EE2713FC>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 188   | [C7CA1B973424](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/C7CA1B973424>) |
| AMD        | Ryzen 5 3600X 6-Core             |      | 186   | [AE75D1AB7CB4](<Desktop/ASUSTek Computer/TUF/TUF B450-PLUS GAMING/AE75D1AB7CB4>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 185   | [BE6B2A31F668](<Desktop/Gigabyte Technology/B450/B450 I AORUS PRO WIFI/BE6B2A31F668>) |
| Intel      | Core i7-4700MQ                   | 2.40 | 185   | [58E500E065B5](<Notebook/Lenovo/ThinkPad/ThinkPad W540 20BHS1J000/58E500E065B5>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 184   | [A2EE7FB360B4](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/A2EE7FB360B4>) |
| AMD        | Ryzen 9 5900HX with Radeon Gr... |      | 184   | [1FE0593076B3](<Desktop/Others/HX/HX90/1FE0593076B3>) |
| Intel      | Core i5-2500                     | 3.30 | 184   | [C58861466405](<Desktop/Others/Others/Others/C58861466405>) |
| Intel      | Core i3-3120M                    | 2.50 | 184   | [8BCDDD9F9C62](<Notebook/Toshiba/Satellite/Satellite C855/8BCDDD9F9C62>) |
| AMD        | Ryzen 7 5700G with Radeon Gra... |      | 182   | [1C885144C28F](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/1C885144C28F>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 181   | [DDF6FDC2A438](<Desktop/ASRock/A320M-HDV/A320M-HDV R4.0/DDF6FDC2A438>) |
| Intel      | Core i3-10110U                   | 2.10 | 181   | [9FC3E9497287](<Notebook/Hewlett-Packard/Laptop/Laptop 15-dw1xxx/9FC3E9497287>) |
| Intel      | Pentium 2020M                    | 2.40 | 180   | [66BB96E66B62](<Notebook/Medion/E/E6234/66BB96E66B62>) |
| Intel      | Core 2 Duo P8600                 | 2.40 | 179   | [70447EBB84BB](<Notebook/Dell/Latitude/Latitude E6400/70447EBB84BB>) |
| Intel      | Core i3-1005G1                   | 1.20 | 176   | [013E551719B3](<Notebook/Acer/Extensa/Extensa 215-52/013E551719B3>) |
| Intel      | Core i5-7300HQ                   | 2.50 | 176   | [74B446CE2C6E](<Notebook/Lenovo/Y520-15IKBN/Y520-15IKBN 80WK/74B446CE2C6E>) |
| Intel      | Core i5 M 460                    | 2.53 | 176   | [8B75DDBC39E0](<Notebook/ASUSTek Computer/K42/K42Jc/8B75DDBC39E0>) |
| Intel      | Core i5 M 520                    | 2.40 | 176   | [255277C340F9](<Notebook/Fujitsu/T/T900/255277C340F9>) |
| Intel      | Core i5-4200M                    | 2.50 | 176   | [0E0E9BD92F1F](<Notebook/Lenovo/ThinkPad/ThinkPad T540p 20BE003YUK/0E0E9BD92F1F>) |
| Intel      | Core i7-4500U                    | 1.80 | 176   | [53EE0636FFCA](<Notebook/Dell/Inspiron/Inspiron 3537/53EE0636FFCA>) |
| AMD        | FX -4300 Quad-Core               |      | 175   | [C85B0030F9F4](<Desktop/MSI/MS/MS-7693/C85B0030F9F4>) |
| Intel      | Celeron J4125                    | 2.00 | 175   | [BD0FBF639942](<Desktop/ASRock/J4125/J4125M/BD0FBF639942>) |
| Intel      | Core i7-3610QM                   | 2.30 | 175   | [B36E5125492E](<Notebook/Toshiba/Satellite/Satellite L855/B36E5125492E>) |
| AMD        | Ryzen 5 2600X Six-Core           |      | 174   | [06F6A88794AD](<Desktop/ASRock/X470/X470 Master SLI/06F6A88794AD>) |
| Intel      | Pentium Dual-Core T4300          | 2.10 | 173   | [95759DCE41E1](<Notebook/eMachines/E/E725/95759DCE41E1>) |
| Intel      | Core i7-2600K                    | 3.40 | 173   | [9F17790B4089](<Desktop/Intel/DZ68DB/DZ68DB AAG27985-101/9F17790B4089>) |
| Intel      | Core i5-7300U                    | 2.60 | 171   | [55DE83D5ACA3](<Convertible/Lenovo/ThinkPad/ThinkPad Yoga 370 20JJS0A44Z/55DE83D5ACA3>) |
| Intel      | Core i5-6400                     | 2.70 | 171   | [A7E6ADB389B1](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1>) |
| Intel      | Atom N2600                       | 1.60 | 167   | [65CA43BBFA98](<Notebook/Intel/powered/powered classmate PC/65CA43BBFA98>) |
| Intel      | Core i5-3317U                    | 1.70 | 167   | [B4E5A7138DB1](<Notebook/Samsung Electronics/530U3/530U3C-530U4C-532U3C/B4E5A7138DB1>) |
| AMD        | Ryzen 9 5950X 16-Core            |      | 166   | [A0A588B9313C](<Desktop/ASRock/X570/X570 Phantom Gaming X/A0A588B9313C>) |
| Intel      | Pentium Dual-Core T4400          | 2.20 | 166   | [B7D24A17624E](<Desktop/Medion/MS/MS-7621/B7D24A17624E>) |
| Intel      | Pentium Dual-Core E5700          | 3.00 | 165   | [0AD4BEF7C1C1](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX/0AD4BEF7C1C1>) |
| Intel      | Pentium N3540                    | 2.16 | 165   | [AE366F96F926](<Notebook/Lenovo/Yoga/Yoga 300-11IBY 80M0/AE366F96F926>) |
| Intel      | Celeron 2955U                    | 1.40 | 165   | [B411A7C47BF4](<Notebook/Acer/Peppy/Peppy/B411A7C47BF4>) |
| Intel      | Core i3-6100U                    | 2.30 | 164   | [853AB1A7D0CA](<Notebook/Lenovo/ThinkPad/ThinkPad L560 20F2S13L00/853AB1A7D0CA>) |
| Intel      | Core 2 Duo E6550                 | 2.33 | 163   | [0772711AD395](<Desktop/ASUSTek Computer/P5/P5K/0772711AD395>) |
| Intel      | Core i3-3240                     | 3.40 | 163   | [D9B19A219BD4](<Desktop/Hewlett-Packard/Pro3500/Pro3500 Series/D9B19A219BD4>) |
| AMD        | Ryzen 7 3800X 8-Core             |      | 162   | [638A9F7B01C2](<Desktop/System76/Thelio/Thelio/638A9F7B01C2>) |
| Intel      | Core 2 T7200                     | 2.00 | 161   | [1EF0617FEF8B](<Notebook/Hewlett-Packard/Others/Others/1EF0617FEF8B>) |
| Intel      | Atom Z3735F                      | 1.33 | 161   | [B7F891A25D5D](<Notebook/Hewlett-Packard/Pro/Pro Tablet 10 EE G1/B7F891A25D5D>) |
| Intel      | Core i7-4600U                    | 2.10 | 161   | [6BE8E7B2C3D1](<Notebook/Toshiba/PORTEGE/PORTEGE Z30t-A/6BE8E7B2C3D1>) |
| Intel      | Celeron N2830                    | 2.16 | 157   | [91236DA4B8CC](<Notebook/Hewlett-Packard/15/15/91236DA4B8CC>) |
| Intel      | Pentium G4400                    | 3.30 | 157   | [56AEBC520FFC](<Desktop/Dell/Inspiron/Inspiron 3250/56AEBC520FFC>) |
| Intel      | Core i3-7100                     | 3.90 | 156   | [0401B4CF51F2](<Desktop/Others/Others/Others/0401B4CF51F2>) |
| AMD        | Phenom II X4 965                 |      | 155   | [2DA9AF5AE83C](<Desktop/ASRock/890FX/890FX Deluxe4/2DA9AF5AE83C>) |
| AMD        | Ryzen 5 3550H with Radeon Veg... |      | 155   | [3144AE490C42](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DT_FX505DT/3144AE490C42>) |
| Intel      | Core i5-2540M                    | 2.60 | 155   | [E28D554E86AB](<Notebook/ASUSTek Computer/K54/K54HR/E28D554E86AB>) |
| Intel      | Core 2 Duo P8700                 | 2.53 | 153   | [F6A099116F75](<Notebook/Dell/Inspiron/Inspiron 1545/F6A099116F75>) |
| Intel      | Core i3 M 330                    | 2.13 | 153   | [14BB1CEB4A34](<Notebook/Dell/Inspiron/Inspiron 1564/14BB1CEB4A34>) |
| Intel      | Core i5-7500                     | 3.40 | 152   | [623C6DFA14C1](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/623C6DFA14C1>) |
| Intel      | Core i3-8100                     | 3.60 | 151   | [5322EAC8B99B](<All In One/Apple/iMac19/iMac19,2/5322EAC8B99B>) |
| Intel      | Core i3 M 350                    | 2.27 | 151   | [358862D39503](<Notebook/Lenovo/G560/G560 0679/358862D39503>) |
| Intel      | Core i5 M 480                    | 2.67 | 151   | [26799175FD73](<Notebook/Toshiba/Satellite/Satellite L655/26799175FD73>) |
| Intel      | Core i5-10400                    | 2.90 | 150   | [B2419177B3BB](<Notebook/Lenovo/IdeaCentre/IdeaCentre AIO 3 24IMB05 F0EU00M8RU/B2419177B3BB>) |
| Intel      | Pentium N3700                    | 1.60 | 149   | [9AE6692DF089](<Notebook/Compaq/420/420/9AE6692DF089>) |
| AMD        | E-350                            |      | 146   | [8EE658D49209](<Notebook/eMachines/eMachiens/eMachiens G443/8EE658D49209>) |
| Intel      | Core 2 Duo P8400                 | 2.26 | 146   | [27C961FA19BA](<Notebook/Sony/VGN-AW11/VGN-AW11M_H/27C961FA19BA>) |
| Intel      | Core i7-3520M                    | 2.90 | 146   | [0CD38833C0EF](<Notebook/Lenovo/ThinkPad/ThinkPad W530 24473F2/0CD38833C0EF>) |
| Intel      | Core i3-4160                     | 3.60 | 146   | [69A6781598B0](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 USDT/69A6781598B0>) |
| Intel      | Core i7-6820HQ                   | 2.70 | 146   | [19A0DFEDBDBA](<Notebook/Dell/Latitude/Latitude E5570/19A0DFEDBDBA>) |
| AMD        | Phenom II X4 955                 |      | 145   | [196D4EF3C39F](<Desktop/Gigabyte Technology/GA-890/GA-890GPA-UD3H/196D4EF3C39F>) |
| Intel      | Core i7-10710U                   | 1.10 | 143   | [1139C4064B3E](<Notebook/Dell/XPS/XPS 13 7390/1139C4064B3E>) |
| Intel      | Pentium Dual-Core T4200          | 2.00 | 143   | [70AE28A451E1](<Notebook/Acer/Aspire/Aspire 5737Z/70AE28A451E1>) |
| Intel      | Pentium N3710                    | 1.60 | 143   | [A9E04C353111](<Notebook/ASUSTek Computer/X751/X751SA/A9E04C353111>) |
| Intel      | Core i5 M 560                    | 2.67 | 142   | [4CD8E7447BCF](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537CC5/4CD8E7447BCF>) |
| Intel      | Pentium Silver N5000             | 1.10 | 141   | [222540F56EB8](<Notebook/Dell/Latitude/Latitude 3190/222540F56EB8>) |
| Intel      | Core i7-3632QM                   | 2.20 | 141   | [F3A46F755B08](<Notebook/Hewlett-Packard/ProBook/ProBook 4540s/F3A46F755B08>) |
| Intel      | Core i7-5600U                    | 2.60 | 141   | [15A99CEFC60A](<Notebook/Dell/Latitude/Latitude E7450/15A99CEFC60A>) |
| Intel      | Core i3-4030U                    | 1.90 | 141   | [0D939CEB1C39](<Notebook/Acer/Aspire/Aspire E5-571/0D939CEB1C39>) |
| Intel      | Core i5-6600K                    | 3.50 | 141   | [4023F73158C0](<Desktop/MSI/MS/MS-7977/4023F73158C0>) |
| Intel      | Pentium M processor              | 1.20 | 140   | [9F658ADA0B8C](<Notebook/Fujitsu Siemens/AMILO/AMILO Pro V2085/9F658ADA0B8C>) |
| Intel      | Core i3-8130U                    | 2.20 | 140   | [843240D4F665](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KQS0B800/843240D4F665>) |
| Intel      | Core i5-9400F                    | 2.90 | 140   | [61CCACD32BF7](<Desktop/ASRock/B365/B365M-HDV/61CCACD32BF7>) |
| Intel      | Core 2 Duo E7400                 | 2.80 | 139   | [A182B9C1083D](<Desktop/Dell/OptiPlex/OptiPlex 360/A182B9C1083D>) |
| Intel      | Pentium G630                     | 2.70 | 139   | [95E149EAB845](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LE/95E149EAB845>) |
| AMD        | Ryzen 3 3200U with Radeon Veg... |      | 138   | [3776BE581EA4](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db1xxx/3776BE581EA4>) |
| Intel      | Pentium Dual-Core E5400          | 2.70 | 138   | [8C4550B7A236](<Desktop/Hewlett-Packard/NY705AA-ABL/NY705AA-ABL p6204y/8C4550B7A236>) |
| Intel      | Core i5-4440                     | 3.10 | 138   | [5679A1E0F90A](<Desktop/ASUSTek Computer/All/All Series/5679A1E0F90A>) |
| Intel      | Core i7-4710HQ                   | 2.50 | 138   | [C9A4FBC6CC20](<Notebook/ASUSTek Computer/N550/N550JK/C9A4FBC6CC20>) |
| Intel      | Core 2 Duo E4500                 | 2.20 | 137   | [A00073A380BB](<Desktop/Hewlett-Packard/Compaq/Compaq dc5700 Microtower/A00073A380BB>) |
| Intel      | Core i7-8850H                    | 2.60 | 137   | [87A913ED52D7](<Notebook/Hewlett-Packard/ZBook/ZBook 17 G5/87A913ED52D7>) |
| Intel      | Core i5 750                      | 2.67 | 137   | [B36DC4286599](<Desktop/Gigabyte Technology/P55/P55M-UD2/B36DC4286599>) |
| Intel      | Pentium P6200                    | 2.13 | 137   | [BBDFB7B4C795](<Notebook/Acer/Aspire/Aspire 5733Z/BBDFB7B4C795>) |
| Intel      | Core i5 M 430                    | 2.27 | 136   | [16E400040011](<Notebook/Dell/Studio/Studio 1749/16E400040011>) |
| Intel      | Pentium N4200                    | 1.10 | 134   | [B50AFE691E19](<Notebook/Acer/Aspire/Aspire ES1-132/B50AFE691E19>) |
| Intel      | Core i5-3330                     | 3.00 | 133   | [A200DB8D59E6](<Desktop/Gigabyte Technology/H61/H61M-DS2/A200DB8D59E6>) |
| Intel      | Core 2 Duo E8500                 | 3.16 | 132   | [37AA4ADCE327](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO E5730/37AA4ADCE327>) |
| AMD        | E-300 APU with Radeon HD Grap... |      | 131   | [C4520EE41BBA](<Desktop/Acer/Aspire/Aspire X1430/C4520EE41BBA>) |
| Intel      | Atom N570                        | 1.66 | 131   | [13EB7525030C](<Notebook/ASUSTek Computer/1011/1011PX/13EB7525030C>) |
| Intel      | Core i7-4770K                    | 3.50 | 131   | [1994E7184BE8](<Desktop/ASUSTek Computer/All/All Series/1994E7184BE8>) |
| Intel      | Pentium G3220                    | 3.00 | 131   | [27BE6AA7E202](<Desktop/ASUSTek Computer/All/All Series/27BE6AA7E202>) |
| Intel      | Core i3-10100                    | 3.60 | 130   | [370152E34E95](<Desktop/Gigabyte Technology/H410M/H410M H/370152E34E95>) |
| Intel      | Core i7-2677M                    | 1.80 | 130   | [588BA5B99F69](<Notebook/Toshiba/PORTEGE/PORTEGE Z830/588BA5B99F69>) |
| AMD        | A8-7410 APU with AMD Radeon R... |      | 129   | [DB0B516E7227](<Notebook/Lenovo/IdeaPad/IdeaPad 110-15ACL 80TJ/DB0B516E7227>) |
| Intel      | Core i7-7600U                    | 2.80 | 129   | [D3E48CC00280](<Notebook/Dell/Latitude/Latitude 5580/D3E48CC00280>) |
| Intel      | Pentium P6100                    | 2.00 | 129   | [281A2D7E86DE](<Notebook/Acer/Aspire/Aspire 4738Z/281A2D7E86DE>) |
| Intel      | Celeron N4100                    | 1.10 | 127   | [A06CAC27185E](<Notebook/UMAX/VisionBook/VisionBook 15Wg Plus/A06CAC27185E>) |
| Intel      | Atom D525                        | 1.80 | 127   | [4A875927140B](<Desktop/Standard/XS/XS35/4A875927140B>) |
| Intel      | Core 2 Duo T7500                 | 2.20 | 126   | [BEAC6535D134](<Notebook/Toshiba/Satellite/Satellite U300/BEAC6535D134>) |
| Intel      | 11th Gen Core i7-11390H          | 3.40 | 125   | [8F79CD741C6A](<Notebook/Acer/Aspire/Aspire AV15-51/8F79CD741C6A>) |
| Intel      | Core i5-9400                     | 2.90 | 125   | [8E72A411386D](<Desktop/Gigabyte Technology/Z390/Z390 UD/8E72A411386D>) |
| Intel      | Core i3-2370M                    | 2.40 | 125   | [C606E552CA9D](<Notebook/Hewlett-Packard/Pavilion/Pavilion g4/C606E552CA9D>) |
| Intel      | Core i7-10700                    | 2.90 | 124   | [97C1F8B840C8](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8>) |
| Intel      | Celeron N3450                    | 1.10 | 124   | [8D451E22FBA6](<Notebook/Medion/E/E11201/8D451E22FBA6>) |
| Intel      | Core i3 550                      | 3.20 | 123   | [CD13ABD91DA2](<Desktop/Hewlett-Packard/PPPPP-CCC#MMMMMMMM/PPPPP-CCC#MMMMMMMM/CD13ABD91DA2>) |
| Intel      | Pentium 4                        | 3.20 | 122   | [A43658F87F83](<Desktop/Fujitsu Siemens/D2156/D2156-A1/A43658F87F83>) |
| Intel      | Core 2 Duo T8100                 | 2.10 | 122   | [258D5EEEFCDD](<Notebook/Toshiba/dynabook/dynabook SS M42 210E-3W/258D5EEEFCDD>) |
| AMD        | FX -6100 Six-Core                |      | 121   | [BE1BD60498B9](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/BE1BD60498B9>) |
| Intel      | Pentium 4                        | 3.00 | 121   | [664E7BEB3DAE](<Desktop/Gigabyte Technology/8IPE1000/8IPE1000-G/664E7BEB3DAE>) |
| Intel      | Core 2 Duo T7250                 | 2.00 | 121   | [2E4E795E6EF5](<Notebook/Hewlett-Packard/Compaq/Compaq 6720s/2E4E795E6EF5>) |
| Intel      | Core 2 Duo T8300                 | 2.40 | 121   | [8FF6EAC5652A](<Notebook/Dell/Inspiron/Inspiron 1720/8FF6EAC5652A>) |
| Intel      | Pentium G620                     | 2.60 | 121   | [D98A1DAB1265](<Desktop/Dell/OptiPlex/OptiPlex 390/D98A1DAB1265>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 3266 | 963   | [40E4E0D39D59](<Notebook/Lenovo/IdeaPad/IdeaPad 530S-14ARR 81H1/40E4E0D39D59>) |
| SK hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2667 | 943   | [CF634F337F26](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MR001YMZ/CF634F337F26>) |
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 929   | [6451DAC2C40C](<Notebook/Clevo/W240/W240EL-W250ELQ-W270ELQ/6451DAC2C40C>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 843   | [91236DA4B8CC](<Notebook/Hewlett-Packard/15/15/91236DA4B8CC>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 790   | [BE159E2FFF98](<Notebook/Lenovo/ThinkPad/ThinkPad T440 20B7A0CYFR/BE159E2FFF98>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 787   | [E10E74F99078](<Convertible/Lenovo/ThinkPad/ThinkPad L13 Yoga Gen 2 20VK0019US/E10E74F99078>) |
|            | 123456789012345678 SODIMM... | 2 GB     |      | 2400 | 656   | [F85ED92E93ED](<Notebook/GPU Company/GWTC116/GWTC116-2/F85ED92E93ED>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 650   | [2EDB83247697](<Notebook/Hewlett-Packard/Notebook/Notebook/2EDB83247697>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 649   | [5AD4BE07916A](<Notebook/Lenovo/IdeaPad/IdeaPad 320-15IKB 80YH/5AD4BE07916A>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 644   | [B84254541CB4](<Notebook/Lenovo/ThinkPad/ThinkPad Edge E320 129885G/B84254541CB4>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 638   | [36027F8271C2](<Desktop/ASUSTek Computer/P5/P5Q/36027F8271C2>) |
|            | Module DIMM SDRAM            | 2048 MB  |      |      | 616   | [367737B0531D](<Desktop/ECS/G31/G31T-M7/367737B0531D>) |
|            | Module DIMM                  | 4096 MB  |      | 1333 | 570   | [9A8304B2EB9E](<Desktop/Gigabyte Technology/GA-970/GA-970A-UD3/9A8304B2EB9E>) |
|            | Module DIMM                  | 2048 MB  |      | 800  | 568   | [4C1C2EA37337](<Desktop/Gigabyte Technology/M56/M56S-S3/4C1C2EA37337>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 567   | [674D96FDF457](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus M15 GU502LW_GU502LW/674D96FDF457>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 560   | [C215D8839BA5](<Notebook/Panasonic/CF-54/CF-54-1/C215D8839BA5>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 545   | [4BEE0CAA54AA](<Notebook/Hewlett-Packard/250/250 G5 Notebook PC/4BEE0CAA54AA>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 525   | [6AF4025C842E](<Notebook/Hewlett-Packard/Laptop/Laptop 15-da1xxx/6AF4025C842E>) |
|            | Module DIMM                  | 2048 MB  |      | 1333 | 516   | [196D4EF3C39F](<Desktop/Gigabyte Technology/GA-890/GA-890GPA-UD3H/196D4EF3C39F>) |
|            | Module DIMM SDRAM            | 1024 MB  |      |      | 493   | [CAC1B02939F7](<Desktop/MSI/MS-7210/MS-7210 100/CAC1B02939F7>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 478   | [C358BF3191FD](<Notebook/ASUSTek Computer/X501/X501A1/C358BF3191FD>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2048 MB  | DDR3 | 4199 | 474   | [03CF7A67BAC6](<Notebook/Dell/Latitude/Latitude E5520/03CF7A67BAC6>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 463   | [5F4D0AB0905E](<Notebook/Lenovo/Legion/Legion Y540-15IRH 81SX/5F4D0AB0905E>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8192 MB  | DDR3 | 1600 | 463   | [4D3BE90674ED](<Notebook/Lenovo/E50-80/E50-80 80J2/4D3BE90674ED>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 461   | [B36E5125492E](<Notebook/Toshiba/Satellite/Satellite L855/B36E5125492E>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2048 MB  |      | 1600 | 456   | [255277C340F9](<Notebook/Fujitsu/T/T900/255277C340F9>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3600 | 451   | [0A9E01FDC5FC](<Desktop/MSI/MS-7/MS-7A34/0A9E01FDC5FC>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 433   | [995D0AA58091](<Notebook/Lenovo/IdeaPad/IdeaPad 330S-15IKB 81F5/995D0AA58091>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8192 MB  | DDR3 | 1867 | 422   | [441E0E237259](<Notebook/Acer/Aspire/Aspire E5-571G/441E0E237259>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2667 | 405   | [2144FBCACB95](<Notebook/ASUSTek Computer/VivoBook/VivoBook 15_ASUS Laptop X507UAR/2144FBCACB95>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8192 MB  | DDR3 | 1600 | 397   | [5951FA74A2EE](<Notebook/Lenovo/ThinkPad/ThinkPad W541 20EGS0B010/5951FA74A2EE>) |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 381   | [A3EC1FBD0030](<Notebook/Lenovo/ThinkPad/ThinkPad T470 20HD0001MX/A3EC1FBD0030>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 800  | 380   | [35969E35F43D](<Desktop/Intel/DG41RQ/DG41RQ AAE54511-203/35969E35F43D>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 372   | [AA102333E166](<Desktop/Standard/XS/XS35/AA102333E166>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 367   | [71FFDA7F373E](<Notebook/Dell/Latitude/Latitude 7490/71FFDA7F373E>) |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8 GB     | DDR4 | 3200 | 358   | [7E43A9DF4838](<Notebook/Lenovo/V17/V17 G2 ITL 82NX/7E43A9DF4838>) |
| SK hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 351   | [4DDB8C367C5E](<Convertible/Lenovo/Yoga/Yoga 530-14IKB 81EK/4DDB8C367C5E>) |
| Samsung    | M471A1K43EB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 343   | [61779DC30678](<Notebook/Hewlett-Packard/Laptop/Laptop 17-cn2xxx/61779DC30678>) |
| SK hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 335   | [159C1420443D](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-dk0xxx/159C1420443D>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3200 | 318   | [B647CF3822F1](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-G GAMING/B647CF3822F1>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 1600 | 318   | [5F478F119DC0](<Desktop/Shuttle/SZ/SZ77/5F478F119DC0>) |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8 GB     | DDR4 | 3200 | 315   | [BA29145B1BAF](<Notebook/Lenovo/ThinkBook/ThinkBook 15 G2 ARE 20VG/BA29145B1BAF>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 312   | [DB0B516E7227](<Notebook/Lenovo/IdeaPad/IdeaPad 110-15ACL 80TJ/DB0B516E7227>) |
|            | Module SODIMM                | 2048 MB  | DDR2 |      | 307   | [E55BD7ACEF7B](<Notebook/Acer/Aspire/Aspire 5110/E55BD7ACEF7B>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 304   | [25DC47FCD4CF](<Notebook/Apple/MacBook3/MacBook3,1/25DC47FCD4CF>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 | 1600 | 297   | [0931B22FD179](<Desktop/ASRock/Z97/Z97 Extreme4/0931B22FD179>) |
|            | Module DIMM                  | 1024 MB  |      | 800  | 297   | [379945E91382](<Desktop/Gigabyte Technology/G41/G41M-ES2L/379945E91382>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4096 MB  | DDR3 | 1334 | 296   | [BD76C9627370](<Notebook/ASUSTek Computer/X202/X202E/BD76C9627370>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1333 | 295   | [BE1BD60498B9](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/BE1BD60498B9>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 667  | 294   | [AE084EA145E6](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO EDITION P2511/AE084EA145E6>) |
| SK hynix   | HMT451S6AFR8A-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 293   | [EB7267A67BDA](<Notebook/ASUSTek Computer/X550/X550LB/EB7267A67BDA>) |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 291   | [11F61137DC15](<Notebook/Dynabook/Satellite/Satellite Pro C50-J/11F61137DC15>) |
| Micron     | 8ATF1G64HZ-3G2J1 SODIMM      | 8 GB     | DDR4 | 3200 | 289   | [69E8EF1A2769](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DT_FX505DT/69E8EF1A2769>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 8400 | 280   | [9654B0B310BA](<Desktop/Others/Others/Others/9654B0B310BA>) |
| Samsung    | M471B5673FH0-CH9 SODIMM      | 2048 MB  | DDR3 | 1334 | 279   | [E48B9460A6B3](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2540p/E48B9460A6B3>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 667  | 276   | [AE084EA145E6](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO EDITION P2511/AE084EA145E6>) |
| SK hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2667 | 273   | [0A14953B346E](<Desktop/Dell/OptiPlex/OptiPlex 3050/0A14953B346E>) |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4 GB     | DDR4 | 3200 | 269   | [EEC49B509995](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ee1xxx/EEC49B509995>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 269   | [287C0142E54D](<Notebook/ASUSTek Computer/X555/X555LJ/287C0142E54D>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 267   | [B469300A3E04](<Notebook/Dell/Latitude/Latitude 5310/B469300A3E04>) |
|            | 123456789012345678 DIMM L... | 2 GB     |      | 2400 | 266   | [7E2DCAD143A6](<Desktop/Others/Others/Others/7E2DCAD143A6>) |
| Micron     | 8ATF1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 266   | [3735EB8699CE](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X510QA_X510QA/3735EB8699CE>) |
| SK hynix   | Module SODIMM                | 1 GB     | DDR2 | 800  | 264   | [D9B78B2BBE43](<Notebook/Apple/MacBook5/MacBook5,2/D9B78B2BBE43>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 261   | [99DA8E367A7A](<Desktop/Gigabyte Technology/Z68/Z68MA-D2H-B3/99DA8E367A7A>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 252   | [16E400040011](<Notebook/Dell/Studio/Studio 1749/16E400040011>) |
|            | Module SODIMM                | 1024 MB  | DDR2 |      | 251   | [AC99315BC1FF](<Notebook/Toshiba/Satellite/Satellite A100/AC99315BC1FF>) |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 3466 | 248   | [06D2617A49D3](<Desktop/Gigabyte Technology/Z370/Z370 HD3P/06D2617A49D3>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 244   | [BF600B17E00E](<Notebook/ASUSTek Computer/S550/S550CM/BF600B17E00E>) |
|            | Module SODIMM                | 1024 MB  | DDR2 | 667  | 242   | [061881953EF5](<Notebook/Lenovo/ThinkPad/ThinkPad SL500 27464DG/061881953EF5>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 242   | [3FD6E4DB1ED2](<Desktop/ASUSTek Computer/P5Q/P5Q SE2/3FD6E4DB1ED2>) |
| Micron     | 4ATF51264HZ-2G3B1 SODIMM     | 4 GB     | DDR4 | 2400 | 240   | [6637BFAE0708](<Notebook/Acer/Aspire/Aspire A315-53/6637BFAE0708>) |
|            | Module SODIMM                | 4096 MB  | DDR3 |      | 239   | [9465299787D1](<Notebook/Sony/SVF1521/SVF1521C6EW/9465299787D1>) |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     |      | 1334 | 235   | [221FB2041E0B](<Notebook/Fujitsu/FMVA705/FMVA705ABS/221FB2041E0B>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 233   | [169175B3E5B7](<Desktop/ASRock/A330/A330GC/169175B3E5B7>) |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16 GB    | DDR4 | 2667 | 233   | [057161CC5B29](<Notebook/Lenovo/ThinkPad/ThinkPad T470 20HES63400/057161CC5B29>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 3866 | 232   | [94E45CAB4EE0](<Desktop/Gigabyte Technology/Z390/Z390 GAMING X/94E45CAB4EE0>) |
| Micron     | 4ATF1G64HZ-3G2E1 Row Of C... | 8 GB     | DDR4 | 3200 | 231   | [6D5F5C296418](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14IIL05 81X1/6D5F5C296418>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8192 MB  | DDR4 | 3200 | 227   | [BC262F5312A0](<Notebook/Dell/Latitude/Latitude 5520/BC262F5312A0>) |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 226   | [391EED81DBAB](<Notebook/Lenovo/ThinkBook/ThinkBook 16p Gen 2 20YM/391EED81DBAB>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3600 | 225   | [D1E7CA404339](<Desktop/ASUSTek Computer/PRIME/PRIME X570-PRO/D1E7CA404339>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3600 | 222   | [2A24C69265A0](<Desktop/MSI/MS-7/MS-7C37/2A24C69265A0>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 220   | [D88E08C3A7A1](<Notebook/TerraQue/W65/W65_W67RB/D88E08C3A7A1>) |
| SK hynix   | H9CCNNNCLGALAR-NVD Row Of... | 8 GB     |      | 2133 | 220   | [1139C4064B3E](<Notebook/Dell/XPS/XPS 13 7390/1139C4064B3E>) |
| SK hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 215   | [A448AB0E32FF](<Notebook/Dell/Inspiron/Inspiron 5521/A448AB0E32FF>) |
| Samsung    | M471B5273CH0-CK0 SODIMM      | 4 GB     | DDR3 | 1333 | 215   | [B9DCF480A389](<Notebook/ASUSTek Computer/X401/X401A1/B9DCF480A389>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 214   | [13F02D223AC8](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770-US3/13F02D223AC8>) |
|            | Module DIMM                  | 2048 MB  |      | 667  | 212   | [FF39EAFDF33C](<Desktop/Gigabyte Technology/G33/G33M-S2/FF39EAFDF33C>) |
|            | Module DIMM                  | 4096 MB  |      | 1600 | 209   | [1FBAF6BE6F36](<Desktop/ASUSTek Computer/M4A785TD-M/M4A785TD-M EVO/1FBAF6BE6F36>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 2133 | 208   | [CC8F22CF0D4F](<Desktop/MSI/MS/MS-7922/CC8F22CF0D4F>) |
|            | Module DIMM                  | 1024 MB  |      | 667  | 200   | [379945E91382](<Desktop/Gigabyte Technology/G41/G41M-ES2L/379945E91382>) |
| Samsung    | M471A5244CB0-CWE Row Of C... | 4 GB     | DDR4 | 3200 | 197   | [0D45CB7AAF30](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15IML05 81WB/0D45CB7AAF30>) |
| SK hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2667 | 197   | [97C1F8B840C8](<Mini Pc/ZOTAC/ZBOX-ECM7307/ZBOX-ECM73070C-7307LH-53060C/97C1F8B840C8>) |
| SK hynix   | HMA82GS6JJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 197   | [D3E48CC00280](<Notebook/Dell/Latitude/Latitude 5580/D3E48CC00280>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 194   | [D52DC518DF62](<Notebook/Dell/Inspiron/Inspiron 5490/D52DC518DF62>) |
| Kingston   | KHX2400C15/8G DIMM           | 8 GB     | DDR4 | 3400 | 193   | [251C93855B45](<Desktop/MSI/MS-7/MS-7A33/251C93855B45>) |
|            | Module DIMM                  | 2048 MB  | DDR3 | 1333 | 193   | [25E2FF4C9B8F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/25E2FF4C9B8F>) |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8192 MB  | DDR4 | 3200 | 192   | [1DCD288DE1CB](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/1DCD288DE1CB>) |
| SK hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1800 | 192   | [4B34DC92D076](<Desktop/Dell/OptiPlex/OptiPlex 7010/4B34DC92D076>) |
| SK hynix   | HYMP125S64CP8-S6 SODIMM DDR  | 2 GB     |      | 800  | 192   | [F6A099116F75](<Notebook/Dell/Inspiron/Inspiron 1545/F6A099116F75>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4096 MB  | DDR3 | 1333 | 190   | [BA1DF2DADB62](<Notebook/ASUSTek Computer/K73/K73SJ/BA1DF2DADB62>) |
| SK hynix   | HMT41GS6AFR8A-PB SODIMM      | 8192 MB  | DDR3 | 1600 | 190   | [58E500E065B5](<Notebook/Lenovo/ThinkPad/ThinkPad W540 20BHS1J000/58E500E065B5>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 190   | [9DC8CA3DF416](<Notebook/Dell/Latitude/Latitude E7450/9DC8CA3DF416>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 190   | [A77DA1060A8E](<Desktop/Foxconn/H61/H61MXV-H67MXV/A77DA1060A8E>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 189   | [03EEFC9685DF](<Notebook/Lenovo/G50-70/G50-70 20351/03EEFC9685DF>) |
| Samsung    | M471A2K43DB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 189   | [F5BC18F8B347](<Notebook/Lenovo/Legion/Legion Y540-17IRH 81Q4/F5BC18F8B347>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 186   | [B50AFE691E19](<Notebook/Acer/Aspire/Aspire ES1-132/B50AFE691E19>) |
| SK hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 3200 | 185   | [36D732658869](<Notebook/ASUSTek Computer/S551/S551LN/36D732658869>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 184   | [578E80B42B1D](<Notebook/Dell/Vostro/Vostro 14-3468/578E80B42B1D>) |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3400 | 183   | [27EB1FCAC7E3](<Desktop/ASUSTek Computer/PRIME/PRIME Z490-A/27EB1FCAC7E3>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 183   | [2BE152EEFFDD](<Notebook/Lenovo/Legion/Legion 5 15ACH6 82JW/2BE152EEFFDD>) |
| Nanya      | NT4GC64B8HB0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 183   | [7713EE2713FC](<Notebook/Acer/Aspire/Aspire 5750G/7713EE2713FC>) |
| Samsung    | M471A2G44AM0-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 183   | [453DF2D4D0F6](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20S0S2FQ00/453DF2D4D0F6>) |
|            | Module DIMM                  | 2048 MB  |      | 400  | 182   | [0D061C50B134](<Desktop/Gigabyte Technology/EG41/EG41MFT-US2H/0D061C50B134>) |
| SK hynix   | HMT325S6BFR8C-H9 SODIMM      | 2 GB     |      | 1600 | 181   | [221FB2041E0B](<Notebook/Fujitsu/FMVA705/FMVA705ABS/221FB2041E0B>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 178   | [989373FD84A0](<Notebook/Acer/Aspire/Aspire E5-521G/989373FD84A0>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 178   | [EE2D95CF9A1E](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-USB3/EE2D95CF9A1E>) |
|            | Module DIMM SDRAM            | 512 MB   |      |      | 178   | [7CD02692A8A4](<Desktop/EVERCOM NETWORK/Others/Others/7CD02692A8A4>) |
| Elpida     | EBJ40UG8BBU0-GN-F SODIMM     | 4 GB     | DDR3 | 1600 | 173   | [8854B2161F24](<Notebook/Lenovo/ThinkPad/ThinkPad T420s 4174W2X/8854B2161F24>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 173   | [4A54E9E0D620](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 173   | [632E4360ACF2](<Notebook/Lenovo/20RD001/20RD001FHV/632E4360ACF2>) |
| Kingston   | 99U5584-005.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 172   | [7854EA01C399](<Desktop/ASUSTek Computer/F1/F1A75-V/7854EA01C399>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8192 MB  | DDR4 | 3200 | 169   | [168A3EC1E1EA](<Notebook/Hewlett-Packard/Victus/Victus by Laptop 16-e0xxx/168A3EC1E1EA>) |
| Samsung    | M471B5674QH0-YK0 SODIMM      | 2 GB     | DDR3 | 1600 | 169   | [AE366F96F926](<Notebook/Lenovo/Yoga/Yoga 300-11IBY 80M0/AE366F96F926>) |
| Samsung    | M471B5773DH0-CK0 SODIMM      | 2 GB     | DDR3 | 1600 | 169   | [0F767C61EAA3](<Notebook/Lenovo/V580c/V580c 20160/0F767C61EAA3>) |
| Micron     | 16JSF51264HZ-1G4D1 SODIMM    | 4 GB     | DDR3 | 1334 | 167   | [18328F956F7B](<Notebook/Hewlett-Packard/Others/Others/18328F956F7B>) |
|            | Module DIMM                  | 1024 MB  |      |      | 165   | [92C78BFA8A5B](<Desktop/EPoX Computer/nForce3/nForce3 DDR: 8KDA3I Series/92C78BFA8A5B>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4 GB     | DDR3 | 2133 | 165   | [D98A1DAB1265](<Desktop/Dell/OptiPlex/OptiPlex 390/D98A1DAB1265>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 165   | [B723043741B6](<Notebook/Dell/XPS/XPS 15 9570/B723043741B6>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 165   | [2D936D9BC482](<Notebook/Medion/X/X6816/2D936D9BC482>) |
| 48spaces   | 0123456789012345678901234... | 2 GB     | DDR2 | 667  | 159   | [5FAE2CF4B073](<Notebook/Samsung Electronics/NC210/NC210-NC110/5FAE2CF4B073>) |
| Nanya      | NT4GC64B8HG0NS-CG SODIMM     | 4096 MB  | DDR3 | 1334 | 159   | [E28D554E86AB](<Notebook/ASUSTek Computer/K54/K54HR/E28D554E86AB>) |
|            | Module SODIMM                | 4 GB     | DDR3 |      | 158   | [F82C1434057C](<Notebook/Sony/SVF1521/SVF1521G1EW/F82C1434057C>) |
| Samsung    | M471A1G44BB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 157   | [EAB3E679E00F](<Notebook/Lenovo/ThinkPad/ThinkPad L13 Gen 3 21BAS0X700/EAB3E679E00F>) |
| Samsung    | M471A5244BB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 155   | [5DBF672BE302](<Notebook/Hewlett-Packard/240/240 G6 Notebook PC/5DBF672BE302>) |
| Samsung    | M471A5244CB0-CTD Row Of C... | 4 GB     | DDR4 | 2667 | 155   | [10E137561305](<Notebook/HUAWEI/BOHK-WAX9/BOHK-WAX9X/10E137561305>) |
| Samsung    | M471A2G43AB2-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 154   | [8C478B25D8B8](<Notebook/Dell/Precision/Precision 7550/8C478B25D8B8>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 153   | [82074F847535](<Notebook/eMachines/eMG/eMG620/82074F847535>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 151   | [4A54E9E0D620](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/4A54E9E0D620>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1600 | 151   | [0FB5B778B8FA](<Desktop/Acer/Aspire/Aspire M7811/0FB5B778B8FA>) |
| SK hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 151   | [1CCC12BCA23A](<Notebook/ASUSTek Computer/Strix/Strix GL504GS_GL504GS/1CCC12BCA23A>) |
| Micron     | MT52L1G32D4PG-093 Row Of ... | 8 GB     |      | 2133 | 150   | [6AF72B9E35F5](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X403FA_X403FA/6AF72B9E35F5>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 149   | [ACA7A7AF2693](<Desktop/MSI/MS/MS-7673/ACA7A7AF2693>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 148   | [605BD9AFAC61](<Notebook/Toshiba/PORTEGE/PORTEGE R830/605BD9AFAC61>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 148   | [0D263D3267F2](<Notebook/Acer/Aspire/Aspire V5-571P/0D263D3267F2>) |
| Ramaxel    | RMT3160ED58E9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 148   | [14945A3CB42C](<Notebook/Medion/X681/X681X/14945A3CB42C>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 148   | [29258FB520FE](<Desktop/Lenovo/ThinkCentre/ThinkCentre M83 10AHS0CK14/29258FB520FE>) |
| Kingston   | KHX1600C10D3/4G DIMM         | 4096 MB  | DDR3 | 1866 | 147   | [43C25A9EA8C2](<Desktop/Hewlett-Packard/Compaq/Compaq Pro 6300 MT/43C25A9EA8C2>) |
|            | Module DIMM DDR              | 2048 MB  |      | 1333 | 147   | [AF56DA109B0C](<Desktop/ASUSTek Computer/P7H55-M/P7H55-M LE/AF56DA109B0C>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1600 | 147   | [273F2675355C](<Desktop/Biostar/A68/A68N-5100/273F2675355C>) |
| Elpida     | Module SODIMM                | 2 GB     | DDR3 | 1333 | 146   | [77E59E48D72A](<Notebook/ASUSTek Computer/UX31/UX31E/77E59E48D72A>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2048 MB  | DDR3 | 1333 | 146   | [D7591CF7C8EA](<Desktop/Dell/OptiPlex/OptiPlex 7010/D7591CF7C8EA>) |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 146   | [540AF9B46C29](<Notebook/Samsung Electronics/350V5/350V5C-351V5C-3540VC-3440VC/540AF9B46C29>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 146   | [2F3EAFFD46E4](<Notebook/Lenovo/IdeaPad/IdeaPad U510 20191/2F3EAFFD46E4>) |
| Elpida     | EBJ21UE8BDS0-DJ-F SODIMM     | 2 GB     |      | 1334 | 145   | [8908DA2EE463](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/8908DA2EE463>) |
| Micron     | 8JSF25664HZ-1G4D1 SODIMM     | 2 GB     | DDR3 | 1334 | 145   | [CEDFE32C9D52](<Notebook/Dell/Inspiron/Inspiron N5110/CEDFE32C9D52>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 144   | [F965CE321B66](<Notebook/Hewlett-Packard/Pavilion/Pavilion g6/F965CE321B66>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8 GB     | DDR3 | 1600 | 144   | [8AD38FC6EFF5](<Notebook/Notebook/W54/W54_55SU1,SUW/8AD38FC6EFF5>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     |      | 1600 | 142   | [2DA9AF5AE83C](<Desktop/ASRock/890FX/890FX Deluxe4/2DA9AF5AE83C>) |
| Elpida     | EBJ21UE8BFU0-DJ-F SODIMM     | 2048 MB  | DDR3 | 1334 | 139   | [312162E4A31C](<Notebook/Toshiba/Satellite/Satellite C855-12N/312162E4A31C>) |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2 GB     | DDR3 | 4199 | 139   | [5B5B94441F81](<Notebook/Toshiba/Satellite/Satellite C640/5B5B94441F81>) |
| Kingston   | KHX3200C16D4/16GX DIMM       | 16 GB    | DDR4 | 3600 | 138   | [8AA5E51F68FC](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/8AA5E51F68FC>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 800  | 137   | [B98875E62A9C](<Notebook/Samsung Electronics/RV408/RV408-RV508/B98875E62A9C>) |
| Micron     | 8ATF1G64HZ-2G3B1 SODIMM      | 8 GB     | DDR4 | 2400 | 135   | [B18B674EE141](<Notebook/Dell/Precision/Precision 7720/B18B674EE141>) |
| Ramaxel    | RMSA3270ME86H9F-2666 SODIMM  | 4 GB     | DDR4 | 2667 | 135   | [48120198E4DD](<Notebook/Lenovo/IdeaPad/IdeaPad L340-17API 81LY/48120198E4DD>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1867 | 135   | [A6D68C2F6B29](<Desktop/Dell/OptiPlex/OptiPlex 990/A6D68C2F6B29>) |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1333 | 134   | [DDB3CA994B67](<Notebook/Digibras/NH4/NH4CU03/DDB3CA994B67>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8 GB     | DDR3 | 1600 | 133   | [C3DF7CBECBA0](<Desktop/ASUSTek Computer/P8H77-M/P8H77-M PRO/C3DF7CBECBA0>) |
| SK hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 133   | [41F24CD9EBA0](<Notebook/Lenovo/ThinkPad/ThinkPad T530 24294A1/41F24CD9EBA0>) |
|            | Module DIMM                  | 4096 MB  |      | 400  | 132   | [CD88FBA23CCD](<Desktop/Gigabyte Technology/G41/G41M-Combo/CD88FBA23CCD>) |
| Kingston   | ACR256X64D3S1333C9 SODIMM    | 2 GB     | DDR3 | 1334 | 131   | [66FE7E8D7F44](<Notebook/Hewlett-Packard/630/630/66FE7E8D7F44>) |
|            | Module DIMM                  | 2048 MB  |      | 1066 | 131   | [C8ECDC6BA2DD](<Desktop/Gigabyte Technology/M52/M52LT-D3/C8ECDC6BA2DD>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 131   | [15315EE5426D](<Notebook/Acer/TravelMate/TravelMate 8572T/15315EE5426D>) |
| Kingston   | 99U5471-020.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 130   | [AA1E95BD9503](<Desktop/ASUSTek Computer/M4/M4A89GTD-PRO-USB3/AA1E95BD9503>) |
| SK hynix   | HMT325S6CFR8C-PB SODIMM      | 2048 MB  | DDR3 | 1600 | 129   | [655040974D4A](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2560p/655040974D4A>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 129   | [AA82EE9EA95F](<Notebook/Sony/SVE1713/SVE1713A1EW/AA82EE9EA95F>) |
| Ramaxel    | RMT3170ME68F9F1600 SODIMM    | 4 GB     | DDR3 | 1600 | 128   | [B477AFB73A44](<Notebook/Lenovo/B50-70/B50-70 80EU/B477AFB73A44>) |
| Samsung    | M4 70T5663QZ3-CF7 SODIMM DDR | 2 GB     |      | 2048 | 128   | [5940627C6D0F](<Notebook/Dell/Inspiron/Inspiron MM061/5940627C6D0F>) |
| SK hynix   | HMT451U6AFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 127   | [4DD5319CB14B](<Desktop/Lenovo/ThinkCentre/ThinkCentre M83 10AHS0W300/4DD5319CB14B>) |
| Micron     | 4ATF51264HZ-3G2J1 Row Of ... | 4 GB     | DDR4 | 3200 | 127   | [025CD388C420](<Notebook/Lenovo/IdeaPad/IdeaPad 5 14ALC05 82LM/025CD388C420>) |
| Ramaxel    | RMT3170EB68F9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 127   | [6FFE12406668](<Notebook/Lenovo/G/G700/6FFE12406668>) |
| Samsung    | M471B5173BH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 127   | [5A83E6F1C4D7](<Notebook/Lenovo/IdeaPad/IdeaPad S510p 20298/5A83E6F1C4D7>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 126   | [CEE8A0F5FCB6](<Notebook/Acer/Swift/Swift SF314-41/CEE8A0F5FCB6>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 125   | [0EAC158BB4C2](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15ARR 81D2/0EAC158BB4C2>) |
|            | Module SODIMM DDR            | 1024 MB  |      |      | 125   | [E587DFDCB4C9](<Notebook/IBM/ThinkPad/ThinkPad T41 23731HG/E587DFDCB4C9>) |
|            | Module DIMM                  | 1024 MB  | DDR2 |      | 125   | [A65895D913D5](<Desktop/ABIT/I-45/I-45CV/A65895D913D5>) |
|            | Module SODIMM DRAM           | 1024 MB  |      |      | 125   | [D0740CBC6042](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile V5535/D0740CBC6042>) |
| Samsung    | M471A4G43AB1-CWE SODIMM      | 32 GB    | DDR4 | 3200 | 125   | [512CE5A79924](<Desktop/ASRock/4X4-4000/4X4-4000 Series/512CE5A79924>) |
| Samsung    | M471B5273EB0-CK0 SODIMM      | 4 GB     | DDR3 | 4199 | 124   | [8BCDDD9F9C62](<Notebook/Toshiba/Satellite/Satellite C855/8BCDDD9F9C62>) |
| Samsung    | UBE3D4AA-MGCR Row Of Chip... | 2048 MB  |      | 4267 | 124   | [F74F913BD7D2](<Convertible/ASUSTek Computer/Zenbook/Zenbook UP5401EA_UP5401EA/F74F913BD7D2>) |
| Samsung    | K4EBE304EB-EGCG Row Of Ch... | 8 GB     |      | 2133 | 122   | [4EC50344FB96](<Notebook/ASUSTek Computer/UX430/UX430UNR/4EC50344FB96>) |
| Samsung    | M471A1K43BB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 122   | [033977C615EA](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N20008US/033977C615EA>) |
|            | Module SODIMM SDRAM          | 2048 MB  |      |      | 121   | [B2FE664B3D97](<Notebook/ASUSTek Computer/F5/F5SL/B2FE664B3D97>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 120   | [B0C3AEAA59D5](<Desktop/ASUSTek Computer/B150-PRO/B150-PRO D3/B0C3AEAA59D5>) |
| Kingston   | ACR16D3LS1KFG/4G SODIMM      | 4 GB     | DDR3 | 1600 | 120   | [909871A56E7E](<Notebook/Acer/Aspire/Aspire E3-111/909871A56E7E>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 333  | 120   | [FB088E456F37](<Desktop/ASUSTek Computer/P5/P5GC-MX/FB088E456F37>) |
|            | Module SODIMM                | 1 GB     | DDR2 | 667  | 120   | [258D5EEEFCDD](<Notebook/Toshiba/dynabook/dynabook SS M42 210E-3W/258D5EEEFCDD>) |
| Samsung    | M471B2873FHS-CH9 SODIMM      | 1 GB     | DDR3 | 1334 | 120   | [281A2D7E86DE](<Notebook/Acer/Aspire/Aspire 4738Z/281A2D7E86DE>) |
| Kingston   | KHX1866C10D3/4G DIMM         | 4 GB     | DDR3 | 1867 | 119   | [37C23860D721](<Desktop/ASUSTek Computer/All/All Series/37C23860D721>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 119   | [2254AF4107F2](<Notebook/ASUSTek Computer/X756/X756UJ/2254AF4107F2>) |
| SK hynix   | Module SODIMM                | 4 GB     | DDR3 | 1600 | 119   | [ED988FB747CF](<All In One/Apple/iMac13/iMac13,1/ED988FB747CF>) |
| Corsair    | CMK16GX4M2A2666C16 DIMM      | 8 GB     | DDR4 | 3400 | 118   | [C23E2E331FC1](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/C23E2E331FC1>) |
| Micron     | 8ATF1G64HZ-3G2R1 SODIMM      | 8 GB     | DDR4 | 3200 | 117   | [5D93153924FD](<Notebook/MSI/Katana/Katana GF66 11UE/5D93153924FD>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4096 MB  | DDR3 | 1600 | 116   | [D4F3D3623D0C](<Notebook/Dell/Inspiron/Inspiron 5558/D4F3D3623D0C>) |
| SK hynix   | HMA851S6DJR6N-XN SODIMM      | 4 GB     | DDR4 | 3200 | 116   | [265341C0BA65](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X415EA_X415EA/265341C0BA65>) |
| SK hynix   | HMT325S6BFR8C-H9 SODIMM      | 2048 MB  | DDR3 | 1333 | 115   | [03CF7A67BAC6](<Notebook/Dell/Latitude/Latitude E5520/03CF7A67BAC6>) |
| Patriot    | 3200 C16 Series DIMM         | 8 GB     | DDR4 | 3266 | 115   | [06D2617A49D3](<Desktop/Gigabyte Technology/Z370/Z370 HD3P/06D2617A49D3>) |
|            | Module DIMM                  | 2048 MB  | DDR2 |      | 114   | [0CAEFEDD2BC9](<Desktop/ECS/K8/K8M890M-M/0CAEFEDD2BC9>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 114   | [D87A74C2C54D](<Notebook/Lenovo/IdeaPad/IdeaPad 310-15ISK 80UH/D87A74C2C54D>) |
| SK hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 114   | [0217A612716E](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509JA_X509JA/0217A612716E>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 113   | [F2FC8D92167B](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NK000XBR/F2FC8D92167B>) |
|            | Module DIMM SDRAM            | 4096 MB  |      |      | 113   | [FD3682A77774](<Desktop/Intel/H/H55/FD3682A77774>) |
|            | Module SODIMM                | 2048 MB  | DDR3 |      | 112   | [4918FDDA4745](<Notebook/Sony/SVE1513/SVE1513C5E/4918FDDA4745>) |
| A-DATA     | DDR4 3200 DIMM               | 8 GB     | DDR4 | 3600 | 111   | [5CD9D1C7363B](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/5CD9D1C7363B>) |
| Nanya      | NT4GC64B8HG0NS-DI SODIMM     | 4 GB     | DDR3 | 1600 | 111   | [A91CB55D9DAD](<Notebook/ASUSTek Computer/X550/X550CA/A91CB55D9DAD>) |
| Micron     | 4ATS2G64HZ-3G2B1 SODIMM      | 16 GB    | DDR4 | 3200 | 110   | [C8933F6E73F1](<Notebook/Lenovo/ThinkPad/ThinkPad T15 Gen 2i 20W4CTO1WW/C8933F6E73F1>) |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1333 | 110   | [36A5543B052C](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4291T4Y/36A5543B052C>) |
| SK hynix   | HMA851S6CJR6N-VK Row Of C... | 4 GB     | DDR4 | 2667 | 109   | [26116FF2B2E2](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/26116FF2B2E2>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1333 | 109   | [BE1BD60498B9](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/BE1BD60498B9>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1600 | 109   | [B0100D0F1501](<Desktop/ASUSTek Computer/A68/A68HM-K/B0100D0F1501>) |
| SK hynix   | HMAA2GS6CJR8N-XN SODIMM      | 16 GB    | DDR4 | 3200 | 109   | [8B88F37C6042](<Notebook/Lenovo/ThinkBook/ThinkBook 15p Gen 2 21B1/8B88F37C6042>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 1600 | 108   | [1B67F8711069](<Tablet/Lenovo/MIIX/MIIX 320-10ICR 80XF/1B67F8711069>) |
| A-DATA     | AD73I1C1674EV SODIMM         | 4 GB     | DDR3 | 1334 | 106   | [912243495AB4](<Notebook/Hewlett-Packard/Pavilion/Pavilion g7/912243495AB4>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 333  | 106   | [AD7E535377DC](<Desktop/ASUSTek Computer/P5/P5SD2-VM/AD7E535377DC>) |
| Team       | TEAMGROUP-UD4-3200 DIMM      | 8 GB     | DDR4 | 3800 | 106   | [405CEAE381D2](<Desktop/ASRock/B450M/B450M Steel Legend/405CEAE381D2>) |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 105   | [753782FFE946](<Notebook/Acer/Aspire/Aspire A715-72G/753782FFE946>) |
|            | Module DIMM SDRAM            | 1 GB     |      |      | 105   | [E65CFCE88793](<Desktop/ASRock/G41/G41C-GS/E65CFCE88793>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1333 | 105   | [DB41A06B4FE4](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML310e Gen8 v2/DB41A06B4FE4>) |
| Samsung    | Module SODIMM                | 8 GB     | DDR4 | 2133 | 105   | [961F670F4BDF](<Notebook/Hewlett-Packard/ProBook/ProBook 650 G4/961F670F4BDF>) |
| Kingston   | KHX2666C15S4/16G SODIMM      | 16 GB    | DDR4 | 2667 | 104   | [D9525DA7254E](<Notebook/MSI/Modern/Modern 14 A10M/D9525DA7254E>) |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1600 | 104   | [DC30228D2ADB](<Tablet/ASUSTek Computer/T103/T103HAF/DC30228D2ADB>) |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4 GB     | DDR3 | 1867 | 104   | [D0383231F31D](<Desktop/Dell/OptiPlex/OptiPlex 3020/D0383231F31D>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 104   | [5CAAF3725021](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/5CAAF3725021>) |
| SK hynix   | HMT351U6CFR8C-H9 DIMM        | 4 GB     | DDR3 | 1600 | 103   | [CD1EB621EC76](<Desktop/Dell/OptiPlex/OptiPlex 790/CD1EB621EC76>) |
| SK hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 102   | [398AFC2DCD84](<Notebook/Acer/Aspire/Aspire A315-42/398AFC2DCD84>) |
| SK hynix   | HMA451S6AFR8N-TF SODIMM      | 4096 MB  | DDR4 | 2133 | 102   | [A7E6ADB389B1](<Desktop/ASUSTek Computer/D320/D320SF/A7E6ADB389B1>) |
|            | Module SODIMM SDRAM          | 1024 MB  |      |      | 101   | [B2FE664B3D97](<Notebook/ASUSTek Computer/F5/F5SL/B2FE664B3D97>) |
| Samsung    | M471B5273CH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 101   | [C606E552CA9D](<Notebook/Hewlett-Packard/Pavilion/Pavilion g4/C606E552CA9D>) |
| G.Skill    | F4-3200C16-8GIS DIMM         | 8 GB     | DDR4 | 3200 | 100   | [27C9C6FA7847](<Desktop/CSL-Computer/V2888/V28880w/27C9C6FA7847>) |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1600 | 100   | [DC27A3540C58](<Tablet/Lenovo/MIIX/MIIX 310-10ICR 80SG/DC27A3540C58>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1333 | 100   | [4B51A0766BCB](<Desktop/ASUSTek Computer/CROSSBLADE/CROSSBLADE RANGER/4B51A0766BCB>) |
| Samsung    | M4 70T5663EH3-CF7 SODIMM     | 2 GB     | DDR2 | 975  | 100   | [AE67D017FFD5](<Notebook/Toshiba/Satellite/Satellite L300D/AE67D017FFD5>) |
| Samsung    | M471A1G43DB0-CPB SODIMM      | 8 GB     | DDR4 | 2400 | 100   | [BD36213603BD](<Notebook/Lenovo/ThinkBook/ThinkBook 14-IML 20RV/BD36213603BD>) |
| SK hynix   | HMA82GS6DJR8N-XN SODIMM      | 16 GB    | DDR4 | 3200 | 100   | [85E79C2C1537](<Notebook/Dell/XPS/XPS 15 9500/85E79C2C1537>) |
|            | Module SODIMM                | 512 MB   | DDR2 |      | 98    | [2BEE4480A9C3](<Notebook/Fujitsu Siemens/AMILO/AMILO Pro Edition V3505/2BEE4480A9C3>) |
| Ramaxel    | RMT3170MN68F9F1600 SODIMM    | 4 GB     | DDR3 | 1600 | 98    | [27A8CB39F479](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK A555/27A8CB39F479>) |
| Samsung    | Module SODIMM                | 16384 MB | DDR4 | 2667 | 98    | [D5FE9D804340](<Notebook/Hewlett-Packard/EliteBook/EliteBook 755 G5/D5FE9D804340>) |
| Kingston   | KHX1600C10D3/8GX DIMM        | 8 GB     | DDR3 | 1600 | 97    | [59EF573E85F4](<Desktop/ASRock/970/970 Pro3 R2.0/59EF573E85F4>) |
| Ramaxel    | RMT3020EC58E9F1333 SODIMM    | 4 GB     | DDR3 | 4199 | 97    | [1F5C959CE79E](<Notebook/Lenovo/ThinkPad/ThinkPad L512 4444PS9/1F5C959CE79E>) |
| Samsung    | K4E6E304EC-EGCG Row Of Ch... | 4 GB     |      | 2133 | 97    | [1EC55A488EF5](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X432FA_S432FA/1EC55A488EF5>) |
| Samsung    | M378A1K43CB2-CTD DIMM        | 8 GB     | DDR4 | 3266 | 97    | [1B36F0DF1999](<Desktop/ASRock/B450/B450 Gaming K4/1B36F0DF1999>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| ASUSTek    | ASUS           | 42.2  | Li-ion  | 2632  | [F4D1F788E1](https://linux-hardware.org/?probe=f4d1f788e1) |
| Hewlett... | PABAS0241231   | 41.9  | Li-ion  | 1213  | [E1313AF3E6](https://linux-hardware.org/?probe=e1313af3e6) |
| Compal     | PABAS0241231   | 48.8  | Li-ion  | 927   | [47F5FE62AA](https://linux-hardware.org/?probe=47f5fe62aa) |
| Lenovo     | PABAS0241231   | 45.0  | Li-ion  | 774   | [9355511511](https://linux-hardware.org/?probe=9355511511) |
| MSI        | BIF0_9         | 51.4  | Li-ion  | 709   | [E69F8169FC](https://linux-hardware.org/?probe=e69f8169fc) |
| SMP        | bq20z451       | 63.2  | Li-ion  | 607   | [B951048D8F](https://linux-hardware.org/?probe=b951048d8f) |
| Intel SR 1 | SR Real        | 45.6  |         | 508   | [535CC48341](https://linux-hardware.org/?probe=535cc48341) |
| OEM        | standard       | 93.5  | Li-ion  | 467   | [D6C6781535](https://linux-hardware.org/?probe=d6c6781535) |
| Samsung    |                | 49    | Li-ion  | 466   | [A91BA19B0A](https://linux-hardware.org/?probe=a91ba19b0a) |
| Hewlett... | Primary        | 45    | Li-ion  | 436   | [C78F20F332](https://linux-hardware.org/?probe=c78f20f332) |
| Samsung    | SR Real        | 39.0  | Li-ion  | 374   | [167229560A](https://linux-hardware.org/?probe=167229560a) |
| Hewlett... | Primary        | 48    | Li-ion  | 372   | [C941DA38CD](https://linux-hardware.org/?probe=c941da38cd) |
| SANYO      | Li_Ion_4000mA  | 47.5  | Li-ion  | 366   | [8394909745](https://linux-hardware.org/?probe=8394909745) |
| ASUSTek    | A32-K55        | 48.0  | Li-ion  | 357   | [B1B0FA7485](https://linux-hardware.org/?probe=b1b0fa7485) |
| SMP        | DELL GPM0365   | 97.0  | Li-ion  | 342   | [15160B0649](https://linux-hardware.org/?probe=15160b0649) |
| Hewlett... | Primary        | 40    | Li-ion  | 280   | [48D87E5C6E](https://linux-hardware.org/?probe=48d87e5c6e) |
| LG         | PABAS0241231   | 48.9  | Li-ion  | 269   | [DA1C6920B6](https://linux-hardware.org/?probe=da1c6920b6) |
| SANYO      | 45N1773        | 23.2  | Li-ion  | 241   | [CB2A0EFE72](https://linux-hardware.org/?probe=cb2a0efe72) |
| Hewlett... | Primary        | 42    | Li-ion  | 238   | [3C422C5E96](https://linux-hardware.org/?probe=3c422c5e96) |
| Hewlett... | Primary        | 41    | Li-ion  | 237   | [446A548122](https://linux-hardware.org/?probe=446a548122) |
| DP         | bq20z451       | 54.3  | Li-ion  | 228   | [97D802A5D6](https://linux-hardware.org/?probe=97d802a5d6) |
| Hewlett... | Primary        | 44    | Li-ion  | 224   | [56542DE280](https://linux-hardware.org/?probe=56542de280) |
| Notebook   | BAT            | 49    | Li-ion  | 219   | [F63A54BF5F](https://linux-hardware.org/?probe=f63a54bf5f) |
| Hewlett... | Primary        | 39    | Li-ion  | 213   | [EC3EE4B9DA](https://linux-hardware.org/?probe=ec3ee4b9da) |
| LGC        | 45N1127        | 23.5  | Li-ion  | 212   | [8A7ED180C0](https://linux-hardware.org/?probe=8a7ed180c0) |
| Hewlett... | Primary        | 50    | Li-ion  | 209   | [A86BD404E0](https://linux-hardware.org/?probe=a86bd404e0) |
| Hewlett... | Primary        | 53    | Li-ion  | 205   | [1C98821416](https://linux-hardware.org/?probe=1c98821416) |
| Hewlett... | Primary        | 38    | Li-ion  | 202   | [A3065A1B59](https://linux-hardware.org/?probe=a3065a1b59) |
| Samsung    |                | 44    | Li-ion  | 193   | [9908964D4A](https://linux-hardware.org/?probe=9908964d4a) |
| SMP        | L16M2PB1       | 30.0  | Li-poly | 192   | [483415E8CB](https://linux-hardware.org/?probe=483415e8cb) |
| ASUSTek    | X550A26        | 38.0  | Li-ion  | 188   | [3D35FF8B68](https://linux-hardware.org/?probe=3d35ff8b68) |
| Hewlett... | Primary        | 56    | Li-ion  | 186   | [907A94AE07](https://linux-hardware.org/?probe=907a94ae07) |
| Hewlett... | Primary        | 43    | Li-ion  | 185   | [C8373114EF](https://linux-hardware.org/?probe=c8373114ef) |
| Hewlett... | Primary        | 46    | Li-ion  | 183   | [64BBFA416B](https://linux-hardware.org/?probe=64bbfa416b) |
| Hewlett... | Primary        | 41    | Li-ion  | 179   | [B3BF20B454](https://linux-hardware.org/?probe=b3bf20b454) |
| Hewlett... | Primary        | 36    | Li-ion  | 175   | [A0B1299BAA](https://linux-hardware.org/?probe=a0b1299baa) |
| SMP        | DELL G8VCF6C   | 52.0  | Li-poly | 175   | [F830561F82](https://linux-hardware.org/?probe=f830561f82) |
| LGC        | AP18C8K        | 48.0  | Li-ion  | 173   | [B76E0E7397](https://linux-hardware.org/?probe=b76e0e7397) |
| SANYO      | PABAS0241231   | 63.4  | Li-ion  | 172   | [44C5B43B8D](https://linux-hardware.org/?probe=44c5b43b8d) |
| SANYO      | AL12A32        | 37.0  | Li-ion  | 171   | [E9212685F5](https://linux-hardware.org/?probe=e9212685f5) |
| Notebook   | BAT            | 48    | Li-ion  | 164   | [1D50DA2BA5](https://linux-hardware.org/?probe=1d50da2ba5) |
| CPT-COS    | L16C2PB2       | 30.6  | Li-poly | 161   | [E80EA5C4AE](https://linux-hardware.org/?probe=e80ea5c4ae) |
| SANYO      | AL10B31        | 48.8  | Li-ion  | 160   | [5FE24A9991](https://linux-hardware.org/?probe=5fe24a9991) |
| SANYO      | 45N1775        | 23.2  | Li-ion  | 159   | [CB2A0EFE72](https://linux-hardware.org/?probe=cb2a0efe72) |
|            | Battery        |       |         | 158   | [8A7ED180C0](https://linux-hardware.org/?probe=8a7ed180c0) |
| Hewlett... | Primary        | 37    | Li-ion  | 154   | [FD991056E0](https://linux-hardware.org/?probe=fd991056e0) |
| SIMPLO     | PABAS0241231   | 77.0  | Li-ion  | 154   | [C17CFE4D6D](https://linux-hardware.org/?probe=c17cfe4d6d) |
| LGC        | AP18E8M        | 57.5  | Li-ion  | 151   | [E788D3FEE0](https://linux-hardware.org/?probe=e788d3fee0) |
| SMP        | L16M2PB2       | 35.0  | Li-poly | 149   | [BBE569DFF7](https://linux-hardware.org/?probe=bbe569dff7) |
| SANYO      | AL15A32        | 37.0  | Li-ion  | 148   | [EDFA9FCBEF](https://linux-hardware.org/?probe=edfa9fcbef) |
| Panasonic  | AP16M5J        | 37.0  | Li-ion  | 147   | [8849D7A1C9](https://linux-hardware.org/?probe=8849d7a1c9) |
| Panasonic  | Li_Ion_4000mA  | 47.5  | Li-ion  | 144   | [6B908B35CC](https://linux-hardware.org/?probe=6b908b35cc) |
| LG         | Li_Ion_4000mA  | 47.5  | Li-ion  | 139   | [289BD8C2FD](https://linux-hardware.org/?probe=289bd8c2fd) |
| SMP        | DELL 70N2F95   | 84.3  | Li-poly | 137   | [2AB4F57FF6](https://linux-hardware.org/?probe=2ab4f57ff6) |
| ASUSTek    | UX31-35        | 47.9  | Li-ion  | 136   | [1FB0CA13FF](https://linux-hardware.org/?probe=1fb0ca13ff) |
| LGC        | AC14B8K        | 48.9  | Li-ion  | 134   | [CBD0938F3C](https://linux-hardware.org/?probe=cbd0938f3c) |
| SANYO      | AS10D31        | 47.5  | Li-ion  | 132   | [05291D9029](https://linux-hardware.org/?probe=05291d9029) |
| Hewlett... | Primary        | 49    | Li-ion  | 131   | [23B5CBFB33](https://linux-hardware.org/?probe=23b5cbfb33) |
| Hewlett... | Primary        |       | Li-ion  | 130   | [716373F59A](https://linux-hardware.org/?probe=716373f59a) |
| LGC        | L16L2PB2       | 30.0  | Li-poly | 128   | [C53EC6A9C0](https://linux-hardware.org/?probe=c53ec6a9c0) |
| Sony       | 45N1111        | 23.2  | Li-poly | 126   | [BF207E9DC3](https://linux-hardware.org/?probe=bf207e9dc3) |
| ASUSTek    | F82-22         | 48.4  | Li-ion  | 122   | [E5AAD61A1B](https://linux-hardware.org/?probe=e5aad61a1b) |
| ASUSTek    | K52F-44        | 72.6  | Li-ion  | 121   | [AE414CF185](https://linux-hardware.org/?probe=ae414cf185) |
| LGC        | 45N1049        | 40.4  | Li-ion  | 121   | [8A0AF12A27](https://linux-hardware.org/?probe=8a0af12a27) |
| SMP        | DELL Y3F7Y6B   | 42.0  | Li-ion  | 120   | [9EAA09FAF0](https://linux-hardware.org/?probe=9eaa09faf0) |
| LG         | 004B3842343... | 48.9  | Li-ion  | 119   | [BD4C84DA60](https://linux-hardware.org/?probe=bd4c84da60) |
| ASUSTek    | X550A30        | 44.2  | Li-ion  | 118   | [053E93702B](https://linux-hardware.org/?probe=053e93702b) |
| Samsung    |                | 48    | Li-ion  | 118   | [F983DADFEB](https://linux-hardware.org/?probe=f983dadfeb) |
| SANYO      | GC86508SAT0    | 44.4  | Li-ion  | 117   | [F566395F99](https://linux-hardware.org/?probe=f566395f99) |
| LGC        | 5B10W139       | 57.0  | Li-poly | 116   | [A27C899176](https://linux-hardware.org/?probe=a27c899176) |
| TKBSS      | NS2P3SZMC4WR   | 49.5  | Li-ion  | 116   | [525C048249](https://linux-hardware.org/?probe=525c048249) |
| Emdoor     |  Li-ion        | 38.0  | Li-ion  | 115   | [DD406112DE](https://linux-hardware.org/?probe=dd406112de) |
| Hewlett... | Primary        | 35    | Li-ion  | 115   | [DDF0CB8A28](https://linux-hardware.org/?probe=ddf0cb8a28) |
| SANYO      | 00323341343... | 55.9  | Li-ion  | 115   | [4B45FABD96](https://linux-hardware.org/?probe=4b45fabd96) |
| Sony       | VGP-BPS26      | 43.2  | Li-ion  | 115   | [521DB31DFC](https://linux-hardware.org/?probe=521db31dfc) |
| Hewlett... | Primary        | 34    | Li-ion  | 113   | [1BF512EE24](https://linux-hardware.org/?probe=1bf512ee24) |
| Hewlett... | Primary        | 47    | Li-ion  | 113   | [34F1E1686E](https://linux-hardware.org/?probe=34f1e1686e) |
| Notebook   | BAT            | 62    | Li-ion  | 112   | [F4E4C58948](https://linux-hardware.org/?probe=f4e4c58948) |
| LGC        | 45N1113        | 23.5  | Li-ion  | 111   | [7FCB72C132](https://linux-hardware.org/?probe=7fcb72c132) |
| LGC        | AC14B18J       | 36.7  | Li-ion  | 110   | [1AF4545239](https://linux-hardware.org/?probe=1af4545239) |
| Hewlett... | Primary        | 32    | Li-ion  | 109   | [C8B979D035](https://linux-hardware.org/?probe=c8b979d035) |
| Lenovo     | BASE-BAT       | 30.0  | Li-poly | 108   | [D79463EA93](https://linux-hardware.org/?probe=d79463ea93) |
| Panasonic  | AS16A5K        | 41.4  | Li-ion  | 108   | [6F8DBB2E8E](https://linux-hardware.org/?probe=6f8dbb2e8e) |
| SANYO      | PABAS024       | 48.8  | Li-ion  | 107   | [4C0751AA89](https://linux-hardware.org/?probe=4c0751aa89) |
| Hewlett... | Primary        | 51    | Li-ion  | 105   | [C7308F11CE](https://linux-hardware.org/?probe=c7308f11ce) |
|            | 47.52          | 48    | Li-ion  | 101   | [775C7346EB](https://linux-hardware.org/?probe=775c7346eb) |
| SMP        | 01AV421        | 24.0  | Li-poly | 100   | [66B49186CB](https://linux-hardware.org/?probe=66b49186cb) |
| Hewlett... | Primary        | 28    | Li-ion  | 99    | [DD6FFB8639](https://linux-hardware.org/?probe=dd6ffb8639) |
| WB SR 1    | WB Lion        | 41.8  | Li-ion  | 99    | [A915E84A9A](https://linux-hardware.org/?probe=a915e84a9a) |
| ASUSTek    | X555-50        | 37.3  | Li-ion  | 98    | [C7F621E335](https://linux-hardware.org/?probe=c7f621e335) |
| Hewlett... | Primary        | 55    | Li-ion  | 97    | [E3F05FE37F](https://linux-hardware.org/?probe=e3f05fe37f) |
| Hewlett... | Primary        | 30    | Li-ion  | 95    | [168B3CF595](https://linux-hardware.org/?probe=168b3cf595) |
| Panasonic  | AP19B5L        | 53.0  | Li-ion  | 95    | [F7C7C572E4](https://linux-hardware.org/?probe=f7c7c572e4) |
| SMP        | 5B10W13933     | 46.0  | Li-poly | 94    | [C5687C048F](https://linux-hardware.org/?probe=c5687c048f) |
| ASUSTek    | K55--44        | 47.5  | Li-ion  | 92    | [0ABF7DF439](https://linux-hardware.org/?probe=0abf7df439) |
| SANYO      | 45N1001        | 71.3  | Li-ion  | 91    | [7AEC73DFA1](https://linux-hardware.org/?probe=7aec73dfa1) |
| CPT-COS    | L16C2PB1       | 35.3  | Li-poly | 89    | [C8A19F5567](https://linux-hardware.org/?probe=c8a19f5567) |
| Hewlett... | Primary        | 31    | Li-ion  | 88    | [4F777DF0E8](https://linux-hardware.org/?probe=4f777df0e8) |
| Razer      | Blade          | 70.6  |         | 87    | [4B2265C354](https://linux-hardware.org/?probe=4b2265c354) |
| Samsung    |                | 58    | Li-ion  | 87    | [EA4FDD80E6](https://linux-hardware.org/?probe=ea4fdd80e6) |
| Lenovo ... |                | 28    |         | 86    | [784570BAE3](https://linux-hardware.org/?probe=784570bae3) |
| LGC        | L16L2PB3       | 35.0  | Li-poly | 86    | [EB559D913E](https://linux-hardware.org/?probe=eb559d913e) |
| LG         | PABAS024       | 40.0  | Li-ion  | 85    | [2DF8B64F07](https://linux-hardware.org/?probe=2df8b64f07) |
| Notebook   | BAT            | 74    | Li-ion  | 84    | [C775137D4F](https://linux-hardware.org/?probe=c775137d4f) |
| CosMX      | AP20CBL        | 53.0  | Li-ion  | 83    | [9D7736A816](https://linux-hardware.org/?probe=9d7736a816) |
| NVT        | Framewo        | 55.0  | Li-ion  | 82    | [78E63B3BD3](https://linux-hardware.org/?probe=78e63b3bd3) |
| SIMPLO     | SDI ICR18650   | 64.0  | Li-ion  | 82    | [DB8E950D12](https://linux-hardware.org/?probe=db8e950d12) |
| Celxpert   | 01AV448        | 45.7  | Li-poly | 80    | [95A77F6DCC](https://linux-hardware.org/?probe=95a77f6dcc) |
| Hewlett... | Primary        | 33    | Li-ion  | 80    | [11B0A5BAA1](https://linux-hardware.org/?probe=11b0a5baa1) |
| SMP        | DELL VN3N047   | 41.4  | Li-ion  | 80    | [FCCFCD375F](https://linux-hardware.org/?probe=fccfcd375f) |
| SMP        | 01AV447        | 45.7  | Li-poly | 79    | [1E65B46A12](https://linux-hardware.org/?probe=1e65b46a12) |
| Sony       | Li_Ion_4000mA  | 97.7  | Li-ion  | 79    | [1C163EB17F](https://linux-hardware.org/?probe=1c163eb17f) |
| Sunwoda-H  | HB4692Z9ECW... | 55.2  | Li-ion  | 78    | [1B0786EC5E](https://linux-hardware.org/?probe=1b0786ec5e) |
|            | 48.6           | 49    | Li-ion  | 77    | [5E78FF90CC](https://linux-hardware.org/?probe=5e78ff90cc) |
| Celxpert   | 01AV424        | 24.1  | Li-poly | 77    | [66B49186CB](https://linux-hardware.org/?probe=66b49186cb) |
| SMP        | 00HW023        | 23.5  | Li-poly | 77    | [4229BE0AFA](https://linux-hardware.org/?probe=4229be0afa) |
| Sony       |                | 42    | Li-ion  | 77    | [C182925286](https://linux-hardware.org/?probe=c182925286) |
| AS3GWAF3KC | GA50358        | 90.0  | Li-ion  | 76    | [E43DA42C9C](https://linux-hardware.org/?probe=e43da42c9c) |
| Hewlett... | Primary        | 89    | Li-ion  | 76    | [2AE0D7557B](https://linux-hardware.org/?probe=2ae0d7557b) |
| Hewlett... | Primary        | 42    | Li-ion  | 76    | [816F9E047A](https://linux-hardware.org/?probe=816f9e047a) |
| ASUSTek    | K53--52        | 48.4  | Li-ion  | 75    | [4F37849C94](https://linux-hardware.org/?probe=4f37849c94) |
| Hewlett... | Primary        | 29    | Li-ion  | 75    | [A3496C8509](https://linux-hardware.org/?probe=a3496c8509) |
| LGC        | 45N1011        | 86.6  | Li-ion  | 75    | [D95CCBF97D](https://linux-hardware.org/?probe=d95ccbf97d) |
| OEM        | FX50442        | 48.0  | Li-ion  | 74    | [F23FB5CCA0](https://linux-hardware.org/?probe=f23fb5cca0) |
| CPT-COS    | L17C4PB0       | 45.5  | Li-poly | 72    | [4B23B933B5](https://linux-hardware.org/?probe=4b23b933b5) |
| LGC        | 45N1005        | 56.2  | Li-ion  | 72    | [8695D820E4](https://linux-hardware.org/?probe=8695d820e4) |
| SMP        | DELL VM73283   | 42.0  | Li-poly | 72    | [DAD60CB86A](https://linux-hardware.org/?probe=dad60cb86a) |
| CPT-COS    | L14C3P6        | 36.6  | Li-ion  | 71    | [BD97B057E3](https://linux-hardware.org/?probe=bd97b057e3) |
| Hewlett... | Primary        | 26    | Li-ion  | 71    | [AA27725A50](https://linux-hardware.org/?probe=aa27725a50) |
| SANYO      | 45N1043        | 38.9  | Li-ion  | 71    | [74348D01F3](https://linux-hardware.org/?probe=74348d01f3) |
| Hewlett... | Primary        | 27    | Li-ion  | 70    | [CB00A3E89D](https://linux-hardware.org/?probe=cb00a3e89d) |
| Samsung... | DELL P8TC727   | 31.1  | Li-ion  | 70    | [B72361CA9E](https://linux-hardware.org/?probe=b72361ca9e) |
| SMP        | DELL TP1GT61   | 60.0  | Li-poly | 70    | [8C73ABE0EE](https://linux-hardware.org/?probe=8c73abe0ee) |
| Sunwoda    | R15B01W        | 60.5  | Li-ion  | 70    | [C41D566374](https://linux-hardware.org/?probe=c41d566374) |
| SANYO      | 01AV405        | 26.3  | Li-ion  | 69    | [4229BE0AFA](https://linux-hardware.org/?probe=4229be0afa) |
| Sunwoda-H  | HB4692Z9ECW-41 | 55.2  | Li-ion  | 69    | [A4F5DCE6D6](https://linux-hardware.org/?probe=a4f5dce6d6) |
| ASUSTek    | N56--52        | 57.2  | Li-ion  | 68    | [C49DEE996B](https://linux-hardware.org/?probe=c49dee996b) |
| SIMPLO     | BASE-BAT       | 38.0  | Li-poly | 68    | [CACF6A8831](https://linux-hardware.org/?probe=cacf6a8831) |
| ASUSTek    | F3---24        | 52.8  | Li-ion  | 67    | [3D4D35A9A7](https://linux-hardware.org/?probe=3d4d35a9a7) |
| ASUSTek    | K55--47        | 48.4  | Li-ion  | 67    | [5ECB1BB650](https://linux-hardware.org/?probe=5ecb1bb650) |
| Celxpert   | L19C3PD6       | 52.5  | Li-poly | 67    | [E1F824B7E1](https://linux-hardware.org/?probe=e1f824b7e1) |
| Dynapack   | HB4593R1ECW    | 56.3  | Li-ion  | 67    | [2CF04D07FB](https://linux-hardware.org/?probe=2cf04d07fb) |
| Notebook   | BAT            | 53    | Li-ion  | 67    | [5DA0DF2CF0](https://linux-hardware.org/?probe=5da0df2cf0) |
| SANYO      | L09S6Y02       | 38.9  | Li-ion  | 67    | [C59C5C0CDF](https://linux-hardware.org/?probe=c59c5c0cdf) |
| ASUSTek    | X453-42        | 31.7  | Li-ion  | 66    | [0A307C8C2B](https://linux-hardware.org/?probe=0a307c8c2b) |
| Hewlett... | Primary        | 38    | Li-ion  | 66    | [A36C4E671D](https://linux-hardware.org/?probe=a36c4e671d) |
| SMP        | 00NY493        | 90.0  | Li-poly | 66    | [85A4DE4E58](https://linux-hardware.org/?probe=85a4de4e58) |
|            | 48.84          | 49    | Li-ion  | 65    | [53538C2AE9](https://linux-hardware.org/?probe=53538c2ae9) |
| LGC        | 01AV445        | 45.0  | Li-poly | 65    | [47BFD44610](https://linux-hardware.org/?probe=47bfd44610) |
| SMP        | 01AV430        | 57.0  | Li-poly | 65    | [4B60A30117](https://linux-hardware.org/?probe=4b60a30117) |
| SMP        | L19M4PC0       | 60.0  | Li-poly | 65    | [4AD69AEA88](https://linux-hardware.org/?probe=4ad69aea88) |
| SANYO      | GRAPE32        | 21.9  | Li-ion  | 64    | [8154485976](https://linux-hardware.org/?probe=8154485976) |
| SMP        | L17M3PG2       | 57.0  | Li-poly | 64    | [00DF9B6BDA](https://linux-hardware.org/?probe=00df9b6bda) |
| Hewlett... | 5600           | 62.2  | Li-ion  | 63    | [C91E4D9C5A](https://linux-hardware.org/?probe=c91e4d9c5a) |
| LGC        | 01AV489        | 23.9  | Li-poly | 63    | [F67154866C](https://linux-hardware.org/?probe=f67154866c) |
| LGC        | L17L2PF1       | 30.0  | Li-poly | 63    | [580E3A1237](https://linux-hardware.org/?probe=580e3a1237) |
| Sunwoda    | 5B10X025       | 45.0  | Li-poly | 63    | [FC28F6D3F0](https://linux-hardware.org/?probe=fc28f6d3f0) |
| LGC        | 45N1025        | 62.2  | Li-ion  | 62    | [874513DB8D](https://linux-hardware.org/?probe=874513db8d) |
| SANYO      | 45N1023        | 48.8  | Li-ion  | 62    | [D8EC895BEA](https://linux-hardware.org/?probe=d8ec895bea) |
| ASUSTek    | F5---22        | 48.4  | Li-ion  | 61    | [1E5BB7661E](https://linux-hardware.org/?probe=1e5bb7661e) |
| Celxpert   | 5B10X026       | 45.0  | Li-poly | 61    | [AF9591CEDC](https://linux-hardware.org/?probe=af9591cedc) |
| LGC        | LNV-45N1       | 47.0  | Li-ion  | 61    | [A8090F51BC](https://linux-hardware.org/?probe=a8090f51bc) |
| Notebook   | BAT            | 35    | Li-ion  | 61    | [51EE77485D](https://linux-hardware.org/?probe=51ee77485d) |
| SMP        | AP18E7M        | 58.8  | Li-ion  | 61    | [EFB597952F](https://linux-hardware.org/?probe=efb597952f) |
| SMP        | DELL DM3WC64   | 60.0  | Li-poly | 61    | [DC5C96E431](https://linux-hardware.org/?probe=dc5c96e431) |
| Sunwoda-H  | HB4692J5ECW-31 | 41.4  | Li-ion  | 61    | [21577119AD](https://linux-hardware.org/?probe=21577119ad) |
| Hewlett... | Primary        | 54    | Li-ion  | 60    | [8A1EF40351](https://linux-hardware.org/?probe=8a1ef40351) |
| SANYO      | AP13B3K        | 53.4  | Li-ion  | 60    | [4FA79FB180](https://linux-hardware.org/?probe=4fa79fb180) |
| SMP        | 02DL005        | 51.0  | Li-poly | 60    | [7C862E338C](https://linux-hardware.org/?probe=7c862e338c) |
| SMP        | DELL VM73297   | 42.0  | Li-poly | 60    | [6A837BDF4D](https://linux-hardware.org/?probe=6a837bdf4d) |
| Hewlett... | Primary        | 40    | Li-ion  | 59    | [3C321C476A](https://linux-hardware.org/?probe=3c321c476a) |
| Hewlett... | Primary        | 57    | Li-ion  | 58    | [7ED9078ED9](https://linux-hardware.org/?probe=7ed9078ed9) |
| Lenovo     |                | 28    |         | 58    | [C8D8595AF5](https://linux-hardware.org/?probe=c8d8595af5) |
| LG         | LGC-LGC        | 80.0  | Li-ion  | 58    | [F8F6EC2123](https://linux-hardware.org/?probe=f8f6ec2123) |
| SANYO      | 00HW022        | 23.5  | Li-poly | 57    | [7A570EFE74](https://linux-hardware.org/?probe=7a570efe74) |
| SMP        | DELL GD1JP65   | 68.0  | Li-poly | 57    | [89F89D2A9E](https://linux-hardware.org/?probe=89f89d2a9e) |
| Sunwoda    | HB6081V1ECW-41 | 55.2  | Li-ion  | 57    | [3C82FEA068](https://linux-hardware.org/?probe=3c82fea068) |
| ASUSTek    | 1015PE         | 47.5  | Li-ion  | 56    | [6AA9D32DDA](https://linux-hardware.org/?probe=6aa9d32dda) |
| LGC        | 45N1738        | 71.1  | Li-ion  | 56    | [1701C2BAAE](https://linux-hardware.org/?probe=1701c2baae) |
| Samsung    |                | 24    | Li-ion  | 56    | [4B58936AD7](https://linux-hardware.org/?probe=4b58936ad7) |
| SMP        | ASMB016        | 57.7  | Li-ion  | 56    | [E7EBC0EC0E](https://linux-hardware.org/?probe=e7ebc0ec0e) |
| ASUSTek    | K53--27        | 37.8  | Li-ion  | 55    | [77CBFA62CD](https://linux-hardware.org/?probe=77cbfa62cd) |
| ASUSTek    | K56--30        | 33.0  | Li-ion  | 55    | [D878FAD4D0](https://linux-hardware.org/?probe=d878fad4d0) |
|            |                | 38    | Li-ion  | 55    | [73E11E9235](https://linux-hardware.org/?probe=73e11e9235) |
| LGC        | 01AV490        | 23.9  | Li-poly | 55    | [00DE843C75](https://linux-hardware.org/?probe=00de843c75) |
| Notebook   | BAT            | 60    | Li-ion  | 55    | [A4BD2C22EB](https://linux-hardware.org/?probe=a4bd2c22eb) |
| SANYO      | 42T4763        | 47.5  | Li-ion  | 55    | [40489044A0](https://linux-hardware.org/?probe=40489044a0) |
| Sony       |                | 51    | Li-ion  | 55    | [49DC80D94C](https://linux-hardware.org/?probe=49dc80d94c) |
| Hewlett... | Primary        | 52    | Li-ion  | 54    | [D0319BDF17](https://linux-hardware.org/?probe=d0319bdf17) |
| Lenovo ... |                | 38    |         | 54    | [5234925C5C](https://linux-hardware.org/?probe=5234925c5c) |
| LGC KT0... | AP18C8K        | 48.0  | Li-ion  | 54    | [6FD79B811F](https://linux-hardware.org/?probe=6fd79b811f) |
| OEM        | AS10D31        | 48.4  | Li-ion  | 54    | [5F191F449F](https://linux-hardware.org/?probe=5f191f449f) |
| SMP        | L19M3PF7       | 45.0  | Li-poly | 54    | [0E798DB6A8](https://linux-hardware.org/?probe=0e798db6a8) |
| ASUSTek    | N550-40        | 59.2  | Li-ion  | 53    | [A799667521](https://linux-hardware.org/?probe=a799667521) |
| GLK MRD    |  Li-ion        | 34.2  | Li-ion  | 53    | [208F6823ED](https://linux-hardware.org/?probe=208f6823ed) |
| Hewlett... | Primary        | 24    | Li-ion  | 53    | [A63003783D](https://linux-hardware.org/?probe=a63003783d) |
| LGC        | 02DL004        | 51.0  | Li-poly | 53    | [C81213C25E](https://linux-hardware.org/?probe=c81213c25e) |
| SANYO      | 42T4799        | 86.6  | Li-ion  | 53    | [AAAD7B3A55](https://linux-hardware.org/?probe=aaad7b3a55) |
| SMP        | 5B10W138       | 45.3  | Li-poly | 53    | [915C34D052](https://linux-hardware.org/?probe=915c34d052) |
| SMP        | L14M3P24       | 45.0  | Li-poly | 53    | [AD9AF07A7C](https://linux-hardware.org/?probe=ad9af07a7c) |
| Celxpert   | 5B10W138       | 45.7  | Li-poly | 52    | [B402183807](https://linux-hardware.org/?probe=b402183807) |
| APL MRD    |  Li-ion        | 38.0  | Li-ion  | 50    | [5FE84B74B0](https://linux-hardware.org/?probe=5fe84b74b0) |
| LGC        | 5B10X026       | 45.0  | Li-poly | 50    | [A438A0C994](https://linux-hardware.org/?probe=a438a0c994) |
| Panasonic  | AS10D51        | 47.5  | Li-ion  | 50    | [A74C66FC15](https://linux-hardware.org/?probe=a74c66fc15) |
| SANYO      | AS07B31        | 47.5  | Li-ion  | 50    | [224DC7209E](https://linux-hardware.org/?probe=224dc7209e) |
| Toshiba    | PABAS0241231   | 32.1  | Li-ion  | 50    | [338DA8730F](https://linux-hardware.org/?probe=338da8730f) |
| Dynapack   | HB4593J6ECW    | 41.2  | Li-ion  | 49    | [D07874C829](https://linux-hardware.org/?probe=d07874c829) |
| Hewlett... | Primary        | 22    | Li-ion  | 49    | [F78F58795C](https://linux-hardware.org/?probe=f78f58795c) |
| Samsung    |                | 45    | Li-ion  | 49    | [D016282342](https://linux-hardware.org/?probe=d016282342) |
| SANYO      | AS07A31        | 48.8  | Li-ion  | 49    | [4463D7323A](https://linux-hardware.org/?probe=4463d7323a) |
| SMP        | 5B10W139       | 50.5  | Li-poly | 49    | [E9D9710EF9](https://linux-hardware.org/?probe=e9d9710ef9) |
| Sunwoda    | 5B10W13935     | 46.0  | Li-poly | 49    | [BAB222234A](https://linux-hardware.org/?probe=bab222234a) |
| Notebook   | BAT            | 45    | Li-ion  | 48    | [6D89F7E662](https://linux-hardware.org/?probe=6d89f7e662) |
| ASUSTek    | UX425          | 50.0  | Li-ion  | 47    | [679F0C2F88](https://linux-hardware.org/?probe=679f0c2f88) |
| ASUSTek    | X200-30        | 33.8  | Li-ion  | 47    | [1F7840B315](https://linux-hardware.org/?probe=1f7840b315) |
| LGC        | L11L6Y01       | 40.4  | Li-ion  | 47    | [EFB4022E4C](https://linux-hardware.org/?probe=efb4022e4c) |
| SANYO      | 42T4791        | 56.2  | Li-ion  | 47    | [0C4578A674](https://linux-hardware.org/?probe=0c4578a674) |
| SMP        | L17M3PG1       | 52.5  | Li-poly | 47    | [510237FACD](https://linux-hardware.org/?probe=510237facd) |
| Sony       | PABAS024       | 52.7  | Li-ion  | 47    | [7A1A8BB421](https://linux-hardware.org/?probe=7a1a8bb421) |
| Sunwoda    | 5B10W13975     | 57.0  | Li-poly | 47    | [B9CFD37540](https://linux-hardware.org/?probe=b9cfd37540) |
| TPS        | S10            | 44.7  | Li-ion  | 47    | [FFAA34D0C1](https://linux-hardware.org/?probe=ffaa34d0c1) |
| Hewlett... | Primary        | 39    | Li-ion  | 46    | [198FA6162E](https://linux-hardware.org/?probe=198fa6162e) |
| LGC        | 01AV494        | 57.0  | Li-poly | 46    | [A467A04489](https://linux-hardware.org/?probe=a467a04489) |
| LGC        | 45N1147        | 56.2  | Li-ion  | 46    | [988731AC8D](https://linux-hardware.org/?probe=988731ac8d) |
| Notebook   | BAT            | 36    | Li-ion  | 46    | [069A675D2A](https://linux-hardware.org/?probe=069a675d2a) |
| SMP        | 45N1045        | 42.8  | Li-ion  | 46    | [5AAD144224](https://linux-hardware.org/?probe=5aad144224) |
| SMP        | 5B10X026       | 45.7  | Li-poly | 46    | [69D1F17B35](https://linux-hardware.org/?probe=69d1f17b35) |
| ASUSTek    | T12--22        | 46.2  | Li-ion  | 45    | [95935443C0](https://linux-hardware.org/?probe=95935443c0) |
| Celxpert   | 01AY969        | 80.4  | Li-poly | 45    | [D859E0FF10](https://linux-hardware.org/?probe=d859e0ff10) |
| Celxpert   | L20C4PC1       | 80.0  | Li-poly | 45    | [ACD4C4AF90](https://linux-hardware.org/?probe=acd4c4af90) |
| Hewlett... | Primary        | 37    | Li-ion  | 45    | [D809F15D99](https://linux-hardware.org/?probe=d809f15d99) |
| LGC        | 45N1735        | 47.5  | Li-ion  | 45    | [F945EC106E](https://linux-hardware.org/?probe=f945ec106e) |
| SANYO      | 45N1777        | 71.3  | Li-ion  | 45    | [A8DEB2307C](https://linux-hardware.org/?probe=a8deb2307c) |
| SMP        | 01AV452        | 24.0  | Li-poly | 45    | [96E067F5C8](https://linux-hardware.org/?probe=96e067f5c8) |
| SMP        | 5B11C732       | 57.0  | Li-poly | 45    | [1E70580006](https://linux-hardware.org/?probe=1e70580006) |
| SMP        | L09M6Y02       | 46.4  | Li-ion  | 45    | [2316D5DC8B](https://linux-hardware.org/?probe=2316d5dc8b) |
| Sunwoda    | L20D4PC1       | 80.0  | Li-poly | 45    | [2BAF2CBC85](https://linux-hardware.org/?probe=2baf2cbc85) |
| ASUSTek    | PA3533U        | 56.2  | Li-ion  | 44    | [F21E7219CE](https://linux-hardware.org/?probe=f21e7219ce) |
| Getac      | BC 4S1P        | 73.4  | Li-ion  | 44    | [40C181B615](https://linux-hardware.org/?probe=40c181b615) |
| Hewlett... | Primary        | 5     | Li-ion  | 44    | [0519471935](https://linux-hardware.org/?probe=0519471935) |
| Panasonic  | AS16B5J        | 62.2  | Li-ion  | 44    | [3497FEDA9F](https://linux-hardware.org/?probe=3497feda9f) |
| SANYO      | 45N1779        | 99.5  | Li-ion  | 44    | [228AEC8C45](https://linux-hardware.org/?probe=228aec8c45) |
| SMP        | 00HW029        | 52.1  | Li-poly | 44    | [7ADB4B2000](https://linux-hardware.org/?probe=7adb4b2000) |
| SMP        | 01AV446        | 45.3  | Li-poly | 44    | [779E8396D6](https://linux-hardware.org/?probe=779e8396d6) |
| ASUSTek    | UX325          | 67.3  | Li-ion  | 43    | [92CBB2E876](https://linux-hardware.org/?probe=92cbb2e876) |
| ASUSTek    | X550E26        | 37.4  | Li-ion  | 43    | [00FBE71B59](https://linux-hardware.org/?probe=00fbe71b59) |
| Hewlett... | Primary        | 18    | Li-ion  | 43    | [CC5F5EE72C](https://linux-hardware.org/?probe=cc5f5ee72c) |
| LGC        | 01AV478        | 57.0  | Li-poly | 43    | [47AC6239D5](https://linux-hardware.org/?probe=47ac6239d5) |
| LGC        | 02DL007        | 50.5  | Li-poly | 43    | [C7CA4B1477](https://linux-hardware.org/?probe=c7ca4b1477) |
| LGC        | 42T4911        | 47.5  | Li-ion  | 43    | [10DE9F17E1](https://linux-hardware.org/?probe=10de9f17e1) |

