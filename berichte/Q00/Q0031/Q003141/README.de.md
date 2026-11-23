[English](README.md) · [Deutsch](README.de.md)

# Technical Documentation of the National Information Security Standardization Technical Committee: Basic Safety Requirements for Generative Artificial Intelligence Services (Draft for Feedback)

Bericht Q003141 · Quelle cset.georgetown.edu · Datum 2023-11-08 · [Original öffnen](https://cset.georgetown.edu/publication/china-safety-requirements-for-generative-ai/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Bericht ist nur ein Auszug aus einer Zusammenfassung und dem Beginn der Übersetzung eines chinesischen Entwurfs zu Sicherheitsanforderungen für öffentliche generative KI-Dienste. Laut Einleitung umfasst der Entwurf mehr als 30 Risiken und verlangt unter anderem mehr fremdsprachige Trainingsdaten; die vollständigen Anforderungen und Risikolisten sind hier nicht enthalten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 45 / 68 % | 44 / 95 % | 99 / 100 % | 44 / 69 % | 15 / 42 % | 26 / 56 % | 28 / 69 % | 19 / 45 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 58 / 72 % | 92 / 99 % | 89 / 95 % | 65 / 82 % | 39 / 65 % | 64 / 80 % | 63 / 85 % | 43 / 67 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 53 / 72 % | 82 / 95 % | 68 / 87 % | 65 / 82 % | 36 / 60 % | 59 / 75 % | 37 / 70 % | 34 / 62 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 39 / 61 % | 81 / 96 % | 80 / 90 % | 62 / 79 % | 24 / 48 % | 49 / 68 % | 23 / 45 % | 43 / 68 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 34 / 55 % | 72 / 97 % | 0 / 0 % | 41 / 69 % | 28 / 54 % | 51 / 72 % | 15 / 47 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 43 / 62 % | 64 / 89 % | 57 / 82 % | 35 / 65 % | 19 / 46 % | 47 / 70 % | 15 / 40 % | 23 / 46 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 28 / 52 % | 47 / 90 % | 60 / 83 % | 26 / 51 % | 11 / 32 % | 21 / 50 % | 11 / 38 % | 20 / 43 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 20 / 47 % | 58 / 89 % | 17 / 56 % | 18 / 40 % | 6 / 24 % | 11 / 26 % | 3 / 17 % | 11 / 32 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 18 / 41 % | 57 / 91 % | 38 / 79 % | 22 / 50 % | 5 / 20 % | 11 / 25 % | 5 / 17 % | 25 / 57 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 18 / 34 % | 55 / 85 % | 52 / 79 % | 13 / 30 % | 7 / 27 % | 11 / 31 % | 7 / 21 % | 21 / 44 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 24 / 50 % | 51 / 70 % | 26 / 59 % | 7 / 23 % | 22 / 44 % | 6 / 25 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 30 / 53 % | 49 / 95 % | 23 / 46 % | 21 / 44 % | 8 / 27 % | 27 / 53 % | 6 / 20 % | 30 / 58 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 17 / 43 % | 5 / 60 % | 40 / 73 % | 16 / 49 % | 2 / 13 % | 14 / 35 % | 4 / 17 % | 9 / 24 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 16 / 41 % | 39 / 88 % | 5 / 25 % | 12 / 32 % | 5 / 17 % | 13 / 29 % | 3 / 15 % | 10 / 31 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 38 / 84 % | 35 / 64 % | 23 / 48 % | 6 / 20 % | 7 / 20 % | 6 / 19 % | 8 / 27 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 37 / 81 % | 25 / 56 % | 15 / 36 % | 7 / 17 % | 11 / 22 % | 4 / 14 % | 9 / 28 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 23 / 53 % | 27 / 55 % | 0 / 0 % | 31 / 57 % | 12 / 32 % | 13 / 28 % | 12 / 36 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 16 / 30 % | 30 / 68 % | 0 / 0 % | 14 / 36 % | 2 / 8 % | 6 / 17 % | 2 / 9 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 49 % | 8 / 20 % | 0 / 0 % | 0 / 0 % | 29 / 49 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 26 / 65 % | 0 / 0 % | 9 / 22 % | 2 / 11 % | 7 / 17 % | 1 / 8 % | 10 / 29 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 25 / 49 % | 0 / 0 % | 12 / 28 % | 5 / 16 % | 8 / 18 % | 4 / 12 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 23 / 68 % | 9 / 34 % | 12 / 37 % | 2 / 9 % | 7 / 21 % | 1 / 7 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 22 / 64 % | 21 / 38 % | 8 / 18 % | 1 / 8 % | 6 / 12 % | 0 / 3 % | 7 / 22 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 18 / 37 % | 22 / 46 % | 0 / 0 % | 15 / 41 % | 8 / 25 % | 15 / 31 % | 4 / 16 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 21 / 52 % | 0 / 3 % | 10 / 27 % | 4 / 15 % | 8 / 20 % | 2 / 9 % | 3 / 17 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 43 % | 0 / 0 % | 0 / 0 % | 19 / 40 % | 8 / 21 % | 18 / 38 % | 6 / 21 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 20 / 43 % | 8 / 16 % | 1 / 7 % | 0 / 0 % | 0 / 2 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 10 / 47 % | 2 / 13 % | 6 / 17 % | 1 / 9 % | 5 / 14 % | 0 / 5 % | 19 / 41 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 15 / 48 % | 7 / 26 % | 19 / 38 % | 7 / 20 % | 12 / 23 % | 4 / 13 % | 8 / 23 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 17 / 47 % | 0 / 0 % | 9 / 21 % | 1 / 7 % | 5 / 14 % | 1 / 5 % | 12 / 30 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 16 / 70 % | 0 / 9 % | 11 / 26 % | 2 / 10 % | 8 / 16 % | 0 / 3 % | 4 / 20 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 26 % | 2 / 59 % | 0 / 0 % | 11 / 26 % | 4 / 14 % | 6 / 16 % | 1 / 6 % | 10 / 27 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 18 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 2 / 10 % | 7 / 18 % | 1 / 7 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 4 / 13 % | 6 / 14 % | 0 / 4 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 28 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 2 / 8 % | 6 / 13 % | 0 / 4 % | 5 / 19 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 1 / 7 % | 5 / 13 % | 0 / 4 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 3 / 11 % | 8 / 16 % | 1 / 6 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 7 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 7 / 17 % | 2 / 8 % | 6 / 14 % | 1 / 5 % | 4 / 16 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 8 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 1 / 4 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
