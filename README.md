# UniteArithmetiqueLogique

Diviseur ou comparateur choisi grace à un multiplexeur.

Laboratoire : 2

Cours : INF1500 Logique des systèmes numériques

Partenaire : James Brutus


## Objectifs

Modéliser un diviseur entier par 4 ou comparateur choisi grace à un multiplexeur, le tout sur 4 bits.

## Utilisations
Logiciel de moélisation : [Vivado 2020.1](https://www.xilinx.com/support/download.html)

École : [Polytechnique Montréal](https://www.polymtl.ca)


## Représentation

### Circuits

UAL final.

![alt text](https://github.com/TritzA/UAL/blob/main/images/UAL.PNG)

Comparateur 4 bits.

![alt text](https://github.com/TritzA/UAL/blob/main/images/CMP_4B.PNG)

Diviseur 4 bits.

![alt text](https://github.com/TritzA/UAL/blob/main/images/DIV_4B.PNG)

Multiplexeur 4 bits.

![alt text](https://github.com/TritzA/UAL/blob/main/images/MUX_2_1_4B.PNG)

Multiplexeur 1 bit.

![alt text](https://github.com/TritzA/UAL/blob/main/images/MUX_2_1_1B.PNG)

### Tests

Test exhaustif de l'UAL.

![alt text](https://github.com/TritzA/UAL/blob/main/images/exhaustif.PNG)

Test centré en A = 0xF de l'UAL.

![alt text](https://github.com/TritzA/UAL/blob/main/images/a_vaut_f.PNG)

### Implémentation phyisque sur une carte FPGA

Fichier de contraintes en *.txt avant sa modification en *.xdc.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/contraintes.PNG)

Carte FPGA.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/Nexys4.jpg)

Circuit de la carte FPGA.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/Mapping_Nexys4.png)
