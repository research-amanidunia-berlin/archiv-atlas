[English](README.md) · [Deutsch](README.de.md)

# Little Swift Tip: AttributedString Attention Points

Bericht Q009644 · Quelle medium.com · Datum 2026-09-19 · [Original öffnen](https://medium.com/@itsuki.enjoy/little-swift-tip-attributedstring-attention-points-60285ed4cfd8)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor nennt vier Probleme bei Swift-Attributtexten: Formatierungen können bei `transformAttributes` über mehrere unterschiedlich formatierte Runs verloren gehen, `transform(updating:)` betreffe seiner Interpretation nach den gesamten String, das Zusammenführen könne das Entfernen von Attributen über `nil` ignorieren, und eigene Attribute würden nicht automatisch in Schreibattribute übernommen. Er zeigt mögliche Umgehungen, weist aber selbst auf Grenzen hin, insbesondere bei nicht zusammenhängenden Auswahlen; eine systematische Versionsprüfung beschreibt der Erfahrungsbericht nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
