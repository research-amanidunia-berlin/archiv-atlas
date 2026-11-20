[English](README.md) · [Deutsch](README.de.md)

# AWS Bedrock Converse API with Rust: Basic

Bericht Q010621 · Quelle medium.com · Datum 2024-08-11 · [Original öffnen](https://medium.com/gitconnected/aws-bedrock-converse-api-with-rust-basic-8f492cfbd586)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag zeigt Rust-Beispiele zur Nutzung der AWS Bedrock Converse API für Text, Bilder, PDF-Dokumente und Streaming, einschließlich Systemprompt und Inferenzparametern. Die Verarbeitung von Werkzeugaufrufen bleibt ausgeklammert; außerdem erklärt der Artikel nicht die Abweichung, dass eine JPG-Datei im Beispiel als PNG markiert wird.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | 0 / 0 % | 5 / 12 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 8 % | 0 / 0 % | 5 / 10 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 9 % | 0 / 0 % | 5 / 11 % |
