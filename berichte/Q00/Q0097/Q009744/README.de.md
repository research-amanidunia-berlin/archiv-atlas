[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: A Custom ScrollView Without ScrollView

Bericht Q009744 · Quelle medium.com · Datum 2026-06-17 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-macos-a-custom-scrollview-without-scrollview-802b1589be3e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt, wie er Scroll-Deltas unter macOS mit einem lokalen `NSEvent`-Monitor erfasst und damit eine SwiftUI-Ansicht verschiebt. Einen `NSPanGestureRecognizer` und ein überlagertes `NSView` verwirft er aufgrund seiner Erfahrungen mit Gestenerkennung beziehungsweise blockiertem Hit-Testing; die vermutete Beta-Fehlerursache bleibt unbestätigt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
