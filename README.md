# PBL - Satellite Module Design
 
Designed with CATIA, Module 2: Computer and ODH



## File designation

A part will be designed as follows:
      
      NNN_NN

Where:

      the first number refers to the module within the whole project

      the second number refers to  the subset within the module

      the third number refers to  the product within the subset

      the two numbers after the low bar indicate the part within the product
  
## About parametrization

Every part will be parametrized independently and then all parameters will be set and linked in a single CATPart called 'M2_PARAMETROS' which is a product that contains parameter parts named as their product
 

## Subsets, products, and parts 

### Subsets
      20: Module 2: Computer & ODH (Módulo 2: Ordenador) ASSEMBLY
      21: Bandeja
      22: Pseudo-bandeja + ordenador
      23: Separadores
      24: Paneles de cortadura
      25: Paneles de cierre

### Products

Bandeja

      21: 211
      211: Bandeja Módulo 2

Pseudo-bandeja + ordenador

      22: 221
      221: Pseudo-bandeja + ordenador
      
Separadores

      23: 231
      231: Separadores Módulo 2

Paneles de cortadura

      24: 241
      241: Paneles de cortadura Módulo 2

Paneles de cierre

      25: 251
      251: Paneles de cierre Módulo 2


### Parts

Bandeja

      211_01: Bandeja Módulo 2
      211_01_Parameters: Parameters Bandeja Módulo 2

Pseudo-bandeja + ordenador

      221_01: Pseudo-bandeja
      221_02: Shock-absorbers
      221_03: Ordenador
      221_Parameters: Parameters Bandeja Módulo 2
      
Separadores

      231_01: Separadores Módulo 2
      231_01_Parameters: Parameters Separadores Módulo 2
      
Paneles de cortadura

      241_01: Paneles de cortadura Módulo 2
      241_01_Parameters: Parameters Paneles de cortadura Módulo 2

Paneles de cierre

      251_01: Paneles de cierre Módulo 2
      251_01_Parameters: Parameters Paneles de cierre Módulo 2
      
      
More information is given in the description of each .CATIAPART as to avoid any confusion with the number scheme implemented. This will also show in the bill of materials which will make it easier to understand.
