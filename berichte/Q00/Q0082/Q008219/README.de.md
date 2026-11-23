[English](README.md) · [Deutsch](README.de.md)

# Simplifying, stabilizing, and scaling continuous-time consistency models

Bericht Q008219 · Quelle openai.com · Datum 2024-10-23 · [Original öffnen](https://openai.com/index/simplifying-stabilizing-and-scaling-continuous-time-consistency-models/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt sCM als Verfahren, das kontinuierliche Consistency-Modelle stabiler trainieren und auf zwei Sampling-Schritte beschleunigen soll. Laut Bericht erreicht es dabei vergleichbare Qualität zu führenden Diffusionsmodellen bei deutlich geringerem Sampling-Aufwand, bleibt aber von vortrainierten Diffusionsmodellen abhängig und weist einen kleinen Qualitätsabstand auf; zudem bildet FID Qualität nur begrenzt ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 80 / 87 % | 12 / 31 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 67 / 85 % | 18 / 34 % | 14 / 32 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | 60 / 67 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 7 / 47 % | 38 / 59 % | 6 / 14 % | 0 / 0 % | 4 / 9 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 20 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 19 / 34 % | 9 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 10 % | – | – |
