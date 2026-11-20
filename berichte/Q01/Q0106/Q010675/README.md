[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin: Get File Extension and android.webkit.MimeTypeMap Pitfall

Report Q010675 · Source medium.com · Date 2024-06-14 · [Open original](https://medium.com/towardsdev/android-kotlin-get-file-extension-and-android-webkit-mimetypemap-pitfall-dd419f5a89cf)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor berichtet, dass `MimeTypeMap.getFileExtensionFromUrl` bei Dateinamen mit japanischen Zeichen eine leere Endung liefern könne, weil der gezeigte Android-Code nur eine begrenzte Menge ASCII-Zeichen akzeptiert. Für die Dateiendung empfiehlt er in Kotlin `File.extension`; der Bericht belegt dies anhand eines Beispiels und des zitierten Quellcodes.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
