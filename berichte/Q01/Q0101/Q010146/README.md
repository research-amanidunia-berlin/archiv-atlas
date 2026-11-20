[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: LongPressGesture OnChange Not triggered! Updating Not triggered!

Report Q010146 · Source medium.com · Date 2025-09-17 · [Open original](https://medium.com/gitconnected/swiftui-longpressgesture-onchange-not-triggered-updating-not-triggered-30e241a7820d)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Beitrag zeigt, dass `onChanged` und `updating` laut Autor bei `LongPressGesture(minimumDuration: 0)` keinen brauchbaren gedrückten Zustand liefern; bei `updating` klappt das Beispiel mit einer Sekunde Mindestdauer. Als funktionierende Lösung für Dauer null nennt er `onLongPressGesture` mit `onPressingChanged`, kann den Unterschied der Callbacks aber nicht erklären.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
