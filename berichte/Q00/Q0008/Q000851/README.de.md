[English](README.md) · [Deutsch](README.de.md)

# Reflections from red-teaming Codex auto-review

Bericht Q000851 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/monitoring/reflections-from-red-teaming-codex-auto-review)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Text ist ein Auszug und enthält keine detaillierten Testergebnisse. Apollo beschreibt einen Red-Team-Pilotversuch mit OpenAI zu Codex Auto-Review und betont Fragen zur Herkunft von Genehmigungen, zur Bedeutung ausdrücklicher Verbote, zu organisatorischen Zuständigkeiten und zu informierter Zustimmung bei Datenweitergaben. Laut Apollo wurden Schwachstellen gefunden; künftig sollen eingebettete Evaluierungen stärker in den Mittelpunkt rücken.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 57 / 73 % | 93 / 98 % | – | 82 / 91 % | 75 / 86 % | 76 / 85 % | 87 / 94 % | 47 / 71 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 36 / 53 % | 86 / 96 % | – | 30 / 53 % | 14 / 25 % | 22 / 38 % | 7 / 16 % | 17 / 37 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 54 % | 77 / 99 % | – | 60 / 80 % | 39 / 60 % | 48 / 67 % | 16 / 43 % | 25 / 45 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 39 / 57 % | 72 / 99 % | – | 50 / 75 % | 42 / 61 % | 53 / 72 % | 32 / 65 % | 15 / 38 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 21 / 43 % | 68 / 94 % | – | 35 / 60 % | 30 / 48 % | 35 / 54 % | 14 / 27 % | 21 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 30 / 50 % | 58 / 96 % | – | 31 / 57 % | 9 / 20 % | 26 / 44 % | 6 / 16 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 35 % | 51 / 78 % | – | 11 / 26 % | 3 / 8 % | 14 / 25 % | 1 / 4 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 17 / 37 % | 49 / 81 % | – | 26 / 48 % | 6 / 10 % | 20 / 34 % | 2 / 9 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 27 / 46 % | 26 / 97 % | – | 39 / 64 % | 27 / 44 % | 45 / 62 % | 8 / 20 % | 14 / 38 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 43 / 79 % | – | 9 / 23 % | 0 / 0 % | 8 / 17 % | 1 / 4 % | 13 / 35 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 41 / 66 % | – | 0 / 0 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 6 / 20 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 40 / 79 % | – | 28 / 56 % | 6 / 14 % | 28 / 44 % | 2 / 9 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 17 / 37 % | 0 / 0 % | – | 38 / 61 % | 8 / 17 % | 17 / 33 % | 4 / 13 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 14 / 33 % | 35 / 94 % | – | 12 / 33 % | 4 / 10 % | 12 / 27 % | 2 / 7 % | 15 / 45 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 26 / 62 % | – | 12 / 35 % | 1 / 2 % | 0 / 0 % | 1 / 3 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 25 / 51 % | – | 6 / 14 % | 3 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 24 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 15 / 72 % | – | 23 / 47 % | 6 / 15 % | 6 / 14 % | 8 / 20 % | 11 / 28 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 20 / 44 % | 0 / 0 % | – | 22 / 48 % | 7 / 16 % | 9 / 19 % | 1 / 6 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 21 / 92 % | – | 5 / 12 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 17 / 30 % | 0 / 0 % | – | 16 / 39 % | 3 / 7 % | 12 / 24 % | 2 / 9 % | 14 / 35 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 17 / 51 % | – | 10 / 26 % | 1 / 3 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | 12 / 29 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | – | 9 / 26 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 6 / 24 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 4 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 5 / 40 % | – | 7 / 16 % | 1 / 3 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 7 / 14 % | 0 / 1 % | 4 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 7 / 15 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 1 / 4 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 1 / 3 % | 3 / 5 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
