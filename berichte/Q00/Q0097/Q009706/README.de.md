[English](README.md) · [Deutsch](README.de.md)

# Swift: Dive into On-Device STT With CoreAI (Whisper)

Bericht Q009706 · Quelle medium.com · Datum 2026-07-20 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-dive-into-on-device-stt-with-coreai-whisper-734d35f3388b)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht erklärt, wie Whisper mit CoreAI in Swift aufgerufen wird: Audio wird in 30-Sekunden-Spektrogramme umgewandelt, und der Aufrufer steuert die Token-generierende Schleife selbst. Der Autor führt die langsame Ausführung seines gezeigten Exports auf fehlenden KV-Cache und wiederholte Berechnungen zurück; seine Laufzeitangaben sind Schätzungen, und ein vorgeschlagener Umbau wurde noch nicht erprobt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 99 / 100 % | 0 / 0 % | 95 / 97 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 37 / 87 % | 0 / 0 % | 89 / 93 % | 5 / 10 % | 4 / 9 % | 0 / 0 % |
