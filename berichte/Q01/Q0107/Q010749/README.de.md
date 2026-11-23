[English](README.md) · [Deutsch](README.de.md)

# AWS: Integrate Bedrock Knowledge Base (AWS SDK & LangChain)

Bericht Q010749 · Quelle medium.com · Datum 2024-03-23 · [Original öffnen](https://medium.com/aws-tip/aws-integrate-bedrock-knowledge-base-aws-sdk-langchain-7b79d4944f7f)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, wie eine bestehende Bedrock Knowledge Base direkt mit boto3 oder über LangChain abgefragt wird. Laut Artikel bietet der direkte Aufruf Antwortabschnitte mit Quellenzuordnungen, während LangChains RetrievalQA zwar Quelldokumente, aber keine Zuordnung zu einzelnen Antwortteilen liefert; für Gesprächsverläufe beschreibt der Autor zusätzliche Speicher- und Konfigurationseinstellungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 70 / 91 % | 0 / 0 % | 11 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 22 / 55 % | 4 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 2 / 35 % | 19 / 35 % | 6 / 15 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 1 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
