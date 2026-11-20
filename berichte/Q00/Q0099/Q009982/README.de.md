[English](README.md) · [Deutsch](README.de.md)

# Little SwiftUI Tip: Get & Set & Watch Interface Orientation & Orientation Lock

Bericht Q009982 · Quelle medium.com · Datum 2025-12-17 · [Original öffnen](https://medium.com/@itsuki.enjoy/little-swiftui-tip-get-set-watch-interface-orientation-orientation-lock-5076a0923c14)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag beschreibt das Auslesen und Beobachten der UI-Ausrichtung über `UIWindowScene.effectiveGeometry` sowie das Anfordern einer Ausrichtung mit `requestGeometryUpdate`. Laut Autor kann die gewünschte Orientierung abgelehnt werden; eine Orientierungssperre ließ sich in seinen Versuchen nicht zuverlässig allein mit SwiftUI setzen, und die Laufzeitaussagen beruhen auf eigenen Tests.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
