[English](README.md) · [Deutsch](README.de.md)

# Understanding Learning from Human Preferences

Bericht Q005215 · Quelle deepmind.google · Datum 2024-03-11 · [Original öffnen](https://deepmind.google/research/publications/54918/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Text ist nur ein Auszug aus dem Abstract. Er stellt ΨPO vor, ein direkt auf paarweisen Präferenzen beruhendes Lernziel, das zwei Annahmen verbreiteter RLHF-Verfahren umgehen soll, und beschreibt IPO als Sonderfall mit Optimierungsverfahren und Leistungsgarantien. Laut Abstract können RLHF und DPO trotz Regularisierung übertrainieren, während IPO robust bleibe; Einzelheiten und Grenzen sind im Auszug nicht enthalten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 60 / 84 % | 9 / 25 % | 6 / 16 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 20 / 62 % | 0 / 0 % | 56 / 77 % | 14 / 38 % | 8 / 20 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 14 / 42 % | 0 / 0 % | 0 / 0 % | 12 / 32 % | 0 / 0 % |
