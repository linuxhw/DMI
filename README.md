DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by Linux users at https://linux-hardware.org.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Total reports: 105979.

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
| Intel      | 11th Gen Core i5-1135G7          | 2.40 | 2741  | [A2A365A795E5](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga Gen 6 20XYCTO1WW/A2A365A795E5>) |
| Intel      | Core i5-8250U                    | 1.60 | 1036  | [E799DF02E5A3](<Notebook/Dell/XPS/XPS 13 9370/E799DF02E5A3>) |
| Intel      | Core i7-8550U                    | 1.80 | 960   | [39EE02D40549](<Notebook/Dell/XPS/XPS 13 9370/39EE02D40549>) |
| Intel      | Core i5-7200U                    | 2.50 | 842   | [DA67C3C0247F](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20HN0015GE/DA67C3C0247F>) |
| AMD        | Ryzen 5 3600 6-Core              |      | 738   | [2370D821533B](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/2370D821533B>) |
| Intel      | Core i7-10510U                   | 1.80 | 675   | [D76D74ED9BB6](<Notebook/Hewlett-Packard/ENVY/ENVY Laptop 13-aq1xxx/D76D74ED9BB6>) |
| Intel      | Core i7-9750H                    | 2.60 | 665   | [0EFBC06F4005](<Notebook/SLIMBOOK/PROX/PROX15/0EFBC06F4005>) |
| AMD        | Ryzen 5 3500U with Radeon Veg... |      | 653   | [D7489F37B116](<Notebook/Lenovo/IdeaPad/IdeaPad S340-15API 81NC/D7489F37B116>) |
| Intel      | Core i7-8750H                    | 2.20 | 644   | [E2360AE2AC48](<Notebook/Lenovo/Legion/Legion Y530-15ICH 81FV/E2360AE2AC48>) |
| Intel      | Core i5-10210U                   | 1.60 | 628   | [66A4B1E48D59](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20S0000JGE/66A4B1E48D59>) |
| Intel      | Core i5-3210M                    | 2.50 | 611   | [4827CD3B80C9](<Desktop/OEM/Others/Others/4827CD3B80C9>) |
| Intel      | Core i7-7700HQ                   | 2.80 | 588   | [24BB5C2F2D02](<Notebook/ASUSTek Computer/GL553/GL553VD/24BB5C2F2D02>) |
| Intel      | Core i5-6200U                    | 2.30 | 588   | [F7400FEAE6C3](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G3/F7400FEAE6C3>) |
| AMD        | Ryzen 7 3700X 8-Core             |      | 583   | [FFA4C14AE125](<Desktop/MSI/MS-7/MS-7C94/FFA4C14AE125>) |
| Intel      | 12th Gen Core i7-12700H          |      | 557   | [C8E8AFA7806B](<Notebook/Lenovo/IdeaPad/IdeaPad 5 14IAL7 82SD/C8E8AFA7806B>) |
| Intel      | Core i7-7500U                    | 2.70 | 524   | [69F03FF97A26](<Notebook/Dell/Inspiron/Inspiron 17-7779/69F03FF97A26>) |
| Intel      | Core i5-8265U                    | 1.60 | 497   | [BA15845847B8](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2001YUS/BA15845847B8>) |
| Intel      | 11th Gen Core i7-11850H          | 2.50 | 493   | [6CE0A379241E](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 17-ck0xxx/6CE0A379241E>) |
| Intel      | Core i7-8565U                    | 1.80 | 488   | [CBEBA031D0F3](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G6/CBEBA031D0F3>) |
| Intel      | Celeron N2840                    | 2.16 | 485   | [EB99CDE14AB4](<Notebook/ASUSTek Computer/X553/X553MA/EB99CDE14AB4>) |
| Intel      | Core i5-3470                     | 3.20 | 475   | [68BB5ECA2E65](<Desktop/Dell/OptiPlex/OptiPlex 7010/68BB5ECA2E65>) |
| Intel      | Core i5-2520M                    | 2.50 | 474   | [F59E9D5E4D8C](<Notebook/Dell/Latitude/Latitude E6320/F59E9D5E4D8C>) |
| Intel      | Core i7-10750H                   | 2.60 | 458   | [8A83519658C8](<Notebook/MSI/GF75/GF75 Thin 10UEK/8A83519658C8>) |
| Intel      | Core i5-5200U                    | 2.20 | 452   | [45CC6121C541](<Notebook/Hewlett-Packard/Pavilion/Pavilion Notebook/45CC6121C541>) |
| Intel      | Core i5-3230M                    | 2.60 | 439   | [78106D700829](<Notebook/Acer/Aspire/Aspire E1-571/78106D700829>) |
| Intel      | Core i5-3320M                    | 2.60 | 436   | [80FF86FE6AC7](<Notebook/Lenovo/ThinkPad/ThinkPad T430s 235368U/80FF86FE6AC7>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 418   | [AEF5125E12BA](<Desktop/Hewlett-Packard/Compaq/Compaq dc7900 Small Form Factor/AEF5125E12BA>) |
| Intel      | Core i7-3770                     | 3.40 | 402   | [8C4BA069ADF8](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH Z77/8C4BA069ADF8>) |
| AMD        | Ryzen 5 2600 Six-Core            |      | 396   | [298F9834E307](<Desktop/CSL-Computer/A/A0000001/298F9834E307>) |
| AMD        | Ryzen 7 4700U with Radeon Gra... |      | 396   | [5979766DA5FA](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15-ee0xxx/5979766DA5FA>) |
| Intel      | Core i5-4210U                    | 1.70 | 396   | [BFDFDD92DE8A](<Notebook/Acer/Aspire/Aspire E5-571G/BFDFDD92DE8A>) |
| Intel      | Atom x5-Z8350                    | 1.44 | 393   | [F2E11AF892C4](<Notebook/Positivo/CHT14/CHT14B/F2E11AF892C4>) |
| Intel      | Core i7-8565U                    | 1.80 | 392   | [6D96B300DA6C](<Notebook/TUXEDO/Others/Others/6D96B300DA6C>) |
| Intel      | Core i7-6700HQ                   | 2.60 | 385   | [AB8AEB132E69](<Notebook/Alienware/15/15 R3/AB8AEB132E69>) |
| Intel      | Core i5-2400                     | 3.10 | 379   | [90A5DDFE18F3](<Desktop/Lenovo/ThinkCentre/ThinkCentre M91 4518E4S/90A5DDFE18F3>) |
| Intel      | Core i5-2410M                    | 2.30 | 376   | [2CAA09DC28F0](<Notebook/Hewlett-Packard/ProBook/ProBook 6460b/2CAA09DC28F0>) |
| AMD        | FX -6300 Six-Core                |      | 374   | [E34B94A1BD83](<Desktop/MSI/MS/MS-7641/E34B94A1BD83>) |
| Intel      | Core i3-2120                     | 3.30 | 374   | [789B55394748](<Desktop/ASRock/Z77/Z77 Pro3/789B55394748>) |
| Intel      | Core i5-6300U                    | 2.40 | 372   | [414397FA3DF7](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FMS1GX0C/414397FA3DF7>) |
| AMD        | Ryzen 7 4800H with Radeon Gra... |      | 371   | [4EB353B4C60D](<Notebook/Lenovo/Legion/Legion 5 15ARH05H 82B1/4EB353B4C60D>) |
| AMD        | Ryzen 5 5500U with Radeon Gra... |      | 369   | [7675A6D4AB24](<Notebook/Acer/Aspire/Aspire A515-45/7675A6D4AB24>) |
| AMD        | FX-8350 Eight-Core               |      | 367   | [46A79944CC96](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX R2.0/46A79944CC96>) |
| Intel      | Core i5-1035G1                   | 1.00 | 365   | [1BD772748699](<Notebook/Lenovo/IdeaPad/IdeaPad S340-15IIL 81VW/1BD772748699>) |
| AMD        | Ryzen 9 3900X 12-Core            |      | 364   | [750B8F8B60FE](<Desktop/ASRock/B450M/B450M Pro4-F R2.0/750B8F8B60FE>) |
| Intel      | Core i5-2450M                    | 2.50 | 363   | [D313F7D98EDE](<Notebook/Acer/Aspire/Aspire 7750G/D313F7D98EDE>) |
| AMD        | Ryzen 5 4500U with Radeon Gra... |      | 358   | [D0884E9D2DE7](<Notebook/Lenovo/ThinkBook/ThinkBook 15 G2 ARE 20VG/D0884E9D2DE7>) |
| Intel      | Core i7-1065G7                   | 1.30 | 347   | [8889C0E9C03C](<Notebook/Dell/Inspiron/Inspiron 3793/8889C0E9C03C>) |
| AMD        | Ryzen 7 2700X Eight-Core         |      | 335   | [92A8E62FD610](<Desktop/Gigabyte Technology/B450M/B450M DS3H V2/92A8E62FD610>) |
| Intel      | Core 2 Duo P7450                 | 2.13 | 334   | [172E05E8B466](<Notebook/Apple/MacBook5/MacBook5,2/172E05E8B466>) |
| Intel      | Core i5-8265U                    | 1.60 | 332   | [E0AC4EFBECDA](<Notebook/HUAWEI/WRT-WX/WRT-WX9/E0AC4EFBECDA>) |
| Intel      | Core i5-4200U                    | 1.60 | 329   | [C3B2D6DEC6A5](<Desktop/AOpen/WB/WB5200/C3B2D6DEC6A5>) |
| Intel      | Celeron N3060                    | 1.60 | 329   | [C17C1877DA77](<Notebook/Hewlett-Packard/Stream/Stream Laptop 14-ax0XX/C17C1877DA77>) |
| AMD        | Ryzen 7 5800H with Radeon Gra... |      | 327   | [4C28FBE6911E](<Notebook/Lenovo/IdeaPad/IdeaPad 5 Pro 16ACH6 82L5/4C28FBE6911E>) |
| Intel      | Core i7-4790                     | 3.60 | 326   | [43A49BCC58C2](<Desktop/Gigabyte Technology/H87/H87M-HD3/43A49BCC58C2>) |
| AMD        | Ryzen 7 5700U with Radeon Gra... |      | 325   | [D33BBF7B9C9D](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ALC7 82R9/D33BBF7B9C9D>) |
| Intel      | 11th Gen Core i7-11700           | 2.50 | 325   | [C73CA3A43AC1](<Desktop/MSI/MS-7/MS-7D15/C73CA3A43AC1>) |
| Intel      | Core i3-6006U                    | 2.00 | 323   | [16D2C114BAD5](<Notebook/ASUSTek Computer/VivoBook/VivoBook 15_ASUS Laptop X540UB/16D2C114BAD5>) |
| Intel      | Core i3-3110M                    | 2.40 | 322   | [EDC1EC50AB33](<Notebook/Lenovo/B590/B590 20208/EDC1EC50AB33>) |
| Intel      | Core 2 Duo E7500                 | 2.93 | 310   | [B09B293AF277](<Desktop/Gigabyte Technology/G41/G41M-ES2L/B09B293AF277>) |
| Intel      | Core i3-2100                     | 3.10 | 308   | [3BAB3FE2FAAA](<Desktop/MSI/MS/MS-7676/3BAB3FE2FAAA>) |
| Intel      | Core i3-2350M                    | 2.30 | 307   | [19EF00784453](<Notebook/Medion/P/P6634/19EF00784453>) |
| Intel      | Core i7-6500U                    | 2.50 | 306   | [5F38F37F57B7](<Notebook/ASUSTek Computer/K501/K501UW/5F38F37F57B7>) |
| Intel      | Core i3-5005U                    | 2.00 | 305   | [D7E710F7FDB7](<Notebook/Hewlett-Packard/Notebook/Notebook/D7E710F7FDB7>) |
| Intel      | Core 2 Quad Q6600                | 2.40 | 298   | [A3BA6198939B](<Desktop/Dell/Studio/Studio 540/A3BA6198939B>) |
| Intel      | Core i5-2430M                    | 2.40 | 298   | [7DF18AFE7B73](<Notebook/Dell/System/System XPS L702X/7DF18AFE7B73>) |
| Intel      | Core i3-3220                     | 3.30 | 296   | [3173DD855FA6](<Desktop/ASUSTek Computer/P8/P8B75-V/3173DD855FA6>) |
| Intel      | Core i7-2600                     | 3.40 | 291   | [293B762E7CD7](<Desktop/ASUSTek Computer/P8/P8H67-M/293B762E7CD7>) |
| Intel      | Core i3-2310M                    | 2.10 | 288   | [40907C0859B5](<Notebook/Medion/E/E7220/40907C0859B5>) |
| Intel      | 12th Gen Core i9-12900K          |      | 282   | [6FDB2DE8CFBF](<Desktop/ASUSTek Computer/ProArt/ProArt Z690-CREATOR WIFI/6FDB2DE8CFBF>) |
| AMD        | Ryzen 5 5600X 6-Core             |      | 275   | [7852C4598C6A](<Desktop/Gigabyte Technology/B550/B550 AORUS PRO AC/7852C4598C6A>) |
| Intel      | Core i5-6500                     | 3.20 | 274   | [405A568E5493](<Desktop/MSI/MS-7/MS-7A64/405A568E5493>) |
| Intel      | Celeron N3350                    | 1.10 | 270   | [D0D96C8EED3E](<Notebook/Google/Robo/Robo/D0D96C8EED3E>) |
| Intel      | Core i3 M 370                    | 2.40 | 269   | [D691423E0DAD](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537CS0/D691423E0DAD>) |
| Intel      | Core i5-4460                     | 3.20 | 269   | [B801E1EB0466](<Desktop/ASUSTek Computer/All/All Series/B801E1EB0466>) |
| Intel      | Celeron N4020                    | 1.10 | 266   | [C4CBA76C3D30](<Notebook/Lenovo/IdeaPad/IdeaPad 1 14IGL7 82V6/C4CBA76C3D30>) |
| Intel      | Core i5-5300U                    | 2.30 | 266   | [551233FA35E3](<Notebook/Dell/Latitude/Latitude E5450/551233FA35E3>) |
| Intel      | Atom N270                        | 1.60 | 259   | [5C21ED840185](<Notebook/Intel/Calistoga/Calistoga & ICH7M Chipset/5C21ED840185>) |
| Intel      | Core i5-8300H                    | 2.30 | 257   | [06BBB615CF62](<Notebook/Dell/G3/G3 3779/06BBB615CF62>) |
| Intel      | Core i3 M 380                    | 2.53 | 256   | [72C64637E292](<Notebook/Acer/Aspire/Aspire 5742G/72C64637E292>) |
| AMD        | Ryzen 5 2500U with Radeon Veg... |      | 254   | [F42D6DACF167](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ag0xxx/F42D6DACF167>) |
| Intel      | Pentium Silver N6000             | 1.10 | 254   | [C940BE7D5C44](<Notebook/Chuwi/GemiBook/GemiBook Pro/C940BE7D5C44>) |
| Intel      | Pentium B960                     | 2.20 | 254   | [19B948417345](<Notebook/Dell/Inspiron/Inspiron N4050/19B948417345>) |
| Intel      | Core i7-6700K                    | 4.00 | 252   | [D90A406CB2A6](<Desktop/Gigabyte Technology/Z170/Z170XP-SLI/D90A406CB2A6>) |
| Intel      | Core i5-4570                     | 3.20 | 251   | [1301F2FACA03](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/1301F2FACA03>) |
| Intel      | Core i7-8650U                    | 1.90 | 245   | [8F249F8C2356](<Notebook/Dell/Latitude/Latitude 7490/8F249F8C2356>) |
| Intel      | Core i7-3630QM                   | 2.40 | 245   | [35F38F9FD769](<Notebook/ASUSTek Computer/N76/N76VZ/35F38F9FD769>) |
| AMD        | Ryzen 5 4600H with Radeon Gra... |      | 243   | [A3DD93D9B859](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/A3DD93D9B859>) |
| Intel      | Core i5-4300U                    | 1.90 | 241   | [387DA1C9A615](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AMS0RR00/387DA1C9A615>) |
| Intel      | Core i7-6700                     | 3.40 | 241   | [A4BDAD04F25E](<Desktop/Hewlett-Packard/860/860-014/A4BDAD04F25E>) |
| Intel      | Core i7-2670QM                   | 2.20 | 239   | [48C48CE24154](<Notebook/Others/Others/Others/48C48CE24154>) |
| Intel      | Atom N450                        | 1.66 | 236   | [AE6E7A450EF4](<Notebook/Acer/AOD/AOD255/AE6E7A450EF4>) |
| Intel      | Core i7-4770                     | 3.40 | 231   | [02D2AE60AFD8](<Desktop/MSI/MS/MS-7922/02D2AE60AFD8>) |
| AMD        | E-450 APU with Radeon HD Grap... |      | 229   | [6D04A7D2E14D](<Notebook/Hewlett-Packard/635/635/6D04A7D2E14D>) |
| AMD        | Ryzen 7 3700U with Radeon Veg... |      | 229   | [E0325F9B0934](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ADA05 81W1/E0325F9B0934>) |
| AMD        | Ryzen 7 PRO 4750U with Radeon... |      | 228   | [78CB2C557CE0](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UD006BGE/78CB2C557CE0>) |
| AMD        | Ryzen 5 1600 Six-Core            |      | 227   | [6031864F7E84](<Desktop/MSI/MS-7/MS-7A34/6031864F7E84>) |
| AMD        | Ryzen 3 2200G with Radeon Veg... |      | 226   | [DF568E4EF2BA](<Desktop/Gigabyte Technology/A320M-S2H/A320M-S2H V2/DF568E4EF2BA>) |
| Intel      | Core i7-6600U                    | 2.60 | 224   | [14C7710D041F](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/14C7710D041F>) |
| Intel      | Core i7-5500U                    | 2.40 | 222   | [6B294E83122F](<Notebook/Hewlett-Packard/ENVY/ENVY 15/6B294E83122F>) |
| AMD        | Ryzen 5 3400G with Radeon Veg... |      | 221   | [657F7C654B00](<Desktop/MSI/MS-7/MS-7B86/657F7C654B00>) |
| Intel      | Core i3-3217U                    | 1.80 | 217   | [F2FF30739026](<Notebook/ASUSTek Computer/X550/X550CL/F2FF30739026>) |
| Intel      | Core i5-4590                     | 3.30 | 215   | [D2DC450B4349](<Desktop/Dell/OptiPlex/OptiPlex 9020/D2DC450B4349>) |
| Intel      | Core i7-4790K                    | 4.00 | 215   | [6C891C8585EF](<Desktop/MSI/MS/MS-7917/6C891C8585EF>) |
| Intel      | Core i7-8700                     | 3.20 | 214   | [5E4C54F510D9](<Desktop/ASUSTek Computer/TUF/TUF B360-PLUS GAMING/5E4C54F510D9>) |
| Intel      | Core i5-7400                     | 3.00 | 210   | [87B5E6EFECC5](<All In One/Apple/iMac18/iMac18,2/87B5E6EFECC5>) |
| Intel      | Core i5-3570K                    | 3.40 | 205   | [AED95066DC81](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/AED95066DC81>) |
| Intel      | Core i5-8400                     | 2.80 | 202   | [8BB9FDEABD15](<Desktop/MSI/B360/B360 Gaming Aegis 3 8/8BB9FDEABD15>) |
| Intel      | Core i3-4005U                    | 1.70 | 201   | [FFC152AAB8BE](<Notebook/Acer/Aspire/Aspire E5-771/FFC152AAB8BE>) |
| Intel      | Core i7-8665U                    | 1.90 | 200   | [E180419888FC](<Notebook/Dell/Latitude/Latitude 5300/E180419888FC>) |
| Intel      | Core i7-3770K                    | 3.50 | 200   | [1BDBC84877C6](<Desktop/ASRock/Z77/Z77 Extreme6/1BDBC84877C6>) |
| Intel      | Core i5-5250U                    | 1.60 | 200   | [BEFE8469A672](<Notebook/Apple/MacBookAir7/MacBookAir7,2/BEFE8469A672>) |
| Intel      | Celeron N3050                    | 1.60 | 200   | [3ABBCA728E02](<Desktop/Acer/Revo/Revo M1-601/3ABBCA728E02>) |
| Intel      | Core i3-2330M                    | 2.20 | 198   | [B0043AF25190](<Notebook/ASUSTek Computer/K53/K53SC/B0043AF25190>) |
| Intel      | Core i5-3337U                    | 1.80 | 196   | [67B1ACAFCC2D](<Notebook/MobileDemand/xTablet/xTablet T1200/67B1ACAFCC2D>) |
| AMD        | Ryzen 5 5600G with Radeon Gra... |      | 194   | [248B1E3ECDC1](<Desktop/MSI/MS-7/MS-7C92/248B1E3ECDC1>) |
| Intel      | Celeron N4000                    | 1.10 | 194   | [3581881FD400](<Notebook/Haier/A1410/A1410ED/3581881FD400>) |
| AMD        | Athlon II X2 250                 |      | 193   | [295E08E13748](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/295E08E13748>) |
| Intel      | Core i7-7700K                    | 4.20 | 193   | [FC5B108CD74D](<Desktop/MSI/MS-7/MS-7A68/FC5B108CD74D>) |
| Intel      | Pentium Dual-Core T4500          | 2.30 | 192   | [954B2DC792ED](<Desktop/Medion/P961/P961x/954B2DC792ED>) |
| AMD        | Ryzen 7 5800X 8-Core             |      | 191   | [7CBBE9952420](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-A GAMING/7CBBE9952420>) |
| Intel      | Pentium Dual-Core E5300          | 2.60 | 191   | [3066EE449489](<Desktop/Biostar/G41/G41-M7/3066EE449489>) |
| AMD        | FX-8320 Eight-Core               |      | 190   | [6582E001E020](<Desktop/MSI/MS/MS-7693/6582E001E020>) |
| AMD        | Ryzen 7 2700 Eight-Core          |      | 190   | [B14FC569F9D7](<Desktop/MSI/MS-7/MS-7B86/B14FC569F9D7>) |
| Intel      | Core i7-8700K                    | 3.70 | 189   | [4C1AB2E04C1F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-F GAMING/4C1AB2E04C1F>) |
| Intel      | Core i7-7700                     | 3.60 | 187   | [E14B1D4DEDAC](<Desktop/ASUSTek Computer/H110/H110M-A-M.2/E14B1D4DEDAC>) |
| Intel      | Core i5-2500K                    | 3.30 | 187   | [12A87CC42228](<Desktop/Gigabyte Technology/Z68/Z68X-UD3H-B3/12A87CC42228>) |
| Intel      | Core i5-8350U                    | 1.70 | 186   | [FE0C09BB867F](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L6S8B500/FE0C09BB867F>) |
| Intel      | Core i5-3570                     | 3.40 | 185   | [6E2A863662CA](<Desktop/Huanan/B75/B75 V10.1 376/6E2A863662CA>) |
| Intel      | Core i7-4510U                    | 2.00 | 185   | [03BEDFB2837C](<Notebook/Lenovo/Z50-70/Z50-70 20354/03BEDFB2837C>) |
| Intel      | Core i3-4130                     | 3.40 | 184   | [A1DE5102E68C](<Desktop/MSI/MS/MS-7821/A1DE5102E68C>) |
| Intel      | Atom N455                        | 1.66 | 183   | [AE9330768475](<Notebook/Packard Bell/DOT/DOT S/AE9330768475>) |
| Intel      | Core i3-6100                     | 3.70 | 183   | [CAD45A6B0996](<Desktop/ASUSTek Computer/H110/H110M-R/CAD45A6B0996>) |
| Intel      | Core i5-9300H                    | 2.40 | 180   | [697E85CD8F44](<Notebook/Dell/G3/G3 3590/697E85CD8F44>) |
| AMD        | Ryzen 7 1700 Eight-Core          |      | 179   | [386071DA0D0C](<Desktop/ASRock/X370/X370 Gaming X/386071DA0D0C>) |
| Intel      | Core i7-2630QM                   | 2.00 | 179   | [D85DB39D5437](<Notebook/Toshiba/Satellite/Satellite L735/D85DB39D5437>) |
| AMD        | Ryzen 5 3600X 6-Core             |      | 178   | [64BD08958A9D](<Desktop/ASUSTek Computer/TUF/TUF B450M-PRO GAMING/64BD08958A9D>) |
| Intel      | Core i3-7100U                    | 2.40 | 177   | [9FF202ED96DA](<Mini Pc/Intel/NUC7/NUC7i3BNH/9FF202ED96DA>) |
| Intel      | Core i3-3120M                    | 2.50 | 177   | [4EEE2FC7E4D8](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23066RC/4EEE2FC7E4D8>) |
| Intel      | Core i7-4700MQ                   | 2.40 | 177   | [A84000D050D2](<Notebook/Hewlett-Packard/ENVY/ENVY 15/A84000D050D2>) |
| AMD        | Ryzen 9 5900X 12-Core            |      | 176   | [4FA7A06C1247](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PRO/4FA7A06C1247>) |
| Intel      | Pentium 2020M                    | 2.40 | 175   | [09EDACCD6C35](<Notebook/Toshiba/Satellite/Satellite C70-A/09EDACCD6C35>) |
| Intel      | Core i5-2500                     | 3.30 | 174   | [1EF3D6FF1AB5](<Desktop/Acer/Veriton/Veriton M4610G/1EF3D6FF1AB5>) |
| AMD        | Ryzen 3 3200G with Radeon Veg... |      | 172   | [79834B9B84B7](<Desktop/Biostar/B450/B450MH/79834B9B84B7>) |
| Intel      | Core 2 Duo P8600                 | 2.40 | 170   | [EEBAF731F975](<Notebook/Dell/Studio/Studio XPS 1640/EEBAF731F975>) |
| Intel      | Core i7-2600K                    | 3.40 | 170   | [B40BEBC12839](<Desktop/ASUSTek Computer/P8P67/P8P67 WS REVOLUTION/B40BEBC12839>) |
| Intel      | Core i5-4200M                    | 2.50 | 170   | [63939D023E34](<Notebook/Notebook/W35/W35xSTQ_370ST/63939D023E34>) |
| Intel      | Core i7-4500U                    | 1.80 | 170   | [88E43438D43C](<Notebook/Dell/Inspiron/Inspiron 5737/88E43438D43C>) |
| AMD        | FX -4300 Quad-Core               |      | 169   | [8A543FC1B8A4](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/8A543FC1B8A4>) |
| AMD        | Ryzen 5 2400G with Radeon Veg... |      | 169   | [4E093131D6EB](<Desktop/ASUSTek Computer/ROG/ROG STRIX B350-F GAMING/4E093131D6EB>) |
| Intel      | Core i5-10300H                   | 2.50 | 169   | [C1910C9A6514](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming F15 FX506LH_FX506LH/C1910C9A6514>) |
| Intel      | Pentium Dual-Core T4300          | 2.10 | 167   | [6CBC12B1D864](<Notebook/MSI/CX/CX600/6CBC12B1D864>) |
| Intel      | Core i7-3610QM                   | 2.30 | 167   | [5649042F3794](<Notebook/Lenovo/IdeaPad/IdeaPad Y580/5649042F3794>) |
| AMD        | Ryzen 5 2600X Six-Core           |      | 166   | [8A12F6F00B35](<Desktop/MSI/MS-7/MS-7B79/8A12F6F00B35>) |
| Intel      | Pentium Dual-Core E5700          | 3.00 | 164   | [3D03913555EA](<Desktop/Acer/Aspire/Aspire X3910/3D03913555EA>) |
| Intel      | Core i5 M 460                    | 2.53 | 164   | [9B9CF6F55CD7](<Notebook/ASUSTek Computer/K52/K52F/9B9CF6F55CD7>) |
| Intel      | Atom N2600                       | 1.60 | 164   | [D744EC860194](<Notebook/Packard Bell/DOT/DOT S/D744EC860194>) |
| Intel      | Core i3-1005G1                   | 1.20 | 163   | [11883274E416](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X515JA_X515JA/11883274E416>) |
| Intel      | Core i5-6400                     | 2.70 | 161   | [6E8CFF2494E9](<Desktop/MSI/MS/MS-7971/6E8CFF2494E9>) |
| Intel      | Core i5 M 520                    | 2.40 | 160   | [1A91C1BDDE7A](<Notebook/Lenovo/ThinkPad/ThinkPad T410 25376B8/1A91C1BDDE7A>) |
| Intel      | Core 2 Duo E6550                 | 2.33 | 159   | [8FC362E5299E](<Desktop/Gigabyte Technology/P35/P35-DS3/8FC362E5299E>) |
| Intel      | Core i5-7300HQ                   | 2.50 | 159   | [0F8385CFAEBE](<Notebook/ASUSTek Computer/GL703/GL703VD/0F8385CFAEBE>) |
| AMD        | Ryzen 9 5900HX with Radeon Gr... |      | 158   | [934E05EB73BF](<Notebook/SLIMBOOK/TITAN/TITAN/934E05EB73BF>) |
| Intel      | Celeron 2955U                    | 1.40 | 158   | [6512788EBC6F](<Notebook/Google/Peppy/Peppy/6512788EBC6F>) |
| Intel      | Core i5-7300U                    | 2.60 | 156   | [2B677D343A47](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G5/2B677D343A47>) |
| Intel      | Pentium Dual-Core T4400          | 2.20 | 156   | [95AA8AF6CBD5](<Notebook/Samsung Electronics/R530/R530-R730/95AA8AF6CBD5>) |
| Intel      | Core i5-3317U                    | 1.70 | 156   | [92598272883E](<Notebook/Apple/MacBookAir5/MacBookAir5,2/92598272883E>) |
| Intel      | Core i3-6100U                    | 2.30 | 156   | [B0E8E1BF8A5F](<Notebook/Dell/Inspiron/Inspiron 13-5368/B0E8E1BF8A5F>) |
| Intel      | Core 2 T7200                     | 2.00 | 155   | [835E1A017EC4](<Notebook/Lenovo/ThinkPad/ThinkPad T60 8744HDG/835E1A017EC4>) |
| Intel      | 12th Gen Core i5-1235U           |      | 155   | [D804077E8E8E](<Notebook/Hewlett-Packard/ENVY/ENVY Laptop 17-cr0xxx/D804077E8E8E>) |
| Intel      | Pentium N3540                    | 2.16 | 155   | [C9B36EC058BE](<Notebook/Hewlett-Packard/14/14/C9B36EC058BE>) |
| AMD        | Ryzen 7 3800X 8-Core             |      | 154   | [2B248EDDF6A7](<Desktop/MSI/MS-7/MS-7A32/2B248EDDF6A7>) |
| AMD        | Ryzen 5 5600H with Radeon Gra... |      | 154   | [743907C28449](<Convertible/ASUSTek Computer/Zenbook/Zenbook UN5401QAB_UN5401QA/743907C28449>) |
| Intel      | Celeron J4125                    | 2.00 | 154   | [ADB893E07ACF](<Desktop/LTD Delovoy Office/311/311/ADB893E07ACF>) |
| Intel      | Atom Z3735F                      | 1.33 | 154   | [F88C5A9F9C20](<Notebook/Linx/LINX1010/LINX1010B/F88C5A9F9C20>) |
| Intel      | Core i7-4600U                    | 2.10 | 154   | [8BFEAC5DB3B4](<Notebook/Dell/Latitude/Latitude E7240/8BFEAC5DB3B4>) |
| Intel      | Core i3-3240                     | 3.40 | 153   | [D5B0F9D722D1](<Desktop/Intel/H/H61/D5B0F9D722D1>) |
| AMD        | Ryzen 9 5950X 16-Core            |      | 152   | [88E3C40315C8](<Desktop/MSI/MS-7/MS-7C37/88E3C40315C8>) |
| Intel      | Pentium G4400                    | 3.30 | 152   | [2C753108A135](<Desktop/MSI/MS/MS-7996/2C753108A135>) |
| AMD        | Ryzen 7 5700G with Radeon Gra... |      | 151   | [AD950AA73CDA](<Desktop/Gigabyte Technology/A520M/A520M DS3H/AD950AA73CDA>) |
| Intel      | Core i3-10110U                   | 2.10 | 150   | [D0A7B44DC4F8](<Notebook/Google/Dragonair/Dragonair/D0A7B44DC4F8>) |
| Intel      | Core i3-7100                     | 3.90 | 150   | [A65B4BC89A4A](<Desktop/ASRock/B250/B250M-HDV/A65B4BC89A4A>) |
| AMD        | Phenom II X4 965                 |      | 149   | [711353369BFE](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/711353369BFE>) |
| Intel      | Core i3 M 350                    | 2.27 | 147   | [D4BB7EE44FCD](<Notebook/Dell/Studio/Studio 1558/D4BB7EE44FCD>) |
| Intel      | Celeron N2830                    | 2.16 | 147   | [2F224AD5326A](<Notebook/Hewlett-Packard/240/240 G3/2F224AD5326A>) |
| AMD        | Ryzen 5 3550H with Radeon Veg... |      | 146   | [0D453998F2D1](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec0xxx/0D453998F2D1>) |
| Intel      | Pentium N3700                    | 1.60 | 146   | [02CEB250CB89](<Notebook/ASUSTek Computer/X553/X553SA/02CEB250CB89>) |
| Intel      | Core i3 M 330                    | 2.13 | 145   | [730A5F5C7255](<Notebook/Toshiba/Satellite/Satellite L650/730A5F5C7255>) |
| Intel      | Core i5 M 480                    | 2.67 | 145   | [534528DAD72C](<Notebook/Samsung Electronics/Q/Q330/534528DAD72C>) |
| Intel      | Core i5-2540M                    | 2.60 | 145   | [9CF5FCEF24D5](<Notebook/Lenovo/ThinkPad/ThinkPad T520 4243WRK/9CF5FCEF24D5>) |
| AMD        | Phenom II X4 955                 |      | 142   | [154E1A7936A6](<Desktop/Gigabyte Technology/GA-880/GA-880GMA-USB3/154E1A7936A6>) |
| AMD        | E-350                            |      | 142   | [60B9042EC3D2](<Notebook/ASUSTek Computer/1215/1215B/60B9042EC3D2>) |
| Intel      | Core 2 Duo P8400                 | 2.26 | 140   | [CA0BD1B18860](<Notebook/Hewlett-Packard/Compaq/Compaq Presario CQ70/CA0BD1B18860>) |
| Intel      | Core 2 Duo P8700                 | 2.53 | 139   | [B58147ED699A](<Notebook/Apple/MacBookPro5/MacBookPro5,4/B58147ED699A>) |
| Intel      | Pentium M processor              | 1.20 | 138   | [A6C6FCC9536B](<Notebook/IBM/ThinkPad/ThinkPad T43 18714AG/A6C6FCC9536B>) |
| Intel      | Core i3-8100                     | 3.60 | 138   | [8DB0E21BB512](<Desktop/CSL-Computer/A/A0000001/8DB0E21BB512>) |
| Intel      | Core i7-10710U                   | 1.10 | 138   | [F5D34816D4F0](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/F5D34816D4F0>) |
| Intel      | Core i5-10400                    | 2.90 | 137   | [DF0ED67418B3](<Desktop/Gigabyte Technology/H410M/H410M H V3/DF0ED67418B3>) |
| Intel      | Pentium Dual-Core T4200          | 2.00 | 137   | [30BF54237E47](<Notebook/Samsung Electronics/R519/R519-R719/30BF54237E47>) |
| Intel      | Core i5 M 560                    | 2.67 | 137   | [0AD9B9AE5413](<Notebook/Lenovo/ThinkPad/ThinkPad L512 4444PV3/0AD9B9AE5413>) |
| Intel      | Core i3-4160                     | 3.60 | 137   | [9E9D881DFE2E](<Desktop/Gigabyte Technology/H97/H97M-D3H/9E9D881DFE2E>) |
| Intel      | Core i3-8130U                    | 2.20 | 136   | [1705FE3734D4](<Notebook/Hewlett-Packard/Sona/Sona/1705FE3734D4>) |
| Intel      | Core i7-3632QM                   | 2.20 | 136   | [23CC5754D42D](<Notebook/Lenovo/ThinkPad/ThinkPad T530 2392AQU/23CC5754D42D>) |
| Intel      | Pentium N3710                    | 1.60 | 136   | [CC6A180592A6](<Notebook/Positivo/S14/S14BW01/CC6A180592A6>) |
| Intel      | Pentium Silver N5000             | 1.10 | 135   | [222540F56EB8](<Notebook/Dell/Latitude/Latitude 3190/222540F56EB8>) |
| Intel      | Core i5-7500                     | 3.40 | 135   | [0CE87B97ADF2](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G4 SFF/0CE87B97ADF2>) |
| Intel      | Core i7-3520M                    | 2.90 | 134   | [C8D828336335](<Notebook/Lenovo/ThinkPad/ThinkPad T430s 23562Z3/C8D828336335>) |
| Intel      | Core i7-5600U                    | 2.60 | 134   | [D508D79E9BE1](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS1110E/D508D79E9BE1>) |
| Intel      | Core i5-9400F                    | 2.90 | 133   | [7A7B5D889373](<Desktop/MSI/MS-7/MS-7C09/7A7B5D889373>) |
| Intel      | Pentium G630                     | 2.70 | 133   | [EA6EAE3BAF0B](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS/EA6EAE3BAF0B>) |
| Intel      | Core i5-4440                     | 3.10 | 133   | [EA550A423986](<Desktop/Intel/DB85FL/DB85FL AAG89861-203/EA550A423986>) |
| Intel      | Core 2 Duo E4500                 | 2.20 | 131   | [022BD9DB6705](<Desktop/ECS/G31/G31T-M9/022BD9DB6705>) |
| Intel      | Core 2 Duo E7400                 | 2.80 | 131   | [A233E4C407C6](<Desktop/ASUSTek Computer/P5/P5KPL-CM/A233E4C407C6>) |
| Intel      | Core i5 750                      | 2.67 | 131   | [28576A387BF7](<Desktop/ASUSTek Computer/P7/P7H55-M/28576A387BF7>) |
| Intel      | Core i3-4030U                    | 1.90 | 131   | [08AFD1B0BD96](<Notebook/ASUSTek Computer/S551/S551LN/08AFD1B0BD96>) |
| Intel      | Core i7-6820HQ                   | 2.70 | 131   | [BD225591F5A9](<Notebook/Hewlett-Packard/ProBook/ProBook 650 G2/BD225591F5A9>) |
| AMD        | Ryzen 3 3200U with Radeon Veg... |      | 130   | [2A8869A419FF](<Notebook/Acer/Aspire/Aspire A515-43/2A8869A419FF>) |
| Intel      | Core 2 Duo E8500                 | 3.16 | 129   | [62C7C6EA68B6](<Desktop/Gigabyte Technology/G31/G31M-S2L/62C7C6EA68B6>) |
| Intel      | Core i5 M 430                    | 2.27 | 129   | [C4EC6CC0A05D](<Notebook/Hewlett-Packard/ProBook/ProBook 6440b/C4EC6CC0A05D>) |
| Intel      | Pentium P6200                    | 2.13 | 129   | [09508BF50867](<Notebook/Toshiba/Satellite/Satellite C660/09508BF50867>) |
| Intel      | Core i7-4710HQ                   | 2.50 | 129   | [087D0F8BF36E](<Notebook/Lenovo/Y50-70/Y50-70 20378/087D0F8BF36E>) |
| Intel      | Core i5-6600K                    | 3.50 | 129   | [16DFC314B4A7](<Desktop/MSI/MS-7/MS-7A11/16DFC314B4A7>) |
| Intel      | Pentium Dual-Core E5400          | 2.70 | 128   | [8CB11EEF7ABB](<Desktop/ASUSTek Computer/CM/CM5571/8CB11EEF7ABB>) |
| Intel      | Core i5-3330                     | 3.00 | 128   | [90B24BECC813](<Desktop/Dell/Inspiron/Inspiron 660/90B24BECC813>) |
| AMD        | E-300 APU with Radeon HD Grap... |      | 127   | [BF7446AAE452](<Notebook/Hewlett-Packard/Presario/Presario CQ57/BF7446AAE452>) |
| Intel      | Core i7-8850H                    | 2.60 | 127   | [806892A57543](<Notebook/Dell/Latitude/Latitude 5491/806892A57543>) |
| Intel      | Atom N570                        | 1.66 | 127   | [C4C0C672723E](<Notebook/ASUSTek Computer/1011/1011PX/C4C0C672723E>) |
| Intel      | Pentium G3220                    | 3.00 | 127   | [D4942DE9F18D](<Desktop/Dell/Inspiron/Inspiron 3647/D4942DE9F18D>) |
| Intel      | Pentium P6100                    | 2.00 | 125   | [E2A03E725B22](<Notebook/ASUSTek Computer/K52/K52F/E2A03E725B22>) |
| AMD        | A8-7410 APU with AMD Radeon R... |      | 123   | [7D22BE3D3CF2](<Notebook/Dell/Inspiron/Inspiron 5555/7D22BE3D3CF2>) |
| Intel      | Celeron N4100                    | 1.10 | 123   | [2D8BDFE0E9B2](<Convertible/Teclast/F/F5/2D8BDFE0E9B2>) |
| Intel      | Core i5-9400                     | 2.90 | 123   | [9A23611FAA1B](<Desktop/Gigabyte Technology/B360/B360M-DS3H/9A23611FAA1B>) |
| Intel      | Pentium N4200                    | 1.10 | 123   | [1CF9B9D6206E](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/1CF9B9D6206E>) |
| Intel      | Atom D525                        | 1.80 | 122   | [7E512C1A1497](<Desktop/Intel/D525MW/D525MW AAE93082-401/7E512C1A1497>) |
| Intel      | Pentium 4                        | 3.00 | 121   | [04FEFA1A5AA3](<Desktop/Hewlett-Packard/Compaq/Compaq dc7100 USDT/04FEFA1A5AA3>) |
| Intel      | Pentium 4                        | 3.20 | 121   | [53497F6DDB27](<Desktop/Dell/OptiPlex/OptiPlex GX520/53497F6DDB27>) |
| Intel      | Core 2 Duo T7500                 | 2.20 | 121   | [66306C6B6581](<Notebook/Hewlett-Packard/Compaq/Compaq 6510b/66306C6B6581>) |
| Intel      | Core i7-2677M                    | 1.80 | 121   | [9D66FDFD8ED4](<Notebook/ASUSTek Computer/UX31/UX31E/9D66FDFD8ED4>) |
| Intel      | Core i7-4770K                    | 3.50 | 121   | [8297C3BE8BFB](<Desktop/Gigabyte Technology/Z87/Z87-HD3/8297C3BE8BFB>) |
| Intel      | Core 2 Duo T8100                 | 2.10 | 120   | [D8EC87177B41](<Notebook/Dell/Vostro/Vostro 1510/D8EC87177B41>) |
| Intel      | Core i3 550                      | 3.20 | 120   | [DB6FB2F3DAF1](<Desktop/Hewlett-Packard/p6610/p6610it/DB6FB2F3DAF1>) |
| Intel      | Celeron N3450                    | 1.10 | 119   | [651D20597F8E](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/651D20597F8E>) |
| Intel      | Core 2 Duo T8300                 | 2.40 | 118   | [ABBAD64ECA84](<Notebook/Lenovo/ThinkPad/ThinkPad T61p 6457UN2/ABBAD64ECA84>) |
| Intel      | Core i3-2370M                    | 2.40 | 118   | [41422F3B2FC9](<Notebook/Hewlett-Packard/450/450/41422F3B2FC9>) |
| Intel      | Core i5-4690K                    | 3.50 | 118   | [739BAB2B884C](<Desktop/Hewlett-Packard/750/750-050xt/739BAB2B884C>) |
| Intel      | Pentium G620                     | 2.60 | 117   | [79CF60FEE4EB](<Desktop/Hewlett-Packard/Compaq/Compaq 6200 Pro SFF PC/79CF60FEE4EB>) |
| Intel      | Core 2 Duo E8400                 | 3.00 | 116   | [6A034D02984E](<Desktop/Gigabyte Technology/EP35/EP35-DS3L/6A034D02984E>) |
| AMD        | Athlon II X4 640                 |      | 115   | [96C1A1BCC8AB](<Desktop/ASRock/N68-GE3/N68-GE3 UCC/96C1A1BCC8AB>) |
| AMD        | Ryzen 9 3950X 16-Core            |      | 115   | [29C52425FF8B](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/29C52425FF8B>) |
| Intel      | Core i7-7600U                    | 2.80 | 115   | [381541B1222E](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20HN001NUS/381541B1222E>) |
| Intel      | Core 2 Duo T7250                 | 2.00 | 115   | [AB1D97149E6F](<Notebook/Hewlett-Packard/Compaq/Compaq 6820s/AB1D97149E6F>) |

### Memory

| MFG        | Name                         | Size     | Type | MT/s | Count | Report |
|------------|------------------------------|----------|------|------|-------|--------|
| Samsung    | M471A5244CB0-CTD SODIMM      | 4 GB     | DDR4 | 3266 | 913   | [D76D74ED9BB6](<Notebook/Hewlett-Packard/ENVY/ENVY Laptop 13-aq1xxx/D76D74ED9BB6>) |
| Samsung    | M471B5273DH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 894   | [AC4ED63C5B02](<Notebook/Samsung Electronics/530U3/530U3BI-530U4BI-530U4BH/AC4ED63C5B02>) |
| SK hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 | 2667 | 875   | [BDEB589C8B94](<Notebook/Dell/Inspiron/Inspiron 5575/BDEB589C8B94>) |
| Samsung    | M471B5173DB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 802   | [80FF86FE6AC7](<Notebook/Lenovo/ThinkPad/ThinkPad T430s 235368U/80FF86FE6AC7>) |
| Samsung    | M471B5173QH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 741   | [C4921D5766B3](<Notebook/Dell/Latitude/Latitude E7440/C4921D5766B3>) |
| Samsung    | M471A1G44AB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 731   | [66A4B1E48D59](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20S0000JGE/66A4B1E48D59>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 800  | 634   | [33330BA92CDF](<Desktop/ASUSTek Computer/P5/P5KPL-AM/33330BA92CDF>) |
| Samsung    | M471A5244CB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 620   | [32C7D9CEE612](<Convertible/Lenovo/Yoga/Yoga 720-12IKB 81B5/32C7D9CEE612>) |
|            | Module DIMM SDRAM            | 2048 MB  |      |      | 614   | [11978265EA1F](<Desktop/MSI/MS/MS-7383/11978265EA1F>) |
| Samsung    | M471B5273CH0-CH9 SODIMM      | 4 GB     | DDR3 | 1334 | 611   | [1D9B1E6CF3E5](<Notebook/Hewlett-Packard/G/G62/1D9B1E6CF3E5>) |
| Samsung    | M471B5173EB0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 610   | [02CEB250CB89](<Notebook/ASUSTek Computer/X553/X553SA/02CEB250CB89>) |
|            | 123456789012345678 SODIMM... | 2 GB     |      | 2400 | 587   | [E63A4A0E554B](<Notebook/Others/Others/Others/E63A4A0E554B>) |
|            | Module DIMM                  | 4096 MB  |      | 1333 | 568   | [2661C9C2DBA8](<Desktop/ASUSTek Computer/P6T/P6T SE/2661C9C2DBA8>) |
|            | Module DIMM                  | 2048 MB  |      | 800  | 567   | [F09DC01C74E1](<Desktop/Gigabyte Technology/EP45/EP45-UD3P/F09DC01C74E1>) |
| Samsung    | M471A1K43DB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 530   | [9177B2145423](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 15-eg0xxx/9177B2145423>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4096 MB  | DDR3 | 1600 | 523   | [387DA1C9A615](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AMS0RR00/387DA1C9A615>) |
|            | Module DIMM                  | 2048 MB  |      | 1333 | 514   | [E694BACCD996](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/E694BACCD996>) |
| Samsung    | M471A1K43CB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 500   | [DA67C3C0247F](<Notebook/Lenovo/ThinkPad/ThinkPad X270 20HN0015GE/DA67C3C0247F>) |
|            | Module DIMM SDRAM            | 1024 MB  |      |      | 491   | [CDCD847DC9C7](<Desktop/Others/865/865GV-ICH5/CDCD847DC9C7>) |
| Samsung    | M471A1K43CB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 489   | [6D96B300DA6C](<Notebook/TUXEDO/Others/Others/6D96B300DA6C>) |
| Samsung    | M471B5773CHS-CH9 SODIMM      | 2 GB     | DDR3 | 4199 | 456   | [F0A3574875E7](<Notebook/Samsung Electronics/RV419/RV419-RV420/F0A3574875E7>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 453   | [9BFEEDC7627F](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AWS0XX04/9BFEEDC7627F>) |
| Samsung    | M471B5773DH0-CH9 SODIMM      | 2 GB     | DDR3 | 1600 | 445   | [4EEE2FC7E4D8](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23066RC/4EEE2FC7E4D8>) |
| Samsung    | M471B5273DH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 443   | [8F7AF0214EED](<Notebook/Samsung Electronics/730U3/730U3E-740U3E/8F7AF0214EED>) |
| Samsung    | M471A1K43DB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 436   | [6A48296FAAF8](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S3UL00/6A48296FAAF8>) |
| Samsung    | M471B1G73DB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 435   | [6B294E83122F](<Notebook/Hewlett-Packard/ENVY/ENVY 15/6B294E83122F>) |
| Corsair    | CMK16GX4M2B3200C16 DIMM      | 8 GB     | DDR4 | 3600 | 418   | [E2EAAD29B2DA](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E2EAAD29B2DA>) |
| Micron     | 4ATF51264HZ-2G6E1 SODIMM     | 4 GB     | DDR4 | 2667 | 410   | [740512036BD3](<Notebook/Hewlett-Packard/Laptop/Laptop 15s-du3xxx/740512036BD3>) |
| Samsung    | M471B1G73QH0-YK0 SODIMM      | 8 GB     | DDR3 | 1867 | 392   | [6B294E83122F](<Notebook/Hewlett-Packard/ENVY/ENVY 15/6B294E83122F>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2667 | 387   | [BA398B6EF68D](<Desktop/Hardkernel/ODROID-H/ODROID-H2/BA398B6EF68D>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 800  | 379   | [FDAFBE27DB37](<Desktop/PCChips/P/P49G/FDAFBE27DB37>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 371   | [D7E710F7FDB7](<Notebook/Hewlett-Packard/Notebook/Notebook/D7E710F7FDB7>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 667  | 369   | [551969013650](<Notebook/Lenovo/ThinkPad/ThinkPad X61 Tablet 7767B8G/551969013650>) |
| Samsung    | M471A1K43BB1-CRC SODIMM      | 8 GB     | DDR4 | 2667 | 335   | [6212510F658C](<Notebook/MSI/GP73/GP73 Leopard 8RE/6212510F658C>) |
| Samsung    | M471A5244CB0-CWE SODIMM      | 4 GB     | DDR4 | 3200 | 330   | [D0884E9D2DE7](<Notebook/Lenovo/ThinkBook/ThinkBook 15 G2 ARE 20VG/D0884E9D2DE7>) |
| SK hynix   | HMA81GS6CJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 329   | [FE0C09BB867F](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L6S8B500/FE0C09BB867F>) |
| Samsung    | M471A1G44AB0-CWE Row Of C... | 8 GB     | DDR4 | 3200 | 322   | [C5B4D2A705BB](<Notebook/Timi/RedmiBook/RedmiBook Pro 14S/C5B4D2A705BB>) |
| SK hynix   | HMA81GS6JJR8N-VK SODIMM      | 8 GB     | DDR4 | 2667 | 314   | [DDF7B2F2594F](<Notebook/ASUSTek Computer/ROG/ROG Strix G731GU_G731GU/DDF7B2F2594F>) |
|            | Module SODIMM                | 2048 MB  | DDR2 |      | 304   | [13BAB46EEF6F](<Notebook/Sony/VGN-CS11/VGN-CS11Z_R/13BAB46EEF6F>) |
| Kingston   | KHX1600C9D3/4GX DIMM         | 4 GB     | DDR3 | 2400 | 302   | [B40BEBC12839](<Desktop/ASUSTek Computer/P8P67/P8P67 WS REVOLUTION/B40BEBC12839>) |
| Corsair    | CMK16GX4M2B3000C15 DIMM      | 8 GB     | DDR4 | 3200 | 301   | [76DF930A84BA](<Desktop/MSI/MS-7/MS-7B17/76DF930A84BA>) |
|            | Module DIMM                  | 1024 MB  |      | 800  | 297   | [379945E91382](<Desktop/Gigabyte Technology/G41/G41M-ES2L/379945E91382>) |
| Samsung    | M471B1G73EB0-YK0 SODIMM      | 8 GB     | DDR3 | 1600 | 295   | [60803812B02A](<Notebook/ASUSTek Computer/K501/K501UX/60803812B02A>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1333 | 293   | [FB41CB13C89A](<Desktop/Lenovo/ThinkCentre/ThinkCentre M72e 3655A79/FB41CB13C89A>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 667  | 292   | [EA4E28039693](<Desktop/ASUSTek Computer/V-M3/V-M3N8200/EA4E28039693>) |
| Micron     | 4ATF1G64HZ-3G2E1 SODIMM      | 8 GB     | DDR4 | 3200 | 289   | [992294E76777](<Notebook/Lenovo/ThinkPad/ThinkPad E15 Gen 3 20YG003VGE/992294E76777>) |
| Elpida     | EBJ41UF8BCS0-DJ-F SODIMM     | 4 GB     | DDR3 | 1334 | 281   | [4A51E6DF5493](<Notebook/Acer/AO/AO722/4A51E6DF5493>) |
| Kingston   | KHX1600C10D3/8G DIMM         | 8 GB     | DDR3 |      | 277   | [DAF55CF3270D](<Desktop/Intel/H/H61/DAF55CF3270D>) |
| SK hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 276   | [8BFEAC5DB3B4](<Notebook/Dell/Latitude/Latitude E7240/8BFEAC5DB3B4>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 667  | 273   | [E60161C9DB0C](<Desktop/ASUSTek Computer/M3/M3N78-VM/E60161C9DB0C>) |
| Micron     | 8ATF1G64HZ-3G2J1 SODIMM      | 8 GB     | DDR4 | 3200 | 269   | [383EAA281729](<Notebook/ASUSTek Computer/ROG/ROG Strix G512LI_G512LI/383EAA281729>) |
| Samsung    | M471A2K43DB1-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 268   | [A15A177EA238](<Notebook/Dell/Latitude/Latitude 5511/A15A177EA238>) |
| Samsung    | M471B5673FH0-CH9 SODIMM      | 2 GB     | DDR3 | 1334 | 267   | [AE2D05A38BCB](<Notebook/Dell/Latitude/Latitude E4200/AE2D05A38BCB>) |
|            | Module SODIMM                | 2 GB     | DDR2 | 667  | 264   | [ABBAD64ECA84](<Notebook/Lenovo/ThinkPad/ThinkPad T61p 6457UN2/ABBAD64ECA84>) |
| Samsung    | M471A1K43EB1-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 261   | [D804077E8E8E](<Notebook/Hewlett-Packard/ENVY/ENVY Laptop 17-cr0xxx/D804077E8E8E>) |
| Samsung    | M471A2K43CB1-CTD SODIMM      | 16 GB    | DDR4 | 8400 | 261   | [768B6692FB22](<Notebook/Hewlett-Packard/OMEN/OMEN by Laptop 15-dc0xxx/768B6692FB22>) |
| SK hynix   | Module SODIMM                | 1 GB     | DDR2 | 800  | 258   | [4D6A73FB0B2D](<Notebook/Apple/MacBook5/MacBook5,2/4D6A73FB0B2D>) |
| Micron     | 8KTF51264HZ-1G6E1 SODIMM     | 4 GB     | DDR3 | 1600 | 257   | [50735D38FB7C](<Notebook/Dell/Latitude/Latitude E6440/50735D38FB7C>) |
| SK hynix   | HMA41GS6AFR8N-TF SODIMM      | 8 GB     | DDR4 | 2667 | 255   | [0A14953B346E](<Desktop/Dell/OptiPlex/OptiPlex 3050/0A14953B346E>) |
| Micron     | 8ATF1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 253   | [CD804C87BD4C](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK U748/CD804C87BD4C>) |
|            | Module SODIMM                | 1024 MB  | DDR2 |      | 250   | [2C33BB3E93DC](<Notebook/Acer/TravelMate/TravelMate 3270/2C33BB3E93DC>) |
| Micron     | 4ATF51264HZ-3G2J1 SODIMM     | 4 GB     | DDR4 | 3200 | 243   | [505EA2D9F8FB](<Convertible/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop TP420IA_TM420IA/505EA2D9F8FB>) |
| Samsung    | M471B5673FH0-CF8 SODIMM      | 2 GB     | DDR3 | 1067 | 242   | [730A5F5C7255](<Notebook/Toshiba/Satellite/Satellite L650/730A5F5C7255>) |
| Micron     | 16KTF51264HZ-1G6M1 SODIMM    | 4 GB     | DDR3 | 1600 | 238   | [4AC455A1BD5F](<Desktop/Quanta/2AF5/2AF5 011/4AC455A1BD5F>) |
|            | Module SODIMM                | 4096 MB  | DDR3 |      | 237   | [4918FDDA4745](<Notebook/Sony/SVE1513/SVE1513C5E/4918FDDA4745>) |
|            | Module SODIMM                | 1024 MB  | DDR2 | 667  | 235   | [67D1EC71B6A1](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv9500/67D1EC71B6A1>) |
| Kingston   | KHX2666C16/8G DIMM           | 8192 MB  | DDR4 | 3466 | 233   | [EE0FD95D2764](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A/EE0FD95D2764>) |
|            | Module DIMM                  | 4 GB     |      | 1333 | 233   | [295E08E13748](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/295E08E13748>) |
|            | 123456789012345678 DIMM L... | 2 GB     |      | 2400 | 230   | [ADB893E07ACF](<Desktop/LTD Delovoy Office/311/311/ADB893E07ACF>) |
| Nanya      | NT2GC64B88B0NS-CG SODIMM     | 2 GB     | DDR3 | 1334 | 230   | [EF05D70BFFDF](<Notebook/Dell/Latitude/Latitude E6410/EF05D70BFFDF>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 227   | [7A99051E71A1](<Notebook/Hewlett-Packard/Laptop/Laptop 15-dw3xxx/7A99051E71A1>) |
|            | Module DIMM                  | 2 GB     | DDR2 | 800  | 218   | [146938264E3F](<Desktop/ASUSTek Computer/P5G41-M/P5G41-M LX/146938264E3F>) |
| Samsung    | M471A2K43CB1-CRC SODIMM      | 16 GB    | DDR4 | 2667 | 217   | [280C4727311C](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L6S3PV00/280C4727311C>) |
| G.Skill    | F4-3200C16-8GVKB DIMM        | 8 GB     | DDR4 | 3866 | 216   | [92E88E4B27A0](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-H GAMING/92E88E4B27A0>) |
| Micron     | 4ATF51264HZ-2G3B1 SODIMM     | 4 GB     | DDR4 | 2400 | 216   | [872A7CAC19EA](<Notebook/Acer/Aspire/Aspire A515-51/872A7CAC19EA>) |
|            | Module DIMM SDRAM            | 2 GB     |      |      | 214   | [5B364860F551](<Desktop/ASUSTek Computer/P5/P5GDC/5B364860F551>) |
|            | Module DIMM                  | 2048 MB  |      | 667  | 212   | [FF39EAFDF33C](<Desktop/Gigabyte Technology/G33/G33M-S2/FF39EAFDF33C>) |
| Kingston   | KHX3200C16D4/8GX DIMM        | 8 GB     | DDR4 | 3600 | 209   | [DC0340342D7F](<Desktop/MSI/MS-7/MS-7B84/DC0340342D7F>) |
|            | Module DIMM                  | 4096 MB  |      | 1600 | 209   | [1FBAF6BE6F36](<Desktop/ASUSTek Computer/M4A785TD-M/M4A785TD-M EVO/1FBAF6BE6F36>) |
| SK hynix   | H9CCNNNCLGALAR-NVD Row Of... | 8 GB     |      | 2133 | 208   | [51461F937E72](<Notebook/Dell/XPS/XPS 13 9380/51461F937E72>) |
| G.Skill    | F4-3200C16-16GVK DIMM        | 16 GB    | DDR4 | 3600 | 205   | [9395B9743085](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/9395B9743085>) |
| Samsung    | M471B5273CH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 205   | [D313F7D98EDE](<Notebook/Acer/Aspire/Aspire 7750G/D313F7D98EDE>) |
| Crucial    | CT102464BF160B.C16 SODIMM    | 8 GB     | DDR3 | 1600 | 202   | [87B1E9D262C7](<Notebook/Lenovo/ThinkPad/ThinkPad Edge E530 62724FU/87B1E9D262C7>) |
| SK hynix   | HMT351S6EFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 202   | [9BFEEDC7627F](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AWS0XX04/9BFEEDC7627F>) |
| Kingston   | KHX1866C10D3/8G DIMM         | 8 GB     | DDR3 | 2133 | 202   | [C8965ED60551](<Desktop/ASUSTek Computer/BM6630/BM6630_BM6330_BP6230/C8965ED60551>) |
|            | Module DIMM                  | 1024 MB  |      | 667  | 200   | [379945E91382](<Desktop/Gigabyte Technology/G41/G41M-ES2L/379945E91382>) |
| Micron     | 4ATF1G64HZ-3G2E1 Row Of C... | 8 GB     | DDR4 | 3200 | 198   | [5DAFB1DF7836](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 5 14ALC05 82HU/5DAFB1DF7836>) |
| Micron     | 4ATF1G64HZ-3G2E2 SODIMM      | 8 GB     | DDR4 | 3200 | 194   | [6100E3A7DF18](<Notebook/ASUSTek Computer/ROG/ROG Strix G513QY_G513QY/6100E3A7DF18>) |
|            | Module DIMM                  | 2 GB     |      | 800  | 194   | [62C7C6EA68B6](<Desktop/Gigabyte Technology/G31/G31M-S2L/62C7C6EA68B6>) |
|            | Module DIMM                  | 2048 MB  | DDR3 | 1333 | 193   | [25E2FF4C9B8F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/25E2FF4C9B8F>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 192   | [E34D770DE93E](<Notebook/Lenovo/ThinkPad/ThinkPad T16 Gen 1 21BV0095US/E34D770DE93E>) |
| SK hynix   | HMA82GS6JJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 188   | [B90F60589E1F](<Desktop/Others/Others/Others/B90F60589E1F>) |
| G.Skill    | F4-3000C16-8GISB DIMM        | 8 GB     | DDR4 | 3200 | 184   | [0A658C78C2F5](<Desktop/ASRock/A320M-DVS/A320M-DVS R4.0/0A658C78C2F5>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 184   | [703410084673](<Notebook/Acer/Aspire/Aspire A515-52G/703410084673>) |
| Kingston   | KHX2400C15/8G DIMM           | 8 GB     | DDR4 | 3400 | 183   | [D57980EEEB55](<Desktop/Gigabyte Technology/H270/H270M-D3H/D57980EEEB55>) |
| SK hynix   | HMA82GS6AFR8N-UH SODIMM      | 16 GB    | DDR4 | 2667 | 183   | [69F03FF97A26](<Notebook/Dell/Inspiron/Inspiron 17-7779/69F03FF97A26>) |
| SK hynix   | HYMP125S64CP8-S6 SODIMM DDR  | 2 GB     |      | 800  | 183   | [D8EC87177B41](<Notebook/Dell/Vostro/Vostro 1510/D8EC87177B41>) |
|            | Module DIMM                  | 2048 MB  |      | 400  | 182   | [F158976C6A44](<Desktop/Gigabyte Technology/D525/D525TUD/F158976C6A44>) |
| SK hynix   | HMT41GS6AFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 179   | [D7D4A73BFFF0](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570w/D7D4A73BFFF0>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 178   | [234EE0C2FEE0](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4290RV5/234EE0C2FEE0>) |
| SK hynix   | HMT351U6CFR8C-PB DIMM        | 4 GB     | DDR3 | 1800 | 178   | [D560D96EF397](<Desktop/Fujitsu/ESPRIMO/ESPRIMO PH320/D560D96EF397>) |
| Kingston   | 99U5428-018.A00LF SODIMM     | 8 GB     | DDR3 | 1600 | 175   | [EA91ECD23727](<Notebook/Toshiba/Satellite/Satellite Pro R50-B/EA91ECD23727>) |
| Samsung    | M471A2K43DB1-CTD SODIMM      | 16 GB    | DDR4 | 2667 | 175   | [BBA9E5D5AD1F](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0C300/BBA9E5D5AD1F>) |
| Crucial    | CT102464BF160B.M16 SODIMM    | 8 GB     | DDR3 | 1600 | 174   | [454911211166](<Notebook/ASUSTek Computer/X555/X555LJ/454911211166>) |
|            | Module DIMM SDRAM            | 512 MB   |      |      | 174   | [E1476B0B5E6F](<Desktop/ASUSTek Computer/P4/P4P800/E1476B0B5E6F>) |
| SK hynix   | HMT325S6BFR8C-H9 SODIMM      | 2048 MB  | DDR3 | 1600 | 174   | [E2A03E725B22](<Notebook/ASUSTek Computer/K52/K52F/E2A03E725B22>) |
| Micron     | 16KTF1G64HZ-1G6E1 SODIMM     | 8 GB     | DDR3 | 1600 | 172   | [9C3035A6FFDA](<Notebook/Hewlett-Packard/ENVY/ENVY 15/9C3035A6FFDA>) |
| Samsung    | M471A5244CB0-CWE Row Of C... | 4 GB     | DDR4 | 3200 | 170   | [3526B15504F8](<Convertible/Lenovo/IdeaPadFlex/IdeaPadFlex 3 11ADA05 82G4/3526B15504F8>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 169   | [D7CCA0FAA70C](<Notebook/Hewlett-Packard/1000/1000/D7CCA0FAA70C>) |
| Corsair    | CMK32GX4M2B3200C16 DIMM      | 16 GB    | DDR4 | 3400 | 168   | [623B536727E2](<Desktop/Gigabyte Technology/B450M/B450M S2H/623B536727E2>) |
| SK hynix   | HMT425S6AFR6A-PB SODIMM      | 2 GB     | DDR3 | 3200 | 168   | [08AFD1B0BD96](<Notebook/ASUSTek Computer/S551/S551LN/08AFD1B0BD96>) |
| Samsung    | M471A1K43BB0-CPB SODIMM      | 8 GB     | DDR4 | 2133 | 168   | [5F38F37F57B7](<Notebook/ASUSTek Computer/K501/K501UW/5F38F37F57B7>) |
| Nanya      | NT4GC64B8HB0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 167   | [43C31E49EF42](<Notebook/Packard Bell/EasyNote/EasyNote TK87/43C31E49EF42>) |
|            | Module DIMM                  | 4 GB     | DDR3 | 1333 | 167   | [E159B92C618A](<Desktop/ASRock/FM2A58M-VG3+/FM2A58M-VG3+ R2.0/E159B92C618A>) |
|            | Module DIMM                  | 1024 MB  |      |      | 165   | [92C78BFA8A5B](<Desktop/EPoX Computer/nForce3/nForce3 DDR: 8KDA3I Series/92C78BFA8A5B>) |
| Kingston   | 99U5584-005.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 164   | [4A9F80F6E95A](<Desktop/ASRock/H81/H81M-HDS/4A9F80F6E95A>) |
| Elpida     | EBJ40UG8BBU0-GN-F SODIMM     | 4 GB     | DDR3 | 1600 | 163   | [00DC6BF01FE7](<Notebook/ASUSTek Computer/X75/X75VD/00DC6BF01FE7>) |
| Samsung    | M471B5674QH0-YK0 SODIMM      | 2 GB     | DDR3 | 1600 | 163   | [4AC455A1BD5F](<Desktop/Quanta/2AF5/2AF5 011/4AC455A1BD5F>) |
| Ramaxel    | RMSA3260ME78HAF-2666 SODIMM  | 8 GB     | DDR4 | 2667 | 161   | [A053B0259753](<Notebook/Lenovo/ThinkBook/ThinkBook 14-IIL 20SL/A053B0259753>) |
| Samsung    | M471A2G44AM0-CWE SODIMM      | 16 GB    | DDR4 | 3200 | 161   | [78CB2C557CE0](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 1 20UD006BGE/78CB2C557CE0>) |
| Micron     | 16JSF51264HZ-1G4D1 SODIMM    | 4 GB     | DDR3 | 1334 | 160   | [D9BFDC983E07](<Notebook/Hewlett-Packard/ProBook/ProBook 5320m/D9BFDC983E07>) |
| Samsung    | M471B5773DH0-CK0 SODIMM      | 2 GB     | DDR3 | 1600 | 160   | [41422F3B2FC9](<Notebook/Hewlett-Packard/450/450/41422F3B2FC9>) |
| SK hynix   | HMT351S6CFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 160   | [5257071C8A12](<Notebook/Toshiba/PORTEGE/PORTEGE Z830/5257071C8A12>) |
|            | Module DIMM                  | 2 GB     |      | 1333 | 159   | [295E08E13748](<Desktop/ASUSTek Computer/M4N68T-M/M4N68T-M LE/295E08E13748>) |
| Samsung    | M471A4G43MB1-CTD SODIMM      | 32 GB    | DDR4 | 2667 | 159   | [21D2A3C2CECA](<Notebook/Dell/Precision/Precision 7540/21D2A3C2CECA>) |
| Nanya      | NT4GC64B8HG0NS-CG SODIMM     | 4 GB     | DDR3 | 1334 | 156   | [1A91C1BDDE7A](<Notebook/Lenovo/ThinkPad/ThinkPad T410 25376B8/1A91C1BDDE7A>) |
| 48spaces   | 0123456789012345678901234... | 1024 MB  | DDR2 | 667  | 155   | [7B26E147AE9A](<Notebook/Samsung Electronics/N102/N102S/7B26E147AE9A>) |
| Micron     | 8JTF51264AZ-1G6E1 DIMM       | 4 GB     | DDR3 | 1600 | 154   | [A7B2003BB7EC](<Desktop/Dell/XPS/XPS 8700/A7B2003BB7EC>) |
| Samsung    | M378B5273DH0-CH9 DIMM        | 4 GB     | DDR3 | 2133 | 152   | [90A5DDFE18F3](<Desktop/Lenovo/ThinkCentre/ThinkCentre M91 4518E4S/90A5DDFE18F3>) |
|            | Module DIMM DDR              | 2048 MB  |      | 1333 | 147   | [AF56DA109B0C](<Desktop/ASUSTek Computer/P7H55-M/P7H55-M LE/AF56DA109B0C>) |
|            | Module DIMM                  | 4096 MB  | DDR3 | 1600 | 147   | [273F2675355C](<Desktop/Biostar/A68/A68N-5100/273F2675355C>) |
| SK hynix   | HMA81GS6DJR8N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 146   | [C2EF98F2985B](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 15-eh1xxx/C2EF98F2985B>) |
| Samsung    | M471A5244BB0-CRC SODIMM      | 4 GB     | DDR4 | 2667 | 146   | [CBCD9552E6B0](<Notebook/Hewlett-Packard/250/250 G6 Notebook PC/CBCD9552E6B0>) |
| Samsung    | M471A5244CB0-CTD Row Of C... | 4 GB     | DDR4 | 2667 | 146   | [FEB58E4DED85](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/FEB58E4DED85>) |
| Kingston   | 99U5471-012.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 145   | [799C09CD3FB0](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX R2.0/799C09CD3FB0>) |
| SK hynix   | HMA82GS6CJR8N-VK SODIMM      | 16 GB    | DDR4 | 2667 | 145   | [99B4AA85388C](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX504GE_FX80GE/99B4AA85388C>) |
| Crucial    | CT51264BF160B.C16F SODIMM    | 4 GB     | DDR3 | 1600 | 144   | [67B1ACAFCC2D](<Notebook/MobileDemand/xTablet/xTablet T1200/67B1ACAFCC2D>) |
| SK hynix   | HMAA1GS6CJR6N-XN SODIMM      | 8 GB     | DDR4 | 3200 | 144   | [7675A6D4AB24](<Notebook/Acer/Aspire/Aspire A515-45/7675A6D4AB24>) |
| Samsung    | M378B5673FH0-CH9 DIMM        | 2 GB     | DDR3 | 1600 | 144   | [AE1DD2EBB7DB](<Desktop/Hewlett-Packard/Compaq/Compaq 6000 Pro MT Brazil PC/AE1DD2EBB7DB>) |
| Ramaxel    | RMT3160ED58E9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 143   | [64B93107613A](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2347G7G/64B93107613A>) |
| Elpida     | EBJ21UE8BDS0-DJ-F SODIMM     | 2 GB     | DDR3 | 1334 | 142   | [E3CA3F89BD34](<Notebook/Hewlett-Packard/ProBook/ProBook 6450b/E3CA3F89BD34>) |
| Kingston   | KHX1600C9S3L/8G SODIMM       | 8 GB     | DDR3 | 1600 | 142   | [AD7F8A1EAC61](<Notebook/Lenovo/ThinkPad/ThinkPad E560 20EVCTO1WW/AD7F8A1EAC61>) |
| Micron     | 8JSF25664HZ-1G4D1 SODIMM     | 2 GB     | DDR3 | 1334 | 142   | [6D08955FC6FC](<Notebook/Dell/Inspiron/Inspiron N5110/6D08955FC6FC>) |
|            | Module SODIMM                | 2 GB     | DDR2 |      | 142   | [5C21ED840185](<Notebook/Intel/Calistoga/Calistoga & ICH7M Chipset/5C21ED840185>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 140   | [9B9CF6F55CD7](<Notebook/ASUSTek Computer/K52/K52F/9B9CF6F55CD7>) |
| Corsair    | CMZ8GX3M2A1600C9 DIMM        | 4 GB     | DDR3 | 1600 | 139   | [A1DE5102E68C](<Desktop/MSI/MS/MS-7821/A1DE5102E68C>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1333 | 139   | [76747AE9E96D](<Notebook/Dell/Inspiron/Inspiron 5520/76747AE9E96D>) |
| Kingston   | KHX1600C10D3/4G DIMM         | 4 GB     | DDR3 | 1866 | 139   | [A77F6A960E14](<Desktop/ASRock/FM2A78/FM2A78 Pro4+/A77F6A960E14>) |
| Micron     | MT52L1G32D4PG-093 Row Of ... | 8 GB     |      | 2133 | 139   | [39EE02D40549](<Notebook/Dell/XPS/XPS 13 9370/39EE02D40549>) |
|            | Module SODIMM                | 4 GB     | DDR3 |      | 139   | [4B27E08DF918](<Notebook/Sony/VPCCW23/VPCCW23FX/4B27E08DF918>) |
| Samsung    | M378B5173DB0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 137   | [7403924D239F](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/7403924D239F>) |
| Samsung    | M471B5173BH0-CK0 SODIMM      | 4 GB     | DDR3 | 1600 | 137   | [540AF9B46C29](<Notebook/Samsung Electronics/350V5/350V5C-351V5C-3540VC-3440VC/540AF9B46C29>) |
| Elpida     | Module SODIMM                | 2 GB     | DDR3 | 1333 | 136   | [9D66FDFD8ED4](<Notebook/ASUSTek Computer/UX31/UX31E/9D66FDFD8ED4>) |
|            | Module SODIMM                | 2048 MB  | DDR2 | 800  | 136   | [D19176E847E3](<All In One/Apple/iMac8/iMac8,1/D19176E847E3>) |
| Elpida     | EBJ21UE8BFU0-DJ-F SODIMM     | 2 GB     | DDR3 | 1334 | 135   | [F40111BA39E9](<Notebook/Hewlett-Packard/Notebook/Notebook/F40111BA39E9>) |
| SK hynix   | HMT351S6CFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 135   | [0B82F6039EA0](<Notebook/Hewlett-Packard/Folio/Folio 13/0B82F6039EA0>) |
| Samsung    | M378B5173QH0-CK0 DIMM        | 4 GB     | DDR3 | 1600 | 134   | [C8399965789E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M82 2929A1G/C8399965789E>) |
| Samsung    | M378B5773DH0-CH9 DIMM        | 2 GB     | DDR3 | 1333 | 134   | [5F0F1A025A1A](<Desktop/ASRock/Z77/Z77 Extreme6-TB4/5F0F1A025A1A>) |
| Samsung    | M471A2G43AB2-CWE SODIMM      | 16384 MB | DDR4 | 3200 | 134   | [B7064CDDC23A](<Notebook/Alienware/m15/m15 Ryzen Ed. R5/B7064CDDC23A>) |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1333 | 133   | [309261AD2974](<Notebook/AXDIA International/WINPAD/WINPAD V10/309261AD2974>) |
|            | Module DIMM                  | 2048 MB  |      | 1066 | 131   | [C8ECDC6BA2DD](<Desktop/Gigabyte Technology/M52/M52LT-D3/C8ECDC6BA2DD>) |
| Samsung    | M471B5673EH1-CF8 SODIMM      | 2 GB     |      | 4199 | 131   | [D9407E87D07C](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv7/D9407E87D07C>) |
|            | Module DIMM                  | 4096 MB  |      | 400  | 130   | [E37B2CA4C5C3](<Desktop/Gigabyte Technology/P41/P41T-D3P/E37B2CA4C5C3>) |
| Samsung    | M378B5773CH0-CH9 DIMM        | 2 GB     | DDR3 | 1867 | 130   | [4E1AAC55058E](<Desktop/Hewlett-Packard/18E4/18E4/4E1AAC55058E>) |
| Crucial    | BLS8G3D1609DS1S00. DIMM      | 8 GB     | DDR3 | 1600 | 128   | [8E6EF6F82D36](<Desktop/ASRock/Z87M/Z87M Extreme4/8E6EF6F82D36>) |
| Kingston   | KHX3200C16D4/16GX DIMM       | 16 GB    | DDR4 | 3600 | 128   | [92A8E62FD610](<Desktop/Gigabyte Technology/B450M/B450M DS3H V2/92A8E62FD610>) |
| Micron     | 8ATF1G64HZ-2G3B1 SODIMM      | 8 GB     | DDR4 | 2400 | 128   | [AC2834FC0E19](<Mini Pc/Intel/NUC7/NUC7i3BNK/AC2834FC0E19>) |
| Ramaxel    | RMSA3270ME86H9F-2666 SODIMM  | 4 GB     | DDR4 | 2667 | 128   | [F9ABE54AC57F](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15IKB 81DE/F9ABE54AC57F>) |
| Kingston   | 99U5471-020.A00LF DIMM       | 4 GB     | DDR3 | 1600 | 127   | [EA6EAE3BAF0B](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS/EA6EAE3BAF0B>) |
| Kingston   | ACR256X64D3S1333C9 SODIMM    | 2 GB     | DDR3 | 1334 | 127   | [72C64637E292](<Notebook/Acer/Aspire/Aspire 5742G/72C64637E292>) |
| SK hynix   | HMT325S6CFR8C-PB SODIMM      | 2 GB     | DDR3 | 1600 | 126   | [19E0AC8453FF](<Notebook/ASUSTek Computer/X55/X55VD/19E0AC8453FF>) |
| SK hynix   | HMT351S6EFR8C-PB SODIMM      | 4 GB     | DDR3 | 1600 | 126   | [61A9C47EA4F8](<Notebook/Lenovo/IdeaPad/IdeaPad Z585 20152/61A9C47EA4F8>) |
| SK hynix   | HMT351S6BFR8C-H9 SODIMM      | 4 GB     | DDR3 | 1334 | 126   | [1A91C1BDDE7A](<Notebook/Lenovo/ThinkPad/ThinkPad T410 25376B8/1A91C1BDDE7A>) |
|            | Module SODIMM DDR            | 1024 MB  |      |      | 125   | [E587DFDCB4C9](<Notebook/IBM/ThinkPad/ThinkPad T41 23731HG/E587DFDCB4C9>) |
|            | Module DIMM                  | 1024 MB  | DDR2 |      | 125   | [A65895D913D5](<Desktop/ABIT/I-45/I-45CV/A65895D913D5>) |
|            | Module SODIMM DRAM           | 1024 MB  |      |      | 125   | [D0740CBC6042](<Notebook/Fujitsu Siemens/ESPRIMO/ESPRIMO Mobile V5535/D0740CBC6042>) |
| Samsung    | M471B5173BH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 124   | [06ADBF621B4E](<Notebook/Toshiba/Satellite/Satellite P75-A/06ADBF621B4E>) |
| SK hynix   | HMA851S6CJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 123   | [3638E3679428](<Notebook/Acer/Aspire/Aspire A515-44/3638E3679428>) |
| Kingston   | 99U5469-045.A00LF SODIMM     | 4 GB     | DDR3 | 1600 | 123   | [55D765B7E842](<Notebook/ASUSTek Computer/X550/X550JF/55D765B7E842>) |
| Ramaxel    | RMT3170EB68F9W1600 SODIMM    | 4 GB     | DDR3 | 1600 | 123   | [FDE975018164](<Notebook/Lenovo/IdeaPad/IdeaPad U310 Touch/FDE975018164>) |
| Samsung    | M4 70T5663QZ3-CF7 SODIMM     | 2 GB     | DDR2 | 2048 | 122   | [EC50067C2C26](<Notebook/Semp Toshiba/IS/IS 1413G/EC50067C2C26>) |
| SK hynix   | HMA851S6AFR6N-UH SODIMM      | 4 GB     | DDR4 | 2400 | 121   | [4916206B0094](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ak0xx/4916206B0094>) |
| SK hynix   | HMT451U6AFR8C-PB DIMM        | 4 GB     | DDR3 | 1600 | 120   | [432BFB67B33F](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/432BFB67B33F>) |
|            | Module DIMM                  | 1024 MB  | DDR2 | 333  | 120   | [FB088E456F37](<Desktop/ASUSTek Computer/P5/P5GC-MX/FB088E456F37>) |
|            | Module SODIMM SDRAM          | 2048 MB  |      |      | 120   | [A18D82F4BF35](<Notebook/ASUSTek Computer/K50/K50C/A18D82F4BF35>) |
| Ramaxel    | RMT3170ME68F9F1600 SODIMM    | 4 GB     | DDR3 | 1600 | 120   | [46643CC86DAF](<Notebook/Lenovo/Y430P/Y430P 20435/46643CC86DAF>) |
| Samsung    | M471A1K43BB1-CTD SODIMM      | 8 GB     | DDR4 | 2667 | 120   | [6A48296FAAF8](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3S3UL00/6A48296FAAF8>) |
| Samsung    | M471B5273EB0-CK0 SODIMM      | 4 GB     | DDR3 | 4199 | 120   | [0A396544A3B7](<Notebook/Samsung Electronics/350V5/350V5C-350V5X-350V4C-350V4X-351V5C-351V5X-351V4C-351V4X-3540VC-3540VX-3440VC-3440VX/0A396544A3B7>) |
| Samsung    | M471B2873FHS-CH9 SODIMM      | 1 GB     | DDR3 | 1334 | 118   | [C9CB128DFBDF](<Notebook/Hewlett-Packard/620/620/C9CB128DFBDF>) |
| Samsung    | K4EBE304EB-EGCG Row Of Ch... | 8 GB     |      | 2133 | 117   | [F305EC3BAEC2](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LDCTO1WW/F305EC3BAEC2>) |
| Kingston   | KHX1866C10D3/4G DIMM         | 4 GB     | DDR3 | 1867 | 116   | [5DFF33E9A8DF](<Desktop/MSI/MS/MS-7918/5DFF33E9A8DF>) |
| Micron     | 4ATF51264HZ-3G2J1 Row Of ... | 4 GB     | DDR4 | 3200 | 115   | [942606C59EF9](<Notebook/Lenovo/V15/V15 G2 ITL 82KB/942606C59EF9>) |
| SK hynix   | HMT325S6BFR8C-H9 SODIMM      | 2 GB     | DDR3 | 1333 | 114   | [DF42A3694FAC](<Notebook/Acer/Aspire/Aspire 4750/DF42A3694FAC>) |
| Kingston   | 99U5471-054.A00LF DIMM       | 8 GB     | DDR3 | 1600 | 113   | [6C891C8585EF](<Desktop/MSI/MS/MS-7917/6C891C8585EF>) |
| Kingston   | ACR16D3LS1KFG/4G SODIMM      | 4 GB     | DDR3 | 1600 | 113   | [480FAD94A8C0](<Notebook/Acer/Aspire/Aspire E1-522/480FAD94A8C0>) |
|            | Module DIMM                  | 2048 MB  | DDR2 |      | 113   | [EEF33A93D047](<Server/MSI/MCP/MCP55/EEF33A93D047>) |
| SK hynix   | HMT451S6BFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 113   | [06BCF10B3322](<Notebook/Lenovo/IdeaPad/IdeaPad 300-15ISK 80Q7/06BCF10B3322>) |
| Corsair    | CMK16GX4M2A2666C16 DIMM      | 8 GB     | DDR4 | 3400 | 112   | [2D9B1EF58C0B](<Desktop/ASUSTek Computer/PRIME/PRIME X399-A/2D9B1EF58C0B>) |
|            | Module SODIMM                | 1 GB     | DDR2 | 667  | 112   | [4D38D46F27D0](<Notebook/Acer/Aspire/Aspire 5920G/4D38D46F27D0>) |
|            | Module SODIMM                | 2048 MB  | DDR3 |      | 112   | [4918FDDA4745](<Notebook/Sony/SVE1513/SVE1513C5E/4918FDDA4745>) |
|            | Module DIMM SDRAM            | 4096 MB  |      |      | 112   | [358E1ACCD5FB](<Desktop/ASRock/P45/P45DE3/358E1ACCD5FB>) |
| Samsung    | M471A4G43AB1-CWE SODIMM      | 32 GB    | DDR4 | 3200 | 112   | [B0BE5D686006](<Notebook/Acer/Nitro/Nitro AN517-55/B0BE5D686006>) |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1333 | 110   | [36A5543B052C](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4291T4Y/36A5543B052C>) |
| Samsung    | M471A1G44BB0-CWE SODIMM      | 8 GB     | DDR4 | 3200 | 110   | [A3EB49F5FACC](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop S5402ZA_S5402ZA/A3EB49F5FACC>) |
| Samsung    | UBE3D4AA-MGCR Row Of Chip... | 2 GB     |      | 4267 | 110   | [B770E4DD0A92](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX425EA_UX425EA/B770E4DD0A92>) |
| Micron     | 4ATS1G64HZ-2G6E1 SODIMM      | 8 GB     | DDR4 | 2667 | 109   | [BA15845847B8](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2001YUS/BA15845847B8>) |
| Micron     | 8KTF51264HZ-1G6N1 SODIMM     | 4096 MB  | DDR3 | 1600 | 109   | [17881A19FE19](<Notebook/Hewlett-Packard/Pavilion/Pavilion 17/17881A19FE19>) |
| Nanya      | NT4GC64B8HG0NS-DI SODIMM     | 4 GB     | DDR3 | 1600 | 108   | [721CF412B68C](<Notebook/Lenovo/ThinkPad/ThinkPad W530 2463A49/721CF412B68C>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1600 | 108   | [8D3D9C85BD5B](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/8D3D9C85BD5B>) |
| SK hynix   | Module SODIMM                | 4 GB     | DDR3 | 1600 | 108   | [E375C99C3BC2](<Notebook/Apple/MacBookPro10/MacBookPro10,2/E375C99C3BC2>) |
|            | Module DIMM                  | 8192 MB  | DDR3 | 1333 | 107   | [1567E7B66486](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/1567E7B66486>) |
| Samsung    | M471A5143EB0-CPB SODIMM      | 4 GB     | DDR4 | 2133 | 107   | [09024D6D46F9](<Notebook/Hewlett-Packard/250/250 G5 Notebook PC/09024D6D46F9>) |
| A-DATA     | AD73I1C1674EV SODIMM         | 4 GB     | DDR3 | 1334 | 106   | [FD5B2DFF8829](<Notebook/Hewlett-Packard/Pavilion/Pavilion g6/FD5B2DFF8829>) |
|            | Module DIMM                  | 2048 MB  | DDR2 | 333  | 106   | [AD7E535377DC](<Desktop/ASUSTek Computer/P5/P5SD2-VM/AD7E535377DC>) |
| SK hynix   | HMA851S6CJR6N-VK Row Of C... | 4 GB     | DDR4 | 2667 | 105   | [49D7DE7236D7](<Notebook/HUAWEI/NBLK-WAX9/NBLK-WAX9X/49D7DE7236D7>) |
| Patriot    | 3200 C16 Series DIMM         | 8 GB     | DDR4 | 3266 | 104   | [DA0BA7340865](<Desktop/MSI/MS-7/MS-7C83/DA0BA7340865>) |
| SK hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 104   | [8DC3BDC9A2EC](<Notebook/Dell/Latitude/Latitude 3500/8DC3BDC9A2EC>) |
| Kingston   | KHX2666C15S4/16G SODIMM      | 16 GB    | DDR4 | 2667 | 103   | [E2360AE2AC48](<Notebook/Lenovo/Legion/Legion Y530-15ICH 81FV/E2360AE2AC48>) |
| SK hynix   | HMA851S6DJR6N-XN SODIMM      | 4 GB     | DDR4 | 3200 | 103   | [9177B2145423](<Notebook/Hewlett-Packard/Pavilion/Pavilion Laptop 15-eg0xxx/9177B2145423>) |
|            | Module SODIMM                | 4096 MB  | DDR3 | 1600 | 101   | [AAF1E6E3D074](<Tablet/Microsoft/Surface/Surface Pro 3/AAF1E6E3D074>) |
|            | Module SODIMM SDRAM          | 1024 MB  |      |      | 100   | [17F26DF1EB79](<Notebook/ASUSTek Computer/1003/1003HAG/17F26DF1EB79>) |
| SK hynix   | HMT351U6CFR8C-H9 DIMM        | 4 GB     | DDR3 | 1600 | 99    | [43A49BCC58C2](<Desktop/Gigabyte Technology/H87/H87M-HD3/43A49BCC58C2>) |
| Micron     | 4ATS2G64HZ-3G2B1 SODIMM      | 16 GB    | DDR4 | 3200 | 99    | [FAA92319E4B3](<Notebook/Lenovo/ThinkPad/ThinkPad T14 Gen 3 21AJS1DB00/FAA92319E4B3>) |
|            | Module SODIMM                | 2048 MB  | DDR3 | 1600 | 99    | [B04C4FDB8064](<Notebook/Insyde/CherryTrail/CherryTrail/B04C4FDB8064>) |
| SK hynix   | HMAA2GS6CJR8N-XN SODIMM      | 16 GB    | DDR4 | 3200 | 99    | [4B3E0B10A17C](<Notebook/Dell/Latitude/Latitude 5420/4B3E0B10A17C>) |
| SK hynix   | HMA851S6JJR6N-VK SODIMM      | 4 GB     | DDR4 | 2667 | 98    | [2C9CC1A12C09](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X412DAP_F412DA/2C9CC1A12C09>) |
| Samsung    | M4 70T5663EH3-CF7 SODIMM     | 2048 MB  | DDR2 | 975  | 98    | [8BCCE0EC904D](<Notebook/Hewlett-Packard/Compaq/Compaq 515/8BCCE0EC904D>) |
| Samsung    | Module SODIMM                | 16384 MB | DDR4 | 2667 | 98    | [D5FE9D804340](<Notebook/Hewlett-Packard/EliteBook/EliteBook 755 G5/D5FE9D804340>) |
| Micron     | 16ATF2G64HZ-2G6E1 SODIMM     | 16 GB    | DDR4 | 2667 | 97    | [726B921F6B34](<Desktop/Maxtang/EHL/EHL30/726B921F6B34>) |
| Samsung    | M378B5273CH0-CH9 DIMM        | 4 GB     | DDR3 | 1867 | 97    | [43A49BCC58C2](<Desktop/Gigabyte Technology/H87/H87M-HD3/43A49BCC58C2>) |
|            | Module SODIMM                | 512 MB   | DDR2 |      | 96    | [D89991083A03](<Notebook/Acer/Aspire/Aspire 5540/D89991083A03>) |
| Samsung    | Module SODIMM                | 8 GB     | DDR4 | 2133 | 96    | [A8FA5C81BE84](<Notebook/Hewlett-Packard/ZBook/ZBook Studio G3/A8FA5C81BE84>) |
| Kingston   | KHX1600C10D3/8GX DIMM        | 8192 MB  | DDR3 | 1600 | 95    | [8582F253BD21](<Desktop/ASRock/B75/B75 Pro3-M/8582F253BD21>) |
|            | Module DIMM SDRAM            | 1 GB     |      |      | 95    | [3A4FB03DDA4A](<Desktop/ASUSTek Computer/P5GD1/P5GD1 PRO/3A4FB03DDA4A>) |
|            | Module SODIMM                | 4 GB     | DDR3 | 1600 | 95    | [B6EC98750356](<Tablet/Microsoft/Surface/Surface Pro 3/B6EC98750356>) |
|            | Module DIMM                  | 8192 MB  |      | 1333 | 95    | [B84F04A7C5A4](<Desktop/Gigabyte Technology/PH67/PH67A-D3-B3/B84F04A7C5A4>) |
| SK hynix   | HMA451S6AFR8N-TF SODIMM      | 4 GB     | DDR4 | 2133 | 95    | [1602BFEF8553](<Notebook/ASUSTek Computer/P453/P453UA/1602BFEF8553>) |
|            | Module DIMM                  | 2048 MB  |      |      | 94    | [2E6F68FBCDD0](<Desktop/ASUSTek Computer/P6T/P6T WS PRO/2E6F68FBCDD0>) |
| Samsung    | M471B5273CH0-YK0 SODIMM      | 4 GB     | DDR3 | 1600 | 94    | [ECCDA202FFA9](<Notebook/ASUSTek Computer/X550/X550CC/ECCDA202FFA9>) |
| SK hynix   | HMT41GS6BFR8A-PB SODIMM      | 8 GB     | DDR3 | 1600 | 94    | [26C7B87FA7FD](<Notebook/Dell/Latitude/Latitude E6510/26C7B87FA7FD>) |
|            | Module DIMM                  | 2 GB     | DDR3 | 1333 | 93    | [04CBD3898548](<Server/Hewlett-Packard/ProLiant/ProLiant DL320 G6/04CBD3898548>) |
| SK hynix   | HMT451S6AFR8A-PB SODIMM      | 4 GB     | DDR3 | 1600 | 92    | [087D0F8BF36E](<Notebook/Lenovo/Y50-70/Y50-70 20378/087D0F8BF36E>) |
| SK hynix   | HMA81GS6AFR8N-UH SODIMM      | 8 GB     | DDR4 |      | 91    | [E040BAE3B239](<Notebook/Acer/Nitro/Nitro AN515-42/E040BAE3B239>) |
| Ramaxel    | RMT3020EC58E9F1333 SODIMM    | 4 GB     | DDR3 | 4199 | 91    | [D4BB7EE44FCD](<Notebook/Dell/Studio/Studio 1558/D4BB7EE44FCD>) |
| Samsung    | Module SODIMM                | 8192 MB  | DDR4 | 2133 | 91    | [BD225591F5A9](<Notebook/Hewlett-Packard/ProBook/ProBook 650 G2/BD225591F5A9>) |
| SK hynix   | HMA82GS6DJR8N-XN SODIMM      | 16384 MB | DDR4 | 3200 | 91    | [336478DAF0A4](<Notebook/Dell/Precision/Precision 5750/336478DAF0A4>) |
| Team       | TEAMGROUP-UD4-3200 DIMM      | 8 GB     | DDR4 | 3800 | 91    | [36A194C75384](<Desktop/MSI/MS-7/MS-7B17/36A194C75384>) |
| Crucial    | CT51264BA160B.C16F DIMM      | 4 GB     | DDR3 | 1600 | 90    | [A676DFF54379](<Desktop/ASUSTek Computer/P8P67/P8P67 PRO/A676DFF54379>) |
| G.Skill    | F4-3200C16-8GIS DIMM         | 8192 MB  | DDR4 | 3200 | 90    | [BA12BC4C864F](<Desktop/Gigabyte Technology/B450M/B450M GAMING/BA12BC4C864F>) |
| Kingston   | 99U5428-063.A00LF SODIMM     | 8192 MB  | DDR3 | 1600 | 90    | [864CF5869F42](<Notebook/MSI/GE70/GE70 2PL/864CF5869F42>) |

### Battery

| MFG        | Name           | Wh    | Type    | Count | Probe |
|------------|----------------|-------|---------|-------|-------|
| ASUSTek    | ASUS           | 50.0  | Li-ion  | 2406  | [9497D288F6](https://linux-hardware.org/?probe=9497d288f6) |
| Hewlett... | PABAS0241231   | 55.7  | Li-ion  | 1098  | [5CE5272A93](https://linux-hardware.org/?probe=5ce5272a93) |
| Compal     | PABAS0241231   | 99.0  | Li-ion  | 890   | [C273319D9D](https://linux-hardware.org/?probe=c273319d9d) |
| Lenovo     | PABAS0241231   | 28.5  | Li-ion  | 746   | [DA3030DAAE](https://linux-hardware.org/?probe=da3030daae) |
| MSI        | BIF0_9         | 51.4  | Li-ion  | 639   | [B29933336D](https://linux-hardware.org/?probe=b29933336d) |
| SMP        | bq20z451       | 63.2  | Li-ion  | 564   | [46AAFC59C4](https://linux-hardware.org/?probe=46aafc59c4) |
| Intel SR 1 | SR Real Bat... |       |         | 455   | [AF76238A5C](https://linux-hardware.org/?probe=af76238a5c) |
| Samsung    |                | 49    | Li-ion  | 453   | [FEDDB64B95](https://linux-hardware.org/?probe=feddb64b95) |
| OEM        | standard       | 93.5  | Li-ion  | 415   | [87BE6C6120](https://linux-hardware.org/?probe=87be6c6120) |
| Hewlett... | Primary        | 45    | Li-ion  | 408   | [5BF3FDCE42](https://linux-hardware.org/?probe=5bf3fdce42) |
| Hewlett... | Primary        | 48    | Li-ion  | 350   | [33D9C73CB9](https://linux-hardware.org/?probe=33d9c73cb9) |
| SANYO      | Li_Ion_4000mA  | 47.5  | Li-ion  | 347   | [B090683ED1](https://linux-hardware.org/?probe=b090683ed1) |
| Samsung    | SR Real        | 43.1  | Li-ion  | 337   | [D7F1482689](https://linux-hardware.org/?probe=d7f1482689) |
| SMP        | DELL GPM0365   | 97.0  | Li-ion  | 327   | [01319AC289](https://linux-hardware.org/?probe=01319ac289) |
| ASUSTek    | A32-K55        | 48.0  | Li-ion  | 314   | [0B622220D7](https://linux-hardware.org/?probe=0b622220d7) |
| Hewlett... | Primary        | 40    | Li-ion  | 269   | [26D3505372](https://linux-hardware.org/?probe=26d3505372) |
| LG         | PABAS0241231   | 52.5  | Li-ion  | 255   | [E521C55B1A](https://linux-hardware.org/?probe=e521c55b1a) |
| Hewlett... | Primary        | 41    | Li-ion  | 227   | [307B9D4A7B](https://linux-hardware.org/?probe=307b9d4a7b) |
| SANYO      | 45N1773        | 23.2  | Li-ion  | 227   | [F546833D76](https://linux-hardware.org/?probe=f546833d76) |
| Hewlett... | Primary        | 42    | Li-ion  | 226   | [93C3D6C151](https://linux-hardware.org/?probe=93c3d6c151) |
| DP         | bq20z451       | 38.8  | Li-ion  | 220   | [3407774BA7](https://linux-hardware.org/?probe=3407774ba7) |
| Hewlett... | Primary        | 44    | Li-ion  | 218   | [A6BDE6DB60](https://linux-hardware.org/?probe=a6bde6db60) |
| Notebook   | BAT            | 49    | Li-ion  | 203   | [516A173DCB](https://linux-hardware.org/?probe=516a173dcb) |
| Hewlett... | Primary        | 39    | Li-ion  | 198   | [AF86E6CB72](https://linux-hardware.org/?probe=af86e6cb72) |
| LGC        | 45N1127        | 23.5  | Li-ion  | 196   | [BF015F98C2](https://linux-hardware.org/?probe=bf015f98c2) |
| Hewlett... | Primary        | 50    | Li-ion  | 194   | [0D451E418C](https://linux-hardware.org/?probe=0d451e418c) |
| Hewlett... | Primary        | 38    | Li-ion  | 191   | [0CD82BF0C0](https://linux-hardware.org/?probe=0cd82bf0c0) |
| Samsung    |                | 44    | Li-ion  | 191   | [C72C5CF640](https://linux-hardware.org/?probe=c72c5cf640) |
| ASUSTek    | X550A26        | 57.1  | Li-ion  | 186   | [51FD1F6C24](https://linux-hardware.org/?probe=51fd1f6c24) |
| Hewlett... | Primary        | 53    | Li-ion  | 185   | [FCBEC20556](https://linux-hardware.org/?probe=fcbec20556) |
| SMP        | L16M2PB1       | 30.0  | Li-poly | 185   | [9368822D6A](https://linux-hardware.org/?probe=9368822d6a) |
| Hewlett... | Primary        | 43    | Li-ion  | 176   | [345CB01BCC](https://linux-hardware.org/?probe=345cb01bcc) |
| Hewlett... | Primary        | 46    | Li-ion  | 176   | [F8B182D99B](https://linux-hardware.org/?probe=f8b182d99b) |
| Hewlett... | Primary        | 56    | Li-ion  | 173   | [A9D6AE7B72](https://linux-hardware.org/?probe=a9d6ae7b72) |
| Hewlett... | Primary        | 36    | Li-ion  | 166   | [54E092F58F](https://linux-hardware.org/?probe=54e092f58f) |
| SMP        | DELL G8VCF6C   | 52.0  | Li-poly | 164   | [36BF8AF789](https://linux-hardware.org/?probe=36bf8af789) |
| SANYO      | PABAS0241231   | 30.1  | Li-ion  | 163   | [30D8845F10](https://linux-hardware.org/?probe=30d8845f10) |
| SANYO      | AL12A32        | 37.0  | Li-ion  | 162   | [6064A923C6](https://linux-hardware.org/?probe=6064a923c6) |
| SANYO      | AL10B31        | 48.8  | Li-ion  | 157   | [1F57142FFD](https://linux-hardware.org/?probe=1f57142ffd) |
| Hewlett... | Primary        | 41    | Li-ion  | 155   | [4577D3D99D](https://linux-hardware.org/?probe=4577d3d99d) |
| SANYO      | 45N1775        | 23.2  | Li-ion  | 151   | [31AE950D04](https://linux-hardware.org/?probe=31ae950d04) |
| SIMPLO     | PABAS0241231   | 30.0  | Li-ion  | 151   | [4EB3C2AFB3](https://linux-hardware.org/?probe=4eb3c2afb3) |
| LGC        | AP18C8K        | 48.0  | Li-ion  | 149   | [FCF01071E5](https://linux-hardware.org/?probe=fcf01071e5) |
| CPT-COS    | L16C2PB2       | 30.6  | Li-poly | 148   | [FFD622D65F](https://linux-hardware.org/?probe=ffd622d65f) |
| Notebook   | BAT            | 48    | Li-ion  | 146   | [D15806C6C2](https://linux-hardware.org/?probe=d15806c6c2) |
|            | Battery        |       |         | 145   | [6D64083839](https://linux-hardware.org/?probe=6d64083839) |
| Hewlett... | Primary        | 37    | Li-ion  | 145   | [6EF7E95717](https://linux-hardware.org/?probe=6ef7e95717) |
| SANYO      | AL15A32        | 37.0  | Li-ion  | 144   | [CDBD2AD757](https://linux-hardware.org/?probe=cdbd2ad757) |
| Panasonic  | AP16M5J        | 37.0  | Li-ion  | 142   | [B452C164D0](https://linux-hardware.org/?probe=b452c164d0) |
| Panasonic  | Li_Ion_4000mA  | 47.5  | Li-ion  | 142   | [E4B193C332](https://linux-hardware.org/?probe=e4b193c332) |
| LGC        | AP18E8M        | 57.5  | Li-ion  | 141   | [162B72D7A8](https://linux-hardware.org/?probe=162b72d7a8) |
| SMP        | L16M2PB2       | 35.0  | Li-poly | 136   | [76F2F157A5](https://linux-hardware.org/?probe=76f2f157a5) |
| LG         | Li_Ion_4000mA  | 47.5  | Li-ion  | 135   | [ADA6DD2B76](https://linux-hardware.org/?probe=ada6dd2b76) |
| ASUSTek    | UX31-35        | 47.9  | Li-ion  | 127   | [E6391763B2](https://linux-hardware.org/?probe=e6391763b2) |
| SANYO      | AS10D31        | 47.5  | Li-ion  | 127   | [F1168775A7](https://linux-hardware.org/?probe=f1168775a7) |
| LGC        | AC14B8K        | 48.9  | Li-ion  | 126   | [021D999708](https://linux-hardware.org/?probe=021d999708) |
| SMP        | DELL 70N2F95   | 84.3  | Li-poly | 123   | [1263022267](https://linux-hardware.org/?probe=1263022267) |
| ASUSTek    | F82--22        | 47.3  | Li-ion  | 121   | [9D476DFADE](https://linux-hardware.org/?probe=9d476dfade) |
| Hewlett... | Primary        | 49    | Li-ion  | 121   | [430B938694](https://linux-hardware.org/?probe=430b938694) |
| Hewlett... | Primary        |       | Li-ion  | 120   | [D556BF453D](https://linux-hardware.org/?probe=d556bf453d) |
| LGC        | L16L2PB2       | 30.0  | Li-poly | 120   | [7D4406C9BC](https://linux-hardware.org/?probe=7d4406c9bc) |
| SMP        | DELL Y3F7Y6B   | 42.0  | Li-ion  | 119   | [CF5749E5BE](https://linux-hardware.org/?probe=cf5749e5be) |
| Sony       | 45N1111        | 23.2  | Li-poly | 119   | [4EA8B48D8D](https://linux-hardware.org/?probe=4ea8b48d8d) |
| ASUSTek    | K52F-44        | 47.3  | Li-ion  | 117   | [F87ECE85E9](https://linux-hardware.org/?probe=f87ece85e9) |
| ASUSTek    | X550A30        | 44.2  | Li-ion  | 116   | [4C50999862](https://linux-hardware.org/?probe=4c50999862) |
| LGC        | 45N1049        | 40.4  | Li-ion  | 115   | [A3B352975C](https://linux-hardware.org/?probe=a3b352975c) |
| Samsung    |                | 48    | Li-ion  | 115   | [7EC9E518C4](https://linux-hardware.org/?probe=7ec9e518c4) |
| LG         | 004B3842343... | 48.9  | Li-ion  | 112   | [065827A397](https://linux-hardware.org/?probe=065827a397) |
| SANYO      | GC86508SAT0    | 71.0  | Li-ion  | 112   | [2D98A8CEF2](https://linux-hardware.org/?probe=2d98a8cef2) |
| Sony       | VGP-BPS26      | 45.4  | Li-ion  | 111   | [43F51D50C1](https://linux-hardware.org/?probe=43f51d50c1) |
| LGC        | 5B10W139       | 50.5  | Li-poly | 109   | [AC71E5B8EF](https://linux-hardware.org/?probe=ac71e5b8ef) |
| SANYO      | 00323341343... | 55.9  | Li-ion  | 108   | [7A47FAB9F3](https://linux-hardware.org/?probe=7a47fab9f3) |
| Notebook   | BAT            | 62    | Li-ion  | 107   | [B63184CD07](https://linux-hardware.org/?probe=b63184cd07) |
| Hewlett... | Primary        | 32    | Li-ion  | 106   | [946FEC8F7D](https://linux-hardware.org/?probe=946fec8f7d) |
| Hewlett... | Primary        | 34    | Li-ion  | 106   | [1F55CA148F](https://linux-hardware.org/?probe=1f55ca148f) |
| TKBSS      | NS2P3SZMC4WR   | 686.9 | Li-ion  | 105   | [66A7F0123F](https://linux-hardware.org/?probe=66a7f0123f) |
| Hewlett... | Primary        | 47    | Li-ion  | 104   | [288E753767](https://linux-hardware.org/?probe=288e753767) |
| Panasonic  | AS16A5K        | 41.4  | Li-ion  | 104   | [4332A351BF](https://linux-hardware.org/?probe=4332a351bf) |
| SANYO      | PABAS024       | 38.9  | Li-ion  | 104   | [7B255B7FE7](https://linux-hardware.org/?probe=7b255b7fe7) |
| LGC        | AC14B18J       | 36.7  | Li-ion  | 103   | [FDE7BAF9E8](https://linux-hardware.org/?probe=fde7baf9e8) |
| Hewlett... | Primary        | 35    | Li-ion  | 102   | [0CBE95253A](https://linux-hardware.org/?probe=0cbe95253a) |
| Lenovo     | BASE-BAT       | 30.0  | Li-poly | 101   | [02B69364A6](https://linux-hardware.org/?probe=02b69364a6) |
|            | 47.52          | 48    | Li-ion  | 99    | [8F22E1BEAA](https://linux-hardware.org/?probe=8f22e1beaa) |
| LGC        | 45N1113        | 23.5  | Li-ion  | 99    | [CCA484A94E](https://linux-hardware.org/?probe=cca484a94e) |
| Emdoor     |  Li-ion        | 38.0  | Li-ion  | 98    | [EC840E7D97](https://linux-hardware.org/?probe=ec840e7d97) |
| Hewlett... | Primary        | 28    | Li-ion  | 97    | [CC5E272CA9](https://linux-hardware.org/?probe=cc5e272ca9) |
| SMP        | 5B10W13933     | 46.0  | Li-poly | 94    | [FD0B6A7A49](https://linux-hardware.org/?probe=fd0b6a7a49) |
| ASUSTek    | X555-50        | 35.8  | Li-ion  | 93    | [75924D49A1](https://linux-hardware.org/?probe=75924d49a1) |
| SMP        | 01AV421        | 24.0  | Li-poly | 92    | [269420C3FE](https://linux-hardware.org/?probe=269420c3fe) |
| ASUSTek    | K55--44        | 49.5  | Li-ion  | 91    | [02AD2B36F1](https://linux-hardware.org/?probe=02ad2b36f1) |
| Hewlett... | Primary        | 55    | Li-ion  | 89    | [7100A33E7E](https://linux-hardware.org/?probe=7100a33e7e) |
| Hewlett... | Primary        | 51    | Li-ion  | 87    | [2BE1A08EF2](https://linux-hardware.org/?probe=2be1a08ef2) |
| Panasonic  | AP19B5L        | 53.0  | Li-ion  | 87    | [7C1423B767](https://linux-hardware.org/?probe=7c1423b767) |
| Hewlett... | Primary        | 30    | Li-ion  | 85    | [1867884EDE](https://linux-hardware.org/?probe=1867884ede) |
| CPT-COS    | L16C2PB1       | 35.3  | Li-poly | 84    | [28AC8FEE12](https://linux-hardware.org/?probe=28ac8fee12) |
| LG         | PABAS024       | 40.0  | Li-ion  | 84    | [F6F1441538](https://linux-hardware.org/?probe=f6f1441538) |
| SANYO      | 45N1001        | 56.2  | Li-ion  | 84    | [567AE7F5BA](https://linux-hardware.org/?probe=567ae7f5ba) |
| WB SR 1    | WB Lion        | 51.3  | Li-ion  | 84    | [0792D1E257](https://linux-hardware.org/?probe=0792d1e257) |
| Razer      | Blade          | 80.2  |         | 83    | [41D33A9029](https://linux-hardware.org/?probe=41d33a9029) |
| Hewlett... | Primary        | 31    | Li-ion  | 82    | [058DBD3D5A](https://linux-hardware.org/?probe=058dbd3d5a) |
| LGC        | L16L2PB3       | 35.0  | Li-poly | 82    | [96D63FF41B](https://linux-hardware.org/?probe=96d63ff41b) |
| Samsung    |                | 58    | Li-ion  | 82    | [14B589709D](https://linux-hardware.org/?probe=14b589709d) |
| Celxpert   | 01AV448        | 45.7  | Li-poly | 78    | [29660BBD04](https://linux-hardware.org/?probe=29660bbd04) |
| Sony       | Li_Ion_4000mA  | 48.8  | Li-ion  | 76    | [FE1DAC78BB](https://linux-hardware.org/?probe=fe1dac78bb) |
| Lenovo ... |                | 28    |         | 75    | [3932889971](https://linux-hardware.org/?probe=3932889971) |
| SMP        | DELL VN3N047   | 41.4  | Li-ion  | 75    | [CAF63A9D0F](https://linux-hardware.org/?probe=caf63a9d0f) |
| ASUSTek    | K53--52        | 57.2  | Li-ion  | 74    | [DBAF532969](https://linux-hardware.org/?probe=dbaf532969) |
| Hewlett... | Primary        | 29    | Li-ion  | 74    | [A941237BF3](https://linux-hardware.org/?probe=a941237bf3) |
| Hewlett... | Primary        | 89    | Li-ion  | 74    | [0D7E58014A](https://linux-hardware.org/?probe=0d7e58014a) |
| NVT        | Framewo        | 55.0  | Li-ion  | 74    | [96671141F9](https://linux-hardware.org/?probe=96671141f9) |
| SIMPLO     | SDI ICR18650   | 48.2  | Li-ion  | 74    | [97F3FD27FA](https://linux-hardware.org/?probe=97f3fd27fa) |
| Hewlett... | Primary        | 33    | Li-ion  | 73    | [07EA9D3C2F](https://linux-hardware.org/?probe=07ea9d3c2f) |
| SMP        | 01AV447        | 45.7  | Li-poly | 73    | [D9ACA3E679](https://linux-hardware.org/?probe=d9aca3e679) |
| Sony       |                | 42    | Li-ion  | 72    | [D6A7454695](https://linux-hardware.org/?probe=d6a7454695) |
| Celxpert   | 01AV424        | 24.1  | Li-poly | 71    | [A4FD7CDAA8](https://linux-hardware.org/?probe=a4fd7cdaa8) |
| CPT-COS    | L14C3P6        | 36.6  | Li-ion  | 71    | [BD97B057E3](https://linux-hardware.org/?probe=bd97b057e3) |
| Notebook   | BAT            | 74    | Li-ion  | 71    | [94CF78A9D9](https://linux-hardware.org/?probe=94cf78a9d9) |
| SMP        | 00HW023        | 23.5  | Li-poly | 71    | [1ECE644FE1](https://linux-hardware.org/?probe=1ece644fe1) |
|            | 48.6           | 49    | Li-ion  | 70    | [481FB97852](https://linux-hardware.org/?probe=481fb97852) |
| Hewlett... | Primary        | 27    | Li-ion  | 70    | [CB00A3E89D](https://linux-hardware.org/?probe=cb00a3e89d) |
| SMP        | DELL TP1GT61   | 60.0  | Li-poly | 70    | [8C73ABE0EE](https://linux-hardware.org/?probe=8c73abe0ee) |
| CPT-COS    | L17C4PB0       | 45.5  | Li-poly | 69    | [36F57D56F8](https://linux-hardware.org/?probe=36f57d56f8) |
| LGC        | 45N1011        | 93.6  | Li-ion  | 69    | [9B5FFC7C58](https://linux-hardware.org/?probe=9b5ffc7c58) |
| ASUSTek    | N56--52        | 57.7  | Li-ion  | 68    | [ED9BD6B127](https://linux-hardware.org/?probe=ed9bd6b127) |
| Hewlett... | Primary        | 26    | Li-ion  | 68    | [6E00C72683](https://linux-hardware.org/?probe=6e00c72683) |
| Hewlett... | Primary        | 42    | Li-ion  | 68    | [DB998ABDAE](https://linux-hardware.org/?probe=db998abdae) |
| OEM        | FX50442        | 48.0  | Li-ion  | 68    | [0713732442](https://linux-hardware.org/?probe=0713732442) |
| SANYO      | 45N1043        | 38.9  | Li-ion  | 68    | [FCF87BE002](https://linux-hardware.org/?probe=fcf87be002) |
| SMP        | DELL VM73283   | 42.0  | Li-poly | 68    | [C158CD6095](https://linux-hardware.org/?probe=c158cd6095) |
| ASUSTek    | F3---24        | 51.3  | Li-ion  | 66    | [DFFA412A98](https://linux-hardware.org/?probe=dffa412a98) |
| LGC        | 45N1005        | 47.5  | Li-ion  | 66    | [A471EAB123](https://linux-hardware.org/?probe=a471eab123) |
| SANYO      | 01AV405        | 26.3  | Li-ion  | 66    | [E1678320FC](https://linux-hardware.org/?probe=e1678320fc) |
| Sunwoda-H  | HB4692Z9ECW-41 | 55.2  | Li-ion  | 66    | [F544702336](https://linux-hardware.org/?probe=f544702336) |
| Notebook   | BAT            | 53    | Li-ion  | 65    | [D770BA8B7B](https://linux-hardware.org/?probe=d770ba8b7b) |
| AS3GWAF3KC | GA50358        | 90.0  | Li-ion  | 64    | [4A5C7432AE](https://linux-hardware.org/?probe=4a5c7432ae) |
| ASUSTek    | X453-42        | 30.1  | Li-ion  | 64    | [DC294F018E](https://linux-hardware.org/?probe=dc294f018e) |
| Celxpert   | L19C3PD6       | 52.5  | Li-poly | 64    | [391C3404D3](https://linux-hardware.org/?probe=391c3404d3) |
| CosMX      | AP20CBL        | 53.0  | Li-ion  | 64    | [CE9F366D7E](https://linux-hardware.org/?probe=ce9f366d7e) |
| Dynapack   | HB4593R1ECW    | 56.3  | Li-ion  | 64    | [43C589627C](https://linux-hardware.org/?probe=43c589627c) |
| Samsung... | DELL P8TC727   | 73.3  | Li-ion  | 64    | [6C3746D120](https://linux-hardware.org/?probe=6c3746d120) |
| SANYO      | GRAPE32        | 48.8  | Li-ion  | 64    | [8154485976](https://linux-hardware.org/?probe=8154485976) |
| SANYO      | L09S6Y02       | 38.9  | Li-ion  | 64    | [376C580DCB](https://linux-hardware.org/?probe=376c580dcb) |
| SMP        | L19M4PC0       | 60.0  | Li-poly | 63    | [C20B6EE7D2](https://linux-hardware.org/?probe=c20b6ee7d2) |
| Sunwoda    | R15B01W        | 60.0  | Li-ion  | 63    | [B3015735E6](https://linux-hardware.org/?probe=b3015735e6) |
|            | 48.84          | 49    | Li-ion  | 62    | [F5D1F04D89](https://linux-hardware.org/?probe=f5d1f04d89) |
| ASUSTek    | K55--47        | 48.4  | Li-ion  | 62    | [81C64D5916](https://linux-hardware.org/?probe=81c64d5916) |
| Hewlett... | 5600           | 62.2  |         | 62    | [F715C6E15C](https://linux-hardware.org/?probe=f715c6e15c) |
| LGC        | 01AV445        | 45.0  | Li-poly | 62    | [44D45B8178](https://linux-hardware.org/?probe=44d45b8178) |
| LGC        | L17L2PF1       | 30.0  | Li-poly | 62    | [B3D3904CEF](https://linux-hardware.org/?probe=b3d3904cef) |
| SMP        | 01AV430        | 57.0  | Li-poly | 62    | [E85E91A7F2](https://linux-hardware.org/?probe=e85e91a7f2) |
| ASUSTek    | F5---22        | 48.4  | Li-ion  | 61    | [1E5BB7661E](https://linux-hardware.org/?probe=1e5bb7661e) |
| SMP        | 00NY493        | 90.0  | Li-poly | 61    | [AD0F22FE34](https://linux-hardware.org/?probe=ad0f22fe34) |
| LGC        | LNV-45N1       | 47.0  | Li-ion  | 60    | [7D55F655BB](https://linux-hardware.org/?probe=7d55f655bb) |
| SIMPLO     | BASE-BAT       | 36.5  | Li-poly | 60    | [537237C180](https://linux-hardware.org/?probe=537237c180) |
| Sunwoda    | 5B10X025       | 45.0  | Li-poly | 60    | [FFCE390164](https://linux-hardware.org/?probe=ffce390164) |
| LGC        | 45N1025        | 57.7  | Li-ion  | 59    | [C20B87316B](https://linux-hardware.org/?probe=c20b87316b) |
| SMP        | L17M3PG2       | 57.0  | Li-poly | 59    | [96A5CA6B92](https://linux-hardware.org/?probe=96a5ca6b92) |
| Hewlett... | Primary        | 54    | Li-ion  | 58    | [0BD59541F9](https://linux-hardware.org/?probe=0bd59541f9) |
| SMP        | DELL DM3WC64   | 60.0  | Li-poly | 58    | [8A7E0B16D5](https://linux-hardware.org/?probe=8a7e0b16d5) |
| Celxpert   | 5B10X026       | 45.0  | Li-poly | 57    | [413341361A](https://linux-hardware.org/?probe=413341361a) |
| Lenovo     |                | 28    |         | 57    | [2CD0131BB6](https://linux-hardware.org/?probe=2cd0131bb6) |
| LGC        | 01AV489        | 23.9  | Li-poly | 57    | [B4CBE5BF11](https://linux-hardware.org/?probe=b4cbe5bf11) |
| Notebook   | BAT            | 35    | Li-ion  | 57    | [5681AB6B5D](https://linux-hardware.org/?probe=5681ab6b5d) |
| SMP        | 02DL005        | 51.0  | Li-poly | 57    | [C5F2F2DB53](https://linux-hardware.org/?probe=c5f2f2db53) |
| SMP        | DELL VM73297   | 42.0  | Li-poly | 57    | [08B4259FA6](https://linux-hardware.org/?probe=08b4259fa6) |
| Sunwoda-H  | HB4692J5ECW-31 | 41.4  | Li-ion  | 57    | [07B498F669](https://linux-hardware.org/?probe=07b498f669) |
| ASUSTek    | K53--27        | 37.8  | Li-ion  | 55    | [8568B17267](https://linux-hardware.org/?probe=8568b17267) |
| Hewlett... | Primary        | 40    | Li-ion  | 55    | [0BA680DD8F](https://linux-hardware.org/?probe=0ba680dd8f) |
| LG         | LGC-LGC        | 80.0  | Li-ion  | 55    | [9D6736BCCD](https://linux-hardware.org/?probe=9d6736bccd) |
| Samsung    |                | 24    | Li-ion  | 55    | [C23908CF42](https://linux-hardware.org/?probe=c23908cf42) |
| SANYO      | 45N1023        | 64.0  | Li-ion  | 55    | [1BD88FF8C7](https://linux-hardware.org/?probe=1bd88ff8c7) |
| Sunwoda-H  | HB4692Z9ECW... | 55.2  | Li-ion  | 55    | [B16EA0055D](https://linux-hardware.org/?probe=b16ea0055d) |
| Hewlett... | Primary        | 52    | Li-ion  | 54    | [D0319BDF17](https://linux-hardware.org/?probe=d0319bdf17) |
| Hewlett... | Primary        | 57    | Li-ion  | 54    | [0D16C9013F](https://linux-hardware.org/?probe=0d16c9013f) |
| Hewlett... | Primary        | 38    | Li-ion  | 54    | [023F1E3CDC](https://linux-hardware.org/?probe=023f1e3cdc) |
| LGC        | 01AV490        | 23.9  | Li-poly | 54    | [56CA260FB1](https://linux-hardware.org/?probe=56ca260fb1) |
| LGC        | 45N1738        | 71.1  | Li-ion  | 54    | [EE4A3F359B](https://linux-hardware.org/?probe=ee4a3f359b) |
| SANYO      | AP13B3K        | 53.4  | Li-ion  | 54    | [E253D5B49B](https://linux-hardware.org/?probe=e253d5b49b) |
| SMP        | AP18E7M        | 58.8  | Li-ion  | 54    | [5F59ACBF0D](https://linux-hardware.org/?probe=5f59acbf0d) |
| LGC        | 02DL004        | 51.0  | Li-poly | 53    | [72AB240431](https://linux-hardware.org/?probe=72ab240431) |
| Notebook   | BAT            | 60    | Li-ion  | 53    | [680BDF5ADA](https://linux-hardware.org/?probe=680bdf5ada) |
| SANYO      | 42T4763        | 47.5  | Li-ion  | 53    | [A411BF80E1](https://linux-hardware.org/?probe=a411bf80e1) |
| SMP        | DELL GD1JP65   | 68.0  | Li-poly | 53    | [EE1B786FD9](https://linux-hardware.org/?probe=ee1b786fd9) |
| Sony       |                | 51    | Li-ion  | 53    | [E252F11A47](https://linux-hardware.org/?probe=e252f11a47) |
| ASUSTek    | 1015PE         | 56.2  | Li-ion  | 52    | [81F71F26FC](https://linux-hardware.org/?probe=81f71f26fc) |
|            |                | 38    | Li-ion  | 52    | [86103B5293](https://linux-hardware.org/?probe=86103b5293) |
| Lenovo ... |                | 38    |         | 52    | [ADE67F432F](https://linux-hardware.org/?probe=ade67f432f) |
| ASUSTek    | K56--30        | 31.7  | Li-ion  | 51    | [62AA75F57A](https://linux-hardware.org/?probe=62aa75f57a) |
| SMP        | 5B10W138       | 45.7  | Li-poly | 51    | [3FB25133EC](https://linux-hardware.org/?probe=3fb25133ec) |
| GLK MRD    |  Li-ion        | 26.6  | Li-ion  | 50    | [30E30A5C3E](https://linux-hardware.org/?probe=30e30a5c3e) |
| LGC        | 5B10X026       | 45.0  | Li-poly | 50    | [353BD3A5B2](https://linux-hardware.org/?probe=353bd3a5b2) |
| SANYO      | 00HW022        | 23.5  | Li-poly | 50    | [E1678320FC](https://linux-hardware.org/?probe=e1678320fc) |
| SANYO      | 42T4799        | 86.6  | Li-ion  | 50    | [FC0430B8FE](https://linux-hardware.org/?probe=fc0430b8fe) |
| SMP        | L14M3P24       | 45.0  | Li-poly | 50    | [4804425ADC](https://linux-hardware.org/?probe=4804425adc) |
| SMP        | L19M3PF7       | 45.0  | Li-poly | 50    | [B3EAC5C97D](https://linux-hardware.org/?probe=b3eac5c97d) |
| ASUSTek    | N550-40        | 59.2  | Li-ion  | 49    | [46A727AE8F](https://linux-hardware.org/?probe=46a727ae8f) |
| LGC KT0... | AP18C8K        | 48.0  | Li-ion  | 49    | [AE9DE10584](https://linux-hardware.org/?probe=ae9de10584) |
| OEM        | AS10D31        | 48.4  | Li-ion  | 49    | [5E29FF0071](https://linux-hardware.org/?probe=5e29ff0071) |
| Toshiba    | PABAS0241231   | 96.0  | Li-ion  | 49    | [A70DA6118B](https://linux-hardware.org/?probe=a70da6118b) |
| Hewlett... | Primary        | 24    | Li-ion  | 48    | [91DE8B5956](https://linux-hardware.org/?probe=91de8b5956) |
| Panasonic  | AS10D51        | 45.4  | Li-ion  | 48    | [9DE636B72E](https://linux-hardware.org/?probe=9de636b72e) |
| SANYO      | AS07B31        | 48.8  | Li-ion  | 48    | [A9A9E21B5A](https://linux-hardware.org/?probe=a9a9e21b5a) |
| APL MRD    |  Li-ion        | 36.5  | Li-ion  | 47    | [C65B530677](https://linux-hardware.org/?probe=c65b530677) |
| Celxpert   | 5B10W138       | 45.7  | Li-poly | 47    | [A9567DC72B](https://linux-hardware.org/?probe=a9567dc72b) |
| Notebook   | BAT            | 45    | Li-ion  | 47    | [A6FC9167F7](https://linux-hardware.org/?probe=a6fc9167f7) |
| Samsung    |                | 45    | Li-ion  | 47    | [44E18A0F72](https://linux-hardware.org/?probe=44e18a0f72) |
| SANYO      | AS07A31        | 48.8  | Li-ion  | 47    | [A2AB102EEB](https://linux-hardware.org/?probe=a2ab102eeb) |
| SMP        | 5B10W139       | 57.0  | Li-poly | 47    | [8EF4F014F2](https://linux-hardware.org/?probe=8ef4f014f2) |
| Sunwoda    | 5B10W13935     | 46.0  | Li-poly | 47    | [27411524DB](https://linux-hardware.org/?probe=27411524db) |
| TPS        | S10            | 44.7  | Li-ion  | 47    | [FFAA34D0C1](https://linux-hardware.org/?probe=ffaa34d0c1) |
| Hewlett... | Primary        | 22    | Li-ion  | 46    | [912213D849](https://linux-hardware.org/?probe=912213d849) |
| LGC        | L11L6Y01       | 43.6  | Li-ion  | 46    | [F51C90CADC](https://linux-hardware.org/?probe=f51c90cadc) |
| SMP        | L17M3PG1       | 52.5  | Li-poly | 46    | [66218C2375](https://linux-hardware.org/?probe=66218c2375) |
| Sunwoda    | HB6081V1ECW-41 | 55.2  | Li-ion  | 46    | [0663975741](https://linux-hardware.org/?probe=0663975741) |
| Celxpert   | 01AY969        | 80.4  | Li-poly | 45    | [D859E0FF10](https://linux-hardware.org/?probe=d859e0ff10) |
| SANYO      | 42T4791        | 56.2  | Li-ion  | 45    | [8BE9A889B7](https://linux-hardware.org/?probe=8be9a889b7) |
| SMP        | L09M6Y02       | 46.4  | Li-ion  | 45    | [2316D5DC8B](https://linux-hardware.org/?probe=2316d5dc8b) |
| ASUSTek    | X200-30        | 33.8  | Li-ion  | 44    | [8C2A91C204](https://linux-hardware.org/?probe=8c2a91c204) |
| Notebook   | BAT            | 36    | Li-ion  | 44    | [CCA307C7DB](https://linux-hardware.org/?probe=cca307c7db) |
| Sony       | PABAS024       | 47.5  | Li-ion  | 44    | [7BEA18122C](https://linux-hardware.org/?probe=7bea18122c) |
| ASUSTek    | T12--22        | 48.4  | Li-ion  | 43    | [B482DC649B](https://linux-hardware.org/?probe=b482dc649b) |
| ASUSTek    | UX325          | 67.3  | Li-ion  | 43    | [92CBB2E876](https://linux-hardware.org/?probe=92cbb2e876) |
| Hewlett... | Primary        | 37    | Li-ion  | 43    | [6569B3D50D](https://linux-hardware.org/?probe=6569b3d50d) |
| Hewlett... | Primary        | 39    | Li-ion  | 43    | [6F8FADFE19](https://linux-hardware.org/?probe=6f8fadfe19) |
| LGC        | 01AV494        | 57.0  | Li-poly | 43    | [1E3CEEF5E6](https://linux-hardware.org/?probe=1e3ceef5e6) |
| LGC        | 45N1147        | 56.2  | Li-ion  | 43    | [CC5F5375D2](https://linux-hardware.org/?probe=cc5f5375d2) |
| SMP        | 45N1045        | 42.8  | Li-ion  | 43    | [14243E79D2](https://linux-hardware.org/?probe=14243e79d2) |
| ASUSTek    | M50--24        | 85.8  | Li-ion  | 42    | [FDF56C0639](https://linux-hardware.org/?probe=fdf56c0639) |
| Celxpert   | L19C3PF5       | 57.0  | Li-poly | 42    | [ABA30BB2D8](https://linux-hardware.org/?probe=aba30bb2d8) |
| Dynapack   | HB4593J6ECW    | 41.2  | Li-ion  | 42    | [13866E78A2](https://linux-hardware.org/?probe=13866e78a2) |
| LGC        | 02DL007        | 50.5  | Li-poly | 42    | [DC352CD9DC](https://linux-hardware.org/?probe=dc352cd9dc) |
| LGC        | 42T4911        | 47.5  | Li-ion  | 42    | [5900D34C9A](https://linux-hardware.org/?probe=5900d34c9a) |
| LGC        | 45N1735        | 47.5  | Li-ion  | 42    | [D159971F77](https://linux-hardware.org/?probe=d159971f77) |
| SANYO      | 45N1777        | 71.3  | Li-ion  | 42    | [22EE871680](https://linux-hardware.org/?probe=22ee871680) |
| SMP        | 5B10X026       | 45.7  | Li-poly | 42    | [5CEE302318](https://linux-hardware.org/?probe=5cee302318) |
| ASUSTek    | UX425          | 67.3  | Li-ion  | 41    | [BB1C4209C7](https://linux-hardware.org/?probe=bb1c4209c7) |
| Hewlett... | Primary        | 18    | Li-ion  | 41    | [57DE0F3103](https://linux-hardware.org/?probe=57de0f3103) |
| Hewlett... | Primary        | 5     | Li-ion  | 41    | [7CA9BF386B](https://linux-hardware.org/?probe=7ca9bf386b) |
| Notebook   | BAT            | 71    | Li-ion  | 41    | [0A33AD889C](https://linux-hardware.org/?probe=0a33ad889c) |
| Panasonic  | AS16B5J        | 62.2  | Li-ion  | 41    | [68847EB1E6](https://linux-hardware.org/?probe=68847eb1e6) |
| SANYO      | AC14B13J       | 37.7  | Li-ion  | 41    | [4D2872E685](https://linux-hardware.org/?probe=4d2872e685) |
| SANYO      | AL10A31        | 24.4  | Li-ion  | 41    | [C26F1D77E6](https://linux-hardware.org/?probe=c26f1d77e6) |
| SMP        | 00HW029        | 52.1  | Li-poly | 41    | [5F50538338](https://linux-hardware.org/?probe=5f50538338) |
| SMP        | 01AV452        | 24.0  | Li-poly | 41    | [B4CBE5BF11](https://linux-hardware.org/?probe=b4cbe5bf11) |
| SMP        | 02DL008        | 50.5  | Li-poly | 41    | [D324A863A5](https://linux-hardware.org/?probe=d324a863a5) |
| Toshiba    | PA3817U-1BRS   | 47.5  | Li-ion  | 41    | [9CABFFBC86](https://linux-hardware.org/?probe=9cabffbc86) |
| ASUSTek    | PA3533U        | 56.2  | Li-ion  | 40    | [A56A3691E9](https://linux-hardware.org/?probe=a56a3691e9) |
| ASUSTek    | X550E26        | 37.4  | Li-ion  | 40    | [658C4A4CBD](https://linux-hardware.org/?probe=658c4a4cbd) |
| Celxpert   | LNV-5B10W13897 | 45.7  | Li-poly | 40    | [84411DF81A](https://linux-hardware.org/?probe=84411df81a) |
| Lenovo     | LCFC           | 23.8  |         | 40    | [FE19098E1D](https://linux-hardware.org/?probe=fe19098e1d) |

