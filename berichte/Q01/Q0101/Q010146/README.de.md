[English](README.md) · [Deutsch](README.de.md)

# SwiftUI: LongPressGesture OnChange Not triggered! Updating Not triggered!

Bericht Q010146 · Quelle medium.com · Datum 2025-09-17 · [Original öffnen](https://medium.com/gitconnected/swiftui-longpressgesture-onchange-not-triggered-updating-not-triggered-30e241a7820d)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Beitrag zeigt, dass `onChanged` und `updating` laut Autor bei `LongPressGesture(minimumDuration: 0)` keinen brauchbaren gedrückten Zustand liefern; bei `updating` klappt das Beispiel mit einer Sekunde Mindestdauer. Als funktionierende Lösung für Dauer null nennt er `onLongPressGesture` mit `onPressingChanged`, kann den Unterschied der Callbacks aber nicht erklären.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
