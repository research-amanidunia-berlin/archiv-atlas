[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: A Custom ScrollView Without ScrollView

Report Q009744 · Source medium.com · Date 2026-06-17 · [Open original](https://medium.com/@itsuki.enjoy/swiftui-macos-a-custom-scrollview-without-scrollview-802b1589be3e)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor beschreibt, wie er Scroll-Deltas unter macOS mit einem lokalen `NSEvent`-Monitor erfasst und damit eine SwiftUI-Ansicht verschiebt. Einen `NSPanGestureRecognizer` und ein überlagertes `NSView` verwirft er aufgrund seiner Erfahrungen mit Gestenerkennung beziehungsweise blockiertem Hit-Testing; die vermutete Beta-Fehlerursache bleibt unbestätigt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
