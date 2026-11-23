[English](README.md) · [Deutsch](README.de.md)

# Learning dexterity

Bericht Q008347 · Quelle openai.com · Datum 2018-07-30 · [Original öffnen](https://openai.com/index/learning-dexterity/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAIs Dactyl lernte in einer absichtlich variierten Simulation, Objekte mit einer Roboterhand zu drehen, und übertrug die Steuerung ohne Feinanpassung auf den realen Roboter. Bei Blockversuchen schnitt Training mit Randomisierung deutlich besser ab als ohne; die Ergebnisse waren bei einem Prisma gut, bei einer Kugel aber begrenzt. Die Autoren betonen, dass die Befunde auf die getesteten Objekte und Bedingungen beschränkt sind.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 62 / 88 % | 93 / 96 % | 10 / 23 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 51 / 87 % | 86 / 90 % | 7 / 19 % | 0 / 0 % | 10 / 23 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 71 / 80 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 60 / 88 % | 24 / 52 % | 8 / 25 % | 0 / 0 % | 7 / 17 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 60 / 77 % | 6 / 13 % | 0 / 0 % | 5 / 11 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 9 / 48 % | 53 / 66 % | 8 / 21 % | 0 / 0 % | 7 / 19 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 25 / 66 % | 36 / 51 % | 21 / 40 % | 0 / 0 % | 9 / 17 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 0 / 0 % | 32 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 19 / 48 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 18 / 58 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 8 / 15 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | – | – |
