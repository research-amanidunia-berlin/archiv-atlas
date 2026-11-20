[English](README.md) · [Deutsch](README.de.md)

# Little SwiftUI Tip: When Picker Options Depends On Some Other Controls

Bericht Q009964 · Quelle medium.com · Datum 2025-12-25 · [Original öffnen](https://medium.com/@itsuki.enjoy/little-swiftui-tip-when-picker-options-depends-on-some-other-controls-75e5cb5a3f25)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, dass ein abhängiger SwiftUI-Picker trotz scheinbar korrekter Anzeige im Simulator eine ungültige Auswahl melden kann. Itsuki empfiehlt, den Picker nur einzublenden, wenn die aktuelle Auswahl zu den Optionen gehört; im beschriebenen Beispiel verschwanden dadurch die Warnungen, doch mögliche Probleme in anderen Fällen oder im Produktivbetrieb werden nicht ausgeschlossen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
