[English](README.md) · [Deutsch](README.de.md)

# Swift: Streaming OpenAI API Response (Chunked Encoding Transfer)

Bericht Q010704 · Quelle medium.com · Datum 2024-05-11 · [Original öffnen](https://medium.com/stackademic/swift-streaming-openai-api-response-chunked-encoding-transfer-48b7f1785f5f)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel demonstriert eine SwiftUI-Anwendung, die OpenAI-Antworten über `URLSession.shared.bytes` schrittweise empfängt, SSE-Zeilen dekodiert und den Text fortlaufend anzeigt. Der Autor weist auf mögliche geteilte JSON-Daten und API-Fehler hin; die Lösung bleibt eine einfache Demo ohne belegte systematische Prüfung, und der mögliche Teilungsfall wurde laut Autor selbst nicht beobachtet.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
