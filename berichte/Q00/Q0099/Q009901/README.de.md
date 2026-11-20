[English](README.md) · [Deutsch](README.de.md)

# (MTL S01E12) MPSGraph

Bericht Q009901 · Quelle gostrobrod.medium.com · Datum 2024-12-29 · [Original öffnen](https://gostrobrod.medium.com/mtl-s01e12-mpsgraph-108be9253a52)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt MPSGraph für Tensorberechnungen in Metal vor und zeigt anhand einer Bildpipeline RGB-YUV-Umwandlung, Helligkeitsnormalisierung und Farbkorrektur. Er erläutert die teils überraschenden Wechsel des zugrunde liegenden Metal-Command-Buffers und warnt vor möglichem internem Speicherbedarf; Benchmarks enthält er nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 10 / 59 % | 0 / 0 % | 40 / 61 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 23 / 82 % | 0 / 0 % | 28 / 52 % | 0 / 0 % | 0 / 0 % |
