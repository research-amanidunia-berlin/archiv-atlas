[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Please SWITCH To MY Keyboard. Said by my Container App Input.

Bericht Q009792 · Quelle medium.com · Datum 2026-05-13 · [Original öffnen](https://medium.com/@itsuki.enjoy/swiftui-please-switch-to-my-keyboard-said-by-my-container-app-input-2e311af170c6)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor schlägt vor, den aktiven Zustand der eigenen Tastaturerweiterung über ein Bool-Flag in gemeinsam genutzten User Defaults an die Container-App zu melden. Er empfiehlt UIKit-Lebenszyklusmethoden statt SwiftUIs `onAppear` und `onDisappear`, die nach seiner Erfahrung unzuverlässig sein können, und zeigt ergänzend Overrides zur Auswahl einer Tastatur. Die Zuverlässigkeit über verschiedene iOS-Versionen hinweg wird nicht systematisch untersucht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
