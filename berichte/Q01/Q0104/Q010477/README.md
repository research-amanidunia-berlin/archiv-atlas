[English](README.md) · [Deutsch](README.de.md)

# Little Rust Tip: Create a Static at Runtime

Report Q010477 · Source medium.com · Date 2025-02-02 · [Open original](https://medium.com/gitconnected/little-rust-tip-create-a-static-at-runtime-fe0effd13fa9)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor zeigt anhand einer AWS-Region, warum ein zur Laufzeit aus der Umgebung gelesener Rust-String nicht einfach als `'static`-Referenz ausgeliehen werden kann. Als Lösung verwendet er `OnceLock<String>`, das den Wert samt Ersatzregion einmalig speichert und als statische Referenz bereitstellt; weitere Grenzen des Ansatzes werden nicht erläutert.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
