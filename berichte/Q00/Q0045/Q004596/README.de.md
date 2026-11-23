[English](README.md) · [Deutsch](README.de.md)

# China-Based Artificial Intelligence Companies Conducting Industrial-Scale Distillation Campaigns Against U.S. AI Companies

Bericht Q004596 · Quelle cisa.gov · Datum 2026-09-08 · [Original öffnen](https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-251a)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

NSA, CISA und FBI behaupten, mehrere in China ansässige KI-Unternehmen hätten seit mindestens Ende 2024 in großem Umfang Antworten US-amerikanischer Modelle gesammelt, um Fähigkeiten wie Schlussfolgern, Programmieren und Agentenfunktionen zu übernehmen. Sie beschreiben dafür verteilte Zugangswege und empfehlen Überwachung, gezielte Antwortänderungen bei bestätigtem Verdacht sowie den Austausch von Indikatoren zwischen Anbietern. Die Zuschreibungen bleiben Einschätzungen des Hinweises; eine unabhängige Prüfung wird im Text nicht ausgeführt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 47 % | 79 / 93 % | 100 / 100 % | 44 / 67 % | 15 / 31 % | 40 / 60 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 71 / 83 % | 83 / 95 % | 96 / 98 % | 92 / 95 % | 89 / 93 % | 92 / 94 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 81 / 93 % | 95 / 97 % | 53 / 74 % | 9 / 21 % | 45 / 66 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 92 / 99 % | 84 / 91 % | 53 / 74 % | 23 / 42 % | 45 / 65 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 89 / 97 % | 79 / 85 % | 45 / 66 % | 10 / 26 % | 30 / 46 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 71 / 92 % | 86 / 94 % | 43 / 69 % | 13 / 32 % | 62 / 75 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 50 / 66 % | 75 / 92 % | 86 / 92 % | 68 / 81 % | 51 / 62 % | 73 / 82 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 43 / 85 % | 85 / 93 % | 40 / 64 % | 9 / 22 % | 32 / 53 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 51 / 86 % | 75 / 95 % | 17 / 44 % | 5 / 17 % | 13 / 40 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 59 / 84 % | 74 / 83 % | 43 / 63 % | 12 / 26 % | 30 / 47 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 74 / 95 % | 73 / 85 % | 17 / 42 % | 8 / 21 % | 14 / 37 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 69 / 95 % | 32 / 48 % | 19 / 45 % | 5 / 16 % | 26 / 50 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 56 / 94 % | 0 / 0 % | 14 / 41 % | 11 / 26 % | 19 / 43 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 56 / 84 % | 9 / 17 % | 30 / 52 % | 22 / 37 % | 47 / 63 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 33 / 53 % | 55 / 83 % | 40 / 73 % | 47 / 69 % | 17 / 35 % | 30 / 50 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 23 / 41 % | 54 / 85 % | 0 / 0 % | 25 / 48 % | 13 / 25 % | 38 / 57 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 51 / 80 % | 40 / 55 % | 9 / 18 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 4 / 37 % | 46 / 71 % | 18 / 45 % | 8 / 20 % | 13 / 37 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 19 / 28 % | 19 / 62 % | 41 / 69 % | 29 / 55 % | 7 / 16 % | 21 / 42 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 17 / 62 % | 19 / 44 % | 21 / 50 % | 9 / 22 % | 35 / 52 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 35 / 78 % | 0 / 0 % | 20 / 46 % | 12 / 27 % | 16 / 29 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 35 / 85 % | 7 / 23 % | 12 / 32 % | 5 / 14 % | 7 / 18 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 10 / 29 % | 25 / 60 % | 4 / 25 % | 9 / 24 % | 8 / 22 % | 12 / 33 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 25 / 75 % | 0 / 0 % | 13 / 33 % | 3 / 10 % | 10 / 35 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 6 / 37 % | 0 / 0 % | 12 / 38 % | 6 / 17 % | 24 / 49 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 24 / 70 % | 0 / 0 % | 13 / 39 % | 5 / 12 % | 9 / 19 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 22 / 65 % | 14 / 46 % | 15 / 40 % | 6 / 17 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 21 / 61 % | 18 / 35 % | 16 / 33 % | 0 / 0 % | 12 / 23 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 43 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 45 % | 0 / 0 % | 7 / 17 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 37 % | 0 / 0 % | 11 / 24 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 16 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 7 / 20 % | 15 / 33 % | 6 / 15 % | 11 / 25 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 34 % | 0 / 0 % | 14 / 30 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 0 / 0 % | 12 / 26 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 35 % | 2 / 14 % | 8 / 22 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 6 / 41 % | 0 / 0 % | 11 / 32 % | 0 / 0 % | 3 / 9 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 11 / 31 % | 9 / 26 % | 0 / 0 % | 5 / 13 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 1 / 24 % | 0 / 0 % | 10 / 23 % | 0 / 0 % | 6 / 14 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
