[English](README.md) · [Deutsch](README.de.md)

# SwiftUI AppStorage: DO NOT USE DOT(.)! In That KEY!

Report Q009825 · Source medium.com · Date 2026-04-10 · [Open original](https://medium.com/@itsuki.enjoy/swiftui-appstorage-do-not-use-dot-in-that-key-21e88d3c3c0b)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor berichtet, dass ein Punkt im `AppStorage`-Schlüssel bei seinen Tests die Änderungsbeobachtung zwischen App und Tastaturerweiterung stört, obwohl der Wert gespeichert wird. Schlüssel ohne Punkt oder mit Unterstrich synchronisieren laut ihm in beide Richtungen; die Erklärung über KVO und den Richtungsunterschied bleibt eine Vermutung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
