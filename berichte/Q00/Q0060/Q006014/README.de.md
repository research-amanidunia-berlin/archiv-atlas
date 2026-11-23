[English](README.md) · [Deutsch](README.de.md)

# Step-Back Prompting Enables Reasoning via Abstraction in Large Language Models

Bericht Q006014 · Quelle deepmind.google · Datum 2023-10-09 · [Original öffnen](https://deepmind.google/research/publications/50274/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Bericht ist ein Auszug: Er beschreibt „Step-Back Prompting“, bei dem Sprachmodelle erst allgemeine Prinzipien aus konkreten Beispielen ableiten und diese dann zum Schlussfolgern verwenden sollen. Laut Abstract erzielte das Verfahren in Tests mit PaLM-2 bei mehreren Aufgaben Leistungszuwächse; nähere Angaben zu Versuchsaufbau und Unsicherheiten enthält der Auszug nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | – | 6 / 16 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | 14 / 27 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
