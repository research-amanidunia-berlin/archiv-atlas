[English](README.md) · [Deutsch](README.de.md)

# Scaling PostgreSQL to power 800 million ChatGPT users

Bericht Q008040 · Quelle openai.com · Datum 2026-01-22 · [Original öffnen](https://openai.com/index/scaling-postgresql/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet, PostgreSQL mit einer einzelnen primären Azure-Instanz und fast 50 Lesereplikaten auf Millionen Abfragen pro Sekunde für überwiegend lesende Arbeitslasten skaliert zu haben. Dafür senke das Unternehmen Schreiblast und Abfragekosten und setze unter anderem Verbindungspooling, Cache-Sperren, Ratenbegrenzungen und Hochverfügbarkeit ein. Weitere Migrationen laufen; kaskadierende Replikation ist noch in der Testphase, und die Leistungsangaben stammen aus dem Beitrag selbst.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 80 / 96 % | 76 / 82 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 78 / 96 % | 53 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 75 / 95 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
