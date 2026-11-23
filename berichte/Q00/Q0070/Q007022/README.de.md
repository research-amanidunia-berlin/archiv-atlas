[English](README.md) · [Deutsch](README.de.md)

# Introducing GPT-5.5

Bericht Q007022 · Quelle openai.com · Datum 2026-04-23 · [Original öffnen](https://openai.com/index/introducing-gpt-5-5/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI zufolge verbessert GPT‑5.5 die Leistung bei vielen Aufgaben in Programmierung, Wissensarbeit und Forschung und arbeitet dabei effizienter; Benchmarks, interne Fälle und ausgewählte Testerberichte dienen als Belege. Die Ergebnisse sind laut Beitrag durch Forschungsbedingungen, interne Tests und mögliche Memorierung bei einem Benchmark eingeschränkt; außerdem widersprechen sich die Angaben zur API-Verfügbarkeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 35 / 55 % | 97 / 100 % | 99 / 100 % | 68 / 84 % | 15 / 35 % | 62 / 79 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 29 / 48 % | 97 / 98 % | 95 / 97 % | 64 / 81 % | 20 / 36 % | 64 / 76 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 51 / 68 % | 92 / 97 % | 97 / 99 % | 40 / 62 % | 31 / 51 % | 78 / 87 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 45 % | 97 / 100 % | 92 / 96 % | 27 / 52 % | 12 / 23 % | 38 / 61 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 53 % | 92 / 99 % | 95 / 97 % | 51 / 76 % | 31 / 52 % | 65 / 83 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 18 / 33 % | 88 / 98 % | 92 / 95 % | 68 / 84 % | 18 / 34 % | 63 / 77 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 16 / 37 % | 80 / 95 % | 88 / 92 % | 31 / 59 % | 11 / 26 % | 33 / 59 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 33 / 69 % | 83 / 91 % | 8 / 22 % | 0 / 0 % | 6 / 10 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 14 / 31 % | 53 / 88 % | 80 / 86 % | 11 / 31 % | 2 / 8 % | 11 / 23 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 32 / 49 % | 60 / 89 % | 78 / 92 % | 62 / 80 % | 9 / 24 % | 49 / 67 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 16 / 75 % | 77 / 87 % | 55 / 76 % | 8 / 20 % | 11 / 24 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 31 / 51 % | 63 / 90 % | 76 / 92 % | 58 / 77 % | 10 / 27 % | 45 / 64 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 68 / 80 % | 13 / 39 % | 3 / 11 % | 9 / 24 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 61 / 88 % | 64 / 78 % | 12 / 36 % | 1 / 7 % | 11 / 27 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 41 / 85 % | 60 / 73 % | 11 / 29 % | 0 / 2 % | 6 / 15 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 36 / 75 % | 58 / 77 % | 9 / 27 % | 2 / 7 % | 9 / 15 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 29 / 50 % | 49 / 86 % | 26 / 55 % | 53 / 77 % | 8 / 20 % | 30 / 58 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 29 / 85 % | 51 / 71 % | 24 / 55 % | 4 / 15 % | 14 / 46 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 13 / 33 % | 47 / 87 % | 50 / 73 % | 40 / 64 % | 13 / 25 % | 17 / 35 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 17 / 45 % | 0 / 0 % | 48 / 63 % | 22 / 49 % | 2 / 9 % | 10 / 23 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 16 / 38 % | 42 / 67 % | 8 / 29 % | 20 / 44 % | 9 / 23 % | 25 / 44 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 39 / 71 % | 13 / 22 % | 12 / 33 % | 3 / 10 % | 8 / 17 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 37 / 59 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 6 / 13 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 36 / 81 % | 0 / 0 % | 9 / 23 % | 3 / 9 % | 6 / 14 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 33 / 78 % | 27 / 46 % | 15 / 34 % | 7 / 19 % | 15 / 30 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 32 / 85 % | 15 / 30 % | 9 / 25 % | 2 / 9 % | 7 / 17 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 4 / 44 % | 31 / 48 % | 15 / 41 % | 5 / 14 % | 20 / 41 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 22 / 53 % | 0 / 0 % | 0 / 0 % | 12 / 37 % | 1 / 5 % | 10 / 45 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 11 / 86 % | 0 / 0 % | 6 / 15 % | 0 / 3 % | 6 / 11 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 9 / 20 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 1 / 2 % | 6 / 14 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 2 % | 4 / 10 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 0 / 1 % | 8 / 13 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 5 / 17 % | 7 / 18 % | 1 / 6 % | 7 / 13 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 1 / 3 % | 5 / 9 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 1 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 2 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 1 % | 5 / 9 % | – | – |
