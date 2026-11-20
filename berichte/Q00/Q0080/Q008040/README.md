[English](README.md) · [Deutsch](README.de.md)

# Scaling PostgreSQL to power 800 million ChatGPT users

Report Q008040 · Source openai.com · Date 2026-01-22 · [Open original](https://openai.com/index/scaling-postgresql/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, PostgreSQL mit einer einzelnen primären Azure-Instanz und fast 50 Lesereplikaten auf Millionen Abfragen pro Sekunde für überwiegend lesende Arbeitslasten skaliert zu haben. Dafür senke das Unternehmen Schreiblast und Abfragekosten und setze unter anderem Verbindungspooling, Cache-Sperren, Ratenbegrenzungen und Hochverfügbarkeit ein. Weitere Migrationen laufen; kaskadierende Replikation ist noch in der Testphase, und die Leistungsangaben stammen aus dem Beitrag selbst.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 80 / 96 % | – | 76 / 82 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 78 / 96 % | – | 53 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 75 / 95 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
