[English](README.md) · [Deutsch](README.de.md)

# AWS Bedrock Converse API with Rust: Tool Use + Streaming

Bericht Q010619 · Quelle medium.com · Datum 2024-08-11 · [Original öffnen](https://medium.com/gitconnected/aws-bedrock-converse-api-with-rust-tool-use-streaming-e20b7f42a5bd)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel zeigt, wie Rust einen gestreamten Bedrock-Werkzeugaufruf anhand von Werkzeug-ID, Namen und stückweise eintreffender Eingabe verarbeitet, diese Eingabe in `Document` umwandelt und das Werkzeugergebnis für eine weitere Modellantwort zurücksendet. Das Beispiel führt das Werkzeug nicht tatsächlich aus, sondern verwendet ein fest codiertes Ergebnis und vereinfacht die Annahme, dass die Folgeantwort keinen weiteren Werkzeugaufruf enthält.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 47 / 79 % | 0 / 0 % | 28 / 50 % | 9 / 20 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 37 % | 7 / 15 % | 0 / 0 % |
