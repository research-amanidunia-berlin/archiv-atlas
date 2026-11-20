[English](README.md) · [Deutsch](README.de.md)

# Solving SwiftUI Performance Issues with the Instruments App

Bericht Q011678 · Quelle medium.com · Datum 2023-12-29 · [Original öffnen](https://medium.com/@jpmtech/solving-swiftui-performance-issues-with-the-instruments-app-fb4a9737e39e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht demonstriert anhand von Instruments-Messungen zwei SwiftUI-Leistungsprobleme: Eine Tab-Ansicht soll durch eine eigene Komponente ersetzt worden sein, woraufhin die App im Beispiel 19-mal schneller lief. In einem zweiten Beispiel beseitigt async-Code laut Autor weitgehend Bedienungshänger, während Memoisierung die weiterhin langsame Fibonacci-Berechnung stark beschleunigt; genaue Bedingungen und ein abschließender Laufzeitwert werden nicht genannt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
