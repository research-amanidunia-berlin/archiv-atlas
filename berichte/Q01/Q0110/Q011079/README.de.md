[English](README.md) · [Deutsch](README.de.md)

# Claude Fable 5 Turned a Two-Month Migration Into a Day’s Work. You Have Two Weeks to Try It.

Bericht Q011079 · Quelle medium.com · Datum 2026-06-10 · [Original öffnen](https://medium.com/data-science-collective/claude-fable-5-turned-a-two-month-migration-into-a-days-work-you-have-two-weeks-to-try-it-b4a83973d8c1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor sieht in Fable 5s angeblich deutlich schnellerer Bearbeitung einer großen Stripe-Migration einen möglichen Wendepunkt für aufgeschobene Wartung, betont aber, dass die Zahl aus einer Hersteller-Fallstudie stammt und sorgfältige Prüfung sowie belastbare Tests weiterhin nötig sind. Er beschreibt weitere Fähigkeiten und die Sicherheitsfilter, Datenaufbewahrung sowie befristete Abo-Verfügbarkeit als Chancen und Einschränkungen, deren praktische Folgen besonders Entwickler sicherheitsnaher Systeme betreffen könnten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 44 % | 80 / 93 % | 29 / 59 % | 100 / 100 % | 65 / 82 % | 61 / 77 % | 14 / 33 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 78 / 92 % | 2 / 11 % | 98 / 99 % | 13 / 36 % | 9 / 25 % | 3 / 13 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 47 / 75 % | 0 / 3 % | 98 / 99 % | 10 / 24 % | 7 / 12 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 27 / 45 % | 43 / 71 % | 22 / 39 % | 95 / 98 % | 31 / 52 % | 51 / 69 % | 21 / 38 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 51 / 79 % | 2 / 9 % | 95 / 97 % | 13 / 34 % | 8 / 18 % | 4 / 14 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 16 / 32 % | 88 / 94 % | 23 / 31 % | 94 / 96 % | 40 / 63 % | 20 / 34 % | 8 / 21 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 15 / 32 % | 50 / 81 % | 10 / 24 % | 93 / 96 % | 32 / 55 % | 23 / 41 % | 8 / 18 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 28 / 46 % | 44 / 71 % | 11 / 26 % | 91 / 94 % | 42 / 67 % | 45 / 67 % | 21 / 41 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 15 / 30 % | 39 / 66 % | 3 / 9 % | 88 / 92 % | 38 / 63 % | 40 / 57 % | 13 / 28 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 32 / 50 % | 48 / 83 % | 13 / 40 % | 84 / 92 % | 45 / 67 % | 27 / 47 % | 9 / 28 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 23 / 44 % | 29 / 71 % | 9 / 18 % | 79 / 86 % | 39 / 62 % | 32 / 51 % | 20 / 36 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 75 / 83 % | 10 / 19 % | 4 / 8 % | 1 / 5 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 5 / 13 % | 67 / 77 % | 23 / 45 % | 12 / 26 % | 5 / 14 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 23 / 44 % | 51 / 78 % | 17 / 30 % | 62 / 73 % | 56 / 75 % | 49 / 65 % | 18 / 37 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 2 / 10 % | 59 / 71 % | 9 / 23 % | 6 / 16 % | 3 / 10 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 8 / 35 % | 1 / 5 % | 58 / 73 % | 24 / 47 % | 8 / 20 % | 6 / 16 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 24 / 32 % | 2 / 4 % | 7 / 9 % | 27 / 40 % | 52 / 70 % | 43 / 52 % | 13 / 25 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 40 % | 0 / 0 % | 5 / 17 % | 49 / 69 % | 32 / 55 % | 20 / 38 % | 5 / 17 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 39 / 75 % | 2 / 7 % | 42 / 61 % | 21 / 47 % | 12 / 29 % | 6 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 24 / 46 % | 18 / 54 % | 14 / 42 % | 41 / 56 % | 34 / 57 % | 26 / 43 % | 11 / 31 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 32 % | 40 / 70 % | 1 / 8 % | 28 / 48 % | 13 / 33 % | 12 / 28 % | 3 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 35 / 64 % | 0 / 2 % | 17 / 29 % | 9 / 21 % | 10 / 19 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 27 / 70 % | 1 / 6 % | 34 / 41 % | 16 / 35 % | 7 / 16 % | 3 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 25 / 50 % | 1 / 4 % | 32 / 49 % | 10 / 23 % | 10 / 20 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 51 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 40 % | 7 / 13 % | 5 / 9 % | 2 / 8 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 27 % | 6 / 12 % | 5 / 10 % | 0 / 1 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 33 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 11 / 29 % | 14 / 28 % | 2 / 7 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 2 / 6 % | 16 / 24 % | 12 / 28 % | 12 / 25 % | 3 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 25 % | 9 / 19 % | 1 / 4 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 12 / 28 % | 12 / 28 % | 5 / 15 % | 2 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 6 / 12 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 5 / 17 % | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 6 / 11 % | 1 / 4 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 14 % | 8 / 15 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 2 / 5 % | 8 / 18 % | 7 / 16 % | 3 / 8 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 7 / 12 % | 1 / 3 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 16 % | 6 / 13 % | 2 / 9 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | 1 / 3 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 5 / 10 % | 1 / 4 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % |
