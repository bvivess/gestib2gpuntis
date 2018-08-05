# gestib2gpuntis
Compara el codi de les matèries de l'XML generat pel GestIB d'un any amb el del següent, modificant els codis modificats

Baixar el repositori
====================

git clone https://github.com/bvivess/gestib2gpuntis.git

Per executar
===========
python gestib2gpuntis.py -g ExportacioDadesHoraris_2018.xml ExportacioDadesHoraris_2019.xml -a

Opcions obligatòries
====================
  -g/--gestib origen desti : Especifica els fitxers XML generats per l'aplicació Gestib ORIGEN i DESTÍ

Opció de l'operació a realitzar
===============================
    -v/--view : Veure els canvis que hi hauria
    -a/--apply : Aplicar els canvis, creant un arxiu de sortida 'output.xml'