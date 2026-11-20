[English](README.md) · [Deutsch](README.de.md)

# Swift Foundation Models: A little Better Tools with Context!

Report Q010130 · Source medium.com · Date 2025-09-27 · [Open original](https://medium.com/@itsuki.enjoy/swift-foundation-models-a-little-better-tools-with-context-ff24f456f115)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor erklärt, wie Tools in Apples Foundation Models über `ToolCallContext` das Sitzungstranskript auswerten können, und demonstriert damit eine Begrenzung auf einen Aufruf pro Sitzung. Das Beispiel scheitert bei zwei Tool-Aufrufen und funktioniert bei einem; laut Bericht müssen zusätzlich eine gewöhnliche Aufrufmethode implementiert und Einschränkungen der Beta-Schnittstelle berücksichtigt werden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 31 / 53 % | 77 / 97 % | 0 / 0 % | 97 / 99 % | 36 / 60 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 19 / 36 % | 12 / 46 % | 0 / 0 % | 74 / 86 % | 15 / 35 % | 6 / 17 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 71 / 89 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 25 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 5 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 4 / 7 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 5 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
