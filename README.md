# CSN-EN-50128

* stanovuje soubor požadavků, které musí být splněny během vývoje, nasazení a údržby jakéhokoliv bezpečnostně relevantního software pro drážní řídicí a ochranné aplikace
* definuje požadavky na organizační strukturu, vztahy mezi organizacemi, kvalifikaci a odbornost personálu a rozdělení odpovědnosti týkající se vývoje, nasazení a údržby.
* projekt převádí normu do podoby procesu Eclipse Proces Framework Composeru
* byly vybrány požadavky, jenž podmiňují SIL 4

## Reprezentace úkolů
* úkoly (tasky) jsou rozděleny do balíků podle kapitol a podkapitol
* jsou odvozeny z aktivit popsaných v textu normy
* závislosti mezi úkoly jsou vytvořeny pouze takové, které jsou explicitně uvedeny v normě (např. podmíněné dokumenty)

## Reprezentace rolí
* v normě jsou definovány role v rámci dodavatelské orgaanizace i mimo ni včetně dodavatele samotného
* dodavatel jako role nadřazená několika ostatním je reprezentována jak rolí (aby mohla být přiřazena jako vykonavatel úkolu), tak jako skupina rolí (role set), jenž obsahuje všechny podřazené role i dodavatele samotného

## Reprezentace artefaktů
* artefakty mají danou hiearchii založenou na jejich povaze
* tato hiearchie artefaktů je naznačena na diagramu artefacts.pdf v adresáři doc
* na některých místech je na artefakty odkazováno po skupinách, tyto skupiny jsou v projektu reprezentovány jako typy artefaktů (work product kinds) a zároveň artefakty (aby na ně mohlo být odkazováno z úkolů)
