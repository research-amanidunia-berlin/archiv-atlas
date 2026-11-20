[English](README.md) · [Deutsch](README.de.md)

# (MTL S02E10) Manual Diagnostics: pt.2 Tooling-level

Bericht Q009675 · Quelle gostrobrod.medium.com · Datum 2026-05-18 · [Original öffnen](https://gostrobrod.medium.com/mtl-s02e10-manual-diagnostics-pt-2-tooling-level-9d63b2d709eb)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt Diagnosehilfen für Metal-Pipelines: Texturen nach Abschluss des GPU-Command-Buffers kopieren und auslesen, Zwischenbilder erfassen, Differenzen und Mip-Stufen visualisieren sowie GPU-Zähler einsetzen. Deterministische Shader-Mathematik kann teilweise CPU-seitig getestet werden; GPU-spezifisches Verhalten muss weiterhin auf der GPU geprüft werden. Diagnosecode soll das Produktionsverhalten nicht verändern und wegen möglicher Timing-Effekte bei Leistungsmessungen deaktiviert sein.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
