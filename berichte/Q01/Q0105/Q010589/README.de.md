[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Sync/Observe UserDefaults Change 2 ways

Bericht Q010589 · Quelle medium.com · Datum 2024-09-20 · [Original öffnen](https://medium.com/gitconnected/swiftui-sync-observe-userdefaults-change-2-ways-f935fa27871d)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel erklärt anhand eines Zählers zwei Wege, Änderungen aus `UserDefaults` in mehreren SwiftUI-Ansichten sichtbar zu machen: `@AppStorage` und einen Combine-Publisher mit einem `ObservableObject`-Manager. Der Autor zeigt beide Ansätze als funktionierend; als Einschränkung von `@AppStorage` nennt er komplexe Objekte und die Datenverwaltung direkt in Views.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
