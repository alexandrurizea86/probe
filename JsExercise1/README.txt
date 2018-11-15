Am pornit in rezolvarea acestei cerinte de la urmatoarea problema (stackoverflow):
    https://stackoverflow.com/questions/24926028/drag-and-drop-multiple-objects-in-html5-canvas

Am adaugat functii pentru a trata evenimentele diferit in functie de tipul componentei (e.g. cerc, patrat).
De asemenea, tinand cont ca nu toate componentele sunt "draggable", sunt necesare modificari
aduse mecanismului de afisare a elementelor pe canvas.

## Probleme implementare ##
De asemenea, elementele de tip cerc sunt draggable, dar din cauza mecanismului de afisare prin intermediul 
arc-ului, poate fi mutat numai click-uind si dragg-uind cercul prin jumatatea inferior-dreapta a acestuia.