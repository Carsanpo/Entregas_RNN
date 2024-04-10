ASIM/MXGS (ISS)
https://www.asim.dk/index.php
radiacion gamma
que triggers son autenticos y cuales no

BGO (Bismuth Germanium Oxide)
Per al cas de BGO, les columnes son:
#1 Timeline (continuous list of numbers)
#2 Time Stamp of each count in us
#3 Overflow hit flag (0 si tot normal)
#4 Detector bar BGO (Quina de les 12 barres és)
#5 PH [0-1023] (es pot traduir com a energia (200keV-20MeV))
#6 always 0
Trabajar con las columnas 1 y 5

CZT (Cadmium Zinc Telluride)
#1 Timeline (continuous list of numbers)
#2 Time Stamp of each count in us
#3 Mult hit flag (0 si tot normal)
#4 ASICadress [0-1] (Part de la direccio del pixel)
#5 DAU number [0-3] (Part de la direccio del pixel)
#6 DM number [0-15] (Part de la direccio del pixel)
#7 ASIC chanel [0-127] (Part de la direccio del pixel)
#8 PH [0-1023] (es pot traduir com a energia (50-450keV))
#9 always 0
Trabajar con las columnas 1 y 8