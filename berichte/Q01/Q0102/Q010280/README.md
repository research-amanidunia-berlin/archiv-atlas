[English](README.md) · [Deutsch](README.de.md)

# Rust/Axum: Custom Error Handling on Rejection

Report Q010280 · Source medium.com · Date 2025-07-03 · [Open original](https://medium.com/gitconnected/rust-axum-custom-error-handling-on-rejection-8b5a10e7d8bc)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht zeigt, wie Axum-Handler mit `Result<T, T::Rejection>` konkrete Extraktionsfehler erkennen und eigene Antworten erstellen können. Eigene Extractors ermöglichen laut Autor flexiblere Eingabeformate, liefern aber oft weniger genaue Fehlermeldungen; bei Bedarf an Request-Teilen und Body empfiehlt er `FromRequest` mit erst `extract_parts`, dann `extract`.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
