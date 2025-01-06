DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by Linux users at https://linux-hardware.org.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 162480.

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
| Intel      | 11th Gen Core i5-1135G7          | 2.40 | 4867  | [673A82CC398B](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ITL05 82HS/673A82CC398B>) |
| Intel      | 12th Gen Core i7-12700H          |      | 2027  | [77DBFC2A6E52](<Notebook/Acer/Aspire/Aspire A515-57/77DBFC2A6E52>) |
| Intel      | Core i5-8250U                    | 1.60 | 1471  | [D815A0CA9F13](<Notebook/Dell/Latitude/Latitude 7390/D815A0CA9F13>) |
| Intel      | Core i7-8550U                    | 1.80 | 1313  | [3203336A2B46](<Notebook/Dell/Inspiron/Inspiron 5570/3203336A2B46>) |
| Intel      | Core i5-7200U                    | 2.50 | 1211  | [1EEF9A4214F5](<Convertible/Lenovo/Yoga/Yoga 720-12IKB 81B5/1EEF9A4214F5>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 1108  | [C7A89415BB4B](<Desktop/MSI/MS-7/MS-7C02/C7A89415BB4B>) |
| Intel      | 12th Gen Core i5-1235U           |      | 1067  | [21DA868DBAA1](<Notebook/Hewlett-Packard/ProBook/ProBook 440 14 inch G9 Notebook PC/21DA868DBAA1>) |
| Intel      | Core i5-10210U                   | 1.60 | 985   | [EE2448EC4BD6](<Convertible/Lenovo/IdeaPad/IdeaPad Flex-14IML 81XG/EE2448EC4BD6>) |
| Intel      | 11th Gen Core i7-11850H          | 2.50 | 983   | [A0E8DB681FDD](<Notebook/Acer/Nitro/Nitro AN517-54/A0E8DB681FDD>) |
| Intel      | Core i7-10510U                   | 1.80 | 943   | [F23C082FDA9E](<Convertible/Lenovo/IdeaPad/IdeaPad Flex-15IML 81XH/F23C082FDA9E>) |
| Intel      | Core i7-9750H                    | 2.60 | 911   | [59B69D658F39](<Notebook/Lenovo/IdeaPad/IdeaPad L340-15IRH Gaming 81LK/59B69D658F39>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 908   | [3035086EFC0B](<Notebook/Acer/Aspire/Aspire A315-42/3035086EFC0B>) |
| Intel      | 13th Gen Core i5-1340P           |      | 865   | [E28A1E841461](<Notebook/Framework/Laptop/Laptop/E28A1E841461>) |
| Intel      | Core i5-6200U                    | 2.30 | 846   | [2CD52138069F](<Notebook/ASUSTek Computer/X556/X556UR/2CD52138069F>) |
| Intel      | Core i7-8750H                    | 2.20 | 842   | [2E7CE511186E](<Notebook/ASUSTek Computer/Strix/Strix 15 GL503GE/2E7CE511186E>) |
| Intel      | Core i5-3210M                    | 2.50 | 835   | [752E7F63EA4A](<Mini Pc/Apple/Macmini6/Macmini6,1/752E7F63EA4A>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 827   | [2B2FB01EB8B4](<Desktop/Gigabyte Technology/X470/X470 AORUS ULTRA GAMING/2B2FB01EB8B4>) |
| Intel      | 13th Gen Core i7-13700K          |      | 826   | [54E9F4E8E3F9](<Notebook/Lenovo/Legion/Legion Pro 5 16IRX8 82WK/54E9F4E8E3F9>) |
| AMD        | Ryzen 5 5500U with Radeon Gra... |      | 825   | [1722BB93FF17](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y70038US/1722BB93FF17>) |
| Intel      | Core i7-7700HQ                   | 2.80 | 792   | [A39D5CE4C3D7](<Notebook/ASUSTek Computer/GL703/GL703VM/A39D5CE4C3D7>) |
| AMD        | Ryzen 7 5700U with Radeon Gra... |      | 775   | [7A2551764539](<Notebook/Acer/Aspire/Aspire A315-44P/7A2551764539>) |
| Intel      | 12th Gen Core i9-12900K          |      | 757   | [B57482B55E27](<Desktop/ASRock/Z790/Z790 PG SONIC/B57482B55E27>) |
| Intel      | Core i7-7500U                    | 2.70 | 729   | [D9CD642F66C1](<Convertible/ASUSTek Computer/Q524/Q524UQK/D9CD642F66C1>) |
| Intel      | Core i7-10750H                   | 2.60 | 714   | [E43BF5E3F0FB](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 17-cd1xxx/E43BF5E3F0FB>) |
| Intel      | Core i5-3470                     | 3.20 | 700   | [05DEE4E22315](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315>) |
| AMD        | Ryzen 7 5800H with Radeon Gra... |      | 698   | [47BA57D1C1B2](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop M1603QA_M1603QA/47BA57D1C1B2>) |
| Intel      | Core i5-8265U                    | 1.60 | 694   | [5D11FE94E7EF](<Notebook/ASUSTek Computer/VivoBook/VivoBook S13 X330FN_S330FN/5D11FE94E7EF>) |
| Intel      | Core i5-6300U                    | 2.40 | 685   | [E658B68361F2](<Notebook/Lenovo/ThinkPad/ThinkPad T560 20FJS44L0B/E658B68361F2>) |
| Intel      | Core i5-2520M                    | 2.50 | 664   | [F09CF33870BD](<Notebook/Hewlett-Packard/ProBook/ProBook 6560b/F09CF33870BD>) |
| Intel      | 11th Gen Core i7-11700           | 2.50 | 648   | [8318D3FD8343](<Desktop/Gigabyte Technology/B560M/B560M AORUS ELITE/8318D3FD8343>) |
| Intel      | Core i5-5200U                    | 2.20 | 638   | [9845589C2E2E](<Notebook/Toshiba/Satellite/Satellite C70-B/9845589C2E2E>) |
| Intel      | Core i7-8565U                    | 1.80 | 622   | [4EC1B097E2BE](<Notebook/Lenovo/IdeaPad/IdeaPad S540-14IWL 81ND/4EC1B097E2BE>) |
| Intel      | Pentium Silver N6000             | 1.10 | 608   | [9A4014CDA6EF](<Desktop/AZW/MINI/MINI S/9A4014CDA6EF>) |
| Intel      | Core i7-3770                     | 3.40 | 601   | [0EF93A75DC6F](<Desktop/Hewlett-Packard/h8/h8-1520t/0EF93A75DC6F>) |
| Intel      | Celeron N4020                    | 1.10 | 600   | [D5BB73BFCD47](<Notebook/VALE/Notebook/Notebook Slim S132/D5BB73BFCD47>) |
| Intel      | Core i5-3320M                    | 2.60 | 599   | [BED2AB98C19A](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349TFK/BED2AB98C19A>) |
| Intel      | Core i5-1035G1                   | 1.00 | 596   | [E4ACDDB3B2C7](<Notebook/Acer/Aspire/Aspire A317-52/E4ACDDB3B2C7>) |
| Intel      | Celeron N2840                    | 2.16 | 596   | [C42FEE2E30C9](<Notebook/Hewlett-Packard/Stream/Stream Notebook PC 13/C42FEE2E30C9>) |
| Intel      | Core i5-3230M                    | 2.60 | 590   | [37E21E49E6EF](<Notebook/Acer/Aspire/Aspire E1-571G/37E21E49E6EF>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 575   | [10FCED84DE65](<Desktop/MSI/MS-7/MS-7B86/10FCED84DE65>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 548   | [75C49E26FFD1](<Notebook/HUAWEI/KLVL-WXX/KLVL-WXX9/75C49E26FFD1>) |
| Intel      | Core i5-2400                     | 3.10 | 542   | [1F2A81C4AB8E](<Desktop/Dell/OptiPlex/OptiPlex 790/1F2A81C4AB8E>) |
| Intel      | Core i5-4210U                    | 1.70 | 542   | [46F718A80B6D](<Notebook/Dell/Inspiron/Inspiron 3542/46F718A80B6D>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 540   | [4EFAD502F05E](<Desktop/Hewlett-Packard/Compaq/Compaq 8000 Elite SFF PC/4EFAD502F05E>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 538   | [826DD5643F33](<Notebook/MSI/GS60/GS60 6QE/826DD5643F33>) |
| AMD        | Ryzen 5 5600G with Radeon Gra... |      | 537   | [B82F7FACAFF0](<Desktop/Gigabyte Technology/A520M/A520M DS3H/B82F7FACAFF0>) |
| Intel      | Atom x5-Z8350                    | 1.44 | 532   | [A586653DE545](<Notebook/Morshow/CB/CB01/A586653DE545>) |
| Intel      | Core i7-4790                     | 3.60 | 513   | [89A433DBAC77](<Desktop/Dell/OptiPlex/OptiPlex 9020/89A433DBAC77>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 510   | [5E9CA431A68F](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 3 24ARE05 F0EW004WUK/5E9CA431A68F>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 509   | [E0839CF115CB](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/E0839CF115CB>) |
| AMD        | Ryzen 5 4500U with Radeon Gra... |      | 500   | [34FBC94B9A9A](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ARE05 81X2/34FBC94B9A9A>) |
| Intel      | Core i3-2120                     | 3.30 | 496   | [4AFB3EC71AB3](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro SFF PC/4AFB3EC71AB3>) |
| Intel      | Celeron N3350                    | 1.10 | 493   | [56B59C250BC0](<Tablet/Jumper/EZpad/EZpad/56B59C250BC0>) |
| Intel      | Core i7-1065G7                   | 1.30 | 491   | [288CF2E38A6C](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X712JA_S712JA/288CF2E38A6C>) |
| Intel      | Celeron N3060                    | 1.60 | 490   | [0354CE3B7A28](<Notebook/Hewlett-Packard/Laptop/Laptop 14-bs0xx/0354CE3B7A28>) |
| Intel      | Core i7-8565U                    | 1.80 | 489   | [B3BF76AA6381](<Notebook/Lenovo/ThinkPad/ThinkPad L390 20NR001HPG/B3BF76AA6381>) |
| AMD        | FX-8350 Eight-Core               |      | 474   | [EDE97632E268](<Desktop/ASRock/960GC-GS/960GC-GS FX/EDE97632E268>) |
| Intel      | Core i5-2410M                    | 2.30 | 472   | [3490DCB42F4E](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK AH531/3490DCB42F4E>) |
| Intel      | Core i7-8650U                    | 1.90 | 470   | [980E2F97C968](<Tablet/Lenovo/ThinkPad/ThinkPad X1 Tablet Gen 3 20KKS0S901/980E2F97C968>) |
| AMD        | FX -6300 Six-Core                |      | 469   | [8F462E74EBFD](<Desktop/MSI/MS/MS-7693/8F462E74EBFD>) |
| Intel      | Core i5-2450M                    | 2.50 | 468   | [17F6CAD4252F](<Notebook/Samsung Electronics/300E4/300E4A-300E5A-300E7A-3430EA-3530EA/17F6CAD4252F>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 459   | [E252D6C18DE3](<Desktop/ASUSTek Computer/ROG/ROG STRIX B350-F GAMING/E252D6C18DE3>) |
| Intel      | Core i7-6500U                    | 2.50 | 458   | [BAEAB9ABEA9E](<Notebook/Acer/Aspire/Aspire V3-372/BAEAB9ABEA9E>) |
| Intel      | Core i5-6500                     | 3.20 | 458   | [1958717F42C8](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M710q 10MQS2M703/1958717F42C8>) |
| Intel      | Core i5-8350U                    | 1.70 | 455   | [D06ECE8FBB9A](<Notebook/Dell/Latitude/Latitude 7390 2-in-1/D06ECE8FBB9A>) |
| Intel      | Core i3-6006U                    | 2.00 | 431   | [0471C76D1EC5](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bs0xx/0471C76D1EC5>) |
| Intel      | Core i5-4200U                    | 1.60 | 430   | [C7107FE133FA](<Notebook/Lenovo/Yoga/Yoga 2 13 20344/C7107FE133FA>) |
| Intel      | Core i3-5005U                    | 2.00 | 429   | [FF50D96BC6B1](<Notebook/Acer/Aspire/Aspire E5-573G/FF50D96BC6B1>) |
| AMD        | Ryzen 5 5600X 6-Core             |      | 428   | [5342B9CA551D](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/5342B9CA551D>) |
| Intel      | Core i5-8265U                    | 1.60 | 428   | [E5006ED04FFC](<Notebook/Lenovo/ThinkPad/ThinkPad E490 20N8CTO1WW/E5006ED04FFC>) |
| Intel      | 13th Gen Core i7-1355U           |      | 423   | [03554E0996C1](<Notebook/Hewlett-Packard/250/250 15.6 inch G10/03554E0996C1>) |
| Intel      | Core i7-2600                     | 3.40 | 420   | [1EF1ECE712DD](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/1EF1ECE712DD>) |
| Intel      | Core i3-3110M                    | 2.40 | 410   | [73E673B38E27](<Notebook/ASUSTek Computer/X550/X550VL/73E673B38E27>) |
| Intel      | Core i5-5300U                    | 2.30 | 407   | [4C5860CF97FA](<Notebook/Dell/Latitude/Latitude E7450/4C5860CF97FA>) |
| AMD        | Ryzen 7 5700G with Radeon Gra... |      | 404   | [57D9DF839B4F](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS WIFI II/57D9DF839B4F>) |
| Intel      | Core i5-4460                     | 3.20 | 403   | [282BDAD48ABF](<Desktop/MSI/MS/MS-7924/282BDAD48ABF>) |
| AMD        | Ryzen 5 5600H with Radeon Gra... |      | 397   | [166BCE9277D1](<Notebook/Hewlett-Packard/Victus/Victus by Gaming Laptop 15-fb0xxx/166BCE9277D1>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 397   | [5DC4E38B3B74](<Desktop/Dell/OptiPlex/OptiPlex 780/5DC4E38B3B74>) |
| Intel      | Core i7-6700                     | 3.40 | 397   | [3C0F57476362](<Desktop/ASUSTek Computer/G20/G20CB/3C0F57476362>) |
| Intel      | Core i3-3220                     | 3.30 | 394   | [68E517D28B5B](<Desktop/Hewlett-Packard/p6/p6-2430ef/68E517D28B5B>) |
| Intel      | Core 2 Duo P7450                 | 2.13 | 392   | [A7036718579C](<Notebook/Apple/MacBook5/MacBook5,2/A7036718579C>) |
| Intel      | Core i3-2350M                    | 2.30 | 384   | [7B539C8539AA](<Notebook/ASUSTek Computer/K53/K53E/7B539C8539AA>) |
| AMD        | Ryzen 5 4600H with Radeon Gra... |      | 383   | [D6ADE9C4B78D](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A17 FA706IH_FA706IH/D6ADE9C4B78D>) |
| Intel      | Core i3-2100                     | 3.10 | 383   | [05F8E32151A5](<Desktop/Lenovo/ThinkCentre/ThinkCentre M81 5049D7G/05F8E32151A5>) |
| Intel      | Core i5-2430M                    | 2.40 | 382   | [307BFD98B544](<Notebook/Hewlett-Packard/Pavilion/Pavilion g7/307BFD98B544>) |
| Intel      | N100                             |      | 380   | [A87F09289266](<Desktop/PELADN/WI/WI-6/A87F09289266>) |
| Intel      | Core i5-4300U                    | 1.90 | 380   | [9A502B2F7D5F](<Tablet/Microsoft/Surface/Surface Pro 2/9A502B2F7D5F>) |
| Intel      | Core i3-2310M                    | 2.10 | 379   | [8536F70D7731](<Notebook/ASUSTek Computer/K53/K53E/8536F70D7731>) |
| Intel      | Core Ultra 7 155H                |      | 374   | [38BFA92704CB](<Convertible/Lenovo/Yoga/Yoga 7 2-in-1 14IML9 83DJ/38BFA92704CB>) |
| Intel      | Core i5-4570                     | 3.20 | 372   | [7609A4D128DC](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/7609A4D128DC>) |
| Intel      | Core i3 M 370                    | 2.40 | 364   | [B4E20CCBCA01](<Notebook/Lenovo/G460/G460 20041/B4E20CCBCA01>) |
| Intel      | Core i7-6600U                    | 2.60 | 360   | [C21CC8AC7701](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/C21CC8AC7701>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 357   | [CAD6E08D778D](<Desktop/Dell/OptiPlex/OptiPlex 745/CAD6E08D778D>) |
| Intel      | 12th Gen Core i5-12500           |      | 357   | [A2707C20967C](<Desktop/Graviton/D15/D15i/A2707C20967C>) |
| Intel      | Core i7-6700K                    | 4.00 | 357   | [C3CEAA365EF5](<Desktop/ASUSTek Computer/Z170/Z170 PRO GAMING/C3CEAA365EF5>) |
| Intel      | Core i7-4770                     | 3.40 | 356   | [021D0F97B209](<Desktop/Hewlett-Packard/700/700-019/021D0F97B209>) |
| Intel      | Core i5-8300H                    | 2.30 | 355   | [02407CDB6873](<Notebook/ECT/Others/Others/02407CDB6873>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 347   | [5FF2D0AC5D6D](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-E GAMING/5FF2D0AC5D6D>) |
| Intel      | Core i5-7300U                    | 2.60 | 343   | [71D2DD20CB26](<Tablet/Panasonic/CF-33/CF-33-1/71D2DD20CB26>) |
| Intel      | Core i7-8700                     | 3.20 | 343   | [89370B1DE85C](<Desktop/MSI/MS-7/MS-7B18/89370B1DE85C>) |
| AMD        | Ryzen 5 2500U with Radeon Veg... |      | 342   | [ACFE8ADD45EC](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15ARR 81D2/ACFE8ADD45EC>) |
| Intel      | Core i5-7400                     | 3.00 | 340   | [E4AB5103884A](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p0xx/E4AB5103884A>) |
| Intel      | Core i5-4590                     | 3.30 | 337   | [28AAC0B95507](<Desktop/Acer/Veriton/Veriton S6630G/28AAC0B95507>) |
| AMD        | Ryzen 7 3700U with Radeon Veg... |      | 335   | [8942D56644CD](<Notebook/Lenovo/IdeaPad/IdeaPad S340-15API 81NC/8942D56644CD>) |
| Intel      | Core i7-3630QM                   | 2.40 | 328   | [BBDD2F4A75B6](<Notebook/Hewlett-Packard/ENVY/ENVY dv6/BBDD2F4A75B6>) |
| Intel      | Celeron N4000                    | 1.10 | 326   | [6956EB99B888](<Notebook/Hewlett-Packard/Laptop/Laptop 14-ck0xxx/6956EB99B888>) |
| Intel      | Core i7-5500U                    | 2.40 | 322   | [0049D45200B3](<Notebook/Hewlett-Packard/ENVY/ENVY m7/0049D45200B3>) |
| Intel      | Core i7-4790K                    | 4.00 | 321   | [CAC0DD6997E8](<Desktop/Gigabyte Technology/Z97X-Gaming/Z97X-Gaming 5/CAC0DD6997E8>) |
| Intel      | Core i7-2670QM                   | 2.20 | 319   | [C133C1641ECF](<Notebook/Toshiba/Satellite/Satellite P755/C133C1641ECF>) |
| Intel      | Core i3 M 380                    | 2.53 | 318   | [A5968B277DCB](<Notebook/Lenovo/B560/B560 43308LG/A5968B277DCB>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 314   | [234F8AC2996B](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/234F8AC2996B>) |
| Intel      | Core i5-8400                     | 2.80 | 312   | [69BE606FC895](<Desktop/MSI/MS-7/MS-7B48/69BE606FC895>) |
| Intel      | 11th Gen Core i7-11390H          | 3.40 | 310   | [120F397045B8](<Notebook/Dell/Vostro/Vostro 13 5310/120F397045B8>) |
| AMD        | Ryzen 5 1600 Six-Core            |      | 307   | [D3DABCB5883B](<Desktop/Gigabyte Technology/AB350/AB350-Gaming-CF/D3DABCB5883B>) |
| Intel      | Core i7-8665U                    | 1.90 | 302   | [050B9B1D7FFD](<Convertible/Fujitsu/LIFEBOOK/LIFEBOOK T939/050B9B1D7FFD>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 301   | [EF4B140B96CA](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-K/EF4B140B96CA>) |
| Intel      | Core i7-7700                     | 3.60 | 300   | [292BEB0D4DA6](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/292BEB0D4DA6>) |
| Intel      | Atom N270                        | 1.60 | 299   | [BFDA6EC83E3A](<Notebook/Hewlett-Packard/Compaq/Compaq Mini 311-1100/BFDA6EC83E3A>) |
| Intel      | Core i3-3217U                    | 1.80 | 296   | [BD8CBFC97A7E](<Desktop/Lenovo/IdeaCentre/IdeaCentre Q190 10115/BD8CBFC97A7E>) |
| Intel      | Pentium B960                     | 2.20 | 295   | [C75A2ED8E5A3](<Notebook/Dell/System/System Inspiron N7110/C75A2ED8E5A3>) |
| Intel      | Core i3-10110U                   | 2.10 | 291   | [311332855F16](<Notebook/Dell/Latitude/Latitude 3410/311332855F16>) |
| Intel      | Core i5-10300H                   | 2.50 | 288   | [DF60D39CFF89](<Notebook/Acer/Nitro/Nitro AN517-52/DF60D39CFF89>) |
| Intel      | Core i3-6100                     | 3.70 | 288   | [92BBB4678066](<Desktop/Hewlett-Packard/550/550-166d/92BBB4678066>) |
| Intel      | Core i3-4005U                    | 1.70 | 287   | [B177451C5799](<Notebook/Dell/Inspiron/Inspiron 3542/B177451C5799>) |
| AMD        | Ryzen 7 PRO 4750U with Radeon... |      | 285   | [65C9066BF452](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UES5NA00/65C9066BF452>) |
| Intel      | Core i5-10400                    | 2.90 | 285   | [C701786EF3F7](<Desktop/Lenovo/IdeaCentre/IdeaCentre 5 14IMB05 90NA001RIX/C701786EF3F7>) |
| AMD        | E-450 APU with Radeon HD Grap... |      | 283   | [46D02272EFA3](<Notebook/ASUSTek Computer/1225/1225B/46D02272EFA3>) |
| Intel      | Atom N450                        | 1.66 | 281   | [BCCA88178B39](<Notebook/MSI/MS-N/MS-N014/BCCA88178B39>) |
| AMD        | Ryzen 9 5900HX with Radeon Gr... |      | 280   | [897AA67A4046](<Desktop/Micro Computer (HK) Tech Limited/UM/UM590/897AA67A4046>) |
| Intel      | Core i7-7700K                    | 4.20 | 277   | [5F604152EE58](<Desktop/MSI/MS-7/MS-7A68/5F604152EE58>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 274   | [CE509B54F33A](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/CE509B54F33A>) |
| Intel      | Core i7-4510U                    | 2.00 | 274   | [2CE3E3777DB8](<Notebook/Hewlett-Packard/ProBook/ProBook 440 G2/2CE3E3777DB8>) |
| Intel      | Core i3-4130                     | 3.40 | 273   | [65B45F557B0B](<Desktop/Gigabyte Technology/H97/H97M-HD3/65B45F557B0B>) |
| Intel      | Celeron N3050                    | 1.60 | 271   | [AD7E2D21FE1A](<Notebook/ASUSTek Computer/X540/X540SA/AD7E2D21FE1A>) |
| Intel      | Core i7-8700K                    | 3.70 | 270   | [0F9C63DCE4D3](<Desktop/ASUSTek Computer/PRIME/PRIME H310I-PLUS/0F9C63DCE4D3>) |
| Intel      | Core i7-3770K                    | 3.50 | 269   | [4B8CFE7139DA](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LE PLUS/4B8CFE7139DA>) |
| Intel      | Core i3-1005G1                   | 1.20 | 267   | [97FB2314C1D2](<Notebook/Dell/Vostro/Vostro 3491/97FB2314C1D2>) |
| Intel      | Core i3-7100U                    | 2.40 | 265   | [19288C8FC1B0](<Notebook/Lenovo/ThinkPad/ThinkPad E570 20H5S0CF00/19288C8FC1B0>) |
| Intel      | Core i5-5250U                    | 1.60 | 265   | [64B51A14987B](<Notebook/Apple/MacBookAir7/MacBookAir7,2/64B51A14987B>) |
| Intel      | Core i5-3570                     | 3.40 | 263   | [39846C6908FB](<Desktop/ASRock/Z68/Z68 Extreme4 Gen3/39846C6908FB>) |
| Intel      | Celeron J4125                    | 2.00 | 262   | [6C4A4010567B](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 CJ41GV2-410-O.C 12-02-2022 15:01:15/6C4A4010567B>) |
| Intel      | Core i5-3337U                    | 1.80 | 260   | [A91A0D968260](<Notebook/ASUSTek Computer/K56/K56CA/A91A0D968260>) |
| Intel      | Core i5-9300H                    | 2.40 | 259   | [5298B6A54341](<Notebook/Acer/Nitro/Nitro AN515-54/5298B6A54341>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 253   | [DDBE72A2FA8D](<Desktop/Hewlett-Packard/Desktop/Desktop M01-F0xxx/DDBE72A2FA8D>) |
| Intel      | Core i3-2330M                    | 2.20 | 249   | [499AEFE74238](<Notebook/Lenovo/G470/G470 20078/499AEFE74238>) |
| AMD        | Ryzen 9 5950X 16-Core            |      | 247   | [A68679D3B159](<Desktop/Gigabyte Technology/B550/B550 AORUS PRO AC/A68679D3B159>) |
| Intel      | Pentium Dual-Core T4500          | 2.30 | 247   | [57F9631BBE0B](<Notebook/Lenovo/G550/G550 20023/57F9631BBE0B>) |
| Intel      | Core i7-2630QM                   | 2.00 | 247   | [94EF4F8FC851](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/94EF4F8FC851>) |
| Intel      | Core i7-4700MQ                   | 2.40 | 247   | [0AFE5D8721FC](<Notebook/Notebook/P375/P375SM/0AFE5D8721FC>) |
| Intel      | Core i5-8365U                    | 1.60 | 242   | [4B4A75AA346F](<Notebook/Dell/Latitude/Latitude 5400/4B4A75AA346F>) |
| AMD        | Ryzen 5 3600X 6-Core             |      | 239   | [9E6AC03E4931](<Desktop/ASRock/X370M-HDV/X370M-HDV R4.0/9E6AC03E4931>) |
| Intel      | Core 2 Duo P8600                 | 2.40 | 239   | [D8EB6E6ABAE2](<Notebook/Dell/Inspiron/Inspiron 1545/D8EB6E6ABAE2>) |
| Intel      | Core i5-3570K                    | 3.40 | 238   | [FC045897C1E7](<Desktop/ASRock/Z77/Z77 Extreme4/FC045897C1E7>) |
| Intel      | Core i5-7300HQ                   | 2.50 | 235   | [C72D07F7CCC5](<Notebook/MSI/GL62M/GL62M 7RDX/C72D07F7CCC5>) |
| Intel      | Core i5-7500                     | 3.40 | 235   | [B112ED0889BD](<Desktop/ASUSTek Computer/H110/H110M-K/B112ED0889BD>) |
| Intel      | Core i5-2500K                    | 3.30 | 235   | [E44DB9193FF3](<Desktop/MSI/MS/MS-7673/E44DB9193FF3>) |
| AMD        | FX-8320 Eight-Core               |      | 234   | [B4C8B59A78DE](<Desktop/Gigabyte Technology/970/970A-DS3P/B4C8B59A78DE>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 234   | [55DE784FFBA2](<Desktop/ASRock/AB350M/AB350M Pro4/55DE784FFBA2>) |
| Intel      | Core i5 M 520                    | 2.40 | 234   | [E4369CCED2D6](<Notebook/Lenovo/ThinkPad/ThinkPad X201 3680X08/E4369CCED2D6>) |
| Intel      | Core i3-6100U                    | 2.30 | 234   | [19776503D2C1](<Notebook/Lenovo/ThinkPad/ThinkPad L460 20FVS2LC00/19776503D2C1>) |
| Intel      | Pentium Dual-Core E5300          | 2.60 | 233   | [073D29198D44](<Desktop/Gigabyte Technology/G31/G31M-ES2L/073D29198D44>) |
| Intel      | Core i5-2500                     | 3.30 | 232   | [8B8801C5D917](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M PRO/8B8801C5D917>) |
| Intel      | Core i5-4200M                    | 2.50 | 231   | [5FA7CA50988F](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AN0069US/5FA7CA50988F>) |
| Intel      | Core i7-4500U                    | 1.80 | 231   | [48FAC5ACFBCC](<Notebook/ASUSTek Computer/S551/S551LB/48FAC5ACFBCC>) |
| Intel      | Core i5-6400                     | 2.70 | 231   | [AFC51AE1EE8A](<All In One/MSI/MS-B/MS-B09012/AFC51AE1EE8A>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 226   | [7EFFF0688F78](<Desktop/Gigabyte Technology/B450M/B450M DS3H/7EFFF0688F78>) |
| Intel      | Core i7-3610QM                   | 2.30 | 226   | [142C0ABE36B4](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/142C0ABE36B4>) |
| Intel      | Pentium 2020M                    | 2.40 | 226   | [2846687B9E23](<Notebook/Lenovo/B590/B590 20206/2846687B9E23>) |
| Intel      | Core i7-6820HQ                   | 2.70 | 226   | [3B8F8D2C29D9](<Notebook/Lenovo/ThinkPad/ThinkPad P50 20EQS12Q06/3B8F8D2C29D9>) |
| AMD        | Ryzen 7 3800X 8-Core             |      | 225   | [FC88EA97858B](<Desktop/ASUSTek Computer/TUF/TUF B450-PLUS GAMING/FC88EA97858B>) |
| AMD        | Ryzen 5 2600X Six-Core           |      | 224   | [522A58633AB8](<Desktop/ASRock/B450M/B450M Pro4-F/522A58633AB8>) |
| AMD        | Ryzen 9 7950X 16-Core            |      | 224   | [D3FAB6D34468](<Desktop/ASRock/X670E/X670E Steel Legend/D3FAB6D34468>) |
| AMD        | Athlon II X2 250                 |      | 223   | [F39DBE376494](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LE/F39DBE376494>) |
| Intel      | Atom N455                        | 1.66 | 223   | [86DDC7AC9AB7](<Notebook/eMachines/eM/eM355/86DDC7AC9AB7>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 221   | [D25A5954B7D6](<Desktop/ASUSTek Computer/PRIME/PRIME B350-PLUS/D25A5954B7D6>) |
| Intel      | Core i3-8100                     | 3.60 | 221   | [2230D71B48FF](<Desktop/Lenovo/IdeaCentre/IdeaCentre 510A-15ICB 90HV001MUS/2230D71B48FF>) |
| Intel      | Core i5-3317U                    | 1.70 | 221   | [3F284D368C2E](<Notebook/Apple/MacBookAir5/MacBookAir5,1/3F284D368C2E>) |
| Intel      | Core i7-2600K                    | 3.40 | 220   | [28F5BB366953](<Desktop/Gigabyte Technology/Z68/Z68X-UD3-B3/28F5BB366953>) |
| Intel      | Core i7-4600U                    | 2.10 | 218   | [6D8BFD9B5EF2](<Notebook/Dell/Latitude/Latitude E7440/6D8BFD9B5EF2>) |
| Intel      | Core i5 M 460                    | 2.53 | 216   | [F4D1E695E2E8](<Notebook/Acer/Aspire/Aspire 5742/F4D1E695E2E8>) |
| Intel      | Core i3-3120M                    | 2.50 | 216   | [DE0FA167C05B](<Notebook/Lenovo/ThinkPad/ThinkPad L430 24662N5/DE0FA167C05B>) |
| AMD        | Ryzen 5 3550H with Radeon Veg... |      | 215   | [32B51ED331BD](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec0xxx/32B51ED331BD>) |
| Intel      | Core i5-2540M                    | 2.60 | 215   | [74551388C6E5](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8460p/74551388C6E5>) |
| Intel      | Core 2 Duo P8700                 | 2.53 | 214   | [BF097D2E0EB3](<Notebook/Apple/MacBookPro5/MacBookPro5,5/BF097D2E0EB3>) |
| Intel      | Atom Z3735F                      | 1.33 | 214   | [19BF4FD0AB27](<Notebook/ASUSTek Computer/T100/T100TAF/19BF4FD0AB27>) |
| Intel      | Celeron 2955U                    | 1.40 | 214   | [A0B2FB6F8587](<Notebook/Gateway/NE/NE572/A0B2FB6F8587>) |
| Intel      | Pentium N3540                    | 2.16 | 213   | [5B6A0065F740](<Notebook/Lenovo/Yoga/Yoga 300-11IBY 80M0/5B6A0065F740>) |
| AMD        | Ryzen 5 5625U with Radeon Gra... |      | 211   | [DABAF56E5585](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 15-eh2xxx/DABAF56E5585>) |
| Intel      | Core i3-7100                     | 3.90 | 211   | [1E80645DDF9B](<Desktop/PCWare/IPMH110/IPMH110G-DDR3/1E80645DDF9B>) |
| Intel      | Core i3-3240                     | 3.40 | 211   | [D25D96FF8FA5](<Desktop/Biostar/H61/H61MGC/D25D96FF8FA5>) |
| AMD        | FX -4300 Quad-Core               |      | 206   | [F8C4D55B70EA](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/F8C4D55B70EA>) |
| Intel      | Pentium Dual-Core T4300          | 2.10 | 205   | [3A2238B0E18B](<Notebook/Samsung Electronics/R530/R530-R730/3A2238B0E18B>) |
| Intel      | Pentium Dual-Core E5700          | 3.00 | 203   | [FB11F6ADEB7F](<Desktop/ICP-iEi/SA/SA16/FB11F6ADEB7F>) |
| Intel      | Pentium G4400                    | 3.30 | 202   | [E21E2252C54A](<Desktop/MSI/MS/MS-7996/E21E2252C54A>) |
| Intel      | Pentium Dual-Core T4400          | 2.20 | 201   | [20A7B1828118](<Notebook/Acer/Aspire/Aspire 5732Z/20A7B1828118>) |
| Intel      | Core i7-3520M                    | 2.90 | 201   | [0E84946ED7FC](<Notebook/Apple/MacBookPro9/MacBookPro9,2/0E84946ED7FC>) |
| Intel      | Core i7-5600U                    | 2.60 | 201   | [CCE186DED05F](<Notebook/Dell/Latitude/Latitude E5550/CCE186DED05F>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 200   | [B7784E7921C1](<Desktop/MSI/MS-7/MS-7D14/B7784E7921C1>) |
| Intel      | Core i3-8130U                    | 2.20 | 199   | [F6FC816725AE](<All In One/Hewlett-Packard/All-in-One/All-in-One 24-f0xx/F6FC816725AE>) |
| Intel      | Atom N2600                       | 1.60 | 199   | [3189AD0C2029](<Notebook/ASUSTek Computer/1015/1015CX/3189AD0C2029>) |
| AMD        | Ryzen 5 5600X 6-Core             |      | 197   | [593FF1160899](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/593FF1160899>) |
| Intel      | Core i5-3330                     | 3.00 | 197   | [691348F9B8F7](<Desktop/MSI/MS/MS-7758/691348F9B8F7>) |
| AMD        | Ryzen 7 6800H with Radeon Gra... |      | 196   | [6C33B6C5E4CA](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA507RE_FA577RE/6C33B6C5E4CA>) |
| Intel      | Core i7-8850H                    | 2.60 | 195   | [55C5D1D9BCA3](<Notebook/Lenovo/ThinkPad/ThinkPad P1 20MES1V800/55C5D1D9BCA3>) |
| Intel      | Core i5-9400F                    | 2.90 | 193   | [610FBBCCDC71](<Desktop/ASUSTek Computer/PRIME/PRIME H310-PLUS R2.0/610FBBCCDC71>) |
| Intel      | Core i3 M 330                    | 2.13 | 193   | [C31F487E8425](<Notebook/Dell/Inspiron/Inspiron 1564/C31F487E8425>) |
| AMD        | Ryzen 7 5825U with Radeon Gra... |      | 191   | [60364FEADB18](<Desktop/Shenzhen DOKE electronic/MP/MP100/60364FEADB18>) |
| Intel      | Celeron N2830                    | 2.16 | 191   | [882C9935ACA7](<Notebook/Dell/Inspiron/Inspiron 11 - 3147/882C9935ACA7>) |
| AMD        | Ryzen 7 7730U with Radeon Gra... |      | 190   | [BF78C6914A9F](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ABR8 82XX/BF78C6914A9F>) |
| Intel      | Core 2 Duo E7400                 | 2.80 | 189   | [370FD27E468C](<Desktop/ASUSTek Computer/P5KPL-AM/P5KPL-AM SE/370FD27E468C>) |
| Intel      | Core i3-4030U                    | 1.90 | 189   | [425DA2347FFC](<Notebook/Dell/Inspiron/Inspiron 11 - 3148/425DA2347FFC>) |
| Intel      | Core i5-9400                     | 2.90 | 188   | [3F7945C53716](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-E R2.0/3F7945C53716>) |
| Intel      | Core i5 M 560                    | 2.67 | 188   | [33953B7BF047](<Notebook/Hewlett-Packard/G/G42/33953B7BF047>) |
| Intel      | Core i3-10100                    | 3.60 | 187   | [F54ADC493621](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621>) |
| Intel      | Pentium N3700                    | 1.60 | 187   | [4210D97C8BC6](<Notebook/DNS/W510/W510LU/4210D97C8BC6>) |
| Intel      | Core i3-4160                     | 3.60 | 186   | [4222E42A139A](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G2 MT/4222E42A139A>) |
| Intel      | Core i7-10700                    | 2.90 | 185   | [BD8F80012FA4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B460-H GAMING/BD8F80012FA4>) |
| Intel      | Core i5-4440                     | 3.10 | 185   | [C9C29CB7A349](<Desktop/ASUSTek Computer/All/All Series/C9C29CB7A349>) |
| Intel      | Core i7-4710HQ                   | 2.50 | 185   | [E85588B5C0C2](<Notebook/ASUSTek Computer/G771/G771JM/E85588B5C0C2>) |
| AMD        | Ryzen 3 3200U with Radeon Veg... |      | 184   | [01DDE0B05DAB](<Notebook/Lenovo/IdeaPad/IdeaPad L340-15API 81LW/01DDE0B05DAB>) |
| Intel      | Core i7-7600U                    | 2.80 | 184   | [F075C17EEE65](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 5th 20HRCTO1WW/F075C17EEE65>) |
| Intel      | Core i7-3632QM                   | 2.20 | 184   | [3A482B4BD601](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349A17/3A482B4BD601>) |
| AMD        | Ryzen 7 5700X 8-Core             |      | 182   | [0CF125A71FC2](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-ZAKU/0CF125A71FC2>) |
| Intel      | Celeron N4100                    | 1.10 | 180   | [2CC76EFD06D0](<Notebook/Dell/Wyse/Wyse 5470/2CC76EFD06D0>) |
| Intel      | Core 2 Duo E6550                 | 2.33 | 180   | [9FE84A87E749](<Desktop/Gigabyte Technology/P35/P35-DS3R/9FE84A87E749>) |
| Intel      | Core i5 M 480                    | 2.67 | 180   | [D97ACAF2A028](<Notebook/Acer/Aspire/Aspire 5742/D97ACAF2A028>) |
| AMD        | E-350                            |      | 179   | [190269634D32](<Notebook/Acer/Aspire/Aspire 5253/190269634D32>) |
| Intel      | Pentium Silver N5000             | 1.10 | 179   | [7697A87466CB](<Notebook/ASUSTek Computer/VivoBook/VivoBook 14_ASUS Laptop X407MA_X407MA/7697A87466CB>) |
| Intel      | Celeron N3450                    | 1.10 | 179   | [772DD01C99D2](<Notebook/Hampoo/C3/C3W6_AP108_4GB/772DD01C99D2>) |
| Intel      | Core i3 M 350                    | 2.27 | 178   | [D43480FE5D66](<Notebook/ASUSTek Computer/K72/K72Jr/D43480FE5D66>) |
| AMD        | Phenom II X4 955                 |      | 176   | [CA1D9809D4A3](<Desktop/ASUSTek Computer/M4/M4A785T-M/CA1D9809D4A3>) |
| AMD        | Phenom II X4 965                 |      | 176   | [565BD96C0912](<Desktop/ASUSTek Computer/M4A79XTD/M4A79XTD EVO/565BD96C0912>) |
| Intel      | Core 2 T7200                     | 2.00 | 176   | [ABFBEC695A67](<Notebook/Dell/Inspiron/Inspiron MM061/ABFBEC695A67>) |
| Intel      | Core 2 Duo P8400                 | 2.26 | 174   | [7D3E8CB7704B](<Notebook/Packard Bell/EasyNote/EasyNote ML65/7D3E8CB7704B>) |
| Intel      | Pentium G3220                    | 3.00 | 174   | [A7A5A85D06C6](<Desktop/Gigabyte Technology/H81/H81M-S2PH/A7A5A85D06C6>) |
| Intel      | Pentium N4200                    | 1.10 | 174   | [FAB169D73643](<Notebook/Acer/Aspire/Aspire A114-31/FAB169D73643>) |
| AMD        | Ryzen 3 3250U with Radeon Gra... |      | 173   | [BC7A8F028184](<Notebook/Unchartevice/6540/6540/BC7A8F028184>) |
| Intel      | Core i5 M 430                    | 2.27 | 173   | [7ECF22E8607B](<Notebook/Hewlett-Packard/ProBook/ProBook 4720s/7ECF22E8607B>) |
| Intel      | Pentium N3710                    | 1.60 | 172   | [E84CE2292245](<Notebook/Dell/Inspiron/Inspiron 15-3552/E84CE2292245>) |
| Intel      | Core i7-10710U                   | 1.10 | 171   | [01AA0F125F1B](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/01AA0F125F1B>) |
| Intel      | Celeron N4120                    | 1.10 | 170   | [4DDCFDF3E5EE](<Convertible/Medion/E/E3224/4DDCFDF3E5EE>) |
| Intel      | Core i5-6600K                    | 3.50 | 170   | [9725E019A5E8](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 7/9725E019A5E8>) |
| AMD        | A8-7410 APU with AMD Radeon R... |      | 167   | [56E83070BA6B](<Desktop/Hewlett-Packard/260/260-a123nl/56E83070BA6B>) |
| Intel      | Core i5 750                      | 2.67 | 167   | [14462A4951D0](<Desktop/MSI/MS/MS-7583/14462A4951D0>) |
| Intel      | Pentium Dual-Core T4200          | 2.00 | 166   | [886BF877022D](<Notebook/Toshiba/Satellite/Satellite U400/886BF877022D>) |
| Intel      | Pentium M processor              | 1.20 | 165   | [FABC5AC48B1E](<Notebook/Fujitsu Siemens/LIFEBOOK/LIFEBOOK S7020/FABC5AC48B1E>) |
| Intel      | Pentium Dual-Core E5400          | 2.70 | 165   | [D818B3CDE8A3](<Desktop/Biostar/G41/G41D3/D818B3CDE8A3>) |
| AMD        | Ryzen 5 7520U with Radeon Gra... |      | 162   | [9DDB0CB01873](<Notebook/ASUSTek Computer/Vivobook/Vivobook Go E1504FA_E1504FA/9DDB0CB01873>) |
| Intel      | Core i7-4770K                    | 3.50 | 162   | [E9FC93F4366A](<Desktop/ASUSTek Computer/All/All Series/E9FC93F4366A>) |
| Intel      | Pentium P6100                    | 2.00 | 161   | [CEAA1DA52EDF](<Notebook/Acer/Aspire/Aspire 5742Z/CEAA1DA52EDF>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 3266 | 1300  | [E4ACDDB3B2C7](<Notebook/Acer/Aspire/Aspire A317-52/E4ACDDB3B2C7>) |
| SK hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2667 | 1294  | [AAFEFBFC85EE](<Notebook/Dell/Inspiron/Inspiron 5567/AAFEFBFC85EE>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 1190  | [673A82CC398B](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ITL05 82HS/673A82CC398B>) |
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 1172  | [307BFD98B544](<Notebook/Hewlett-Packard/Pavilion/Pavilion g7/307BFD98B544>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 1137  | [321789196A5C](<Notebook/Dell/Latitude/Latitude E7440/321789196A5C>) |
|            | 123456789012345678 SODIMM    | 4 GB     | DDR4 | 2400 | 1097  | [4DDCFDF3E5EE](<Convertible/Medion/E/E3224/4DDCFDF3E5EE>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 1047  | [BED2AB98C19A](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349TFK/BED2AB98C19A>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 869   | [4F3C4511C7E0](<Notebook/Lenovo/ThinkPad/ThinkPad T450s 20BWS5F400/4F3C4511C7E0>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 847   | [1EEF9A4214F5](<Convertible/Lenovo/Yoga/Yoga 720-12IKB 81B5/1EEF9A4214F5>) |
| Samsung    | M471A1K43EB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 826   | [750FE26CFBDC](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X1704VA_F1704VA/750FE26CFBDC>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 817   | [D97ACAF2A028](<Notebook/Acer/Aspire/Aspire 5742/D97ACAF2A028>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 803   | [3F26AB4D5CB4](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA401IV_GA401IV/3F26AB4D5CB4>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 777   | [19288C8FC1B0](<Notebook/Lenovo/ThinkPad/ThinkPad E570 20H5S0CF00/19288C8FC1B0>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 776   | [C133C1641ECF](<Notebook/Toshiba/Satellite/Satellite P755/C133C1641ECF>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 732   | [7382ABA92246](<Notebook/MSI/GF63/GF63 Thin 8SC/7382ABA92246>) |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 704   | [288CF2E38A6C](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X712JA_S712JA/288CF2E38A6C>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3600 | 678   | [0E0AE5C97293](<Desktop/ASUSTek Computer/PRIME/PRIME B560-PLUS/0E0AE5C97293>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 643   | [E88D352A1406](<Desktop/Intel/DP35DP/DP35DP AAD81073-206/E88D352A1406>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 632   | [2E7CE511186E](<Notebook/ASUSTek Computer/Strix/Strix 15 GL503GE/2E7CE511186E>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 629   | [17F6CAD4252F](<Notebook/Samsung Electronics/300E4/300E4A-300E5A-300E7A-3430EA-3530EA/17F6CAD4252F>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 626   | [46F718A80B6D](<Notebook/Dell/Inspiron/Inspiron 3542/46F718A80B6D>) |
|            | Module DIMM SDRAM            | 2048 MB  |      |      | 624   | [5D3AFC349EB5](<Desktop/MSI/MS/MS-7267/5D3AFC349EB5>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 595   | [F09CF33870BD](<Notebook/Hewlett-Packard/ProBook/ProBook 6560b/F09CF33870BD>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 589   | [CA16AD8F340D](<Notebook/Hewlett-Packard/Laptop/Laptop 14-cm0xxx/CA16AD8F340D>) |
|            | Module DIMM                  | 2048 MB  |      | 800  | 581   | [E1A6C7BBBCB7](<Desktop/ASUSTek Computer/M2/M2N-E/E1A6C7BBBCB7>) |
|            | Module DIMM                  | 4096 MB  |      | 1333 | 581   | [403486D514D6](<Desktop/Gigabyte Technology/GA-780/GA-780T-D3L/403486D514D6>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 575   | [8C592F7882A5](<Desktop/Dell/OptiPlex/OptiPlex 9020M/8C592F7882A5>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2 GB     | DDR3 | 4199 | 569   | [6274932030CE](<Notebook/Toshiba/Satellite/Satellite L755/6274932030CE>) |
| Samsung    | M471A1G44BB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 566   | [E26E6F99E56D](<Notebook/Lenovo/ThinkPad/ThinkPad E15 Gen 4 21E7S4BD00/E26E6F99E56D>) |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8 GB     | DDR4 | 3200 | 558   | [75C49E26FFD1](<Notebook/HUAWEI/KLVL-WXX/KLVL-WXX9/75C49E26FFD1>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 4 GB     | DDR3 | 2400 | 551   | [DFDA2CCFCE2C](<Notebook/Toshiba/Satellite/Satellite C655D/DFDA2CCFCE2C>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1600 | 543   | [32AA4D8C9F5E](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6/32AA4D8C9F5E>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4096 MB  | DDR4 | 2667 | 542   | [0471C76D1EC5](<Notebook/Hewlett-Packard/Laptop/Laptop 15-bs0xx/0471C76D1EC5>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 529   | [0A26B6F080AE](<Notebook/Lenovo/IdeaPad/IdeaPad 710S Plus-13IKB 80W3/0A26B6F080AE>) |
|            | Module DIMM                  | 2048 MB  |      | 1333 | 521   | [B9F30C2A959A](<Desktop/Gigabyte Technology/H67/H67A-UD3H-B3/B9F30C2A959A>) |
|            | Module DIMM SDRAM            | 1024 MB  |      |      | 498   | [DC0D37153663](<Desktop/ASRock/Wolfdale1333/Wolfdale1333-D667/DC0D37153663>) |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8 GB     | DDR4 | 3200 | 480   | [A8C54F684530](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus M16 GU603HM_GU603HM/A8C54F684530>) |
| SK hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 461   | [2E7CE511186E](<Notebook/ASUSTek Computer/Strix/Strix 15 GL503GE/2E7CE511186E>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 457   | [F9466773AA13](<Notebook/ASUSTek Computer/1015/1015PN/F9466773AA13>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 450   | [0A56E7AAF61F](<Notebook/Acer/TMP645/TMP645-M/0A56E7AAF61F>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 447   | [5383C735EF5E](<Notebook/Acer/Aspire/Aspire A715-51G/5383C735EF5E>) |
| SK hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 436   | [4EC1B097E2BE](<Notebook/Lenovo/IdeaPad/IdeaPad S540-14IWL 81ND/4EC1B097E2BE>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3600 | 418   | [A20D3408DAA4](<Desktop/ASRock/B450M/B450M Pro4/A20D3408DAA4>) |
| Micron     | 8ATF1G64HZ-3G2J1 SODIMM      | 8 GB     | DDR4 | 3200 | 418   | [A8C54F684530](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus M16 GU603HM_GU603HM/A8C54F684530>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 414   | [145540D21FF5](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 15-eg2xxx/145540D21FF5>) |
|            | 123456789012345678 DIMM L... | 2048 MB  |      | 2400 | 411   | [6C4A4010567B](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 CJ41GV2-410-O.C 12-02-2022 15:01:15/6C4A4010567B>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 398   | [7997391A348D](<Desktop/Dell/Studio/Studio XPS 8100/7997391A348D>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 1800 | 397   | [05DEE4E22315](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V LX/05DEE4E22315>) |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4 GB     | DDR4 | 3200 | 397   | [8931357C872D](<Convertible/Lenovo/IdeaPad/IdeaPad C340-15IIL 81XJ/8931357C872D>) |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 390   | [FD48C5C782DD](<Notebook/Dell/Precision/Precision 7750/FD48C5C782DD>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 | 1600 | 388   | [691348F9B8F7](<Desktop/MSI/MS/MS-7758/691348F9B8F7>) |
| SK hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 385   | [8721BA59F35E](<Notebook/Dell/Latitude/Latitude E6220/8721BA59F35E>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 800  | 384   | [7F6B6AF8ED05](<Desktop/Wortmann AG/P5/P5K-MVM/7F6B6AF8ED05>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 384   | [5E82909F272A](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile V6535/5E82909F272A>) |
| SK hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2667 | 384   | [965492A8792A](<Desktop/Lenovo/ThinkCentre/ThinkCentre M900 10FLS2XC00/965492A8792A>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 382   | [E76AFAC83B95](<Notebook/Dell/Latitude/Latitude E6430/E76AFAC83B95>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 382   | [D9929FA1336B](<Desktop/ASUSTek Computer/M4/M4A785-M/D9929FA1336B>) |
| Micron     | 8ATF1G64HZ-3G2R1 SODIMM      | 8 GB     | DDR4 | 3200 | 376   | [166BCE9277D1](<Notebook/Hewlett-Packard/Victus/Victus by Gaming Laptop 15-fb0xxx/166BCE9277D1>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4 GB     | DDR3 | 1334 | 373   | [32F108EFA19F](<Notebook/ASUSTek Computer/N53/N53SV/32F108EFA19F>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 8400 | 370   | [D815A0CA9F13](<Notebook/Dell/Latitude/Latitude 7390/D815A0CA9F13>) |
| Micron     | 4ATF1G64HZ-3G2E1 Row Of C... | 8 GB     | DDR4 | 3200 | 365   | [EB36684248CC](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ALC05 82HU/EB36684248CC>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 361   | [BEFD57C0148A](<Desktop/ASRock/G31/G31M-GS/BEFD57C0148A>) |
| Micron     | 8ATF1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 348   | [10E9FB511960](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20RUTOEIIT/10E9FB511960>) |
| Micron     | 4ATF1G64HZ-3G2F1 SODIMM      | 8 GB     | DDR4 | 3200 | 347   | [928526AD5068](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X1704ZA_F1704ZA/928526AD5068>) |
| Samsung    | M471B5673FH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 345   | [ED6AC14F653C](<Notebook/Acer/Others/Others/ED6AC14F653C>) |
| Samsung    | M471A5244CB0-CWE Row Of C... | 4 GB     | DDR4 | 3200 | 342   | [59C105260EC3](<Notebook/Lenovo/IdeaPad/IdeaPad 5 15ALC05 82LN/59C105260EC3>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3600 | 327   | [3CDF356CA9A8](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-F GAMING/3CDF356CA9A8>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 4000 | 326   | [D22F4BB88C59](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/D22F4BB88C59>) |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16 GB    | DDR4 | 2667 | 326   | [707A3D8F2480](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20K5S1A524/707A3D8F2480>) |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 324   | [957C4D53C299](<Notebook/Gigabyte Technology/AERO/AERO 17 KC/957C4D53C299>) |
|            | Module SODIMM                | 2048 MB  | DDR2 |      | 318   | [E20753192FA0](<Notebook/Lenovo/ThinkPad/ThinkPad T60 1953D9U/E20753192FA0>) |
| Micron     | 4ATF51264HZ-2G3B1 SODIMM     | 4 GB     | DDR4 | 3200 | 316   | [DB4FB3E0DA86](<Notebook/Acer/Aspire/Aspire ES1-572/DB4FB3E0DA86>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 315   | [00EC1CA477D6](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8560w/00EC1CA477D6>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3733 | 311   | [10FCED84DE65](<Desktop/MSI/MS-7/MS-7B86/10FCED84DE65>) |
| Kingston   | KHX2666C16/8G DIMM           | 8 GB     | DDR4 | 3466 | 308   | [B6E6160B9705](<Desktop/Gigabyte Technology/B560M/B560M DS3H/B6E6160B9705>) |
| SK hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2667 | 308   | [8D8D80F3ABC2](<Notebook/Dell/Inspiron/Inspiron 5567/8D8D80F3ABC2>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 308   | [91E400AA092D](<Notebook/Lenovo/ThinkPad/ThinkPad L13 Gen 1 20R4S0G500/91E400AA092D>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8192 MB  | DDR3 | 1600 | 307   | [D8291EF1E6D2](<Notebook/Lenovo/ThinkPad/ThinkPad T420 418062U/D8291EF1E6D2>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 306   | [0B137467B2D8](<Notebook/Lenovo/Legion/Legion S7 15ACH6 82K8/0B137467B2D8>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1333 | 304   | [D57F558F7A82](<Desktop/ASRock/B85M/B85M Pro4/D57F558F7A82>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 304   | [94DC153C38C2](<Notebook/Toshiba/Satellite/Satellite C650/94DC153C38C2>) |
|            | Module DIMM                  | 1024 MB  |      | 800  | 299   | [61AADFA12FB2](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/61AADFA12FB2>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 667  | 299   | [9DE96B29B899](<Desktop/Gateway/945/945GCT-M3/9DE96B29B899>) |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     | DDR3 | 1334 | 295   | [D97ACAF2A028](<Notebook/Acer/Aspire/Aspire 5742/D97ACAF2A028>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 293   | [E31357392155](<Desktop/Intel/H/H81/E31357392155>) |
| SK hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 288   | [C133C1641ECF](<Notebook/Toshiba/Satellite/Satellite P755/C133C1641ECF>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 283   | [B37417979A6E](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/B37417979A6E>) |
| Samsung    | M471A2K43DB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 282   | [8931357C872D](<Convertible/Lenovo/IdeaPad/IdeaPad C340-15IIL 81XJ/8931357C872D>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 667  | 281   | [AE084EA145E6](<Desktop/Fujitsu Siemens/ESPRIMO/ESPRIMO EDITION P2511/AE084EA145E6>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 278   | [0049D45200B3](<Notebook/Hewlett-Packard/ENVY/ENVY m7/0049D45200B3>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 270   | [4222E42A139A](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G2 MT/4222E42A139A>) |
| Samsung    | M425R1GB4BB0-CQKOL SODIMM    | 8 GB     | DDR5 | 4800 | 269   | [F1BA918E8023](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A16 FA617NS_FA617NS/F1BA918E8023>) |
| SK hynix   | H9CCNNNCLGALAR-NVD Row Of... | 8 GB     |      | 2133 | 269   | [DE9C1EA4683F](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ae0xx/DE9C1EA4683F>) |
| SK hynix   | Module SODIMM                | 1 GB     | DDR2 | 800  | 267   | [666DC9525D7D](<Notebook/Apple/MacBook5/MacBook5,2/666DC9525D7D>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 266   | [E119ABC80EC8](<Notebook/Dell/Latitude/Latitude 7490/E119ABC80EC8>) |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8 GB     | DDR4 | 3200 | 265   | [E703390C6D6E](<Desktop/ASRock/A320M/A320M Pro4 R2.0/E703390C6D6E>) |
| SK hynix   | HMT41GS6AFR8A-PB SODIMM      | 8 GB     | DDR3 | 2667 | 265   | [3490DCB42F4E](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK AH531/3490DCB42F4E>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 265   | [AB8973E3B2CB](<Desktop/ASUSTek Computer/M4/M4A78LT-M-LE/AB8973E3B2CB>) |
| SK hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1800 | 263   | [021D0F97B209](<Desktop/Hewlett-Packard/700/700-019/021D0F97B209>) |
|            | Module SODIMM                | 4 GB     | DDR3 |      | 263   | [1612583DFCAB](<Notebook/Sony/VPCSB3/VPCSB3V9R/1612583DFCAB>) |
| Samsung    | M471A2G44AM0-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 261   | [18826ED2270B](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 2i 20W000NXIX/18826ED2270B>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 259   | [7757E259E194](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20YE000GCD/7757E259E194>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 2133 | 258   | [C5A2AEE85970](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX R2.0/C5A2AEE85970>) |
| Kingston   | KHX2400C15/8G DIMM           | 8 GB     | DDR4 | 3400 | 258   | [B439AF57EE23](<Desktop/MSI/MS-7/MS-7B45/B439AF57EE23>) |
|            | Module SODIMM                | 1024 MB  | DDR2 |      | 258   | [E20753192FA0](<Notebook/Lenovo/ThinkPad/ThinkPad T60 1953D9U/E20753192FA0>) |
| SK hynix   | HMA82GS6JJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 256   | [CD7C542F15EB](<Desktop/Dell/OptiPlex/OptiPlex 3080/CD7C542F15EB>) |
| Samsung    | M471B5273CH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 255   | [03DFC14FA38D](<Notebook/Hewlett-Packard/ProBook/ProBook 4330s/03DFC14FA38D>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 253   | [6D8BFD9B5EF2](<Notebook/Dell/Latitude/Latitude E7440/6D8BFD9B5EF2>) |
| SK hynix   | HYMP125S64CP8-S6 SODIMM      | 2048 MB  | DDR2 | 975  | 251   | [91D4FA24ADBE](<Notebook/Dell/Latitude/Latitude E6500/91D4FA24ADBE>) |
| SK hynix   | Module SODIMM                | 4 GB     | DDR3 | 1600 | 251   | [8862854ABDE3](<Notebook/Apple/MacBookAir6/MacBookAir6,2/8862854ABDE3>) |
|            | Module SODIMM                | 1024 MB  | DDR2 | 667  | 250   | [5E82909F272A](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile V6535/5E82909F272A>) |
| Corsair    | CMK32GX4M2E3200C16 DIMM      | 16 GB    | DDR4 | 3534 | 245   | [5FF2D0AC5D6D](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-E GAMING/5FF2D0AC5D6D>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 244   | [9EF31BA9AAA0](<Notebook/Hewlett-Packard/Notebook/Notebook/9EF31BA9AAA0>) |
|            | Module SODIMM                | 4096 MB  | DDR3 |      | 242   | [4513137DD41B](<Notebook/Sony/SVE1511/SVE1511C1RB/4513137DD41B>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 242   | [E5006ED04FFC](<Notebook/Lenovo/ThinkPad/ThinkPad E490 20N8CTO1WW/E5006ED04FFC>) |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3800 | 240   | [9565FA8F0E15](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/9565FA8F0E15>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 236   | [479BFC1603C2](<Notebook/ASUSTek Computer/X555/X555YI/479BFC1603C2>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 233   | [EAF4136FB502](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252UG/EAF4136FB502>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 230   | [6B5EB9D79098](<Notebook/Sony/VGN-CR220/VGN-CR220E/6B5EB9D79098>) |
| SK hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 3200 | 228   | [E27929CBCC01](<Notebook/ASUSTek Computer/S301/S301LA/E27929CBCC01>) |
| Kingston   | KF3200C16D4/8GX DIMM         | 8 GB     | DDR4 | 3600 | 228   | [892ED35F8D6B](<Desktop/MSI/MS-7/MS-7C95/892ED35F8D6B>) |
| Samsung    | M471A2G43AB2-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 228   | [56CBC8038B88](<Notebook/Hewlett-Packard/Laptop/Laptop 17-cn0xxx/56CBC8038B88>) |
| Elpida     | EBJ40UG8BBU0-GN-F SODIMM     | 4 GB     | DDR3 | 1600 | 222   | [FC163D18511C](<Notebook/ASUSTek Computer/X502/X502CA/FC163D18511C>) |
| SK hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 221   | [F6F92F033FA3](<Notebook/Lenovo/ThinkPad/ThinkPad P52s 20LCS08300/F6F92F033FA3>) |
| Nanya      | NT4GC64B8HB0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 220   | [5527891B54F6](<Notebook/Acer/Aspire/Aspire 5742G/5527891B54F6>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 220   | [DE0871A8855E](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/DE0871A8855E>) |
|            | Module DIMM                  | 2048 MB  |      | 667  | 219   | [928DE04C6943](<Desktop/Gigabyte Technology/945/945GCM-S2L/928DE04C6943>) |
| Samsung    | M471A5244BB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 219   | [16EE3F3B4751](<Mini Pc/Hewlett-Packard/t530/t530 Thin Client/16EE3F3B4751>) |
| Samsung    | Module SODIMM                | 8 GB     | DDR4 | 2133 | 219   | [960BBF1370AB](<Notebook/Hewlett-Packard/EliteBook/EliteBook 850 G4/960BBF1370AB>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4096 MB  | DDR3 | 1600 | 217   | [F51FFCD16AF1](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/F51FFCD16AF1>) |
| SK hynix   | HMA851S6DJR6N-XN SODIMM      | 4 GB     | DDR4 | 3200 | 217   | [BC193EBC5536](<Notebook/Acer/Aspire/Aspire A315-58/BC193EBC5536>) |
| SK hynix   | HMT325S6BFR8C-H9 SODIMM      | 2048 MB  | DDR3 | 1600 | 217   | [0637990DAC59](<Notebook/Lenovo/ThinkPad/ThinkPad Edge 031925U/0637990DAC59>) |
| Kingston   | 99U5584-005.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 216   | [649FA9690F10](<Desktop/ASUSTek Computer/All/All Series/649FA9690F10>) |
|            | Module DIMM                  | 4096 MB  |      | 1600 | 215   | [E16F0428121F](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/E16F0428121F>) |
| Samsung    | M471A5244CB0-CTD Row Of C... | 4 GB     | DDR4 | 2667 | 213   | [010DA2EEF7B0](<Notebook/Lenovo/V15-IIL/V15-IIL 82C5/010DA2EEF7B0>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4096 MB  | DDR3 | 2133 | 210   | [BAD5FEF5927B](<Desktop/Lenovo/1730/1730-A1G/BAD5FEF5927B>) |
| SK hynix   | HMAA2GS6CJR8N-XN SODIMM      | 16 GB    | DDR4 | 3200 | 210   | [EBD9F4A07E2A](<Notebook/Acer/Aspire/Aspire A515-57/EBD9F4A07E2A>) |
| Micron     | 16JSF51264HZ-1G4D1 SODIMM    | 4 GB     | DDR3 | 1334 | 207   | [94EF4F8FC851](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/94EF4F8FC851>) |
|            | Module DIMM                  | 1024 MB  |      | 667  | 205   | [928DE04C6943](<Desktop/Gigabyte Technology/945/945GCM-S2L/928DE04C6943>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 205   | [D02AD4C72CA7](<Notebook/Dell/Inspiron/Inspiron N5050/D02AD4C72CA7>) |
| Kingston   | KHX3200C16D4/16GX DIMM       | 16 GB    | DDR4 | 3600 | 203   | [BD8F80012FA4](<Desktop/ASUSTek Computer/ROG/ROG STRIX B460-H GAMING/BD8F80012FA4>) |
| Nanya      | NT4GC64B8HG0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 203   | [95767550A471](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4180F64/95767550A471>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 203   | [CEEF3F35B577](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HJS0AQ2S/CEEF3F35B577>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 202   | [0911ED8F0EC5](<Notebook/ASUSTek Computer/G53/G53SW/0911ED8F0EC5>) |
| Samsung    | M471B5674QH0-YK0 SODIMM      | 2 GB     | DDR3 | 3200 | 202   | [549BBDF2E4E4](<Notebook/Dell/Inspiron/Inspiron 5555/549BBDF2E4E4>) |
| Micron     | MT52L1G32D4PG-093 Row Of ... | 8 GB     |      | 2133 | 200   | [681360B86112](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX334FLC_UX334FL/681360B86112>) |
| Kingston   | KF3200C16D4/16GX DIMM        | 16 GB    | DDR4 | 3200 | 199   | [B7784E7921C1](<Desktop/MSI/MS-7/MS-7D14/B7784E7921C1>) |
|            | Module DIMM                  | 2048 MB  | DDR3 | 1333 | 199   | [F6BC11D86C9B](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LE/F6BC11D86C9B>) |
| Samsung    | M471B5773DH0-CK0 SODIMM      | 2 GB     | DDR3 | 1600 | 196   | [8B1670CC4954](<Notebook/Lenovo/ThinkPad/ThinkPad T520 4242A25/8B1670CC4954>) |
| Ramaxel    | RMT3160ED58E9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 194   | [EAF4136FB502](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252UG/EAF4136FB502>) |
| Samsung    | UBE3D4AA-MGCR Row Of Chip... | 2 GB     |      | 4267 | 193   | [714803C5D648](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX325EA_UX325EA/714803C5D648>) |
|            | Module DIMM SDRAM            | 512 MB   |      |      | 189   | [2E43AB03C3FC](<Desktop/Others/Alviso/Alviso/2E43AB03C3FC>) |
| 48spaces   | 0123456789012345678901234... | 2 GB     | DDR2 | 667  | 188   | [B5A919D45ED7](<Notebook/Samsung Electronics/N150/N150-N210-N220/B5A919D45ED7>) |
| A-DATA     | DDR4 3200 DIMM               | 8 GB     | DDR4 | 3600 | 188   | [9C4BEE3F5B7B](<Desktop/CSL-Computer/T/T8186/9C4BEE3F5B7B>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 187   | [EC4C5F544880](<Notebook/ASUSTek Computer/X550/X550CC/EC4C5F544880>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 |      | 187   | [2CAE737842A0](<Desktop/Intel/B/B75/2CAE737842A0>) |
| Kingston   | KHX1600C10D3/4G DIMM         | 4 GB     | DDR3 | 1600 | 187   | [688F167541E1](<Desktop/ASRock/Z97X/Z97X Killer/688F167541E1>) |
|            | Module SODIMM                | 8 GB     | DDR3 | 1600 | 187   | [C1056B2F0556](<Desktop/Hewlett-Packard/ProOne/ProOne 600 G1 AiO/C1056B2F0556>) |
| Samsung    | M471A4G43AB1-CWE SODIMM      | 32 GB    | DDR4 | 3200 | 187   | [DA6C3047EF76](<Desktop/AZW/U/U59/DA6C3047EF76>) |
| G.Skill    | F4-3200C16-8GIS DIMM         | 8 GB     | DDR4 | 3200 | 186   | [234F8AC2996B](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/234F8AC2996B>) |
| Micron     | 4ATF51264HZ-3G2J1 Row Of ... | 4 GB     | DDR4 | 3200 | 186   | [24F03572999C](<Notebook/Lenovo/IdeaPad/IdeaPad 3 14ITL6 82H7/24F03572999C>) |
|            | Module SODIMM                | 1 GB     | DDR2 | 667  | 186   | [C6C289849FAF](<Notebook/Acer/TravelMate/TravelMate 6292/C6C289849FAF>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1800 | 184   | [D696AF592395](<Desktop/ASUSTek Computer/All/All Series/D696AF592395>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 184   | [E6B6E1B9CF85](<Notebook/Toshiba/Satellite/Satellite C50D-A-12M/E6B6E1B9CF85>) |
|            | Module DIMM                  | 2048 MB  |      | 400  | 183   | [30269FB3C8E0](<Desktop/Gigabyte Technology/G41/G41M-Combo/30269FB3C8E0>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8 GB     | DDR3 | 1800 | 182   | [AF30A1F68DA8](<Desktop/Gigabyte Technology/B85/B85M-D3H/AF30A1F68DA8>) |
| Samsung    | M4 70T5663QZ3-CF7 SODIMM     | 2 GB     | DDR2 | 2048 | 182   | [7E0D24A68E5C](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8730w/7E0D24A68E5C>) |
| Team       | TEAMGROUP-UD4-3200 DIMM      | 8 GB     | DDR4 | 3800 | 182   | [695E352A1B48](<Desktop/ASRock/B550/B550M-C/695E352A1B48>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 1600 | 181   | [7DAC1838861C](<Notebook/Dell/Latitude/Latitude E5550/7DAC1838861C>) |
| Ramaxel    | RMSA3270ME86H9F-2666 SODIMM  | 4 GB     | DDR4 | 2667 | 181   | [01DDE0B05DAB](<Notebook/Lenovo/IdeaPad/IdeaPad L340-15API 81LW/01DDE0B05DAB>) |
| Samsung    | K4EBE304EB-EGCG Row Of Ch... | 8 GB     |      | 2133 | 181   | [157A4C5AF28C](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 6th 20KGS0N400/157A4C5AF28C>) |
| Samsung    | M471A1K43BB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 181   | [6A69B366C2BD](<Notebook/Lenovo/ThinkPad/ThinkPad X390 20Q0CTO1WW/6A69B366C2BD>) |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 181   | [2846687B9E23](<Notebook/Lenovo/B590/B590 20206/2846687B9E23>) |
| Micron     | 8ATF1G64HZ-2G3B1 SODIMM      | 8 GB     | DDR4 | 2400 | 180   | [718204E689F2](<Notebook/Hewlett-Packard/Notebook/Notebook/718204E689F2>) |
| Elpida     | Module SODIMM                | 2 GB     | DDR3 | 1333 | 178   | [E0336250387E](<All In One/Apple/iMac12/iMac12,2/E0336250387E>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1600 | 178   | [635367FC7718](<Desktop/Lenovo/ThinkCentre/ThinkCentre M90p 5536P79/635367FC7718>) |
| SK hynix   | HMT451U6AFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 176   | [50E8B6DB82B3](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 TWR/50E8B6DB82B3>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1600 | 176   | [A4B3E062D24F](<Desktop/Acer/Veriton/Veriton X2631G/A4B3E062D24F>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2048 MB  | DDR3 | 1333 | 175   | [D9D8F7D4B536](<Desktop/ECS/A55/A55F-M3/D9D8F7D4B536>) |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2 GB     |      | 4199 | 175   | [463FEDA8D262](<Notebook/Acer/Aspire/Aspire 5738/463FEDA8D262>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 172   | [E4369CCED2D6](<Notebook/Lenovo/ThinkPad/ThinkPad X201 3680X08/E4369CCED2D6>) |
| Micron     | 8JSF25664HZ-1G4D1 SODIMM     | 2 GB     | DDR3 | 1334 | 171   | [BB53DD4ACB6A](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2540p/BB53DD4ACB6A>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 170   | [F2A12A751B05](<Notebook/Hewlett-Packard/ProBook/ProBook 4535s/F2A12A751B05>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1867 | 170   | [CADC0571A83C](<Desktop/Dell/Inspiron/Inspiron 560/CADC0571A83C>) |
| Elpida     | EBJ21UE8BDS0-DJ-F SODIMM     | 2 GB     | DDR3 | 1334 | 169   | [2108CB020FBA](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8440p/2108CB020FBA>) |
| Samsung    | M471A2K43EB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 169   | [7C75519B591E](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X1605VA_X1605VA/7C75519B591E>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 168   | [9A72CAFFBFD7](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS2JD00/9A72CAFFBFD7>) |
| Ramaxel    | RMT3170ME68F9F1600 SODIMM    | 4 GB     | DDR3 | 1600 | 168   | [03379A91D4DC](<Notebook/Hewlett-Packard/EliteBook/EliteBook Folio 9480m/03379A91D4DC>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 167   | [55D765B7E842](<Notebook/ASUSTek Computer/X550/X550JF/55D765B7E842>) |
|            | Module DIMM                  | 1024 MB  |      |      | 166   | [5E0A14BCF009](<Desktop/Hewlett-Packard/GG045AA-ABA/GG045AA-ABA a6142n/5E0A14BCF009>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8192 MB  | DDR3 | 1600 | 165   | [8ABA5CD64582](<Desktop/Lenovo/ThinkCentre/ThinkCentre M92z 33252S6/8ABA5CD64582>) |
| Micron     | MTC4C10163S1SC48BA1 SODIMM   | 8 GB     | DDR5 | 4800 | 165   | [6C33B6C5E4CA](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA507RE_FA577RE/6C33B6C5E4CA>) |
| Elpida     | Module SODIMM                | 4 GB     | DDR3 | 1600 | 164   | [7D9EECEFFC2B](<Notebook/Apple/MacBookAir7/MacBookAir7,2/7D9EECEFFC2B>) |
| SK hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 163   | [D2EFD6893E78](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349NZ4/D2EFD6893E78>) |
| SK hynix   | H9JCNNNCP3MLYR-N6E Row Of... | 2 GB     |      | 6400 | 163   | [F2FBCD1C359C](<Notebook/ASUSTek Computer/Zenbook/Zenbook UX3402ZA_UX3402ZA/F2FBCD1C359C>) |
| Patriot    | 3200 C16 Series DIMM         | 4 GB     | DDR4 | 3600 | 162   | [B82F7FACAFF0](<Desktop/Gigabyte Technology/A520M/A520M DS3H/B82F7FACAFF0>) |
| Elpida     | EBJ21UE8BFU0-DJ-F SODIMM     | 2 GB     | DDR3 | 1333 | 160   | [8536F70D7731](<Notebook/ASUSTek Computer/K53/K53E/8536F70D7731>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 160   | [19C51B14C7DD](<Notebook/Lenovo/IdeaPad/IdeaPad S145-15API 81UT/19C51B14C7DD>) |
| Samsung    | Module SODIMM                | 16 GB    | DDR4 | 3200 | 159   | [21DA868DBAA1](<Notebook/Hewlett-Packard/ProBook/ProBook 440 14 inch G9 Notebook PC/21DA868DBAA1>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 158   | [CD52135FD93F](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X512DA_X512DA/CD52135FD93F>) |
| Kingston   | 99U5471-020.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 158   | [DAAEDA573AD3](<Desktop/MSI/MS/MS-7798/DAAEDA573AD3>) |
| Samsung    | M425R2GA3BB0-CQKOL SODIMM    | 16 GB    | DDR5 | 4800 | 157   | [AB12BC8E8260](<Notebook/MSI/Vector/Vector GP66 12UHSO/AB12BC8E8260>) |
| SK hynix   | Module SODIMM                | 8 GB     | DDR4 | 2133 | 156   | [8DD774BAE2EB](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G3/8DD774BAE2EB>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4 GB     | DDR3 | 1600 | 156   | [B2CBCCF999D1](<Notebook/Hewlett-Packard/Notebook/Notebook/B2CBCCF999D1>) |
| Ramaxel    | RMT3170EB68F9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 156   | [8741D27EB7F3](<Desktop/Lenovo/ThinkCentre/ThinkCentre E93z 10BA0001AU/8741D27EB7F3>) |
| SK hynix   | HMT325S6CFR8C-PB SODIMM      | 2 GB     | DDR3 | 1600 | 155   | [ED64DC835252](<Notebook/Lenovo/ThinkPad/ThinkPad X131e 33722WU/ED64DC835252>) |
| SK hynix   | Module SODIMM                | 8 GB     | DDR3 | 1600 | 155   | [1AAE3FCFA334](<Notebook/Apple/MacBookPro11/MacBookPro11,4/1AAE3FCFA334>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 154   | [4B216AA9EA52](<Desktop/Dell/OptiPlex/OptiPlex 7010/4B216AA9EA52>) |
| Micron     | 4ATS2G64HZ-3G2B1 SODIMM      | 16 GB    | DDR4 | 3200 | 153   | [9A6593AB3EF9](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 2i 20W000BWMX/9A6593AB3EF9>) |
| Samsung    | M471B5173BH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 153   | [F0E4B8D772B3](<Notebook/Toshiba/Satellite/Satellite C50D-A-133/F0E4B8D772B3>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 153   | [5E43D288C796](<All In One/Hewlett-Packard/27/27-p014/5E43D288C796>) |
| Kingston   | ACR256X64D3S1333C9 SODIMM    | 2 GB     | DDR3 | 1334 | 152   | [E78EE4A92CE7](<Notebook/Acer/Aspire/Aspire 5733/E78EE4A92CE7>) |
|            | Module DIMM DDR              | 2048 MB  |      | 1333 | 152   | [B1764C728D58](<Desktop/ASUSTek Computer/M4A79T/M4A79T Deluxe/B1764C728D58>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1333 | 151   | [5E59DF1A21D1](<Desktop/ASUSTek Computer/A68/A68HM-K/5E59DF1A21D1>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1600 | 151   | [F51FFCD16AF1](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/F51FFCD16AF1>) |
|            | Module DIMM                  | 8 GB     | DDR3 | 1333 | 151   | [1EF1ECE712DD](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/1EF1ECE712DD>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 151   | [2CD52138069F](<Notebook/ASUSTek Computer/X556/X556UR/2CD52138069F>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 151   | [DEB1561C4802](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FMS3320G/DEB1561C4802>) |
| Corsair    | CMK16GX4M2A2666C16 DIMM      | 8 GB     | DDR4 | 3400 | 150   | [E4AB5103884A](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p0xx/E4AB5103884A>) |
| SK hynix   | HMA82GS6DJR8N-XN SODIMM      | 16 GB    | DDR4 | 3200 | 150   | [E43BF5E3F0FB](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 17-cd1xxx/E43BF5E3F0FB>) |
| SK hynix   | HMA851S6CJR6N-VK Row Of C... | 4 GB     | DDR4 | 2667 | 149   | [EB58F64E2F99](<Notebook/HUAWEI/BOHK-WAX9/BOHK-WAX9X/EB58F64E2F99>) |
| Samsung    | M471A1G43DB0-CPB SODIMM      | 8 GB     | DDR4 | 3200 | 149   | [3B8F8D2C29D9](<Notebook/Lenovo/ThinkPad/ThinkPad P50 20EQS12Q06/3B8F8D2C29D9>) |
| Samsung    | M471B5273EB0-CK0 SODIMM      | 4096 MB  | DDR3 | 4199 | 148   | [B7601389FED4](<All In One/Dell/XPS/XPS One 2710/B7601389FED4>) |
|            | Module DIMM SDRAM            | 1 GB     |      |      | 146   | [592887AB254B](<Desktop/MSI/MS/MS-6701/592887AB254B>) |
| Samsung    | M471B5273CH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 146   | [D6743F69927F](<Notebook/Toshiba/Satellite/Satellite L855/D6743F69927F>) |
| Kingston   | ACR16D3LS1KFG/4G SODIMM      | 4 GB     | DDR3 | 1600 | 145   | [7E87E58E0326](<Notebook/Acer/Aspire/Aspire E1-731/7E87E58E0326>) |
|            | Module DIMM                  | 4 GB     |      | 1600 | 145   | [8C361D61CA81](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/8C361D61CA81>) |
| Samsung    | U6E3S4AA-MGCR Row Of Chip... | 1 GB     |      | 4267 | 144   | [27E5EAA2D856](<Notebook/Acer/Swift/Swift SF314-59/27E5EAA2D856>) |
| Kingston   | KHX1866C10D3/4G DIMM         | 4 GB     | DDR3 | 1923 | 143   | [EA467D68B2B0](<Desktop/ASRock/Z87/Z87 Killer/EA467D68B2B0>) |
| Nanya      | NT4GC64B8HG0NS-DI SODIMM     | 4 GB     | DDR3 | 1600 | 143   | [9B8B98C59599](<Notebook/Dell/Vostro/Vostro 2520/9B8B98C59599>) |
|            | Module Row Of Chips LPDDR4   | 2 GB     |      | 4267 | 143   | [E40D55F40B44](<Notebook/HUAWEI/RLEF-XX/RLEF-XX/E40D55F40B44>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1600 | 143   | [EC6669129997](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX/EC6669129997>) |
| SK hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 142   | [6A8AAA05DEA5](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 m3 Convertible/6A8AAA05DEA5>) |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 141   | [050B9B1D7FFD](<Convertible/Fujitsu/LIFEBOOK/LIFEBOOK T939/050B9B1D7FFD>) |
| Samsung    | Module SODIMM                | 16 GB    | DDR4 | 2667 | 141   | [E5F896FA5EDA](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G4 DM/E5F896FA5EDA>) |
| SK hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 141   | [D90176014461](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X509JA_X509JA/D90176014461>) |
| Corsair    | CMK16GX4M2D3600C18 DIMM      | 8 GB     | DDR4 | 3600 | 140   | [1308B9921756](<Desktop/ASRock/Z370/Z370 Pro4/1308B9921756>) |
| SK hynix   | HMT351U6EFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 140   | [D21E9EEFFC43](<Desktop/Dell/OptiPlex/OptiPlex 9020/D21E9EEFFC43>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 800  | 140   | [8CFB09ABBC00](<Notebook/Samsung Electronics/R528/R528-R728/8CFB09ABBC00>) |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1333 | 140   | [19BF4FD0AB27](<Notebook/ASUSTek Computer/T100/T100TAF/19BF4FD0AB27>) |
| Team       | TEAMGROUP-UD4-3200 DIMM      | 8 GB     | DDR4 | 3733 | 140   | [5342B9CA551D](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/5342B9CA551D>) |
| Corsair    | CMK32GX4M2D3600C18 DIMM      | 16 GB    | DDR4 | 3800 | 139   | [0CF125A71FC2](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550M-ZAKU/0CF125A71FC2>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 667  | 139   | [F87484BC20AC](<Desktop/ASUSTek Computer/M3/M3A78-CM/F87484BC20AC>) |
|            | Module SODIMM                | 2 GB     | DDR3 | 1333 | 139   | [3CDFDFEDA432](<Notebook/Positivo/W940/W940TU/3CDFDFEDA432>) |
| SK hynix   | HMAA1GS6CJR6N-XN Row Of C... | 8 GB     | DDR4 | 3200 | 138   | [F0368201B804](<Notebook/Lenovo/IdeaPad/IdeaPad 1 15ALC7 82R4/F0368201B804>) |
| Samsung    | M378A1K43CB2-CTD DIMM        | 8 GB     | DDR4 | 3266 | 138   | [ADBCE64F802C](<Desktop/ASUSTek Computer/ROG/ROG Strix GL10DH_GL10DH/ADBCE64F802C>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 1333 | 137   | [BACCDDF67BC6](<Notebook/Digibras/NH4/NH4CU53/BACCDDF67BC6>) |
| Samsung    | M471B2873FHS-CH9 SODIMM      | 1 GB     | DDR3 | 1333 | 137   | [9DF2A2067147](<Notebook/Lenovo/G41-35/G41-35 80M7/9DF2A2067147>) |
| SK hynix   | HMT325S6BFR8C-H9 SODIMM      | 2 GB     | DDR3 | 1333 | 135   | [FCC0FE6F7D0B](<Notebook/Lenovo/ThinkPad/ThinkPad X130e 233827C/FCC0FE6F7D0B>) |
| SK hynix   | HMT451U6BFR8A-PB DIMM        | 4 GB     | DDR3 | 1600 | 135   | [89A433DBAC77](<Desktop/Dell/OptiPlex/OptiPlex 9020/89A433DBAC77>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| ASUSTek    | ASUS           | 39.0  | Li-ion  | 4346  | [8550E720AF](https://linux-hardware.org/?probe=8550e720af) |
| Hewlett... | PABAS0241231   | 51.0  | Li-ion  | 1780  | [F3519FBD26](https://linux-hardware.org/?probe=f3519fbd26) |
| Compal     | PABAS0241231   | 4.2   | Li-ion  | 1179  | [919F9D689C](https://linux-hardware.org/?probe=919f9d689c) |
| MSI        | BIF0_9         | 80.3  | Li-ion  | 1157  | [B064D5D8AA](https://linux-hardware.org/?probe=b064d5d8aa) |
| SMP        | bq20z451       | 54.3  | Li-ion  | 1069  | [531FEB4D85](https://linux-hardware.org/?probe=531feb4d85) |
| Lenovo     | PABAS0241231   | 50.2  | Li-ion  | 934   | [1BE4064009](https://linux-hardware.org/?probe=1be4064009) |
| Intel SR 1 | SR Real        | 50.0  |         | 879   | [A5D0C097A5](https://linux-hardware.org/?probe=a5d0c097a5) |
| OEM        | standard       | 99.1  | Li-ion  | 733   | [5D3FE59ED7](https://linux-hardware.org/?probe=5d3fe59ed7) |
| ASUSTek    | A32-K55        | 64.4  | Li-ion  | 731   | [3CF042BF3F](https://linux-hardware.org/?probe=3cf042bf3f) |
| Hewlett... | Primary        | 45    | Li-ion  | 638   | [2E0D9756FE](https://linux-hardware.org/?probe=2e0d9756fe) |
| Samsung    | SR Real        | 43.1  | Li-ion  | 600   | [7D22EFB355](https://linux-hardware.org/?probe=7d22efb355) |
| Samsung    |                | 49    | Li-ion  | 549   | [C66EAF3382](https://linux-hardware.org/?probe=c66eaf3382) |
| Hewlett... | Primary        | 48    | Li-ion  | 524   | [EB07190046](https://linux-hardware.org/?probe=eb07190046) |
| SANYO      | Li_Ion_4000mA  | 47.5  | Li-ion  | 451   | [AA9170D15A](https://linux-hardware.org/?probe=aa9170d15a) |
| SMP        | DELL GPM0365   | 97.0  | Li-ion  | 416   | [4780FBFF59](https://linux-hardware.org/?probe=4780fbff59) |
| Hewlett... | Primary        | 50    | Li-ion  | 378   | [E0F48651C0](https://linux-hardware.org/?probe=e0f48651c0) |
| Hewlett... | Primary        | 41    | Li-ion  | 372   | [94FDF69690](https://linux-hardware.org/?probe=94fdf69690) |
| DP         | bq20z451       | 54.3  | Li-ion  | 366   | [16DF9D43B9](https://linux-hardware.org/?probe=16df9d43b9) |
| Hewlett... | Primary        | 40    | Li-ion  | 363   | [C2AE1365C2](https://linux-hardware.org/?probe=c2ae1365c2) |
| SANYO      | 45N1773        | 23.2  | Li-ion  | 344   | [E45E264430](https://linux-hardware.org/?probe=e45e264430) |
| LG         | PABAS0241231   | 40.4  | Li-ion  | 341   | [0CCE8338D7](https://linux-hardware.org/?probe=0cce8338d7) |
| Hewlett... | Primary        | 41    | Li-ion  | 330   | [2E065DA895](https://linux-hardware.org/?probe=2e065da895) |
| Hewlett... | Primary        | 53    | Li-ion  | 321   | [9F0FC66E58](https://linux-hardware.org/?probe=9f0fc66e58) |
| LGC        | 45N1127        | 23.5  | Li-ion  | 318   | [56B90E34AE](https://linux-hardware.org/?probe=56b90e34ae) |
| Hewlett... | Primary        | 42    | Li-ion  | 315   | [2B45C6C699](https://linux-hardware.org/?probe=2b45c6c699) |
| Hewlett... | Primary        | 56    | Li-ion  | 303   | [97A21CD2B9](https://linux-hardware.org/?probe=97a21cd2b9) |
| Hewlett... | Primary        | 43    | Li-ion  | 289   | [2127FD790B](https://linux-hardware.org/?probe=2127fd790b) |
| Hewlett... | Primary        | 38    | Li-ion  | 288   | [ACB7DEECE7](https://linux-hardware.org/?probe=acb7deece7) |
| Hewlett... | Primary        | 39    | Li-ion  | 286   | [BA44D0E580](https://linux-hardware.org/?probe=ba44d0e580) |
| Hewlett... | Primary        | 44    | Li-ion  | 285   | [2729BDE753](https://linux-hardware.org/?probe=2729bde753) |
| LGC        | AP18C8K        | 48.0  | Li-ion  | 280   | [52B26CAC3F](https://linux-hardware.org/?probe=52b26cac3f) |
| Hewlett... | Primary        | 46    | Li-ion  | 279   | [349DDF33A4](https://linux-hardware.org/?probe=349ddf33a4) |
| Hewlett... | Primary        | 51    | Li-ion  | 273   | [60AB24F653](https://linux-hardware.org/?probe=60ab24f653) |
| Notebook   | BAT            | 49    | Li-ion  | 267   | [7DA1ABB74D](https://linux-hardware.org/?probe=7da1abb74d) |
| LGC        | AP18E8M        | 57.5  | Li-ion  | 264   | [8461425EC1](https://linux-hardware.org/?probe=8461425ec1) |
| SMP        | L16M2PB1       | 30.0  | Li-poly | 249   | [3200CAAB14](https://linux-hardware.org/?probe=3200caab14) |
| Hewlett... | Primary        | 36    | Li-ion  | 248   | [D87A6139F6](https://linux-hardware.org/?probe=d87a6139f6) |
| WB SR 1    | WB Lion        | 19.2  | Li-ion  | 240   | [DAE997FEE3](https://linux-hardware.org/?probe=dae997fee3) |
| ASUSTek    | X550A26        | 34.6  | Li-ion  | 231   | [FFFC36417C](https://linux-hardware.org/?probe=fffc36417c) |
|            | Battery        |       |         | 229   | [EB1866B0F2](https://linux-hardware.org/?probe=eb1866b0f2) |
| SANYO      | 45N1775        | 23.2  | Li-ion  | 228   | [F78ACAD9FD](https://linux-hardware.org/?probe=f78acad9fd) |
| Notebook   | BAT            | 48    | Li-ion  | 225   | [C4AF5FAFE4](https://linux-hardware.org/?probe=c4af5fafe4) |
| CPT-COS    | L16C2PB2       | 30.6  | Li-poly | 222   | [145B300A77](https://linux-hardware.org/?probe=145b300a77) |
| Hewlett... | Primary        | 37    | Li-ion  | 218   | [317B3A0D60](https://linux-hardware.org/?probe=317b3a0d60) |
| SMP        | L16M2PB2       | 35.0  | Li-poly | 217   | [B55322DD58](https://linux-hardware.org/?probe=b55322dd58) |
| SANYO      | AL12A32        | 37.0  | Li-ion  | 212   | [C0F17443E2](https://linux-hardware.org/?probe=c0f17443e2) |
| SMP        | DELL G8VCF6C   | 52.0  | Li-poly | 207   | [E6D3CB85C1](https://linux-hardware.org/?probe=e6d3cb85c1) |
| Panasonic  | AP16M5J        | 37.0  | Li-ion  | 206   | [734FD13848](https://linux-hardware.org/?probe=734fd13848) |
| Samsung    |                | 44    | Li-ion  | 206   | [924A6A8572](https://linux-hardware.org/?probe=924a6a8572) |
| Panasonic  | AP19B5L        | 53.0  | Li-ion  | 204   | [D2483D4BB8](https://linux-hardware.org/?probe=d2483d4bb8) |
| SMP        | DELL 70N2F95   | 84.3  | Li-poly | 204   | [D929F4B785](https://linux-hardware.org/?probe=d929f4b785) |
| SANYO      | PABAS0241231   | 38.9  | Li-ion  | 203   | [9CBBD96A18](https://linux-hardware.org/?probe=9cbbd96a18) |
| SANYO      | AL15A32        | 29.6  | Li-ion  | 198   | [42555DDE71](https://linux-hardware.org/?probe=42555dde71) |
| Emdoor     |  Li-ion        | 38.0  | Li-ion  | 194   | [4A1B8628E0](https://linux-hardware.org/?probe=4a1b8628e0) |
| SIMPLO     | PABAS0241231   | 46.0  | Li-ion  | 194   | [4D428FF2FD](https://linux-hardware.org/?probe=4d428ff2fd) |
| CosMX      | AP20CBL        | 53.0  | Li-ion  | 181   | [67B8E4D3E7](https://linux-hardware.org/?probe=67b8e4d3e7) |
| SANYO      | AL10B31        | 48.8  | Li-ion  | 180   | [99379DECCC](https://linux-hardware.org/?probe=99379deccc) |
| Hewlett... | Primary        |       | Li-ion  | 178   | [010343CF1D](https://linux-hardware.org/?probe=010343cf1d) |
| Sony       | 45N1111        | 23.2  | Li-poly | 171   | [C62F3B52E2](https://linux-hardware.org/?probe=c62f3b52e2) |
| LGC        | AC14B8K        | 48.9  | Li-ion  | 170   | [ED218C23AE](https://linux-hardware.org/?probe=ed218c23ae) |
| SMP        | 01AV421        | 24.0  | Li-poly | 169   | [A84D2E6201](https://linux-hardware.org/?probe=a84d2e6201) |
| Sunwoda-H  | HB4692Z9ECW... | 55.2  | Li-ion  | 169   | [B88F684622](https://linux-hardware.org/?probe=b88f684622) |
| LGC        | L16L2PB2       | 29.6  | Li-poly | 168   | [2BC9B23A42](https://linux-hardware.org/?probe=2bc9b23a42) |
| Hewlett... | Primary        | 32    | Li-ion  | 167   | [EA9DCCD4A8](https://linux-hardware.org/?probe=ea9dccd4a8) |
| Panasonic  | Li_Ion_4000mA  | 47.5  | Li-ion  | 166   | [18A8D13FE9](https://linux-hardware.org/?probe=18a8d13fe9) |
| Hewlett... | Primary        | 49    | Li-ion  | 165   | [87AEA4A07B](https://linux-hardware.org/?probe=87aea4a07b) |
| AS3GWAF3KC | GA50358        | 90.0  |         | 163   | [EEEF064F3D](https://linux-hardware.org/?probe=eeef064f3d) |
| Hewlett... | Primary        | 34    | Li-ion  | 161   | [98D64B84A8](https://linux-hardware.org/?probe=98d64b84a8) |
| LG         | Li_Ion_4000mA  | 47.5  | Li-ion  | 160   | [1C7D970F58](https://linux-hardware.org/?probe=1c7d970f58) |
| Hewlett... | Primary        | 35    | Li-ion  | 158   | [F6EDF49C41](https://linux-hardware.org/?probe=f6edf49c41) |
| Hewlett... | Primary        | 47    | Li-ion  | 158   | [F1BC5970F8](https://linux-hardware.org/?probe=f1bc5970f8) |
| LGC        | 45N1113        | 23.5  | Li-ion  | 157   | [E29CC227AE](https://linux-hardware.org/?probe=e29cc227ae) |
| LGC        | 5B10W139       | 57.0  | Li-poly | 154   | [31A4026530](https://linux-hardware.org/?probe=31a4026530) |
| ASUSTek    | UX31-35        | 47.9  | Li-ion  | 149   | [E909C7AC51](https://linux-hardware.org/?probe=e909c7ac51) |
| LGC        | 45N1049        | 47.5  | Li-ion  | 148   | [0EC203FDB6](https://linux-hardware.org/?probe=0ec203fdb6) |
| Lenovo     | BASE-BAT       | 32.2  | Li-poly | 146   | [B458C0587B](https://linux-hardware.org/?probe=b458c0587b) |
| LGC        | AC14B18J       | 36.7  | Li-ion  | 146   | [D4CF291B46](https://linux-hardware.org/?probe=d4cf291b46) |
| Notebook   | BAT            | 74    | Li-ion  | 146   | [C5C16912FE](https://linux-hardware.org/?probe=c5c16912fe) |
| SANYO      | 00323341343... | 55.9  | Li-ion  | 146   | [4E3D903B5D](https://linux-hardware.org/?probe=4e3d903b5d) |
| SANYO      | AS10D31        | 73.3  | Li-ion  | 146   | [7F36D968E4](https://linux-hardware.org/?probe=7f36d968e4) |
| ASUSTek    | X550A30        | 37.4  | Li-ion  | 144   | [F39F501A7F](https://linux-hardware.org/?probe=f39f501a7f) |
| LG         | 004B3842343... | 48.9  | Li-ion  | 143   | [7784C8E1A1](https://linux-hardware.org/?probe=7784c8e1a1) |
| Samsung    |                | 48    | Li-ion  | 142   | [76E645E1F5](https://linux-hardware.org/?probe=76e645e1f5) |
| TKBSS      | NS2P3SZMC4WR   | 48.4  | Li-ion  | 142   | [38ED2A4B9E](https://linux-hardware.org/?probe=38ed2a4b9e) |
| SMP        | DELL Y3F7Y6B   | 42.0  | Li-ion  | 141   | [06F46F7744](https://linux-hardware.org/?probe=06f46f7744) |
| Panasonic  | AS16A5K        | 41.4  | Li-ion  | 140   | [19077CD048](https://linux-hardware.org/?probe=19077cd048) |
| NVT        | Framewo        | 55.0  | Li-ion  | 139   | [705DCE2BDC](https://linux-hardware.org/?probe=705dce2bdc) |
|            | 47.52          | 48    | Li-ion  | 138   | [6C895D905F](https://linux-hardware.org/?probe=6c895d905f) |
| Notebook   | BAT            | 62    | Li-ion  | 137   | [02CCCCE76F](https://linux-hardware.org/?probe=02cccce76f) |
| ASUSTek    | K52F-44        | 57.2  | Li-ion  | 136   | [A19AD8FBD8](https://linux-hardware.org/?probe=a19ad8fbd8) |
| Razer      | Blade          | 65.0  |         | 136   | [E052122061](https://linux-hardware.org/?probe=e052122061) |
| SANYO      | GC86508SAT0    | 44.4  | Li-ion  | 136   | [10F43A8F8C](https://linux-hardware.org/?probe=10f43a8f8c) |
| Sony       | VGP-BPS26      | 45.0  | Li-ion  | 136   | [11625E4A3C](https://linux-hardware.org/?probe=11625e4a3c) |
| Hewlett... | Primary        | 28    | Li-ion  | 135   | [413B02DC7A](https://linux-hardware.org/?probe=413b02dc7a) |
| SIMPLO     | BASE-BAT       | 66.0  | Li-poly | 135   | [B0481EA420](https://linux-hardware.org/?probe=b0481ea420) |
| ASUSTek    | F82-22         | 46.2  | Li-ion  | 134   | [707B1552B4](https://linux-hardware.org/?probe=707b1552b4) |
| SMP        | AP18E7M        | 58.8  | Li-ion  | 134   | [E3FB9AF71C](https://linux-hardware.org/?probe=e3fb9af71c) |
| Hewlett... | Primary        | 33    | Li-ion  | 131   | [AC422E1A6C](https://linux-hardware.org/?probe=ac422e1a6c) |
| SANYO      | PABAS024       | 38.9  | Li-ion  | 130   | [9D15C84512](https://linux-hardware.org/?probe=9d15c84512) |
| ASUSTek    | X555-50        | 37.3  | Li-ion  | 128   | [220480564A](https://linux-hardware.org/?probe=220480564a) |
| LGC        | L16L2PB3       | 35.0  | Li-poly | 127   | [DD0F8BEB36](https://linux-hardware.org/?probe=dd0f8beb36) |
| Hewlett... | Primary        | 55    | Li-ion  | 126   | [BB10D0F283](https://linux-hardware.org/?probe=bb10d0f283) |
| Celxpert   | 01AV424        | 24.1  | Li-poly | 124   | [CC7C458456](https://linux-hardware.org/?probe=cc7c458456) |
| Hewlett... | Primary        | 31    | Li-ion  | 124   | [B31F0109E7](https://linux-hardware.org/?probe=b31f0109e7) |
| SANYO      | 45N1001        | 56.2  | Li-ion  | 124   | [F06B701043](https://linux-hardware.org/?probe=f06b701043) |
| CPT-COS    | L16C2PB1       | 35.3  | Li-poly | 122   | [F149ED620F](https://linux-hardware.org/?probe=f149ed620f) |
| Hewlett... | Primary        | 30    | Li-ion  | 121   | [9CE5B91ECB](https://linux-hardware.org/?probe=9ce5b91ecb) |
| Desay      | HB4692Z9ECW... | 55.2  | Li-ion  | 117   | [E97A651E78](https://linux-hardware.org/?probe=e97a651e78) |
| SIMPLO     | SDI ICR18650   | 48.0  | Li-ion  | 116   | [02F586555D](https://linux-hardware.org/?probe=02f586555d) |
| LGC        | 01AV489        | 23.9  | Li-poly | 112   | [55F0836EA7](https://linux-hardware.org/?probe=55f0836ea7) |
| Hewlett... | Primary        | 38    | Li-ion  | 109   | [83D420AB00](https://linux-hardware.org/?probe=83d420ab00) |
| SANYO      | 01AV405        | 26.3  | Li-ion  | 108   | [701FC032DB](https://linux-hardware.org/?probe=701fc032db) |
| SMP        | 5B10W13933     | 46.0  | Li-poly | 108   | [9B87A450BD](https://linux-hardware.org/?probe=9b87a450bd) |
| Hewlett... | Primary        | 42    | Li-ion  | 107   | [941BD5D7BC](https://linux-hardware.org/?probe=941bd5d7bc) |
| Samsung... | DELL P8TC727   | 48.8  | Li-ion  | 107   | [C3A5CF03A9](https://linux-hardware.org/?probe=c3a5cf03a9) |
| Lenovo ... |                | 28    |         | 106   | [E3FF832AE6](https://linux-hardware.org/?probe=e3ff832ae6) |
| ASUSTek    | K55--44        | 48.4  | Li-ion  | 105   | [991EDF32B4](https://linux-hardware.org/?probe=991edf32b4) |
| SMP        | 00HW023        | 23.5  | Li-poly | 105   | [A22BE910D2](https://linux-hardware.org/?probe=a22be910d2) |
| Sony       | Li_Ion_4000mA  | 47.5  | Li-ion  | 105   | [2D5EEF0754](https://linux-hardware.org/?probe=2d5eef0754) |
| Hewlett... | Primary        | 29    | Li-ion  | 104   | [4891753C29](https://linux-hardware.org/?probe=4891753c29) |
| OEM        | FX50442        | 48.0  | Li-ion  | 103   | [AAED88422C](https://linux-hardware.org/?probe=aaed88422c) |
| Celxpert   | 01AV448        | 45.7  | Li-poly | 101   | [D64710669E](https://linux-hardware.org/?probe=d64710669e) |
| LGC        | 45N1005        | 56.2  | Li-ion  | 100   | [FBC061A72A](https://linux-hardware.org/?probe=fbc061a72a) |
| SMP        | 00NY493        | 90.0  | Li-poly | 100   | [ECD4468E9C](https://linux-hardware.org/?probe=ecd4468e9c) |
|            | 48.6           | 49    | Li-ion  | 99    | [5014D7827E](https://linux-hardware.org/?probe=5014d7827e) |
| SMP        | 01AV430        | 57.0  | Li-poly | 99    | [5F5AE67CD6](https://linux-hardware.org/?probe=5f5ae67cd6) |
| SMP        | DELL VN3N047   | 41.4  | Li-ion  | 99    | [35F435CD1F](https://linux-hardware.org/?probe=35f435cd1f) |
| SANYO      | 00HW022        | 23.5  | Li-poly | 98    | [701FC032DB](https://linux-hardware.org/?probe=701fc032db) |
| SMP        | L20M2PF0       | 38.0  | Li-poly | 98    | [079C56CEAB](https://linux-hardware.org/?probe=079c56ceab) |
| Sunwoda    | 5B10W13975     | 57.0  | Li-poly | 98    | [7D10950E55](https://linux-hardware.org/?probe=7d10950e55) |
| Sunwoda-H  | HB4692J5ECW-31 | 41.4  | Li-ion  | 98    | [3B12D86F3D](https://linux-hardware.org/?probe=3b12d86f3d) |
| ASUSTek    | K53--52        | 48.4  | Li-ion  | 97    | [33CE8DAF57](https://linux-hardware.org/?probe=33ce8daf57) |
| Hewlett... | Primary        | 89    | Li-ion  | 97    | [6C3D7E52E4](https://linux-hardware.org/?probe=6c3d7e52e4) |
| Samsung    |                | 58    | Li-ion  | 97    | [981D2CCF1D](https://linux-hardware.org/?probe=981d2ccf1d) |
| SMP        | 01AV447        | 45.7  | Li-poly | 97    | [61FE1222C2](https://linux-hardware.org/?probe=61fe1222c2) |
| SMP        | DELL DM3WC64   | 60.0  | Li-poly | 97    | [FAA26E30D0](https://linux-hardware.org/?probe=faa26e30d0) |
| SANYO      | 45N1023        | 93.2  | Li-ion  | 96    | [68E4BABAF4](https://linux-hardware.org/?probe=68e4babaf4) |
| Hewlett... | Primary        | 26    | Li-ion  | 95    | [CF6BA1EAD2](https://linux-hardware.org/?probe=cf6ba1ead2) |
| Hewlett... | Primary        | 27    | Li-ion  | 95    | [14D900EECC](https://linux-hardware.org/?probe=14d900eecc) |
| Hewlett... | Primary        | 40    | Li-ion  | 95    | [90DDB2C764](https://linux-hardware.org/?probe=90ddb2c764) |
| LG         | PABAS024       | 40.0  | Li-ion  | 95    | [B41AB58347](https://linux-hardware.org/?probe=b41ab58347) |
| SMP        | DELL VM73283   | 42.0  | Li-poly | 92    | [083EF3A0A2](https://linux-hardware.org/?probe=083ef3a0a2) |
| Hewlett... | Primary        | 70    | Li-ion  | 91    | [779320377B](https://linux-hardware.org/?probe=779320377b) |
| SMP        | DELL TP1GT61   | 60.0  | Li-poly | 91    | [4E5B03BFD7](https://linux-hardware.org/?probe=4e5b03bfd7) |
| SMP        | L19M4PC0       | 60.0  | Li-poly | 91    | [79AB3BBC9E](https://linux-hardware.org/?probe=79ab3bbc9e) |
| Desay      | HB4692J5ECW-31 | 41.4  | Li-ion  | 90    | [94C62E3B8B](https://linux-hardware.org/?probe=94c62e3b8b) |
| LGC        | 45N1011        | 93.6  | Li-ion  | 90    | [278931EF6A](https://linux-hardware.org/?probe=278931ef6a) |
| CPT-COS    | L17C4PB0       | 45.5  | Li-poly | 89    | [22FCB1190C](https://linux-hardware.org/?probe=22fcb1190c) |
| LG         | LGC-LGC        | 80.0  | Li-ion  | 89    | [CC84DBC880](https://linux-hardware.org/?probe=cc84dbc880) |
| LGC        | 45N1025        | 57.7  | Li-ion  | 89    | [155F2F1E8F](https://linux-hardware.org/?probe=155f2f1e8f) |
| Sony       |                | 42    | Li-ion  | 89    | [2B91CCAB1C](https://linux-hardware.org/?probe=2b91ccab1c) |
| Sunwoda-H  | HB4692Z9ECW-41 | 55.2  | Li-ion  | 89    | [287C370D01](https://linux-hardware.org/?probe=287c370d01) |
| ASUSTek    | N56--52        | 54.0  | Li-ion  | 88    | [952D22573D](https://linux-hardware.org/?probe=952d22573d) |
| SMP        | DELL VM73297   | 42.0  | Li-poly | 88    | [97DAAED0C7](https://linux-hardware.org/?probe=97daaed0c7) |
| ASUSTek    | K55--47        | 51.7  | Li-ion  | 87    | [5A4A07F120](https://linux-hardware.org/?probe=5a4a07f120) |
| LGC        | 01AV445        | 45.0  | Li-poly | 87    | [99C42F786E](https://linux-hardware.org/?probe=99c42f786e) |
| LGC        | L17L2PF1       | 30.0  | Li-poly | 87    | [CDD64FE0E0](https://linux-hardware.org/?probe=cdd64fe0e0) |
| APL MRD    |  Li-ion        | 27.8  | Li-ion  | 86    | [87F8D03C80](https://linux-hardware.org/?probe=87f8d03c80) |
| Hewlett... | Primary        | 37    | Li-ion  | 86    | [210729B8A3](https://linux-hardware.org/?probe=210729b8a3) |
| Celxpert   | L19C3PD6       | 52.5  | Li-poly | 85    | [56DA00ADA2](https://linux-hardware.org/?probe=56da00ada2) |
| SANYO      | 45N1043        | 38.9  | Li-ion  | 85    | [E73050A450](https://linux-hardware.org/?probe=e73050a450) |
| SMP        | DELL GD1JP65   | 68.0  | Li-poly | 85    | [B9ACBDA728](https://linux-hardware.org/?probe=b9acbda728) |
| SMP        | L17M3PG2       | 57.4  | Li-poly | 85    | [CBEBFA258B](https://linux-hardware.org/?probe=cbebfa258b) |
| LGC        | AP19B8K        | 41.8  | Li-ion  | 84    | [3D85A6B6D7](https://linux-hardware.org/?probe=3d85a6b6d7) |
| Sunwoda    | 5B10X025       | 45.0  | Li-poly | 82    | [46361A1B83](https://linux-hardware.org/?probe=46361a1b83) |
| ASUSTek    | X453-42        | 31.7  | Li-ion  | 81    | [68441310DB](https://linux-hardware.org/?probe=68441310db) |
| LGC        | 01AV490        | 23.9  | Li-poly | 81    | [A84D2E6201](https://linux-hardware.org/?probe=a84d2e6201) |
| Notebook   | BAT            | 53    | Li-ion  | 81    | [1E6E93D88B](https://linux-hardware.org/?probe=1e6e93d88b) |
| Sunwoda    | R15B01W        | 60.0  | Li-ion  | 81    | [4A2509BD5A](https://linux-hardware.org/?probe=4a2509bd5a) |
| Dynapack   | HB4593R1ECW    | 56.3  | Li-ion  | 80    | [6BCB7835D8](https://linux-hardware.org/?probe=6bcb7835d8) |
| Hewlett... | Primary        | 24    | Li-ion  | 80    | [7D0E5BBE48](https://linux-hardware.org/?probe=7d0e5bbe48) |
| LGC        | LNV-45N1       | 47.5  | Li-ion  | 80    | [0AD5EC9E46](https://linux-hardware.org/?probe=0ad5ec9e46) |
| Notebook   | BAT            | 36    | Li-ion  | 80    | [4CDFCE4D81](https://linux-hardware.org/?probe=4cdfce4d81) |
| SANYO      | 42T4763        | 47.5  | Li-ion  | 80    | [467D5BF559](https://linux-hardware.org/?probe=467d5bf559) |
| Standard   | SR Real        | 43.9  | Li-ion  | 80    | [1D27092258](https://linux-hardware.org/?probe=1d27092258) |
|            | 48.84          | 49    | Li-ion  | 79    | [53E5C4A853](https://linux-hardware.org/?probe=53e5c4a853) |
| Celxpert   | 5B10X026       | 45.0  | Li-poly | 78    | [C4604E2890](https://linux-hardware.org/?probe=c4604e2890) |
| Hewlett... | Primary        | 57    | Li-ion  | 78    | [E2BABD2E7E](https://linux-hardware.org/?probe=e2babd2e7e) |
| Notebook   | BAT            | 60    | Li-ion  | 78    | [1BCBFEE6C4](https://linux-hardware.org/?probe=1bcbfee6c4) |
| AS3GWYF3KC | GA50358        | 90.0  | Li-ion  | 76    | [537E296CF8](https://linux-hardware.org/?probe=537e296cf8) |
| Sunwoda    | HB6081V1ECW-41 | 55.2  | Li-ion  | 76    | [5B9314F900](https://linux-hardware.org/?probe=5b9314f900) |
| Hewlett... | Primary        | 54    | Li-ion  | 75    | [003D0CC183](https://linux-hardware.org/?probe=003d0cc183) |
| Hewlett... | Primary        | 39    | Li-ion  | 75    | [F2B2C52113](https://linux-hardware.org/?probe=f2b2c52113) |
| SMP        | L19M3PF7       | 45.0  | Li-poly | 75    | [986D807D00](https://linux-hardware.org/?probe=986d807d00) |
| Celxpert   | L20C4PC1       | 80.0  | Li-poly | 74    | [B4EC08B540](https://linux-hardware.org/?probe=b4ec08b540) |
| GLK MRD    |  Li-ion        | 29.6  | Li-ion  | 74    | [1B076CC569](https://linux-hardware.org/?probe=1b076cc569) |
| LGC        | 01AV494        | 57.0  | Li-poly | 74    | [07DF89F610](https://linux-hardware.org/?probe=07df89f610) |
| ASUSTek    | F3---24        | 51.3  | Li-ion  | 73    | [5AE3280AA4](https://linux-hardware.org/?probe=5ae3280aa4) |
| LGC        | 01AV478        | 57.0  | Li-poly | 73    | [77513C5287](https://linux-hardware.org/?probe=77513c5287) |
| Notebook   | BAT            | 35    | Li-ion  | 73    | [A45B75D9EC](https://linux-hardware.org/?probe=a45b75d9ec) |
| SANYO      | L09S6Y02       | 38.9  | Li-ion  | 73    | [E6F8F51A09](https://linux-hardware.org/?probe=e6f8f51a09) |
| DSY        | bq20z451       | 54.7  | Li-ion  | 72    | [D91DBCCFEE](https://linux-hardware.org/?probe=d91dbccfee) |
| SANYO      | GRAPE32        | 48.8  | Li-ion  | 72    | [D596BA355A](https://linux-hardware.org/?probe=d596ba355a) |
| SMP        | 02DL005        | 51.0  | Li-poly | 72    | [21EE611B47](https://linux-hardware.org/?probe=21ee611b47) |
| Sunwoda    | L20D4PC1       | 80.0  | Li-poly | 72    | [F7062395DC](https://linux-hardware.org/?probe=f7062395dc) |
| CPT-COS    | L14C3P6        | 36.6  | Li-ion  | 71    | [074B44CE16](https://linux-hardware.org/?probe=074b44ce16) |
| Lenovo     |                | 28    |         | 71    | [9228EF946E](https://linux-hardware.org/?probe=9228ef946e) |
| SMP        | L14M3P24       | 45.0  | Li-poly | 71    | [E21A2D89C6](https://linux-hardware.org/?probe=e21a2d89c6) |
|            |                | 38    | Li-ion  | 70    | [4B5DE9A37A](https://linux-hardware.org/?probe=4b5de9a37a) |
| SANYO      | 42T4799        | 93.2  | Li-ion  | 70    | [9FDE9FE106](https://linux-hardware.org/?probe=9fde9fe106) |
| SANYO      | AP13B3K        | 54.9  | Li-ion  | 70    | [6E5B5FDDF5](https://linux-hardware.org/?probe=6e5b5fddf5) |
| Hewlett... | 5600           | 62.2  |         | 69    | [92FE6246AB](https://linux-hardware.org/?probe=92fe6246ab) |
| Hewlett... | Primary        | 36    | Li-ion  | 69    | [92FAD15C25](https://linux-hardware.org/?probe=92fad15c25) |
| Lenovo ... |                | 38    |         | 69    | [03181287B8](https://linux-hardware.org/?probe=03181287b8) |
| Notebook   | BAT            | 71    | Li-ion  | 69    | [3863C274D8](https://linux-hardware.org/?probe=3863c274d8) |
| Panasonic  | AP19B5K        | 39.7  | Li-ion  | 69    | [E373D8AEF5](https://linux-hardware.org/?probe=e373d8aef5) |
| SMP        | 5B10X026       | 45.7  | Li-poly | 69    | [F6852CBDBB](https://linux-hardware.org/?probe=f6852cbdbb) |
| OEM        | AS10D31        | 48.4  | Li-ion  | 68    | [FDEB7FFD07](https://linux-hardware.org/?probe=fdeb7ffd07) |
| SANYO      | 45N1777        | 71.3  | Li-ion  | 68    | [D92935DB90](https://linux-hardware.org/?probe=d92935db90) |
| SMP        | 01AV452        | 24.0  | Li-poly | 68    | [DC1B85E281](https://linux-hardware.org/?probe=dc1b85e281) |
| SMP        | 5B10W138       | 45.3  | Li-poly | 68    | [EADC7945CF](https://linux-hardware.org/?probe=eadc7945cf) |
| SMP        | 5B10W13973     | 57.0  | Li-poly | 68    | [E08182ADC8](https://linux-hardware.org/?probe=e08182adc8) |
| ASUSTek    | UX425          | 67.3  | Li-ion  | 67    | [17286DDCF5](https://linux-hardware.org/?probe=17286ddcf5) |
| LGC        | 45N1147        | 56.2  | Li-ion  | 67    | [0574E44035](https://linux-hardware.org/?probe=0574e44035) |
| LGC        | 45N1735        | 47.5  | Li-ion  | 67    | [90C5C9954F](https://linux-hardware.org/?probe=90c5c9954f) |
| LGC KT0... | AP18C8K        | 48.0  | Li-ion  | 67    | [4C12C9EEDA](https://linux-hardware.org/?probe=4c12c9eeda) |
| SMP        | 5B10W139       | 57.0  | Li-poly | 67    | [7BFAD25E97](https://linux-hardware.org/?probe=7bfad25e97) |
| ASUSTek    | K56--30        | 44.6  | Li-ion  | 66    | [89F8BE5027](https://linux-hardware.org/?probe=89f8be5027) |
| Hewlett... | Primary        | 22    | Li-ion  | 66    | [AA662F23E7](https://linux-hardware.org/?probe=aa662f23e7) |
| SMP        | 01AV406        | 26.1  | Li-poly | 66    | [6ABE074048](https://linux-hardware.org/?probe=6abe074048) |
| ASUSTek    | F5---22        | 47.3  | Li-ion  | 65    | [8B5218D324](https://linux-hardware.org/?probe=8b5218d324) |
| LGC        | 45N1738        | 71.1  | Li-ion  | 65    | [CA04E40DD4](https://linux-hardware.org/?probe=ca04e40dd4) |
| SANYO      | 45N1767        | 47.5  | Li-ion  | 65    | [B200A9D4F6](https://linux-hardware.org/?probe=b200a9d4f6) |
| SMP        | 5B10W13906     | 50.5  | Li-poly | 65    | [E5BF005A5F](https://linux-hardware.org/?probe=e5bf005a5f) |
| SMP        | 5B11C732       | 57.0  | Li-poly | 65    | [ED035FD7D8](https://linux-hardware.org/?probe=ed035fd7d8) |
| ASUSTek    | UM3402         | 75.1  | Li-ion  | 64    | [FAE705DE3F](https://linux-hardware.org/?probe=fae705de3f) |
| Hewlett... | Primary        | 18    | Li-ion  | 64    | [5692787B6F](https://linux-hardware.org/?probe=5692787b6f) |
| Sony       |                | 51    | Li-ion  | 64    | [B7D8F997E5](https://linux-hardware.org/?probe=b7d8f997e5) |
|            |                |       | Li-ion  | 63    | [9E63659C87](https://linux-hardware.org/?probe=9e63659c87) |
| BYD        | L20B2PF0       | 38.0  | Li-poly | 63    | [4053C77698](https://linux-hardware.org/?probe=4053c77698) |
| LGC        | 02DL004        | 51.0  | Li-poly | 63    | [2D1F00B430](https://linux-hardware.org/?probe=2d1f00b430) |
| Samsung    |                | 24    | Li-ion  | 63    | [8147199CF5](https://linux-hardware.org/?probe=8147199cf5) |
| ASUSTek    | K53--27        | 37.8  | Li-ion  | 62    | [BE228218D5](https://linux-hardware.org/?probe=be228218d5) |
| ASUSTek    | N550-40        | 60.5  | Li-ion  | 62    | [9601E6C7A2](https://linux-hardware.org/?probe=9601e6c7a2) |
| ASUSTek    | UX325          | 67.3  | Li-ion  | 62    | [12BE2072AF](https://linux-hardware.org/?probe=12be2072af) |
| LGC        | L20L2PF0       | 38.0  | Li-poly | 62    | [CD9B055146](https://linux-hardware.org/?probe=cd9b055146) |
| Notebook   | BAT            | 47    | Li-ion  | 62    | [FEC43DC843](https://linux-hardware.org/?probe=fec43dc843) |
| Samsung    |                | 45    | Li-ion  | 62    | [B56D767DB4](https://linux-hardware.org/?probe=b56d767db4) |
| SMP        | 5B10W51827     | 50.5  | Li-poly | 62    | [369CDD52D8](https://linux-hardware.org/?probe=369cdd52d8) |
| SWD        | bq20z451       | 58.2  | Li-ion  | 62    | [73163D4EE6](https://linux-hardware.org/?probe=73163d4ee6) |
| Hewlett... | Primary        | 52    | Li-ion  | 61    | [62C6C176F6](https://linux-hardware.org/?probe=62c6c176f6) |
| LGC        | 5B10X026       | 45.0  | Li-poly | 61    | [32F125D899](https://linux-hardware.org/?probe=32f125d899) |
| Panasonic  | AS16B5J        | 48.8  | Li-ion  | 61    | [AEB8A7CB0E](https://linux-hardware.org/?probe=aeb8a7cb0e) |
| SANYO      | AS07B31        | 48.8  | Li-ion  | 61    | [9426ED7AFF](https://linux-hardware.org/?probe=9426ed7aff) |
| Toshiba    | PABAS0241231   | 45.0  | Li-ion  | 61    | [1D473C3A6C](https://linux-hardware.org/?probe=1d473c3a6c) |
| Amd Bat... |  Real Li-ion   | 49.1  | Li-ion  | 60    | [F57DB5B2DD](https://linux-hardware.org/?probe=f57db5b2dd) |
| Celxpert   | 5B10W138       | 45.7  | Li-poly | 60    | [2F3855ED8D](https://linux-hardware.org/?probe=2f3855ed8d) |
| Getac      | BC 4S1P        | 73.4  | Li-ion  | 60    | [AD76CB1437](https://linux-hardware.org/?probe=ad76cb1437) |
| Notebook   | BAT            | 52    | Li-ion  | 60    | [CB477659F5](https://linux-hardware.org/?probe=cb477659f5) |
| Panasonic  | AP15O5L        | 53.9  | Li-ion  | 60    | [6A294F74E1](https://linux-hardware.org/?probe=6a294f74e1) |

