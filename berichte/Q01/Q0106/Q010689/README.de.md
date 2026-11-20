[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Screen Size 2 ways and fillMaxSize pitfall!

Bericht Q010689 · Quelle medium.com · Datum 2024-05-29 · [Original öffnen](https://medium.com/stackademic/android-kotlin-jetpack-compose-screen-size-2-ways-and-fillmaxsize-pitfall-42a7fd902d0e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht vergleicht `WindowManager`, das Maße in Pixeln einschließlich Systemleisten-Insets liefert, mit `LocalConfiguration`, das dp-Werte ohne diese Insets bereitstellt. Für ein `ModalBottomSheet`, das bei `dragHandle = null` über die Statusleiste reichen kann, empfiehlt der Autor `safeDrawingPadding()`; das beobachtete Bedienproblem trat in seinen Tests nur auf Pixel 7 Pro und Pixel 6a auf.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
