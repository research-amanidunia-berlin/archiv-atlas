[English](README.md) · [Deutsch](README.de.md)

# AI Safety Institute approach to evaluations

Bericht Q002335 · Quelle aisi.gov.uk · Datum 2024-02-09 · [Original öffnen](https://www.aisi.gov.uk/blog/our-approach-to-evaluations)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt AISI-Evaluationen zu Missbrauch, gesellschaftlichen Auswirkungen, autonomen Agenten und Schutzmaßnahmen. Frühe Tests zeigen mögliche Risiken und Verzerrungen, sind laut Institut aber vorläufige, begrenzte Untersuchungen und erlauben keine umfassenden Sicherheitsurteile oder verlässlichen Aussagen zur Häufigkeit im realen Einsatz.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 74 / 87 % | 95 / 96 % | – | 100 / 100 % | 92 / 95 % | 79 / 89 % | 88 / 93 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 30 / 55 % | 98 / 99 % | – | 99 / 100 % | 59 / 78 % | 36 / 59 % | 54 / 70 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 60 / 80 % | 96 / 99 % | – | 97 / 99 % | 86 / 93 % | 60 / 79 % | 89 / 94 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 28 / 53 % | 96 / 99 % | – | 97 / 99 % | 44 / 74 % | 47 / 73 % | 60 / 79 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 54 / 75 % | 93 / 99 % | – | 96 / 99 % | 20 / 48 % | 72 / 87 % | 85 / 92 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 43 / 67 % | 80 / 95 % | – | 96 / 99 % | 75 / 87 % | 26 / 55 % | 72 / 83 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 23 / 49 % | 94 / 99 % | – | 74 / 87 % | 60 / 81 % | 33 / 61 % | 63 / 78 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 44 / 63 % | 94 / 98 % | – | 94 / 97 % | 66 / 83 % | 27 / 51 % | 55 / 72 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 13 / 43 % | 72 / 94 % | – | 91 / 96 % | 38 / 64 % | 9 / 23 % | 32 / 48 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 34 / 56 % | 83 / 98 % | – | 91 / 98 % | 59 / 81 % | 38 / 68 % | 54 / 76 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 38 / 62 % | 80 / 95 % | – | 89 / 95 % | 44 / 72 % | 43 / 63 % | 40 / 56 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 30 / 61 % | 88 / 95 % | – | 89 / 97 % | 37 / 58 % | 33 / 57 % | 56 / 72 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 20 / 50 % | 39 / 88 % | – | 87 / 97 % | 34 / 65 % | 18 / 43 % | 30 / 67 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 18 / 47 % | 85 / 98 % | – | 34 / 65 % | 58 / 79 % | 22 / 50 % | 58 / 73 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 18 / 47 % | 78 / 95 % | – | 72 / 88 % | 38 / 65 % | 17 / 38 % | 35 / 61 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 17 / 35 % | 70 / 86 % | – | 75 / 90 % | 21 / 51 % | 6 / 16 % | 11 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 25 / 51 % | 45 / 82 % | – | 74 / 92 % | 55 / 78 % | 17 / 43 % | 25 / 51 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 10 / 32 % | 74 / 94 % | – | 42 / 79 % | 17 / 42 % | 8 / 29 % | 18 / 50 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 27 / 52 % | 51 / 95 % | – | 64 / 81 % | 66 / 83 % | 27 / 55 % | 73 / 85 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 46 / 80 % | – | 72 / 85 % | 10 / 29 % | 4 / 14 % | 12 / 20 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 14 / 44 % | 67 / 98 % | – | 23 / 74 % | 35 / 68 % | 17 / 36 % | 34 / 65 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 63 / 94 % | – | 11 / 39 % | 11 / 27 % | 1 / 8 % | 15 / 31 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 29 % | 61 / 97 % | – | 36 / 65 % | 12 / 31 % | 6 / 19 % | 9 / 22 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 10 / 31 % | 51 / 96 % | – | 55 / 91 % | 27 / 55 % | 9 / 26 % | 14 / 40 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 36 % | 43 / 90 % | – | 2 / 25 % | 14 / 39 % | 9 / 26 % | 25 / 47 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 39 / 62 % | – | 7 / 31 % | 8 / 19 % | 6 / 14 % | 8 / 19 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 38 / 70 % | – | 0 / 0 % | 10 / 33 % | 1 / 7 % | 12 / 27 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 34 % | 24 / 55 % | – | 7 / 23 % | 28 / 57 % | 13 / 28 % | 35 / 54 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 9 / 27 % | 33 / 94 % | – | 17 / 42 % | 15 / 40 % | 8 / 27 % | 19 / 37 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 13 / 46 % | – | 0 / 0 % | 10 / 32 % | 5 / 17 % | 27 / 47 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 39 % | 1 / 5 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 20 / 89 % | – | 0 / 0 % | 5 / 12 % | 1 / 5 % | 9 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 16 / 47 % | – | 10 / 34 % | 10 / 32 % | 2 / 8 % | 10 / 25 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 8 / 18 % | 9 / 47 % | – | 6 / 22 % | 12 / 39 % | 3 / 12 % | 15 / 27 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 8 / 89 % | – | 1 / 15 % | 7 / 25 % | 2 / 10 % | 12 / 25 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 9 / 40 % | – | 0 / 0 % | 12 / 42 % | 3 / 14 % | 12 / 30 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 3 / 20 % | – | 4 / 16 % | 11 / 38 % | 1 / 7 % | 10 / 37 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 11 / 52 % | – | 1 / 9 % | 7 / 19 % | 1 / 5 % | 10 / 20 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 1 / 5 % | 10 / 17 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 1 % | 10 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 8 / 23 % | 2 / 21 % | – | 0 / 0 % | 7 / 19 % | 3 / 15 % | 9 / 16 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 2 / 7 % | 8 / 15 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 3 / 9 % | 7 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 3 / 8 % | 7 / 13 % |
