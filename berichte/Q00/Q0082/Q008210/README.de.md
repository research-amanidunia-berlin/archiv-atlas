[English](README.md) · [Deutsch](README.de.md)

# Reptile: A scalable meta-learning algorithm

Bericht Q008210 · Quelle openai.com · Datum 2018-03-07 · [Original öffnen](https://openai.com/index/reptile/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Reptile passt einen Modellstartpunkt an, indem es das Modell auf wechselnden Aufgaben mit mehreren SGD-Schritten trainiert und den Startpunkt in Richtung der resultierenden Parameter verschiebt. Laut Bericht erzielt es auf Omniglot und Mini-ImageNet ähnliche Leistungen wie MAML und konvergiert schneller; konkrete Messwerte und ausführliche Angaben zur Unsicherheit werden nicht genannt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | – | – | 7 / 15 % | – | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | – | – | 5 / 13 % | – | 0 / 0 % |
