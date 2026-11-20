[English](README.md) · [Deutsch](README.de.md)

# Using SwiftData to Store Large Files from an API call

Bericht Q011674 · Quelle medium.com · Datum 2024-01-08 · [Original öffnen](https://medium.com/@jpmtech/using-swiftdata-to-store-large-files-from-an-api-call-11ad83404f76)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erklärt anhand eines Swift-Beispiels, wie Fotos als Binärdaten mit `.externalStorage` in SwiftData abgelegt und anschließend offline aus der Datenbank angezeigt werden können. Der gezeigte Ablauf lädt API-Metadaten und Dateien, lässt bei fehlgeschlagenem Dateiabruf das Datenfeld leer und zeigt Bilder nur an, wenn sich die gespeicherten Bytes in ein `UIImage` umwandeln lassen. Leistungswerte, Tests und Grenzen bei Dateigrößen behandelt der Bericht nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
