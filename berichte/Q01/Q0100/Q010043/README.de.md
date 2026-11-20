[English](README.md) · [Deutsch](README.de.md)

# Bedrock AgentCore Runtime: Stream Response for AI SDK Frontend

Bericht Q010043 · Quelle medium.com · Datum 2025-11-09 · [Original öffnen](https://medium.com/stackademic/bedrock-agentcore-runtime-stream-response-for-ai-sdk-frontend-7d9d545d6441)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel zeigt anhand von Strands, FastAPI und `useChat`, wie AgentCore-Antworten als SSE im AI-SDK-Datenstream-Protokoll übertragen und Werkzeugereignisse dabei abgebildet werden. Er nennt Regeln für Nachrichten- und Textkennungen, doch der Beispielcode sendet den Nachrichtenstart doppelt; die Darstellung konzentriert sich auf Text und Werkzeuge.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 7 / 50 % | 0 / 0 % | 28 / 44 % | 6 / 16 % | 0 / 0 % | 4 / 11 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 27 / 87 % | 0 / 0 % | 13 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
