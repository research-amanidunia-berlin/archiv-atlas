[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Pass Through Gestures on Transparent Image Pixel (Without UIImageView)

Bericht Q010345 · Quelle medium.com · Datum 2025-05-20 · [Original öffnen](https://medium.com/gitconnected/swiftui-pass-through-gestures-on-transparent-image-pixel-without-uiimageview-17ec435ca662)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel schlägt vor, die Trefferfläche eines SwiftUI-Bildes mit einer aus Alpha-Werten abgeleiteten eigenen Shape festzulegen, damit Gesten auf transparenten Bereichen den Hintergrund erreichen. Die Form wird rasterbasiert angenähert; mehr Abtastschritte verbessern laut Autor die Genauigkeit, erhöhen aber den Aufwand, und beim Zugriff auf Pixelwerte muss der Index innerhalb der Bilddaten bleiben.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
