DMI Tables: most popular CPU, RAM and battery
=============================================

This is a repository of decoded DMI tables for various computers collected
by Linux users at https://linux-hardware.org.

The aim of the project is to identify most popular CPU, RAM and battery in modern
computers and share dmidecode reports so that anyone can perform any kind of analysis.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo hw-probe -all -upload

Total reports: 24170.

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
| Intel      | Core i5-3210M                  | 2.50 | 219   | 9084C70732 |
| Intel      | Core i5-3230M                  | 2.60 | 152   | 6251A0DB90 |
| Intel      | Core 2 Duo E8400               | 3.00 | 149   | 439AF540E7 |
| Intel      | Celeron N2840                  | 2.16 | 143   | 2332ED0DD8 |
| Intel      | Pentium B960                   | 2.20 | 140   | 42B284E62D |
| Intel      | Core i5-2410M                  | 2.30 | 139   | 2C0E4BE82C |
| Intel      | Core i5-2450M                  | 2.50 | 139   | 307F08B5FE |
| Intel      | Atom N450                      | 1.66 | 135   | 5031E48DA2 |
| Intel      | Core i3-2350M                  | 2.30 | 134   | 5118CD27DD |
| AMD        | FX -6300 Six-Core              |      | 131   | BF8CFD0B4D |
| Intel      | Core i3-2120                   | 3.30 | 128   | D4AB6C4E06 |
| Intel      | Core i3-2310M                  | 2.10 | 127   | 6D794063DD |
| Intel      | Atom N270                      | 1.60 | 126   | BCFB5FEC5D |
| Intel      | Core i3-3110M                  | 2.40 | 126   | 485C2FB9C0 |
| AMD        | E-450 APU with Radeon HD Gr... |      | 124   | FC53E6761D |
| Intel      | Core 2 Quad Q6600              | 2.40 | 123   | 84ACE23538 |
| Intel      | Core i5-2430M                  | 2.40 | 117   | A9E0A905BD |
| Intel      | Core 2 Duo E7500               | 2.93 | 116   | 2B3693C8F3 |
| Intel      | Core i3 M 370                  | 2.40 | 114   | D5FEC65DF9 |
| Intel      | Core i5-4210U                  | 1.70 | 111   | A807D18119 |
| Intel      | Core i3 M 380                  | 2.53 | 110   | A36FC6A447 |
| Intel      | Core i3-2100                   | 3.10 | 110   | EF2DAAC6D3 |
| AMD        | FX-8350 Eight-Core             |      | 107   | AFDF4A3A9C |
| Intel      | Core i5-7200U                  | 2.50 | 106   | 78818887EE |
| AMD        | Athlon II X2 250               |      | 104   | E5540CB969 |
| Intel      | Atom N2600                     | 1.60 | 103   | 5BD4609615 |
| Intel      | Pentium Dual-Core E5300        | 2.60 | 101   | CED3C3C6BB |
| Intel      | Core i3-3220                   | 3.30 | 100   | 92100B9B64 |
| Intel      | Core i5-8250U                  | 1.60 | 97    | 65B1EB0CA1 |
| Intel      | Core i5-3470                   | 3.20 | 97    | F85FDA7AF0 |
| Intel      | Core i5-2400                   | 3.10 | 95    | D89BBA8D23 |
| Intel      | Pentium 2020M                  | 2.40 | 93    | A7CCDE40EB |
| Intel      | Atom N455                      | 1.66 | 91    | ECD2F0D753 |
| Intel      | Core i7-3770                   | 3.40 | 89    | 779B6B3344 |
| Intel      | Core 2 Duo E6550               | 2.33 | 88    | DE0DC42CA0 |
| Intel      | Core i7-2670QM                 | 2.20 | 86    | A04CA54D26 |
| Intel      | Core i7-8550U                  | 1.80 | 85    | 61DE3D6439 |
| Intel      | Core i7-3630QM                 | 2.40 | 84    | 8CE0C08E9A |
| Intel      | Core i5-6200U                  | 2.30 | 84    | 9F62C51A20 |
| AMD        | FX-8320 Eight-Core             |      | 83    | BB239C7852 |
| Intel      | Pentium Dual-Core T4500        | 2.30 | 82    | D00F8461C6 |
| Intel      | Core i3-2330M                  | 2.20 | 80    | 832F6EF100 |
| Intel      | Core i5-2520M                  | 2.50 | 80    | E6A094ADE5 |
| Intel      | Atom N570                      | 1.66 | 79    | 7C8F8F5E0C |
| Intel      | Pentium 4                      | 3.00 | 78    | 9463E5625F |
| Intel      | Core i7-8750H                  | 2.20 | 78    | 18DC19F3EC |
| Intel      | Core i7-3770K                  | 3.50 | 78    | 44917A35A9 |
| Intel      | Core i5-4460                   | 3.20 | 77    | C222E9C7D2 |
| Intel      | Atom x5-Z8350                  | 1.44 | 77    | AE477CA654 |
| Intel      | Pentium 4                      | 3.00 | 76    | B64547F948 |
| Intel      | Core i7-7700HQ                 | 2.80 | 75    | 961FA2224D |
| Intel      | Core i3-3217U                  | 1.80 | 75    | 4F24AD146B |
| Intel      | Core i5-4200U                  | 1.60 | 75    | F30B5E8075 |
| AMD        | FX -4300 Quad-Core             |      | 73    | 1362FF0163 |
| Intel      | Core i3-3120M                  | 2.50 | 73    | 9C603A17A4 |
| Intel      | Core i5-3337U                  | 1.80 | 72    | 179397B4EA |
| Intel      | Core i3-5005U                  | 2.00 | 72    | CCBB4BE6BB |
| AMD        | A10-4600M APU with Radeon H... |      | 71    | 6447DA85F6 |
| Intel      | Core 2 Duo E4500               | 2.20 | 68    | E643B8ED58 |
| Intel      | Celeron N3050                  | 1.60 | 68    | 32D296FEE0 |
| Intel      | Pentium Dual-Core E5700        | 3.00 | 67    | CBB9AD4CE6 |
| Intel      | Core i5-5200U                  | 2.20 | 67    | 9FC9C18210 |
| Intel      | Core i5 M 460                  | 2.53 | 66    | 15789D122D |
| Intel      | Pentium P6200                  | 2.13 | 66    | 93AB04C913 |
| Intel      | Pentium M processor            | 1.20 | 65    | 8CF7873695 |
| Intel      | Pentium Dual-Core T4300        | 2.10 | 65    | 7834DD5B8F |
| Intel      | Core i7-2600                   | 3.40 | 65    | 6F8237E870 |
| Intel      | Pentium N3540                  | 2.16 | 65    | A0D9281AE2 |
| Intel      | Core i7-6700HQ                 | 2.60 | 65    | 556DD6ED0B |
| Intel      | Pentium 4                      | 3.20 | 64    | 967BB75CBB |
| Intel      | Core i5-2500                   | 3.30 | 64    | B2626606CC |
| Intel      | Pentium Dual-Core T4400        | 2.20 | 63    | 5986AA0AAC |
| Intel      | Core i7-2630QM                 | 2.00 | 63    | 6177430B68 |
| AMD        | Phenom II X4 965               |      | 62    | F1B384A82B |
| Intel      | Core 2 Duo E8500               | 3.16 | 62    | A30E689A9E |
| Intel      | Pentium Dual E2180             | 2.00 | 61    | 53D2EF8D02 |
| Intel      | Core i7-2600K                  | 3.40 | 61    | 0C3D1FCEFE |
| Intel      | Atom Z3735F                    | 1.33 | 61    | 27F3692E24 |
| Intel      | Celeron N2830                  | 2.16 | 61    | 60AED49920 |
| AMD        | Phenom II X4 955               |      | 60    | E722D70419 |
| Intel      | Pentium Dual-Core E5400        | 2.70 | 60    | 71FC19AA7D |
| Intel      | Core 2 Duo E8400               | 3.00 | 60    | EE080EFD68 |
| Intel      | Core i5-2500K                  | 3.30 | 60    | A43E9D5913 |
| Intel      | Core i3-6006U                  | 2.00 | 59    | 3493C4EBA1 |
| AMD        | E-350                          |      | 58    | 72756E903E |
| Intel      | Pentium Dual-Core T4200        | 2.00 | 58    | E6C8F78BDD |
| Intel      | Core i7-3610QM                 | 2.30 | 58    | 0830776CD0 |
| Intel      | Celeron N3060                  | 1.60 | 58    | A14B78EF65 |
| AMD        | Athlon 64 X2 Dual Core 6000+   |      | 57    | 4908CB8960 |
| Intel      | Core 2 Duo E6750               | 2.66 | 57    | 3DCC4EE3D0 |
| Intel      | Core 2 Duo P8400               | 2.26 | 57    | 8263C74190 |
| Intel      | Pentium P6100                  | 2.00 | 57    | E4428DA94F |
| Intel      | Core i5-3570K                  | 3.40 | 57    | 9FFF75FEE2 |
| Intel      | Core i3-6100                   | 3.70 | 57    | A4F2FE8B73 |
| AMD        | FX -4100 Quad-Core             |      | 56    | B2DA218FF6 |
| Intel      | Atom D525                      | 1.80 | 56    | 61CA6E9A9A |
| Intel      | Core i5 M 480                  | 2.67 | 56    | 032EB66625 |
| Intel      | Celeron 2955U                  | 1.40 | 56    | 972580DCF6 |
| AMD        | Athlon 64 X2 Dual Core 5200+   |      | 55    | A26BD26890 |
| AMD        | FX -6100 Six-Core              |      | 55    | 8D6E14813E |
| Intel      | Pentium 4                      | 2.80 | 55    | 4B792E24F9 |
| Intel      | Pentium Dual E2200             | 2.20 | 55    | A5125B3A34 |
| Intel      | Core i3 M 350                  | 2.27 | 55    | 0A084A3FF1 |
| AMD        | Athlon II X4 640               |      | 54    | 064DD1CCBF |
| Intel      | Core i3 M 330                  | 2.13 | 54    | 3619D46367 |
| Intel      | Core i5-3317U                  | 1.70 | 54    | B6260EAFCE |
| Intel      | Core i7-7500U                  | 2.70 | 53    | 25ED159745 |
| Intel      | Pentium Dual E2160             | 1.80 | 53    | 0D49C08D24 |
| Intel      | Core 2 Duo E7200               | 2.53 | 52    | 45021EC259 |
| Intel      | Core i5-2320                   | 3.00 | 52    | 2D378E81BE |
| Intel      | Core i5-4200M                  | 2.50 | 52    | 59DAC5C9A2 |
| AMD        | Athlon II X2 240               |      | 51    | 93E77F9DC3 |
| Intel      | Celeron E3400                  | 2.60 | 51    | 6FDB8DFE61 |
| Intel      | Pentium B950                   | 2.10 | 51    | C790C085ED |
| Intel      | Core i5-3450                   | 3.10 | 51    | 831D7A504B |
| Intel      | Core i5-3570                   | 3.40 | 51    | 2C4F68ECB1 |
| Intel      | Core i7-4770                   | 3.40 | 51    | 0E2A4B6848 |
| Intel      | Core i3-4005U                  | 1.70 | 51    | 3FD761163B |
| AMD        | E-300 APU with Radeon HD Gr... |      | 50    | F396951092 |
| Intel      | Celeron                        | 2.66 | 50    | 83592C8857 |
| Intel      | Core 2 Duo E7400               | 2.80 | 50    | A3F0007670 |
| Intel      | Core 2 Quad Q8300              | 2.50 | 50    | 249DBA1826 |
| Intel      | Pentium G2020                  | 2.90 | 50    | 06052B8628 |
| Intel      | Core i7-4700MQ                 | 2.40 | 50    | 32ECD30DF8 |
| Intel      | Core i7-4790                   | 3.60 | 50    | C7312AA534 |
| Intel      | Pentium D                      | 3.20 | 49    | E587B4122A |
| Intel      | Core 2 Duo T5750               | 2.00 | 49    | F279252F82 |
| Intel      | Core i5 750                    | 2.67 | 49    | B035986A93 |
| Intel      | Core i3-3240                   | 3.40 | 49    | 13AF031E5E |
| Intel      | Core i5-4570                   | 3.20 | 49    | F1886B084F |
| Intel      | Celeron                        | 2.93 | 48    | D0A8B9D7DA |
| Intel      | Core i3-2370M                  | 2.40 | 48    | BEE30FFA1C |
| Intel      | Celeron 1005M                  | 1.90 | 48    | A413F419EF |
| Intel      | Core i5-3330                   | 3.00 | 48    | 481DBAA60F |
| Intel      | Core i3-4130                   | 3.40 | 48    | 15E3126F2C |
| AMD        | C-60 APU with Radeon HD Gra... |      | 47    | A54B8C9315 |
| Intel      | Pentium Dual-Core E5200        | 2.50 | 47    | A5A20E3A8D |
| Intel      | Core i3 550                    | 3.20 | 47    | FF848E7FFB |
| Intel      | Pentium B940                   | 2.00 | 47    | 0832CF2C69 |
| Intel      | Pentium G620                   | 2.60 | 47    | FF8753AFA1 |
| Intel      | Pentium G630                   | 2.70 | 47    | 7CFCB49FC2 |
| Intel      | Core i5-3320M                  | 2.60 | 47    | AD8913BB6B |
| AMD        | A8-4500M APU with Radeon HD... |      | 46    | D93B73AC97 |
| Intel      | Pentium D                      | 2.66 | 46    | 21AE6DBDF0 |
| Intel      | Core 2 Duo E4600               | 2.40 | 46    | 865EB363F8 |
| Intel      | Core i3-7100                   | 3.90 | 46    | B8C562A7E5 |
| Intel      | Core i7-6500U                  | 2.50 | 46    | A43311F999 |
| AMD        | A6-6310 APU with AMD Radeon... |      | 45    | 4DC7D17844 |
| Intel      | Celeron 900                    | 2.20 | 45    | 74221CBEE3 |
| Intel      | Core 2 Duo T6600               | 2.20 | 45    | 3BD04B5CD7 |
| Intel      | Core i5 M 430                  | 2.27 | 45    | 088FFC2823 |
| AMD        | Athlon 64 X2 Dual Core 4000+   |      | 44    | 20F8191625 |
| Intel      | Core i5 760                    | 2.80 | 44    | E40B76E473 |
| Intel      | Celeron B800                   | 1.50 | 44    | 4DB132BB33 |
| Intel      | Celeron B820                   | 1.70 | 44    | 7857E6A77B |
| AMD        | Athlon 64 X2 Dual Core 4200+   |      | 43    | AA6F0FA908 |
| Intel      | Core i3 540                    | 3.07 | 43    | E60C730AE2 |
| Intel      | Core i5-2300                   | 2.80 | 43    | 417453E269 |
| Intel      | Pentium 2117U                  | 1.80 | 43    | E6B4056C8C |
| Intel      | Pentium G3220                  | 3.00 | 43    | DAD43CAD90 |
| Intel      | Core i5-6500                   | 3.20 | 43    | 984F33EE01 |
| Intel      | Pentium G4400                  | 3.30 | 43    | 114CA7D1AB |
| Intel      | Celeron 540                    | 1.86 | 42    | A4D3F8A8AC |
| Intel      | Core 2 Duo E7300               | 2.66 | 42    | B9B80DB558 |
| Intel      | Pentium G2030                  | 3.00 | 42    | E4374EAA46 |
| Intel      | Pentium N3700                  | 1.60 | 42    | 54AFC9D7E6 |
| AMD        | E1-1200 APU with Radeon HD ... |      | 41    | F49AB6DB04 |
| Intel      | Pentium D                      | 3.40 | 41    | 28A9180BC4 |
| Intel      | Core 2 T7200                   | 2.00 | 41    | B39F18123B |
| Intel      | Celeron G530                   | 2.40 | 41    | 6D7E3AA70A |
| Intel      | Core i5-2310                   | 2.90 | 41    | 2DB02E1414 |
| Intel      | Core i3-4010U                  | 1.70 | 41    | B881A7C58C |
| Intel      | Core i3-6100U                  | 2.30 | 41    | 87D31F3F80 |
| AMD        | Athlon 64 X2 Dual Core 5000+   |      | 40    | 6D882902AD |
| AMD        | C-50                           |      | 40    | 8CBAB44CAE |
| Intel      | Core 2 6600                    | 2.40 | 40    | 7B106B9427 |
| Intel      | Celeron G1840                  | 2.80 | 40    | F778A7E362 |
| Intel      | Core i3-4000M                  | 2.40 | 40    | 3E5B3E8D25 |
| Intel      | Core i7-4770K                  | 3.50 | 40    | BAB2716FF6 |
| Intel      | Celeron M processor            | 1.50 | 39    | B7165ADE10 |
| Intel      | Core 2 Duo T7500               | 2.20 | 39    | 64FEC98DF4 |
| Intel      | Atom N2800                     | 1.86 | 39    | 67D7A432DE |
| Intel      | Core i5-4440                   | 3.10 | 39    | 1D2014DD53 |
| Intel      | Core i7-4710HQ                 | 2.50 | 39    | 5B8ADA4B3C |
| Intel      | Core i7-4500U                  | 1.80 | 39    | 33B7BA0542 |
| Intel      | Pentium N3710                  | 1.60 | 39    | 7236E159E0 |
| Intel      | Core i3-4030U                  | 1.90 | 38    | BC300BBD3D |
| Intel      | Core i7-4510U                  | 2.00 | 38    | 23A59BA23A |
| Intel      | Core 2 Quad Q9300              | 2.50 | 37    | 36D3F979DC |
| Intel      | Core i5 M 520                  | 2.40 | 37    | 82CB2D5E90 |
| Intel      | Celeron B815                   | 1.60 | 37    | 6B196867B7 |
| Intel      | Core i7-4790K                  | 4.00 | 37    | 32BCF4D223 |
| AMD        | Athlon 64 X2 Dual Core 4400+   |      | 36    | F3B22A675A |
| Intel      | Pentium 4                      | 3.20 | 36    | 21C788CAAC |
| Intel      | Core 2 Duo T5550               | 1.83 | 36    | CC01255AAA |
| Intel      | Pentium Dual T2390             | 1.86 | 36    | C21C72FEED |
| Intel      | Core i5-7400                   | 3.00 | 36    | 24140DAC5C |
| Intel      | Celeron 430                    | 1.80 | 36    | DD1203BF56 |
| Intel      | Pentium B970                   | 2.30 | 36    | 55153BEE1A |
| Intel      | Core i3-4170                   | 3.70 | 36    | 6DA4739E26 |
| AMD        | A4-5000 APU with Radeon HD ... |      | 35    | 6202D247CD |
| AMD        | Ryzen 3 2200G with Radeon V... |      | 35    | DE065F2CFC |
| Intel      | Core i7-8565U                  | 1.80 | 35    | D1CA80EDFF |
| Intel      | Core 2 Duo T5250               | 1.50 | 35    | 427546EA21 |
| Intel      | Core i3 530                    | 2.93 | 35    | F0971CD52C |
| Intel      | Celeron 1000M                  | 1.80 | 35    | 96C288C457 |
| Intel      | Core i7-6700                   | 3.40 | 35    | BEBF95FDC9 |
| AMD        | Athlon II P320 Dual-Core       |      | 34    | 5ADDDE0384 |
| AMD        | Athlon II X2 220               |      | 34    | 31971EE9A6 |
| AMD        | A4-3300M APU with Radeon HD... |      | 34    | 937DD869FC |
| Intel      | Core 2 Quad Q9400              | 2.66 | 34    | 6949452F0E |
| Intel      | Pentium Dual-Core E6500        | 2.93 | 34    | A55FB3FCA4 |
| AMD        | Athlon 64 X2 Dual Core 4800+   |      | 33    | B656825800 |
| AMD        | Athlon II P340 Dual-Core       |      | 33    | A94427ED76 |
| AMD        | A6-4400M APU with Radeon HD... |      | 33    | C77563A5FB |
| AMD        | Ryzen 5 1600 Six-Core          |      | 33    | 2E3A02EC4D |
| Intel      | Core 2 Duo T5800               | 2.00 | 33    | C6ACD49793 |
| Intel      | Core 2 Duo P8700               | 2.53 | 33    | 25824DFBAE |
| Intel      | Pentium B980                   | 2.40 | 33    | B6EF514918 |
| Intel      | Pentium G860                   | 3.00 | 33    | E2B864CA2E |
| AMD        | Athlon 64 X2 Dual Core 5600+   |      | 32    | 007691F448 |
| AMD        | Athlon II X2 215               |      | 32    | 5492A0F3E3 |
| AMD        | Athlon II X2 245               |      | 32    | E7507BCF5F |
| AMD        | E1-6010 APU with AMD Radeon... |      | 32    | 363B08984A |
| AMD        | Ryzen 7 1700 Eight-Core        |      | 32    | A14B2C7156 |
| AMD        | Ryzen 7 2700X Eight-Core       |      | 32    | E3B6CE369A |
| Intel      | Pentium 4                      | 3.00 | 32    | 60EC6F52F9 |
| Intel      | Pentium Dual-Core E5200        | 2.50 | 32    | 60CA74AFA7 |
| Intel      | Core 2 Duo T8100               | 2.10 | 32    | 4A653FDD06 |
| Intel      | Core i7-3632QM                 | 2.20 | 32    | DA5836E2AA |
| AMD        | Athlon II X2 270               |      | 31    | 792F6ED009 |
| AMD        | E2-1800 APU with Radeon HD ... |      | 31    | 1A825B75E9 |
| Intel      | Core 2 Duo T7250               | 2.00 | 31    | 39BC6E8D0A |
| Intel      | Celeron Dual-Core T3100        | 1.90 | 31    | A7EC10F5EE |
| Intel      | Celeron E3300                  | 2.50 | 31    | 92892F8A8B |
| Intel      | Core 2 Quad Q8400              | 2.66 | 31    | 63957EF2A7 |
| Intel      | Core i5 M 560                  | 2.67 | 31    | 537A117E41 |
| Intel      | Core i5-4670                   | 3.40 | 31    | 26F9516508 |
| Intel      | Core i5-4670K                  | 3.40 | 31    | 2F0B3935B3 |
| AMD        | A6-3400M APU with Radeon HD... |      | 30    | 9C722B6763 |
| AMD        | A8-7410 APU with AMD Radeon... |      | 30    | 2F0C4ABC2E |
| Intel      | Pentium Dual T2370             | 1.73 | 30    | 214044CF8D |
| Intel      | Core 2 T5500                   | 1.66 | 30    | FDEF5F6EBC |
| Intel      | Core 2 Duo P8600               | 2.40 | 30    | 79875B45E4 |
| Intel      | Core 2 Duo T8300               | 2.40 | 30    | 6108B0C47E |
| Intel      | Atom 330                       | 1.60 | 30    | 4DEAD658AD |
| Intel      | Core i7 Q 720                  | 1.60 | 30    | 566E1793D3 |
| Intel      | Core i5-2540M                  | 2.60 | 30    | 3EAB448396 |
| Intel      | Core i7-5500U                  | 2.40 | 30    | D9FB672676 |
| AMD        | A10-5750M APU with Radeon H... |      | 29    | 23388EE023 |

