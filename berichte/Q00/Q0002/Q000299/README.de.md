[English](README.md) · [Deutsch](README.de.md)

# The Hinton Lectures: Paul Christiano

Bericht Q000299 · Quelle medium.com · Datum 2026-11-10 · [Original öffnen](https://medium.com/@ZombieCodeKill/the-hinton-lectures-paul-christiano-6ef705939433)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt Christiano zugeschriebene Warnungen vor KI-Kontrollverlust, schnellen Fähigkeitszuwächsen und erschwerter Abschaltung dar und nennt technische sowie politische Gegenmaßnahmen. Die Zusammenfassung des dritten Vortrags ist unvollständig und bricht im Abschnitt zum Bedarf an mehr Zeit mitten im Satz ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 50 / 74 % | 80 / 97 % | 78 / 93 % | 99 / 100 % | 75 / 89 % | 73 / 87 % | 52 / 76 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 63 % | 94 / 99 % | 54 / 85 % | 97 / 99 % | 68 / 86 % | 69 / 86 % | 64 / 84 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 22 / 52 % | 56 / 98 % | 13 / 50 % | 95 / 99 % | 41 / 67 % | 26 / 56 % | 19 / 53 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 17 / 41 % | 94 / 100 % | 6 / 36 % | 82 / 94 % | 20 / 49 % | 19 / 51 % | 16 / 51 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 23 / 48 % | 74 / 99 % | 7 / 25 % | 88 / 96 % | 47 / 75 % | 59 / 78 % | 37 / 67 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 39 / 62 % | 58 / 89 % | 48 / 77 % | 85 / 95 % | 61 / 82 % | 56 / 78 % | 53 / 79 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 30 / 56 % | 76 / 98 % | 31 / 65 % | 84 / 96 % | 60 / 81 % | 46 / 70 % | 36 / 64 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 23 / 49 % | 73 / 94 % | 14 / 36 % | 83 / 92 % | 48 / 70 % | 60 / 74 % | 49 / 68 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 8 / 37 % | 31 / 82 % | 3 / 16 % | 79 / 90 % | 26 / 53 % | 21 / 46 % | 14 / 40 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 22 / 50 % | 77 / 97 % | 15 / 47 % | 68 / 80 % | 51 / 75 % | 37 / 64 % | 19 / 49 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 14 / 44 % | 44 / 84 % | 14 / 42 % | 70 / 86 % | 28 / 57 % | 47 / 73 % | 25 / 55 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 25 / 53 % | 38 / 90 % | 13 / 48 % | 58 / 78 % | 57 / 80 % | 64 / 82 % | 34 / 68 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 15 / 45 % | 59 / 97 % | 16 / 56 % | 53 / 85 % | 44 / 74 % | 48 / 78 % | 40 / 68 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 20 / 46 % | 59 / 73 % | 8 / 34 % | 44 / 60 % | 21 / 48 % | 22 / 48 % | 13 / 40 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 19 / 48 % | 57 / 91 % | 12 / 50 % | 45 / 74 % | 26 / 62 % | 29 / 65 % | 23 / 55 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 20 / 36 % | 19 / 81 % | 5 / 26 % | 55 / 73 % | 30 / 60 % | 19 / 44 % | 8 / 25 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 32 % | 48 / 97 % | 1 / 10 % | 30 / 59 % | 13 / 37 % | 12 / 38 % | 9 / 34 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 31 / 59 % | 44 / 90 % | 7 / 29 % | 28 / 56 % | 26 / 53 % | 19 / 46 % | 16 / 48 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 14 / 35 % | 42 / 88 % | 6 / 28 % | 11 / 37 % | 29 / 58 % | 30 / 52 % | 13 / 39 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 52 % | 38 / 88 % | 9 / 43 % | 33 / 67 % | 23 / 57 % | 31 / 63 % | 16 / 44 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 14 / 34 % | 34 / 80 % | 1 / 11 % | 25 / 53 % | 15 / 42 % | 15 / 35 % | 6 / 19 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 53 % | 33 / 70 % | 7 / 30 % | 18 / 50 % | 26 / 57 % | 24 / 57 % | 23 / 63 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 11 / 42 % | 32 / 94 % | 1 / 8 % | 19 / 58 % | 13 / 32 % | 13 / 23 % | 3 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 29 / 74 % | 1 / 4 % | 9 / 36 % | 8 / 26 % | 11 / 22 % | 4 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 21 / 48 % | 13 / 55 % | 4 / 11 % | 10 / 37 % | 26 / 51 % | 28 / 44 % | 16 / 34 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 28 / 64 % | 2 / 9 % | 1 / 17 % | 10 / 25 % | 7 / 16 % | 6 / 18 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 9 / 87 % | 3 / 19 % | 22 / 52 % | 27 / 57 % | 16 / 45 % | 19 / 53 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 14 / 34 % | 20 / 92 % | 5 / 30 % | 21 / 61 % | 27 / 56 % | 11 / 34 % | 9 / 31 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 32 % | 25 / 70 % | 0 / 4 % | 1 / 8 % | 9 / 26 % | 13 / 29 % | 7 / 21 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 34 % | 23 / 81 % | 2 / 14 % | 8 / 24 % | 12 / 34 % | 14 / 33 % | 9 / 25 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 16 / 77 % | 2 / 12 % | 23 / 54 % | 19 / 49 % | 20 / 40 % | 2 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 13 / 29 % | 6 / 95 % | 2 / 12 % | 3 / 37 % | 15 / 41 % | 16 / 31 % | 6 / 19 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 11 / 26 % | 16 / 56 % | 2 / 14 % | 0 / 0 % | 14 / 42 % | 12 / 38 % | 10 / 34 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 34 % | 8 / 14 % | 3 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 6 / 31 % | 0 / 4 % | 0 / 0 % | 7 / 18 % | 12 / 25 % | 2 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 12 / 58 % | 1 / 6 % | 0 / 4 % | 7 / 20 % | 9 / 22 % | 2 / 8 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 7 / 44 % | 0 / 3 % | 1 / 13 % | 9 / 23 % | 11 / 22 % | 6 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 34 % | 6 / 49 % | 1 / 7 % | 2 / 12 % | 10 / 30 % | 11 / 23 % | 6 / 17 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 39 % | 0 / 2 % | 6 / 16 % | 7 / 15 % | 9 / 18 % | 1 / 4 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 4 / 71 % | 0 / 2 % | 0 / 0 % | 7 / 19 % | 8 / 13 % | 1 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 7 / 48 % | 0 / 2 % | 0 / 0 % | 7 / 22 % | 8 / 16 % | 3 / 10 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 13 % | 0 / 1 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 7 / 62 % | 0 / 3 % | 0 / 4 % | 7 / 17 % | 7 / 13 % | 1 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 5 / 9 % | 3 / 7 % |
