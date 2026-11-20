[English](README.md) · [Deutsch](README.de.md)

# Perceiver AR: general-purpose, long-context autoregressive generation

Bericht Q003681 · Quelle deepmind.google · Datum 2022-07-16 · [Original öffnen](https://deepmind.google/blog/perceiver-ar-general-purpose-long-context-autoregressive-generation/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Blogbeitrag stellt Perceiver AR vor, eine Architektur, die lange Eingaben in wenige kausal maskierte latente Zustände überführt und so laut den Autorinnen und Autoren effizientere autoregressive Generierung ermöglicht. Sie berichten starke Resultate bei Text-, Bild- und Musikaufgaben; detaillierte Messwerte für alle Benchmarks und eine unabhängige Replikation enthält der Beitrag nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 13 / 46 % | 0 / 0 % | – | 7 / 16 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 11 / 44 % | 0 / 0 % | – | 5 / 12 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 6 / 31 % | 0 / 0 % | – | 6 / 15 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | – |
