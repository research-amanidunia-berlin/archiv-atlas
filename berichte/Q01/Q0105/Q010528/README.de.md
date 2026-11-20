[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Protect Private Information

Bericht Q010528 · Quelle medium.com · Datum 2024-12-15 · [Original öffnen](https://medium.com/gitconnected/swiftui-protect-private-information-2c4bcab3552e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor verbindet `privacySensitive()` für den inaktiven Zustand mit einem UIKit-Umweg über `UITextField.isSecureTextEntry`, um private SwiftUI-Inhalte bei Screenshots und Aufnahmen zu verbergen; eigene Masken seien möglich, benötigten aber einen undurchsichtigen Hintergrund. Laut Beitrag lassen sich die Schutzarten bündeln, doch Screenshots seien nicht vorab erkennbar und der Schutz funktioniere nicht im Simulator, sondern müsse auf einem echten Gerät laufen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
