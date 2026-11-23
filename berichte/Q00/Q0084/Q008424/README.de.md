[English](README.md) · [Deutsch](README.de.md)

# Learning Montezuma’s Revenge from a single demonstration

Bericht Q008424 · Quelle openai.com · Datum 2018-07-04 · [Original öffnen](https://openai.com/index/learning-montezumas-revenge-from-a-single-demonstration/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI zufolge erreichte ein mit einer Demonstration und PPO trainierter Agent in *Montezuma’s Revenge* 74.500 Punkte und übertraf damit die Demonstration. Er lernte schrittweise von Spielzuständen nahe dem Ende zurück bis zum Start, wobei der Bericht auch die Nutzung eines Emulatorfehlers erwähnt. Die Methode blieb empfindlich gegenüber Trainingsparametern und zufälligen Abweichungen; bei anderen Spielen und gestörten Aktionen waren die Ergebnisse deutlich schwächer.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 10 / 49 % | – | 6 / 13 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 6 / 44 % | – | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 10 % | – | – |
