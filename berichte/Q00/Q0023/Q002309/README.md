[English](README.md) · [Deutsch](README.de.md)

# Introducing advanced tool use for Claude

Report Q002309 · Source anthropic.com · Date 2025-11-24 · [Open original](https://www.anthropic.com/research/advanced-tool-use)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic stellt drei Beta-Funktionen vor: bedarfsgesteuerte Werkzeugsuche, codebasierte Orchestrierung mehrerer Werkzeuge und Beispiele für korrekte Aufrufparameter. Interne Tests hätten geringeren Kontextverbrauch und bessere Genauigkeit gezeigt; die Funktionen bringen jeweils zusätzlichen Aufwand mit sich und lohnen sich je nach Größe und Komplexität der Aufgabe unterschiedlich stark.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 22 / 39 % | 53 / 85 % | – | 95 / 97 % | 15 / 36 % | 0 / 0 % | 10 / 22 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 23 / 50 % | 65 / 96 % | – | 79 / 93 % | 29 / 54 % | 4 / 17 % | 18 / 40 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 27 % | 27 / 70 % | – | 0 / 0 % | 6 / 17 % | 0 / 0 % | 4 / 7 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 25 / 70 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 19 / 35 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 0 / 0 % | 9 / 18 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 17 / 32 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 5 / 38 % | – | 15 / 31 % | 8 / 26 % | 1 / 6 % | 5 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 29 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 26 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 1 / 7 % | 7 / 17 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 5 / 63 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
