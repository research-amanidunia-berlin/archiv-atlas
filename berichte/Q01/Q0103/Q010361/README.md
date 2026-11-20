[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/PencilKit: PKToolPicker Not Showing/Hiding

Report Q010361 · Source medium.com · Date 2025-05-08 · [Open original](https://medium.com/gitconnected/swiftui-pencilkit-pktoolpicker-not-showing-hiding-f27ac3cbce3e)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor führt einen nicht angezeigten `PKToolPicker` auf eine fehlende dauerhafte Referenz zurück und empfiehlt, den Picker außerhalb von `makeUIView` zu speichern. Beim Ein- und Ausblenden müsse `updateUIView` den übergebenen Canvas-Parameter verwenden, statt eine andere gespeicherte Canvas-Instanz anzusprechen; die Erklärung zur Freigabe des Pickers ist ausdrücklich eine Vermutung des Autors.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
