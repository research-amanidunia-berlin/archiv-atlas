[English](README.md) · [Deutsch](README.de.md)

# SwiftUI+MapKit: Set and Track Map Position

Bericht Q010612 · Quelle medium.com · Datum 2024-08-20 · [Original öffnen](https://medium.com/gitconnected/swiftui-mapkit-set-and-track-map-position-5b1c5bf8a741)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht zeigt, wie man in SwiftUI mit einer gebundenen `MapCameraPosition` zwischen festen Kartenorten wechselt. Zum Verfolgen der Bewegung empfiehlt der Autor `onMapCameraChange`, da `position.region` laut seinem Beispiel beim Verschieben `nil` sein kann; der Callback kann das Kartenzentrum laufend oder nach Ende der Bewegung liefern.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
