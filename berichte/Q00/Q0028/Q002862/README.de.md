[English](README.md) · [Deutsch](README.de.md)

# The ethics of advanced AI assistants

Bericht Q002862 · Quelle deepmind.google · Datum 2024-04-19 · [Original öffnen](https://deepmind.google/blog/the-ethics-of-advanced-ai-assistants/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht fasst ein vorausschauendes Forschungspapier über Chancen und Risiken fortgeschrittener KI-Assistenten zusammen: Sie könnten viele Lebensbereiche beeinflussen, zugleich aber durch Autonomie, überzeugende Kommunikation und Missbrauch neue Gefahren schaffen. Die Autorinnen und Autoren fordern Wertausrichtung, Schutz der Selbstbestimmung, breiten Zugang, koordinierte Zusammenarbeit und umfassendere Bewertungen; die Aussagen beschreiben mögliche Folgen und Empfehlungen, keine konkreten empirischen Ergebnisse.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 44 / 67 % | 98 / 100 % | 64 / 79 % | 98 / 99 % | 61 / 82 % | 56 / 75 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 28 / 55 % | 96 / 100 % | 22 / 66 % | 91 / 99 % | 35 / 66 % | 37 / 76 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 12 / 43 % | 47 / 95 % | 7 / 32 % | 85 / 95 % | 17 / 48 % | 22 / 61 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 36 / 60 % | 81 / 98 % | 41 / 81 % | 79 / 96 % | 55 / 81 % | 50 / 82 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 22 / 47 % | 77 / 99 % | 6 / 29 % | 68 / 93 % | 25 / 60 % | 19 / 64 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 21 / 53 % | 56 / 91 % | 30 / 77 % | 55 / 93 % | 41 / 70 % | 30 / 67 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 19 / 51 % | 37 / 97 % | 15 / 53 % | 43 / 94 % | 23 / 60 % | 15 / 61 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 42 / 84 % | 1 / 7 % | 6 / 50 % | 7 / 21 % | 6 / 13 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 10 / 38 % | 19 / 93 % | 6 / 32 % | 37 / 88 % | 15 / 49 % | 9 / 49 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 9 / 36 % | 35 / 87 % | 1 / 12 % | 5 / 41 % | 12 / 37 % | 8 / 33 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 39 % | 33 / 96 % | 0 / 5 % | 7 / 38 % | 7 / 25 % | 5 / 12 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 18 / 53 % | 32 / 96 % | 8 / 37 % | 25 / 74 % | 14 / 54 % | 15 / 58 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 20 / 50 % | 17 / 94 % | 8 / 37 % | 16 / 64 % | 30 / 67 % | 26 / 67 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 10 / 44 % | 28 / 89 % | 0 / 3 % | 0 / 9 % | 5 / 15 % | 5 / 12 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 9 / 40 % | 28 / 92 % | 3 / 22 % | 6 / 65 % | 14 / 46 % | 10 / 48 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 9 / 43 % | 27 / 77 % | 7 / 37 % | 21 / 78 % | 25 / 56 % | 11 / 57 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 40 % | 27 / 95 % | 2 / 12 % | 2 / 36 % | 11 / 34 % | 11 / 40 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 10 / 31 % | 26 / 79 % | 3 / 13 % | 3 / 40 % | 12 / 36 % | 6 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 18 / 45 % | 13 / 91 % | 8 / 31 % | 17 / 52 % | 20 / 48 % | 25 / 53 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 10 / 37 % | 20 / 87 % | 1 / 10 % | 13 / 54 % | 7 / 26 % | 9 / 30 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 31 % | 20 / 93 % | 1 / 9 % | 0 / 20 % | 6 / 17 % | 6 / 19 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 17 / 49 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 5 / 16 % | 5 / 13 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 7 / 39 % | 15 / 95 % | 1 / 10 % | 10 / 69 % | 10 / 38 % | 5 / 27 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 14 / 70 % | 0 / 2 % | 3 / 29 % | 7 / 21 % | 2 / 7 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 14 / 26 % | 5 / 85 % | 1 / 6 % | 3 / 42 % | 7 / 26 % | 5 / 18 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 13 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 33 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 5 / 13 % | 6 / 13 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 12 / 37 % | 5 / 92 % | 1 / 9 % | 1 / 22 % | 7 / 25 % | 5 / 14 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 10 / 54 % | 0 / 0 % | 1 / 8 % | 0 / 0 % | 6 / 26 % | 5 / 15 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 7 / 67 % | 0 / 5 % | 3 / 33 % | 8 / 29 % | 5 / 17 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 7 / 33 % | 0 / 0 % | 0 / 2 % | 1 / 14 % | 5 / 13 % | 4 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 5 / 77 % | 0 / 3 % | 0 / 0 % | 7 / 22 % | 6 / 17 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 7 / 35 % | 2 / 73 % | 0 / 4 % | 1 / 12 % | 6 / 17 % | 5 / 14 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 6 / 11 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 14 % | 5 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 5 / 65 % | 0 / 3 % | 1 / 18 % | 0 / 0 % | 5 / 15 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 96 % | 0 / 0 % | 0 / 5 % | 5 / 14 % | 5 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 4 / 94 % | 0 / 1 % | 0 / 0 % | 5 / 12 % | 4 / 8 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 2 / 7 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % |
