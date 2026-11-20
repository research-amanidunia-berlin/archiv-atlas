[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Manage View State and Force a Screen Refresh/Reload

Bericht Q010683 · Quelle medium.com · Datum 2024-06-04 · [Original öffnen](https://medium.com/towardsdev/swiftui-manage-view-state-and-force-a-screen-refresh-reload-c5fe64ef682f)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht vergleicht zwei SwiftUI-Ansätze, um Ladeabläufe durch einen `ViewState` erneut auszuführen: die Ansicht neu aufzubauen oder intern mit `.onChange` auf Zustandswechsel zu reagieren. Der Autor bevorzugt die interne Zustandssteuerung und erweitert sie beispielhaft um Lade-, Fehler- und Abschlusszustände; die Aussagen beruhen auf den gezeigten Beispielen und eigenen Tests zur Verzögerung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
