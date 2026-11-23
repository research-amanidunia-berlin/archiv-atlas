[English](README.md) · [Deutsch](README.de.md)

# BigCode: toward open AI governance processes in LLMs for coding

Bericht Q006044 · Quelle oecd.ai · Datum 2023-08-08 · [Original öffnen](https://oecd.ai/en/wonk/bigcode)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht schildert BigCodes offene Governance für Code-Sprachmodelle: Dazu gehören ein Datensatz mit Opt-out- und Wartungsverfahren, ein Werkzeug zur Prüfung möglicher Trainingsdaten-Übereinstimmungen sowie Datenschutzmaßnahmen und eine Lizenz mit Nutzungsauflagen. Er nennt außerdem Kennzahlen zur PII-Erkennung und zu Trainingsemissionen; diese beruhen auf den im Bericht beschriebenen Methoden und Annahmen. Eine Governance Card soll die Entscheidungen dokumentieren und anderen Projekten als Orientierung dienen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 74 / 85 % | 100 / 100 % | 100 / 100 % | 90 / 94 % | 88 / 93 % | 88 / 93 % | 94 / 97 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 61 / 79 % | 100 / 100 % | 96 / 99 % | 77 / 87 % | 65 / 80 % | 78 / 88 % | 74 / 88 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 42 / 64 % | 99 / 100 % | 100 / 100 % | 61 / 78 % | 44 / 67 % | 48 / 70 % | 35 / 64 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 35 / 56 % | 91 / 99 % | 99 / 100 % | 51 / 74 % | 30 / 55 % | 50 / 72 % | 27 / 58 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 38 / 58 % | 94 / 98 % | 99 / 100 % | 48 / 69 % | 53 / 76 % | 38 / 63 % | 19 / 46 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 69 / 94 % | 94 / 96 % | 7 / 22 % | 4 / 13 % | 7 / 15 % | 1 / 4 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 45 / 66 % | 87 / 96 % | 91 / 96 % | 54 / 73 % | 36 / 60 % | 26 / 49 % | 16 / 45 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 18 / 41 % | 28 / 97 % | 87 / 96 % | 23 / 48 % | 13 / 37 % | 15 / 38 % | 4 / 20 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 32 / 53 % | 85 / 99 % | 72 / 85 % | 19 / 51 % | 41 / 65 % | 39 / 66 % | 7 / 28 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 31 / 55 % | 85 / 99 % | 79 / 88 % | 31 / 57 % | 41 / 64 % | 32 / 56 % | 16 / 44 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 35 / 57 % | 82 / 97 % | 44 / 65 % | 41 / 64 % | 10 / 24 % | 42 / 57 % | 12 / 23 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 75 / 97 % | 55 / 69 % | 31 / 56 % | 37 / 55 % | 36 / 52 % | 20 / 31 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 73 / 93 % | 0 / 0 % | 40 / 64 % | 11 / 24 % | 15 / 27 % | 5 / 10 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 33 / 76 % | 62 / 81 % | 7 / 18 % | 1 / 7 % | 2 / 6 % | 0 / 3 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 60 / 98 % | 29 / 62 % | 10 / 25 % | 3 / 14 % | 5 / 13 % | 0 / 2 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 10 / 77 % | 56 / 73 % | 22 / 41 % | 26 / 46 % | 40 / 55 % | 9 / 18 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 33 / 93 % | 53 / 79 % | 12 / 32 % | 6 / 17 % | 6 / 16 % | 2 / 6 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 34 / 71 % | 50 / 76 % | 6 / 13 % | 2 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 23 % | 45 / 92 % | 31 / 59 % | 7 / 17 % | 1 / 8 % | 7 / 15 % | 0 / 2 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 6 / 46 % | 13 / 40 % | 45 / 66 % | 7 / 20 % | 8 / 18 % | 1 / 4 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 45 / 77 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 27 / 81 % | 10 / 31 % | 38 / 59 % | 26 / 48 % | 44 / 62 % | 26 / 40 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 42 / 94 % | 7 / 26 % | 11 / 29 % | 7 / 19 % | 8 / 18 % | 3 / 10 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 16 / 45 % | 40 / 64 % | 11 / 27 % | 2 / 8 % | 7 / 16 % | 1 / 3 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 28 / 64 % | 36 / 64 % | 9 / 21 % | 3 / 9 % | 5 / 12 % | 0 / 2 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 34 / 72 % | 9 / 29 % | 6 / 15 % | 4 / 12 % | 7 / 14 % | 0 / 3 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 34 / 81 % | 0 / 5 % | 7 / 15 % | 5 / 16 % | 6 / 14 % | 1 / 5 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 11 / 33 % | 8 / 60 % | 28 / 50 % | 7 / 20 % | 6 / 17 % | 11 / 23 % | 2 / 6 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 21 / 57 % | 25 / 45 % | 14 / 37 % | 14 / 34 % | 8 / 22 % | 5 / 16 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 24 / 79 % | 0 / 0 % | 7 / 18 % | 6 / 17 % | 7 / 17 % | 1 / 7 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 5 / 17 % | 11 / 24 % | 1 / 4 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 3 / 10 % | 7 / 16 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 6 / 18 % | 7 / 15 % | 1 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 7 / 57 % | 2 / 8 % | 5 / 14 % | 2 / 10 % | 4 / 11 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 3 / 10 % | 6 / 14 % | 1 / 4 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 7 % | 4 / 9 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
