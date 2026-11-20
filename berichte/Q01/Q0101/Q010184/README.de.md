[English](README.md) · [Deutsch](README.de.md)

# Rust: Dyn (Dynamic Dispatch) vs Generics (Monomorphism)

Bericht Q010184 · Quelle medium.com · Datum 2025-08-26 · [Original öffnen](https://medium.com/stackademic/rust-dyn-dynamic-dispatch-vs-generics-monomorphism-91ecafb5e324)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Dynamische Trait-Objekte können in Rust verschiedene konkrete Typen gemeinsam speichern; Generics stehen im Beispiel jeweils für einen konkreten Typ. Der Benchmark des Artikels zeigt einen kleinen Vorteil für die statische Variante, ist aber durch unterschiedliche Testfälle und fehlende Angaben zur Umgebung begrenzt; der Autor empfiehlt, primär nach dem Bedarf für mehrere Typen zu entscheiden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
