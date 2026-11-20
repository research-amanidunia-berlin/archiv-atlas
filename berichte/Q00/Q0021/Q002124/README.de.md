[English](README.md) · [Deutsch](README.de.md)

# 人工智能控制：如何利用违规人工智能体

Bericht Q002124 · Quelle cset.georgetown.edu · Datum 2025-11-05 · [Original öffnen](https://cset.georgetown.edu/publication/ai-control-chinese/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der CSET-Bericht beschreibt KI-Kontrolle als zweite Schutzlinie neben der Ausrichtung: Sie soll verhindern, dass Agenten mit unerwünschten Zielen Schaden anrichten, selbst wenn sie sich regelwidrig verhalten. Vorgeschlagen werden unter anderem begrenzte Zugriffsrechte, Modellüberwachung, alternative Ausgaben und menschliche Prüfung. Der Text betont, dass Kosten, Verzögerungen und die Schwierigkeit, sehr leistungsfähige Agenten zuverlässig zu überwachen, zentrale offene Fragen bleiben.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 56 / 69 % | 88 / 98 % | 77 / 92 % | 99 / 100 % | 82 / 91 % | 81 / 90 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 59 / 79 % | 98 / 100 % | 97 / 99 % | 99 / 100 % | 90 / 94 % | 82 / 90 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 47 / 64 % | 93 / 99 % | 59 / 83 % | 98 / 100 % | 77 / 88 % | 78 / 88 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 55 / 73 % | 76 / 98 % | 85 / 93 % | 89 / 96 % | 84 / 92 % | 86 / 92 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 40 / 60 % | 57 / 93 % | 39 / 69 % | 71 / 88 % | 80 / 89 % | 86 / 92 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 30 / 50 % | 65 / 99 % | 53 / 77 % | 86 / 93 % | 73 / 87 % | 74 / 87 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 25 / 52 % | 79 / 96 % | 6 / 22 % | 82 / 90 % | 41 / 67 % | 49 / 68 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 26 / 62 % | 0 / 0 % | 72 / 88 % | 11 / 34 % | 10 / 16 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 62 / 92 % | 1 / 7 % | 69 / 85 % | 9 / 29 % | 7 / 20 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 35 / 54 % | 65 / 98 % | 42 / 72 % | 62 / 88 % | 45 / 73 % | 52 / 71 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 61 / 94 % | 4 / 14 % | 32 / 74 % | 34 / 63 % | 20 / 37 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 56 / 91 % | 9 / 23 % | 52 / 73 % | 11 / 36 % | 13 / 28 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 15 / 36 % | 50 / 94 % | 13 / 36 % | 37 / 84 % | 37 / 66 % | 26 / 51 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 14 / 40 % | 33 / 94 % | 13 / 43 % | 50 / 87 % | 20 / 51 % | 40 / 65 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 16 / 33 % | 50 / 89 % | 8 / 19 % | 50 / 67 % | 29 / 52 % | 32 / 49 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 11 / 28 % | 9 / 58 % | 3 / 16 % | 48 / 76 % | 21 / 49 % | 11 / 30 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 15 / 35 % | 41 / 94 % | 8 / 34 % | 31 / 75 % | 34 / 62 % | 32 / 50 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 40 / 94 % | 0 / 3 % | 12 / 48 % | 12 / 33 % | 13 / 30 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 32 / 97 % | 1 / 7 % | 21 / 52 % | 10 / 32 % | 17 / 37 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 32 / 94 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 7 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 30 / 82 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 6 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 12 / 27 % | 29 / 83 % | 2 / 14 % | 5 / 40 % | 15 / 39 % | 7 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 27 / 79 % | 2 / 10 % | 25 / 49 % | 19 / 51 % | 15 / 39 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 27 / 80 % | 0 / 3 % | 7 / 19 % | 12 / 33 % | 9 / 19 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 21 / 89 % | 1 / 5 % | 7 / 29 % | 24 / 52 % | 11 / 23 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 24 / 84 % | 0 / 0 % | 14 / 40 % | 13 / 39 % | 12 / 26 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 23 / 47 % | 11 / 78 % | 1 / 6 % | 0 / 0 % | 9 / 24 % | 18 / 42 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 21 / 67 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 6 / 12 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 19 / 59 % | 2 / 10 % | 0 / 0 % | 17 / 46 % | 13 / 29 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 7 / 81 % | 0 / 2 % | 18 / 37 % | 8 / 23 % | 8 / 17 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 16 / 55 % | 0 / 0 % | 8 / 23 % | 12 / 36 % | 10 / 18 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 16 / 53 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 5 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 11 / 31 % | 12 / 24 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 12 / 50 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 4 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 10 / 38 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 9 / 57 % | 0 / 0 % | 1 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 6 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 8 / 28 % | 7 / 17 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 20 % | 7 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 92 % | 0 / 0 % | 0 / 10 % | 7 / 22 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 6 / 12 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 3 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
