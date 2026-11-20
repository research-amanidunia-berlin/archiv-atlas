[English](README.md) · [Deutsch](README.de.md)

# Looking ahead to the AI Seoul Summit

Bericht Q002886 · Quelle deepmind.google · Datum 2024-05-20 · [Original öffnen](https://deepmind.google/blog/looking-ahead-to-the-ai-seoul-summit/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google DeepMind schlägt vor, die AI Seoul Summit-Reihe als Forum für gemeinsame wissenschaftliche Grundlagen, standardisierte KI-Prüfungen und abgestimmte Regeln zur Sicherheit fortgeschrittener KI zu nutzen. Der Beitrag benennt Unsicherheit über künftige Risiken und den frühen Stand der Prüfwissenschaft; er formuliert die Position des Unternehmens, nicht einen Nachweis, dass die vorgeschlagenen Maßnahmen bereits wirken.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 40 / 64 % | 98 / 100 % | 72 / 79 % | 94 / 97 % | 64 / 81 % | 63 / 81 % | 76 / 87 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 35 / 68 % | 65 / 92 % | 82 / 95 % | 97 / 100 % | 74 / 88 % | 58 / 83 % | 67 / 85 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 22 / 55 % | 69 / 90 % | 77 / 93 % | 83 / 99 % | 17 / 43 % | 52 / 79 % | 68 / 85 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 19 / 52 % | 80 / 99 % | 28 / 67 % | 78 / 98 % | 28 / 64 % | 20 / 57 % | 47 / 77 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 13 / 27 % | 51 / 92 % | 1 / 6 % | 78 / 95 % | 9 / 26 % | 2 / 8 % | 6 / 17 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 24 / 52 % | 74 / 98 % | 20 / 56 % | 73 / 96 % | 44 / 73 % | 20 / 53 % | 40 / 71 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 12 / 38 % | 67 / 97 % | 4 / 20 % | 53 / 86 % | 15 / 41 % | 9 / 25 % | 23 / 48 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 31 / 65 % | 67 / 94 % | 22 / 58 % | 57 / 90 % | 35 / 63 % | 23 / 54 % | 35 / 64 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 14 / 41 % | 64 / 92 % | 9 / 25 % | 32 / 72 % | 29 / 57 % | 10 / 30 % | 20 / 46 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 53 % | 61 / 92 % | 16 / 50 % | 50 / 90 % | 27 / 58 % | 10 / 41 % | 20 / 48 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 15 / 42 % | 57 / 97 % | 11 / 48 % | 24 / 87 % | 35 / 65 % | 14 / 44 % | 33 / 60 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 15 / 38 % | 47 / 95 % | 7 / 28 % | 17 / 62 % | 34 / 64 % | 11 / 40 % | 10 / 39 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 9 / 35 % | 47 / 87 % | 1 / 12 % | 30 / 72 % | 10 / 28 % | 4 / 23 % | 7 / 32 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 46 % | 37 / 81 % | 2 / 11 % | 42 / 72 % | 13 / 39 % | 5 / 23 % | 12 / 35 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 30 % | 40 / 77 % | 3 / 15 % | 10 / 54 % | 14 / 37 % | 7 / 24 % | 7 / 26 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 43 % | 39 / 94 % | 4 / 24 % | 20 / 81 % | 21 / 55 % | 8 / 30 % | 15 / 51 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 30 % | 39 / 94 % | 1 / 8 % | 22 / 53 % | 10 / 28 % | 5 / 21 % | 7 / 23 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 14 / 44 % | 37 / 94 % | 2 / 13 % | 29 / 67 % | 14 / 44 % | 2 / 20 % | 8 / 39 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 20 / 52 % | 0 / 3 % | 34 / 66 % | 7 / 26 % | 1 / 7 % | 6 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 33 % | 31 / 86 % | 1 / 7 % | 6 / 36 % | 7 / 23 % | 3 / 16 % | 5 / 17 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 41 % | 28 / 91 % | 6 / 24 % | 11 / 49 % | 12 / 39 % | 8 / 27 % | 13 / 34 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 15 / 47 % | 27 / 76 % | 4 / 19 % | 28 / 67 % | 28 / 61 % | 10 / 39 % | 21 / 56 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 14 / 37 % | 26 / 71 % | 3 / 17 % | 7 / 35 % | 14 / 46 % | 8 / 31 % | 13 / 49 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 26 / 78 % | 1 / 7 % | 3 / 37 % | 6 / 19 % | 2 / 11 % | 6 / 17 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 25 / 90 % | 0 / 4 % | 6 / 44 % | 6 / 16 % | 1 / 6 % | 5 / 9 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 10 / 38 % | 22 / 94 % | 1 / 8 % | 11 / 51 % | 10 / 28 % | 2 / 12 % | 7 / 19 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 13 / 77 % | 0 / 3 % | 5 / 38 % | 7 / 19 % | 0 / 4 % | 4 / 14 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 40 % | 12 / 95 % | 1 / 8 % | 3 / 40 % | 11 / 34 % | 4 / 21 % | 11 / 30 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 11 / 45 % | 0 / 3 % | 11 / 37 % | 5 / 13 % | 0 / 0 % | 5 / 17 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 29 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 10 / 68 % | 0 / 4 % | 0 / 0 % | 5 / 14 % | 1 / 11 % | 6 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 7 / 73 % | 2 / 11 % | 0 / 0 % | 8 / 22 % | 1 / 10 % | 8 / 21 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 7 / 41 % | 0 / 2 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 83 % | 0 / 3 % | 1 / 26 % | 6 / 16 % | 0 / 0 % | 6 / 15 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 5 / 10 % | 1 / 2 % | 5 / 9 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 1 / 21 % | 0 / 2 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 5 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 5 / 12 % | 1 / 6 % | 4 / 9 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 4 / 57 % | 0 / 1 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 4 / 9 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 3 / 78 % | 0 / 2 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 9 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 4 / 53 % | 0 / 3 % | 0 / 7 % | 5 / 12 % | 1 / 6 % | 3 / 7 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 4 / 10 % |
