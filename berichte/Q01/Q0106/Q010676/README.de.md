[English](README.md) · [Deutsch](README.de.md)

# GCP: Obtain JWT OAuth tokens for Service Account

Bericht Q010676 · Quelle medium.com · Datum 2024-06-13 · [Original öffnen](https://medium.com/towardsdev/gcp-obtain-jwt-oauth-tokens-for-service-account-b1efafdaf07e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Bericht beschreibt die Erstellung eines RS256-signierten JWT mit Dienstkonto- und gegebenenfalls delegierten Nutzerangaben, den POST an Googles Token-Endpunkt und das Auslesen des Zugriffstokens. Als eigenen ColdFusion-Fallstrick nennt der Autor automatisch großgeschriebene Claim-Schlüssel, die bei ihm mit einem `400: invalid_client`-Fehler einhergingen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 33 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