### Memory

| MFG        | Name               | Size     | Type | MT/s | Count | Probe      |
|------------|--------------------|----------|------|------|-------|------------|
|            | Module DIMM        | 2048 MB  | DDR2 | 800  | 520   | B9B80DB558 |
|            | Module SDRAM       | 2048 MB  |      |      | 497   | 6FDB8DFE61 |
|            | Module SDRAM       | 1024 MB  |      |      | 458   | 84495E0FB8 |
|            | Module             | 2048 MB  |      | 800  | 444   | D87E2ED1BC |
|            | Module DIMM        | 2048 MB  | DDR2 | 667  | 368   | 34DC7B3038 |
|            | Module SODIMM      | 1024 MB  | DDR2 | 667  | 366   | 60EC6F52F9 |
|            | Module             | 4096 MB  |      | 1333 | 357   | 0D6CA866B0 |
|            | Module             | 2048 MB  |      | 1333 | 348   | E722D70419 |
|            | Module DIMM        | 1024 MB  | DDR2 | 800  | 320   | AFF249E34F |
| Samsung    | M471B5273DH0-CH... | 4096 MB  | DDR3 | 1334 | 309   | FC266328ED |
|            | Module             | 1024 MB  | DDR2 |      | 261   | B39F18123B |
|            | Module             | 2048 MB  | DDR2 |      | 257   | 3DAAC5C0C6 |
|            | Module             | 1024 MB  |      | 800  | 245   | CF7E7BC433 |
|            | Module SODIMM      | 4096 MB  | DDR3 | 1333 | 216   | 71BD398238 |
| Samsung    | M471B5773CHS-CH... | 2048 MB  | DDR3 | 4199 | 215   | A36FC6A447 |
| Samsung    | M471B5173DB0-YK... | 4096 MB  | DDR3 | 1600 | 212   | 3FD761163B |
|            | Module             | 2048 MB  |      | 667  | 206   | 41F3167FB7 |
| Samsung    | M471B5273CH0-CH... | 4096 MB  | DDR3 | 1334 | 206   | 0832CF2C69 |
|            | Module SODIMM      | 2048 MB  | DDR3 | 1333 | 197   | 307F08B5FE |
| Samsung    | M471B5773DH0-CH... | 2048 MB  | DDR3 | 1600 | 194   | E6A094ADE5 |
| Samsung    | M471B5273DH0-CK... | 4096 MB  | DDR3 | 1600 | 182   | F49AB6DB04 |
| Samsung    | M471B5173QH0-YK... | 4096 MB  | DDR3 | 1600 | 177   | CCBB4BE6BB |
|            | Module             | 1024 MB  |      | 667  | 171   | ABA2A5E5E6 |
|            | Module SDRAM       | 512 MB   |      |      | 157   | 83592C8857 |
|            | SODIMM             | 2048 MB  | DDR2 | 667  | 150   | 6108B0C47E |
| Samsung    | M471B5173EB0-YK... | 4096 MB  | DDR3 | 1600 | 140   | 7236E159E0 |
|            | Module             | 2048 MB  |      | 400  | 129   | 61CA6E9A9A |
|            | Module             | 4096 MB  |      | 1600 | 129   | EE209BFCD3 |
|            | Module DIMM        | 4096 MB  | DDR3 | 1600 | 126   | 1A825B75E9 |
| Elpida     | EBJ41UF8BCS0-DJ... | 4096 MB  | DDR3 | 1334 | 123   | 9E910F8C87 |
|            | Module             | 1024 MB  |      |      | 122   | B656825800 |
|            | Module             | 4096 MB  | DDR3 |      | 122   | A9E0A905BD |
|            | Module             | 1024 MB  | DDR2 | 333  | 120   | 9DF2C0E0DD |
| Kingston   | KHX1600C9D3/4GX... | 4096 MB  | DDR3 | 2400 | 116   | C51735EE45 |
|            | Module DDR         | 1024 MB  |      |      | 115   | 6C6A2138D2 |
| SK Hynix   | HMT351S6CFR8C-P... | 4096 MB  | DDR3 | 1600 | 112   | B9DFF8D7A8 |
| Samsung    | M471B5673FH0-CH... | 2048 MB  | DDR3 | 1334 | 109   | C790C085ED |
|            | SODIMM             | 1024 MB  | DDR2 | 667  | 108   | F279252F82 |
|            | Module DRAM        | 1024 MB  |      |      | 103   | 4AA0EF1314 |
| 48spaces   | 012345678901234... | 2048 MB  | DDR2 | 800  | 99    | ECD2F0D753 |
| Nanya      | NT2GC64B88B0NS-... | 2048 MB  | DDR3 | 1334 | 99    | 832F6EF100 |
| Samsung    | M471B5773DH0-CK... | 2048 MB  | DDR3 | 1600 | 92    | C77563A5FB |
|            | Module             | 2048 MB  |      | 1066 | 90    | F7F43B688E |
|            | Module DDR         | 2048 MB  |      | 1333 | 90    | C87B5D73CA |
|            | Module             | 4096 MB  |      | 400  | 90    | EC1F6C8A0B |
|            | Module             | 2048 MB  | DDR2 | 333  | 88    | E643B8ED58 |
| Samsung    | M471B5673FH0-CF... | 2048 MB  | DDR3 | 1067 | 87    | D5AD200701 |
|            | SODIMM             | 2048 MB  | DDR2 | 800  | 85    | 3A86D13DA1 |
|            | Module DIMM        | 512 MB   | DDR2 |      | 84    | 77353D6C03 |
| SK Hynix   | HMT451S6BFR8A-P... | 4096 MB  | DDR3 | 1600 | 83    | 23A59BA23A |
| Elpida     | EBJ40UG8BBU0-GN... | 4096 MB  | DDR3 | 1600 | 80    | 6A087DD575 |
| Samsung    | M471A5244CB0-CR... | 4096 MB  | DDR4 | 2400 | 80    | EBF0A97D73 |
| Elpida     | EBJ21UE8BFU0-DJ... | 2048 MB  | DDR3 | 1334 | 79    | A94427ED76 |
| Nanya      | NT4GC64B8HB0NS-... | 4096 MB  | DDR3 | 1334 | 78    | 566E1793D3 |
|            | Module             | 2048 MB  |      |      | 78    | B656825800 |
| Kingston   | KHX1600C10D3/8G... | 8192 MB  | DDR3 | 1600 | 76    | 1D2014DD53 |
|            | Module             | 2048 MB  | DDR2 | 400  | 74    | 4908CB8960 |
| Micron     | 16KTF51264HZ-1G... | 4096 MB  | DDR3 | 1600 | 73    | 10B4B2CF4D |
|            | Module SODIMM      | 1024 MB  | DDR2 | 533  | 73    | 543C2B2F79 |
| SK Hynix   | HMT351S6CFR8C-H... | 4096 MB  | DDR3 | 1333 | 72    | 563B794D8A |
| SK Hynix   | HMT325S6BFR8C-H... | 2048 MB  | DDR3 | 1334 | 71    | 67111CA463 |
| SK Hynix   | HMT351S6CFR8C-H... | 4096 MB  | DDR3 | 1334 | 71    | 9084C70732 |
| SK Hynix   | HMT425S6AFR6A-P... | 2048 MB  | DDR3 | 1600 | 70    | 4DA3DE9792 |
|            | Module             | 512 MB   |      |      | 70    | 80274F5B0C |
| SK Hynix   | HMA81GS6AFR8N-U... | 8192 MB  | DDR4 | 2400 | 70    | EECDFA47B7 |
| Kingston   | ACR256X64D3S133... | 2048 MB  | DDR3 | 1334 | 68    | 9FBD6EB508 |
| Kingston   | 99U5471-012.A00... | 4096 MB  | DDR3 | 1600 | 67    | 8130E93C90 |
| Nanya      | NT4GC64B8HG0NS-... | 4096 MB  | DDR3 | 1333 | 67    | 932B7F5689 |
| Samsung    | M471B5173BH0-CK... | 4096 MB  | DDR3 | 1600 | 67    | C5694CCAC0 |
| SK Hynix   | HMT325S6CFR8C-P... | 2048 MB  | DDR3 | 1600 | 66    | 338C59EF86 |
| Samsung    | M471B2873FHS-CH... | 1024 MB  | DDR3 | 1334 | 66    | 150F3BC986 |
| ELPIDA     | EBJ21UE8BDS0-DJ... | 2048 MB  | DDR3 | 1334 | 65    | 06738BD923 |
| Samsung    | M471B1G73QH0-YK... | 8192 MB  | DDR3 | 1600 | 65    | 5B8ADA4B3C |
| Micron     | 8JSF25664HZ-1G4... | 2048 MB  | DDR3 | 1333 | 64    | 82CB2D5E90 |
| SK Hynix   | HMT451S6AFR8A-P... | 4096 MB  | DDR3 | 1600 | 61    | E83BF1EF84 |
| Kingston   | 99U5584-005.A00... | 4096 MB  | DDR3 | 1600 | 61    | 13AF031E5E |
| Micron     | 8KTF51264HZ-1G6... | 4096 MB  | DDR3 | 1600 | 61    | 6251A0DB90 |
|            | Module             | 1024 MB  |      | 400  | 61    | 967BB75CBB |
|            | Module SDRAM       | 4096 MB  |      |      | 61    | C0D7396586 |
| SK Hynix   | HMT351S6CFR8C-P... | 4096 MB  | DDR3 | 1600 | 60    | E884A98FED |
|            | Module DIMM        | 2048 MB  | DDR2 | 533  | 60    | 00931DD0B2 |
|            | Module DDR         | 2048 MB  |      | 800  | 59    | A03802AE0A |
| Samsung    | M471A1K43CB1-CR... | 8192 MB  | DDR4 | 2667 | 59    | C7B13E4BA2 |
| Samsung    | M471B1G73DB0-YK... | 8192 MB  | DDR3 | 1600 | 59    | 17ED1F4194 |
| Ramaxel    | RMT3160ED58E9W1... | 4096 MB  | DDR3 | 1600 | 58    | A90C5BFF19 |
| Ramaxel    | RMT3170EB68F9W1... | 4096 MB  | DDR3 | 1600 | 58    | 6447DA85F6 |
|            | Module DIMM        | 512 MB   | DDR2 | 667  | 57    | C2FC59B6DE |
|            | Module             | 2048 MB  | DDR3 |      | 55    | 6E350F6F96 |
| Samsung    | M471B2873FHS-CF... | 1024 MB  | DDR3 | 1067 | 54    | EBDACCAF79 |
| Samsung    | M471B5273CH0-CK... | 4096 MB  | DDR3 | 1600 | 54    | D93B73AC97 |
| Kingston   | 99U5471-020.A00... | 4096 MB  | DDR3 | 1600 | 53    | 2AD366F4C0 |
| Micron     | 16JSF51264HZ-1G... | 4096 MB  | DDR3 | 1334 | 52    | 832F6EF100 |
| SK Hynix   | HMT451S6BFR8A-P... | 4096 MB  | DDR3 | 1600 | 51    | 972580DCF6 |
|            | Module             | 2048 MB  |      | 1600 | 51    | 60E213070F |
| A-DATA     | AD73I1C1674EV S... | 4096 MB  | DDR3 | 1334 | 50    | 2B1A415AF5 |
|            | Module             | 4096 MB  |      | 667  | 50    | A5C61E8040 |
| Samsung    | M471A5244CB0-CT... | 4096 MB  | DDR4 | 2667 | 50    | 16EA8E9AC4 |
| SK Hynix   | HMT325S6BFR8C-H... | 2048 MB  | DDR3 | 1333 | 49    | 4DB132BB33 |
| Ramaxel    | RMT3020EC58E9F1... | 4096 MB  | DDR3 | 4199 | 49    | 72437E888C |
| Kingston   | ACR16D3LS1KFG/4... | 4096 MB  | DDR3 | 1600 | 48    | 216DFBDCC6 |
| Nanya      | NT2GC64B88G0NS-... | 2048 MB  | DDR3 | 1600 | 48    | 1F85BC5BA6 |
|            | Module DDR         | 512 MB   |      |      | 48    | 24A093E347 |
| SK Hynix   | HMA851S6AFR6N-U... | 4096 MB  | DDR4 | 2667 | 48    | D8A105C994 |
|            | Module SODIMM      | 8192 MB  | DDR3 | 1600 | 47    | AD8913BB6B |
| Samsung    | M471B5673EH1-CF... | 2048 MB  | DDR3 | 4199 | 47    | DEEDE4EDFF |
| SK Hynix   | HMT351S6BFR8C-H... | 4096 MB  | DDR3 | 1333 | 46    | 4273B34994 |
| Kingston   | 99U5469-045.A00... | 4096 MB  | DDR3 | 1600 | 46    | 9C722B6763 |
|            | Module DIMM        | 2048 MB  | DDR3 | 1600 | 46    | 1C4F709995 |
|            | Module             | 4096 MB  |      | 1066 | 46    | 3FEC3F3DC6 |
| Ramaxel    | RMT3010EC58E8F1... | 2048 MB  | DDR3 | 1600 | 46    | 82CB2D5E90 |
| Samsung    | M378B5273DH0-CH... | 4096 MB  | DDR2 | 2133 | 46    | 71F9B6C386 |
| Samsung    | M4 70T5663QZ3-C... | 2048 MB  | DDR2 | 2048 | 46    | D987EBD23A |
| SK Hynix   | HMT351S6CFR8C-P... | 4096 MB  | DDR3 | 1600 | 46    | 5A396EFE06 |
| SK Hynix   | HYMP125S64CP8-S... | 2048 MB  |      | 975  | 46    | 64FEC98DF4 |
|            | Module DDR         | 2048 MB  |      |      | 45    | CCB7CB26D3 |
|            | Module             | 4096 MB  |      | 800  | 45    | 3BD04B5CD7 |
| A-DATA     | AD73I1C1674EV S... | 4096 MB  | DDR3 | 1334 | 44    | 6B196867B7 |
| SK Hynix   | HMT351S6EFR8A-P... | 4096 MB  | DDR3 | 1600 | 44    | A0554A7E66 |
| Samsung    | M378B5773CH0-CH... | 2048 MB  | DDR3 | 1867 | 44    | 2D378E81BE |
| Samsung    | M471B5674QH0-YK... | 2048 MB  | DDR3 | 1600 | 44    | F30B5E8075 |
| Kingston   | ACR16D3LFS1KBG/... | 2048 MB  | DDR3 | 1600 | 43    | AF870DDF65 |
| Kingston   | KHX1866C10D3/8G... | 8192 MB  | DDR3 | 2133 | 43    | 09C02E478D |
|            | Module DIMM        | 8192 MB  | DDR3 | 1333 | 43    | B2D6DABAA7 |
| Samsung    | M378B5673FH0-CH... | 2048 MB  | DDR3 | 1600 | 43    | 2D378E81BE |
| Samsung    | M471B1G73EB0-YK... | 8192 MB  | DDR3 | 1600 | 43    | B12FAB166D |
| Nanya      | NT2GC64B8HC0NS-... | 2048 MB  |      | 1334 | 42    | 867B34CD2B |
|            | Module DRAM        | 2048 MB  |      |      | 42    | 40B94D516E |
| Samsung    | M471B5273EB0-CK... | 4096 MB  | DDR3 | 1600 | 42    | 3CEE9E77BE |
| SK Hynix   | HMT451S6MFR8C-P... | 4096 MB  | DDR3 | 1600 | 42    | 0D165C08F9 |
| SK Hynix   | HMT351U6CFR8C-H... | 4096 MB  | DDR3 | 1600 | 40    | A644A3A3AD |
| SK Hynix   | HMT41GS6BFR8A-P... | 8192 MB  | DDR3 | 1600 | 40    | C7F7A6189C |
|            | Module DIMM DDR    | 1024 MB  |      | 667  | 40    | 44E3D900F5 |
|            | Module             | 1024 MB  | DDR2 | 266  | 40    | D9EABC54C1 |
|            | Module SDRAM       | 256 MB   |      |      | 40    | 83592C8857 |
|            | SODIMM             | 1024 MB  | DDR2 | 533  | 40    | FB4073D000 |
| SK Hynix   | HMT451S6AFR8A-P... | 4096 MB  | DDR3 | 1600 | 39    | A807D18119 |
|            | Module             | 512 MB   |      | 667  | 39    | 6DB0F0B43C |
|            | Module             | 8192 MB  |      | 1333 | 39    | 708DFF507F |
| SK Hynix   | HMT325S6CFR8C-H... | 2048 MB  | DDR3 | 1334 | 39    | 9084C70732 |
| Kingston   | KHX1600C10D3/8G... | 8192 MB  | DDR3 | 1600 | 38    | 78C75E4ACF |
| Kingston   | KHX1866C10D3/4G... | 4096 MB  | DDR3 | 1866 | 38    | 0C3D1FCEFE |
|            | Module             | 4096 MB  |      |      | 38    | 5C9AAAAB05 |
|            | Module             | 2048 MB  | DDR3 | 800  | 37    | 87C67E8141 |
|            | Module DDR         | 4096 MB  |      | 1333 | 37    | E40B76E473 |
| Samsung    | M378B5773DH0-CH... | 2048 MB  | DDR3 | 1333 | 37    | 2D378E81BE |
| Kingston   | ACR16D3LS1NGG/4... | 4096 MB  | DDR3 | 1600 | 36    | A3ACD5E8AB |
| Kingston   | KHX1600C10D3/4G... | 4096 MB  | DDR3 | 1600 | 36    | 97152DC2A4 |
| Micron     | 8KTF25664HZ-1G6... | 2048 MB  | DDR3 | 1600 | 36    | 6251A0DB90 |
|            | Module SDRAM       | 1024 MB  |      | 667  | 36    | AE7A8A6B97 |
| SK Hynix   | HMT351S6BFR8C-H... | 4096 MB  | DDR3 | 1334 | 36    | 3E3F341EF4 |
| ELPIDA     | EBJ20UF8BCS0-DJ... | 2048 MB  | DDR3 | 1334 | 35    | 1476158702 |
| Kingston   | 99U5474-028.A00... | 4096 MB  | DDR3 | 1333 | 35    | FD20ECEEC0 |
|            | Module DDR         | 1024 MB  |      | 800  | 35    | DABC1EE203 |
|            | Module SDRAM       | 2048 MB  |      | 800  | 35    | 3DCC4EE3D0 |
| Ramaxel    | RMT3170ME68F9F1... | 4096 MB  | DDR3 | 1600 | 35    | D759A19F78 |
| SK Hynix   | HMT351S6EFR8C-P... | 4096 MB  | DDR3 | 1600 | 34    | 346458F274 |
| SK Hynix   | Module DIMM        | 4096 MB  | DDR3 | 1066 | 34    | AE477CA654 |
| Kingston   | 99U5428-018.A00... | 8192 MB  | DDR3 | 1600 | 34    | 199C248CC1 |
| Micron     | 4ATF51264HZ-2G6... | 4096 MB  | DDR4 | 2667 | 34    | 6EEF4CAED6 |
|            | Module DIMM DDR    | 2048 MB  |      | 667  | 34    | 0C343F4A5E |
|            | Module DRAM        | 512 MB   |      |      | 34    | 062177DB3D |
| SK Hynix   | HMT451S6AFR8A-P... | 4096 MB  | DDR3 | 1600 | 34    | E654330C94 |
| ASint      | SSZ3128M8-EDJEF... | 2048 MB  | DDR3 | 1333 | 33    | 1F28286A78 |
|            | Module DDR         | 1024 MB  |      | 400  | 33    | 97CC3C4274 |
|            | Module             | 1024 MB  | DDR2 | 400  | 33    | 461D79E9EB |
|            | Module             | 4096 MB  | DDR3 | 800  | 33    | 8230399CC0 |
| ASint      | SSY3128M8-EDJEF... | 1024 MB  | DDR3 | 1333 | 32    | AE90CAFD98 |
| Elpida     | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 32    | 12F5A59D53 |
| SK Hynix   | HMT425S6AFR6A-P... | 2048 MB  | DDR3 | 1600 | 32    | 363B08984A |
|            | Module SDRAM       | 1024 MB  |      | 533  | 32    | DE0DC42CA0 |
| Samsung    | M378B5273CH0-CH... | 4096 MB  | DDR3 | 1867 | 32    | 899A6FEBDE |
| Samsung    | M471B5273CH0-YK... | 4096 MB  | DDR3 | 1600 | 32    | F8184570CF |
| Crucial    | CT51264BA160B.C... | 4096 MB  | DDR3 | 1600 | 31    | E1685D9BA3 |
| ELPIDA     | EBJ21UE8BDS0-AE... | 2048 MB  |      | 1067 | 31    | 5986AA0AAC |
| SK Hynix   | HMA851S6AFR6N-U... | 4096 MB  | DDR4 | 2400 | 31    | 32A2FCF51F |
| Samsung    | M4 70T5663EH3-C... | 2048 MB  | DDR2 | 2048 | 31    | 1F49A84F1F |
|            | 123456789012345... | 1024 MB  | DDR3 | 2400 | 30    | CBA368D785 |
| Crucial    | CT51264BF160B.C... | 4096 MB  | DDR3 | 1600 | 30    | 056AE2C36A |
| SK Hynix   | HMT325S6CFR8C-H... | 2048 MB  | DDR3 | 1333 | 30    | ECACED6F64 |
| Micron     | 4ATF51264HZ-2G3... | 4096 MB  | DDR4 | 2400 | 30    | B81745E987 |
| Nanya      | NT4GC64B8HG0NS-... | 4096 MB  | DDR3 | 1600 | 30    | AD5138A45F |
|            | Module             | 1024 MB  |      | 1333 | 30    | 38598A4379 |
| Samsung    | M471B5773CHS-CF... | 2048 MB  | DDR3 | 1067 | 30    | EBDACCAF79 |
| Kingston   | 99U5469-046.A00... | 4096 MB  | DDR3 | 1333 | 29    | 5CBDF51766 |
|            | Module             | 2048 MB  | DDR2 | 266  | 29    | 2CB4EBD1DF |
| Samsung    | M471A1K43BB1-CR... | 8192 MB  | DDR4 | 2667 | 29    | 7C2CCF2AA7 |
| SK Hynix   | HMT351U6CFR8C-P... | 4096 MB  | DDR3 | 1800 | 28    | F1886B084F |
| SK Hynix   | Module DIMM        | 4096 MB  | DDR3 | 1600 | 28    | 4A970C7F9C |
| Kingston   | 99U5469-041.A00... | 4096 MB  | DDR3 | 1600 | 28    | CD3B715681 |
| Micron     | 16KTF1G64HZ-1G6... | 8192 MB  | DDR3 | 1600 | 28    | 87F64102A9 |
| Micron     | 8ATF1G64HZ-2G6E... | 8192 MB  | DDR4 | 2667 | 28    | 0F6F830F1B |
| Micron     | 8KTF51264HZ-1G6... | 4096 MB  | DDR3 | 1600 | 28    | 0E74429D54 |
| Nanya      | M2S4G64CB8HG5N-... | 4096 MB  | DDR3 | 1334 | 28    | A04CA54D26 |
| SK Hynix   | HMT351S6BFR8C-H... | 4096 MB  | DDR3 | 1333 | 27    | 09FCCD1B05 |
| Kingston   | 99U5428-063.A00... | 8192 MB  | DDR3 | 1600 | 27    | 12F5A59D53 |
| Micron     | 16JSF25664HZ-1G... | 2048 MB  | DDR3 | 1067 | 27    | 09FCCD1B05 |
|            | Module             | 1024 MB  |      | 66   | 27    | F4389CC577 |
|            | Module             | 8192 MB  |      | 1600 | 27    | 4237BD1A34 |
| Samsung    | M471B5173BH0-YK... | 4096 MB  | DDR3 | 1600 | 27    | 363B08984A |
| Samsung    | M471B5273CM0-CH... | 4096 MB  | DDR3 | 1333 | 27    | C790C085ED |
| SK Hynix   | HMT351S6EFR8A-P... | 4096 MB  | DDR3 | 1600 | 27    | 713A72E731 |
| Elpida     | EBJ40UG8EFU0 SO... | 4096 MB  | DDR3 | 1600 | 26    | 179397B4EA |
| Kingston   | KHX1600C9S3L/8G... | 8192 MB  | DDR3 | 1600 | 26    | F00CD48568 |
| Kingston   | KHX1866C9D3/4GX... | 4096 MB  | DDR3 | 1867 | 26    | 0C3D1FCEFE |
| Micron     | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 26    | 0F412B6C32 |
|            | Module SDRAM       | 2048 MB  |      | 533  | 26    | FC04012849 |
| Samsung    | M4 70T2953EZ3-C... | 1024 MB  | DDR2 |      | 26    | 0F6F76F8A1 |
| Samsung    | Module DIMM        | 1024 MB  | DDR2 | 533  | 26    | 9939882441 |
|            | SODIMM             | 1024 MB  | DDR2 | 800  | 26    | 3A86D13DA1 |
| Corsair    | CMX8GX3M2A1600C... | 4096 MB  | DDR3 | 1600 | 25    | FB8D17D634 |
| SK Hynix   | HMT325S6CFR8C-P... | 2048 MB  | DDR3 | 800  | 25    | E884A98FED |
| Micron     | MT8KTF51264HZ-1... | 4096 MB  | DDR3 | 1600 | 25    | 3904BD69E1 |
|            | Module             | 512 MB   | DDR2 | 333  | 25    | B934938C50 |
| SHARETR... | Module SODIMM      | 4096 MB  | DDR3 | 1600 | 25    | B5887147DA |
| SK Hynix   | HMA81GS6CJR8N-V... | 8192 MB  | DDR4 | 2667 | 25    | 0F12A3E78B |
| Corsair    | CMZ8GX3M2A1600C... | 4096 MB  | DDR2 | 1600 | 24    | F9847F8DC5 |
| Kingston   | Module DIMM        | 2048 MB  | DDR2 | 800  | 24    | 6D882902AD |
|            | Module             | 256 MB   |      |      | 24    | 80274F5B0C |
| SK Hynix   | HMA41GS6AFR8N-T... | 8192 MB  | DDR4 | 2133 | 24    | F83C53AEE9 |
| SK Hynix   | HYMP512S64CP8-Y... | 1024 MB  |      | 667  | 24    | FC12FD231D |
|            | SODIMM             | 2048 MB  | DDR2 | 533  | 24    | 2EE51E8201 |
| Elpida     | EBJ40UG8EFU0-GN... | 4096 MB  | DDR3 | 1600 | 23    | AE8B5F3F83 |
| SK Hynix   | HYMP125S64CP8-S... | 2048 MB  | DDR2 | 800  | 23    | 189F28A68E |
| SK Hynix   | HMT41GS6AFR8A-P... | 8192 MB  | DDR3 | 1600 | 23    | 9D71909E26 |
| Kingston   | 99U5428-046.A00... | 4096 MB  | DDR3 | 1334 | 23    | CB04E44290 |
| Kingston   | 99U5471-054.A00... | 8192 MB  | DDR3 | 1600 | 23    | FBE43FC861 |
| Kingston   | ACR16D3LS1KNG/4... | 4096 MB  | DDR3 | 1600 | 23    | E164F394F1 |
| Kingston   | ACR256X64D3S13C... | 2048 MB  | DDR3 | 1334 | 23    | 0290B46D43 |
|            | Module             | 4096 MB  | DDR3 | 1066 | 23    | B7DB1F6D08 |
|            | Module SODIMM      | 4096 MB  | DDR3 | 1067 | 23    | 4BE423D57C |
|            | Module DDR         | 512 MB   |      | 333  | 23    | D14D031927 |
|            | Module DDR         | 512 MB   |      | 400  | 23    | D20509CA50 |
| Ramaxel    | RMT3170EF68F9W1... | 4096 MB  | DDR3 | 1600 | 23    | A4450354FC |
| SK Hynix   | HMT112S6TFR8C-H... | 1024 MB  | DDR3 | 1333 | 23    | 239DB5D282 |
| A-DATA     | AM1L16BC2P1-B1F... | 2048 MB  | DDR3 | 1600 | 22    | A400ADA54A |
| A-DATA     | AM1U16BC4P2-B19... | 4096 MB  | DDR3 | 1600 | 22    | 5E75474417 |
| SK Hynix   | HMT325S6BFR8C-H... | 2048 MB  | DDR3 | 1334 | 22    | C831C850C9 |
| SK Hynix   | HMT451S6MFR8C-P... | 4096 MB  | DDR3 | 1600 | 22    | DAB56079A8 |
| Kingston   | 9905471-001.A01... | 2048 MB  |      | 1600 | 22    | CB82599869 |
| Kingston   | 99U5428-040.A01... | 4096 MB  | DDR3 | 1334 | 22    | 61F7EC13D8 |
| Kingston   | KNWMX1-ETB SODIMM  | 4096 MB  | DDR3 | 1600 | 22    | E7B3F80120 |
|            | Module             | 1024 MB  | DDR3 | 1333 | 22    | E647A34B03 |
|            | Module DIMM        | 2048 MB  | DDR3 | 1067 | 22    | 293EB63C5D |
|            | Module SDRAM       | 2048 MB  |      | 667  | 22    | AE7A8A6B97 |
| Ramaxel    | RMT3170MN68F9F1... | 4096 MB  | DDR3 | 1600 | 22    | C1C9DD614A |
| Samsung    | M471A1K43CB1-CT... | 8192 MB  | DDR4 | 2667 | 22    | 992E2074FF |
| SK Hynix   | HMT451S6BFR8A-P... | 4096 MB  | DDR3 | 1600 | 22    | 4F5D1AE105 |
| SK Hynix   | HYMP112S64CP6-Y... | 1024 MB  |      | 667  | 22    | E5DE762918 |
| Kingston   | KHX1600C9S3L/4G... | 4096 MB  | DDR3 | 1600 | 21    | 1676E72B8C |
| Kingston   | KHX2133C11D3/4G... | 4096 MB  | DDR3 | 2133 | 21    | 81DDFD7F61 |

