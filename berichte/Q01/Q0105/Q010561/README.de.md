[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Migrate from ObservableObject to Observable macro

Bericht Q010561 · Quelle medium.com · Datum 2024-10-26 · [Original öffnen](https://medium.com/gitconnected/swiftui-migrate-from-observableobject-to-observable-macro-ee11b4a502fc)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt die Migration von `ObservableObject` zu `@Observable`: `@Published` entfällt, Views nutzen je nach Fall `State` und `Environment`, und für Bindings kommt `@Bindable` zum Einsatz. Außerdem beschreibt der Autor, wie ein registrierter Manager zwischen SwiftUI-App und `AppIntents` geteilt werden kann; die Vorteile werden anhand einfacher Beispiele erläutert, aber nicht durch Messungen belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
