[English](README.md) · [Deutsch](README.de.md)

# Does Self-Improvement Still Work on an Engineered Agent Harness?

Bericht Q005255 · Quelle alphasignal.ai · Datum 2026-08-19 · [Original öffnen](https://alphasignal.ai/news/does-self-improvement-still-work-on-an-engineered-agent-harness)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug berichtet von zwei SWE-bench-Agenten-Harnesses: Verbesserungen auf den jeweiligen Validierungssätzen führten nicht durchweg zu ebenso klaren Gewinnen auf versiegelten Aufgaben. Die Autorin stellt deshalb die Zuverlässigkeit der Prüfsätze in den Mittelpunkt; der Bericht ist unvollständig und endet, bevor Versuchsaufbau und weitere Ergebnisse ausgeführt werden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 32 / 53 % | 77 / 94 % | – | 33 / 60 % | 0 / 0 % | 24 / 44 % | 6 / 22 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 33 / 57 % | 75 / 93 % | – | 48 / 70 % | 22 / 40 % | 38 / 60 % | 27 / 64 % | 31 / 57 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 48 / 93 % | – | 10 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 43 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 30 / 82 % | – | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 29 / 81 % | – | 6 / 14 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 14 / 41 % | 22 / 58 % | – | 9 / 22 % | 0 / 0 % | 0 / 0 % | 3 / 17 % | 6 / 23 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 21 / 65 % | – | 11 / 29 % | 0 / 0 % | 7 / 20 % | 1 / 11 % | 13 / 28 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | – | 12 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | – | 8 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | – | 8 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | – | 7 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 6 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 6 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
