[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Recognize & Search Handwritings

Bericht Q009684 · Quelle medium.com · Datum 2026-08-14 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-recognize-search-handwritings-e47bdff0c760)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erläutert Handschrifterkennung, Textsuche und Spotlight-Indexierung für PencilKit-Zeichnungen in SwiftUI. Wichtig ist, den `PKStrokeRecognizer` vor jeder Anfrage mit der aktuellen Zeichnung zu aktualisieren; die Erkennung kann scheitern und ihre Genauigkeit hängt unter anderem von der Schreibgröße ab. Ein Verhalten beim Zurücksetzen der Auswahl führt der Autor auf einen möglichen, aber nicht bestätigten Framework-Fehler zurück.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
