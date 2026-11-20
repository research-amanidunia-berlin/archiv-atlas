[English](README.md) · [Deutsch](README.de.md)

# Scaling Kubernetes to 2,500 nodes

Report Q008243 · Source openai.com · Date 2018-01-18 · [Open original](https://openai.com/index/scaling-kubernetes-to-2500-nodes/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, Kubernetes 2018 auf mehr als 2.500 Azure-Knoten skaliert und dabei Engpässe bei etcd, API-Abfragen, DNS, Docker-Abrufen, Netzwerk und ARP-Caches durch gezielte Konfigurationsänderungen behoben zu haben. Das Unternehmen meldete anschließend rund drei Monate ohne Zwischenfälle; die Wirksamkeit der Maßnahmen wird im Text als eigene Erfahrung beschrieben, nicht unabhängig belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 69 / 93 % | – | 88 / 94 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 88 / 99 % | – | 81 / 90 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 62 / 92 % | – | 44 / 59 % | 0 / 0 % | 0 / 0 % |
