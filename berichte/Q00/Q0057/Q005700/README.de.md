[English](README.md) · [Deutsch](README.de.md)

# Experts Don't Cheat: Learning What You Don't Know by Predicting Pairs

Bericht Q005700 · Quelle deepmind.google · Datum 2024-02-15 · [Original öffnen](https://deepmind.google/research/publications/73709/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug stellt eine Methode vor, bei der Modelle Antwortpaare vorhersagen und dabei eine Antwort nutzen dürfen, um die andere besser einzuschätzen; wie stark sie diesen Vorteil nutzen, soll fehlendes Wissen sichtbar machen. Laut Abstract beruht dies auf einer theoretischen Verbindung zu zweitordentlicher Kalibrierung und wurde in drei Aufgabenbereichen erfolgreich getestet. Konkrete Messwerte und Details zu den Grenzen sind im bereitgestellten Abstract nicht enthalten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 12 / 45 % | 88 / 95 % | 10 / 26 % | 0 / 0 % | 5 / 17 % | 1 / 10 % | 22 / 40 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 3 / 30 % | 0 / 0 % | 10 / 27 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 32 / 50 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 0 / 0 % | 28 / 61 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 26 / 50 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 33 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 32 % | 0 / 0 % | 9 / 24 % | 2 / 14 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 9 / 53 % | 0 / 0 % | 9 / 27 % | 0 / 0 % | 6 / 17 % | 1 / 10 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
