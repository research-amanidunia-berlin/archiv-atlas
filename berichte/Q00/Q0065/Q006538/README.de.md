[English](README.md) · [Deutsch](README.de.md)

# Принципы ИИ: Рекомендации по этичному использованию искусственного интеллекта Министерством обороны

Bericht Q006538 · Quelle cset.georgetown.edu · Datum 2019-12-10 · [Original öffnen](https://cset.georgetown.edu/publication/%d0%bf%d1%80%d0%b8%d0%bd%d1%86%d0%b8%d0%bf%d1%8b-%d0%b8%d0%b8-%d1%80%d0%b5%d0%ba%d0%be%d0%bc%d0%b5%d0%bd%d0%b4%d0%b0%d1%86%d0%b8%d0%b8-%d0%bf%d0%be-%d1%8d%d1%82%d0%b8%d1%87%d0%bd%d0%be%d0%bc%d1%83/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht schlägt fünf ethische Grundsätze für KI im US-Verteidigungsministerium vor: menschliche Verantwortung, Vermeidung unbeabsichtigter Verzerrungen, Nachvollziehbarkeit, Zuverlässigkeit und Kontrollierbarkeit. Zwölf Empfehlungen sollen ihre mögliche Umsetzung unterstützen; ob das Ministerium sie übernimmt, bleibt ihm überlassen. Der vorliegende Text ist laut Vorspann eine nicht offizielle russische Übersetzung und keine Billigung durch CSET.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 40 / 62 % | 60 / 95 % | – | 100 / 100 % | 80 / 91 % | 51 / 75 % | 42 / 67 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 56 / 73 % | 97 / 98 % | – | 97 / 99 % | 84 / 91 % | 81 / 90 % | 56 / 74 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 36 / 57 % | 96 / 98 % | – | 83 / 93 % | 67 / 85 % | 51 / 67 % | 37 / 63 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 56 / 71 % | 82 / 93 % | – | 96 / 98 % | 85 / 92 % | 82 / 90 % | 76 / 88 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 26 / 51 % | 91 / 99 % | – | 96 / 99 % | 54 / 76 % | 37 / 58 % | 21 / 45 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 44 / 61 % | 95 / 98 % | – | 90 / 94 % | 76 / 87 % | 67 / 80 % | 63 / 79 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 19 / 33 % | 92 / 98 % | – | 94 / 98 % | 29 / 57 % | 32 / 55 % | 25 / 54 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 26 / 47 % | 68 / 96 % | – | 85 / 95 % | 58 / 77 % | 35 / 60 % | 27 / 54 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 47 % | 81 / 93 % | – | 61 / 91 % | 64 / 84 % | 61 / 80 % | 33 / 58 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 35 / 53 % | 78 / 98 % | – | 50 / 72 % | 37 / 70 % | 44 / 67 % | 28 / 50 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 49 / 69 % | 74 / 91 % | – | 69 / 87 % | 61 / 80 % | 74 / 86 % | 62 / 79 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 72 / 88 % | 19 / 47 % | 19 / 33 % | 12 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 29 / 47 % | 71 / 93 % | – | 61 / 78 % | 49 / 76 % | 32 / 58 % | 12 / 29 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 65 / 93 % | – | 28 / 51 % | 24 / 52 % | 24 / 48 % | 12 / 24 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 23 / 51 % | 51 / 90 % | – | 64 / 89 % | 36 / 70 % | 19 / 57 % | 11 / 31 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 11 / 33 % | 58 / 97 % | – | 42 / 79 % | 31 / 58 % | 30 / 63 % | 26 / 54 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 57 / 95 % | – | 47 / 87 % | 27 / 60 % | 14 / 36 % | 11 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 55 / 87 % | – | 27 / 61 % | 10 / 25 % | 18 / 30 % | 7 / 15 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 54 / 81 % | – | 16 / 32 % | 17 / 44 % | 11 / 28 % | 7 / 17 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 26 / 49 % | 52 / 95 % | – | 33 / 66 % | 29 / 57 % | 23 / 43 % | 13 / 29 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 28 % | 47 / 86 % | – | 18 / 62 % | 8 / 24 % | 7 / 14 % | 4 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 46 / 89 % | – | 27 / 75 % | 20 / 47 % | 11 / 37 % | 9 / 27 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 16 / 80 % | – | 37 / 58 % | 14 / 37 % | 17 / 37 % | 6 / 19 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 37 / 96 % | – | 2 / 27 % | 17 / 52 % | 21 / 48 % | 3 / 17 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 13 / 29 % | 34 / 70 % | – | 37 / 63 % | 20 / 52 % | 13 / 30 % | 7 / 21 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 34 / 88 % | – | 0 / 0 % | 25 / 62 % | 28 / 57 % | 14 / 30 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 28 / 78 % | – | 2 / 12 % | 14 / 46 % | 13 / 34 % | 5 / 15 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 43 % | 23 / 75 % | – | 0 / 0 % | 16 / 46 % | 13 / 29 % | 7 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 21 / 42 % | 10 / 17 % | 5 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 20 / 95 % | – | 2 / 32 % | 14 / 43 % | 11 / 23 % | 5 / 17 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 19 / 83 % | – | 0 / 0 % | 13 / 37 % | 16 / 32 % | 6 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 19 / 87 % | – | 9 / 46 % | 12 / 38 % | 9 / 27 % | 7 / 24 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 19 / 86 % | – | 12 / 39 % | 13 / 34 % | 9 / 24 % | 7 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 17 / 78 % | – | 12 / 47 % | 17 / 46 % | 7 / 20 % | 7 / 21 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 14 / 25 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 10 / 27 % | 4 / 12 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 4 / 62 % | – | 1 / 7 % | 8 / 28 % | 10 / 20 % | 2 / 6 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 64 % | – | 0 / 0 % | 8 / 25 % | 10 / 19 % | 3 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 5 / 67 % | – | 0 / 0 % | 7 / 19 % | 9 / 17 % | 4 / 11 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 5 / 53 % | – | 5 / 21 % | 8 / 23 % | 9 / 20 % | 5 / 13 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 76 % | – | 0 / 0 % | 5 / 13 % | 8 / 19 % | 1 / 4 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 8 / 15 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 7 / 20 % | 3 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 15 % | 4 / 11 % |
