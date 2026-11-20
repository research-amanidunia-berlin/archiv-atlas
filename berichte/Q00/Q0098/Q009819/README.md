[English](README.md) · [Deutsch](README.de.md)

# Swift/iOS: Release File Lock If App Not Running Actively!

Report Q009819 · Source medium.com · Date 2026-04-15 · [Open original](https://medium.com/@itsuki.enjoy/swift-ios-release-file-lock-if-app-not-running-actively-6ea1d9d5bdeb)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor führt die beschriebenen Abstürze von TestFlight-Builds auf eine beim App-Start erworbene Dateisperre zurück: Ohne `acquireLock()` trat der Fehler in seinen Versuchen nicht mehr auf. Als Ersatz schlägt er einen regelmäßig aktualisierten Heartbeat vor; seine Beobachtungen beschränken sich auf den geschilderten Fall und unterscheiden sich von den problemlos laufenden lokalen Builds.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 92 / 94 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 53 / 78 % | 0 / 0 % | 83 / 89 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
