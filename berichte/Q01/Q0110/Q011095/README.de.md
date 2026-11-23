[English](README.md) · [Deutsch](README.de.md)

# How I Built a RAG (Retrieval-Augmented Generation) System Using n8n — No Code, No Stress (Part 2/2)

Bericht Q011095 · Quelle medium.com · Datum 2025-04-21 · [Original öffnen](https://medium.com/gitconnected/how-i-built-a-rag-retrieval-augmented-generation-system-using-n8n-no-code-no-stress-part-2-2-488a82c013fe)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug beschreibt einen geplanten n8n-Workflow für einen RAG-Chatbot: Ein KI-Agent soll relevante Textabschnitte aus Pinecone abrufen und mit OpenAI eine darauf gestützte Antwort erzeugen. Der Text endet an einer Medium-Mitgliederseite; konkrete Umsetzungsschritte und Ergebnisse liegen nicht vor.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 43 / 74 % | 28 / 47 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 31 / 56 % | 36 / 55 % | 9 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 9 / 39 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 3 / 8 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 4 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
