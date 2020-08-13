# ag-spiel_analytics

## Intro
Das Fan-Projekt *ag-spiel_analytics* nutzt die Daten-API aus dem AG-Spiel (https://www.ag-spiel.de/).
Wir verwenden vorrangig html/css/js damit die APP einfach im Browser funktioniert.

## Installationsanleitung
Download der Datei ag-spiel_adhoc_analytics.html und anschließend im Brower öffnen.
Die Kompatibilität wird ausschließlich für den Chrome-Brower getestet.

## Feature-Requests
Bitte lasst mich eure Wünsche wissen, welche Daten wollt ihr sehen, kombinieren, auswerten, visualisieren.
Macht bitte einfach einen Issue hier in github auf (https://github.com/SpekulantAC/ag-spiel_analytics/issues)

## Change Log
### v0.4 Top 20 AGs mit geringsten Spreads
- veröffentlicht: 13.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Der Bericht *TOP 20 AGs with lowest Spreads* zeigt die 20 AGs mit dem aktuell geringsten Spreads zwischen Brief- und Geldkurs. Geringe Spreads sprechen für vergleichsweise hohes Vertrauen des Marktes in diese AGs. Möglicherweise ein Qualitätsmerkmal?   

### v0.3 Anleihebuch der Systembank
- veröffentlicht: 13.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Der Bericht *Anleihebuch der Systembank* zeigt die Bargeldzuflüsse aus dem Anleihegeschäft pro Tag. Dieser kann zur Schätzung der künftigen Zinsentwicklung herangezogen werden und gegenenfalls zur Optimierung von Investitionen in Anleihen (Timing) beitragen.  

### v0.2 Total Market
- veröffentlicht: 08.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Zusätzlich werden nun die Informationen zu den AGs aggregiert:
 Marktbewertung (Anzahl Aktien\*Kurs),
 Bargeldbestände,
 Anleihen,
 künfitge Zinserträge aus Anleihen,
 Kredite,
 Kreditkosten

### v0.1 Hello World
- veröffentlicht: 06.08.2020
- Mitwirkende: SpekulantAC
- Änderungen: Die erste Version läde das data.json von https://www.ag-spiel.de/api/get/data.php und zeigt die allgemeinen Informationen an (timestamp, Anzahl AGs, Anzahl Orders 24h, Volumen Orders 24h)

