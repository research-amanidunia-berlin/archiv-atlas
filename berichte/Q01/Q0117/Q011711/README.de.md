[English](README.md) · [Deutsch](README.de.md)

# Making a Performant Paged TabView

Bericht Q011711 · Quelle medium.com · Datum 2023-10-07 · [Original öffnen](https://medium.com/@jpmtech/making-a-performant-paged-tabview-45e360d55637)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor berichtet, dass seine SwiftUI-Lösung mit horizontaler `ScrollView` und `LazyHGrid` bei 100.000 Seiten im beschriebenen Simulatorversuch etwa 31 MB statt 360 MB beim Standard-`TabView` benötigte und flüssiger lief. Einschränkungen: Die Eigenlösung war laut Bericht nur im Hochformat zuverlässig und unterstützte iOS 16.4 nicht über den gezeigten Kompatibilitätsweg.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
