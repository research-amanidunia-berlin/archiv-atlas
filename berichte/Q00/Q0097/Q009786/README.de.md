[English](README.md) · [Deutsch](README.de.md)

# Swift: Wait! Locale.current is NOT My Current Locale?

Bericht Q009786 · Quelle medium.com · Datum 2026-05-15 · [Original öffnen](https://medium.com/@itsuki.enjoy/swift-wait-locale-current-is-not-my-current-locale-b68a571e99a1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor berichtet, dass `Locale.current` in seiner nur englischsprachigen App zwar die richtige Region, aber nicht die erwartete Gerätesprache liefert. Er empfiehlt `Locale.preferredLocales` oder `Locale.preferredLanguages`, die laut ihm bevorzugte Sprachen und App-spezifische Überschreibungen abbilden; eine umfassende Prüfung legt der Bericht nicht vor.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
