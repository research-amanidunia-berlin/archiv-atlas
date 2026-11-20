[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin/Jetpack Compose: Save File/Documents to Files App and Solve item can’t be saved…

Report Q010681 · Source medium.com · Date 2024-06-07 · [Open original](https://medium.com/stackademic/android-kotlin-jetpack-compose-save-file-documents-to-files-app-and-solve-item-cant-be-saved-3ed63c422b85)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht erklärt, wie Compose mit `ACTION_CREATE_DOCUMENT` ein Dokument anlegt und anschließend über einen Ausgabestrom in dessen `Uri` schreibt. Der Autor schildert außerdem Dateinamen-Probleme und führt den Fehler „item can’t be saved“ auf nicht speicherbaren `rememberSaveable`-Zustand zurück; als Abhilfe nennt er einen eigenen Saver, eine gespeicherte ID oder ein `ViewModel`, wobei die Beobachtungen aus seinem persönlichen Fall stammen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
