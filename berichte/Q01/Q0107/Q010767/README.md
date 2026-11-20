[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: ViewModel Pitfall: Not Recomposing on State Variable Change

Report Q010767 · Source medium.com · Date 2024-02-23 · [Open original](https://medium.com/@itsuki.enjoy/android-kotlin-jetpack-compose-viewmodel-pitfall-not-recomposing-on-state-variable-change-6679c3410405)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht zeigt ein Compose-Beispiel, bei dem ein innerhalb einer Composable erstelltes ViewModel laut Autor nicht zur erwarteten erneuten Zusammensetzung führt. Als bevorzugte Abhilfe empfiehlt der Text, die Initialisierung mit `LaunchedEffect` nach erfolgreicher Zusammensetzung auszuführen; das Lesen des Zustands über `derivedStateOf` wird als eingeschränkte Alternative beschrieben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
