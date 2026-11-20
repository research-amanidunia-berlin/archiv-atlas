[English](README.md) · [Deutsch](README.de.md)

# SwiftUI AppStorage: DO NOT USE DOT(.)! In That KEY!

Bericht Q009825 · Quelle medium.com · Datum 2026-04-10 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-appstorage-do-not-use-dot-in-that-key-21e88d3c3c0b)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor berichtet, dass ein Punkt im `AppStorage`-Schlüssel bei seinen Tests die Änderungsbeobachtung zwischen App und Tastaturerweiterung stört, obwohl der Wert gespeichert wird. Schlüssel ohne Punkt oder mit Unterstrich synchronisieren laut ihm in beide Richtungen; die Erklärung über KVO und den Richtungsunterschied bleibt eine Vermutung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
