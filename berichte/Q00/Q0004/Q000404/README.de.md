[English](README.md) · [Deutsch](README.de.md)

# Introducing Inkling 2 Small

Bericht Q000404 · Quelle thinkingmachines.ai · Datum 2026-11-05 · [Original öffnen](https://thinkingmachines.ai/news/inkling-2-small/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Thinking Machines Lab präsentiert Inkling 2 Small als bildfähiges Modell, das laut eigenen Benchmarks in mehreren Bereichen stark, in anderen jedoch konkurrenzfähig oder unterlegen ist. Der Bericht beschreibt umfangreiches Training und Sicherheitsmaßnahmen, nennt aber auch Fehlverhalten früherer Trainingsstände, Alignment-Abstände zu geschlossenen Modellen und Schwächen im Chatgebrauch; die Leistungsangaben stammen vom Hersteller.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 55 / 71 % | 99 / 100 % | 100 / 100 % | 81 / 90 % | 65 / 78 % | 83 / 89 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 46 / 65 % | 94 / 97 % | 100 / 100 % | 75 / 87 % | 71 / 84 % | 82 / 91 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 52 / 70 % | 96 / 98 % | 100 / 100 % | 87 / 92 % | 79 / 89 % | 90 / 94 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 57 / 73 % | 100 / 100 % | 100 / 100 % | 86 / 92 % | 68 / 82 % | 80 / 89 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 40 / 57 % | 94 / 96 % | 100 / 100 % | 86 / 92 % | 61 / 77 % | 80 / 87 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 95 / 97 % | 99 / 100 % | 61 / 82 % | 0 / 0 % | 38 / 58 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 49 / 68 % | 95 / 98 % | 99 / 100 % | 78 / 89 % | 47 / 70 % | 77 / 89 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 23 / 44 % | 98 / 100 % | 67 / 83 % | 66 / 81 % | 14 / 33 % | 54 / 70 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 34 / 55 % | 98 / 99 % | 98 / 99 % | 70 / 84 % | 18 / 33 % | 73 / 83 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 44 / 64 % | 97 / 99 % | 93 / 97 % | 72 / 85 % | 28 / 43 % | 63 / 74 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 81 / 95 % | 90 / 93 % | 30 / 54 % | 9 / 17 % | 26 / 47 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 35 / 84 % | 89 / 92 % | 16 / 37 % | 3 / 8 % | 17 / 29 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 30 / 52 % | 67 / 92 % | 88 / 92 % | 80 / 89 % | 50 / 67 % | 84 / 90 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 31 / 60 % | 87 / 99 % | 71 / 84 % | 60 / 80 % | 14 / 25 % | 67 / 77 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 85 / 94 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 4 / 8 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 21 / 42 % | 78 / 90 % | 84 / 90 % | 57 / 78 % | 14 / 26 % | 45 / 59 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 38 / 67 % | 77 / 87 % | 13 / 34 % | 2 / 6 % | 10 / 23 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 75 / 84 % | 46 / 69 % | 10 / 20 % | 13 / 26 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 41 / 60 % | 67 / 81 % | 45 / 68 % | 13 / 25 % | 31 / 51 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 67 / 96 % | 30 / 46 % | 35 / 57 % | 0 / 0 % | 21 / 36 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 62 / 85 % | 43 / 65 % | 8 / 23 % | 1 / 5 % | 7 / 16 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 60 / 91 % | 49 / 62 % | 33 / 55 % | 10 / 21 % | 12 / 25 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 59 / 88 % | 48 / 58 % | 27 / 51 % | 5 / 12 % | 13 / 27 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 20 / 42 % | 44 / 83 % | 52 / 66 % | 26 / 52 % | 11 / 22 % | 29 / 48 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 54 % | 4 / 12 % | 43 / 64 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 21 / 32 % | 35 / 61 % | 5 / 10 % | 17 / 36 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 31 / 50 % | 6 / 17 % | 2 / 5 % | 4 / 9 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 30 / 53 % | 3 / 7 % | 17 / 38 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 19 / 47 % | 0 / 0 % | 0 / 0 % | 30 / 54 % | 7 / 15 % | 11 / 22 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 28 / 46 % | 10 / 28 % | 4 / 9 % | 14 / 27 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 25 / 66 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 6 / 10 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 28 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 3 / 16 % | 10 / 22 % | 3 / 9 % | 2 / 5 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 24 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 3 / 7 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 3 / 6 % | 4 / 9 % | – | – |
