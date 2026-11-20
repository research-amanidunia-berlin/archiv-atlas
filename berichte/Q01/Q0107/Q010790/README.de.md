[English](README.md) · [Deutsch](README.de.md)

# IOS/Swift: Remove/Change UIButton Paddings

Bericht Q010790 · Quelle medium.com · Datum 2024-01-18 · [Original öffnen](https://medium.com/@itsuki.enjoy/ios-swift-remove-change-uibutton-paddings-3baaf25946b1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht beschreibt drei Storyboard-Inset-Einstellungen für Button-Inhalte und zeigt Code-Alternativen, falls diese nicht wie gewünscht greifen. Für ältere iOS-Versionen verwendet der Autor `contentEdgeInsets` mit einem nahezu null gesetzten Wert; ab iOS 15 empfiehlt der Artikel stattdessen `UIButton.Configuration` mit `contentInsets`.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
