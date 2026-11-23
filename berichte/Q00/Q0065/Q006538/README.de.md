[English](README.md) · [Deutsch](README.de.md)

# Принципы ИИ: Рекомендации по этичному использованию искусственного интеллекта Министерством обороны

Bericht Q006538 · Quelle cset.georgetown.edu · Datum 2019-12-10 · [Original öffnen](https://cset.georgetown.edu/publication/%d0%bf%d1%80%d0%b8%d0%bd%d1%86%d0%b8%d0%bf%d1%8b-%d0%b8%d0%b8-%d1%80%d0%b5%d0%ba%d0%be%d0%bc%d0%b5%d0%bd%d0%b4%d0%b0%d1%86%d0%b8%d0%b8-%d0%bf%d0%be-%d1%8d%d1%82%d0%b8%d1%87%d0%bd%d0%be%d0%bc%d1%83/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht schlägt fünf ethische Grundsätze für KI im US-Verteidigungsministerium vor: menschliche Verantwortung, Vermeidung unbeabsichtigter Verzerrungen, Nachvollziehbarkeit, Zuverlässigkeit und Kontrollierbarkeit. Zwölf Empfehlungen sollen ihre mögliche Umsetzung unterstützen; ob das Ministerium sie übernimmt, bleibt ihm überlassen. Der vorliegende Text ist laut Vorspann eine nicht offizielle russische Übersetzung und keine Billigung durch CSET.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 40 / 62 % | 60 / 95 % | 100 / 100 % | 80 / 91 % | 42 / 67 % | 51 / 75 % | – | 52 / 78 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 56 / 73 % | 97 / 98 % | 97 / 99 % | 84 / 91 % | 56 / 74 % | 81 / 90 % | – | 68 / 83 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 36 / 57 % | 96 / 98 % | 83 / 93 % | 67 / 85 % | 37 / 63 % | 51 / 67 % | – | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 56 / 71 % | 82 / 93 % | 96 / 98 % | 85 / 92 % | 76 / 88 % | 82 / 90 % | – | 62 / 80 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 26 / 51 % | 91 / 99 % | 96 / 99 % | 54 / 76 % | 21 / 45 % | 37 / 58 % | – | 44 / 71 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 44 / 61 % | 95 / 98 % | 90 / 94 % | 76 / 87 % | 63 / 79 % | 67 / 80 % | – | 52 / 75 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 19 / 33 % | 92 / 98 % | 94 / 98 % | 29 / 57 % | 25 / 54 % | 32 / 55 % | – | 38 / 65 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 26 / 47 % | 68 / 96 % | 85 / 95 % | 58 / 77 % | 27 / 54 % | 35 / 60 % | – | 32 / 62 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 47 % | 81 / 93 % | 61 / 91 % | 64 / 84 % | 33 / 58 % | 61 / 80 % | – | 27 / 50 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 35 / 53 % | 78 / 98 % | 50 / 72 % | 37 / 70 % | 28 / 50 % | 44 / 67 % | – | 24 / 41 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 49 / 69 % | 74 / 91 % | 69 / 87 % | 61 / 80 % | 62 / 79 % | 74 / 86 % | – | 32 / 60 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 72 / 88 % | 19 / 47 % | 12 / 25 % | 19 / 33 % | – | 16 / 33 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 29 / 47 % | 71 / 93 % | 61 / 78 % | 49 / 76 % | 12 / 29 % | 32 / 58 % | – | 21 / 43 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 65 / 93 % | 28 / 51 % | 24 / 52 % | 12 / 24 % | 24 / 48 % | – | 19 / 38 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 23 / 51 % | 51 / 90 % | 64 / 89 % | 36 / 70 % | 11 / 31 % | 19 / 57 % | – | 28 / 51 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 11 / 33 % | 58 / 97 % | 42 / 79 % | 31 / 58 % | 26 / 54 % | 30 / 63 % | – | 36 / 60 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 57 / 95 % | 47 / 87 % | 27 / 60 % | 11 / 25 % | 14 / 36 % | – | 32 / 55 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 55 / 87 % | 27 / 61 % | 10 / 25 % | 7 / 15 % | 18 / 30 % | – | 13 / 36 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 54 / 81 % | 16 / 32 % | 17 / 44 % | 7 / 17 % | 11 / 28 % | – | 28 / 52 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 26 / 49 % | 52 / 95 % | 33 / 66 % | 29 / 57 % | 13 / 29 % | 23 / 43 % | – | 26 / 59 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 46 / 89 % | 27 / 75 % | 20 / 47 % | 9 / 27 % | 11 / 37 % | – | 49 / 73 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 28 % | 47 / 86 % | 18 / 62 % | 8 / 24 % | 4 / 11 % | 7 / 14 % | – | 18 / 46 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 16 / 80 % | 37 / 58 % | 14 / 37 % | 6 / 19 % | 17 / 37 % | – | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 37 / 96 % | 2 / 27 % | 17 / 52 % | 3 / 17 % | 21 / 48 % | – | 23 / 53 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 13 / 29 % | 34 / 70 % | 37 / 63 % | 20 / 52 % | 7 / 21 % | 13 / 30 % | – | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 34 / 88 % | 0 / 0 % | 25 / 62 % | 14 / 30 % | 28 / 57 % | – | 16 / 35 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 28 / 78 % | 2 / 12 % | 14 / 46 % | 5 / 15 % | 13 / 34 % | – | 11 / 24 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 43 % | 23 / 75 % | 0 / 0 % | 16 / 46 % | 7 / 18 % | 13 / 29 % | – | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 42 % | 5 / 13 % | 10 / 17 % | – | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 19 / 87 % | 9 / 46 % | 12 / 38 % | 7 / 24 % | 9 / 27 % | – | 20 / 46 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 20 / 95 % | 2 / 32 % | 14 / 43 % | 5 / 17 % | 11 / 23 % | – | 8 / 35 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 19 / 83 % | 0 / 0 % | 13 / 37 % | 6 / 16 % | 16 / 32 % | – | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 19 / 86 % | 12 / 39 % | 13 / 34 % | 7 / 20 % | 9 / 24 % | – | 18 / 40 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 17 / 78 % | 12 / 47 % | 17 / 46 % | 7 / 21 % | 7 / 20 % | – | 11 / 32 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 14 / 25 % | – | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 5 / 53 % | 5 / 21 % | 8 / 23 % | 5 / 13 % | 9 / 20 % | – | 11 / 32 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 4 / 12 % | 10 / 27 % | – | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 4 / 62 % | 1 / 7 % | 8 / 28 % | 2 / 6 % | 10 / 20 % | – | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 64 % | 0 / 0 % | 8 / 25 % | 3 / 10 % | 10 / 19 % | – | 4 / 15 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 5 / 67 % | 0 / 0 % | 7 / 19 % | 4 / 11 % | 9 / 17 % | – | 8 / 24 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 76 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 8 / 19 % | – | 9 / 26 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 8 / 15 % | – | 4 / 18 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 3 / 12 % | 7 / 20 % | – | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 6 / 15 % | – | 0 / 0 % |
