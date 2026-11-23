[English](README.md) · [Deutsch](README.de.md)

# San Diego Alignment Workshop 2025

Bericht Q001716 · Quelle far.ai · Datum 2026-07-16 · [Original öffnen](https://www.far.ai/blog/san-diego-alignment-workshop-2025)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht fasst Vorträge eines Alignment-Workshops zusammen, in denen Forschende Risiken wie Sabotage, Jailbreaks, manipulative Einflussnahme und unzuverlässige Benchmarks beschrieben und mögliche Sicherheitsansätze vorstellten. Die Befunde sind den Vortragenden zugeschrieben; als Veranstaltungsrückblick liefert der Text nur begrenzte Angaben, um Studienmethoden und Ergebnisse eigenständig zu beurteilen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 53 / 71 % | 96 / 99 % | 100 / 100 % | 84 / 91 % | 72 / 85 % | 83 / 91 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 45 / 67 % | 78 / 96 % | 100 / 100 % | 79 / 90 % | 57 / 81 % | 77 / 89 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 48 / 69 % | 83 / 93 % | 99 / 100 % | 49 / 72 % | 67 / 83 % | 86 / 93 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 40 / 64 % | 99 / 100 % | 98 / 100 % | 73 / 86 % | 56 / 77 % | 77 / 88 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 49 / 69 % | 71 / 90 % | 92 / 97 % | 84 / 91 % | 78 / 89 % | 90 / 94 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 34 / 60 % | 49 / 82 % | 89 / 97 % | 71 / 85 % | 29 / 61 % | 43 / 69 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 30 / 54 % | 59 / 86 % | 89 / 94 % | 51 / 75 % | 23 / 51 % | 50 / 69 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 34 / 69 % | 87 / 93 % | 27 / 57 % | 8 / 32 % | 23 / 56 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 18 / 42 % | 62 / 95 % | 85 / 93 % | 34 / 57 % | 12 / 32 % | 36 / 55 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 13 / 39 % | 50 / 89 % | 81 / 88 % | 45 / 69 % | 13 / 41 % | 20 / 50 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 18 / 41 % | 58 / 99 % | 78 / 86 % | 25 / 54 % | 11 / 36 % | 18 / 50 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 42 / 71 % | 60 / 95 % | 76 / 93 % | 66 / 81 % | 30 / 54 % | 49 / 66 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 75 / 99 % | 53 / 79 % | 26 / 50 % | 10 / 31 % | 21 / 43 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 38 % | 23 / 81 % | 75 / 87 % | 33 / 61 % | 13 / 39 % | 21 / 63 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 23 / 71 % | 72 / 89 % | 52 / 75 % | 15 / 41 % | 19 / 45 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 22 / 50 % | 69 / 97 % | 66 / 89 % | 57 / 79 % | 22 / 44 % | 41 / 70 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 14 / 46 % | 32 / 81 % | 65 / 76 % | 32 / 59 % | 14 / 37 % | 17 / 43 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 24 / 52 % | 40 / 88 % | 42 / 56 % | 64 / 82 % | 36 / 59 % | 49 / 65 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 44 % | 22 / 85 % | 63 / 84 % | 60 / 79 % | 16 / 36 % | 45 / 63 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 24 / 54 % | 60 / 94 % | 61 / 81 % | 45 / 71 % | 18 / 49 % | 50 / 72 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 17 / 44 % | 56 / 91 % | 31 / 60 % | 23 / 51 % | 8 / 23 % | 20 / 41 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 20 / 46 % | 56 / 84 % | 7 / 24 % | 36 / 60 % | 16 / 35 % | 32 / 52 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 13 / 36 % | 45 / 71 % | 14 / 28 % | 37 / 60 % | 12 / 26 % | 32 / 48 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 16 / 76 % | 44 / 72 % | 15 / 40 % | 5 / 16 % | 12 / 27 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 12 / 34 % | 41 / 93 % | 12 / 61 % | 30 / 57 % | 10 / 30 % | 11 / 34 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 21 / 65 % | 32 / 53 % | 31 / 59 % | 13 / 43 % | 33 / 61 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 51 % | 12 / 59 % | 10 / 39 % | 27 / 55 % | 11 / 31 % | 15 / 29 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 15 / 42 % | 2 / 36 % | 10 / 23 % | 19 / 48 % | 6 / 23 % | 22 / 50 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 20 / 66 % | 0 / 3 % | 9 / 24 % | 6 / 21 % | 11 / 20 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 18 / 81 % | 15 / 46 % | 17 / 46 % | 3 / 11 % | 16 / 31 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 54 % | 1 / 19 % | 8 / 27 % | 5 / 17 % | 16 / 30 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 11 / 58 % | 0 / 0 % | 15 / 44 % | 3 / 13 % | 16 / 35 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 2 / 9 % | 14 / 25 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 9 / 25 % | 0 / 0 % | 1 / 5 % | 11 / 30 % | 5 / 19 % | 13 / 24 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 34 % | 0 / 26 % | 3 / 10 % | 13 / 34 % | 4 / 14 % | 10 / 23 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 7 % | 12 / 21 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 1 / 13 % | 3 / 18 % | 10 / 28 % | 6 / 20 % | 11 / 24 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 11 / 40 % | 0 / 0 % | 10 / 23 % | 5 / 14 % | 10 / 19 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 34 % | 3 / 11 % | 6 / 19 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 4 / 11 % | 10 / 17 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 6 % | 10 / 18 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 7 / 38 % | 0 / 0 % | 6 / 14 % | 2 / 8 % | 9 / 17 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 9 / 19 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 7 % | 9 / 20 % | – | – |
