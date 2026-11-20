[English](README.md) · [Deutsch](README.de.md)

# Contextual retrieval in AI systems

Bericht Q002258 · Quelle anthropic.com · Datum 2024-09-19 · [Original öffnen](https://www.anthropic.com/research/contextual-retrieval)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic beschreibt Contextual Retrieval als RAG-Erweiterung, bei der jeder Textausschnitt vor der Suche um knappen, dokumentbezogenen Kontext ergänzt wird. In den von Anthropic berichteten Tests sank die Rate übersehener relevanter Treffer unter den ersten 20 durch kontextuelle Einbettungen, BM25 und zusätzliches Reranking schrittweise von 5,7 auf 1,9 Prozent. Die Ergebnisse hängen laut Bericht von Datenbestand und Einstellungen ab; Reranking kann zudem Laufzeit und Kosten erhöhen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 11 / 83 % | – | 74 / 84 % | 6 / 17 % | 0 / 0 % | 3 / 8 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 27 / 59 % | – | 69 / 78 % | 0 / 0 % | 0 / 0 % | 4 / 8 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 13 / 46 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 11 / 78 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
