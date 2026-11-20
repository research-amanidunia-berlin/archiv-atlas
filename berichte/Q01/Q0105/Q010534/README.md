[English](README.md) · [Deutsch](README.de.md)

# HTML/Javascript: Global Function Variable Value based on Executed Script

Report Q010534 · Source medium.com · Date 2024-12-07 · [Open original](https://medium.com/gitconnected/html-javascript-global-function-variable-value-based-on-executed-script-6e32feaed801)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht empfiehlt, jedem Skript ein Datenattribut zu geben und es in einer globalen Funktion über `document.currentScript` auszulesen. Laut Autor funktioniert das beim unmittelbaren Aufruf, aber nicht zuverlässig in späteren Rückrufen oder Ereignis-Handlern, wo `document.currentScript` etwa `null` sein könne.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
