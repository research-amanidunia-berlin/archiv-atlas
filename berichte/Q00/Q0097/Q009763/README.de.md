[English](README.md) · [Deutsch](README.de.md)

# Swift: Timeout Await Functions that JUST DON’T Cancel

Bericht Q009763 · Quelle medium.com · Datum 2026-06-01 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-timeout-await-functions-that-just-dont-cancel-61b69a4a83f4)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Itsuki zeigt, dass sein Swift-Timeout bei einer gewöhnlichen Schlafoperation früh abbricht, eine über `withCheckedContinuation` eingebundene Completion-Handler-Funktion in den Beispielen aber weiterläuft. Ein Ansatz mit getrenntem Timer-Task lässt den Aufrufer früh zurückkehren, beendet die eigentliche Arbeit jedoch nicht; der Bericht beansprucht keine allgemeingültige Abbruchlösung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
