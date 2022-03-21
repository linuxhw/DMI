DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by Linux users at https://linux-hardware.org.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 77411.

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
| Intel      | 11th Gen Core i5-1135G7          | 2.40 | 1350  | [C35BF89AA0CF](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Nano Gen 1 20UN002PCK/C35BF89AA0CF>) |
| Intel      | Core i5-8250U                    | 1.60 | 776   | [61077ED80EDE](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN002YPH/61077ED80EDE>) |
| Intel      | Core i7-8550U                    | 1.80 | 736   | [0D8B48BD5BBE](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L5A07TAU/0D8B48BD5BBE>) |
| Intel      | Core i5-7200U                    | 2.50 | 626   | [3C51D6FFF918](<Notebook/Hewlett-Packard/ZBook/ZBook 14u G4/3C51D6FFF918>) |
| Intel      | Core i7-9750H                    | 2.60 | 517   | [C6267579482D](<Notebook/Dell/G7/G7 7590/C6267579482D>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 510   | [40C39ADB36D3](<Desktop/MSI/MS-7/MS-7B89/40C39ADB36D3>) |
| Intel      | Core i7-8750H                    | 2.20 | 501   | [1020FE6EFFAE](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc0xxx/1020FE6EFFAE>) |
| Intel      | Core i7-10510U                   | 1.80 | 500   | [4F4BEFFC091C](<Notebook/Lenovo/ThinkPad/ThinkPad E15 20RD0016GE/4F4BEFFC091C>) |
| Intel      | Core i5-3210M                    | 2.50 | 483   | [1D425D5F0660](<Notebook/ASUSTek Computer/N56/N56VJ/1D425D5F0660>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 480   | [F1FF0FAF7B7F](<Notebook/HUAWEI/BOHK-WAX9/BOHK-WAX9X/F1FF0FAF7B7F>) |
| Intel      | Core i7-7700HQ                   | 2.80 | 446   | [4079965A25F0](<Notebook/Acer/Predator/Predator G3-572/4079965A25F0>) |
| Intel      | Core i5-6200U                    | 2.30 | 433   | [6D894B1F1576](<Notebook/ASUSTek Computer/X541/X541UV/6D894B1F1576>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 427   | [4001EA066FBB](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/4001EA066FBB>) |
| Intel      | Core i7-7500U                    | 2.70 | 421   | [3139F7166296](<Notebook/Dell/Inspiron/Inspiron 15-5578/3139F7166296>) |
| Intel      | Core i7-8565U                    | 1.80 | 409   | [974FF46B3D36](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2000KRT/974FF46B3D36>) |
| Intel      | Core i5-10210U                   | 1.60 | 401   | [70FDDABF265C](<Convertible/Lenovo/IdeaPad/IdeaPad C340-14IML 81TK/70FDDABF265C>) |
| Intel      | Core i5-2520M                    | 2.50 | 365   | [45C5B8282921](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4290EC5/45C5B8282921>) |
| Intel      | Core i5-3470                     | 3.20 | 365   | [10C8FEF878C9](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/10C8FEF878C9>) |
| Intel      | Celeron N2840                    | 2.16 | 360   | [BDC9D6953015](<Notebook/Lenovo/Flex/Flex 3-1120 80LX/BDC9D6953015>) |
| Intel      | Core i5-3230M                    | 2.60 | 356   | [8AADC209F667](<Notebook/Lenovo/G580/G580 20150/8AADC209F667>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 348   | [D6DA53EF4163](<Desktop/Hewlett-Packard/Compaq/Compaq 8000 Elite CMT PC/D6DA53EF4163>) |
| Intel      | Core i5-8265U                    | 1.60 | 341   | [3249008C6C8B](<Convertible/Lenovo/ThinkPad/ThinkPad L390 Yoga 20NT000JUS/3249008C6C8B>) |
| Intel      | Core i5-5200U                    | 2.20 | 339   | [209FEBF36AAD](<Notebook/Dell/Inspiron/Inspiron 3543/209FEBF36AAD>) |
| AMD        | FX -6300 Six-Core                |      | 310   | [AA95C0CBEBC9](<Desktop/MSI/Z1/Z1-7641/AA95C0CBEBC9>) |
| Intel      | Core i5-4210U                    | 1.70 | 308   | [F9AAF769770A](<Notebook/Lenovo/Flex/Flex 2-15 20405/F9AAF769770A>) |
| Intel      | Core i5-2410M                    | 2.30 | 304   | [98DCAD753107](<Notebook/Acer/Aspire/Aspire 4750/98DCAD753107>) |
| Intel      | Core i5-2450M                    | 2.50 | 304   | [2F15B1114F38](<Notebook/Dell/Inspiron/Inspiron N5110/2F15B1114F38>) |
| Intel      | Core i7-3770                     | 3.40 | 302   | [64F44AE44C19](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 All-in-One PC/64F44AE44C19>) |
| Intel      | Core i3-2120                     | 3.30 | 301   | [63009F68F515](<Desktop/MSI/MS/MS-7740/63009F68F515>) |
| Intel      | Core i5-3320M                    | 2.60 | 301   | [18483B5A05FE](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2347H76/18483B5A05FE>) |
| Intel      | Atom x5-Z8350                    | 1.44 | 299   | [D453CC3A0C14](<Notebook/Positivo/CHT12/CHT12CP/D453CC3A0C14>) |
| AMD        | FX-8350 Eight-Core               |      | 295   | [3894B389EDFC](<Desktop/ASUSTek Computer/Crosshair/Crosshair V Formula/3894B389EDFC>) |
| Intel      | Core i7-8565U                    | 1.80 | 295   | [3FAF3307D68D](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX450FDX_UX480FD/3FAF3307D68D>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 291   | [87D6BDDD71D0](<Notebook/Acer/Swift/Swift SF314-42/87D6BDDD71D0>) |
| Intel      | Core i7-10750H                   | 2.60 | 291   | [8CA23085D4F7](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15IMH05 81Y4/8CA23085D4F7>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 285   | [EA99D39366F3](<Desktop/Gigabyte Technology/AB350/AB350M-DS3H/EA99D39366F3>) |
| Intel      | Core i5-2400                     | 3.10 | 284   | [730ACCC800BC](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/730ACCC800BC>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 284   | [0E22532FC18F](<Notebook/Dell/XPS/XPS 15 9550/0E22532FC18F>) |
| Intel      | Core i3-3110M                    | 2.40 | 269   | [6A02236A28E8](<Notebook/Lenovo/B590/B590 20208/6A02236A28E8>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 268   | [075DC59573FF](<Desktop/MSI/MS-7/MS-7C36/075DC59573FF>) |
| Intel      | Core i3-2350M                    | 2.30 | 266   | [62EC09661292](<Notebook/Acer/P5/P5WE0/62EC09661292>) |
| AMD        | Ryzen 5 4500U with Radeon Gra... |      | 262   | [EDDF0EB351FF](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ARE05 81X2/EDDF0EB351FF>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 259   | [AA43E48AF02F](<Notebook/Dell/G5/G5 5505/AA43E48AF02F>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 257   | [15BC795C51C1](<Desktop/MSI/MS-7/MS-7C02/15BC795C51C1>) |
| Intel      | Core i5-6300U                    | 2.40 | 253   | [4B704EA0CF4E](<Notebook/Lenovo/ThinkPad/ThinkPad X260 20F5S6MF02/4B704EA0CF4E>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 252   | [0E378723C03A](<Desktop/MSI/MS/MS-7383/0E378723C03A>) |
| Intel      | Core i3-2100                     | 3.10 | 251   | [142916096E18](<Desktop/ASUSTek Computer/P8H61-MX/P8H61-MX R2.0/142916096E18>) |
| Intel      | Core i5-8265U                    | 1.60 | 247   | [7689799477A6](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX431FA/7689799477A6>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 245   | [95521280363C](<Desktop/ASUSTek Computer/P5Q/P5Q DELUXE/95521280363C>) |
| Intel      | Core i5-1035G1                   | 1.00 | 244   | [1F529A73EE54](<Convertible/Acer/Spin/Spin SP314-54N/1F529A73EE54>) |
| Intel      | Core i5-4200U                    | 1.60 | 244   | [8150F1E3711A](<Notebook/ASUSTek Computer/BU401/BU401LA/8150F1E3711A>) |
| Intel      | Core i5-2430M                    | 2.40 | 241   | [822FE70185B3](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4177R3U/822FE70185B3>) |
| Intel      | Core i3-5005U                    | 2.00 | 241   | [E361BE6FA3A4](<Notebook/Lenovo/IdeaPad/IdeaPad 100-15IBD 80QQ/E361BE6FA3A4>) |
| Intel      | Core i3-6006U                    | 2.00 | 241   | [7063C8B4BE67](<Notebook/Lenovo/IdeaPad/IdeaPad 320-15ISK 80XH/7063C8B4BE67>) |
| Intel      | Core i7-1065G7                   | 1.30 | 238   | [FF8F84C8407D](<Notebook/Dell/Inspiron/Inspiron 3793/FF8F84C8407D>) |
| Intel      | Core i7-4790                     | 3.60 | 238   | [ACEAAE9A8A20](<Desktop/Dell/Inspiron/Inspiron 3847/ACEAAE9A8A20>) |
| Intel      | Core i3-2310M                    | 2.10 | 237   | [B9B75BA01934](<Notebook/Toshiba/Satellite/Satellite C660/B9B75BA01934>) |
| Intel      | Core i3-3220                     | 3.30 | 237   | [49A9D2094E5F](<Desktop/Dell/OptiPlex/OptiPlex 7010/49A9D2094E5F>) |
| Intel      | Core i7-6500U                    | 2.50 | 233   | [7D9567596332](<Notebook/Dell/XPS/XPS 13 9350/7D9567596332>) |
| Intel      | Core i7-2600                     | 3.40 | 232   | [5DE062D01A07](<Desktop/Gigabyte Technology/H61/H61M-S2PV/5DE062D01A07>) |
| Intel      | Core i3 M 370                    | 2.40 | 230   | [903C3D17346D](<Notebook/Lenovo/B/B560/903C3D17346D>) |
| Intel      | Atom N270                        | 1.60 | 227   | [F956F70FEE41](<Notebook/Hewlett-Packard/2140/2140/F956F70FEE41>) |
| Intel      | Pentium B960                     | 2.20 | 225   | [57E25B3C59BC](<Notebook/Hewlett-Packard/Pavilion/Pavilion g6/57E25B3C59BC>) |
| Intel      | Celeron N3060                    | 1.60 | 219   | [2B556CB28D03](<Notebook/Hewlett-Packard/Notebook/Notebook/2B556CB28D03>) |
| Intel      | Core i3 M 380                    | 2.53 | 211   | [81177EF487D6](<Notebook/Acer/Aspire/Aspire 5733/81177EF487D6>) |
| Intel      | Atom N450                        | 1.66 | 208   | [720297696DAA](<Notebook/ASUSTek Computer/1005/1005P/720297696DAA>) |
| AMD        | Ryzen 5 2500U with Radeon Veg... |      | 205   | [E10C1473180B](<Notebook/Lenovo/IdeaPad/IdeaPad 330S-15ARR 81FB/E10C1473180B>) |
| Intel      | Core i5-4460                     | 3.20 | 203   | [94A541C6A3F8](<Desktop/MSI/MS/MS-7817/94A541C6A3F8>) |
| Intel      | Core i5-6500                     | 3.20 | 197   | [7E034427C03F](<All In One/Apple/iMac17/iMac17,1/7E034427C03F>) |
| Intel      | Core i7-2670QM                   | 2.20 | 196   | [1E712B2B15A0](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/1E712B2B15A0>) |
| AMD        | E-450 APU with Radeon HD Grap... |      | 195   | [9B4F4FE6A9A2](<Notebook/ASUSTek Computer/K53/K53U/9B4F4FE6A9A2>) |
| Intel      | Core i5-5300U                    | 2.30 | 195   | [7C50274A6FA9](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS14900/7C50274A6FA9>) |
| Intel      | Core i7-3630QM                   | 2.40 | 191   | [47231B7CAF33](<Notebook/ASUSTek Computer/K55/K55VD/47231B7CAF33>) |
| Intel      | Core i5-8300H                    | 2.30 | 190   | [E24BF48CCE67](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X571GT_A571GT/E24BF48CCE67>) |
| Intel      | Core i7-6700K                    | 4.00 | 190   | [4593A2E4A7D0](<Desktop/ASUSTek Computer/Z170I/Z170I PRO GAMING/4593A2E4A7D0>) |
| Intel      | Core i7-8650U                    | 1.90 | 185   | [A71C35C06A6A](<Notebook/Dell/XPS/XPS 13 9370/A71C35C06A6A>) |
| Intel      | Celeron N3350                    | 1.10 | 185   | [5082BCE4838F](<Notebook/Noblex/N14/N14WD21/5082BCE4838F>) |
| Intel      | Core i5-4570                     | 3.20 | 184   | [55A4AE88B3AA](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/55A4AE88B3AA>) |
| Intel      | Core i5-4300U                    | 1.90 | 177   | [C58673A1A81B](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS08Q00/C58673A1A81B>) |
| Intel      | Core i5-5250U                    | 1.60 | 176   | [CFD543BAF35C](<Notebook/Apple/MacBookAir7/MacBookAir7,2/CFD543BAF35C>) |
| Intel      | Core i7-6700                     | 3.40 | 176   | [35B21DA5C533](<Desktop/Acer/Predator/Predator G3-710/35B21DA5C533>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 175   | [E1EBBF30880A](<Desktop/Biostar/X370/X370GTN/E1EBBF30880A>) |
| Intel      | Core i3-3217U                    | 1.80 | 175   | [6530DDA6BF02](<Notebook/ASUSTek Computer/X450/X450CC/6530DDA6BF02>) |
| Intel      | Core i7-4770                     | 3.40 | 175   | [F087E85B32A8](<Desktop/ASUSTek Computer/All/All Series/F087E85B32A8>) |
| AMD        | Ryzen 5 1600 Six-Core            |      | 174   | [415BB315446E](<Desktop/MSI/MS-7/MS-7A34/415BB315446E>) |
| AMD        | Ryzen 7 PRO 4750U with Radeon... |      | 174   | [CE2A5D77CFEE](<Notebook/Hewlett-Packard/EliteBook/EliteBook 845 G7 Notebook PC/CE2A5D77CFEE>) |
| AMD        | Ryzen 7 3700U with Radeon Veg... |      | 171   | [1BB05E0BCDAC](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/1BB05E0BCDAC>) |
| AMD        | Athlon II X2 250                 |      | 170   | [238E55628E17](<Desktop/ASRock/N68C-S/N68C-S UCC/238E55628E17>) |
| Intel      | Pentium Dual-Core E5300          | 2.60 | 170   | [4396CCAAC4E1](<Desktop/Digitron/G31/G31T-M7/4396CCAAC4E1>) |
| Intel      | Core i7-5500U                    | 2.40 | 167   | [D6693998C7C0](<Notebook/Dell/XPS/XPS 13 9343/D6693998C7C0>) |
| Intel      | Core i7-4790K                    | 4.00 | 166   | [82EAE9110BBD](<Desktop/ASUSTek Computer/All/All Series/82EAE9110BBD>) |
| AMD        | Ryzen 5 5600X 6-Core             |      | 164   | [A2C546D96445](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/A2C546D96445>) |
| Intel      | Core i7-3770K                    | 3.50 | 164   | [060D31747A00](<Desktop/Biostar/TZ77/TZ77XE3/060D31747A00>) |
| Intel      | Pentium Dual-Core T4500          | 2.30 | 163   | [3BE885BACF91](<Notebook/Dell/Inspiron/Inspiron 1545/3BE885BACF91>) |
| Intel      | Core i3-2330M                    | 2.20 | 163   | [0A1512B3A973](<Notebook/Sony/VPCEH2/VPCEH2J1E/0A1512B3A973>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 162   | [451DDE02D840](<Desktop/MSI/MS-7/MS-7B89/451DDE02D840>) |
| Intel      | 11th Gen Core i7-11850H          | 2.50 | 162   | [E3FECBFB1971](<Notebook/MSI/Creator/Creator Z16 A11UET/E3FECBFB1971>) |
| Intel      | Atom N455                        | 1.66 | 162   | [8309E1560AC2](<Notebook/Samsung Electronics/NC210/NC210-NC110/8309E1560AC2>) |
| Intel      | Core i5-2500K                    | 3.30 | 160   | [EB2B21B97997](<Desktop/Gigabyte Technology/H61/H61M-S2PV/EB2B21B97997>) |
| Intel      | Core i7-2630QM                   | 2.00 | 160   | [CF65132134C6](<Notebook/Toshiba/QOSMIO/QOSMIO X770/CF65132134C6>) |
| Intel      | Core i5-3337U                    | 1.80 | 158   | [1E1289439524](<Notebook/Acer/Aspire/Aspire V5-571G/1E1289439524>) |
| Intel      | Core i5-7400                     | 3.00 | 156   | [23E79BD78168](<Desktop/Hewlett-Packard/OMEN/OMEN by Desktop PC 870-2XX/23E79BD78168>) |
| Intel      | Core i7-6600U                    | 2.60 | 156   | [046B50AF97D4](<Notebook/Dell/Latitude/Latitude 7480/046B50AF97D4>) |
| Intel      | Core i7-8700                     | 3.20 | 153   | [0F979600BFB1](<Desktop/Dell/Precision/Precision Tower 3431/0F979600BFB1>) |
| Intel      | Core i3-4005U                    | 1.70 | 153   | [17BC4634E0B7](<Notebook/Acer/Aspire/Aspire E5-571/17BC4634E0B7>) |
| Intel      | Core i5-4590                     | 3.30 | 152   | [9432F9FD1040](<Desktop/MSI/MS/MS-7918/9432F9FD1040>) |
| Intel      | Celeron N3050                    | 1.60 | 152   | [E75602F7D755](<Notebook/Hewlett-Packard/Notebook/Notebook/E75602F7D755>) |
| Intel      | Core i7-4700MQ                   | 2.40 | 151   | [B6072358711D](<Notebook/Lenovo/ThinkPad/ThinkPad T540p 20BE005YMH/B6072358711D>) |
| Intel      | Pentium 2020M                    | 2.40 | 149   | [F2681B1F8909](<Notebook/Medion/Akoya/Akoya E7221/F2681B1F8909>) |
| AMD        | FX-8320 Eight-Core               |      | 148   | [BDEBEEDB188E](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/BDEBEEDB188E>) |
| Intel      | Core i7-8665U                    | 1.90 | 148   | [A8B5AAF45EC2](<Notebook/Hewlett-Packard/ZBook/ZBook 15u G6/A8B5AAF45EC2>) |
| Intel      | Atom N2600                       | 1.60 | 148   | [3D641BBC20B1](<Notebook/ASUSTek Computer/X101/X101CH/3D641BBC20B1>) |
| Intel      | Core i5-3570K                    | 3.40 | 148   | [35292A5F7354](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LK/35292A5F7354>) |
| Intel      | Core i5-2500                     | 3.30 | 147   | [0FC0402E52E7](<Desktop/Gigabyte Technology/HA65/HA65M-D2H-B3/0FC0402E52E7>) |
| AMD        | Ryzen 5 4600H with Radeon Gra... |      | 146   | [A0DBD4894CC0](<Notebook/HUAWEI/HVY-WXX/HVY-WXX9/A0DBD4894CC0>) |
| Intel      | Core 2 Duo E6550                 | 2.33 | 145   | [A07474B6C7A3](<Desktop/Hewlett-Packard/Compaq/Compaq dc7800p Convertible Minitower/A07474B6C7A3>) |
| AMD        | FX -4300 Quad-Core               |      | 144   | [8C3AF54FF460](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/8C3AF54FF460>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 144   | [1FB5A6F67D05](<Desktop/ASUSTek Computer/ROG/ROG STRIX X370-F GAMING/1FB5A6F67D05>) |
| Intel      | Core i3-3120M                    | 2.50 | 144   | [7F33B1B4365C](<Notebook/Hewlett-Packard/ProBook/ProBook 4340s/7F33B1B4365C>) |
| Intel      | Core i7-8700K                    | 3.70 | 142   | [65A3A46F7F4A](<Desktop/ASUSTek Computer/PRIME/PRIME Z370-P/65A3A46F7F4A>) |
| Intel      | Core i7-4510U                    | 2.00 | 140   | [3A08EC13AED2](<Notebook/Hewlett-Packard/ProBook/ProBook 470 G2/3A08EC13AED2>) |
| Intel      | Core i5-8400                     | 2.80 | 139   | [8286140E1C85](<Desktop/ASRock/H310/H310M-HDV/8286140E1C85>) |
| Intel      | Core i5-3570                     | 3.40 | 139   | [C75E8438CE4B](<Desktop/Hewlett-Packard/520/520-1175a/C75E8438CE4B>) |
| Intel      | 11th Gen Core i7-11700           | 2.50 | 138   | [2E3DF6B59548](<Desktop/Dell/XPS/XPS 8940/2E3DF6B59548>) |
| Intel      | Core i7-2600K                    | 3.40 | 138   | [3A8ADF0D8CF6](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH P67/3A8ADF0D8CF6>) |
| Intel      | Core i5-9300H                    | 2.40 | 137   | [40BAF5C8DEF5](<Notebook/MSI/GF63/GF63 Thin 9SC/40BAF5C8DEF5>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 136   | [DC0340342D7F](<Desktop/MSI/MS-7/MS-7B84/DC0340342D7F>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 136   | [7B56B88F045B](<Desktop/ASUSTek Computer/PRIME/PRIME A520M-A/7B56B88F045B>) |
| Intel      | Pentium Dual-Core E5700          | 3.00 | 136   | [0ADDF9768967](<Desktop/MSI/MS/MS-7592/0ADDF9768967>) |
| Intel      | Pentium Dual-Core T4300          | 2.10 | 136   | [51D431EC5846](<Notebook/Acer/Aspire/Aspire 5732Z/51D431EC5846>) |
| Intel      | Core i5 M 460                    | 2.53 | 136   | [A5CB5B6164C5](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/A5CB5B6164C5>) |
| Intel      | Core i5 M 520                    | 2.40 | 136   | [60E94FBE6817](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537VGY/60E94FBE6817>) |
| Intel      | Core i7-7700K                    | 4.20 | 134   | [697AFA7C443A](<Desktop/ASUSTek Computer/PRIME/PRIME H270M-PLUS/697AFA7C443A>) |
| Intel      | Core i3-6100                     | 3.70 | 134   | [B180D6E62B60](<Desktop/ASUSTek Computer/H170M-E/H170M-E D3/B180D6E62B60>) |
| Intel      | Core i3-4130                     | 3.40 | 133   | [3B483596CCDB](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P720/3B483596CCDB>) |
| Intel      | Core i5-4200M                    | 2.50 | 133   | [1BB311C9A030](<Notebook/Toshiba/Satellite/Satellite C55-A-1P6/1BB311C9A030>) |
| AMD        | Ryzen 5 3600X 6-Core             |      | 131   | [52B170598D86](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/52B170598D86>) |
| Intel      | Celeron N4000                    | 1.10 | 130   | [29CEA6655244](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15IGM 81D1/29CEA6655244>) |
| Intel      | Core i7-3610QM                   | 2.30 | 130   | [3ABD3077E5C2](<All In One/Lenovo/A/A720/3ABD3077E5C2>) |
| AMD        | Ryzen 5 5500U with Radeon Gra... |      | 128   | [19886291EEA7](<Notebook/HONOR/BMH-WCX/BMH-WCX9/19886291EEA7>) |
| Intel      | Atom Z3735F                      | 1.33 | 128   | [14CCAB5BE212](<Notebook/Acer/TP-SW5/TP-SW5-012-16UW/14CCAB5BE212>) |
| Intel      | Core i5-3317U                    | 1.70 | 128   | [EC94C82618D5](<Tablet/Microsoft/Surface/Surface with Windows 8 Pro/EC94C82618D5>) |
| Intel      | Core i5-6400                     | 2.70 | 128   | [3C92CB30C4CC](<Desktop/Dell/Inspiron/Inspiron 3650/3C92CB30C4CC>) |
| Intel      | Pentium N3540                    | 2.16 | 127   | [837B847F3C24](<Notebook/Lenovo/IdeaPad/IdeaPad S20-30/837B847F3C24>) |
| Intel      | Core i3 M 350                    | 2.27 | 126   | [4BB927D1F853](<Notebook/Acer/Aspire/Aspire 7745/4BB927D1F853>) |
| AMD        | E-350                            |      | 125   | [B6EE6BA14152](<Notebook/ASUSTek Computer/K73/K73BY/B6EE6BA14152>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 125   | [0A9310A22D87](<Desktop/ASRock/A320M-HDV/A320M-HDV R4.0/0A9310A22D87>) |
| Intel      | Core i5-7300HQ                   | 2.50 | 125   | [0458E57753A0](<Notebook/Acer/Aspire/Aspire VX5-591G/0458E57753A0>) |
| Intel      | Core 2 Duo P8600                 | 2.40 | 125   | [F66931592D8E](<Notebook/Dell/Studio/Studio 1737/F66931592D8E>) |
| Intel      | Core i5 M 480                    | 2.67 | 125   | [E7F94FDB9327](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/E7F94FDB9327>) |
| Intel      | Celeron 2955U                    | 1.40 | 125   | [A9A4953B82AD](<Notebook/Dell/Inspiron/Inspiron 3537/A9A4953B82AD>) |
| Intel      | Core i7-4500U                    | 1.80 | 125   | [CBF5B428D99D](<Notebook/ASUSTek Computer/S301/S301LP/CBF5B428D99D>) |
| Intel      | Core i7-4600U                    | 2.10 | 125   | [65CF657D748C](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AMS35500/65CF657D748C>) |
| Intel      | Core i3-6100U                    | 2.30 | 125   | [E284EA08A387](<Notebook/Acer/Aspire/Aspire ES1-572/E284EA08A387>) |
| Intel      | Core i7-7700                     | 3.60 | 124   | [572D30F97D55](<Desktop/ASUSTek Computer/STRIX/STRIX Z270E GAMING/572D30F97D55>) |
| AMD        | Phenom II X4 955                 |      | 123   | [7D1567B2D032](<Desktop/Gigabyte Technology/GA-880/GA-880GM-UD2H/7D1567B2D032>) |
| Intel      | Pentium Dual-Core T4400          | 2.20 | 123   | [C29DCE2B81D9](<Notebook/Acer/Extensa/Extensa 5635ZG/C29DCE2B81D9>) |
| AMD        | Phenom II X4 965                 |      | 122   | [85548CCDD242](<Desktop/Foxconn/A74ML-A74ML-K/A74ML-A74ML-K 3.0 1.0/85548CCDD242>) |
| Intel      | Pentium Dual-Core T4200          | 2.00 | 122   | [1045062C78EF](<Notebook/Fujitsu Siemens/AMILO/AMILO Li3910/1045062C78EF>) |
| Intel      | Core 2 Duo P8400                 | 2.26 | 121   | [822A42E7F792](<Notebook/Dell/Latitude/Latitude E6400/822A42E7F792>) |
| Intel      | Core 2 Duo E4500                 | 2.20 | 118   | [FCDB5EC76D38](<Desktop/ASUSTek Computer/P5/P5GC-MX-MEDION-SI/FCDB5EC76D38>) |
| Intel      | Pentium N3700                    | 1.60 | 118   | [E8521B24F159](<Notebook/ASUSTek Computer/E205/E205SA/E8521B24F159>) |
| AMD        | Ryzen 5 2600X Six-Core           |      | 117   | [84ACADF7AB31](<Desktop/Gigabyte Technology/B450M/B450M DS3H/84ACADF7AB31>) |
| Intel      | Pentium M processor              | 1.20 | 117   | [6A8FD8C3E5B7](<Notebook/Dell/Inspiron/Inspiron 6000/6A8FD8C3E5B7>) |
| Intel      | Celeron N2830                    | 2.16 | 117   | [A9FDDB34F3B7](<Notebook/Dell/Inspiron/Inspiron 3531/A9FDDB34F3B7>) |
| AMD        | Ryzen 7 5800H with Radeon Gra... |      | 116   | [701977B77E24](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop M3500QA_M3500QA/701977B77E24>) |
| Intel      | Pentium 4                        | 3.00 | 116   | [2C4B19FCA7DB](<Desktop/ASUSTek Computer/P5/P5VDC-X/2C4B19FCA7DB>) |
| Intel      | Core i3-7100U                    | 2.40 | 116   | [9810F5D193B3](<Notebook/Dell/Inspiron/Inspiron 5566/9810F5D193B3>) |
| Intel      | Pentium N3710                    | 1.60 | 115   | [9B669BA6736E](<Notebook/Lenovo/IdeaPad/IdeaPad 110-15IBR 80T7/9B669BA6736E>) |
| Intel      | Pentium P6200                    | 2.13 | 113   | [3D7EFF65AF74](<Notebook/LG Electronics/C400/C400-G.BC22P1/3D7EFF65AF74>) |
| Intel      | Core i3-7100                     | 3.90 | 112   | [D9DFB620C951](<Desktop/Gigabyte Technology/H110/H110M-S2V/D9DFB620C951>) |
| Intel      | Core i3 M 330                    | 2.13 | 112   | [4B8A786D7FBE](<Notebook/Hewlett-Packard/ProBook/ProBook 4720s/4B8A786D7FBE>) |
| Intel      | Core i5-2540M                    | 2.60 | 112   | [D74FF9CB9D32](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4180MBM/D74FF9CB9D32>) |
| Intel      | Core i3-3240                     | 3.40 | 112   | [38EBDC8121CF](<Desktop/Gigabyte Technology/H61M-DS2/H61M-DS2 DVI/38EBDC8121CF>) |
| AMD        | Ryzen 7 5700U with Radeon Gra... |      | 111   | [BFC66FC359C3](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 15ALC05 82HV/BFC66FC359C3>) |
| Intel      | Pentium G630                     | 2.70 | 111   | [79F8BADF0504](<Desktop/ECS/H61/H61H2-M13/79F8BADF0504>) |
| AMD        | Ryzen 7 3800X 8-Core             |      | 110   | [F4181369F614](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VII HERO/F4181369F614>) |
| Intel      | Core 2 Duo E8500                 | 3.16 | 110   | [06DB9F3AB20E](<Desktop/Gigabyte Technology/G41/G41M-Combo/06DB9F3AB20E>) |
| Intel      | Core i7-3520M                    | 2.90 | 110   | [31DF16F8AF4F](<Notebook/Apple/MacBookPro9/MacBookPro9,2/31DF16F8AF4F>) |
| AMD        | E-300 APU with Radeon HD Grap... |      | 109   | [8C9082C00908](<Notebook/Packard Bell/EasyNote/EasyNote TK11BZ/8C9082C00908>) |
| Intel      | Pentium 4                        | 3.20 | 109   | [4033B8E02395](<Desktop/Medion/MS/MS-7091/4033B8E02395>) |
| Intel      | Core 2 Duo P8700                 | 2.53 | 109   | [32B729EF8312](<Notebook/Dell/Latitude/Latitude E6500/32B729EF8312>) |
| Intel      | Atom N570                        | 1.66 | 109   | [B009AF88D443](<Notebook/ASUSTek Computer/1011/1011PX/B009AF88D443>) |
| Intel      | Core i5 M 560                    | 2.67 | 109   | [B6C99D7F3716](<Notebook/Toshiba/TECRA/TECRA M11/B6C99D7F3716>) |
| Intel      | Core i5 M 430                    | 2.27 | 108   | [D2C007C69B47](<Notebook/Acer/Aspire/Aspire 5742/D2C007C69B47>) |
| Intel      | Core i3-4160                     | 3.60 | 108   | [03B5479FC7D7](<Desktop/ASRock/H81M-VG4/H81M-VG4 R2.0/03B5479FC7D7>) |
| Intel      | Pentium Dual-Core E5400          | 2.70 | 107   | [29F44FE2FDCE](<Desktop/Acer/Aspire/Aspire X5810/29F44FE2FDCE>) |
| Intel      | Core i5 750                      | 2.67 | 107   | [EBF1969A1344](<Desktop/ASRock/H55/H55M-LE/EBF1969A1344>) |
| Intel      | Pentium G4400                    | 3.30 | 107   | [53020D74CC73](<Desktop/ASUSTek Computer/Z170/Z170-P/53020D74CC73>) |
| Intel      | Core i3 550                      | 3.20 | 105   | [3E653BBA301A](<Desktop/Intel/DH55TC/DH55TC AAE70932-206/3E653BBA301A>) |
| Intel      | Pentium P6100                    | 2.00 | 105   | [58E4194C125C](<Notebook/Samsung Electronics/RV411/RV411-RV511-E3511-S3511-RV711-E3411/58E4194C125C>) |
| Intel      | Core i3-2370M                    | 2.40 | 105   | [32A30A3A3068](<Notebook/Hewlett-Packard/ProBook/ProBook 6470b/32A30A3A3068>) |
| Intel      | Core i3-4030U                    | 1.90 | 105   | [4CF0B95A2A5D](<Notebook/Lenovo/B50-80/B50-80 80LT/4CF0B95A2A5D>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 104   | [AB25447D4406](<Desktop/MSI/MS-7/MS-7B93/AB25447D4406>) |
| Intel      | Core i7-10710U                   | 1.10 | 104   | [8638844D4716](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/8638844D4716>) |
| Intel      | Core i7-4770K                    | 3.50 | 104   | [AEECDAA08AD3](<Desktop/ASUSTek Computer/All/All Series/AEECDAA08AD3>) |
| Intel      | Core i5-10300H                   | 2.50 | 103   | [EC7BE1BF6FCC](<Notebook/Acer/Nitro/Nitro AN515-55/EC7BE1BF6FCC>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 103   | [F612463D4F4F](<Desktop/ASUSTek Computer/P5/P5Q/F612463D4F4F>) |
| Intel      | Core i7-3632QM                   | 2.20 | 103   | [791A65EEF799](<Notebook/Lenovo/ThinkPad/ThinkPad Edge E530c 33667MG/791A65EEF799>) |
| Intel      | Core i5-4440                     | 3.10 | 103   | [BB1FF32279B7](<Desktop/ASUSTek Computer/All/All Series/BB1FF32279B7>) |
| AMD        | FX -6100 Six-Core                |      | 102   | [7FDE1C2D3DEE](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3 PLUS/7FDE1C2D3DEE>) |
| AMD        | A8-7410 APU with AMD Radeon R... |      | 102   | [505A3811BD7C](<Notebook/Hewlett-Packard/Others/Others/505A3811BD7C>) |
| Intel      | Core i3-8100                     | 3.60 | 102   | [BFAC8BBEE43F](<Desktop/ASUSTek Computer/PRIME/PRIME B365M-A/BFAC8BBEE43F>) |
| Intel      | Atom D525                        | 1.80 | 102   | [BAB93579A95F](<Desktop/Hewlett-Packard/CQ1507/CQ1507LA/BAB93579A95F>) |
| Intel      | Core i5-3330                     | 3.00 | 102   | [AD473F747E89](<Desktop/Acer/Aspire/Aspire XC600/AD473F747E89>) |
| Intel      | Core 2 Duo T7500                 | 2.20 | 100   | [301537D2AE06](<Notebook/ASUSTek Computer/F3/F3Sr/301537D2AE06>) |
| Intel      | Pentium Dual E2180               | 2.00 | 100   | [A2439EE60805](<Desktop/ASUSTek Computer/P5/P5GC-MX-1333/A2439EE60805>) |
| Intel      | Core 2 Duo E7400                 | 2.80 | 100   | [6951E18673DA](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Small Form Factor/6951E18673DA>) |
| Intel      | Core i3-8130U                    | 2.20 | 99    | [13B56A2CF8AB](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 14-ce0xxx/13B56A2CF8AB>) |
| Intel      | Core 2 Quad Q8300                | 2.50 | 99    | [8CA44222473E](<Desktop/Acer/Aspire/Aspire M5800-M3800/8CA44222473E>) |
| Intel      | Pentium 4                        | 3.00 | 98    | [D4B72E97AC23](<Desktop/Hewlett-Packard/Compaq/Compaq dx2200 MT/D4B72E97AC23>) |
| AMD        | A10-4600M APU with Radeon HD ... |      | 97    | [3A4921411C5D](<Notebook/Toshiba/Satellite/Satellite S855D/3A4921411C5D>) |
| Intel      | Core 2 Duo T6600                 | 2.20 | 97    | [45EFE031F17C](<Notebook/Samsung Electronics/R530/R530-R730/45EFE031F17C>) |
| AMD        | FX -4100 Quad-Core               |      | 96    | [66530EB36F4C](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-USB3/66530EB36F4C>) |
| AMD        | Ryzen 7 1700X Eight-Core         |      | 96    | [F6C60CB350D5](<Desktop/ASRock/B450M/B450M Pro4/F6C60CB350D5>) |
| Intel      | Core i3-1005G1                   | 1.20 | 96    | [77D084D62A49](<Notebook/Acer/Aspire/Aspire A315-57G/77D084D62A49>) |
| Intel      | Pentium G3220                    | 3.00 | 96    | [0F282FDFB77B](<Desktop/Gigabyte Technology/H81/H81M-S2V/0F282FDFB77B>) |
| Intel      | Core i5-6600K                    | 3.50 | 96    | [4B5DEEE5B583](<Desktop/ASUSTek Computer/Maximus/Maximus VIII IMPACT/4B5DEEE5B583>) |
| AMD        | Athlon II X4 640                 |      | 95    | [E83E52132D02](<Desktop/ASRock/N68-VS3/N68-VS3 UCC/E83E52132D02>) |
| AMD        | Ryzen 3 3200U with Radeon Veg... |      | 95    | [D26F74289961](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db1xxx/D26F74289961>) |
| AMD        | Ryzen 5 3550H with Radeon Veg... |      | 95    | [5EA1D9EED139](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DD_FX505DD/5EA1D9EED139>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 95    | [351E7D96217B](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING/351E7D96217B>) |
| Intel      | Pentium Silver N5000             | 1.10 | 95    | [FD1193B1C6DF](<Notebook/Notebook/W517/W517GU1/FD1193B1C6DF>) |
| Intel      | Core i5-8350U                    | 1.70 | 94    | [1B4790D9BC74](<Notebook/Lenovo/ThinkPad/ThinkPad X280 20KES4H34G/1B4790D9BC74>) |
| Intel      | Pentium G620                     | 2.60 | 94    | [07187B792FB5](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/07187B792FB5>) |
| AMD        | A6-6310 APU with AMD Radeon R... |      | 93    | [49481B54F6B7](<Notebook/Toshiba/Satellite/Satellite C75D-B/49481B54F6B7>) |
| Intel      | Pentium B950                     | 2.10 | 93    | [20010974C27A](<Notebook/ASUSTek Computer/K54/K54L/20010974C27A>) |
| Intel      | Celeron 1000M                    | 1.80 | 93    | [A6BB68A8662F](<Notebook/Toshiba/Satellite/Satellite C850-1GF/A6BB68A8662F>) |
| Intel      | Core i7-5600U                    | 2.60 | 93    | [4116FAC45805](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 3rd 20BTS0MX00/4116FAC45805>) |
| Intel      | Core 2 Duo T7250                 | 2.00 | 92    | [EEB44C5107DC](<Notebook/Dell/Latitude/Latitude D830/EEB44C5107DC>) |
| Intel      | Core i5-2320                     | 3.00 | 92    | [71D080A4C791](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX2/71D080A4C791>) |
| AMD        | C-60 APU with Radeon HD Graphics |      | 91    | [4E51373C1D7C](<Notebook/Acer/AO/AO725/4E51373C1D7C>) |
| AMD        | Ryzen 9 3950X 16-Core            |      | 91    | [60A91FA473A7](<Desktop/MSI/MS-7/MS-7B79/60A91FA473A7>) |
| Intel      | Core i7-4710HQ                   | 2.50 | 91    | [B423FDCA4AE6](<Notebook/MSI/GS60/GS60 2PE/B423FDCA4AE6>) |
| Intel      | Core 2 Duo T8300                 | 2.40 | 90    | [7CE99EB9C943](<Notebook/Sony/VGN-FZ31/VGN-FZ31Z/7CE99EB9C943>) |
| Intel      | Core i5 760                      | 2.80 | 90    | [BE53CE9C6D7D](<Desktop/Gigabyte Technology/H57/H57M-USB3/BE53CE9C6D7D>) |
| Intel      | Core i5-2300                     | 2.80 | 90    | [C0B609830055](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX/C0B609830055>) |
| Intel      | Core i7-2620M                    | 2.70 | 89    | [2FDC3FA43513](<Notebook/Dell/Latitude/Latitude E6420/2FDC3FA43513>) |
| AMD        | E1-1200 APU with Radeon HD Gr... |      | 88    | [80891C42AFB5](<Notebook/Lenovo/IdeaPad/IdeaPad S206 20154/80891C42AFB5>) |
| Intel      | Core 2 T7200                     | 2.00 | 88    | [341816537142](<Notebook/Hewlett-Packard/Compaq/Compaq nw8440/341816537142>) |
| Intel      | Core i7-8850H                    | 2.60 | 88    | [5D901380800A](<Notebook/Hewlett-Packard/ZBook/ZBook 15 G5/5D901380800A>) |
| Intel      | Celeron N4100                    | 1.10 | 87    | [AF6799DB46E2](<Convertible/Medion/E/E2292/AF6799DB46E2>) |
| Intel      | Core i5-4670K                    | 3.40 | 87    | [4380533F538F](<Desktop/MSI/MS/MS-7816/4380533F538F>) |
| Intel      | Core 2 Duo E6750                 | 2.66 | 86    | [9124D33B7BE2](<Desktop/ASUSTek Computer/P5/P5K/9124D33B7BE2>) |
| Intel      | Pentium Dual E2200               | 2.20 | 86    | [B38A5C83A51B](<Desktop/Gigabyte Technology/G31/G31M-S2L/B38A5C83A51B>) |
| Intel      | Core i5-7500                     | 3.40 | 86    | [6D0326544A31](<Desktop/Dell/OptiPlex/OptiPlex 5050/6D0326544A31>) |
| Intel      | Celeron E3400                    | 2.60 | 85    | [1E26BB6450DC](<Desktop/ASRock/G41/G41M-S3/1E26BB6450DC>) |
| Intel      | Core i7 Q 720                    | 1.60 | 85    | [F3308DF5663B](<Notebook/Sony/VPCF119/VPCF119FX/F3308DF5663B>) |
| Intel      | Core i5-3450                     | 3.10 | 85    | [4BDE514875F8](<Desktop/ASRock/B75/B75M-DGS/4BDE514875F8>) |
| Intel      | Atom x5-Z8300                    | 1.44 | 85    | [B717D1200791](<Notebook/Positivo/S14/S14CT01/B717D1200791>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 729   | [CF65132134C6](<Notebook/Toshiba/QOSMIO/QOSMIO X770/CF65132134C6>) |
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 3266 | 655   | [70FDDABF265C](<Convertible/Lenovo/IdeaPad/IdeaPad C340-14IML 81TK/70FDDABF265C>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 619   | [65947F3F374E](<Desktop/Intel/DG41RQ/DG41RQ AAE54511-205/65947F3F374E>) |
| SK Hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2667 | 619   | [40F41D913DE9](<Notebook/ASUSTek Computer/X510/X510UAR/40F41D913DE9>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 606   | [1F90623FAB84](<Notebook/Acer/AO/AO722/1F90623FAB84>) |
|            | Module DIMM SDRAM            | 2048 MB  |      |      | 601   | [31C05D671C1F](<Desktop/ASRock/H55/H55M-LE/31C05D671C1F>) |
|            | Module DIMM                  | 2048 MB  |      | 800  | 553   | [673E549E404E](<Desktop/Gigabyte Technology/G31/G31M-S2L/673E549E404E>) |
|            | Module DIMM                  | 4096 MB  |      | 1333 | 549   | [6C9CF1178AC3](<Desktop/ASUSTek Computer/M4A79XTD/M4A79XTD EVO/6C9CF1178AC3>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 545   | [6A02236A28E8](<Notebook/Lenovo/B590/B590 20208/6A02236A28E8>) |
|            | Module DIMM                  | 2048 MB  |      | 1333 | 505   | [6673A93B3D66](<Desktop/ASUSTek Computer/M4/M4A88T-M/6673A93B3D66>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 503   | [AA9902ADCF71](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK S792/AA9902ADCF71>) |
|            | Module DIMM SDRAM            | 1024 MB  |      |      | 486   | [6A6E19F0EB01](<Desktop/ASRock/G41/G41C-VS/6A6E19F0EB01>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 478   | [F145022DA5F8](<Desktop/Dell/OptiPlex/OptiPlex 3050/F145022DA5F8>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 456   | [6A02236A28E8](<Notebook/Lenovo/B590/B590 20208/6A02236A28E8>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8192 MB  | DDR4 | 3200 | 434   | [701977B77E24](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop M3500QA_M3500QA/701977B77E24>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2 GB     | DDR3 | 4199 | 383   | [054E485ECA98](<Notebook/ASUSTek Computer/X450/X450EA/054E485ECA98>) |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 382   | [32A30A3A3068](<Notebook/Hewlett-Packard/ProBook/ProBook 6470b/32A30A3A3068>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 370   | [A8788E2EED17](<Notebook/Dell/Latitude/Latitude E6430s/A8788E2EED17>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1600 | 369   | [B9B75BA01934](<Notebook/Toshiba/Satellite/Satellite C660/B9B75BA01934>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 800  | 368   | [498C6114C475](<Desktop/ASUSTek Computer/P5/P5QPL-AM/498C6114C475>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 367   | [3139F7166296](<Notebook/Dell/Inspiron/Inspiron 15-5578/3139F7166296>) |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 352   | [1D425D5F0660](<Notebook/ASUSTek Computer/N56/N56VJ/1D425D5F0660>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 351   | [720297696DAA](<Notebook/ASUSTek Computer/1005/1005P/720297696DAA>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 346   | [C6267579482D](<Notebook/Dell/G7/G7 7590/C6267579482D>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 311   | [A509A254E32C](<Notebook/Hewlett-Packard/OMEN/OMEN Laptop 15-en0xxx/A509A254E32C>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 309   | [BE7BBE7F6788](<Notebook/Toshiba/Satellite/Satellite L50-C/BE7BBE7F6788>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 300   | [3249008C6C8B](<Convertible/Lenovo/ThinkPad/ThinkPad L390 Yoga 20NT000JUS/3249008C6C8B>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 299   | [2626CCD64C5C](<Notebook/Dell/Inspiron/Inspiron 3493/2626CCD64C5C>) |
|            | Module SODIMM                | 2048 MB  | DDR2 |      | 294   | [4AB0CBD57303](<Notebook/Acer/Aspire/Aspire 3100/4AB0CBD57303>) |
|            | Module DIMM                  | 1024 MB  |      | 800  | 291   | [673E549E404E](<Desktop/Gigabyte Technology/G31/G31M-S2L/673E549E404E>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 667  | 290   | [FB4C5BC2D3B9](<Desktop/Hewlett-Packard/ED842AAR-ABA/ED842AAR-ABA M7250N/FB4C5BC2D3B9>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1333 | 290   | [BB1FF32279B7](<Desktop/ASUSTek Computer/All/All Series/BB1FF32279B7>) |
|            | 123456789012345678 SODIMM... | 1024 MB  |      | 2400 | 284   | [96A0EC35E00A](<Notebook/Chuwi/HeroBook/HeroBook Air/96A0EC35E00A>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8192 MB  | DDR3 | 2667 | 279   | [47231B7CAF33](<Notebook/ASUSTek Computer/K55/K55VD/47231B7CAF33>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 667  | 272   | [13F25640889A](<Desktop/ASUSTek Computer/M2N-MX/M2N-MX SE/13F25640889A>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3600 | 271   | [7B56B88F045B](<Desktop/ASUSTek Computer/PRIME/PRIME A520M-A/7B56B88F045B>) |
| SK Hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 271   | [7C50274A6FA9](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS14900/7C50274A6FA9>) |
| SK Hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2667 | 269   | [1B666FCC2D3A](<Notebook/Acer/Aspire/Aspire A515-51/1B666FCC2D3A>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 2400 | 255   | [10C8FEF878C9](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/10C8FEF878C9>) |
|            | Module SODIMM                | 1024 MB  | DDR2 |      | 243   | [15AC44A84784](<Notebook/Acer/Aspire/Aspire 5610/15AC44A84784>) |
| SK Hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 243   | [65D6062D3513](<Notebook/Dell/Inspiron/Inspiron 5593/65D6062D3513>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4096 MB  | DDR3 | 1334 | 234   | [DB6EF940077E](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/DB6EF940077E>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8192 MB  | DDR4 | 2667 | 233   | [4F19AA0B254D](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/4F19AA0B254D>) |
| SK Hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 231   | [974FF46B3D36](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2000KRT/974FF46B3D36>) |
|            | Module SODIMM                | 4096 MB  | DDR3 |      | 230   | [F65894F76BAC](<Notebook/Sony/SVS1311/SVS13118GBB/F65894F76BAC>) |
|            | Module SODIMM                | 1024 MB  | DDR2 | 667  | 227   | [95FAF42AC4C1](<Notebook/Lenovo/3000/3000 N500 423332G/95FAF42AC4C1>) |
| Samsung    | M471B5673FH0-CH9 SODIMM      | 2048 MB  | DDR3 | 1334 | 224   | [B1CE29E0C8A1](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4291Q50/B1CE29E0C8A1>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 | 1867 | 215   | [BD0F36B63B74](<Desktop/ONDA/A68/A68V+/BD0F36B63B74>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 213   | [8742730C6F9C](<Notebook/Acer/Aspire/Aspire ES1-331/8742730C6F9C>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3000 | 211   | [A23BAB4C3677](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-A/A23BAB4C3677>) |
|            | Module DIMM                  | 2048 MB  |      | 667  | 211   | [B664B194F355](<Desktop/Gigabyte Technology/M61/M61PME-S2/B664B194F355>) |
| SK Hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 206   | [C58673A1A81B](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20ARS08Q00/C58673A1A81B>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 204   | [7BC552597A23](<Notebook/Toshiba/Satellite/Satellite C650/7BC552597A23>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 203   | [1020FE6EFFAE](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc0xxx/1020FE6EFFAE>) |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     | DDR3 | 1334 | 202   | [2FDC3FA43513](<Notebook/Dell/Latitude/Latitude E6420/2FDC3FA43513>) |
|            | Module DIMM                  | 4096 MB  |      | 1600 | 201   | [8134AA1D6242](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/8134AA1D6242>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 200   | [AD6CB8B38707](<Notebook/Fujitsu/FMVA/FMVA05007/AD6CB8B38707>) |
|            | Module DIMM                  | 1024 MB  |      | 667  | 197   | [796426BF5E54](<Desktop/Gigabyte Technology/G31/G31M-ES2C/796426BF5E54>) |
| Micron     | 8ATF1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 193   | [FF8F84C8407D](<Notebook/Dell/Inspiron/Inspiron 3793/FF8F84C8407D>) |
| SK Hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2667 | 191   | [5D4F8C0049B7](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 14-dh1xxx/5D4F8C0049B7>) |
|            | Module DIMM                  | 2048 MB  | DDR3 | 1333 | 186   | [DB4E985D3B0D](<Desktop/Biostar/AM1/AM1ML/DB4E985D3B0D>) |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8 GB     | DDR4 | 3200 | 185   | [01696D092E1F](<Convertible/Lenovo/Yoga/Yoga 7 14ITL5 82BH/01696D092E1F>) |
|            | Module DIMM                  | 2048 MB  |      | 400  | 181   | [238E55628E17](<Desktop/ASRock/N68C-S/N68C-S UCC/238E55628E17>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 178   | [C03845C38550](<Notebook/Hewlett-Packard/Pavilion/Pavilion g4/C03845C38550>) |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 178   | [3F35783A65E6](<Notebook/Dell/XPS/XPS 15 9500/3F35783A65E6>) |
| Micron     | 8ATF1G64HZ-3G2J1 SODIMM      | 8192 MB  | DDR4 | 3200 | 176   | [5EA1D9EED139](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DD_FX505DD/5EA1D9EED139>) |
|            | Module DIMM SDRAM            | 512 MB   |      |      | 170   | [B220762D01F8](<Desktop/Shuttle/System/System/B220762D01F8>) |
| Micron     | 4ATF51264HZ-2G3B1 SODIMM     | 4096 MB  | DDR4 | 2400 | 168   | [E10C1473180B](<Notebook/Lenovo/IdeaPad/IdeaPad 330S-15ARR 81FB/E10C1473180B>) |
|            | Module DIMM                  | 1024 MB  |      |      | 164   | [23DC82E5FA2B](<Desktop/Packard Bell/ISTART/ISTART D5535/23DC82E5FA2B>) |
| SK Hynix   | H9CCNNNCLGALAR-NVD Row Of... | 8 GB     |      | 2133 | 163   | [FC481B1074DF](<Notebook/Timi/RedmiBook/RedmiBook Air 13/FC481B1074DF>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 1867 | 162   | [6DA1DE70C69F](<Desktop/ASUSTek Computer/All/All Series/6DA1DE70C69F>) |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16384 MB | DDR4 | 2667 | 158   | [18E95B12F364](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L60033MX/18E95B12F364>) |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 3200 | 157   | [8382478D22DE](<Desktop/ASUSTek Computer/PRIME/PRIME Z370-P/8382478D22DE>) |
| SK Hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 156   | [D7BA324E42E4](<Notebook/Hewlett-Packard/EliteBook/EliteBook Revolve 810 G1/D7BA324E42E4>) |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8192 MB  | DDR4 | 3200 | 156   | [DFC9BE7636A6](<Notebook/Lenovo/ThinkPad/ThinkPad T14s Gen 1 20T1S8E400/DFC9BE7636A6>) |
| Nanya      | NT4GC64B8HB0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 149   | [2B4CE78E3ACA](<Notebook/Dell/Inspiron/Inspiron N5110/2B4CE78E3ACA>) |
| Samsung    | M471B5273CH0-CK0 SODIMM      | 4096 MB  | DDR3 | 1600 | 149   | [576838609E8D](<Notebook/Toshiba/Satellite/Satellite C870-1F3/576838609E8D>) |
| SK Hynix   | HMT325S6BFR8C-H9 SODIMM      | 2 GB     | DDR3 | 1600 | 148   | [8C9082C00908](<Notebook/Packard Bell/EasyNote/EasyNote TK11BZ/8C9082C00908>) |
| SK Hynix   | HMA82GS6JJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 146   | [4C10BB3B23E4](<Notebook/Dell/Latitude/Latitude 5300/4C10BB3B23E4>) |
| SK Hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 145   | [9AFC2F21A57A](<Notebook/ASUSTek Computer/U24/U24E/9AFC2F21A57A>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 144   | [7B4E41608F26](<Notebook/Toshiba/Satellite/Satellite A660/7B4E41608F26>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 2933 | 143   | [52B170598D86](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/52B170598D86>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1600 | 143   | [00DE9268F454](<Desktop/ASUSTek Computer/CM/CM1435/00DE9268F454>) |
| SK Hynix   | HYMP125S64CP8-S6 SODIMM DDR  | 2 GB     |      | 975  | 143   | [3BE885BACF91](<Notebook/Dell/Inspiron/Inspiron 1545/3BE885BACF91>) |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4 GB     | DDR4 | 3200 | 142   | [77D084D62A49](<Notebook/Acer/Aspire/Aspire A315-57G/77D084D62A49>) |
| Samsung    | M471B5773DH0-CK0 SODIMM      | 2 GB     | DDR3 | 1600 | 141   | [1D425D5F0660](<Notebook/ASUSTek Computer/N56/N56VJ/1D425D5F0660>) |
| 48spaces   | 0123456789012345678901234... | 2 GB     | DDR2 | 667  | 140   | [8309E1560AC2](<Notebook/Samsung Electronics/NC210/NC210-NC110/8309E1560AC2>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 140   | [65F56473253E](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 R2/65F56473253E>) |
|            | Module DIMM DDR              | 2048 MB  |      | 1333 | 139   | [E2D4E3301241](<Desktop/ASUSTek Computer/P7/P7P55D/E2D4E3301241>) |
| Samsung    | M471A2K43DB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 138   | [6185101B495A](<Notebook/Lenovo/ThinkPad/ThinkPad L390 20NSS1YV0B/6185101B495A>) |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 138   | [4BB07732F905](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-fq0xxx/4BB07732F905>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8192 MB  | DDR3 | 1600 | 136   | [48ED763F1AF8](<Notebook/Hewlett-Packard/255/255 G4/48ED763F1AF8>) |
| Kingston   | 99U5584-005.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 136   | [0F282FDFB77B](<Desktop/Gigabyte Technology/H81/H81M-S2V/0F282FDFB77B>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3533 | 136   | [C9A3879713A4](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-E GAMING/C9A3879713A4>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3600 | 135   | [AE8199E3BF75](<Desktop/ASUSTek Computer/ProArt/ProArt X570-CREATOR WIFI/AE8199E3BF75>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 134   | [CCD48173AEB6](<Notebook/Lenovo/ThinkPad/ThinkPad Edge E531 68852BU/CCD48173AEB6>) |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8192 MB  | DDR4 | 3200 | 133   | [65A3A46F7F4A](<Desktop/ASUSTek Computer/PRIME/PRIME Z370-P/65A3A46F7F4A>) |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 133   | [AF6E3B0B1B0D](<Notebook/Hewlett-Packard/245/245 G3/AF6E3B0B1B0D>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 800  | 133   | [D19176E847E3](<All In One/Apple/iMac8/iMac8,1/D19176E847E3>) |
| SK Hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 132   | [7EC4DBCFDEB0](<Notebook/Lenovo/IdeaPad/IdeaPad S540-14IML Touch 81V0/7EC4DBCFDEB0>) |
| Micron     | 16JSF51264HZ-1G4D1 SODIMM    | 4 GB     | DDR3 | 1334 | 131   | [11ECFFA666E6](<Notebook/Medion/E/E6228/11ECFFA666E6>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 131   | [301537D2AE06](<Notebook/ASUSTek Computer/F3/F3Sr/301537D2AE06>) |
| SK Hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 131   | [46E5CB03259C](<Notebook/Toshiba/PORTEGE/PORTEGE R835/46E5CB03259C>) |
| Elpida     | EBJ40UG8BBU0-GN-F SODIMM     | 4 GB     | DDR3 | 1600 | 130   | [E71D539D94F9](<Notebook/ASUSTek Computer/K53/K53Z/E71D539D94F9>) |
| Kingston   | KHX2400C15/8G DIMM           | 8192 MB  | DDR4 | 2933 | 130   | [B53CA139A0EA](<Desktop/ASRock/B360/B360 Gaming K4/B53CA139A0EA>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 130   | [B6072358711D](<Notebook/Lenovo/ThinkPad/ThinkPad T540p 20BE005YMH/B6072358711D>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 129   | [DB16F86988BE](<Desktop/Gigabyte Technology/Z68/Z68XP-UD3/DB16F86988BE>) |
| SK Hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2667 | 129   | [4079965A25F0](<Notebook/Acer/Predator/Predator G3-572/4079965A25F0>) |
| SK Hynix   | HMT351U6CFR8C-PB DIMM        | 4096 MB  | DDR3 | 1800 | 128   | [B70932ED3EE9](<Desktop/Biostar/H61/H61MLV2/B70932ED3EE9>) |
|            | Module DIMM                  | 2048 MB  |      | 1066 | 128   | [C135CB438506](<Desktop/Gigabyte Technology/GA-MA785/GA-MA785GMT-UD2H/C135CB438506>) |
| Nanya      | NT4GC64B8HG0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 127   | [C2F4DACCE417](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4180F64/C2F4DACCE417>) |
|            | Module DIMM                  | 4096 MB  |      | 400  | 127   | [A3FB388EA8E7](<Desktop/ASRock/N68-VS3/N68-VS3 UCC/A3FB388EA8E7>) |
| Samsung    | M471B5674QH0-YK0 SODIMM      | 2 GB     | DDR3 | 1600 | 127   | [837B847F3C24](<Notebook/Lenovo/IdeaPad/IdeaPad S20-30/837B847F3C24>) |
| SK Hynix   | HMT425S6AFR6A-PB SODIMM      | 2048 MB  | DDR3 | 1600 | 126   | [B03DC037536E](<Notebook/ASUSTek Computer/X550/X550CC/B03DC037536E>) |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1333 | 126   | [14CCAB5BE212](<Notebook/Acer/TP-SW5/TP-SW5-012-16UW/14CCAB5BE212>) |
| Elpida     | EBJ21UE8BFU0-DJ-F SODIMM     | 2048 MB  | DDR3 | 1334 | 124   | [31847923E07F](<Notebook/Hewlett-Packard/Pavilion/Pavilion g6/31847923E07F>) |
| SK Hynix   | HMT41GS6AFR8A-PB SODIMM      | 8192 MB  | DDR3 | 1600 | 123   | [0BD8AF587DDC](<Notebook/Dell/Latitude/Latitude E6440/0BD8AF587DDC>) |
| Micron     | 8JSF25664HZ-1G4D1 SODIMM     | 2048 MB  | DDR3 | 1334 | 123   | [725B6221FBB1](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8440p/725B6221FBB1>) |
|            | Module SODIMM DDR            | 1024 MB  |      |      | 123   | [5960DFC154F9](<Notebook/ASUSTek Computer/X51/X51RL/5960DFC154F9>) |
|            | Module DIMM                  | 1024 MB  | DDR2 |      | 123   | [1168851D9A87](<Notebook/Acer/Ferrari/Ferrari 5000/1168851D9A87>) |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4096 MB  | DDR3 | 1600 | 122   | [B2F39EFFD051](<Notebook/Lenovo/B590/B590 20208/B2F39EFFD051>) |
| SK Hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 122   | [34EA23E7BE6D](<Notebook/Dell/Inspiron/Inspiron 5409/34EA23E7BE6D>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8192 MB  | DDR3 | 1600 | 121   | [01DF84254708](<Notebook/Samsung Electronics/350V5/350V5C-350V5X-350V4C-350V4X-351V5C-351V5X-351V4C-351V4X-3540VC-3540VX-3440VC-3440VX/01DF84254708>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 121   | [00BA6B809DED](<Notebook/System76/Lemur/Lemur Pro/00BA6B809DED>) |
|            | Module SODIMM DRAM           | 1024 MB  |      |      | 120   | [085B64D84257](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv8000/085B64D84257>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2048 MB  | DDR3 | 1600 | 120   | [95B331BAD3B6](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro SFF PC/95B331BAD3B6>) |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3400 | 119   | [85A837331B4E](<Desktop/ASUSTek Computer/PRIME/PRIME X399-A/85A837331B4E>) |
| SK Hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 119   | [BFA5E4188338](<Notebook/Dell/Latitude/Latitude E5420/BFA5E4188338>) |
| ELPIDA     | EBJ21UE8BDS0-DJ-F SODIMM     | 2 GB     | DDR3 | 1334 | 118   | [FE678B6F4581](<Notebook/Lenovo/ThinkPad/ThinkPad X201 3680AE2/FE678B6F4581>) |
| Ramaxel    | RMT3160ED58E9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 118   | [C8AAEE28B473](<Notebook/Lenovo/IdeaPad/IdeaPad Z580/C8AAEE28B473>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 118   | [E0194AABCF66](<Notebook/ASUSTek Computer/G752/G752VY/E0194AABCF66>) |
|            | 123456789012345678 DIMM      | 2 GB     | DDR3 | 2400 | 117   | [50E1392351E1](<Notebook/GTZS/Others/Others/50E1392351E1>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4 GB     | DDR3 | 2133 | 117   | [C0B609830055](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX/C0B609830055>) |
| Kingston   | KHX1600C10D3/4G DIMM         | 4 GB     | DDR3 | 1866 | 116   | [5658FF3D9881](<Desktop/Hewlett-Packard/500/500-305nr/5658FF3D9881>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 333  | 116   | [634B75269150](<Desktop/MSI/MS/MS-7309/634B75269150>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8192 MB  | DDR4 | 2667 | 116   | [61077ED80EDE](<Notebook/Lenovo/ThinkPad/ThinkPad E480 20KN002YPH/61077ED80EDE>) |
|            | Module SODIMM SDRAM          | 2048 MB  |      |      | 115   | [C5BC99C143A5](<Notebook/ASUSTek Computer/F5/F5VL/C5BC99C143A5>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 114   | [54A685670DC2](<Desktop/ASUSTek Computer/P5/P5Q/54A685670DC2>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 112   | [0E378723C03A](<Desktop/MSI/MS/MS-7383/0E378723C03A>) |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 111   | [102B49AD0832](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/102B49AD0832>) |
|            | Module DIMM                  | 2048 MB  | DDR2 |      | 110   | [F8C3EB1BD5E6](<Desktop/MSI/MS-7255/MS-7255 V2.0/F8C3EB1BD5E6>) |
| SK Hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 110   | [47D6316200BF](<Notebook/Lenovo/G570/G570 20079/47D6316200BF>) |
| Micron     | MT52L1G32D4PG-093 Row Of ... | 8 GB     |      | 2133 | 109   | [F0783EEF957D](<Notebook/ASUSTek Computer/UX430/UX430UNR/F0783EEF957D>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 109   | [5093EDB3DE85](<Desktop/Gigabyte Technology/G31/G31M-ES2C/5093EDB3DE85>) |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2048 MB  | DDR3 | 4199 | 109   | [D4948B95C865](<Notebook/Lenovo/ThinkPad/ThinkPad W500 40624DG/D4948B95C865>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4096 MB  | DDR3 | 1600 | 108   | [9B22FBBA8175](<Notebook/Lanix/NEURON_FLEX/NEURON_FLEX/9B22FBBA8175>) |
| Kingston   | 99U5471-020.A00LF DIMM       | 4096 MB  | DDR3 | 1600 | 108   | [E7690AFA9459](<Desktop/Intel/DH67VR/DH67VR AAG27177-201/E7690AFA9459>) |
|            | Module DIMM SDRAM            | 4096 MB  |      |      | 108   | [0BA79CA3AC69](<Desktop/Intel/H/H55/0BA79CA3AC69>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2048 MB  | DDR3 | 1867 | 107   | [BDFE1AAE0BC8](<Desktop/Hewlett-Packard/Compaq/Compaq 8000 Elite CMT PC/BDFE1AAE0BC8>) |
| Samsung    | M471A5244BB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 107   | [83B3AAE079AE](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bw0xx/83B3AAE079AE>) |
| Samsung    | M471B2873FHS-CH9 SODIMM      | 1 GB     | DDR3 | 1334 | 107   | [B9B75BA01934](<Notebook/Toshiba/Satellite/Satellite C660/B9B75BA01934>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 106   | [1819FDD9F3F3](<Desktop/Dell/OptiPlex/OptiPlex 790/1819FDD9F3F3>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4096 MB  | DDR3 | 1600 | 106   | [6DE8C9CB50E0](<Notebook/Toshiba/Satellite/Satellite Pro C850/6DE8C9CB50E0>) |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 106   | [26E6E3C2710A](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401QM_GA401QM/26E6E3C2710A>) |
|            | Module SODIMM                | 2048 MB  | DDR3 |      | 106   | [9FCEE346367F](<Notebook/Sony/SVE1511/SVE15111EBS/9FCEE346367F>) |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1333 | 106   | [B6E79EC23107](<Notebook/ASUSTek Computer/X553/X553MA/B6E79EC23107>) |
| Samsung    | M471B5273EB0-CK0 SODIMM      | 4096 MB  | DDR3 | 4199 | 106   | [F2681B1F8909](<Notebook/Medion/Akoya/Akoya E7221/F2681B1F8909>) |
| SK Hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 106   | [DB437DD57DBD](<Notebook/Packard Bell/EasyNote/EasyNote TE11HC/DB437DD57DBD>) |
| SK Hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 104   | [C211F711EF0E](<Notebook/Acer/Aspire/Aspire A315-21/C211F711EF0E>) |
| Kingston   | ACR256X64D3S1333C9 SODIMM    | 2 GB     | DDR3 | 1334 | 104   | [43A982614EFD](<Notebook/Acer/Aspire/Aspire 7250G/43A982614EFD>) |
| SK Hynix   | HMA82GS6CJR8N-VK SODIMM      | 16384 MB | DDR4 | 2667 | 104   | [94FBD70BA704](<Convertible/Fujitsu/LIFEBOOK/LIFEBOOK T939/94FBD70BA704>) |
| SK Hynix   | HMT325S6CFR8C-PB SODIMM      | 2 GB     | DDR3 | 1600 | 103   | [A627508AA712](<Notebook/Dell/Inspiron/Inspiron 7520/A627508AA712>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 103   | [142916096E18](<Desktop/ASUSTek Computer/P8H61-MX/P8H61-MX R2.0/142916096E18>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8192 MB  | DDR3 | 1600 | 102   | [061803342427](<Desktop/ASRock/FM2A88X/FM2A88X Extreme6+/061803342427>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 333  | 102   | [2E07B4740836](<Notebook/MSI/VR/VR630/2E07B4740836>) |
| Ramaxel    | RMT3170EB68F9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 102   | [A1974AA217A4](<Notebook/Lenovo/IdeaPad/IdeaPad Y510P 20217/A1974AA217A4>) |
| Samsung    | M4 70T5663QZ3-CF7 SODIMM     | 2 GB     | DDR2 | 2048 | 102   | [8D3893A85567](<Notebook/Toshiba/Satellite/Satellite L350D/8D3893A85567>) |
| Ramaxel    | RMSA3270ME86H9F-2666 SODIMM  | 4096 MB  | DDR4 | 2667 | 101   | [E10C1473180B](<Notebook/Lenovo/IdeaPad/IdeaPad 330S-15ARR 81FB/E10C1473180B>) |
| SK Hynix   | HMT325S6BFR8C-H9 SODIMM      | 2048 MB  | DDR3 | 1333 | 100   | [B7D1BA0BD879](<Notebook/Dell/Latitude/Latitude E6520/B7D1BA0BD879>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 100   | [A5ACADA3093D](<Desktop/Dell/XPS/XPS 8700/A5ACADA3093D>) |
| Samsung    | M471A2G44AM0-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 100   | [03B6D51ED61F](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 2i 20W0000FRT/03B6D51ED61F>) |
| SK Hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 99    | [A142678A0F18](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349T7Z/A142678A0F18>) |
| Micron     | 4ATF1G64HZ-3G2E1 Row Of C... | 8192 MB  | DDR4 | 3200 | 99    | [BFC66FC359C3](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 15ALC05 82HV/BFC66FC359C3>) |
|            | Module SODIMM SDRAM          | 1024 MB  |      |      | 98    | [C5BC99C143A5](<Notebook/ASUSTek Computer/F5/F5VL/C5BC99C143A5>) |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1600 | 98    | [AC331E492606](<Tablet/ASUSTek Computer/T101/T101HA/AC331E492606>) |
| Samsung    | M471A5244CB0-CTD Row Of C... | 4 GB     | DDR4 | 2667 | 98    | [F37C902F78E2](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15IIL05 81WE/F37C902F78E2>) |
| Kingston   | KHX1866C10D3/4G DIMM         | 4096 MB  | DDR3 | 1867 | 97    | [1B12ED7641A9](<Desktop/MSI/MS/MS-7693/1B12ED7641A9>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1333 | 97    | [730ACCC800BC](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro MT PC/730ACCC800BC>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 96    | [FCC9E00E8E76](<Desktop/Gigabyte Technology/M68/M68MT-S2/FCC9E00E8E76>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1600 | 96    | [B8B73FE9DC5D](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92p 3209AE2/B8B73FE9DC5D>) |
|            | Module DIMM                  | 2048 MB  |      |      | 94    | [04D3945C543C](<Desktop/MSI/MS/MS-7253/04D3945C543C>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 92    | [06C7EA1421C3](<Desktop/Dell/OptiPlex/OptiPlex 7020/06C7EA1421C3>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4096 MB  |      | 1866 | 92    | [85548CCDD242](<Desktop/Foxconn/A74ML-A74ML-K/A74ML-A74ML-K 3.0 1.0/85548CCDD242>) |
| Samsung    | Module SODIMM                | 16384 MB | DDR4 | 2667 | 92    | [F50B1CFDFE6F](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G7 Notebook PC/F50B1CFDFE6F>) |
| Kingston   | ACR16D3LS1KFG/4G SODIMM      | 4 GB     | DDR3 | 1600 | 91    | [816512D2A9F7](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G1/816512D2A9F7>) |
| Samsung    | M471A1K43BB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 91    | [974FF46B3D36](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2000KRT/974FF46B3D36>) |
| SK Hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 91    | [83E2F254AB1A](<Notebook/Dell/G5/G5 5590/83E2F254AB1A>) |
| A-DATA     | AD73I1C1674EV SODIMM         | 4 GB     | DDR3 | 1334 | 90    | [62EC09661292](<Notebook/Acer/P5/P5WE0/62EC09661292>) |
| Kingston   | KHX3200C16D4/16GX DIMM       | 16 GB    | DDR4 | 3600 | 88    | [DADB6007C9F6](<Desktop/Gigabyte Technology/B450M/B450M S2H V2/DADB6007C9F6>) |
| Micron     | 8ATF1G64HZ-2G3B1 SODIMM      | 8192 MB  | DDR4 | 2400 | 88    | [6D894B1F1576](<Notebook/ASUSTek Computer/X541/X541UV/6D894B1F1576>) |
| SK Hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 87    | [19886291EEA7](<Notebook/HONOR/BMH-WCX/BMH-WCX9/19886291EEA7>) |
| Ramaxel    | RMT3170ME68F9F1600 SODIMM    | 4096 MB  | DDR3 | 1600 | 87    | [C37F879592F8](<Notebook/VIT/P/P3400/C37F879592F8>) |
| Samsung    | M471B5173BH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 87    | [34CA006E121F](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK E752/34CA006E121F>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 86    | [152ABEB9848B](<Desktop/ASRock/FM2/FM2A68M-HD+/152ABEB9848B>) |
| Nanya      | NT4GC64B8HG0NS-DI SODIMM     | 4 GB     | DDR3 | 1600 | 86    | [BAC438B6794A](<Notebook/Lenovo/ThinkPad/ThinkPad Edge E330 33544RG/BAC438B6794A>) |
|            | Module DIMM                  | 4096 MB  |      | 667  | 86    | [B06292396246](<Desktop/ASRock/760/760GM-S3/B06292396246>) |
|            | Module SODIMM                | 512 MB   | DDR2 |      | 86    | [F423B8D28ACA](<Notebook/Acer/Aspire/Aspire 5600/F423B8D28ACA>) |
|            | Module DIMM DDR              | 2048 MB  |      | 800  | 85    | [05DA055BCD6E](<Desktop/Intel/DG31PR/DG31PR AAE58249-302/05DA055BCD6E>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 85    | [8B1956B33C0C](<Desktop/Gigabyte Technology/E2500/E2500N/8B1956B33C0C>) |
| Samsung    | M4 70T5663EH3-CF7 SODIMM     | 2048 MB  | DDR2 | 975  | 85    | [D704743A111D](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/D704743A111D>) |
| SK Hynix   | HMT451S6BFR8A-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 85    | [6B013048EA7E](<Notebook/Dell/Inspiron/Inspiron 5759/6B013048EA7E>) |
| Corsair    | CMK16GX4M2A2666C16 DIMM      | 8 GB     | DDR4 | 3200 | 84    | [4E6DCAC3F74A](<Desktop/Gigabyte Technology/B460/B460MDS3H/4E6DCAC3F74A>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4096 MB  | DDR3 | 1600 | 84    | [F640F8067BC1](<Notebook/ASUSTek Computer/X555/X555LAB/F640F8067BC1>) |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1600 | 84    | [964E82AC2486](<Notebook/Dell/Venue/Venue 10 Pro 5056/964E82AC2486>) |
|            | Module DIMM                  | 8192 MB  |      | 1333 | 84    | [0BB8D8851537](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/0BB8D8851537>) |
| Samsung    | K4EBE304EB-EGCG Row Of Ch... | 8192 MB  |      | 2133 | 84    | [3D3FB636D7D4](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KJCTO1WW/3D3FB636D7D4>) |
| SK Hynix   | HMT451U6AFR8C-PB DIMM        | 4096 MB  | DDR3 | 1600 | 82    | [C159B982C0A3](<Desktop/Dell/XPS/XPS 8700/C159B982C0A3>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 82    | [8D43652EF1E4](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NJ0004US/8D43652EF1E4>) |
|            | Module SODIMM                | 4 GB     | DDR3 |      | 82    | [FC63E4EF3121](<Notebook/Sony/VPCEH25/VPCEH25FM/FC63E4EF3121>) |
|            | Module DIMM                  | 512 MB   |      |      | 82    | [767847787F84](<Desktop/Others/NF-CK/NF-CK804/767847787F84>) |
| Kingston   | KHX1600C10D3/8GX DIMM        | 8 GB     | DDR3 | 1600 | 81    | [95481F84493C](<Desktop/ASUSTek Computer/P8/P8H77-M/95481F84493C>) |
| Ramaxel    | RMT3020EC58E9F1333 SODIMM    | 4 GB     | DDR3 | 4199 | 81    | [D2C007C69B47](<Notebook/Acer/Aspire/Aspire 5742/D2C007C69B47>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 81    | [FD4661A696AE](<Notebook/ASUSTek Computer/BU203/BU203UA/FD4661A696AE>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 80    | [7CE99EB9C943](<Notebook/Sony/VGN-FZ31/VGN-FZ31Z/7CE99EB9C943>) |
|            | Module DIMM                  | 4096 MB  |      | 1066 | 80    | [8D101F548ADF](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S5/8D101F548ADF>) |
| Samsung    | M471B2873FHS-CF8 SODIMM      | 1 GB     | DDR3 | 1067 | 80    | [7BC552597A23](<Notebook/Toshiba/Satellite/Satellite C650/7BC552597A23>) |
| Kingston   | KHX2666C15S4/16G SODIMM      | 16 GB    | DDR4 | 2667 | 79    | [14C0A4E81369](<Notebook/Lenovo/Legion/Legion Y740-17IRHg 81UJ/14C0A4E81369>) |
| Samsung    | Module SODIMM                | 8192 MB  | DDR4 | 2133 | 79    | [533270214791](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/533270214791>) |
| Crucial    | CT51264BA160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 78    | [8C3AF54FF460](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/8C3AF54FF460>) |
| Elpida     | Module SODIMM                | 2 GB     | DDR3 | 1333 | 78    | [34BFD3754C9D](<All In One/Apple/iMac12/iMac12,2/34BFD3754C9D>) |
| Samsung    | M471A1K43EB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 78    | [4B98458F8617](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible 14-dy0xxx/4B98458F8617>) |
| SK Hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 77    | [F50BB8181F14](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509DA_D509DA/F50BB8181F14>) |
| SK Hynix   | HMT351U6CFR8C-H9 DIMM        | 4 GB     | DDR3 | 1600 | 77    | [5DE062D01A07](<Desktop/Gigabyte Technology/H61/H61M-S2PV/5DE062D01A07>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 400  | 77    | [7E99126A6978](<Desktop/ASRock/A780/A780LM-S/7E99126A6978>) |
| Samsung    | M471B5273CH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 77    | [E26542CEF3CE](<Notebook/Toshiba/Satellite/Satellite U900/E26542CEF3CE>) |
| SK Hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 77    | [4A76B33F46B6](<Notebook/Lenovo/IdeaPad/IdeaPad Y700-17ISK 80Q0/4A76B33F46B6>) |
| SK Hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 77    | [A61605E07164](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FN003LUK/A61605E07164>) |
| Kingston   | 99U5428-063.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 76    | [B7D5F0DBA7E1](<Notebook/Acer/Aspire/Aspire V3-771/B7D5F0DBA7E1>) |
| SK Hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 76    | [8E2B386FEFA9](<Notebook/Lenovo/G505s/G505s 20255/8E2B386FEFA9>) |
| SK Hynix   | HMA851S6CJR6N-VK Row Of C... | 4096 MB  | DDR4 | 2667 | 75    | [87D19DE46F32](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/87D19DE46F32>) |
| Kingston   | 99U5474-028.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 75    | [55A4AE88B3AA](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/55A4AE88B3AA>) |
| Micron     | 4ATF51264HZ-3G2J1 Row Of ... | 4 GB     | DDR4 | 3200 | 75    | [19886291EEA7](<Notebook/HONOR/BMH-WCX/BMH-WCX9/19886291EEA7>) |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4 GB     | DDR3 | 1867 | 75    | [1D8D4ACC2772](<Desktop/Hewlett-Packard/CQ3321/CQ3321L/1D8D4ACC2772>) |
| A-DATA     | AD73I1C1674EV SODIMM         | 4096 MB  | DDR3 | 1334 | 74    | [565EAE2BD13F](<Notebook/Dell/Latitude/Latitude E5420/565EAE2BD13F>) |
|            | Module DIMM                  | 1024 MB  |      | 400  | 74    | [3342C5FC36D5](<Desktop/Gigabyte Technology/M61/M61SME-S2/3342C5FC36D5>) |
|            | Module SODIMM                | 2048 MB  |      | 800  | 73    | [EE81FA330179](<Notebook/eMachines/E/E725/EE81FA330179>) |
|            | Module SODIMM DRAM           | 2048 MB  |      |      | 72    | [6D4191019A04](<Notebook/Samsung Electronics/R59/R59P-R60P-R61P/6D4191019A04>) |
|            | Module DIMM DDR              | 4096 MB  |      | 1333 | 72    | [E2D4E3301241](<Desktop/ASUSTek Computer/P7/P7P55D/E2D4E3301241>) |
| SK Hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2400 | 70    | [C211F711EF0E](<Notebook/Acer/Aspire/Aspire A315-21/C211F711EF0E>) |
| SK Hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 70    | [FCD087A5B453](<Notebook/Hewlett-Packard/G/G62/FCD087A5B453>) |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 70    | [FFC4E3644992](<Notebook/Dell/XPS/XPS 15 9570/FFC4E3644992>) |
| Samsung    | Module Row Of Chips LPDDR3   | 8192 MB  |      | 2133 | 70    | [5DF167F47532](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 7th 20QD000SUS/5DF167F47532>) |
| Kingston   | ACR16D3LFS1KBG/2G SODIMM     | 2048 MB  | DDR3 | 1600 | 69    | [AE680B572771](<Notebook/Acer/Aspire/Aspire ES1-411/AE680B572771>) |
| Kingston   | KHX2133C14/8G DIMM           | 8 GB     | DDR4 | 2400 | 69    | [9E21E5D22811](<Desktop/Gigabyte Technology/H110/H110M-S2PT-CF/9E21E5D22811>) |
| Samsung    | M471A5244CB0-CWE Row Of C... | 4 GB     | DDR4 | 3200 | 69    | [23E66A988517](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ALC05 82HU/23E66A988517>) |
| SK Hynix   | HMA82GS6DJR8N-XN SODIMM      | 16 GB    | DDR4 | 3200 | 69    | [33F2D924CBA3](<Notebook/Dell/Latitude/Latitude 5411/33F2D924CBA3>) |
| Corsair    | CMX8GX3M2A1600C9 DIMM        | 4096 MB  | DDR3 | 1800 | 68    | [89EFA22E5973](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/89EFA22E5973>) |
| SK Hynix   | HMA81GS6DJR8N-XN SODIMM      | 8192 MB  | DDR4 | 3200 | 68    | [2DE5FE7D7CF9](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-eq1xxx/2DE5FE7D7CF9>) |
| Micron     | 16JSF25664HZ-1G1F1 SODIMM    | 2 GB     | DDR3 | 1067 | 68    | [F03C6FCD4436](<Notebook/ASUSTek Computer/S550/S550CM/F03C6FCD4436>) |
|            | Module SODIMM                | 2048 MB  |      | 667  | 68    | [B009AF88D443](<Notebook/ASUSTek Computer/1011/1011PX/B009AF88D443>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| ASUSTek    | ASUS           | 63.0  | Li-ion  | 1586  | [14237B32D9](https://linux-hardware.org/?probe=14237b32d9) |
| Hewlett... | PABAS0241231   | 41.1  | Li-ion  | 737   | [1064E67665](https://linux-hardware.org/?probe=1064e67665) |
| Compal     | PABAS0241231   | 47.5  | Li-ion  | 690   | [F6068483CE](https://linux-hardware.org/?probe=f6068483ce) |
| Lenovo     | PABAS0241231   | 23.8  | Li-ion  | 612   | [D20EF03D37](https://linux-hardware.org/?probe=d20ef03d37) |
| Samsung    |                | 49    | Li-ion  | 408   | [7E3A87A955](https://linux-hardware.org/?probe=7e3a87a955) |
| SMP        | bq20z451       | 54.7  | Li-ion  | 385   | [2A4E580BD6](https://linux-hardware.org/?probe=2a4e580bd6) |
| MSI        | BIF0_9         | 52.4  | Li-ion  | 359   | [698AF00B9C](https://linux-hardware.org/?probe=698af00b9c) |
| Intel SR 1 | SR Real        | 35.5  |         | 284   | [C166EC8175](https://linux-hardware.org/?probe=c166ec8175) |
| SANYO      | Li_Ion_4000mA  | 73.3  | Li-ion  | 284   | [79A1D21F1E](https://linux-hardware.org/?probe=79a1d21f1e) |
| Hewlett... | Primary        | 45    | Li-ion  | 275   | [311C6DA8E0](https://linux-hardware.org/?probe=311c6da8e0) |
| OEM        | standard       | 47.5  | Li-ion  | 272   | [C2A1BE9B32](https://linux-hardware.org/?probe=c2a1be9b32) |
| Hewlett... | Primary        | 48    | Li-ion  | 269   | [02DF6E8B6E](https://linux-hardware.org/?probe=02df6e8b6e) |
| SMP        | DELL GPM0365   | 97.0  | Li-ion  | 266   | [73526F92AC](https://linux-hardware.org/?probe=73526f92ac) |
| Samsung    | SR Real        | 43.1  | Li-ion  | 218   | [CCA05024CE](https://linux-hardware.org/?probe=cca05024ce) |
| Hewlett... | Primary        | 40    | Li-ion  | 202   | [05BB30084A](https://linux-hardware.org/?probe=05bb30084a) |
| LG         | PABAS0241231   | 4.0   | Li-ion  | 199   | [F7CF64AFDE](https://linux-hardware.org/?probe=f7cf64afde) |
| Hewlett... | Primary        | 44    | Li-ion  | 194   | [FBC726A0B8](https://linux-hardware.org/?probe=fbc726a0b8) |
| Notebook   | BAT            | 49    | Li-ion  | 181   | [04622692C4](https://linux-hardware.org/?probe=04622692c4) |
| Hewlett... | Primary        | 42    | Li-ion  | 175   | [B610AEABED](https://linux-hardware.org/?probe=b610aeabed) |
| ASUSTek    | A32-K55        | 48.0  | Li-ion  | 173   | [5546A82362](https://linux-hardware.org/?probe=5546a82362) |
| Samsung    |                | 44    | Li-ion  | 169   | [546B3E4C0B](https://linux-hardware.org/?probe=546b3e4c0b) |
| SANYO      | 45N1773        | 23.2  | Li-ion  | 168   | [5E026C07C0](https://linux-hardware.org/?probe=5e026c07c0) |
| DP         | bq20z451       | 63.2  | Li-ion  | 166   | [FB03915A3E](https://linux-hardware.org/?probe=fb03915a3e) |
| Hewlett... | Primary        | 41    | Li-ion  | 166   | [3B6604EFC1](https://linux-hardware.org/?probe=3b6604efc1) |
| ASUSTek    | X550A26        | 38.5  | Li-ion  | 160   | [A7394D72A0](https://linux-hardware.org/?probe=a7394d72a0) |
| Hewlett... | Primary        | 39    | Li-ion  | 150   | [CC637B12DE](https://linux-hardware.org/?probe=cc637b12de) |
| Hewlett... | Primary        | 43    | Li-ion  | 144   | [C5BF02A4D7](https://linux-hardware.org/?probe=c5bf02a4d7) |
| SMP        | L16M2PB1       | 30.0  | Li-poly | 144   | [5AF22F3639](https://linux-hardware.org/?probe=5af22f3639) |
| Hewlett... | Primary        | 38    | Li-ion  | 142   | [C98FCBEC3C](https://linux-hardware.org/?probe=c98fcbec3c) |
| LGC        | 45N1127        | 23.5  | Li-ion  | 141   | [5E026C07C0](https://linux-hardware.org/?probe=5e026c07c0) |
| SANYO      | PABAS0241231   | 3.9   | Li-ion  | 140   | [1F84B1E42D](https://linux-hardware.org/?probe=1f84b1e42d) |
| SANYO      | AL10B31        | 48.8  | Li-ion  | 135   | [FC0BCCC42D](https://linux-hardware.org/?probe=fc0bccc42d) |
| Hewlett... | Primary        | 46    | Li-ion  | 131   | [9FFC6B43EC](https://linux-hardware.org/?probe=9ffc6b43ec) |
| SANYO      | AL12A32        | 48.8  | Li-ion  | 128   | [E909E31559](https://linux-hardware.org/?probe=e909e31559) |
| SIMPLO     | PABAS0241231   | 37.5  | Li-ion  | 126   | [36CD8309BC](https://linux-hardware.org/?probe=36cd8309bc) |
| PANASONIC  | Li_Ion_4000mA  | 47.5  | Li-ion  | 124   | [3D4087DC2A](https://linux-hardware.org/?probe=3d4087dc2a) |
| Hewlett... | Primary        | 50    | Li-ion  | 122   | [55A6D982B3](https://linux-hardware.org/?probe=55a6d982b3) |
| Hewlett... | Primary        | 53    | Li-ion  | 120   | [034F4D4131](https://linux-hardware.org/?probe=034f4d4131) |
| LG         | Li_Ion_4000mA  | 47.5  | Li-ion  | 119   | [7535A8D317](https://linux-hardware.org/?probe=7535a8d317) |
| Hewlett... | Primary        | 36    | Li-ion  | 118   | [863340BAB2](https://linux-hardware.org/?probe=863340bab2) |
| SMP        | DELL G8VCF6C   | 52.0  | Li-poly | 118   | [EFC6123D49](https://linux-hardware.org/?probe=efc6123d49) |
| SANYO      | 45N1775        | 23.2  | Li-ion  | 114   | [10655C6E60](https://linux-hardware.org/?probe=10655c6e60) |
| ASUSTek    | K52F-44        | 48.4  | Li-ion  | 107   | [51504B5B77](https://linux-hardware.org/?probe=51504b5b77) |
| SANYO      | AS10D31        | 47.5  | Li-ion  | 107   | [65C44B63D6](https://linux-hardware.org/?probe=65c44b63d6) |
| Hewlett... | Primary        | 37    | Li-ion  | 106   | [65130B9760](https://linux-hardware.org/?probe=65130b9760) |
| Hewlett... | Primary        | 56    | Li-ion  | 106   | [42921AEBFD](https://linux-hardware.org/?probe=42921aebfd) |
| Hewlett... | Primary        | 49    | Li-ion  | 105   | [1F26DFD88F](https://linux-hardware.org/?probe=1f26dfd88f) |
| PANASONIC  | AP16M5J        | 37.0  | Li-ion  | 104   | [435C237F8F](https://linux-hardware.org/?probe=435c237f8f) |
| SANYO      | AL15A32        | 37.0  | Li-ion  | 104   | [C1CD812A42](https://linux-hardware.org/?probe=c1cd812a42) |
| ASUSTek    | F82--22        | 48.4  | Li-ion  | 103   | [F20C485A7B](https://linux-hardware.org/?probe=f20c485a7b) |
|            | Battery        |       |         | 102   | [946300C067](https://linux-hardware.org/?probe=946300c067) |
| CPT-COS    | L16C2PB2       | 30.6  | Li-poly | 99    | [4D274AFB4A](https://linux-hardware.org/?probe=4d274afb4a) |
| Samsung    |                | 48    | Li-ion  | 99    | [A0A9CF96A8](https://linux-hardware.org/?probe=a0a9cf96a8) |
| LGC        | 45N1049        | 40.4  | Li-ion  | 98    | [46D63F7527](https://linux-hardware.org/?probe=46d63f7527) |
| Hewlett... | Primary        |       | Li-ion  | 97    | [1BA50507CC](https://linux-hardware.org/?probe=1ba50507cc) |
| SANYO      | GC86508SAT0    | 44.4  | Li-ion  | 97    | [B18E761C0F](https://linux-hardware.org/?probe=b18e761c0f) |
| SMP        | DELL Y3F7Y6B   | 42.0  | Li-ion  | 97    | [70D2AFDA85](https://linux-hardware.org/?probe=70d2afda85) |
| ASUSTek    | X550A30        | 44.6  | Li-ion  | 93    | [0A1F5E9BED](https://linux-hardware.org/?probe=0a1f5e9bed) |
| LGC        | AC14B8K        | 48.9  | Li-ion  | 93    | [038CC99EAD](https://linux-hardware.org/?probe=038cc99ead) |
| LGC        | L16L2PB2       | 30.0  | Li-poly | 93    | [BF565614CA](https://linux-hardware.org/?probe=bf565614ca) |
| Sony       | 45N1111        | 23.2  | Li-poly | 93    | [10655C6E60](https://linux-hardware.org/?probe=10655c6e60) |
| Sony       | VGP-BPS26      | 43.2  | Li-ion  | 92    | [5A60A14CF4](https://linux-hardware.org/?probe=5a60a14cf4) |
| SANYO      | 00323341343... | 48.8  | Li-ion  | 91    | [C2F6FAF193](https://linux-hardware.org/?probe=c2f6faf193) |
| SANYO      | PABAS024       | 47.5  | Li-ion  | 91    | [A3A3EA2BD9](https://linux-hardware.org/?probe=a3a3ea2bd9) |
| Hewlett... | Primary        | 47    | Li-ion  | 87    | [166E1147D2](https://linux-hardware.org/?probe=166e1147d2) |
| Notebook   | BAT            | 62    | Li-ion  | 87    | [371FBC5A98](https://linux-hardware.org/?probe=371fbc5a98) |
| PANASONIC  | AS16A5K        | 41.4  | Li-ion  | 84    | [9D9AE9F531](https://linux-hardware.org/?probe=9d9ae9f531) |
| SMP        | 5B10W13933     | 46.0  | Li-poly | 84    | [4BC0114FA0](https://linux-hardware.org/?probe=4bc0114fa0) |
| Hewlett... | Primary        | 32    | Li-ion  | 83    | [33D5B7046B](https://linux-hardware.org/?probe=33d5b7046b) |
| Hewlett... | Primary        | 35    | Li-ion  | 83    | [838F13E574](https://linux-hardware.org/?probe=838f13e574) |
| LGC        | AP18C8K        | 48.0  | Li-ion  | 83    | [160A8DD021](https://linux-hardware.org/?probe=160a8dd021) |
| TKBSS      | NS2P3SZMC4WR   | 48.4  | Li-ion  | 83    | [14AC6C1F51](https://linux-hardware.org/?probe=14ac6c1f51) |
| ASUSTek    | K55--44        | 47.5  | Li-ion  | 81    | [C7C38F077D](https://linux-hardware.org/?probe=c7c38f077d) |
| LG         | 004B3842343... | 48.9  | Li-ion  | 81    | [156E7734BE](https://linux-hardware.org/?probe=156e7734be) |
|            | 47.52          | 48    | Li-ion  | 80    | [73D930BE97](https://linux-hardware.org/?probe=73d930be97) |
| ASUSTek    | UX31-35        | 47.9  | Li-ion  | 79    | [62F3B41D12](https://linux-hardware.org/?probe=62f3b41d12) |
| LGC        | 5B10W139       | 50.5  | Li-poly | 79    | [3333E54277](https://linux-hardware.org/?probe=3333e54277) |
| Samsung    |                | 58    | Li-ion  | 78    | [88AA731039](https://linux-hardware.org/?probe=88aa731039) |
| SMP        | L16M2PB2       | 35.0  | Li-poly | 78    | [13BC7E73F1](https://linux-hardware.org/?probe=13bc7e73f1) |
| LG         | PABAS024       | 47.5  | Li-ion  | 77    | [7109402C58](https://linux-hardware.org/?probe=7109402c58) |
| Hewlett... | Primary        | 34    | Li-ion  | 76    | [34D4439B39](https://linux-hardware.org/?probe=34d4439b39) |
| LGC        | AC14B18J       | 36.7  | Li-ion  | 76    | [6F53445C9D](https://linux-hardware.org/?probe=6f53445c9d) |
| Hewlett... | Primary        | 55    | Li-ion  | 75    | [7AC4ED97E7](https://linux-hardware.org/?probe=7ac4ed97e7) |
| ASUSTek    | X555-50        | 37.3  | Li-ion  | 74    | [74E5474A84](https://linux-hardware.org/?probe=74e5474a84) |
| Hewlett... | Primary        | 28    | Li-ion  | 73    | [AD18E8D0B3](https://linux-hardware.org/?probe=ad18e8d0b3) |
| Notebook   | BAT            | 48    | Li-ion  | 73    | [E4CACB360F](https://linux-hardware.org/?probe=e4cacb360f) |
| Lenovo     | BASE-BAT       | 30.0  | Li-poly | 71    | [B950D195CE](https://linux-hardware.org/?probe=b950d195ce) |
| Hewlett... | Primary        | 30    | Li-ion  | 68    | [C4F663B37B](https://linux-hardware.org/?probe=c4f663b37b) |
| LGC        | AP18E8M        | 57.5  | Li-ion  | 68    | [7E967F4DAA](https://linux-hardware.org/?probe=7e967f4daa) |
| LGC        | 45N1113        | 23.5  | Li-ion  | 67    | [BD60AAE97A](https://linux-hardware.org/?probe=bd60aae97a) |
| ASUSTek    | K53--52        | 57.2  | Li-ion  | 66    | [D0ECEBAB71](https://linux-hardware.org/?probe=d0ecebab71) |
| Celxpert   | 01AV448        | 45.7  | Li-poly | 66    | [5DBB969BD8](https://linux-hardware.org/?probe=5dbb969bd8) |
| SMP        | 01AV421        | 24.0  | Li-poly | 66    | [755854F7D4](https://linux-hardware.org/?probe=755854f7d4) |
| SANYO      | 45N1001        | 47.5  | Li-ion  | 63    | [CEEC77F198](https://linux-hardware.org/?probe=ceec77f198) |
| Hewlett... | Primary        | 41    | Li-ion  | 62    | [5C45B0B08A](https://linux-hardware.org/?probe=5c45b0b08a) |
| SANYO      | GRAPE32        | 44.4  | Li-ion  | 62    | [FA85BE94B2](https://linux-hardware.org/?probe=fa85be94b2) |
| Sony       | Li_Ion_4000mA  | 48.8  | Li-ion  | 62    | [C039F0A68D](https://linux-hardware.org/?probe=c039f0a68d) |
| Hewlett... | Primary        | 31    | Li-ion  | 61    | [81371D4535](https://linux-hardware.org/?probe=81371d4535) |
| Hewlett... | Primary        | 89    | Li-ion  | 60    | [4702DAB234](https://linux-hardware.org/?probe=4702dab234) |
| SMP        | DELL 70N2F95   | 84.3  | Li-poly | 60    | [0391AC1BA1](https://linux-hardware.org/?probe=0391ac1ba1) |
| ASUSTek    | F3---24        |       | Li-ion  | 59    | [AB9D32A3FF](https://linux-hardware.org/?probe=ab9d32a3ff) |
| SMP        | 01AV447        | 45.7  | Li-poly | 59    | [235260070B](https://linux-hardware.org/?probe=235260070b) |
| Hewlett... | 5600           | 62.2  |         | 58    | [3BD981AA35](https://linux-hardware.org/?probe=3bd981aa35) |
| Hewlett... | Primary        | 29    | Li-ion  | 58    | [8ADB026A31](https://linux-hardware.org/?probe=8adb026a31) |
| Sony       |                | 42    | Li-ion  | 58    | [B00A6A15B2](https://linux-hardware.org/?probe=b00a6a15b2) |
| Hewlett... | Primary        | 27    | Li-ion  | 57    | [E72FBDDBC9](https://linux-hardware.org/?probe=e72fbddbc9) |
| SMP        | DELL TP1GT61   | 60.0  | Li-poly | 57    | [76D17811E3](https://linux-hardware.org/?probe=76d17811e3) |
| SMP        | DELL VN3N047   | 41.4  | Li-ion  | 57    | [523CBA2431](https://linux-hardware.org/?probe=523cba2431) |
| ASUSTek    | N56--52        | 57.2  | Li-ion  | 56    | [A1D8D94B5F](https://linux-hardware.org/?probe=a1d8d94b5f) |
| CPT-COS    | L17C4PB0       | 45.5  | Li-poly | 56    | [408821B06E](https://linux-hardware.org/?probe=408821b06e) |
| Lenovo ... |                | 28    |         | 56    | [3EA53E359A](https://linux-hardware.org/?probe=3ea53e359a) |
| ASUSTek    | F5---22        | 46.2  | Li-ion  | 55    | [01ACCF63AD](https://linux-hardware.org/?probe=01accf63ad) |
| SANYO      | 45N1043        | 38.9  | Li-ion  | 55    | [B69439C244](https://linux-hardware.org/?probe=b69439c244) |
| Hewlett... | Primary        | 42    | Li-ion  | 54    | [80B844D396](https://linux-hardware.org/?probe=80b844d396) |
| ASUSTek    | K53--27        | 37.8  | Li-ion  | 52    | [5850A8DD22](https://linux-hardware.org/?probe=5850a8dd22) |
| Notebook   | BAT            | 53    | Li-ion  | 52    | [7C9F5C83CF](https://linux-hardware.org/?probe=7c9f5c83cf) |
| SANYO      | L09S6Y02       | 38.9  | Li-ion  | 52    | [92822445BB](https://linux-hardware.org/?probe=92822445bb) |
|            | 48.6           | 49    | Li-ion  | 51    | [A757F64435](https://linux-hardware.org/?probe=a757f64435) |
| Lenovo     |                | 28    |         | 51    | [18BD9BBBE0](https://linux-hardware.org/?probe=18bd9bbbe0) |
| OEM        | FX50442        | 48.0  | Li-ion  | 51    | [ED4DB5233E](https://linux-hardware.org/?probe=ed4db5233e) |
| Samsung    |                | 24    | Li-ion  | 51    | [47EC2E67D9](https://linux-hardware.org/?probe=47ec2e67d9) |
| Simplo     | SDI ICR18650   | 47.5  | Li-ion  | 51    | [80A80D7619](https://linux-hardware.org/?probe=80a80d7619) |
|            | 48.84          | 49    | Li-ion  | 50    | [463CA7F3A3](https://linux-hardware.org/?probe=463ca7f3a3) |
| CPT-COS    | L16C2PB1       | 35.3  | Li-poly | 50    | [0A92C063A1](https://linux-hardware.org/?probe=0a92c063a1) |
| Hewlett... | Primary        | 33    | Li-ion  | 50    | [C313B8EE39](https://linux-hardware.org/?probe=c313b8ee39) |
| LGC        | L16L2PB3       | 35.0  | Li-poly | 50    | [77188D21BF](https://linux-hardware.org/?probe=77188d21bf) |
| DYNAPACK   | HB4593R1ECW    | 56.3  | Li-ion  | 49    | [2816CB0172](https://linux-hardware.org/?probe=2816cb0172) |
| LGC        | 01AV445        | 45.0  | Li-poly | 49    | [2F136D5BF5](https://linux-hardware.org/?probe=2f136d5bf5) |
| LGC        | 45N1025        | 62.2  | Li-ion  | 49    | [D8480748C7](https://linux-hardware.org/?probe=d8480748c7) |
| SMP        | L19M4PC0       | 60.0  | Li-poly | 49    | [92CCEBCC90](https://linux-hardware.org/?probe=92ccebcc90) |
| ASUSTek    | K55--47        | 51.7  | Li-ion  | 48    | [3DF16E8D72](https://linux-hardware.org/?probe=3df16e8d72) |
| ASUSTek    | X453-42        | 31.7  | Li-ion  | 48    | [94EBAA5D9B](https://linux-hardware.org/?probe=94ebaa5d9b) |
| LGC        | 45N1005        | 56.2  | Li-ion  | 48    | [B567C4922E](https://linux-hardware.org/?probe=b567c4922e) |
| LGC        | 45N1011        | 93.6  | Li-ion  | 48    | [6EB3E0ED53](https://linux-hardware.org/?probe=6eb3e0ed53) |
| LGC        | LNV-45N1       | 47.5  | Li-ion  | 48    | [470CD66AE6](https://linux-hardware.org/?probe=470cd66ae6) |
| SMP        | 01AV430        | 57.0  | Li-poly | 48    | [0278765EF8](https://linux-hardware.org/?probe=0278765ef8) |
| Sunwoda-H  | HB4692Z9ECW-41 | 55.2  | Li-ion  | 48    | [6ADD82CE5C](https://linux-hardware.org/?probe=6add82ce5c) |
| ASUSTek    | 1015PE         | 56.2  | Li-ion  | 47    | [776D052837](https://linux-hardware.org/?probe=776d052837) |
| LGC        | 02DL004        | 51.0  | Li-poly | 47    | [E00760F649](https://linux-hardware.org/?probe=e00760f649) |
| Hewlett... | Primary        | 26    | Li-ion  | 46    | [67825B30B9](https://linux-hardware.org/?probe=67825b30b9) |
| Hewlett... | Primary        | 51    | Li-ion  | 46    | [CF41CC6DDB](https://linux-hardware.org/?probe=cf41cc6ddb) |
| Razer      | Blade          | 65.0  |         | 46    | [4B78377A27](https://linux-hardware.org/?probe=4b78377a27) |
| CPT-COS    | L14C3P6        | 36.6  | Li-ion  | 45    | [CB421B796B](https://linux-hardware.org/?probe=cb421b796b) |
| Hewlett... | Primary        | 57    | Li-ion  | 45    | [C9B7431269](https://linux-hardware.org/?probe=c9b7431269) |
| Sony       |                | 51    | Li-ion  | 45    | [47587383D1](https://linux-hardware.org/?probe=47587383d1) |
| Celxpert   | 01AV424        | 24.1  | Li-poly | 44    | [755854F7D4](https://linux-hardware.org/?probe=755854f7d4) |
| Celxpert   | L19C3PD6       | 52.5  | Li-poly | 44    | [DCD6F3190E](https://linux-hardware.org/?probe=dcd6f3190e) |
| LGC        | L17L2PF1       | 30.0  | Li-poly | 44    | [1E700D65EA](https://linux-hardware.org/?probe=1e700d65ea) |
| PANASONIC  | AP19B5L        | 53.0  | Li-ion  | 44    | [68E933E6A3](https://linux-hardware.org/?probe=68e933e6a3) |
| SANYO      | 01AV405        | 26.3  | Li-ion  | 44    | [964C1A1526](https://linux-hardware.org/?probe=964c1a1526) |
| SMP        | 02DL005        | 51.0  | Li-poly | 44    | [6AF6121C33](https://linux-hardware.org/?probe=6af6121c33) |
| SUNWODA    | R15B01W        | 60.0  | Li-ion  | 44    | [5886B2F027](https://linux-hardware.org/?probe=5886b2f027) |
| TPS        | S10            | 48.8  | Li-ion  | 44    | [F3B678924D](https://linux-hardware.org/?probe=f3b678924d) |
| Hewlett... | Primary        | 54    | Li-ion  | 43    | [A97A0BA0EE](https://linux-hardware.org/?probe=a97a0ba0ee) |
| Hewlett... | Primary        | 40    | Li-ion  | 43    | [3FA68165EA](https://linux-hardware.org/?probe=3fa68165ea) |
| LGC        | L11L6Y01       | 43.6  | Li-ion  | 43    | [C6AAA68E9C](https://linux-hardware.org/?probe=c6aaa68e9c) |
| Notebook   | BAT            | 60    | Li-ion  | 43    | [0EC0943D03](https://linux-hardware.org/?probe=0ec0943d03) |
| Panasonic  | AS10D51        | 47.5  | Li-ion  | 43    | [0659469DBE](https://linux-hardware.org/?probe=0659469dbe) |
| SANYO      | 42T4799        | 93.2  | Li-ion  | 43    | [41C5DD8A4A](https://linux-hardware.org/?probe=41c5dd8a4a) |
| SMP        | 00NY493        | 90.0  | Li-poly | 43    | [1F8ABAC9D7](https://linux-hardware.org/?probe=1f8abac9d7) |
| SMP        | 5B10W138       | 45.7  | Li-poly | 43    | [B48A6240BF](https://linux-hardware.org/?probe=b48a6240bf) |
| SMP        | DELL DM3WC64   | 60.0  | Li-poly | 43    | [64F0D004CE](https://linux-hardware.org/?probe=64f0d004ce) |
| SMP        | DELL VM73283   | 42.0  | Li-poly | 43    | [83DEC4F285](https://linux-hardware.org/?probe=83dec4f285) |
| Hewlett... | Primary        | 24    | Li-ion  | 42    | [FE042017E6](https://linux-hardware.org/?probe=fe042017e6) |
| Hewlett... | Primary        | 52    | Li-ion  | 42    | [792465EE85](https://linux-hardware.org/?probe=792465ee85) |
| Lenovo ... |                | 38    |         | 42    | [5210DE65B3](https://linux-hardware.org/?probe=5210de65b3) |
| Samsung... | DELL P8TC727   | 48.8  | Li-ion  | 42    | [282F0E1F65](https://linux-hardware.org/?probe=282f0e1f65) |
| SANYO      | AP13B3K        | 53.4  | Li-ion  | 42    | [924C20D0E4](https://linux-hardware.org/?probe=924c20d0e4) |
| SMP        | L17M3PG2       | 57.0  | Li-poly | 42    | [E1DA80EC6F](https://linux-hardware.org/?probe=e1da80ec6f) |
| Sunwoda    | 5B10W13935     | 46.0  | Li-poly | 42    | [BD330CE757](https://linux-hardware.org/?probe=bd330ce757) |
| ASUSTek    | T12--22        | 47.3  | Li-ion  | 41    | [E1425F037E](https://linux-hardware.org/?probe=e1425f037e) |
| ASUSTek    | X200-30        | 33.5  | Li-ion  | 41    | [EEA123637A](https://linux-hardware.org/?probe=eea123637a) |
| Notebook   | BAT            | 35    | Li-ion  | 41    | [9F2FDBFCE5](https://linux-hardware.org/?probe=9f2fdbfce5) |
| ASUSTek    | K56--30        | 38.5  | Li-ion  | 40    | [C6E3CAD977](https://linux-hardware.org/?probe=c6e3cad977) |
| SANYO      | 42T4763        | 71.3  | Li-ion  | 40    | [A83A1FFE1A](https://linux-hardware.org/?probe=a83a1ffe1a) |
| SANYO      | AS07A31        | 48.8  | Li-ion  | 40    | [13C6C15C9E](https://linux-hardware.org/?probe=13c6c15c9e) |
| SMP        | 00HW023        | 23.5  | Li-poly | 40    | [964C1A1526](https://linux-hardware.org/?probe=964c1a1526) |
| SMP        | L14M3P24       | 45.0  | Li-poly | 40    | [59476747E2](https://linux-hardware.org/?probe=59476747e2) |
|            |                | 38    | Li-ion  | 39    | [A85780AAAE](https://linux-hardware.org/?probe=a85780aaae) |
| Celxpert   | 5B10X026       | 45.0  | Li-poly | 39    | [39A12EAEF0](https://linux-hardware.org/?probe=39a12eaef0) |
| Notebook   | BAT            | 45    | Li-ion  | 39    | [8AC7D4890E](https://linux-hardware.org/?probe=8ac7d4890e) |
| SANYO      | 00HW022        | 23.5  | Li-poly | 39    | [6A6C0B0B39](https://linux-hardware.org/?probe=6a6c0b0b39) |
| SANYO      | AS07B31        | 63.9  | Li-ion  | 39    | [2DA9BDB8AF](https://linux-hardware.org/?probe=2da9bdb8af) |
| Simplo     | BASE-BAT       | 78.0  | Li-poly | 39    | [E1F5370987](https://linux-hardware.org/?probe=e1f5370987) |
| Sony       | PABAS024       | 57.5  | Li-ion  | 39    | [AA5079471B](https://linux-hardware.org/?probe=aa5079471b) |
| ASUSTek    | M50--24        | 51.3  | Li-ion  | 38    | [C9D463149F](https://linux-hardware.org/?probe=c9d463149f) |
| ASUSTek    | N550-40        | 60.5  | Li-ion  | 38    | [0D64CBAB8E](https://linux-hardware.org/?probe=0d64cbab8e) |
| ASUSTek    | X550E26        | 37.4  | Li-ion  | 38    | [C2D198AB83](https://linux-hardware.org/?probe=c2d198ab83) |
| LG         | LGC-LGC        | 80.0  | Li-ion  | 38    | [F4B91CFB92](https://linux-hardware.org/?probe=f4b91cfb92) |
| LGC        | 42T4911        | 47.5  | Li-ion  | 38    | [2D58D0613A](https://linux-hardware.org/?probe=2d58d0613a) |
| OEM        | AS10D31        | 48.4  | Li-ion  | 38    | [1046915C3B](https://linux-hardware.org/?probe=1046915c3b) |
| SANYO      | 42T4791        | 56.2  | Li-ion  | 38    | [15DD95FDFD](https://linux-hardware.org/?probe=15dd95fdfd) |
| SMP        | 45N1045        | 42.8  | Li-ion  | 38    | [AF3BEF5727](https://linux-hardware.org/?probe=af3bef5727) |
| SMP        | DELL GD1JP65   | 68.0  | Li-poly | 38    | [86796279CB](https://linux-hardware.org/?probe=86796279cb) |
| SMP        | L09M6Y02       | 46.4  | Li-ion  | 38    | [68B04EEF9D](https://linux-hardware.org/?probe=68b04eef9d) |
| ASUSTek    | X101CH         | 24.3  | Li-ion  | 37    | [486F5C28AD](https://linux-hardware.org/?probe=486f5c28ad) |
| LGC        | 01AV490        | 23.9  | Li-poly | 37    | [B552B967E4](https://linux-hardware.org/?probe=b552b967e4) |
| Samsung    |                | 45    | Li-ion  | 37    | [18B982D433](https://linux-hardware.org/?probe=18b982d433) |
| SMP        | DELL VM73297   | 42.0  | Li-poly | 37    | [F094B510C8](https://linux-hardware.org/?probe=f094b510c8) |
| Sony       | VGP-BPS35A     | 42.3  | Li-ion  | 37    | [365EF21D2A](https://linux-hardware.org/?probe=365ef21d2a) |
| Toshiba    | PABAS0241231   | 44.1  | Li-ion  | 37    | [5F8AB9C9CE](https://linux-hardware.org/?probe=5f8ab9c9ce) |
| GLK MRD    |  Li-ion        | 38.0  | Li-ion  | 36    | [A124FFB211](https://linux-hardware.org/?probe=a124ffb211) |
| LGC        | 02DL007        | 50.5  | Li-poly | 36    | [AF354B9537](https://linux-hardware.org/?probe=af354b9537) |
| LGC        | 45N1738        | 71.1  | Li-ion  | 36    | [08006B1C3A](https://linux-hardware.org/?probe=08006b1c3a) |
| LGC KT0... | AP18C8K        | 48.0  | Li-ion  | 36    | [23C2A93047](https://linux-hardware.org/?probe=23c2a93047) |
| SANYO      | AL10A31        | 24.4  | Li-ion  | 36    | [337BBF93B3](https://linux-hardware.org/?probe=337bbf93b3) |
| SMP        | 5B10W139       | 48.0  | Li-poly | 36    | [A122EE336D](https://linux-hardware.org/?probe=a122ee336d) |
| SMP        | L17M3PG1       | 52.5  | Li-poly | 36    | [F79196E39C](https://linux-hardware.org/?probe=f79196e39c) |
| Compal     | PA3817U-1BRS   | 47.5  | Li-ion  | 35    | [DE29066B72](https://linux-hardware.org/?probe=de29066b72) |
| Emdoor     |  Li-ion        | 36.5  | Li-ion  | 35    | [674A4FBEDE](https://linux-hardware.org/?probe=674a4fbede) |
| SANYO      | 45N1023        | 84.2  | Li-ion  | 35    | [21C4433BF2](https://linux-hardware.org/?probe=21c4433bf2) |
| ASUSTek    | PA3533U        | 56.2  | Li-ion  | 34    | [1A3F77BE23](https://linux-hardware.org/?probe=1a3f77be23) |
| Celxpert   | 5B10W138       | 45.7  | Li-poly | 34    | [BC65FFE3B4](https://linux-hardware.org/?probe=bc65ffe3b4) |
| Hewlett... | Primary        | 18    | Li-ion  | 34    | [6956607BFD](https://linux-hardware.org/?probe=6956607bfd) |
| SANYO      | AC14B13J       | 38.3  | Li-ion  | 34    | [58E5E2C95C](https://linux-hardware.org/?probe=58e5e2c95c) |
| SANYO      | AS09A31        | 47.5  | Li-ion  | 34    | [0F12BE73FA](https://linux-hardware.org/?probe=0f12be73fa) |
| DYNAPACK   | HB4593J6ECW    | 41.2  | Li-ion  | 33    | [98C6CBB320](https://linux-hardware.org/?probe=98c6cbb320) |
| Hewlett... | Primary        | 22    | Li-ion  | 33    | [8ABEE6201F](https://linux-hardware.org/?probe=8abee6201f) |
| Lenovo     | LCFC           | 23.8  |         | 33    | [0A5275C755](https://linux-hardware.org/?probe=0a5275c755) |
| LGC        | 01AV489        | 23.9  | Li-poly | 33    | [A06DA55EBE](https://linux-hardware.org/?probe=a06da55ebe) |
| LGC        | 45N1147        | 56.2  | Li-ion  | 33    | [3A79F95039](https://linux-hardware.org/?probe=3a79f95039) |
| LGC        | 5B10W138       | 45.0  | Li-poly | 33    | [B34CCF2C06](https://linux-hardware.org/?probe=b34ccf2c06) |
| LGC        | AC14A8L        | 52.5  | Li-ion  | 33    | [FE5DD7A63B](https://linux-hardware.org/?probe=fe5dd7a63b) |
| Notebook   | BAT            | 74    | Li-ion  | 33    | [69CE23B9F3](https://linux-hardware.org/?probe=69ce23b9f3) |
| PANASONIC  | AS16B5J        | 62.2  | Li-ion  | 33    | [E1F58E9713](https://linux-hardware.org/?probe=e1f58e9713) |
| SMP        | 01AV446        | 45.3  | Li-poly | 33    | [4CCCE94591](https://linux-hardware.org/?probe=4ccce94591) |
| SMP        | 01AV452        | 24.0  | Li-poly | 33    | [FDA7557AA0](https://linux-hardware.org/?probe=fda7557aa0) |
| Sunwoda    | 5B10X025       | 45.0  | Li-poly | 33    | [8AAFEBE07C](https://linux-hardware.org/?probe=8aafebe07c) |
| Celxpert   | 01AY969        | 80.4  | Li-poly | 32    | [E12FB3CD9D](https://linux-hardware.org/?probe=e12fb3cd9d) |
| Hewlett... | 5100           | 55.1  |         | 32    | [577F05089D](https://linux-hardware.org/?probe=577f05089d) |
| Hewlett... | Primary        | 5     | Li-ion  | 32    | [52CFF70BE5](https://linux-hardware.org/?probe=52cff70be5) |
| LGC        | 01AV494        | 57.0  | Li-poly | 32    | [48CFC7D185](https://linux-hardware.org/?probe=48cfc7d185) |
| SANYO      | 45N1777        | 71.3  | Li-ion  | 32    | [5819FC1B20](https://linux-hardware.org/?probe=5819fc1b20) |
| SIMPLO     | MWL32b         | 47.5  | Li-ion  | 32    | [43F645DE28](https://linux-hardware.org/?probe=43f645de28) |
| Toshiba    | PA3817U-1BRS   | 48.6  | Li-ion  | 32    | [51FB2A4A10](https://linux-hardware.org/?probe=51fb2a4a10) |
| ASUSTek    | PA3533U        | 56.2  | Li-ion  | 31    | [262BD2B6B5](https://linux-hardware.org/?probe=262bd2b6b5) |
| Hewlett... | 4400           | 47.5  |         | 31    | [B32286ECAD](https://linux-hardware.org/?probe=b32286ecad) |
| Hewlett... | Primary        | 23    | Li-ion  | 31    | [6248023E72](https://linux-hardware.org/?probe=6248023e72) |
| Lenovo     |                | 32    |         | 31    | [6D631D4A4D](https://linux-hardware.org/?probe=6d631d4a4d) |
| LGC        | 45N1735        | 47.5  | Li-ion  | 31    | [F246D643B4](https://linux-hardware.org/?probe=f246d643b4) |
| SMP        | 01AV413        | 45.3  | Li-poly | 31    | [D717AE7A04](https://linux-hardware.org/?probe=d717ae7a04) |
| SMP        | 5B10W13931     | 51.0  | Li-poly | 31    | [505E1DC8CC](https://linux-hardware.org/?probe=505e1dc8cc) |
| Compal     | PABAS024       | 40.0  | Li-ion  | 30    | [55A854B0C1](https://linux-hardware.org/?probe=55a854b0c1) |
| SMP        | 02DL008        | 50.5  | Li-poly | 30    | [76D3C2CFA2](https://linux-hardware.org/?probe=76d3c2cfa2) |
|            |                |       | Li-ion  | 29    | [28339307B2](https://linux-hardware.org/?probe=28339307b2) |
| LGC        | 01AV492        | 71.1  | Li-ion  | 29    | [661BF15DCC](https://linux-hardware.org/?probe=661bf15dcc) |
| SMP        | DELL MKD6223   | 62.2  | Li-ion  | 29    | [A7AFDD9D95](https://linux-hardware.org/?probe=a7afdd9d95) |
| SMP        | L19M3PF7       | 45.0  | Li-poly | 29    | [87E1EB605A](https://linux-hardware.org/?probe=87e1eb605a) |
| Toshiba    | PA3533U        | 71.3  | Li-ion  | 29    | [15ADF4F30A](https://linux-hardware.org/?probe=15adf4f30a) |
| Hewlett... | Primary        | 16    | Li-ion  | 28    | [570C07EE5C](https://linux-hardware.org/?probe=570c07ee5c) |