### Battery

| MFG        | Name          | Wh    | Type    | Count | Probe      |
|------------|---------------|-------|---------|-------|------------|
| Lenovo     | PABAS0241231  | 38.8  | Li-ion  | 267   | F9C34FA042 |
| Samsung    |               | 49    | Li-ion  | 244   | C790C085ED |
| Compal     | PABAS0241231  | 30.9  | Li-ion  | 233   | 5166D85876 |
| ASUSTeK    | ASUS          | 50.1  | Li-ion  | 195   | EF5E47EE93 |
| SANYO      | Li_Ion_4000mA | 47.5  | Li-ion  | 158   | 53ECD14649 |
| Hewlett... | PABAS0241231  | 41.9  | Li-ion  | 135   | 6EEF4CAED6 |
| Samsung    |               | 44    | Li-ion  | 122   | 3A86D13DA1 |
| Notebook   | BAT           | 49    | Li-ion  | 114   | 0E8F6B44E6 |
| SANYO      | AL10B31       | 48.8  | Li-ion  | 92    | 7C8F8F5E0C |
| LG         | Li_Ion_4000mA | 47.5  | Li-ion  | 87    | 7857E6A77B |
| ASUSTeK    | X550A26       | 37.7  | Li-ion  | 80    | A14B78EF65 |
| Samsung    |               | 48    | Li-ion  | 76    | 5118CD27DD |
| PANASONIC  | Li_Ion_4000mA | 47.5  | Li-ion  | 75    | 16478BA376 |
| Hewlett... | Primary       | 48    | Li-ion  | 74    | 59DAC5C9A2 |
| ASUSTek    | K52F-44       | 46.6  | Li-ion  | 72    | 4750F467B4 |
| SANYO      | PABAS0241231  | 55.9  | Li-ion  | 66    | E654330C94 |
| SANYO      | PABAS024      | 85.4  | Li-ion  | 64    | B6EF514918 |
| ASUSTEK    | F82--22       | 46.2  | Li-ion  | 63    | 7EC50CDBEE |
| SANYO      | AS10D31       | 47.5  | Li-ion  | 63    | 9D78BF4EB8 |
| SANYO      | GC86508SAT0   | 41.9  | Li-ion  | 63    | F4585ADF54 |
| Intel SR 1 | SR Real       | 22.1  | Li-ion  | 58    | 4F30AAFDE0 |
| SANYO      | AL12A32       | 37    | Li-ion  | 58    | ACD051D0ED |
| LGC        | 45N1049       | 47.5  | Li-ion  | 57    | 92C25DEB31 |
| LG         | PABAS0241231  | 53.3  | Li-ion  | 56    | E0F719AEB9 |
| Samsung    |               | 58    | Li-ion  | 53    | 2EEDE19D9C |
| LG         | PABAS024      | 52.7  | Li-ion  | 51    | FC338A2AD6 |
| Hewlett... | Primary       | 44    | Li-ion  | 49    | C6F64AAA2B |
| Sony       | VGP-BPS26     | 45.0  | Li-ion  | 49    | A9E0A905BD |
| Hewlett... | Primary       | 42    | Li-ion  | 47    | 708709436E |
| ASUSTeK    | K55--44       | 47.9  | Li-ion  | 46    | 1A825B75E9 |
| ASUSTeK    | X550A30       | 44.6  | Li-ion  | 45    | A0D9281AE2 |
| Samsung    |               | 24    | Li-ion  | 44    | F7520E027B |
| ASUSTEK    | F3---24       | 51.2  | Li-ion  | 43    | 4841CD6D3C |
| Hewlett... | Primary       |       | Li-ion  | 43    | 6C34B57DD0 |
| ASUSTek    | K53--52       | 57.2  | Li-ion  | 41    | 0493D70894 |
| MSI        | BIF0_9        | 53.2  | Li-ion  | 41    | F83C53AEE9 |
| SIMPLO     | PABAS0241231  | 41.6  | Li-ion  | 41    | 6D14F41FBD |
| ASUSTEK    | F5---22       | 47.3  | Li-ion  | 40    | 14EEC92B5D |
| Hewlett... | Primary       | 39    | Li-ion  | 40    | 1053AA1BAD |
| SANYO      | 45N1043       | 38.8  | Li-ion  | 40    | 1C3C62EC29 |
| SANYO      | 0032334134... | 55.9  | Li-ion  | 39    | 3FD761163B |
| Sony       | Li_Ion_4000mA | 47.5  | Li-ion  | 39    | 832F6EF100 |
| OEM        | standard      | 15.8  | Li-ion  | 38    | 199C248CC1 |
| Hewlett... | Primary       | 45    | Li-ion  | 37    | 89E8751AF4 |
| Hewlett... | Primary       | 46    | Li-ion  | 37    | B12FAB166D |
| SANYO      | GRAPE32       | 48.8  | Li-ion  | 37    | E969CCCE8A |
| Hewlett... | 5600          | 62.1  | Li-ion  | 36    | 4A75772380 |
| ASUSTeK    | X555-50       | 37.3  | Li-ion  | 34    | 786924EC40 |
| Hewlett... | Primary       | 40    | Li-ion  | 34    | 6202D247CD |
| SANYO      | L09S6Y02      | 38.8  | Li-ion  | 34    | E69A7237B1 |
| ASUSTEK    | T12--22       | 720.8 | Li-ion  | 33    | BEBBEB331E |
| SMP        | L09M6Y02      | 48.8  | Li-ion  | 33    | 47BBFE4D38 |
| ASUSTek    | X101CH        | 23.7  | Li-ion  | 32    | DB6279F6B9 |
| ASUSTek    | K53--27       | 37.8  | Li-ion  | 32    | 4DB132BB33 |
| Hewlett... | Primary       | 41    | Li-ion  | 32    | 1A4E8CEDDB |
| Hewlett... | Primary       | 50    | Li-ion  | 32    | 10B4B2CF4D |
| LGC        | AC14B8K       | 48.9  | Li-ion  | 32    | F58E07B59C |
| SANYO      | AL15A32       | 37    | Li-ion  | 32    | 7773E6A252 |
| SMP        | bq20z451      | 63.1  | Li-ion  | 32    | 5A84BEDB71 |
|            | 47.52         | 48    | Li-ion  | 31    | F49AB6DB04 |
| Hewlett... | Primary       | 38    | Li-ion  | 31    | 10758FAB29 |
| Hewlett... | Primary       | 43    | Li-ion  | 31    | 7C15CABB87 |
| Samsung    | SR Real       | 43.0  | Li-ion  | 31    | E7A078371A |
| TKBSS      | NS2P3SZMC4WR  | 48.4  | Li-ion  | 31    | AF0C1D5F3C |
| Hewlett... | Primary       | 49    | Li-ion  | 30    | DEFCDB8208 |
| Lenovo     |               | 28    |         | 30    | F2797B8B83 |
| ASUSTek    | 1015PE        | 56.9  | Li-ion  | 29    | 79326DA8CA |
| ASUSTeK    | N56--52       | 56.6  | Li-ion  | 29    | 3BDE09F333 |
| ASUSTeK    | X200-30       | 33.4  | Li-ion  | 29    | 6D7501C42A |
| Hewlett... | Primary       | 55    | Li-ion  | 29    | A1C9FF7880 |
| ASUSTek    | M50--24       | 51.2  | Li-ion  | 28    | B720D65E19 |
|            | Battery       |       |         | 28    | 15D7236D9C |
| SMP        | L16M2PB1      | 30    | Li-poly | 28    | 91D8C5CEC3 |
| ASUSTeK    | X453-42       | 31.6  | Li-ion  | 27    | E69A522EFC |
| LGC        | L11L6Y01      | 43.6  | Li-ion  | 27    | D6B2FD9EC1 |
| ASUSTeK    | K56--30       | 44.6  | Li-ion  | 26    | BD73A2D09B |
| Hewlett... | Primary       | 37    | Li-ion  | 26    | EA1E118AD6 |
| Lenovo     |               | 32    |         | 26    | EE0CB003FC |
| LGC        | AC14B18J      | 36.7  | Li-ion  | 26    | 5C5C71AEB0 |
| Samsung    |               | 45    | Li-ion  | 26    | FFF25A9A01 |
| SANYO      | 45N1773       | 23.2  | Li-ion  | 26    | CE53F07ED9 |
| DP         | bq20z451      | 95.0  | Li-ion  | 25    | 83AFFF14BD |
| Sony       |               | 42    | Li-ion  | 25    | 6E350F6F96 |
| Sony       | PABAS024      | 52.7  | Li-ion  | 25    | 1315834610 |
| Hewlett... | Primary       | 36    | Li-ion  | 24    | CD596675C6 |
| Hewlett... | Primary       | 89    | Li-ion  | 24    | 1D7C1A9789 |
| SANYO      | AP13B3K       | 53.4  | Li-ion  | 24    | 7537E7CB35 |
| SMP        | DELL GPM0365  | 97.0  | Li-ion  | 24    | 18DC19F3EC |
| ASUSTek    | PA3533U       | 51.4  | Li-ion  | 23    | 9A249DA8EE |
|            | 48.84         | 49    | Li-ion  | 22    | E693C5E3B9 |
| Hewlett... | Primary       | 34    | Li-ion  | 22    | 82CB2D5E90 |
| Hewlett... | Primary       | 35    | Li-ion  | 22    | 9C722B6763 |
| Hewlett... | Primary       | 47    | Li-ion  | 22    | 55BD4A5583 |
| OEM        | AS10D31       | 48.4  | Li-ion  | 22    | 19E141A0F7 |
| SANYO      | AL10A31       | 24.4  | Li-ion  | 22    | 5BD4609615 |
| SANYO      | AS09A31       | 47.5  | Li-ion  | 22    | 74221CBEE3 |
| ASUSTeK    | K55--47       | 51.7  | Li-ion  | 21    | 7DEA034FEB |
| ASUSTEK    | PA3533U       | 57.7  | Li-ion  | 21    | AE90CAFD98 |
| Hewlett... | Primary       | 30    | Li-ion  | 21    | 905FA1BD8B |
| Panasonic  | AS10D51       | 47.5  | Li-ion  | 21    | A94427ED76 |
|            | 48.6          | 49    | Li-ion  | 20    | B5293294D6 |
| ASUSTek    | X401-44       | 47.5  | Li-ion  | 20    | CD3B715681 |
| Hewlett... | Primary       | 28    | Li-ion  | 20    | 00C6AFAE23 |
| SANYO      | AS07B31       | 65.1  | Li-ion  | 20    | C6ACD49793 |
| Sony       |               | 51    | Li-ion  | 20    | 1C35FEA298 |
| Sony       | CONIS41       | 48.8  | Li-ion  | 20    | F641323C9D |
| Toshiba    | PA3533U       | 56.1  | Li-ion  | 20    | 72756E903E |
| Lenovo     | BCL3100LiON   | 43.1  | Li-ion  | 19    | BAB3437578 |
| Lenovo ... |               | 32    |         | 19    | A4450354FC |
| SMP        | 45N1045       | 42.7  | Li-ion  | 19    | A90C5BFF19 |
| ASUSTeK    | X550E26       | 37.4  | Li-ion  | 18    | DDE836FF5B |
| ASUSTeK    | X551-30       | 32.6  | Li-ion  | 18    | 5AD90522EC |
| Hewlett... | Primary       | 31    | Li-ion  | 18    | 8962C13BBB |
| Lenovo ... |               | 28    |         | 18    | 3C07CD3DA1 |
| Lenovo     | L11S6Y01      | 38.8  | Li-ion  | 18    | B5887147DA |
| Lenovo     | LCFC          | 31.6  |         | 18    | 14B5F106DB |
| SANYO      | AS07A31       | 48.8  | Li-ion  | 18    | 3EBC919E62 |
| Compal     | PABAS024      | 54.2  | Li-ion  | 17    | 5986AA0AAC |
| CPT-COS    | L16C2PB2      | 30.6  | Li-poly | 17    | FAAF9AC7BA |
| Hewlett... | 5100          | 55.0  |         | 17    | 6814E05B59 |
| Hewlett... | Primary       | 29    | Li-ion  | 17    | 19FA3E985F |
| Hewlett... | Primary       | 32    | Li-ion  | 17    | 215A000BC9 |
| SIMPLO     | MWL32b        | 48.8  | Li-ion  | 17    | 08A3474B8D |
| Acer       | Primary       | 44    | Li-ion  | 16    | F63B72DAC0 |
| ASUSTek    | M50--22       | 47.3  | Li-ion  | 16    | F20A1B20DF |
| ASUSTeK    | N550-40       | 60.4  | Li-ion  | 16    | E5CD52885F |
| Hewlett... | Primary       | 27    | Li-ion  | 16    | E5C53C61E8 |
| PANASONIC  | AS16A5K       | 41.4  | Li-ion  | 16    | 99D56262C0 |
| SANYO      | 45N1001       | 56.1  | Li-ion  | 16    | D4095EF900 |
| SANYO      | L11S6Y01      | 41.9  | Li-ion  | 16    | 46FDE65A43 |
| Sony       | GC86503SY90   | 51.3  | Li-ion  | 16    | 719BE91D02 |
| Toshiba    | PA3817U-1BRS  | 47.5  | Li-ion  | 16    | 3760FFADC6 |
| ASUSTeK    | N750-62       | 69.4  | Li-ion  | 15    | 8E10CD5377 |
| Hewlett... | Primary       | 22    | Li-ion  | 15    | BB92094FD4 |
| LGC        | 45N1127       | 23.4  | Li-ion  | 15    | 92F88BAE64 |
| LGC        | LNV-45N1      | 47.5  | Li-ion  | 15    | C1C9DD614A |
| PANASONIC  | AP16M5J       | 37.0  | Li-ion  | 15    | AE885709D3 |
| SANYO      | 45N1775       | 23.2  | Li-ion  | 15    | 059788B6B9 |
| SIMPLO     | DELL 4DMNG31N | 66.6  | Li-ion  | 15    | 3935C68D79 |
| Simplo     | Li_Ion_4000mA | 48.8  | Li-ion  | 15    | C9C6D4AD6C |
| Sony       | VGP-BPS35A    | 42.3  | Li-ion  | 15    | ADA6FF665C |
| TPS        | S10           | 36.5  | Li-ion  | 15    | A43311F999 |
| 131-42-6E  | HS04041       | 42.0  | Li-ion  | 14    | 2537C26CD2 |
|            |               | 47    | Li-ion  | 14    | 052EF081E3 |
| Compal     | PA3817U-1BRS  | 47.5  | Li-ion  | 14    | 0C917B1E8C |
| Hewlett... | Primary       | 33    | Li-ion  | 14    | B741C8842A |
| NEC        | PC-VP-BP77    | 86.5  | Li-ion  | 14    | 499160C01D |
| PANASONIC  | PABAS024      | 57.5  | Li-ion  | 14    | 6177430B68 |
| ASUSTek    | K53--26       | 39    | Li-ion  | 13    | D0B9F16A5C |
| ASUSTek    | N61--52       | 57.2  | Li-ion  | 13    | 6B772C892D |
| DYNAPACK   | HB4593R1ECW   | 56.3  | Li-ion  | 13    | 61DE3D6439 |
| Hewlett... | Primary       | 16    | Li-ion  | 13    | 06738BD923 |
| Hewlett... | Primary       | 5     | Li-ion  | 13    | B6260EAFCE |
| Hewlett... | Primary       | 54    | Li-ion  | 13    | 3EAB448396 |
| Hewlett... | Primary       | 57    | Li-ion  | 13    | 0B8C8AB6F3 |
| SANYO      | L10S6Y01      | 47.5  | Li-ion  | 13    | 3C20BDA761 |
| SDI        | Dell          | 49    | Li-ion  | 13    | 35FB98B552 |
| Sony       | AS10D41       | 47.5  | Li-ion  | 13    | B13B756085 |
| Toshiba    | PA3465U       | 65.1  | Li-ion  | 13    | 04FEFA3CE2 |
| ASUSTek    | 1001PX        | 46.4  | Li-ion  | 12    | DDBC734D1C |
| ASUSTek    | 1025C         | 56.1  | Li-ion  | 12    | F923747F5E |
| ASUSTEK    | A8---24       | 51.2  | Li-ion  | 12    | 427546EA21 |
| Hewlett... | Primary       | 18    | Li-ion  | 12    | B85810FAD7 |
| Hewlett... | Primary       | 23    | Li-ion  | 12    | D231B98589 |
| Hewlett... | Primary       | 26    | Li-ion  | 12    | 34BC9ED910 |
| LION       |               | 48    |         | 12    | 72878CC6E9 |
| Notebook   | BAT           | 62    | Li-ion  | 12    | 0830776CD0 |
| Notebook   | BAT           | 77    | Li-ion  | 12    | FF0FE48329 |
| SANYO      | AL12B32       | 37    | Li-ion  | 12    | 47615B437F |
| SANYO      | GARDA31       | 48.8  | Li-ion  | 12    | CD4578E8E4 |
| SMP        | DELL G8VCF6C  | 51.9  | Li-poly | 12    | A8CF7BA22D |
| SMP-SDI2.8 | DELL FW1MN31  | 41.4  | Li-ion  | 12    | 4DC7D17844 |
| Toshiba    | PA3534U       | 46.6  | Li-ion  | 12    | CE608A0D1E |
| Toshiba    | PA3534U-1BRS  | 46.6  | Li-ion  | 12    | E6C9D1B45A |
|            | 43.2          | 43    | Li-ion  | 11    | 0F6F76F8A1 |
| ASUSTek    | 1001PXD       | 23.7  | Li-ion  | 11    | CC9E23776C |
| ASUSTek    | N55--52       | 57.2  | Li-ion  | 11    | 1D32FC2BDA |
| ASUSTEK    | UL50-56       | 84    | Li-ion  | 11    | 6439D633F9 |
| ASUSTek    | X202-51       | 38.0  | Li-ion  | 11    | 5BB3C668C2 |
| ASUSTeK    | X551-26       | 37.4  | Li-ion  | 11    | 3904BD69E1 |
|            |               | 24    |         | 11    | 37BFEEE080 |
| Hewlett... | 4400          | 48.8  | Li-ion  | 11    | 0832CF2C69 |
| Hewlett... | Primary       | 20    | Li-ion  | 11    | B881A7C58C |
| Hewlett... | Primary       | 63    | Li-ion  | 11    | 8D43E4B1AB |
| Hewlett... | Primary       | 73    | Li-ion  | 11    | 418918D53F |
| LG         | 004B384234... | 48.9  | Li-ion  | 11    | 23CF8A6381 |
| LGC06      | L10L6Y01      | 48.8  | Li-ion  | 11    | A6CC982E96 |
| Notebook   | BAT           | 33    | Li-ion  | 11    | D4EAA0F0C1 |
| OEM        | AS10D51       | 48.4  | Li-ion  | 11    | 1F28286A78 |
| PANASONIC  | AS10B5E       | 64.8  | Li-ion  | 11    | 6547FBAECA |
| SANYO      | AC13C34       | 30.0  | Li-ion  | 11    | F08AFAA79D |
| SANYO      | AC14B13J      | 38.2  | Li-ion  | 11    | 54AFC9D7E6 |
|            | 48.84         | 49    |         | 10    | 83B1194046 |
|            | 94.576        | 95    | Li-ion  | 10    | 50036892FD |
| ASUSTek    | 1215N         | 57.7  | Li-ion  | 10    | 1D126E3917 |
| ASUSTeK    | N551-52       | 56.1  | Li-ion  | 10    | A8BE285B93 |
| ASUSTek    | UX32-65       | 48.2  | Li-ion  | 10    | E3825A8890 |
| ASUSTek    | X102-30       | 33.4  | Li-ion  | 10    | A7F7276E3D |
| ASUSTeK    | X402--38      | 38.0  | Li-ion  | 10    | 39FEC50B91 |
| Compal     | Li_Ion_4000mA | 47.5  | Li-ion  | 10    | 326131ADDF |
| Hewlett... | Primary       | 14    | Li-ion  | 10    | CEA7815308 |
| Lenovo ... |               | 38    |         | 10    | 5377350816 |
| Lenovo ... |               | 41    |         | 10    | 972580DCF6 |
| LGC        | 42T4911       | 56.1  | Li-ion  | 10    | D10B82AD22 |
| LGC        | 45N1005       | 47.5  | Li-ion  | 10    | DED0A1024C |
| LGC        | 45N1011       | 86.5  | Li-ion  | 10    | 0327550660 |
| LGC        | 45N1025       | 62.1  | Li-ion  | 10    | 047F29B7C7 |
| Notebook   | BAT           | 45    | Li-ion  | 10    | C82361CB3C |
| PAC        | BAT           | 48    |         | 10    | 1676E72B8C |
| PANASONIC  | AS07B51       | 48.6  | Li-ion  | 10    | 649CB24583 |
| Samsung    |               | 38    | Li-ion  | 10    | FA196B80FA |
| SMP        | DELL VN3N047  | 41.4  | Li-ion  | 10    | 5938DFD742 |
| SMP        | DELL Y3F7Y6B  | 41.9  | Li-ion  | 10    | D08F7E2BE4 |
| SMP-SAN2.8 | DELL FW1MN41  | 41.4  | Li-ion  | 10    | 17ED1F4194 |
| Sony       | 45N1111       | 23.2  | Li-poly | 10    | 059788B6B9 |
| Sony       |               | 52    | Li-ion  | 10    | 9E7981F839 |
| Sony       |               | 63    | Li-ion  | 10    | 405F4DEF54 |
| 111-83-72  | HS04041       | 39.5  | Li-ion  | 9     | 1A24B2FB69 |
| 133-42-... | JC04041       | 42.4  | Li-ion  | 9     | 989461CCA6 |
| ASUSTek    | A32-K55       | 64.4  | Li-ion  | 9     | 8FF6A7E718 |
| ASUSTEK    | A6-4224       | 69.9  | Li-ion  | 9     | 17DBD0AEE4 |
| ASUSTek    | K72J-44       | 48.4  | Li-ion  | 9     | E9B489DE35 |
| ASUSTeK    | TP50042       | 48.3  | Li-ion  | 9     | 970FF945D1 |
| Hewlett... | Primary       | 21    | Li-ion  | 9     | 56A12D5F20 |
| Hewlett... | Primary       | 24    | Li-ion  | 9     | C56EC0A2C5 |
| Hewlett... | Primary       | 51    | Li-ion  | 9     | FF5C12BC07 |
| Hewlett... | Primary       | 56    | Li-ion  | 9     | D1A89B5C7B |
| LG         | AS10D81       | 47.5  | Li-ion  | 9     | F56243C8E5 |
| LGC        | 02DL004       | 51.0  | Li-poly | 9     | 1820A998EC |
| Notebook   | BAT           | 60    | Li-ion  | 9     | 844C79C3B9 |
| PAC        | PC-VP-WP93... | 47.5  |         | 9     | ACC8C72C7B |
| SANYO      | 42T4791       | 47.5  | Li-ion  | 9     | BA228615E4 |
| SANYO      | Chapala       | 71.0  | Li-ion  | 9     | 8028F0CCAE |
| SANYO      | NS2P3SZNJ4WR  | 48.7  | Li-ion  | 9     | 5781A29611 |
| SIMPLO     | AS10D73       | 48.8  | Li-ion  | 9     | 2DABFA1484 |
| SMP        | 01AV421       | 24    | Li-poly | 9     | 971B99D081 |
| SMP        | 01AV447       | 45.7  | Li-poly | 9     | 061B2C7F34 |
| Sony       | AS09A41       | 48.8  | Li-ion  | 9     | 184B996E7B |
| SUNWODA    | R15B01W       | 60.0  | Li-ion  | 9     | 4DCFEFF869 |
| 13-54      | MO06062       | 55.5  | Li-ion  | 8     | A2443C2500 |
| ASUSTek    | 1215B         | 56.1  | Li-ion  | 8     | 684866EE94 |
| ASUSTek    | X550E30       | 42.9  | Li-ion  | 8     | 69A2CEC1D7 |
| ASUSTeK    |               |       | Li-ion  | 8     | 179397B4EA |
| ASUSTek    | U31-58        | 81.2  | Li-ion  | 8     | 19D898F4DB |
| ASUSTeK    | UX3-44        | 50.1  | Li-ion  | 8     | A3F0060EB7 |
|            |               |       | Li-ion  | 8     | 6479F7F12B |
|            |               | 16    | Li-ion  | 8     | E647A34B03 |
| Hewlett... | Primary       | 11    | Li-ion  | 8     | 8B37127CB0 |
| Hewlett... | Primary       | 53    | Li-ion  | 8     | 65B1EB0CA1 |
| Lenovo     | BASE-BAT      | 52.5  | Li-poly | 8     | 442F0D1A5A |

