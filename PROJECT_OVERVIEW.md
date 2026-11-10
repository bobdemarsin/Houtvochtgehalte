# Houtvochtgehalte

## Doel
Een rekentool die laat zien hoeveel vochtig hout krimpt nadat het in een droogoven is gedroogd.

## Doelgroep
Leerlingen van de tweede graad die hout opmeten voor en na het drogen.

## Eerste versie
- Afmetingen vóór en na het drogen invoeren in millimeters.
- Het krimppercentage afzonderlijk tonen voor lengte, breedte en dikte.
- Een korte uitleg tonen van de formule: `(afmeting vóór drogen − afmeting na drogen) ÷ afmeting vóór drogen × 100`.
- Metingen in dezelfde browser bewaren.
- De metingen en resultaten als PDF downloaden, zodat leerlingen die aan de leerkracht kunnen bezorgen.

## Nog niet
- Geen account, online inleveromgeving of leerkrachtdashboard.

## Platform
Een website die leerlingen in een browser op een schoolcomputer kunnen gebruiken. Zo is er niets te installeren.

## Frameworks en bouwstenen
React met Vite voor de interactieve rekentool. Dit past bij één scherm met invoervelden en berekeningen, en kan als statische website gepubliceerd worden.

## Opslag
Metingen worden in de browser bewaard en blijven beschikbaar op hetzelfde toestel en in dezelfde browser. De leerling kan de gegevens als PDF downloaden om met de leerkracht te delen.

## Vormgeving
Gebruikt het design system in `design-system/`.

## Eisen
- De afmetingen worden in mm ingegeven.
- Het krimppercentage wordt per afmeting weergegeven.
- De app toont een korte uitleg bij de formule.
- De resultaten zijn downloadbaar als PDF.

## Publicatie
De website wordt gepubliceerd via GitHub Pages. Elke merge naar de hoofdbranch publiceert de site automatisch via een workflow.
