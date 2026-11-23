[English](README.md) · [Deutsch](README.de.md)

# Scaling Kubernetes to 7,500 nodes

Report Q008178 · Source openai.com · Date 2021-01-25 · [Open original](https://openai.com/index/scaling-kubernetes-to-7500-nodes/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt den Betrieb von Kubernetes-Clustern mit bis zu 7.500 Knoten für groß angelegte ML-Jobs und Forschungsarbeit. Der Bericht nennt Maßnahmen für Netzwerk, API-Server, Überwachung, Knotenprüfung und gemeinsame Jobplanung, weist aber auch auf offene Probleme bei Prometheus und der Begrenzung des Pod-Internetverkehrs hin; die Erfahrungen beziehen sich auf eine besondere, nicht allgemein repräsentative Arbeitslast.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 94 / 99 % | 54 / 64 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 90 / 99 % | 89 / 95 % | 11 / 31 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 85 / 96 % | 81 / 90 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 33 / 83 % | 6 / 23 % | 18 / 41 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 33 / 71 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 27 / 58 % | 10 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 11 / 20 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 7 / 14 % | – | – |
