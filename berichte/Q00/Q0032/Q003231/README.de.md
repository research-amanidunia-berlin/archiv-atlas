[English](README.md) · [Deutsch](README.de.md)

# Securing Critical Infrastructure in the Age of AI

Bericht Q003231 · Quelle cset.georgetown.edu · Datum 2024-10-01 · [Original öffnen](https://cset.georgetown.edu/publication/securing-critical-infrastructure-in-the-age-of-ai/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Auszug aus der Zusammenfassung eines Workshop-Berichts beschreibt Chancen von KI für Betrieb und Cyberabwehr kritischer Infrastruktur sowie Risiken durch Fehlfunktionen, Schwachstellen und Missbrauch. Er empfiehlt unter anderem mehr Unterstützung und Informationsaustausch, klare Zuständigkeiten, abgestimmte Leitlinien, Weiterbildung und Vorsicht bei generativer KI in kritischen Aufgaben; die Workshop-Methodik ist im Auszug nicht erläutert.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 14 / 35 % | 89 / 99 % | 8 / 22 % | 73 / 88 % | 23 / 50 % | 19 / 46 % | 9 / 30 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 25 / 47 % | 74 / 88 % | 45 / 67 % | 86 / 93 % | 49 / 75 % | 35 / 63 % | 38 / 64 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 23 / 48 % | 62 / 94 % | 13 / 43 % | 72 / 92 % | 33 / 64 % | 33 / 64 % | 11 / 37 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 16 / 43 % | 27 / 79 % | 11 / 40 % | 66 / 87 % | 39 / 69 % | 25 / 60 % | 9 / 37 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 16 / 35 % | 63 / 84 % | 19 / 42 % | 6 / 62 % | 34 / 66 % | 22 / 52 % | 30 / 56 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 20 / 47 % | 44 / 84 % | 26 / 53 % | 38 / 67 % | 45 / 70 % | 50 / 70 % | 26 / 48 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 50 / 85 % | 1 / 7 % | 44 / 71 % | 12 / 32 % | 11 / 35 % | 3 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 16 / 30 % | 30 / 71 % | 9 / 29 % | 46 / 73 % | 19 / 53 % | 16 / 53 % | 14 / 42 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 36 % | 39 / 88 % | 1 / 9 % | 2 / 47 % | 9 / 30 % | 12 / 37 % | 4 / 20 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 21 / 49 % | 37 / 89 % | 11 / 43 % | 8 / 55 % | 25 / 54 % | 19 / 47 % | 14 / 38 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 33 / 70 % | 3 / 12 % | 6 / 14 % | 18 / 42 % | 17 / 38 % | 6 / 23 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 8 / 31 % | 31 / 68 % | 2 / 10 % | 2 / 23 % | 12 / 33 % | 10 / 27 % | 3 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 45 % | 17 / 96 % | 17 / 61 % | 12 / 62 % | 14 / 44 % | 30 / 64 % | 6 / 33 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 5 / 26 % | 27 / 81 % | 2 / 9 % | 16 / 62 % | 11 / 35 % | 8 / 26 % | 2 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 27 % | 24 / 71 % | 0 / 1 % | 3 / 32 % | 6 / 18 % | 4 / 9 % | 0 / 4 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 24 / 46 % | 10 / 24 % | 0 / 0 % | 20 / 50 % | 14 / 49 % | 19 / 45 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 24 / 79 % | 8 / 26 % | 3 / 54 % | 12 / 46 % | 11 / 35 % | 4 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 23 / 63 % | 1 / 4 % | 1 / 16 % | 6 / 17 % | 7 / 13 % | 2 / 8 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 11 / 23 % | 23 / 60 % | 2 / 10 % | 0 / 0 % | 8 / 23 % | 17 / 43 % | 8 / 25 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 22 / 43 % | 0 / 0 % | 2 / 9 % | 0 / 0 % | 6 / 27 % | 10 / 32 % | 2 / 12 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 16 / 56 % | 2 / 12 % | 2 / 43 % | 10 / 31 % | 12 / 28 % | 2 / 11 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 6 / 32 % | 15 / 79 % | 2 / 13 % | 3 / 46 % | 9 / 25 % | 12 / 32 % | 5 / 19 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 31 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 5 / 12 % | 5 / 11 % | 0 / 3 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 14 / 60 % | 0 / 1 % | 0 / 0 % | 7 / 15 % | 5 / 9 % | 1 / 3 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 10 / 68 % | 1 / 4 % | 11 / 42 % | 8 / 24 % | 7 / 19 % | 2 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 1 / 27 % | 0 / 0 % | 9 / 41 % | 6 / 18 % | 2 / 4 % | 0 / 3 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 31 % | 0 / 0 % | 0 / 5 % | 0 / 0 % | 7 / 18 % | 8 / 22 % | 2 / 8 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 8 / 38 % | 1 / 4 % | 0 / 0 % | 5 / 14 % | 5 / 11 % | 1 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 8 / 57 % | 0 / 4 % | 1 / 19 % | 0 / 0 % | 7 / 15 % | 1 / 7 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 0 / 0 % | 7 / 21 % | 8 / 17 % | 1 / 8 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 7 / 55 % | 0 / 1 % | 0 / 8 % | 6 / 20 % | 6 / 13 % | 1 / 5 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 6 / 46 % | 0 / 3 % | 1 / 19 % | 7 / 23 % | 5 / 13 % | 1 / 6 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 7 / 19 % | 3 / 8 % | 1 / 4 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 6 / 11 % | 1 / 3 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 4 / 10 % | 0 / 3 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 5 / 12 % | 5 / 10 % | 1 / 5 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 3 / 6 % | 1 / 4 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 26 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 5 / 11 % | 1 / 5 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 9 % | 1 / 5 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 12 % | 0 / 3 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 21 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
