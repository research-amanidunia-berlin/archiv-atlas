[English](README.md) · [Deutsch](README.de.md)

# Swift: Delegated Tools With Foundation Models

Report Q009622 · Source medium.com · Date 2026-10-10 · [Open original](https://medium.com/@itsuki.enjoy/swift-delegated-tools-with-foundation-models-fb0e1398c5ea)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag beschreibt einen Swift-`Agent`-Wrapper, der delegierte Tool-Ausgaben zentral abfängt, im Gesprächsverlauf speichert und sowohl bei normalen als auch bei gestreamten Antworten zurückgibt. Das Beispiel zeigt eine nutzbare Folgefrage; laut Autor funktioniert die strukturierte Ausgabe bei direkt zurückgegebenen Tool-Ergebnissen jedoch nicht, und `preserveTranscript` ist nötig, um den Prompt zu erhalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 15 / 36 % | 52 / 77 % | 0 / 0 % | 59 / 75 % | 11 / 24 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 11 / 36 % | 0 / 0 % | 43 / 61 % | 7 / 18 % | 4 / 9 % |
