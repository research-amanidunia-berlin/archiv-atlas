[English](README.md) · [Deutsch](README.de.md)

# Swift: Delegated Tools With Foundation Models

Bericht Q009622 · Quelle medium.com · Datum 2026-10-10 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-delegated-tools-with-foundation-models-fb0e1398c5ea)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag beschreibt einen Swift-`Agent`-Wrapper, der delegierte Tool-Ausgaben zentral abfängt, im Gesprächsverlauf speichert und sowohl bei normalen als auch bei gestreamten Antworten zurückgibt. Das Beispiel zeigt eine nutzbare Folgefrage; laut Autor funktioniert die strukturierte Ausgabe bei direkt zurückgegebenen Tool-Ergebnissen jedoch nicht, und `preserveTranscript` ist nötig, um den Prompt zu erhalten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 15 / 36 % | 52 / 77 % | 59 / 75 % | 11 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 11 / 36 % | 43 / 61 % | 7 / 18 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
