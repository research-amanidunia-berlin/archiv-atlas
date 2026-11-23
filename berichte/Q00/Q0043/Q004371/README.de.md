[English](README.md) · [Deutsch](README.de.md)

# Estimating training compute of deep learning models

Bericht Q004371 · Quelle epoch.ai · Datum 2022-01-20 · [Original öffnen](https://epoch.ai/publications/estimating-training-compute)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Epoch AI stellt eine architekturbasierte FLOP-Zählung und eine Schätzung anhand von GPU-Zeit und Spitzenleistung vor. Beide hängen von Annahmen ab: besonders von Architekturdetails beziehungsweise Hardware, Zahlenpräzision und tatsächlicher GPU-Auslastung; Profiler können ebenfalls ungenau sein. Der Bericht empfiehlt, beide Schätzungen nach Möglichkeit als gegenseitige Plausibilitätskontrolle zu nutzen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 45 / 65 % | 78 / 98 % | 54 / 79 % | 63 / 79 % | 0 / 0 % | 0 / 0 % | 50 / 89 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 55 / 91 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 9 / 46 % | 40 / 67 % | 11 / 30 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 30 / 54 % | 19 / 89 % | 22 / 53 % | 15 / 41 % | 0 / 0 % | 18 / 29 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 5 / 82 % | 28 / 55 % | 6 / 16 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 5 / 43 % | 0 / 0 % | 11 / 30 % | 0 / 0 % | 0 / 0 % | 1 / 18 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 11 / 63 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 9 / 16 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 5 / 49 % | 0 / 0 % | 6 / 21 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
