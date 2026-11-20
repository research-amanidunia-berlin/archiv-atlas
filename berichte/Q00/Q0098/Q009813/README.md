[English](README.md) · [Deutsch](README.de.md)

# SwiftUI / Keyboard Kit: Be Careful On Retaining Self! weak self WITHIN weak self is required!

Report Q009813 · Source medium.com · Date 2026-04-21 · [Open original](https://medium.com/@itsuki.enjoy/swiftui-keyboard-extension-dont-use-keyboard-kit-eece34c21441)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor führt den steigenden Speicherverbrauch seiner Keyboard-Kit-Tastatur auf eine gespeicherte Rückruffunktion zurück, die den View Controller über eine direkte Methodenreferenz festhielt. Eine eigene Rückruffunktion mit erneutem [weak self] habe den Verbrauch in seinem Fall stabilisiert; der Bericht belegt keine allgemeine Ursache für vergleichbare Probleme.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
