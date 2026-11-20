[English](README.md) · [Deutsch](README.de.md)

# HTML/Javascript: Global Function Variable Value based on Executed Script

Bericht Q010534 · Quelle medium.com · Datum 2024-12-07 · [Original öffnen](https://medium.com/gitconnected/html-javascript-global-function-variable-value-based-on-executed-script-6e32feaed801)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht empfiehlt, jedem Skript ein Datenattribut zu geben und es in einer globalen Funktion über `document.currentScript` auszulesen. Laut Autor funktioniert das beim unmittelbaren Aufruf, aber nicht zuverlässig in späteren Rückrufen oder Ereignis-Handlern, wo `document.currentScript` etwa `null` sein könne.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
