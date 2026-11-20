[English](README.md) · [Deutsch](README.de.md)

# Paul Christiano: AI Alignment - What’s Working and What’s Not | The Hinton Lectures 2026 (Night 1)

Bericht Q000297 · Quelle youtube.com · Datum 2026-11-09 · [Original öffnen](https://www.youtube.com/watch?v=-Ef0ocEoBCs)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 63 / 78 % | 99 / 100 % | – | 100 / 100 % | 92 / 96 % | 81 / 90 % | 82 / 91 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 61 / 77 % | 99 / 100 % | – | 100 / 100 % | 96 / 97 % | 89 / 94 % | 42 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 42 / 65 % | 91 / 98 % | – | 99 / 100 % | 80 / 90 % | 76 / 89 % | 72 / 89 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 46 / 72 % | 88 / 99 % | – | 99 / 100 % | 89 / 94 % | 69 / 85 % | 33 / 64 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 26 / 54 % | 49 / 89 % | – | 97 / 99 % | 51 / 77 % | 47 / 73 % | 23 / 52 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 33 / 53 % | 96 / 99 % | – | 93 / 98 % | 68 / 86 % | 69 / 83 % | 62 / 78 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 15 / 47 % | 50 / 87 % | – | 96 / 98 % | 53 / 76 % | 39 / 66 % | 36 / 59 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 31 / 57 % | 94 / 99 % | – | 81 / 90 % | 52 / 76 % | 69 / 82 % | 33 / 56 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 48 / 71 % | 68 / 98 % | – | 93 / 97 % | 88 / 93 % | 87 / 93 % | 83 / 92 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 17 / 35 % | 93 / 98 % | – | 93 / 98 % | 29 / 62 % | 28 / 61 % | 13 / 38 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 27 / 54 % | 92 / 98 % | – | 83 / 95 % | 47 / 74 % | 55 / 72 % | 29 / 52 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 25 / 49 % | 89 / 98 % | – | 76 / 90 % | 44 / 71 % | 35 / 50 % | 22 / 38 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 23 / 44 % | 54 / 85 % | – | 88 / 94 % | 46 / 72 % | 36 / 58 % | 9 / 22 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 33 / 60 % | 74 / 93 % | – | 80 / 95 % | 70 / 86 % | 62 / 82 % | 54 / 79 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 24 / 52 % | 45 / 92 % | – | 76 / 91 % | 32 / 61 % | 23 / 50 % | 18 / 43 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 19 / 54 % | 41 / 89 % | – | 75 / 90 % | 40 / 68 % | 50 / 74 % | 26 / 55 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 18 / 49 % | 73 / 99 % | – | 54 / 89 % | 55 / 81 % | 44 / 73 % | 47 / 72 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 22 / 39 % | 56 / 91 % | – | 73 / 90 % | 25 / 53 % | 21 / 39 % | 13 / 34 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 27 / 53 % | 53 / 96 % | – | 71 / 86 % | 51 / 72 % | 46 / 63 % | 36 / 57 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 20 / 55 % | 54 / 85 % | – | 56 / 85 % | 47 / 74 % | 34 / 55 % | 34 / 52 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 13 / 29 % | 16 / 94 % | – | 55 / 78 % | 37 / 65 % | 18 / 40 % | 14 / 39 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 14 / 42 % | 53 / 99 % | – | 51 / 75 % | 33 / 64 % | 25 / 50 % | 11 / 30 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 24 / 44 % | 52 / 94 % | – | 50 / 79 % | 36 / 63 % | 25 / 47 % | 14 / 35 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 51 / 85 % | – | 37 / 50 % | 29 / 56 % | 33 / 54 % | 19 / 34 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 24 / 49 % | 50 / 95 % | – | 37 / 73 % | 27 / 57 % | 29 / 50 % | 11 / 25 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 19 / 91 % | – | 30 / 76 % | 39 / 66 % | 42 / 59 % | 13 / 39 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 41 / 81 % | – | 11 / 36 % | 7 / 22 % | 15 / 28 % | 6 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 17 / 33 % | 38 / 98 % | – | 31 / 73 % | 36 / 64 % | 16 / 36 % | 9 / 25 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 23 / 57 % | 35 / 92 % | – | 18 / 57 % | 26 / 58 % | 36 / 61 % | 23 / 49 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 8 / 78 % | – | 27 / 53 % | 9 / 25 % | 16 / 36 % | 6 / 17 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 11 / 36 % | 23 / 84 % | – | 9 / 35 % | 9 / 29 % | 15 / 26 % | 10 / 22 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 6 / 58 % | – | 10 / 29 % | 16 / 41 % | 22 / 36 % | 10 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 21 / 67 % | – | 13 / 26 % | 11 / 32 % | 15 / 24 % | 9 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 21 / 86 % | – | 15 / 61 % | 9 / 21 % | 20 / 33 % | 5 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 16 / 35 % | 4 / 97 % | – | 10 / 61 % | 13 / 38 % | 21 / 36 % | 10 / 26 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 2 / 35 % | – | 0 / 0 % | 5 / 14 % | 19 / 28 % | 2 / 6 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 18 / 31 % | 1 / 4 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 18 / 95 % | – | 8 / 36 % | 8 / 23 % | 16 / 33 % | 3 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 4 / 50 % | – | 16 / 41 % | 7 / 19 % | 16 / 28 % | 2 / 8 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 12 / 75 % | – | 2 / 17 % | 10 / 28 % | 14 / 28 % | 8 / 21 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 12 / 94 % | – | 0 / 0 % | 5 / 12 % | 14 / 22 % | 3 / 9 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 13 / 22 % | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 3 / 55 % | – | 12 / 51 % | 8 / 24 % | 10 / 18 % | 9 / 22 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 15 % | 12 / 20 % | 5 / 12 % |
