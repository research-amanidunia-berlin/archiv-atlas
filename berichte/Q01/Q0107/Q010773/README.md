[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Avoid Auto-Resizing on Re-compose

Report Q010773 · Source medium.com · Date 2024-02-17 · [Open original](https://medium.com/@itsuki.enjoy/android-kotlin-jetpack-compose-avoid-auto-resizing-on-re-compose-b718bef62a24)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor schlägt vor, beim ersten Layout die Höhe einer Compose-Box mit `onGloballyPositioned` zu messen und zu speichern, um sie bei späteren Zusammensetzungen festzusetzen. In der gezeigten Vorschau soll das verhindern, dass ein Popup mit einklappbaren Tabellenzeilen seine Größe und Position verändert; demonstriert wird der Ansatz nur für die Höhe und das Beispiel.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
