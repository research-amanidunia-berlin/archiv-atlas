[English](README.md) · [Deutsch](README.de.md)

# What’s the backward-forward FLOP ratio for neural networks?

Bericht Q003775 · Quelle epoch.ai · Datum 2021-12-13 · [Original öffnen](https://epoch.ai/publications/backward-forward-FLOP-ratio)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht leitet theoretisch ein Rückwärts-zu-Vorwärts-Verhältnis von etwa 1:1 bis 3:1 her und bezeichnet 2:1 für tiefe Netze mit großen Batches als typischen Wert. Messungen stützen diese Einschätzung, doch mögliche Über- und Unterzählungen des verwendeten Profilers lassen einen Rest an Unsicherheit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 4 / 57 % | 0 / 0 % | 85 / 91 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 6 / 63 % | 0 / 0 % | 25 / 47 % | 27 / 49 % | 0 / 0 % |
