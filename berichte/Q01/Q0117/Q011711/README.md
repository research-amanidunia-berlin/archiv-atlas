[English](README.md) · [Deutsch](README.de.md)

# Making a Performant Paged TabView

Report Q011711 · Source medium.com · Date 2023-10-07 · [Open original](https://medium.com/@jpmtech/making-a-performant-paged-tabview-45e360d55637)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor berichtet, dass seine SwiftUI-Lösung mit horizontaler `ScrollView` und `LazyHGrid` bei 100.000 Seiten im beschriebenen Simulatorversuch etwa 31 MB statt 360 MB beim Standard-`TabView` benötigte und flüssiger lief. Einschränkungen: Die Eigenlösung war laut Bericht nur im Hochformat zuverlässig und unterstützte iOS 16.4 nicht über den gezeigten Kompatibilitätsweg.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
