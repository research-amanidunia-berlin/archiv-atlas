[English](README.md) · [Deutsch](README.de.md)

# Rust Excel Reader (Parser) Part2: Parse Some Drawings!

Bericht Q010337 · Quelle medium.com · Datum 2025-05-26 · [Original öffnen](https://medium.com/gitconnected/rust-excel-reader-parser-part2-parse-some-drawings-93adcc6b503b)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Artikel gibt einen Überblick darüber, wie ein Rust-Parser Zeichnungen in Excel-Dateien über DrawingML-Beziehungen findet und deren Inhalte, Verankerung, Position, Gestaltung und Text ausliest. Der Autor sieht vollständiges Parsen von Grafikrahmen wegen ihrer beliebigen XML-Inhalte als kaum praktikabel an und beschränkt den möglichen Ansatz auf die Erkennung des Objekttyps; die Darstellung bleibt insgesamt auf hoher Ebene.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
