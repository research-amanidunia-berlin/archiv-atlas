[English](README.md) · [Deutsch](README.de.md)

# GCP: Obtain JWT OAuth tokens for Service Account

Report Q010676 · Source medium.com · Date 2024-06-13 · [Open original](https://medium.com/towardsdev/gcp-obtain-jwt-oauth-tokens-for-service-account-b1efafdaf07e)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Bericht beschreibt die Erstellung eines RS256-signierten JWT mit Dienstkonto- und gegebenenfalls delegierten Nutzerangaben, den POST an Googles Token-Endpunkt und das Auslesen des Zugriffstokens. Als eigenen ColdFusion-Fallstrick nennt der Autor automatisch großgeschriebene Claim-Schlüssel, die bei ihm mit einem `400: invalid_client`-Fehler einhergingen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 33 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
