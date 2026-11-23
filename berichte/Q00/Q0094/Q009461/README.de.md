[English](README.md) · [Deutsch](README.de.md)

# gpt-oss-120b & gpt-oss-20b Model Card

Bericht Q009461 · Quelle arxiv.org · Datum – · [Original öffnen](https://arxiv.org/pdf/2508.10925)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt zwei offene Modelle, die bei mehreren Mathematik-, Programmier- und Werkzeugtests starke Ergebnisse erzielen, aber bei Faktenfragen ohne Webzugriff häufiger halluzinieren und Anweisungsrangfolgen weniger zuverlässig schützen als o4-mini. Laut den berichteten Tests erreichten weder die Standardmodelle noch adversarial angepasste Varianten die internen Schwellen für hohe Fähigkeiten in Biologie/Chemie, Cybersecurity oder KI-Selbstverbesserung; die Aussage ist auf die geprüften Bedingungen begrenzt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 27 / 53 % | 100 / 100 % | – | 59 / 83 % | 23 / 46 % | 57 / 76 % | 30 / 55 % | 23 / 41 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 64 / 78 % | 97 / 98 % | – | 86 / 93 % | 58 / 74 % | 83 / 90 % | 80 / 91 % | 53 / 73 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 62 / 77 % | 96 / 97 % | – | 91 / 95 % | 35 / 55 % | 79 / 88 % | 73 / 84 % | 54 / 72 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 32 / 53 % | 96 / 99 % | – | 71 / 85 % | 10 / 26 % | 52 / 69 % | 35 / 57 % | 25 / 53 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 48 / 65 % | 95 / 96 % | – | 81 / 90 % | 70 / 84 % | 89 / 94 % | 84 / 91 % | 28 / 48 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 65 / 79 % | 93 / 97 % | – | 87 / 94 % | 54 / 73 % | 83 / 89 % | 94 / 97 % | 76 / 89 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 30 / 52 % | 92 / 97 % | – | 56 / 77 % | 21 / 38 % | 37 / 59 % | 11 / 22 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 39 / 58 % | 89 / 97 % | – | 77 / 88 % | 33 / 55 % | 61 / 77 % | 31 / 54 % | 32 / 51 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 44 / 62 % | 87 / 97 % | – | 83 / 91 % | 33 / 58 % | 75 / 86 % | 65 / 83 % | 31 / 50 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 26 / 42 % | 86 / 99 % | – | 27 / 53 % | 8 / 18 % | 16 / 30 % | 6 / 14 % | 14 / 29 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 34 / 54 % | 78 / 98 % | – | 78 / 89 % | 42 / 66 % | 83 / 90 % | 33 / 56 % | 18 / 37 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 40 / 62 % | 76 / 92 % | – | 79 / 89 % | 38 / 58 % | 81 / 89 % | 51 / 67 % | 21 / 41 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 46 / 65 % | 80 / 96 % | – | 79 / 89 % | 31 / 53 % | 71 / 84 % | 30 / 50 % | 37 / 60 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 50 / 84 % | – | 77 / 89 % | 23 / 43 % | 21 / 42 % | 26 / 44 % | 18 / 39 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 43 / 63 % | 44 / 79 % | – | 76 / 88 % | 18 / 40 % | 55 / 71 % | 24 / 49 % | 20 / 42 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 38 / 55 % | 73 / 97 % | – | 44 / 70 % | 23 / 39 % | 35 / 53 % | 35 / 48 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 64 / 80 % | – | 15 / 34 % | 5 / 14 % | 9 / 17 % | 1 / 5 % | 19 / 38 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 25 / 51 % | 62 / 93 % | – | 46 / 70 % | 6 / 16 % | 29 / 44 % | 8 / 14 % | 20 / 44 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 58 / 89 % | – | 14 / 36 % | 4 / 12 % | 7 / 14 % | 1 / 4 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 56 / 81 % | – | 10 / 27 % | 3 / 10 % | 7 / 17 % | 1 / 4 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 21 / 51 % | 0 / 0 % | – | 45 / 69 % | 12 / 28 % | 14 / 25 % | 11 / 20 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 45 / 90 % | – | 10 / 27 % | 1 / 7 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 13 / 35 % | 42 / 87 % | – | 21 / 44 % | 8 / 22 % | 24 / 42 % | 4 / 12 % | 6 / 18 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 41 / 92 % | – | 10 / 30 % | 3 / 11 % | 7 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 25 / 59 % | 0 / 0 % | – | 16 / 41 % | 6 / 17 % | 30 / 54 % | 1 / 4 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 29 / 86 % | – | 11 / 27 % | 4 / 10 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 20 / 76 % | – | 9 / 24 % | 2 / 9 % | 0 / 0 % | 0 / 2 % | 12 / 27 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 16 / 45 % | – | 16 / 33 % | 5 / 11 % | 9 / 16 % | 0 / 0 % | 20 / 44 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 5 / 50 % | – | 7 / 15 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 17 / 36 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 16 / 39 % | 4 / 13 % | 8 / 18 % | 1 / 7 % | 4 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 14 / 31 % | 1 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 10 / 23 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 9 / 23 % | 2 / 8 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | – | 9 / 20 % | 2 / 6 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 9 / 16 % | 1 / 5 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | – | 8 / 18 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 6 / 18 % | 1 / 5 % | 7 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | 2 / 7 % | 4 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 2 / 11 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
