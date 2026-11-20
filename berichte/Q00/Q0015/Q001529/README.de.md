[English](README.md) · [Deutsch](README.de.md)

# 2023: A Year of Groundbreaking Advances in AI and Computing

Bericht Q001529 · Quelle deepmind.google · Datum 2023-12-22 · [Original öffnen](https://deepmind.google/blog/2023-a-year-of-groundbreaking-advances-in-ai-and-computing/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Googles Rückblick stellt KI-Produkte wie Gemini und PaLM 2 sowie Fortschritte in Forschung, Algorithmen, Klima, Medizin und verantwortungsvoller KI vor. Die Leistungswerte und Projektergebnisse sind Unternehmensangaben zu konkreten Tests oder Kooperationen; einige Vorhaben sind vorläufig, und der Beitrag bezeichnet seine Auswahl selbst als kleinen Ausschnitt der Jahresarbeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 27 / 48 % | 86 / 96 % | – | 97 / 99 % | 49 / 75 % | 63 / 81 % | 18 / 43 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 45 % | 54 / 87 % | – | 95 / 97 % | 48 / 74 % | 54 / 76 % | 18 / 41 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 36 / 56 % | 88 / 99 % | – | 95 / 98 % | 62 / 82 % | 61 / 83 % | 17 / 43 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 27 / 47 % | 94 / 99 % | – | 46 / 67 % | 59 / 80 % | 63 / 78 % | 28 / 53 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 48 / 63 % | 92 / 97 % | – | 94 / 97 % | 84 / 90 % | 85 / 91 % | 77 / 88 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 18 / 41 % | 85 / 99 % | – | 90 / 96 % | 19 / 46 % | 13 / 40 % | 6 / 20 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 32 / 57 % | 72 / 86 % | – | 84 / 94 % | 68 / 81 % | 73 / 85 % | 27 / 48 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 45 % | 48 / 90 % | – | 83 / 93 % | 28 / 55 % | 28 / 52 % | 11 / 33 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 11 / 24 % | 81 / 94 % | – | 12 / 33 % | 12 / 30 % | 14 / 30 % | 5 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 43 / 78 % | – | 73 / 91 % | 9 / 29 % | 9 / 18 % | 1 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 41 % | 69 / 95 % | – | 72 / 86 % | 25 / 52 % | 20 / 43 % | 2 / 15 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 10 / 48 % | – | 71 / 85 % | 38 / 62 % | 13 / 35 % | 7 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 20 / 36 % | 63 / 90 % | – | 70 / 87 % | 25 / 53 % | 23 / 63 % | 7 / 27 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 21 / 48 % | 59 / 97 % | – | 64 / 86 % | 26 / 58 % | 21 / 60 % | 5 / 23 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 24 / 43 % | 46 / 83 % | – | 61 / 77 % | 32 / 58 % | 23 / 47 % | 7 / 25 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 46 / 78 % | – | 21 / 57 % | 34 / 59 % | 27 / 48 % | 4 / 17 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 19 / 53 % | 45 / 90 % | – | 33 / 66 % | 21 / 47 % | 19 / 38 % | 6 / 15 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 11 / 36 % | 40 / 89 % | – | 3 / 27 % | 9 / 28 % | 13 / 32 % | 3 / 14 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 35 / 60 % | – | 10 / 29 % | 13 / 32 % | 10 / 21 % | 4 / 12 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 28 / 77 % | – | 33 / 63 % | 16 / 39 % | 12 / 27 % | 4 / 14 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 30 % | 18 / 54 % | – | 33 / 59 % | 17 / 43 % | 13 / 42 % | 5 / 21 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 30 / 63 % | – | 20 / 47 % | 10 / 31 % | 5 / 19 % | 1 / 7 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 30 / 85 % | – | 0 / 0 % | 6 / 15 % | 7 / 13 % | 1 / 5 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 12 / 31 % | 27 / 75 % | – | 14 / 53 % | 21 / 49 % | 13 / 40 % | 3 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 44 % | 0 / 0 % | – | 25 / 36 % | 11 / 35 % | 7 / 25 % | 1 / 10 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 23 / 47 % | – | 0 / 0 % | 10 / 26 % | 10 / 25 % | 1 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 51 % | 10 / 24 % | 4 / 17 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 34 % | 9 / 84 % | – | 0 / 0 % | 18 / 46 % | 15 / 34 % | 5 / 17 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 34 % | 11 / 81 % | – | 17 / 42 % | 13 / 35 % | 8 / 22 % | 2 / 12 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 28 % | 0 / 9 % | – | 0 / 0 % | 14 / 44 % | 7 / 17 % | 3 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 14 / 46 % | – | 0 / 0 % | 10 / 28 % | 6 / 17 % | 1 / 5 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 3 / 14 % | 13 / 30 % | 6 / 17 % | 3 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 11 / 32 % | 1 / 24 % | – | 9 / 33 % | 9 / 28 % | 10 / 29 % | 3 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 7 / 51 % | – | 0 / 0 % | 11 / 27 % | 9 / 17 % | 3 / 9 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 29 % | 5 / 13 % | 2 / 8 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 15 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 2 / 11 % | 8 / 19 % | 5 / 12 % | 2 / 8 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 14 % | 7 / 13 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 29 % | – | 0 / 0 % | 6 / 15 % | 7 / 16 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 6 / 12 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 5 / 23 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 5 / 10 % | 0 / 3 % |
