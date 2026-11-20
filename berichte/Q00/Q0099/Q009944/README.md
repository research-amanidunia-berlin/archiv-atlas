[English](README.md) · [Deutsch](README.de.md)

# Supabase Edge function/WebSocket : ShutDown Right After Open, No Error, Cloud Only.

Report Q009944 · Source medium.com · Date 2026-01-08 · [Open original](https://medium.com/@itsuki.enjoy/supabase-edge-function-websocket-shutdown-right-after-open-no-error-cloud-only-1e28a4cf707c)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor beschreibt sofortige WebSocket-Abbrüche in gehosteten Supabase Edge Functions, obwohl der Code lokal funktionierte. Das Verschieben einer Datenbankabfrage in den Öffnungs-Handler und der Ersatz einer Bibliothek durch einen direkten `fetch`-Aufruf halfen in seinen Versuchen; CPU- und Speichergrenzen nennt er als Vermutungen, nicht als bestätigte Ursachen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 12 / 45 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
