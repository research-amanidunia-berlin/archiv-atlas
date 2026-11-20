[English](README.md) · [Deutsch](README.de.md)

# Bedrock AgentCore Part2: Memory. A Combination of Raw Database, Vector store, And EventBridges!

Bericht Q010232 · Quelle medium.com · Datum 2025-07-31 · [Original öffnen](https://medium.com/gitconnected/bedrock-agentcore-part2-memory-raw-database-vector-store-some-eventbridge-ish-logics-594aad0389c0)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor zeigt, wie AgentCore Memory Gesprächsereignisse speichert und daraus asynchron Zusammenfassungen oder andere Langzeitinformationen erzeugt, und demonstriert die Einbindung in einen Agenten. Er berichtet für die damalige Vorschauversion von Berechtigungs- und SDK-Lücken, sieht begrenzte Kontrolle über die Verarbeitung und schlägt personalisierte Suchvorschläge als mögliche, im Beitrag nicht erprobte Anwendung vor.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 76 / 98 % | 0 / 0 % | 39 / 60 % | 10 / 24 % | 4 / 11 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 15 / 64 % | 0 / 0 % | 29 / 53 % | 8 / 23 % | 5 / 16 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 15 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 43 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 5 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 1 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
