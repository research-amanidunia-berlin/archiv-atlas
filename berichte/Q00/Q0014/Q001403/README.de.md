[English](README.md) · [Deutsch](README.de.md)

# Technical Innovations for AI Policy 2026: What We Heard, and What It Means

Bericht Q001403 · Quelle far.ai · Datum 2026-08-19 · [Original öffnen](https://www.far.ai/blog/technical-innovations-for-ai-policy-2026)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht schildert, wie die TIAP-Konferenz 2026 Lücken bei KI-Evaluierungen, Modellversionsnachweisen, Sicherheitsstandards und der Governance von Agenten und ihren Interaktionen hervorhob. Die genannten Risiken und Messwerte beruhen teils auf Vorträgen sowie vorläufigen oder simulierten Tests; als zentrale Aufgabe benennt der Beitrag eine engere Zusammenarbeit von Forschung und Politik.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 76 / 87 % | 100 / 100 % | 100 / 100 % | 91 / 95 % | 86 / 93 % | 89 / 94 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 50 / 72 % | 85 / 98 % | 99 / 100 % | 72 / 86 % | 48 / 71 % | 83 / 90 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 42 / 62 % | 99 / 100 % | 99 / 100 % | 68 / 85 % | 76 / 90 % | 79 / 90 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 34 / 58 % | 96 / 99 % | 99 / 100 % | 70 / 86 % | 55 / 81 % | 70 / 87 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 42 / 69 % | 34 / 93 % | 98 / 100 % | 66 / 85 % | 33 / 63 % | 65 / 85 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 43 / 71 % | 71 / 93 % | 96 / 99 % | 43 / 67 % | 71 / 88 % | 82 / 91 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 23 / 48 % | 50 / 89 % | 96 / 98 % | 63 / 81 % | 28 / 52 % | 35 / 59 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 29 / 52 % | 91 / 98 % | 95 / 98 % | 57 / 77 % | 50 / 71 % | 76 / 87 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 31 / 52 % | 50 / 78 % | 92 / 97 % | 32 / 61 % | 17 / 38 % | 35 / 49 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 28 / 54 % | 81 / 96 % | 91 / 96 % | 64 / 81 % | 35 / 64 % | 48 / 67 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 37 % | 26 / 92 % | 91 / 97 % | 19 / 47 % | 8 / 27 % | 21 / 40 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 53 % | 61 / 89 % | 88 / 94 % | 66 / 83 % | 47 / 70 % | 54 / 72 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 29 / 58 % | 84 / 99 % | 84 / 92 % | 55 / 77 % | 35 / 60 % | 71 / 85 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 26 / 55 % | 60 / 88 % | 68 / 93 % | 47 / 71 % | 18 / 48 % | 40 / 65 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 24 / 56 % | 68 / 98 % | 61 / 87 % | 37 / 64 % | 20 / 53 % | 29 / 53 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 30 / 52 % | 60 / 95 % | 53 / 89 % | 56 / 78 % | 28 / 57 % | 67 / 82 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 23 / 50 % | 67 / 98 % | 52 / 78 % | 30 / 55 % | 10 / 37 % | 36 / 56 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 20 / 35 % | 56 / 91 % | 67 / 87 % | 30 / 60 % | 10 / 28 % | 25 / 51 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 21 / 49 % | 65 / 98 % | 60 / 85 % | 42 / 68 % | 15 / 37 % | 26 / 55 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 27 / 45 % | 51 / 83 % | 24 / 39 % | 61 / 80 % | 37 / 53 % | 64 / 75 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 33 / 49 % | 58 / 89 % | 35 / 50 % | 51 / 74 % | 48 / 62 % | 50 / 67 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 26 / 55 % | 53 / 92 % | 57 / 81 % | 38 / 64 % | 16 / 42 % | 34 / 63 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 38 % | 53 / 90 % | 29 / 76 % | 32 / 60 % | 15 / 45 % | 22 / 49 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 33 / 56 % | 50 / 78 % | 53 / 68 % | 23 / 48 % | 14 / 32 % | 30 / 47 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 19 / 41 % | 53 / 90 % | 50 / 77 % | 33 / 62 % | 14 / 43 % | 37 / 66 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 32 % | 45 / 89 % | 18 / 45 % | 10 / 25 % | 4 / 21 % | 12 / 26 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 34 % | 40 / 80 % | 0 / 0 % | 14 / 35 % | 11 / 32 % | 24 / 49 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 31 % | 35 / 95 % | 32 / 58 % | 15 / 37 % | 9 / 32 % | 16 / 42 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 39 % | 34 / 94 % | 9 / 35 % | 18 / 43 % | 11 / 33 % | 22 / 45 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 20 / 49 % | 32 / 96 % | 26 / 55 % | 17 / 43 % | 11 / 31 % | 12 / 28 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 10 / 43 % | 32 / 55 % | 8 / 17 % | 0 / 0 % | 9 / 14 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 31 / 93 % | 0 / 6 % | 9 / 21 % | 4 / 16 % | 14 / 25 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 15 / 83 % | 10 / 36 % | 25 / 54 % | 6 / 22 % | 26 / 47 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 18 / 43 % | 26 / 69 % | 19 / 38 % | 16 / 37 % | 7 / 24 % | 22 / 42 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 25 / 78 % | 1 / 12 % | 20 / 42 % | 6 / 15 % | 14 / 29 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 24 / 84 % | 0 / 0 % | 11 / 25 % | 7 / 23 % | 11 / 23 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 15 / 35 % | 19 / 71 % | 4 / 17 % | 11 / 27 % | 5 / 21 % | 20 / 38 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 4 / 40 % | 0 / 0 % | 15 / 39 % | 6 / 26 % | 17 / 39 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 10 / 21 % | 5 / 86 % | 1 / 16 % | 11 / 31 % | 5 / 22 % | 15 / 32 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 2 / 33 % | 0 / 0 % | 8 / 19 % | 3 / 13 % | 15 / 31 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | 14 / 27 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 31 % | 6 / 44 % | 0 / 3 % | 9 / 20 % | 6 / 14 % | 14 / 26 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 10 / 32 % | 2 / 40 % | 0 / 0 % | 12 / 28 % | 5 / 16 % | 12 / 22 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 4 / 31 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 12 / 20 % | – | – |
