[English](README.md) · [Deutsch](README.de.md)

# Few-Shot Recalibration of Language Models

Bericht Q005225 · Quelle deepmind.google · Datum 2024-03-27 · [Original öffnen](https://deepmind.google/research/publications/47848/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Text enthält nur den Abstract, nicht den vollständigen Artikel. Er beschreibt ein Verfahren, das Konfidenzwerte von Sprachmodellen anhand weniger ungelabelter Beispiele für einzelne Bereiche nachkalibrieren soll; laut Abstract verbessert es unter anderem den Kalibrierungsfehler von PaLM2-Large auf MMLU um 16 Prozent gegenüber Temperature Scaling. Weitere Versuchsdetails und Einschränkungen sind im Auszug nicht enthalten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 7 / 44 % | 94 / 97 % | 8 / 22 % | 0 / 0 % | 5 / 16 % | 0 / 7 % | 18 / 33 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 41 / 74 % | 76 / 92 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
