[English](README.md) · [Deutsch](README.de.md)

# Little SwiftUI Tip:  Pull To Refresh For WebView

Bericht Q010041 · Quelle medium.com · Datum 2025-11-11 · [Original öffnen](https://medium.com/gitconnected/little-swiftui-tip-pull-to-refresh-for-webview-98042334c2d5)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag beschreibt, wie man eine SwiftUI-WebView für Pull-to-Refresh in eine `ScrollView` einbettet und ihre Höhe mit `.containerRelativeFrame(.vertical)` an den Container anpasst. Laut Autor muss `webPage.reload()` asynchron abgewartet werden, damit der Ladeindikator bis zum Ende des Neuladens sichtbar bleibt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
