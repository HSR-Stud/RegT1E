RegT1E - Regelungstechnik 1
======
## Abänderen Seitenrand
Da ich nicht weiss welche Repos vom Submodul betroffen sind, muss es vorerst manuell angepasst werden.

Und zwar im Ordner (Submodul), header.tex
*% Seitenränder*
*\usepackage[left=1cm,right=1cm,top=1cm,bottom=1cm,includeheadfoot]{geometry}*

wird umgeändert zu:                                                                                             
**\usepackage[left=0.5cm,right=0.5cm,top=0.5cm,bottom=0.5cm,includeheadfoot]{geometry}**

# !Achtung!
Sobald dies in HSR-Stud zurück geforkt wird, muss im .gitignore das header.tex wieder gelöscht werden!!

## Ausdruck
* Zusammenfassung am Besten als A5-Booklet ausdrucken

### Licence 
CC BY-NC-SA 3.0 
