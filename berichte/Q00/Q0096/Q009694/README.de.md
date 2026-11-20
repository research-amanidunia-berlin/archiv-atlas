[English](README.md) · [Deutsch](README.de.md)

# I Got a Chance to Build A RAG for Legal Docs

Bericht Q009694 · Quelle medium.com · Datum 2026-08-02 · [Original öffnen](https://medium.com/@itsuki.enjoy/i-got-a-change-to-build-a-rag-for-legal-docs-46f98a0ea9f4)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt seine noch vorläufige Umsetzung eines RAG für Rechtsdokumente: Dokumente sollen strukturiert normalisiert, rechtlich wichtige Versionsinhalte bewahrt und Artikel als eigenständige, kontextreiche Chunks gespeichert werden. Für den Abruf empfiehlt er Anfrageplanung mit Versionsfiltern, Vektorsuche und Reranking; eine systematische Wirksamkeitsmessung berichtet der Artikel nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 91 / 97 % | 0 / 0 % | 79 / 85 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 38 / 90 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 3 / 7 % | 0 / 0 % |
