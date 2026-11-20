[English](README.md) · [Deutsch](README.de.md)

# Anthropic's core views on AI safety

Bericht Q004100 · Quelle anthropic.com · Datum 2023-03-08 · [Original öffnen](https://www.anthropic.com/news/core-views-on-ai-safety)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic hält schnelle KI-Fortschritte und große gesellschaftliche Folgen für plausibel, betont aber, dass die Prognosen unsicher sind. Das Unternehmen will mit empirischer Sicherheitsforschung Risiken erkennen und sichere Trainingsmethoden entwickeln, räumt jedoch ein, dass weder die Lösbarkeit der Sicherheitsprobleme noch der Erfolg der Ansätze feststeht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 33 / 56 % | 93 / 99 % | – | 89 / 97 % | 46 / 74 % | 58 / 78 % | 18 / 47 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 30 / 54 % | 76 / 95 % | – | 91 / 95 % | 46 / 72 % | 60 / 76 % | 15 / 45 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 31 / 57 % | 90 / 99 % | – | 87 / 96 % | 54 / 80 % | 60 / 82 % | 23 / 55 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 28 / 56 % | 83 / 94 % | – | 86 / 95 % | 59 / 81 % | 52 / 76 % | 28 / 60 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 50 / 70 % | 64 / 96 % | – | 86 / 97 % | 78 / 90 % | 83 / 92 % | 68 / 86 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 34 / 59 % | 86 / 97 % | – | 85 / 99 % | 62 / 83 % | 60 / 83 % | 35 / 67 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 45 % | 81 / 94 % | – | 55 / 82 % | 14 / 43 % | 14 / 47 % | 3 / 18 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 21 / 51 % | 80 / 98 % | – | 53 / 82 % | 42 / 69 % | 36 / 56 % | 9 / 32 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 59 / 88 % | – | 79 / 91 % | 15 / 47 % | 18 / 39 % | 5 / 24 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 19 / 48 % | 54 / 88 % | – | 69 / 82 % | 26 / 51 % | 23 / 45 % | 6 / 16 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 30 / 52 % | 64 / 95 % | – | 39 / 55 % | 23 / 51 % | 18 / 36 % | 8 / 19 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 25 / 58 % | 50 / 87 % | – | 60 / 73 % | 21 / 52 % | 32 / 55 % | 6 / 19 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 14 / 38 % | 50 / 89 % | – | 57 / 81 % | 10 / 30 % | 13 / 27 % | 4 / 16 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 9 / 30 % | 53 / 87 % | – | 3 / 30 % | 7 / 22 % | 7 / 20 % | 3 / 16 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 11 / 44 % | 49 / 85 % | – | 32 / 64 % | 17 / 45 % | 9 / 33 % | 3 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 10 / 34 % | 45 / 94 % | – | 27 / 53 % | 9 / 34 % | 9 / 31 % | 2 / 13 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 18 / 50 % | 35 / 89 % | – | 40 / 84 % | 13 / 40 % | 16 / 49 % | 6 / 31 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 11 / 39 % | 40 / 79 % | – | 33 / 80 % | 20 / 49 % | 13 / 36 % | 5 / 24 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 21 / 48 % | 19 / 71 % | – | 39 / 78 % | 30 / 60 % | 11 / 28 % | 5 / 19 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 52 % | 34 / 80 % | – | 28 / 53 % | 25 / 54 % | 15 / 33 % | 8 / 25 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 11 / 37 % | 0 / 0 % | – | 34 / 74 % | 15 / 47 % | 9 / 48 % | 3 / 23 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 18 / 36 % | 23 / 61 % | – | 29 / 65 % | 24 / 53 % | 17 / 41 % | 4 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 16 / 44 % | 9 / 52 % | – | 6 / 30 % | 19 / 51 % | 27 / 46 % | 2 / 9 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 27 / 80 % | – | 0 / 0 % | 5 / 15 % | 6 / 16 % | 2 / 9 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 43 % | 26 / 89 % | – | 4 / 34 % | 15 / 42 % | 14 / 39 % | 5 / 25 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 25 / 62 % | – | 23 / 52 % | 7 / 27 % | 4 / 11 % | 1 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 22 / 75 % | – | 0 / 0 % | 6 / 20 % | 5 / 12 % | 1 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 15 / 39 % | 20 / 65 % | – | 8 / 41 % | 7 / 23 % | 8 / 20 % | 2 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 18 / 79 % | – | 0 / 9 % | 7 / 18 % | 6 / 13 % | 1 / 8 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 10 / 39 % | 15 / 85 % | – | 4 / 30 % | 10 / 37 % | 6 / 24 % | 2 / 19 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 10 / 38 % | 14 / 77 % | – | 2 / 17 % | 7 / 26 % | 7 / 18 % | 2 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 56 % | – | 13 / 37 % | 6 / 16 % | 9 / 20 % | 1 / 5 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 12 / 63 % | – | 0 / 0 % | 8 / 30 % | 7 / 16 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 19 % | 10 / 21 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 10 / 57 % | – | 1 / 17 % | 5 / 17 % | 5 / 15 % | 1 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 10 / 68 % | – | 1 / 22 % | 5 / 17 % | 7 / 17 % | 1 / 7 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 27 % | 9 / 23 % | 1 / 5 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 25 % | 6 / 16 % | 1 / 5 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 2 / 18 % | – | 0 / 0 % | 6 / 15 % | 8 / 15 % | 1 / 5 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 6 / 43 % | – | 0 / 15 % | 0 / 0 % | 6 / 19 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 6 / 15 % | 1 / 4 % |
