[English](README.md) · [Deutsch](README.de.md)

# Streaming in Rust

Report Q010703 · Source medium.com · Date 2024-05-12 · [Open original](https://medium.com/stackademic/streaming-in-rust-4155c7063eb6)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht zeigt, wie Rust-Streams erstellt und Antworten einer Streaming-Anfrage an die ChatGPT-API verarbeitet werden können. Weil Byte-Chunks mehrere Ereignisse enthalten oder JSON über Chunk-Grenzen geteilt sein kann, puffert der Beispielparser unvollständige Daten und behandelt Endsignal sowie Fehler gesondert; die Lösung beruht auf den Beobachtungen des Autors und ist kein Nachweis für alle möglichen Fälle.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
