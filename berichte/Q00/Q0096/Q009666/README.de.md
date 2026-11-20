[English](README.md) · [Deutsch](README.de.md)

# My Legal Doc RAG: The Actual Design + Implementation.

Bericht Q009666 · Quelle medium.com · Datum 2026-08-23 · [Original öffnen](https://medium.com/@itsuki.enjoy/my-legal-doc-rag-the-actual-design-implementation-9cf699d2055a)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor stellt einen konkreten RAG-Entwurf für Rechtsdokumente vor: quellenspezifische Normalisierung mit Text- und Originaldatei-Fallbacks, kontextbewusstes Chunking und einen Abruf mit Datumsplanung, zusätzlichem Versionsfilter und nachgelagertem Reranking. Da nur ausdrücklich festgelegte Ablaufdaten erfasst werden, kann die Vektorsuche Versionen nicht vollständig aussortieren; der Beitrag beschreibt einen Ansatz samt Beispielen, aber keine systematische Leistungsprüfung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 82 / 93 % | 0 / 0 % | 84 / 89 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 13 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
