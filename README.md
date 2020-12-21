# ModuleFPGAblocs1

Diviseur ou comparateur choisi grace à un multiplexeur.

Laboratoire : 2/5

Cours : INF1500 Logique des systèmes numériques

Partenaire : James Brutus


## Objectifs

Modéliser, implémenter et tester un diviseur entier par 4 ou comparateur choisi grace à un multiplexeur, le tout sur 4 bits.

## Utilisations
Logiciel de moélisation : [Vivado 2020.1](https://www.xilinx.com/support/download.html)

École : [Polytechnique Montréal](https://www.polymtl.ca)


## Représentation

### Circuits

Objectif.

![alt text](https://github.com/TritzA/ModuleFPGAblocs1/blob/main/images/image_2020-12-20_221816.png)

UAL final.

![alt text](https://github.com/TritzA/UAL/blob/main/images/UAL.png)

Comparateur 4 bits.

![alt text](https://github.com/TritzA/UAL/blob/main/images/CMP_4B.png)

Diviseur 4 bits.

![alt text](https://github.com/TritzA/UAL/blob/main/images/DIV_4B.png)

Multiplexeur 4 bits.

![alt text](https://github.com/TritzA/UAL/blob/main/images/MUX_2_1_4B.png)

Multiplexeur 1 bit.

![alt text](https://github.com/TritzA/UAL/blob/main/images/MUX_2_1_1B.png)

### Tests

Test exhaustif de l'UAL.

![alt text](https://github.com/TritzA/UAL/blob/main/images/exhaustif.png)

Test centré en A = 0xF de l'UAL.

![alt text](https://github.com/TritzA/UAL/blob/main/images/a_vaut_f.png)

### Implémentation phyisque sur une carte FPGA

Fichier de contraintes en *.txt avant sa modification en *.xdc.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/contraintes.png)

Carte FPGA.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/Nexys4.jpg)

Circuit de la carte FPGA.

![alt text](https://github.com/TritzA/UniteArithmetiqueLogique/blob/main/images/Mapping_Nexys4.png)
