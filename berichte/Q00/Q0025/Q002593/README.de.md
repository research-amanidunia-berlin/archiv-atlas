[English](README.md) · [Deutsch](README.de.md)

# Investigating unintended model actions in our evaluations and internal use

Bericht Q002593 · Quelle anthropic.com · Datum 2026-10-09 · [Original öffnen](https://www.anthropic.com/research/investigating-unintended-model-actions)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 43 / 66 % | 99 / 100 % | – | 100 / 100 % | 68 / 85 % | 85 / 92 % | 74 / 88 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 57 / 74 % | 99 / 100 % | – | 100 / 100 % | 81 / 90 % | 75 / 86 % | 68 / 83 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 55 / 71 % | 100 / 100 % | – | 100 / 100 % | 86 / 92 % | 85 / 92 % | 73 / 88 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 61 / 78 % | 100 / 100 % | – | 100 / 100 % | 87 / 93 % | 86 / 91 % | 75 / 88 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 35 / 54 % | 98 / 99 % | – | 99 / 100 % | 63 / 80 % | 74 / 84 % | 43 / 65 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 40 / 60 % | 91 / 98 % | – | 97 / 99 % | 82 / 90 % | 87 / 92 % | 61 / 79 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 29 / 47 % | 42 / 78 % | – | 94 / 98 % | 57 / 79 % | 41 / 61 % | 9 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 35 / 48 % | 48 / 79 % | – | 88 / 94 % | 60 / 81 % | 60 / 78 % | 41 / 63 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 28 / 48 % | 82 / 93 % | – | 85 / 93 % | 61 / 81 % | 62 / 78 % | 30 / 56 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 39 / 53 % | 75 / 92 % | – | 82 / 89 % | 69 / 83 % | 59 / 72 % | 41 / 61 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 30 / 58 % | 66 / 93 % | – | 81 / 96 % | 19 / 43 % | 56 / 76 % | 20 / 44 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 28 / 51 % | 44 / 73 % | – | 65 / 80 % | 61 / 79 % | 81 / 88 % | 53 / 72 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 27 / 48 % | 0 / 0 % | – | 68 / 78 % | 27 / 56 % | 31 / 50 % | 7 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 45 / 81 % | – | 68 / 85 % | 12 / 36 % | 6 / 11 % | 4 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 65 / 93 % | – | 48 / 80 % | 42 / 69 % | 25 / 48 % | 14 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 59 / 76 % | 0 / 0 % | 2 / 6 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 54 / 88 % | – | 36 / 64 % | 13 / 34 % | 9 / 19 % | 2 / 7 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 26 % | 51 / 83 % | – | 22 / 51 % | 8 / 24 % | 7 / 14 % | 4 / 12 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 4 / 48 % | – | 48 / 72 % | 25 / 51 % | 6 / 13 % | 5 / 13 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 44 / 77 % | 7 / 23 % | 6 / 12 % | 3 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 42 / 86 % | – | 43 / 76 % | 8 / 21 % | 13 / 23 % | 3 / 10 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 27 / 97 % | – | 0 / 0 % | 13 / 41 % | 19 / 38 % | 7 / 19 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 17 / 83 % | – | 26 / 60 % | 26 / 54 % | 0 / 0 % | 11 / 31 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 10 / 67 % | – | 22 / 47 % | 20 / 44 % | 12 / 23 % | 9 / 22 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 39 % | 8 / 56 % | – | 0 / 0 % | 20 / 45 % | 11 / 23 % | 10 / 25 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 18 / 39 % | 6 / 18 % | 7 / 12 % | 2 / 7 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 18 / 78 % | – | 4 / 20 % | 11 / 29 % | 8 / 15 % | 2 / 6 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 16 / 82 % | – | 0 / 0 % | 8 / 21 % | 6 / 12 % | 6 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 14 / 94 % | – | 2 / 17 % | 13 / 33 % | 8 / 17 % | 3 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 9 / 28 % | 0 / 0 % | – | 0 / 0 % | 10 / 27 % | 12 / 24 % | 2 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 12 / 60 % | – | 10 / 30 % | 8 / 20 % | 11 / 20 % | 7 / 18 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 30 % | 0 / 0 % | 5 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | 10 / 27 % | 0 / 0 % | 3 / 8 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 9 / 73 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 2 / 8 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 7 / 12 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 6 / 13 % | 1 / 5 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 0 / 0 % | 3 / 7 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 3 / 5 % | 6 / 11 % |
