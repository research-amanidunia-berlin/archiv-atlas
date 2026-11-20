[English](README.md) · [Deutsch](README.de.md)

# METR’s GPT-4.5 pre-deployment evaluations

Bericht Q002575 · Quelle metr.org · Datum 2025-02-27 · [Original öffnen](https://metr.org/blog/2025-02-27-gpt-4-5-evals/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

METR zufolge lag GPT-4.5 in vorläufigen Autonomie- und RE-Bench-Prüfungen zwischen GPT-4o und o1, wobei das eingesetzte Agentengerüst für o1 optimiert war. METR hält große Risiken vorläufig für unwahrscheinlich, erklärt aber, dass die kurzen Tests sie nicht ausschließen und mögliche Fähigkeitssteigerungen durch Nachtraining oder absichtliches Unterbieten offenbleiben. Der bereitgestellte Auszug endet mit einer abgeschnittenen Bildbeschreibung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 41 / 64 % | 97 / 100 % | 85 / 94 % | 95 / 99 % | 58 / 80 % | 64 / 84 % | 80 / 90 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 21 / 48 % | 95 / 100 % | 29 / 56 % | 96 / 99 % | 41 / 68 % | 14 / 33 % | 48 / 69 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 42 / 66 % | 69 / 87 % | 45 / 71 % | 94 / 97 % | 36 / 56 % | 47 / 69 % | 41 / 60 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 41 / 63 % | 89 / 99 % | 54 / 78 % | 83 / 96 % | 55 / 78 % | 50 / 70 % | 68 / 81 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 20 / 92 % | 8 / 27 % | 89 / 96 % | 36 / 64 % | 13 / 36 % | 9 / 21 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 49 % | 49 / 97 % | 10 / 37 % | 89 / 96 % | 26 / 57 % | 9 / 31 % | 31 / 59 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 34 / 65 % | 36 / 83 % | 22 / 55 % | 67 / 92 % | 10 / 23 % | 24 / 52 % | 45 / 67 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 53 / 95 % | 1 / 5 % | 66 / 83 % | 11 / 32 % | 1 / 6 % | 8 / 17 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 30 / 50 % | 20 / 82 % | 10 / 27 % | 64 / 83 % | 50 / 74 % | 11 / 27 % | 65 / 79 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 29 / 51 % | 56 / 94 % | 5 / 16 % | 65 / 88 % | 30 / 59 % | 7 / 22 % | 36 / 61 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 45 / 96 % | 0 / 4 % | 61 / 76 % | 12 / 33 % | 5 / 15 % | 6 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 13 / 72 % | 0 / 0 % | 48 / 69 % | 8 / 23 % | 1 / 5 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 47 / 86 % | 0 / 4 % | 41 / 69 % | 9 / 24 % | 1 / 7 % | 6 / 16 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 18 / 46 % | 28 / 99 % | 6 / 27 % | 46 / 86 % | 27 / 58 % | 5 / 20 % | 25 / 47 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 38 % | 19 / 61 % | 6 / 17 % | 46 / 68 % | 22 / 48 % | 12 / 32 % | 24 / 41 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 4 / 28 % | 0 / 0 % | 45 / 64 % | 9 / 28 % | 2 / 10 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 22 / 46 % | 44 / 92 % | 12 / 45 % | 32 / 72 % | 37 / 64 % | 11 / 32 % | 39 / 59 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 39 / 62 % | 1 / 4 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 1 / 9 % | 39 / 68 % | 7 / 23 % | 3 / 13 % | 6 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 32 / 79 % | 1 / 5 % | 0 / 0 % | 17 / 38 % | 1 / 7 % | 9 / 16 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 30 / 61 % | 7 / 17 % | 2 / 10 % | 9 / 19 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 12 / 38 % | 30 / 82 % | 1 / 8 % | 21 / 57 % | 23 / 46 % | 3 / 12 % | 10 / 20 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 4 / 40 % | 0 / 3 % | 29 / 61 % | 9 / 23 % | 2 / 9 % | 7 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 39 % | 8 / 64 % | 4 / 13 % | 8 / 32 % | 20 / 50 % | 8 / 23 % | 27 / 47 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 5 / 83 % | 3 / 13 % | 0 / 0 % | 9 / 32 % | 3 / 13 % | 24 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 45 % | 16 / 90 % | 1 / 6 % | 24 / 56 % | 13 / 36 % | 1 / 9 % | 14 / 32 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 6 / 83 % | 0 / 2 % | 22 / 46 % | 6 / 17 % | 2 / 9 % | 5 / 12 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 20 / 79 % | 1 / 8 % | 1 / 7 % | 8 / 19 % | 4 / 12 % | 7 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 16 / 77 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 38 % | 9 / 26 % | 0 / 3 % | 8 / 20 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 10 / 73 % | 0 / 2 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 1 / 7 % | 8 / 18 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 28 % | 8 / 22 % | 0 / 3 % | 5 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 1 / 20 % | 0 / 2 % | 0 / 5 % | 6 / 15 % | 1 / 6 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 16 % | 6 / 14 % | 1 / 4 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 4 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 4 / 9 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 2 % | 5 / 14 % |
