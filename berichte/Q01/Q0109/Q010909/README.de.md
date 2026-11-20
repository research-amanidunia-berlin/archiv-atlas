[English](README.md) · [Deutsch](README.de.md)

# How Claude Actually Works — A Developer’s Guide to LLMs Without the Math

Bericht Q010909 · Quelle medium.com · Datum 2026-06-20 · [Original öffnen](https://medium.com/@aitrends24/how-claude-actually-works-a-developers-guide-to-llms-without-the-math-2d663c5b71e4)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vollständige Beitrag erklärt Claude als Modell, das Eingaben in Tokens und Zahlenrepräsentationen umwandelt, Zusammenhänge per Aufmerksamkeit gewichtet und Antworten schrittweise Token für Token erzeugt. Der Autor leitet daraus Empfehlungen für knappe, klare Prompts ab und betont zugleich, dass der Rechenaufwand langer Kontexte sowie der Übergang zu scheinbarem Schlussfolgern nur teilweise erklärt sind; eigene Tests berichtet der Beitrag nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 39 / 82 % | 1 / 15 % | 96 / 99 % | 12 / 38 % | 7 / 24 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 23 / 91 % | 0 / 7 % | 92 / 98 % | 7 / 26 % | 3 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 55 / 96 % | 0 / 4 % | 28 / 77 % | 5 / 17 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 8 / 58 % | 0 / 0 % | 0 / 0 % | 6 / 25 % | 5 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 1 / 32 % | 0 / 0 % | 0 / 10 % | 5 / 11 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 3 / 58 % | 0 / 2 % | 0 / 0 % | 5 / 13 % | 4 / 7 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 1 / 52 % | 0 / 0 % | 0 / 0 % | 5 / 19 % | 4 / 9 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 6 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 2 / 56 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
