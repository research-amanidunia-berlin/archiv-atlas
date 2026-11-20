[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Migrate from ObservableObject to Observable macro

Report Q010561 · Source medium.com · Date 2024-10-26 · [Open original](https://medium.com/gitconnected/swiftui-migrate-from-observableobject-to-observable-macro-ee11b4a502fc)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht zeigt die Migration von `ObservableObject` zu `@Observable`: `@Published` entfällt, Views nutzen je nach Fall `State` und `Environment`, und für Bindings kommt `@Bindable` zum Einsatz. Außerdem beschreibt der Autor, wie ein registrierter Manager zwischen SwiftUI-App und `AppIntents` geteilt werden kann; die Vorteile werden anhand einfacher Beispiele erläutert, aber nicht durch Messungen belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
