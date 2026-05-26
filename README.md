# Olist Marketplace Performance Analyse mit Power BI

## Projektüberblick
Dieses Projekt analysiert den Olist E-Commerce-Datensatz mit Power BI. Ziel ist es, Verkaufsprozesse, Seller Performance, Lieferqualität und Marketingdaten systematisch auszuwerten, Potenziale zu erkennen und konkrete Handlungsempfehlungen für Marketplace-, Sales- und Marketingentscheidungen abzuleiten.

Die Analyse wurde im Rahmen eines Abschlussprojekts im Modul Power BI durchgeführt.

---

## Datensatz
Der Datensatz basiert auf dem Olist E-Commerce-Marktplatz und enthält Informationen zu Bestellungen, Kunden, Produkten, Verkäufern, Bewertungen, Zahlungsinformationen und Marketingdaten.

Enthaltene Analysebereiche:
- Bestellungen und Umsatz
- Produktkategorien
- Kunden- und Verkäuferinformationen
- Lieferdaten und Lieferverzögerungen
- Review Scores
- Zahlungsinformationen
- Marketingdaten zu Leads, Lead-Typen, Profilen und Herkunftskanälen

---

## Analyseziele
- Aufbau eines sauberen Power-BI-Datenmodells
- Analyse von Umsatz, Bestellungen und Marketplace-Performance
- Bewertung von Seller Performance anhand mehrerer Dimensionen
- Untersuchung von Kundenzufriedenheit und Lieferzuverlässigkeit
- Entwicklung eines Seller-Scoring-Modells
- Segmentierung von Sellern nach Potenzial und Qualität
- Analyse der Marketingdaten zur Bewertung von Lead-Gruppen
- Ableitung konkreter Handlungsempfehlungen für Olist

---

## Vorgehen
- Datenimport in Power BI
- Datenbereinigung und Transformation in Power Query
- Korrektur von Datentypen, Datumswerten, Dezimalzahlen und Koordinaten
- Aufbau eines Datenmodells mit Faktentabelle und Dimensionstabellen
- Erstellung einer Datumstabelle
- Ausschluss von stornierten und nicht verfügbaren Bestellungen aus den Haupt-KPIs
- Entwicklung relevanter Measures mit DAX
- Analyse von Umsatz, Bestellungen, Bewertungen und Lieferperformance
- Normierung und Gewichtung einzelner Score-Komponenten
- Erstellung eines Seller Scores
- Ableitung von Seller-Segmenten und Handlungsempfehlungen

---

## Seller-Scoring-Modell
Das Scoring-Modell bewertet Seller anhand von vier Dimensionen:

- Umsatz
- Bestellungen
- Bewertungen
- Lieferperformance

Die Teilbereiche werden auf eine Skala von 0 bis 100 normiert und anschließend gewichtet zu einem Gesamtwert zusammengeführt.

Gewichtung:
- Umsatz: 35 %
- Bestellungen: 20 %
- Bewertungen: 25 %
- Lieferung: 20 %

Nur Seller mit mindestens 50 Bestellungen werden bewertet, um Verzerrungen durch kleine Datenmengen zu reduzieren.

---

## Zentrale Erkenntnisse
- Olist erzielt rund 13,4 Mio. BRL Umsatz bei ca. 97.700 gültigen Bestellungen
- Rund 3.046 Seller verkaufen über den Marketplace
- Die durchschnittliche Bewertung liegt bei etwa 4,0
- Die Top-5-Kategorien machen ca. 40 % des Umsatzes aus
- Die durchschnittliche Verspätungsquote von 7,9 % zeigt Optimierungspotenzial
- Umsatzstarke Seller sind nicht automatisch die besten Seller
- Bewertungen und Lieferperformance sind wichtige Qualitätsindikatoren
- Der Seller Score macht Performance vergleichbar und unterstützt gezielte Priorisierung
- Marketingdaten sollten konsequenter mit späterer Seller Performance verknüpft werden

---

## Handlungsempfehlungen
- Seller Score als Steuerungsinstrument im Account Management einsetzen
- A-Seller priorisiert betreuen
- B- und C-Seller gezielt entwickeln
- D-Seller standardisiert beobachten
- Umsatzstarke Seller mit hoher Verspätungsquote gezielt unterstützen
- Marketingtracking verbessern, um Lead-Qualität früher bewerten zu können
- Marketingbudget stärker auf vielversprechende Lead-Gruppen ausrichten

---

## Verwendete Technologien
- Power BI
- Power Query
- DAX
- Datenmodellierung
- PowerPoint

---

## Projektstruktur
- Power-BI-Datei mit Datenmodell, Measures und Reportseiten
- PowerPoint-Präsentation mit Vorgehen, Ergebnissen und Handlungsempfehlungen

---

## Hinweis
Das Projekt zeigt, wie Power BI zur Entwicklung eines datenbasierten Steuerungsmodells eingesetzt werden kann. Der Seller Score dient als Priorisierungsmodell und nicht als Ausschlussinstrument.
