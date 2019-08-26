# CSN-EN-50128

* stanovuje soubor požadavků, které musí být splněny během vývoje, nasazení a údržby jakéhokoliv bezpečnostně relevantního software pro drážní řídicí a ochranné aplikace
* definuje požadavky na organizační strukturu, vztahy mezi organizacemi, kvalifikaci a odbornost personálu a rozdělení odpovědnosti týkající se vývoje, nasazení a údržby.
* projekt převádí normu do podoby procesu Eclipse Proces Framework Composeru
* byly vybrány požadavky, jenž podmiňují SIL 4

## Reprezentace úkolů (tasků)
* úkoly (tasky) jsou rozděleny do balíků podle kapitol a podkapitol normy
* jsou odvozeny z aktivit popsaných v textu normy
* v projektu jsou pouze ty úkoly, jenž jsou přímo uvedené i v normě (typicky např. napsání dokumentu), přímo tak neodráží veškeré činnosti, které je potřeba v rámci procesu vykonávat i ve skutečnosti
* většina úkolů popsaných v normě nemá jednoznačně definovaný vstup a výstup
* některé úkoly jsou v normě duplikované (například napsání specifikace testů aplikace – body normy 8.4.4.5/8.4.5.2)

## Reprezentace závislostí mezi úkoly
* závislosti mezi úkoly jsou vytvořeny pouze takové, které jsou explicitně uvedeny v normě (např. podmíněné dokumenty)
* norma ve většině případů přímo neurčuje závislosti mezi jednotlivými úkoly a tedy ani pořadí, ve kterém je vhodné je vykonávat

## Reprezentace rolí
* v normě jsou definovány role v rámci dodavatelské orgaanizace i mimo ni včetně dodavatele samotného
* dodavatel jako role nadřazená několika ostatním je reprezentována jak rolí (aby mohla být přiřazena jako vykonavatel úkolu), tak jako skupina rolí (role set), jenž obsahuje všechny podřazené role i dodavatele samotného
* u většiny úkolů v normě není jasně stanoven vykonavatel, v takovém případě je v rámci procesu za vykonavatele označena role dodavatele
* role a jejich odpovědnosti uvedené v příloze B (normativní) jsou přímo začleněny v rámci popisu jednotlivých rolí v procesu

## Reprezentace artefaktů
* artefakty mají danou hiearchii založenou na jejich povaze
* tato hiearchie artefaktů je naznačena na diagramu artefacts.pdf v adresáři doc
* na některých místech je na artefakty odkazováno po skupinách, tyto skupiny jsou v projektu reprezentovány jako typy artefaktů (work product kinds) a zároveň artefakty (aby na ně mohlo být odkazováno z úkolů), tyto skupiny artefaktů však nejsou v normě přímo definovány
* autoři artefaktů a zodpovědné role jsou určeny dle tabulky C.1 – Kontrolní souhrn dokumentů, která je však pouze informativní
* specifikace artefaktů jsou vzaty z těch bodů normy, které jsou typicky uvozeny „Požadavky ... až ... se týkají <artefaktu>.“
* dále jsou součástí specifikací artefaktů všechny body normy, které tyto artefakty popisují/zmiňují
* v normě se vyskytují artefakty, k nimž nenáleží žádný úkol na jejich vytvoření (typicky artefakty vztahující se ke generického softwaru)
