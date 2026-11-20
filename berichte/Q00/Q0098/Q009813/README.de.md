[English](README.md) · [Deutsch](README.de.md)

# SwiftUI / Keyboard Kit: Be Careful On Retaining Self! weak self WITHIN weak self is required!

Bericht Q009813 · Quelle medium.com · Datum 2026-04-21 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-keyboard-extension-dont-use-keyboard-kit-eece34c21441)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor führt den steigenden Speicherverbrauch seiner Keyboard-Kit-Tastatur auf eine gespeicherte Rückruffunktion zurück, die den View Controller über eine direkte Methodenreferenz festhielt. Eine eigene Rückruffunktion mit erneutem [weak self] habe den Verbrauch in seinem Fall stabilisiert; der Bericht belegt keine allgemeine Ursache für vergleichbare Probleme.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
