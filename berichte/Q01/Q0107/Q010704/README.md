[English](README.md) · [Deutsch](README.de.md)

# Swift: Streaming OpenAI API Response (Chunked Encoding Transfer)

Report Q010704 · Source medium.com · Date 2024-05-11 · [Open original](https://medium.com/stackademic/swift-streaming-openai-api-response-chunked-encoding-transfer-48b7f1785f5f)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Artikel demonstriert eine SwiftUI-Anwendung, die OpenAI-Antworten über `URLSession.shared.bytes` schrittweise empfängt, SSE-Zeilen dekodiert und den Text fortlaufend anzeigt. Der Autor weist auf mögliche geteilte JSON-Daten und API-Fehler hin; die Lösung bleibt eine einfache Demo ohne belegte systematische Prüfung, und der mögliche Teilungsfall wurde laut Autor selbst nicht beobachtet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
