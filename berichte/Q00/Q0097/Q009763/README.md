[English](README.md) · [Deutsch](README.de.md)

# Swift: Timeout Await Functions that JUST DON’T Cancel

Report Q009763 · Source medium.com · Date 2026-06-01 · [Open original](https://medium.com/@itsuki.enjoy/swift-timeout-await-functions-that-just-dont-cancel-61b69a4a83f4)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Itsuki zeigt, dass sein Swift-Timeout bei einer gewöhnlichen Schlafoperation früh abbricht, eine über `withCheckedContinuation` eingebundene Completion-Handler-Funktion in den Beispielen aber weiterläuft. Ein Ansatz mit getrenntem Timer-Task lässt den Aufrufer früh zurückkehren, beendet die eigentliche Arbeit jedoch nicht; der Bericht beansprucht keine allgemeingültige Abbruchlösung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
