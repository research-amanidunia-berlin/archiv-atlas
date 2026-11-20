[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Divider Width based of Other Contents

Bericht Q010769 · Quelle medium.com · Datum 2024-02-19 · [Original öffnen](https://medium.com/@itsuki.enjoy/android-kotlin-jetpack-compose-divider-width-based-of-other-contents-80a4e5d5ee50)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, wie man in Jetpack Compose die Breite eines `Divider` an die gemessene Breite der Tab-`Box` koppelt: `onGloballyPositioned` erfasst sie, `LocalDensity` wandelt sie in `Dp` um und `Modifier.width` setzt sie für die Linie. Der Autor zufolge verhindert das, dass die Trennlinie die umgebende Spalte auf die verfügbare Maximalbreite ausdehnt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
