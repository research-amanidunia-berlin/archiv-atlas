[English](README.md) · [Deutsch](README.de.md)

# Streaming in Rust

Bericht Q010703 · Quelle medium.com · Datum 2024-05-12 · [Original öffnen](https://medium.com/stackademic/streaming-in-rust-4155c7063eb6)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht zeigt, wie Rust-Streams erstellt und Antworten einer Streaming-Anfrage an die ChatGPT-API verarbeitet werden können. Weil Byte-Chunks mehrere Ereignisse enthalten oder JSON über Chunk-Grenzen geteilt sein kann, puffert der Beispielparser unvollständige Daten und behandelt Endsignal sowie Fehler gesondert; die Lösung beruht auf den Beobachtungen des Autors und ist kein Nachweis für alle möglichen Fälle.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
