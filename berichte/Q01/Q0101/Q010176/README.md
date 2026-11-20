[English](README.md) · [Deutsch](README.de.md)

# Rust: Verify Slack Request With Signed Secret

Report Q010176 · Source medium.com · Date 2025-08-29 · [Open original](https://medium.com/gitconnected/rust-verify-slack-request-with-signed-secret-3a413166c487)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag zeigt, wie Rust mit einem Slack Signing Secret und HMAC-SHA-256 die Signatur einer Anfrage prüfen kann. Dafür werden Zeitstempel und roher Anfragekörper verwendet; Anfragen mit mehr als fünf Minuten Zeitabweichung weist das Beispiel zurück, während der Autor die Wahl von `v0` als nicht ganz sicher erläutert kennzeichnet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
