[English](README.md) · [Deutsch](README.de.md)

# Little Typescript Tip: A Better(?) Way to create Union of Literal Types

Bericht Q010530 · Quelle medium.com · Datum 2024-12-12 · [Original öffnen](https://medium.com/gitconnected/little-typescript-tip-a-better-way-to-create-union-of-literal-types-d5264ac26803)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag erklärt, wie man mit `as const`, `typeof` und `keyof` aus den Werten eines Objekts eine TypeScript-Union wie `"english" | "japanese"` ableitet und daraus weitere gemappte Typen erstellt. Der Autor bevorzugt diesen Ansatz persönlich gegenüber Enums, führt im Text aber keinen systematischen Vergleich oder konkrete Belege für diese Empfehlung an.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
