[English](README.md) · [Deutsch](README.de.md)

# My Legal Doc RAG: The Actual Design + Implementation.

Report Q009666 · Source medium.com · Date 2026-08-23 · [Open original](https://medium.com/@itsuki.enjoy/my-legal-doc-rag-the-actual-design-implementation-9cf699d2055a)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor stellt einen konkreten RAG-Entwurf für Rechtsdokumente vor: quellenspezifische Normalisierung mit Text- und Originaldatei-Fallbacks, kontextbewusstes Chunking und einen Abruf mit Datumsplanung, zusätzlichem Versionsfilter und nachgelagertem Reranking. Da nur ausdrücklich festgelegte Ablaufdaten erfasst werden, kann die Vektorsuche Versionen nicht vollständig aussortieren; der Beitrag beschreibt einen Ansatz samt Beispielen, aber keine systematische Leistungsprüfung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 82 / 93 % | 0 / 0 % | 84 / 89 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 13 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
