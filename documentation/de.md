<!-- ELUCENIA technical documentation · teste-de-fagerstrom · de · no clinical/professional/rights approval -->

# Fagerström-Test

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/teste-de-fagerstrom)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Wie lange nach dem Aufwachen rauchen Sie Ihre erste Zigarette?

`q1`

- `0` — Mehr als 60 Minuten
- `1` — Von 31 bis 60 Minuten
- `2` — Von 6 bis 30 Minuten
- `3` — In den ersten 5 Minuten

### Fällt es Ihnen schwer, an Orten mit Rauchverbot nicht zu rauchen?

`q2`

- `0` — Nein
- `1` — Ja

### Welche Zigarette des Tages ist am befriedigendsten (oder am schwersten aufzugeben)?

`q3`

- `0` — Jede andere
- `1` — Die erste am Morgen

### Wie viele Zigaretten rauchen Sie pro Tag?

`q4`

- `0` — 10 oder weniger
- `1` — 11 bis 20
- `2` — 21 bis 30
- `3` — 31 oder mehr

### Rauchen Sie in den ersten Stunden nach dem Aufwachen häufiger als im restlichen Tagesverlauf?

`q5`

- `0` — Nein
- `1` — Ja

### Rauchen Sie auch, wenn Sie so krank sind, dass Sie die meiste Zeit im Bett bleiben?

`q6`

- `0` — Nein
- `1` — Ja

## Fassung der Methode

FTND/Heatherton 1991:6 Items, gesamt 0–10; kein Original-Tolerance Questionnaire; brasilianisches Protokoll 2020

## Dokumentierte Formel

Sechs Fragen. Zeit zur ersten Zigarette: ≤ 5 min 3, 6–30 min 2, 31–60 min 1, \> 60 min 0. Zigaretten täglich: ≤ 10 0, 11–20 1, 21–30 2, ≥ 31 3. Vier weitere Fragen je 1 für ja (oder „erste morgens“). Gesamt 0–10.

## Grenzen und Population

Die FTND-Ausgabe überarbeitet FTQ und wurde bei Zigarettenrauchern untersucht. Setzen Sie keine gleichwertige Punktbewertung für jedes Nikotinprodukt oder elektronische Gerät voraus. Das zitierte brasilianische Protokoll und die vollständigen Rubriken erfordern in dieser Prüfung noch Primärquellenprüfung.

## Referenzen

- [Heatherton TF, Kozlowski LT, Frecker RC, Fagerström KO. The Fagerström Test for Nicotine Dependence: a revision of the Fagerström Tolerance Questionnaire. Br J Addict, 1991.](https://doi.org/10.1111/j.1360-0443.1991.tb01879.x)

- [Meneses-Gaya IC, Zuardi AW, Loureiro SR, Crippa JAS. Psychometric properties of the Fagerström Test for Nicotine Dependence. J Bras Pneumol, 2009.](https://doi.org/10.1590/S1806-37132009000100011)

- [Brasil. Ministério da Saúde. Protocolo Clínico e Diretrizes Terapêuticas do Tabagismo (Conitec), 2020.](https://www.gov.br/conitec/pt-br/midias/protocolos/pcdt_tabagismo.pdf)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
