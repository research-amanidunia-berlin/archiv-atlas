[English](README.md) · [Deutsch](README.de.md)

# I Got a Chance to Build A RAG for Legal Docs

Report Q009694 · Source medium.com · Date 2026-08-02 · [Open original](https://medium.com/@itsuki.enjoy/i-got-a-change-to-build-a-rag-for-legal-docs-46f98a0ea9f4)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor beschreibt seine noch vorläufige Umsetzung eines RAG für Rechtsdokumente: Dokumente sollen strukturiert normalisiert, rechtlich wichtige Versionsinhalte bewahrt und Artikel als eigenständige, kontextreiche Chunks gespeichert werden. Für den Abruf empfiehlt er Anfrageplanung mit Versionsfiltern, Vektorsuche und Reranking; eine systematische Wirksamkeitsmessung berichtet der Artikel nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 91 / 97 % | 0 / 0 % | 79 / 85 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 38 / 90 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 3 / 7 % | 0 / 0 % |
