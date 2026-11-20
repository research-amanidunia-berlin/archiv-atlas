[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Screen Size 2 ways and fillMaxSize pitfall!

Report Q010689 · Source medium.com · Date 2024-05-29 · [Open original](https://medium.com/stackademic/android-kotlin-jetpack-compose-screen-size-2-ways-and-fillmaxsize-pitfall-42a7fd902d0e)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht vergleicht `WindowManager`, das Maße in Pixeln einschließlich Systemleisten-Insets liefert, mit `LocalConfiguration`, das dp-Werte ohne diese Insets bereitstellt. Für ein `ModalBottomSheet`, das bei `dragHandle = null` über die Statusleiste reichen kann, empfiehlt der Autor `safeDrawingPadding()`; das beobachtete Bedienproblem trat in seinen Tests nur auf Pixel 7 Pro und Pixel 6a auf.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
