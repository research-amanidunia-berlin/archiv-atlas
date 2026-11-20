[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Intercepting and Disabling Back Press & Back Gesture

Report Q010747 · Source medium.com · Date 2024-03-24 · [Open original](https://medium.com/stackademic/android-kotlin-jetpack-compose-intercepting-and-disabling-back-press-back-gesture-6ec90487fc34)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht zeigt zwei Wege, Zurück in Jetpack Compose zu steuern: `popUpTo` entfernt den vorherigen Bildschirm aus dem Backstack, während `BackHandler` den Vorgang abfängt, etwa um eine Bestätigung anzuzeigen. Im Beispiel schließt Zurück nach `popUpTo` die App; mit Dialog kann man abbrechen oder zu „Main“ zurückkehren. Die Darstellung bleibt bei einem einfachen Beispiel.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
