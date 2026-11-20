[English](README.md) · [Deutsch](README.de.md)

# Data, Architecture, or Losses: What Contributes Most to Multimodal Transformer Success?

Bericht Q002573 · Quelle deepmind.google · Datum 2021-02-02 · [Original öffnen](https://deepmind.google/blog/data-architecture-or-losses-what-contributes-most-to-multimodal-transformer-success/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht führt die Stärke multimodaler Transformer gegenüber getrennten Bild- und Sprachencodern hauptsächlich auf multimodale Aufmerksamkeit zurück, die den Austausch zwischen den Modalitäten ermöglicht. Außerdem berichtet er, dass Datenrauschen und die Nähe der Bildbeschreibungen zur Evaluationsaufgabe neben der Datensatzgröße wichtig sind; bessere Bildverluste und mehr Robustheit bleiben offene Herausforderungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 22 / 56 % | 0 / 0 % | 38 / 57 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 12 / 52 % | 0 / 0 % | 23 / 43 % | 5 / 13 % | 0 / 0 % | 4 / 12 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
