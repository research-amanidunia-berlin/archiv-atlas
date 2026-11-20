[English](README.md) · [Deutsch](README.de.md)

# Contextual retrieval in AI systems

Report Q002258 · Source anthropic.com · Date 2024-09-19 · [Open original](https://www.anthropic.com/research/contextual-retrieval)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic beschreibt Contextual Retrieval als RAG-Erweiterung, bei der jeder Textausschnitt vor der Suche um knappen, dokumentbezogenen Kontext ergänzt wird. In den von Anthropic berichteten Tests sank die Rate übersehener relevanter Treffer unter den ersten 20 durch kontextuelle Einbettungen, BM25 und zusätzliches Reranking schrittweise von 5,7 auf 1,9 Prozent. Die Ergebnisse hängen laut Bericht von Datenbestand und Einstellungen ab; Reranking kann zudem Laufzeit und Kosten erhöhen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 11 / 83 % | – | 74 / 84 % | 6 / 17 % | 3 / 8 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 27 / 59 % | – | 69 / 78 % | 0 / 0 % | 4 / 8 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 13 / 46 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 11 / 78 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
