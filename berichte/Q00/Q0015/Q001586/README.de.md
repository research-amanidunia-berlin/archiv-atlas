[English](README.md) · [Deutsch](README.de.md)

# 2017: DeepMind's year in review

Bericht Q001586 · Quelle deepmind.google · Datum 2017-12-21 · [Original öffnen](https://deepmind.google/blog/2017-deepminds-year-in-review/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

DeepMind berichtet für 2017 von Fortschritten bei KI-Forschung, Sprachsynthese, AlphaGo Zero und Anwendungen im Gesundheitswesen. Zugleich beschreibt das Unternehmen neue Arbeit zu Sicherheit, Erklärbarkeit und gesellschaftlicher Aufsicht, räumt aber ein, dass noch ein weiter Weg vor ihm liege; die Fortschrittsangaben stammen aus dem Unternehmensrückblick.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 51 % | 79 / 98 % | 17 / 33 % | 96 / 99 % | 34 / 66 % | 48 / 74 % | 28 / 56 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 27 / 50 % | 70 / 94 % | 27 / 52 % | 93 / 98 % | 42 / 67 % | 28 / 53 % | 20 / 44 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 23 / 41 % | 84 / 94 % | 30 / 57 % | 91 / 98 % | 39 / 66 % | 45 / 72 % | 26 / 53 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 18 / 43 % | 34 / 78 % | 3 / 12 % | 90 / 95 % | 18 / 46 % | 22 / 53 % | 8 / 28 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 27 / 48 % | 67 / 95 % | 15 / 39 % | 90 / 97 % | 38 / 66 % | 40 / 69 % | 17 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 33 % | 74 / 91 % | 1 / 6 % | 85 / 93 % | 13 / 36 % | 9 / 24 % | 1 / 12 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 41 / 82 % | 1 / 8 % | 84 / 94 % | 11 / 33 % | 11 / 29 % | 1 / 10 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 46 / 90 % | 4 / 14 % | 83 / 93 % | 16 / 37 % | 22 / 49 % | 13 / 34 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 71 / 97 % | 3 / 11 % | 75 / 88 % | 16 / 41 % | 10 / 30 % | 6 / 24 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 72 / 92 % | 3 / 11 % | 10 / 31 % | 13 / 32 % | 10 / 24 % | 6 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 37 / 75 % | 2 / 6 % | 64 / 84 % | 19 / 40 % | 15 / 30 % | 6 / 17 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 16 / 44 % | 44 / 94 % | 2 / 9 % | 58 / 85 % | 12 / 41 % | 9 / 36 % | 2 / 17 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 7 / 52 % | 3 / 12 % | 54 / 85 % | 14 / 38 % | 8 / 26 % | 8 / 29 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 36 / 54 % | 52 / 84 % | 15 / 24 % | 42 / 61 % | 30 / 59 % | 25 / 46 % | 18 / 38 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 12 / 33 % | 1 / 3 % | 52 / 69 % | 17 / 45 % | 7 / 23 % | 3 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 52 / 86 % | 1 / 2 % | 27 / 39 % | 17 / 37 % | 6 / 16 % | 2 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 50 / 69 % | 0 / 0 % | 0 / 0 % | 17 / 39 % | 0 / 0 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 48 / 86 % | 3 / 12 % | 32 / 63 % | 18 / 42 % | 11 / 28 % | 5 / 19 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 34 % | 47 / 88 % | 2 / 6 % | 9 / 41 % | 12 / 35 % | 10 / 29 % | 8 / 25 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 29 / 61 % | 4 / 11 % | 41 / 60 % | 15 / 42 % | 32 / 52 % | 16 / 40 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 2 / 8 % | 36 / 57 % | 14 / 40 % | 7 / 16 % | 3 / 14 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 34 / 46 % | 9 / 25 % | 10 / 23 % | 1 / 11 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 32 / 69 % | 0 / 1 % | 21 / 42 % | 9 / 22 % | 5 / 13 % | 1 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 28 / 77 % | 0 / 3 % | 10 / 45 % | 10 / 30 % | 6 / 14 % | 2 / 16 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 22 / 41 % | 3 / 7 % | 22 / 36 % | 18 / 39 % | 25 / 43 % | 5 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 6 / 52 % | 0 / 2 % | 21 / 52 % | 8 / 20 % | 5 / 13 % | 4 / 16 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 15 / 58 % | 1 / 4 % | 10 / 31 % | 19 / 38 % | 7 / 18 % | 4 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 10 / 30 % | 8 / 18 % | 5 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 2 / 34 % | 0 / 2 % | 10 / 33 % | 8 / 19 % | 8 / 20 % | 3 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 10 / 25 % | 7 / 19 % | 4 / 15 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 6 / 15 % | 6 / 14 % | 2 / 7 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 55 % | 1 / 4 % | 0 / 0 % | 9 / 19 % | 9 / 25 % | 2 / 11 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 7 / 17 % | 1 / 6 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 4 / 10 % | 1 / 6 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 1 / 6 % | 7 / 16 % | 4 / 10 % | 1 / 6 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 1 / 46 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 5 / 10 % | 1 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 56 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 5 / 12 % | 1 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 5 / 8 % | 2 / 7 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 0 / 0 % | 1 / 2 % | 0 / 0 % | 5 / 13 % | 5 / 10 % | 2 / 9 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 44 % | 0 / 2 % | 2 / 13 % | 5 / 14 % | 4 / 13 % | 1 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 4 % |
