[English](README.md) · [Deutsch](README.de.md)

# SwiftUI/MacOS: Detect/Listen To Global Key Events Two Ways!

Bericht Q009968 · Quelle medium.com · Datum 2025-12-23 · [Original öffnen](https://medium.com/gitconnected/swiftui-macos-detect-listen-to-global-key-events-two-ways-df19e565793d)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel stellt `NSEvent`-Monitor und `CGEventTap` als zwei Wege vor, globale Tastaturereignisse in macOS-Apps zu behandeln: Der erste lässt Ereignisse an andere Apps weiterlaufen, der zweite kann sie abfangen. Er beschreibt Beispiele und Berechtigungen, lässt aber ungeklärt, warum das `CGEventTap`-Beispiel zusätzlich Bedienungshilfen-Zugriff prüft, obwohl der Text Input Monitoring als erforderlich nennt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
