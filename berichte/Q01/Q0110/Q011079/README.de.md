[English](README.md) · [Deutsch](README.de.md)

# Claude Fable 5 Turned a Two-Month Migration Into a Day’s Work. You Have Two Weeks to Try It.

Bericht Q011079 · Quelle medium.com · Datum 2026-06-10 · [Original öffnen](https://medium.com/data-science-collective/claude-fable-5-turned-a-two-month-migration-into-a-days-work-you-have-two-weeks-to-try-it-b4a83973d8c1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor sieht in Fable 5s angeblich deutlich schnellerer Bearbeitung einer großen Stripe-Migration einen möglichen Wendepunkt für aufgeschobene Wartung, betont aber, dass die Zahl aus einer Hersteller-Fallstudie stammt und sorgfältige Prüfung sowie belastbare Tests weiterhin nötig sind. Er beschreibt weitere Fähigkeiten und die Sicherheitsfilter, Datenaufbewahrung sowie befristete Abo-Verfügbarkeit als Chancen und Einschränkungen, deren praktische Folgen besonders Entwickler sicherheitsnaher Systeme betreffen könnten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 44 % | 80 / 93 % | 29 / 59 % | 100 / 100 % | 65 / 82 % | 14 / 33 % | 61 / 77 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 78 / 92 % | 2 / 11 % | 98 / 99 % | 13 / 36 % | 3 / 13 % | 9 / 25 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 47 / 75 % | 0 / 3 % | 98 / 99 % | 10 / 24 % | 0 / 0 % | 7 / 12 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 27 / 45 % | 43 / 71 % | 22 / 39 % | 95 / 98 % | 31 / 52 % | 21 / 38 % | 51 / 69 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 51 / 79 % | 2 / 9 % | 95 / 97 % | 13 / 34 % | 4 / 14 % | 8 / 18 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 16 / 32 % | 88 / 94 % | 23 / 31 % | 94 / 96 % | 40 / 63 % | 8 / 21 % | 20 / 34 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 15 / 32 % | 50 / 81 % | 10 / 24 % | 93 / 96 % | 32 / 55 % | 8 / 18 % | 23 / 41 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 28 / 46 % | 44 / 71 % | 11 / 26 % | 91 / 94 % | 42 / 67 % | 21 / 41 % | 45 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 15 / 30 % | 39 / 66 % | 3 / 9 % | 88 / 92 % | 38 / 63 % | 13 / 28 % | 40 / 57 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 32 / 50 % | 48 / 83 % | 13 / 40 % | 84 / 92 % | 45 / 67 % | 9 / 28 % | 27 / 47 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 23 / 44 % | 29 / 71 % | 9 / 18 % | 79 / 86 % | 39 / 62 % | 20 / 36 % | 32 / 51 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 75 / 83 % | 10 / 19 % | 1 / 5 % | 4 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 5 / 13 % | 67 / 77 % | 23 / 45 % | 5 / 14 % | 12 / 26 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 23 / 44 % | 51 / 78 % | 17 / 30 % | 62 / 73 % | 56 / 75 % | 18 / 37 % | 49 / 65 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 2 / 10 % | 59 / 71 % | 9 / 23 % | 3 / 10 % | 6 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 8 / 35 % | 1 / 5 % | 58 / 73 % | 24 / 47 % | 6 / 16 % | 8 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 24 / 32 % | 2 / 4 % | 7 / 9 % | 27 / 40 % | 52 / 70 % | 13 / 25 % | 43 / 52 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 40 % | 0 / 0 % | 5 / 17 % | 49 / 69 % | 32 / 55 % | 5 / 17 % | 20 / 38 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 39 / 75 % | 2 / 7 % | 42 / 61 % | 21 / 47 % | 6 / 18 % | 12 / 29 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 24 / 46 % | 18 / 54 % | 14 / 42 % | 41 / 56 % | 34 / 57 % | 11 / 31 % | 26 / 43 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 32 % | 40 / 70 % | 1 / 8 % | 28 / 48 % | 13 / 33 % | 3 / 12 % | 12 / 28 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 35 / 64 % | 0 / 2 % | 17 / 29 % | 9 / 21 % | 0 / 0 % | 10 / 19 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 27 / 70 % | 1 / 6 % | 34 / 41 % | 16 / 35 % | 3 / 11 % | 7 / 16 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 25 / 50 % | 1 / 4 % | 32 / 49 % | 10 / 23 % | 0 / 0 % | 10 / 20 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 51 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 40 % | 7 / 13 % | 2 / 8 % | 5 / 9 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 27 % | 6 / 12 % | 0 / 1 % | 5 / 10 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 33 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 11 / 29 % | 2 / 7 % | 14 / 28 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 2 / 6 % | 16 / 24 % | 12 / 28 % | 3 / 9 % | 12 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 25 % | 1 / 4 % | 9 / 19 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 12 / 28 % | 12 / 28 % | 2 / 8 % | 5 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 0 / 0 % | 6 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 1 / 5 % | 5 / 17 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 1 / 4 % | 6 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 8 / 15 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 2 / 5 % | 8 / 18 % | 3 / 8 % | 7 / 16 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 3 % | 7 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 16 % | 2 / 9 % | 6 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 1 / 3 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 4 % | 5 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 10 % |
