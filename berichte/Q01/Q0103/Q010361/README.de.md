[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/PencilKit: PKToolPicker Not Showing/Hiding

Bericht Q010361 · Quelle medium.com · Datum 2025-05-08 · [Original öffnen](https://medium.com/gitconnected/swiftui-pencilkit-pktoolpicker-not-showing-hiding-f27ac3cbce3e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor führt einen nicht angezeigten `PKToolPicker` auf eine fehlende dauerhafte Referenz zurück und empfiehlt, den Picker außerhalb von `makeUIView` zu speichern. Beim Ein- und Ausblenden müsse `updateUIView` den übergebenen Canvas-Parameter verwenden, statt eine andere gespeicherte Canvas-Instanz anzusprechen; die Erklärung zur Freigabe des Pickers ist ausdrücklich eine Vermutung des Autors.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
