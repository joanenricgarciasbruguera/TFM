# TFM
Aquest repositori de GitHub fa referència al Treball de Fi de Màster (TFM) del Màster Universitari en Sistemes Intel·ligents (UIB),
"Aplicació del model d'Ising a la dinàmica de xarxes d'interacció d'agents financers".
En aquest TFM s'implementa i estudia el treball realitzat per Adam Lipowski en l'aplicació
del model d'Ising als mercats financers. A partir d'aquest treball, en aquest TFM es proposa un nou model 
capaç de regular el comportament gregari dels agents. El repositori està format per:
  calculs
  figures.ipynb
  script_julia_ising.ipynb

* calculs: fitxer que conté els resultats en format csv de les simulacions numèriques que s'han dut a terme al TFM.
* figures.ipynb: notebook de Python 3 amb les figures que presenten a la memòria.
* script_julia_ising.ipynb: notebook de Julia 1.4.2 amb els mètodes implementats per reproduir els resultats.

La implementació dels models es va dur a terme en primera instància amb Python 3, però degut als elevats temps d'execució s'ha canviat 
el llenguatge de programació a Julia 1.4.2, implicant uns temps d'execució menors.
