[English](README.md) · [Deutsch](README.de.md)

# Frontier threats red teaming for AI safety

Bericht Q002630 · Quelle anthropic.com · Datum 2023-07-26 · [Original öffnen](https://www.anthropic.com/news/frontier-threats-red-teaming-for-ai-safety)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic berichtet von einem biologischen Sicherheitstest, bei dem Fachleute ein KI-Modell über mehr als 150 Stunden untersuchten. Das Unternehmen sieht mögliche Missbrauchsrisiken, die heute noch gering, aber wachsend seien, und nennt Training sowie Filter als Gegenmaßnahmen. Die konkreten Befunde bleiben geheim; die Einschätzung eines möglichen Risikohorizonts von zwei bis drei Jahren ist Anthropics eigene Bewertung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 58 % | 98 / 100 % | – | 100 / 100 % | 62 / 82 % | 28 / 55 % | 67 / 82 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 35 / 58 % | 94 / 98 % | – | 97 / 99 % | 55 / 77 % | 49 / 67 % | 61 / 76 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 30 / 54 % | 90 / 98 % | – | 96 / 99 % | 66 / 82 % | 51 / 67 % | 69 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 35 / 60 % | 94 / 100 % | – | 95 / 99 % | 55 / 80 % | 60 / 80 % | 73 / 86 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 44 / 67 % | 78 / 96 % | – | 86 / 97 % | 12 / 28 % | 61 / 81 % | 71 / 84 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 32 / 54 % | 47 / 82 % | – | 84 / 97 % | 62 / 82 % | 20 / 46 % | 72 / 83 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 22 / 54 % | 62 / 92 % | – | 84 / 96 % | 41 / 67 % | 37 / 61 % | 41 / 69 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 24 / 53 % | 79 / 97 % | – | 73 / 91 % | 41 / 63 % | 21 / 42 % | 36 / 50 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 25 / 50 % | 77 / 98 % | – | 47 / 76 % | 37 / 66 % | 21 / 42 % | 36 / 56 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 42 / 62 % | 72 / 97 % | – | 57 / 91 % | 73 / 87 % | 35 / 59 % | 77 / 87 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 15 / 38 % | 5 / 71 % | – | 72 / 89 % | 22 / 51 % | 7 / 27 % | 15 / 41 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 17 / 45 % | 54 / 89 % | – | 71 / 86 % | 22 / 49 % | 10 / 28 % | 15 / 34 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 12 / 81 % | – | 66 / 83 % | 42 / 68 % | 10 / 30 % | 33 / 62 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 18 / 49 % | 63 / 97 % | – | 33 / 65 % | 26 / 52 % | 12 / 32 % | 23 / 48 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 4 / 42 % | – | 37 / 59 % | 42 / 69 % | 12 / 34 % | 56 / 74 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 26 / 83 % | – | 49 / 82 % | 40 / 67 % | 12 / 34 % | 15 / 37 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 16 / 47 % | 47 / 93 % | – | 34 / 81 % | 30 / 64 % | 13 / 41 % | 25 / 57 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 46 / 70 % | 8 / 19 % | 8 / 20 % | 9 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 42 / 77 % | – | 32 / 70 % | 9 / 26 % | 3 / 14 % | 8 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 39 / 59 % | 7 / 16 % | 0 / 0 % | 7 / 13 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 35 / 50 % | 0 / 0 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 12 / 39 % | 31 / 73 % | – | 31 / 65 % | 16 / 38 % | 6 / 17 % | 15 / 35 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 8 / 30 % | 26 / 78 % | – | 7 / 33 % | 18 / 42 % | 5 / 17 % | 11 / 34 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 25 / 83 % | – | 6 / 31 % | 6 / 20 % | 3 / 10 % | 7 / 16 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 22 / 47 % | 12 / 35 % | 6 / 17 % | 11 / 30 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 21 / 70 % | – | 2 / 22 % | 7 / 17 % | 1 / 7 % | 8 / 25 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 30 % | 17 / 52 % | – | 18 / 46 % | 11 / 32 % | 5 / 20 % | 9 / 29 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 37 % | 14 / 56 % | – | 4 / 23 % | 13 / 34 % | 7 / 21 % | 18 / 40 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 16 / 91 % | – | 17 / 62 % | 11 / 32 % | 5 / 16 % | 12 / 27 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 12 / 21 % | 0 / 0 % | – | 17 / 40 % | 12 / 33 % | 5 / 14 % | 14 / 37 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 32 % | 0 / 0 % | – | 13 / 25 % | 8 / 26 % | 5 / 18 % | 14 / 37 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 29 % | 4 / 11 % | 10 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 51 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 6 / 20 % | 11 / 27 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 33 % | 5 / 18 % | 8 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 6 / 19 % | 7 / 20 % | 4 / 13 % | 10 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 25 % | 8 / 65 % | – | 0 / 0 % | 7 / 19 % | 3 / 13 % | 6 / 14 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | – | 1 / 11 % | 5 / 10 % | 2 / 7 % | 7 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 52 % | – | 2 / 14 % | 6 / 16 % | 2 / 10 % | 6 / 15 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 3 / 9 % | 4 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 7 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 11 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
