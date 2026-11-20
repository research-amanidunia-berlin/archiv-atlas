[English](README.md) · [Deutsch](README.de.md)

# (MTL S02E06) GPU Frame Capture: pt.3 Profiling

Bericht Q009860 · Quelle gostrobrod.medium.com · Datum 2026-01-19 · [Original öffnen](https://gostrobrod.medium.com/mtl-s02e06-gpu-frame-capture-pt-3-profiling-6e9936e0dc80)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt die Instrumente im Performance-Bereich von Xcodes GPU Frame Capture vor: Sie zeigen unter anderem GPU-Aufrufe, Laufzeiten, Ressourcennutzung, Shader und Zähler. Der Autor empfiehlt, für verlässliche Zeitmessungen Instruments zu verwenden, da Profilvergleiche in GPU Frame Capture ungenau sein können.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 4 / 41 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
