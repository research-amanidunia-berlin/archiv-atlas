[English](README.md) · [Deutsch](README.de.md)

# https://arxiv.org/pdf/2410.07095

Bericht Q009434 · Quelle arxiv.org · Datum – · [Original öffnen](https://arxiv.org/pdf/2410.07095)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt MLE-bench, einen Benchmark aus 75 Kaggle-Wettbewerben zur Bewertung von KI-Agenten im Machine-Learning-Engineering. Die beste getestete Kombination, o1-preview mit AIDE, erreichte mindestens eine Medaille bei 16,9 Prozent der Wettbewerbe; mehr Versuche und längere Laufzeiten konnten die Leistung steigern. Die Autoren betonen Grenzen durch die eingeschränkte Abdeckung realer Forschung, mögliche Kontamination, veränderte Datensplits und hohe Rechenkosten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 39 / 56 % | 100 / 100 % | 100 / 100 % | 54 / 76 % | 18 / 34 % | 59 / 75 % | 27 / 60 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 41 / 58 % | 99 / 100 % | 99 / 100 % | 70 / 84 % | 5 / 13 % | 40 / 57 % | 11 / 30 % | 16 / 40 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 83 / 98 % | 89 / 93 % | 22 / 50 % | 7 / 17 % | 28 / 47 % | 4 / 15 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 34 / 54 % | 88 / 98 % | 60 / 82 % | 67 / 85 % | 20 / 39 % | 67 / 78 % | 67 / 86 % | 30 / 54 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 10 / 58 % | 87 / 93 % | 46 / 72 % | 4 / 12 % | 16 / 30 % | 3 / 15 % | 12 / 28 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 61 / 92 % | 79 / 88 % | 20 / 45 % | 3 / 10 % | 20 / 37 % | 1 / 5 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 37 / 57 % | 69 / 94 % | 29 / 47 % | 35 / 63 % | 10 / 26 % | 35 / 55 % | 22 / 57 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 23 / 81 % | 69 / 85 % | 15 / 36 % | 2 / 6 % | 21 / 33 % | 0 / 0 % | 36 / 55 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 15 / 95 % | 67 / 75 % | 12 / 27 % | 0 / 0 % | 8 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 7 / 57 % | 63 / 77 % | 6 / 14 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 61 / 89 % | 50 / 61 % | 26 / 53 % | 0 / 0 % | 23 / 37 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 61 / 86 % | 0 / 0 % | 19 / 39 % | 0 / 0 % | 15 / 24 % | 0 / 0 % | 9 / 25 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 22 / 42 % | 57 / 94 % | 19 / 42 % | 41 / 66 % | 5 / 13 % | 38 / 57 % | 8 / 34 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 43 / 92 % | 56 / 67 % | 9 / 28 % | 3 / 7 % | 13 / 25 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 53 / 78 % | 0 / 0 % | 34 / 60 % | 2 / 8 % | 24 / 38 % | 2 / 12 % | 20 / 35 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 41 / 81 % | 31 / 65 % | 6 / 17 % | 1 / 4 % | 4 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 20 / 77 % | 36 / 56 % | 7 / 20 % | 1 / 4 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 27 / 53 % | 0 / 0 % | 0 / 0 % | 18 / 43 % | 3 / 7 % | 31 / 53 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 31 / 70 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 19 / 40 % | 19 / 98 % | 0 / 0 % | 23 / 48 % | 2 / 9 % | 19 / 35 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 19 / 61 % | 0 / 0 % | 6 / 15 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 17 / 43 % | 10 / 29 % | 1 / 5 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 40 % | 2 / 7 % | 10 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 24 % | 0 / 0 % | 13 / 24 % | 0 / 0 % | 14 / 30 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 12 / 54 % | 0 / 0 % | 10 / 24 % | 4 / 10 % | 13 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 4 / 59 % | 0 / 0 % | 11 / 29 % | 1 / 6 % | 6 / 14 % | 0 / 0 % | 13 / 30 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 4 / 66 % | 0 / 0 % | 8 / 20 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 8 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 0 / 1 % | 7 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 4 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
