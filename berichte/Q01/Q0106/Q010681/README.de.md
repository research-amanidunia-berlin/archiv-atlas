[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Save File/Documents to Files App and Solve item can’t be saved…

Bericht Q010681 · Quelle medium.com · Datum 2024-06-07 · [Original öffnen](https://medium.com/stackademic/android-kotlin-jetpack-compose-save-file-documents-to-files-app-and-solve-item-cant-be-saved-3ed63c422b85)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erklärt, wie Compose mit `ACTION_CREATE_DOCUMENT` ein Dokument anlegt und anschließend über einen Ausgabestrom in dessen `Uri` schreibt. Der Autor schildert außerdem Dateinamen-Probleme und führt den Fehler „item can’t be saved“ auf nicht speicherbaren `rememberSaveable`-Zustand zurück; als Abhilfe nennt er einen eigenen Saver, eine gespeicherte ID oder ein `ViewModel`, wobei die Beobachtungen aus seinem persönlichen Fall stammen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
