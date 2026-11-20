[English](README.md) · [Deutsch](README.de.md)

# Supabase Edge function/WebSocket : ShutDown Right After Open, No Error, Cloud Only.

Bericht Q009944 · Quelle medium.com · Datum 2026-01-08 · [Original öffnen](https://medium.com/@itsuki.enjoy/supabase-edge-function-websocket-shutdown-right-after-open-no-error-cloud-only-1e28a4cf707c)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt sofortige WebSocket-Abbrüche in gehosteten Supabase Edge Functions, obwohl der Code lokal funktionierte. Das Verschieben einer Datenbankabfrage in den Öffnungs-Handler und der Ersatz einer Bibliothek durch einen direkten `fetch`-Aufruf halfen in seinen Versuchen; CPU- und Speichergrenzen nennt er als Vermutungen, nicht als bestätigte Ursachen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 12 / 45 % | 0 / 0 % | – | 0 / 0 % | – |
