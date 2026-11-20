[English](README.md) · [Deutsch](README.de.md)

# Swift: Dive into On-Device STT With CoreAI (Whisper)

Report Q009706 · Source medium.com · Date 2026-07-20 · [Open original](https://medium.com/@itsuki.enjoy/swift-dive-into-on-device-stt-with-coreai-whisper-734d35f3388b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht erklärt, wie Whisper mit CoreAI in Swift aufgerufen wird: Audio wird in 30-Sekunden-Spektrogramme umgewandelt, und der Aufrufer steuert die Token-generierende Schleife selbst. Der Autor führt die langsame Ausführung seines gezeigten Exports auf fehlenden KV-Cache und wiederholte Berechnungen zurück; seine Laufzeitangaben sind Schätzungen, und ein vorgeschlagener Umbau wurde noch nicht erprobt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 99 / 100 % | 0 / 0 % | 95 / 97 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 37 / 87 % | 0 / 0 % | 89 / 93 % | 5 / 10 % | 4 / 9 % |
