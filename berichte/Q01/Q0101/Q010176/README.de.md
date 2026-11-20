[English](README.md) · [Deutsch](README.de.md)

# Rust: Verify Slack Request With Signed Secret

Bericht Q010176 · Quelle medium.com · Datum 2025-08-29 · [Original öffnen](https://medium.com/gitconnected/rust-verify-slack-request-with-signed-secret-3a413166c487)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag zeigt, wie Rust mit einem Slack Signing Secret und HMAC-SHA-256 die Signatur einer Anfrage prüfen kann. Dafür werden Zeitstempel und roher Anfragekörper verwendet; Anfragen mit mehr als fünf Minuten Zeitabweichung weist das Beispiel zurück, während der Autor die Wahl von `v0` als nicht ganz sicher erläutert kennzeichnet.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

Keine Sammelfrage erreicht bei einem Modell 10 % in Stufe 3–7.
