[English](README.md) · [Deutsch](README.de.md)

# 人工智能原则: 美国国防部关于人工智能道德使用的建议

Bericht Q006534 · Quelle cset.georgetown.edu · Datum 2019-12-10 · [Original öffnen](https://cset.georgetown.edu/publication/%e4%ba%ba%e5%b7%a5%e6%99%ba%e8%83%bd%e5%8e%9f%e5%88%99-%e7%be%8e%e5%9b%bd%e5%9b%bd%e9%98%b2%e9%83%a8%e5%85%b3%e4%ba%8e%e4%ba%ba%e5%b7%a5%e6%99%ba%e8%83%bd%e9%81%93%e5%be%b7%e4%bd%bf%e7%94%a8%e7%9a%84/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt fünf vom unabhängigen US-Verteidigungsinnovationsrat vorgeschlagene KI-Grundsätze vor: Verantwortung, Fairness, Nachvollziehbarkeit, Zuverlässigkeit und Kontrollierbarkeit. Zwölf Empfehlungen sollen unter anderem Aufsicht, Ausbildung, Forschung und risikobasierte Prüfungen stärken. Es handelt sich um Vorschläge zur Prüfung durch das Verteidigungsministerium, nicht um bereits beschlossene Politik; die chinesische Übersetzung ist laut CSET nicht offiziell und keine Billigung der Grundsätze.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 47 / 69 % | 79 / 96 % | 99 / 100 % | 79 / 90 % | 62 / 82 % | 55 / 78 % | 57 / 85 % | 49 / 73 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 40 / 60 % | 98 / 99 % | 91 / 95 % | 72 / 85 % | 64 / 78 % | 56 / 70 % | 50 / 62 % | 56 / 75 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 55 / 73 % | 98 / 100 % | 97 / 99 % | 86 / 92 % | 66 / 82 % | 81 / 90 % | 54 / 76 % | 60 / 79 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 59 / 73 % | 95 / 99 % | 95 / 98 % | 84 / 92 % | 76 / 90 % | 80 / 90 % | 84 / 94 % | 53 / 73 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 29 / 55 % | 83 / 97 % | 93 / 98 % | 50 / 74 % | 26 / 50 % | 31 / 54 % | 10 / 31 % | 40 / 67 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 20 / 36 % | 81 / 96 % | 93 / 97 % | 33 / 61 % | 43 / 71 % | 32 / 60 % | 16 / 32 % | 42 / 67 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 53 / 72 % | 92 / 99 % | 67 / 85 % | 65 / 81 % | 72 / 84 % | 80 / 90 % | 33 / 60 % | 39 / 64 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 34 / 53 % | 90 / 96 % | 83 / 92 % | 64 / 83 % | 65 / 81 % | 50 / 64 % | 18 / 33 % | 20 / 36 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 32 / 53 % | 90 / 99 % | 48 / 68 % | 32 / 65 % | 45 / 69 % | 38 / 69 % | 11 / 31 % | 17 / 33 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 24 / 47 % | 81 / 98 % | 56 / 75 % | 22 / 49 % | 12 / 34 % | 23 / 51 % | 6 / 20 % | 21 / 42 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 26 / 47 % | 74 / 98 % | 77 / 92 % | 50 / 73 % | 34 / 61 % | 29 / 53 % | 23 / 52 % | 29 / 58 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 26 / 52 % | 54 / 97 % | 74 / 91 % | 28 / 66 % | 11 / 35 % | 15 / 57 % | 9 / 30 % | 29 / 52 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 33 / 71 % | 74 / 88 % | 17 / 44 % | 11 / 33 % | 20 / 37 % | 5 / 13 % | 16 / 31 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 31 / 48 % | 71 / 93 % | 57 / 78 % | 34 / 66 % | 8 / 24 % | 17 / 43 % | 7 / 17 % | 16 / 33 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 27 / 47 % | 56 / 89 % | 68 / 91 % | 63 / 83 % | 38 / 65 % | 58 / 79 % | 16 / 41 % | 20 / 44 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 30 % | 64 / 96 % | 50 / 87 % | 23 / 56 % | 9 / 23 % | 10 / 34 % | 7 / 18 % | 29 / 57 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 11 / 35 % | 52 / 94 % | 44 / 79 % | 33 / 65 % | 26 / 57 % | 31 / 62 % | 10 / 30 % | 22 / 49 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 16 / 43 % | 51 / 98 % | 47 / 82 % | 30 / 58 % | 10 / 30 % | 17 / 44 % | 8 / 28 % | 44 / 74 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 50 / 82 % | 0 / 0 % | 28 / 63 % | 20 / 45 % | 28 / 58 % | 6 / 19 % | 10 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 43 / 83 % | 21 / 49 % | 11 / 29 % | 5 / 14 % | 16 / 28 % | 1 / 6 % | 16 / 37 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 23 / 51 % | 43 / 97 % | 32 / 68 % | 30 / 58 % | 13 / 34 % | 24 / 46 % | 5 / 19 % | 25 / 56 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 41 / 87 % | 16 / 35 % | 19 / 47 % | 9 / 23 % | 12 / 30 % | 5 / 15 % | 28 / 51 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 40 / 88 % | 0 / 0 % | 14 / 36 % | 8 / 24 % | 9 / 24 % | 1 / 5 % | 25 / 54 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 15 / 28 % | 39 / 84 % | 21 / 60 % | 8 / 24 % | 4 / 16 % | 5 / 16 % | 0 / 4 % | 26 / 54 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 37 / 82 % | 0 / 0 % | 13 / 44 % | 1 / 9 % | 11 / 30 % | 2 / 8 % | 23 / 50 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 14 / 42 % | 35 / 77 % | 36 / 56 % | 16 / 43 % | 6 / 20 % | 19 / 41 % | 2 / 7 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 35 / 81 % | 34 / 60 % | 17 / 47 % | 6 / 18 % | 13 / 29 % | 2 / 9 % | 8 / 22 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 25 / 45 % | 5 / 15 % | 9 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 21 / 95 % | 11 / 50 % | 12 / 38 % | 7 / 26 % | 9 / 30 % | 1 / 10 % | 20 / 49 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 50 % | 20 / 94 % | 0 / 0 % | 17 / 48 % | 11 / 28 % | 12 / 32 % | 5 / 17 % | 10 / 25 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 17 / 77 % | 12 / 45 % | 18 / 47 % | 7 / 21 % | 7 / 21 % | 2 / 8 % | 8 / 27 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 18 / 96 % | 0 / 0 % | 10 / 32 % | 5 / 19 % | 9 / 19 % | 0 / 3 % | 5 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 18 / 72 % | 0 / 0 % | 16 / 48 % | 6 / 14 % | 12 / 36 % | 3 / 11 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 17 / 97 % | 1 / 24 % | 8 / 28 % | 4 / 14 % | 9 / 24 % | 1 / 6 % | 8 / 29 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 10 / 83 % | 0 / 0 % | 8 / 26 % | 6 / 19 % | 14 / 29 % | 2 / 10 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 12 / 87 % | 0 / 0 % | 7 / 24 % | 1 / 9 % | 8 / 16 % | 0 / 2 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 65 % | 0 / 0 % | 5 / 12 % | 2 / 9 % | 6 / 19 % | 0 / 3 % | 12 / 34 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 4 / 14 % | 10 / 27 % | 1 / 7 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 2 / 12 % | 7 / 19 % | 5 / 15 % | 8 / 19 % | 0 / 3 % | 7 / 27 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 2 / 25 % | 0 / 0 % | 7 / 17 % | 4 / 13 % | 7 / 14 % | 0 / 2 % | 6 / 21 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 3 / 11 % | 5 / 18 % | 0 / 3 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 13 % | 6 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 8 % | 5 / 10 % | 0 / 1 % | 3 / 13 % |
