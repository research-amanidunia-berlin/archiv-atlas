[English](README.md) · [Deutsch](README.de.md)

# Prompt Caching: Why Cached Tokens Are 10× Cheaper and Faster

Bericht Q011329 · Quelle medium.com · Datum 2025-12-23 · [Original öffnen](https://medium.com/coding-nexus/prompt-caching-why-cached-tokens-are-10-cheaper-and-faster-cf3c5cefd4c5)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Artikel erklärt Prompt-Caching als Wiederverwendung von Key- und Value-Werten aus dem Attention-Mechanismus, wodurch laut Beitrag Berechnungen für bereits verarbeitete Promptteile entfallen. Er führt mögliche Kosten- und Latenzvorteile an und vergleicht das Caching bei OpenAI und Anthropic, belegt die genannten Zahlen jedoch nicht unabhängig und vereinfacht technische Details.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 9 / 76 % | 0 / 0 % | 80 / 93 % | 6 / 16 % | 3 / 9 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 49 / 72 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 5 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
