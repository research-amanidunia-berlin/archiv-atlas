[English](README.md) · [Deutsch](README.de.md)

# A multi-modal transformer for cell type-agnostic regulatory predictions

Bericht Q002485 · Quelle pmc.ncbi.nlm.nih.gov · Datum – · [Original öffnen](https://pmc.ncbi.nlm.nih.gov/articles/PMC11872434/pdf/main.pdf)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt EpiBERT vor, ein Modell, das DNA-Sequenz und Chromatinzugänglichkeit kombiniert, um regulatorische Signale und Genexpression auch in zurückgehaltenen Zelltypen vorherzusagen. Laut den Autor:innen erzielt es dabei teils vergleichbare, teils bessere Ergebnisse als Enformer, doch seine Übertragbarkeit hängt von der Ähnlichkeit neuer Zelltypen zu den Trainingsdaten ab und es bildet wichtige Chromatinmerkmale nicht ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 99 / 100 % | – | 100 / 100 % | 36 / 52 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | – | 98 / 98 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | – | 93 / 95 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 61 / 89 % | – | 58 / 70 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 41 / 73 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 32 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
