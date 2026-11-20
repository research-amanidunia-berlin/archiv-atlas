[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Avoid Auto-Resizing on Re-compose

Bericht Q010773 · Quelle medium.com · Datum 2024-02-17 · [Original öffnen](https://medium.com/@itsuki.enjoy/android-kotlin-jetpack-compose-avoid-auto-resizing-on-re-compose-b718bef62a24)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor schlägt vor, beim ersten Layout die Höhe einer Compose-Box mit `onGloballyPositioned` zu messen und zu speichern, um sie bei späteren Zusammensetzungen festzusetzen. In der gezeigten Vorschau soll das verhindern, dass ein Popup mit einklappbaren Tabellenzeilen seine Größe und Position verändert; demonstriert wird der Ansatz nur für die Höhe und das Beispiel.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
