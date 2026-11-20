[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Caching in Layout Protocol

Bericht Q010536 · Quelle medium.com · Datum 2024-12-01 · [Original öffnen](https://medium.com/gitconnected/swiftui-caching-in-layout-protocol-a34c1052c7f3)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht erläutert, wie ein SwiftUI-Layout-Cache wiederverwendbare Werte wie Radius und Winkel speichern und bei Bedarf aktualisieren kann. An einem Spiral-Layout zeigt er außerdem, wie ein vorübergehend veränderter Cache Informationen durch rekursive Platzierungsaufrufe weitergibt; Grenzen sind die fehlende Größenprüfung im ersten Beispiel und das nicht implementierte `updateCache` im zweiten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
