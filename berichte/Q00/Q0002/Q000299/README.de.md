[English](README.md) · [Deutsch](README.de.md)

# The Hinton Lectures: Paul Christiano

Bericht Q000299 · Quelle medium.com · Datum 2026-11-10 · [Original öffnen](https://medium.com/@ZombieCodeKill/the-hinton-lectures-paul-christiano-6ef705939433)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt Christiano zugeschriebene Warnungen vor KI-Kontrollverlust, schnellen Fähigkeitszuwächsen und erschwerter Abschaltung dar und nennt technische sowie politische Gegenmaßnahmen. Die Zusammenfassung des dritten Vortrags ist unvollständig und bricht im Abschnitt zum Bedarf an mehr Zeit mitten im Satz ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 50 / 74 % | 80 / 97 % | 99 / 100 % | 75 / 89 % | 52 / 76 % | 73 / 87 % | 78 / 93 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 63 % | 94 / 99 % | 97 / 99 % | 68 / 86 % | 64 / 84 % | 69 / 86 % | 54 / 85 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 22 / 52 % | 56 / 98 % | 95 / 99 % | 41 / 67 % | 19 / 53 % | 26 / 56 % | 13 / 50 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 17 / 41 % | 94 / 100 % | 82 / 94 % | 20 / 49 % | 16 / 51 % | 19 / 51 % | 6 / 36 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 23 / 48 % | 74 / 99 % | 88 / 96 % | 47 / 75 % | 37 / 67 % | 59 / 78 % | 7 / 25 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 39 / 62 % | 58 / 89 % | 85 / 95 % | 61 / 82 % | 53 / 79 % | 56 / 78 % | 48 / 77 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 30 / 56 % | 76 / 98 % | 84 / 96 % | 60 / 81 % | 36 / 64 % | 46 / 70 % | 31 / 65 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 23 / 49 % | 73 / 94 % | 83 / 92 % | 48 / 70 % | 49 / 68 % | 60 / 74 % | 14 / 36 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 8 / 37 % | 31 / 82 % | 79 / 90 % | 26 / 53 % | 14 / 40 % | 21 / 46 % | 3 / 16 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 22 / 50 % | 77 / 97 % | 68 / 80 % | 51 / 75 % | 19 / 49 % | 37 / 64 % | 15 / 47 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 14 / 44 % | 44 / 84 % | 70 / 86 % | 28 / 57 % | 25 / 55 % | 47 / 73 % | 14 / 42 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 25 / 53 % | 38 / 90 % | 58 / 78 % | 57 / 80 % | 34 / 68 % | 64 / 82 % | 13 / 48 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 15 / 45 % | 59 / 97 % | 53 / 85 % | 44 / 74 % | 40 / 68 % | 48 / 78 % | 16 / 56 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 20 / 46 % | 59 / 73 % | 44 / 60 % | 21 / 48 % | 13 / 40 % | 22 / 48 % | 8 / 34 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 19 / 48 % | 57 / 91 % | 45 / 74 % | 26 / 62 % | 23 / 55 % | 29 / 65 % | 12 / 50 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 20 / 36 % | 19 / 81 % | 55 / 73 % | 30 / 60 % | 8 / 25 % | 19 / 44 % | 5 / 26 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 32 % | 48 / 97 % | 30 / 59 % | 13 / 37 % | 9 / 34 % | 12 / 38 % | 1 / 10 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 31 / 59 % | 44 / 90 % | 28 / 56 % | 26 / 53 % | 16 / 48 % | 19 / 46 % | 7 / 29 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 14 / 35 % | 42 / 88 % | 11 / 37 % | 29 / 58 % | 13 / 39 % | 30 / 52 % | 6 / 28 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 52 % | 38 / 88 % | 33 / 67 % | 23 / 57 % | 16 / 44 % | 31 / 63 % | 9 / 43 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 14 / 34 % | 34 / 80 % | 25 / 53 % | 15 / 42 % | 6 / 19 % | 15 / 35 % | 1 / 11 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 53 % | 33 / 70 % | 18 / 50 % | 26 / 57 % | 23 / 63 % | 24 / 57 % | 7 / 30 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 11 / 42 % | 32 / 94 % | 19 / 58 % | 13 / 32 % | 3 / 9 % | 13 / 23 % | 1 / 8 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 29 / 74 % | 9 / 36 % | 8 / 26 % | 4 / 15 % | 11 / 22 % | 1 / 4 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 21 / 48 % | 13 / 55 % | 10 / 37 % | 26 / 51 % | 16 / 34 % | 28 / 44 % | 4 / 11 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 28 / 64 % | 1 / 17 % | 10 / 25 % | 6 / 18 % | 7 / 16 % | 2 / 9 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 9 / 87 % | 22 / 52 % | 27 / 57 % | 19 / 53 % | 16 / 45 % | 3 / 19 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 14 / 34 % | 20 / 92 % | 21 / 61 % | 27 / 56 % | 9 / 31 % | 11 / 34 % | 5 / 30 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 32 % | 25 / 70 % | 1 / 8 % | 9 / 26 % | 7 / 21 % | 13 / 29 % | 0 / 4 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 34 % | 23 / 81 % | 8 / 24 % | 12 / 34 % | 9 / 25 % | 14 / 33 % | 2 / 14 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 16 / 77 % | 23 / 54 % | 19 / 49 % | 2 / 14 % | 20 / 40 % | 2 / 12 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 13 / 29 % | 6 / 95 % | 3 / 37 % | 15 / 41 % | 6 / 19 % | 16 / 31 % | 2 / 12 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 11 / 26 % | 16 / 56 % | 0 / 0 % | 14 / 42 % | 10 / 34 % | 12 / 38 % | 2 / 14 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 34 % | 3 / 10 % | 8 / 14 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 6 / 31 % | 0 / 0 % | 7 / 18 % | 2 / 12 % | 12 / 25 % | 0 / 4 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 12 / 58 % | 0 / 4 % | 7 / 20 % | 2 / 8 % | 9 / 22 % | 1 / 6 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 7 / 44 % | 1 / 13 % | 9 / 23 % | 6 / 18 % | 11 / 22 % | 0 / 3 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 34 % | 6 / 49 % | 2 / 12 % | 10 / 30 % | 6 / 17 % | 11 / 23 % | 1 / 7 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 39 % | 6 / 16 % | 7 / 15 % | 1 / 4 % | 9 / 18 % | 0 / 2 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 4 / 71 % | 0 / 0 % | 7 / 19 % | 1 / 5 % | 8 / 13 % | 0 / 2 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 7 / 48 % | 0 / 0 % | 7 / 22 % | 3 / 10 % | 8 / 16 % | 0 / 2 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 8 / 13 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 7 / 62 % | 0 / 4 % | 7 / 17 % | 1 / 6 % | 7 / 13 % | 0 / 3 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 3 / 7 % | 5 / 9 % | 0 / 0 % | – |
