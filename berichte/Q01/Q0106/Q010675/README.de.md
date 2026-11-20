[English](README.md) · [Deutsch](README.de.md)

# Android/Kotlin: Get File Extension and android.webkit.MimeTypeMap Pitfall

Bericht Q010675 · Quelle medium.com · Datum 2024-06-14 · [Original öffnen](https://medium.com/towardsdev/android-kotlin-get-file-extension-and-android-webkit-mimetypemap-pitfall-dd419f5a89cf)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor berichtet, dass `MimeTypeMap.getFileExtensionFromUrl` bei Dateinamen mit japanischen Zeichen eine leere Endung liefern könne, weil der gezeigte Android-Code nur eine begrenzte Menge ASCII-Zeichen akzeptiert. Für die Dateiendung empfiehlt er in Kotlin `File.extension`; der Bericht belegt dies anhand eines Beispiels und des zitierten Quellcodes.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
