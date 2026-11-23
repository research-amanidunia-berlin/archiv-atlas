[English](README.md) · [Deutsch](README.de.md)

# Performance improves 13x when switching from FP32 to tensor-INT8

Bericht Q006157 · Quelle epoch.ai · Datum 2024-10-23 · [Original öffnen](https://epoch.ai/data-insights/hardware-performance-trend)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Epoch AI zufolge steigt die aggregierte Hardwareleistung gegenüber nicht tensorbasiertem FP32 im Mittel etwa um den Faktor 6 mit TF32, 11 mit Tensor-FP16/BF16 und 13 mit INT8; beim H100 nennt der Bericht für INT8 sogar den Faktor 59. Die Werte beruhen auf geschätzten Format-Trends und variieren zwischen Chips; die Vergleiche decken typischerweise erst den Zeitraum ab etwa 2016 ab und sagen nicht unmittelbar die Beschleunigung konkreter Anwendungen voraus.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 12 / 77 % | 83 / 95 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
