[English](README.md) · [Deutsch](README.de.md)

# Rust/Axum: Custom Error Handling on Rejection

Bericht Q010280 · Quelle medium.com · Datum 2025-07-03 · [Original öffnen](https://medium.com/gitconnected/rust-axum-custom-error-handling-on-rejection-8b5a10e7d8bc)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht zeigt, wie Axum-Handler mit `Result<T, T::Rejection>` konkrete Extraktionsfehler erkennen und eigene Antworten erstellen können. Eigene Extractors ermöglichen laut Autor flexiblere Eingabeformate, liefern aber oft weniger genaue Fehlermeldungen; bei Bedarf an Request-Teilen und Body empfiehlt er `FromRequest` mit erst `extract_parts`, dann `extract`.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
