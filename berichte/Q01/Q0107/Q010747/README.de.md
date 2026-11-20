[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Intercepting and Disabling Back Press & Back Gesture

Bericht Q010747 · Quelle medium.com · Datum 2024-03-24 · [Original öffnen](https://medium.com/stackademic/android-kotlin-jetpack-compose-intercepting-and-disabling-back-press-back-gesture-6ec90487fc34)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt zwei Wege, Zurück in Jetpack Compose zu steuern: `popUpTo` entfernt den vorherigen Bildschirm aus dem Backstack, während `BackHandler` den Vorgang abfängt, etwa um eine Bestätigung anzuzeigen. Im Beispiel schließt Zurück nach `popUpTo` die App; mit Dialog kann man abbrechen oder zu „Main“ zurückkehren. Die Darstellung bleibt bei einem einfachen Beispiel.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
