[English](README.md) · [Deutsch](README.de.md)

# Swift/iOS: Release File Lock If App Not Running Actively!

Bericht Q009819 · Quelle medium.com · Datum 2026-04-15 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-ios-release-file-lock-if-app-not-running-actively-6ea1d9d5bdeb)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor führt die beschriebenen Abstürze von TestFlight-Builds auf eine beim App-Start erworbene Dateisperre zurück: Ohne `acquireLock()` trat der Fehler in seinen Versuchen nicht mehr auf. Als Ersatz schlägt er einen regelmäßig aktualisierten Heartbeat vor; seine Beobachtungen beschränken sich auf den geschilderten Fall und unterscheiden sich von den problemlos laufenden lokalen Builds.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 92 / 94 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 53 / 78 % | 83 / 89 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
