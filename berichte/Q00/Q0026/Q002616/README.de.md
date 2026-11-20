[English](README.md) · [Deutsch](README.de.md)

# Third-party testing in AI policy

Bericht Q002616 · Quelle anthropic.com · Datum 2024-03-25 · [Original öffnen](https://www.anthropic.com/news/third-party-testing)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic fordert unabhängige, eng begrenzte Prüfungen besonders leistungsfähiger KI-Systeme, weil freiwillige Selbstkontrolle Risiken nach seiner Einschätzung nicht ausreichend erfasst. Verfahren und Standards müssten erst erprobt werden; der Beitrag legt die Position des Unternehmens dar und räumt dessen Eigeninteresse bei der Debatte um offene Modelle ein.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 67 / 84 % | 99 / 100 % | – | 95 / 100 % | 80 / 91 % | 84 / 92 % | 78 / 88 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 50 / 76 % | 68 / 93 % | – | 99 / 100 % | 82 / 92 % | 81 / 91 % | 61 / 80 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 36 / 61 % | 89 / 96 % | – | 98 / 100 % | 72 / 87 % | 62 / 83 % | 49 / 76 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 36 / 67 % | 91 / 97 % | – | 97 / 100 % | 56 / 79 % | 75 / 86 % | 47 / 68 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 43 / 65 % | 96 / 99 % | – | 90 / 99 % | 71 / 87 % | 86 / 93 % | 81 / 91 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 56 / 78 % | 96 / 98 % | – | 94 / 99 % | 76 / 88 % | 90 / 94 % | 75 / 85 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 30 / 57 % | 85 / 94 % | – | 96 / 99 % | 42 / 71 % | 59 / 80 % | 27 / 50 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 65 / 85 % | 91 / 97 % | – | 95 / 99 % | 84 / 92 % | 92 / 96 % | 81 / 91 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 15 / 49 % | 93 / 99 % | – | 72 / 96 % | 38 / 67 % | 46 / 74 % | 22 / 49 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 28 / 61 % | 81 / 94 % | – | 83 / 99 % | 21 / 49 % | 81 / 91 % | 77 / 89 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 16 / 44 % | 80 / 95 % | – | 69 / 89 % | 22 / 44 % | 32 / 58 % | 15 / 33 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 39 % | 52 / 90 % | – | 80 / 93 % | 21 / 48 % | 18 / 65 % | 23 / 49 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 26 / 55 % | 75 / 93 % | – | 61 / 87 % | 38 / 69 % | 31 / 58 % | 30 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 28 / 59 % | 70 / 92 % | – | 73 / 96 % | 35 / 61 % | 55 / 75 % | 49 / 72 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 64 / 88 % | – | 65 / 88 % | 13 / 39 % | 8 / 23 % | 3 / 12 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 15 / 45 % | 63 / 83 % | – | 44 / 70 % | 46 / 69 % | 38 / 56 % | 20 / 35 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 26 / 52 % | 62 / 88 % | – | 53 / 89 % | 54 / 78 % | 19 / 54 % | 32 / 58 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 11 / 35 % | 49 / 89 % | – | 30 / 68 % | 29 / 57 % | 11 / 38 % | 12 / 27 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 40 % | 44 / 83 % | – | 24 / 55 % | 14 / 40 % | 12 / 38 % | 6 / 27 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 14 / 42 % | 6 / 65 % | – | 42 / 64 % | 37 / 68 % | 26 / 67 % | 17 / 42 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 15 / 44 % | 34 / 89 % | – | 39 / 74 % | 20 / 52 % | 14 / 59 % | 6 / 25 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 39 % | 35 / 88 % | – | 30 / 57 % | 14 / 41 % | 36 / 62 % | 17 / 39 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 13 / 41 % | 35 / 76 % | – | 16 / 43 % | 16 / 43 % | 20 / 40 % | 10 / 21 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 33 / 81 % | – | 7 / 28 % | 6 / 15 % | 5 / 14 % | 1 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 36 % | 32 / 74 % | – | 14 / 38 % | 14 / 38 % | 26 / 49 % | 9 / 27 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 31 / 55 % | 5 / 14 % | 0 / 0 % | 2 / 6 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 12 / 38 % | 30 / 87 % | – | 23 / 59 % | 16 / 40 % | 15 / 36 % | 6 / 21 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 25 / 64 % | – | 1 / 20 % | 9 / 34 % | 8 / 25 % | 2 / 13 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 23 / 77 % | – | 0 / 12 % | 5 / 13 % | 6 / 14 % | 2 / 8 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 11 / 23 % | 22 / 65 % | – | 13 / 51 % | 11 / 37 % | 8 / 29 % | 3 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 15 / 42 % | – | 0 / 0 % | 21 / 42 % | 14 / 33 % | 6 / 16 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 21 / 64 % | – | 3 / 20 % | 8 / 26 % | 9 / 23 % | 4 / 10 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 19 / 84 % | – | 2 / 32 % | 7 / 27 % | 5 / 12 % | 3 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 17 / 51 % | – | 0 / 0 % | 11 / 40 % | 14 / 37 % | 9 / 32 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 31 % | 16 / 83 % | – | 6 / 25 % | 9 / 30 % | 6 / 19 % | 5 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 34 % | 9 / 63 % | – | 2 / 20 % | 14 / 41 % | 14 / 34 % | 8 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 13 / 47 % | – | 0 / 0 % | 8 / 24 % | 9 / 23 % | 4 / 14 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 1 / 5 % | 6 / 15 % | 7 / 16 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 7 / 28 % | 6 / 14 % | 6 / 14 % | 3 / 13 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 5 / 42 % | – | 0 / 0 % | 6 / 18 % | 7 / 15 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 5 / 16 % | 1 / 5 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 12 % | 0 / 0 % |
