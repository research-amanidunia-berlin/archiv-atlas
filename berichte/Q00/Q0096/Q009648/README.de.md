[English](README.md) · [Deutsch](README.de.md)

# Little SwiftUI Pitfall I Fall In: State Initial Value

Bericht Q009648 · Quelle medium.com · Datum 2026-09-13 · [Original öffnen](https://medium.com/@itsuki.enjoy/little-swiftui-pitfall-i-fall-in-state-initial-value-46f5f959cb74)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht schildert, dass direkte Zuweisungen an `@State` im SwiftUI-Initializer laut Autor zu unerwarteten Anfangswerten führen können. Besonders bei optionalem Zustand empfiehlt er, den Wert ausdrücklich mit `State(initialValue:)` zu setzen; so erklärt er auch ein ausbleibendes Scrollen zu `topItem = 20`.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
