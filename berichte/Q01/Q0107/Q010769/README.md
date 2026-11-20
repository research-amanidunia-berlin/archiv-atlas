[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Divider Width based of Other Contents

Report Q010769 · Source medium.com · Date 2024-02-19 · [Open original](https://medium.com/@itsuki.enjoy/android-kotlin-jetpack-compose-divider-width-based-of-other-contents-80a4e5d5ee50)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht zeigt, wie man in Jetpack Compose die Breite eines `Divider` an die gemessene Breite der Tab-`Box` koppelt: `onGloballyPositioned` erfasst sie, `LocalDensity` wandelt sie in `Dp` um und `Modifier.width` setzt sie für die Linie. Der Autor zufolge verhindert das, dass die Trennlinie die umgebende Spalte auf die verfügbare Maximalbreite ausdehnt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
