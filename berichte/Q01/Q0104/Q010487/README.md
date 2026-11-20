[English](README.md) · [Deutsch](README.de.md)

# Tailwind Style Not Show Up in NextJs Standalone (Regular Build & Docker)

Report Q010487 · Source medium.com · Date 2025-01-25 · [Open original](https://medium.com/gitconnected/tailwind-style-not-show-up-in-nextjs-standalone-regular-build-docker-f09630ca2b2c)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor führt fehlende Tailwind-Stile in seinem Next.js-Standalone-Build darauf zurück, dass `.next/static` nicht automatisch kopiert wird. Er empfiehlt, die Dateien nach `.next` zu kopieren – im Docker-Beispiel nach `./.next`, damit nicht versehentlich `.next/static/static` entsteht. Laut seinem Bericht behebt das den Fehler in seiner Anwendung; eine allgemeine Prüfung anderer Konfigurationen enthält der Text nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

No collected question reaches 10 % in levels 3–7 with any model.
