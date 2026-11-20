[English](README.md) · [Deutsch](README.de.md)

# Difference Between try, try? and try! and When to Use Them in Swift

Bericht Q011657 · Quelle medium.com · Datum 2024-05-20 · [Original öffnen](https://medium.com/@jpmtech/difference-between-try-try-and-try-and-when-to-use-them-in-swift-d0e7102865b8)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Artikel erklärt `try` zum Abfangen oder Weiterreichen von Fehlern, `try?` zum Umwandeln eines Fehlschlags in `nil` und `try!` als Variante, die bei einem Fehler zum Absturz führt. Der Autor empfiehlt `try` für gezielte Fehlerbehandlung, `try?` bei unwichtiger Fehlerursache und `try!` nur bei garantiert ausbleibendem Fehler oder zum Debuggen; für Produktionscode rät er generell zu sicherer Behandlung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
