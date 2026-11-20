[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Create App-Specific Custom Keyboard

Bericht Q010639 · Quelle medium.com · Datum 2024-07-20 · [Original öffnen](https://medium.com/gitconnected/swiftui-create-app-specific-custom-keyboard-e080b4378029)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, wie eine SwiftUI-Tastatur über `UIHostingController`, `UIViewRepresentable` und `UIInputView` als app-spezifische Tastatur eines `UITextField` eingebunden wird. Laut Autor muss die Tastatur den Feldtext direkt ändern, weil die gezeigte State-Synchronisierung nur vom Textfeld zurück zum SwiftUI-State verläuft; alternativ demonstriert er `UITextDocumentProxy`.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
