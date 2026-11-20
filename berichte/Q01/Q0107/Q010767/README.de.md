[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: ViewModel Pitfall: Not Recomposing on State Variable Change

Bericht Q010767 · Quelle medium.com · Datum 2024-02-23 · [Original öffnen](https://medium.com/@itsuki.enjoy/android-kotlin-jetpack-compose-viewmodel-pitfall-not-recomposing-on-state-variable-change-6679c3410405)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt ein Compose-Beispiel, bei dem ein innerhalb einer Composable erstelltes ViewModel laut Autor nicht zur erwarteten erneuten Zusammensetzung führt. Als bevorzugte Abhilfe empfiehlt der Text, die Initialisierung mit `LaunchedEffect` nach erfolgreicher Zusammensetzung auszuführen; das Lesen des Zustands über `derivedStateOf` wird als eingeschränkte Alternative beschrieben.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
