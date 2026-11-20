[English](README.md) · [Deutsch](README.de.md)

# Swift: Continuation, Convert Completion Handlers/Callback into async & async throws, Prevent…

Report Q010692 · Source medium.com · Date 2024-05-25 · [Open original](https://medium.com/towardsdev/swift-continuation-and-convert-completion-handlers-callback-into-async-async-throws-3895c76980c1)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Artikel erklärt anhand einfacher Swift-Beispiele, wie `withCheckedContinuation` und `withCheckedThrowingContinuation` Completion-Handler in `async`- beziehungsweise `async throws`-Funktionen überführen. Gegen mehrfaches Fortsetzen empfiehlt der Autor, eine optionale Continuation nach dem ersten Aufruf auf `nil` zu setzen; weitergehende Fragen zur Synchronisierung werden nicht behandelt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
