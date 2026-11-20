[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: Sync User Preferences with iCloud Key-Value Storage

Bericht Q010270 · Quelle medium.com · Datum 2025-07-08 · [Original öffnen](https://medium.com/gitconnected/swiftui-sync-user-preferences-with-icloud-key-value-storage-252d155c8a1b)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt, wie `NSUbiquitousKeyValueStore` SwiftUI-Einstellungen über iCloud abgleichen kann, und zeigt Einrichtung, Benachrichtigungsverarbeitung sowie einen Beispielmanager. Der Abgleich ist systemgesteuert und nicht sofort garantiert; `synchronize()` erzwingt laut Artikel keinen Upload, auch wenn der Autor berichtet, dass er den Aufruf in seinem Beispiel für zuverlässiges Verhalten benötigte.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
