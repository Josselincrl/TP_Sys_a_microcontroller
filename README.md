# TP_Sys_a_microcontroller
TP de système a microcontrolleur

Salut salut ! :)


################ Partie STM32 #####################

Q.13 PA9 est relié à la masse par ce que c'est le reset et afin que son etat ne sois pas flottant.

Q.14 Ces componsants servent à faire du filtrage entre la partie analogique (VA -> Vanalogique) et la partie numérique (V)


################ Partie LDO #####################
Q.1 Page 1 les condo doivent etre superieur a 0.47uF 

################ Partie DAC #####################

Q.5 Les condos sont spécifiés page 25

Q.6 Le role de la broche notCS est de choisir le chip sur lequel on travail. Dans le cas de ce compansant il met en route l'horlaoge du DAC 
"CS is the Chip Select input pin, which requires an active-low to enable serial clock and data functions."

Q.7 nLDAC permet d'activer la sortie du DAC. Cela peut etre utile pour synchroniser plusieurs DAC. Synchronization Input. This pin is used to transfer DAC settings
(Input Registers) to the output registers (VOUT)"

Q.8 MISO n'est pas utilisé car le DAC recoit unniquement des données. Aucune données vont dans l'autre sens.

################ Partie empreinte #####################

Q.3 0805 0603 sont des tailles normés de composants

Q.4 LQFP, SOT-223, SOIC sont des boitiers 