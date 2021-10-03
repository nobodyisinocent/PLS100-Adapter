# PLS100 PCB Adapter

![pcb-final](https://user-images.githubusercontent.com/80821708/135584468-13270c0e-cef6-4cf4-8371-452aca3065be.png)
Final version of the pcb's adapter.

# Why a such adapter
This adapter is useful for programming PLS100 PLA with ALL-03 & ALL-07 programmers to replace the orignal PLA chip of the Commodore 64.

The schematic of the adapter has been made by Tinhead. Many thanks to him for his autorization of the publication of this adapter.

For informations about the HI-LO universal parallel programmer, you can visit the following very interesting resources page made by Matthieu Benoit:
http://matthieu.benoit.free.fr/hilosystem_all-07_universal_programmer.htm

# Prototype adapter's pictures:
The prototype has been assembled, tested and validated by Lolof.

![1633015156800](https://user-images.githubusercontent.com/80821708/135536298-2cba94d8-4857-4d01-be51-67288b8df728.jpg)

![1633015156812](https://user-images.githubusercontent.com/80821708/135536301-30e64171-836b-46ff-a20a-f811aec49ba1.jpg)

![1633015156824_resultat](https://user-images.githubusercontent.com/80821708/135588524-aefd67b9-7a7a-4eac-bbe9-160f5e8a7088.jpg)

# Adapter onto the ALL-03 programmer
Please pay attention to the orientation of the adapter and the PLA onto the programmer. This orientation is the same for the ALL-07 programmer.
A wrong orientation will destroy the PLA.

![1633026784102_resultat](https://user-images.githubusercontent.com/80821708/135588559-c5fdf837-8838-4d8e-ba8b-8952af01e64c.jpg)

![1633026784117_resultat](https://user-images.githubusercontent.com/80821708/135588572-e705a10a-a0a5-4c49-9695-b97456b70c08.jpg)

# About the project files
The complete project is available here for downloading.

The project has been made with Kicad: https://www.kicad.org/

and FreeRooting: https://github.com/freerouting/freerouting under Linux.

#BOM
Here is the BOM made by Lolof. Thanks to him !

|Id	|Designator	|Package	|Quantity	|Designation	|Reichelt part number	|Link  |
|---|---|---|---|---|---|---|
|1	|D1,D2      |	D_DO-41_SOD81_P7.62mm_Horizontal	|2	|UF10-005	|UF 4003	|https://www.reichelt.de/de/fr/diode-de-redressement-ultrarapide-do41-200-v-1-a-uf-4003-p42034.html |
|2	|D3 to D8   |	D_DO-35_SOD27_P7.62mm_Horizontal	|6	|1N4150	|1N 4148	|https://www.reichelt.de/de/fr/diode-de-commutation-100-v-150-ma-do-35-1n-4148-p1730.html |
|3	|Q1,Q2	    |TO-18-3	|2	|2N2222A	|2N 2222A	|https://www.reichelt.de/de/fr/transistor-npn-to-18-40-v-0-8-a-0-5-w-2n-2222a-p1968.html |
|4	|R1,R3	    |R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	|2	|1K	METALL |1,00K	|https://www.reichelt.de/de/fr/r-sistance-film-m-tallique-de-1-00-kohms-metall-1-00k-p11403.html?r=1 |
|5	|R2,R4	    |R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal	|2	|3K3	METALL |3,30K	|https://www.reichelt.de/de/fr/r-sistance-film-m-tallique-de-3-30-kohms-metall-3-30k-p11693.html?&trstct=pos_0&nbc=1 |
|6	|U1 |DIP-40_W15.24mm	|1	|ZIF HEADER| |  |
|7	|ZIF-HEADER	|DIP-28_W15.24mm	|1	|ZIF|	|  |

