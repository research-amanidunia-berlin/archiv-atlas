[English](README.md) · [Deutsch](README.de.md)

# Swift: Continuation, Convert Completion Handlers/Callback into async & async throws, Prevent…

Bericht Q010692 · Quelle medium.com · Datum 2024-05-25 · [Original öffnen](https://medium.com/towardsdev/swift-continuation-and-convert-completion-handlers-callback-into-async-async-throws-3895c76980c1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel erklärt anhand einfacher Swift-Beispiele, wie `withCheckedContinuation` und `withCheckedThrowingContinuation` Completion-Handler in `async`- beziehungsweise `async throws`-Funktionen überführen. Gegen mehrfaches Fortsetzen empfiehlt der Autor, eine optionale Continuation nach dem ersten Aufruf auf `nil` zu setzen; weitergehende Fragen zur Synchronisierung werden nicht behandelt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
