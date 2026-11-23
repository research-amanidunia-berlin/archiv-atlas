[English](README.md) · [Deutsch](README.de.md)

# An Opinionated Evals Reading List

Bericht Q001095 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/science/an-opinionated-evals-reading-list)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Apollo Research stellt eine subjektive, ausdrücklich nicht vollständige Leseliste zu LLM-Evaluationen, Benchmarks, Agenten, Sicherheit und verwandten Forschungsfeldern vor. Die Kommentare heben methodische Grenzen wie mögliche Benchmark-Sättigung, Prompt-Empfindlichkeit und die Einschränkungen von Black-Box-Prüfungen hervor; die Empfehlungen sind persönliche Einschätzungen, keine Ergebnisse einer neuen systematischen Studie.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 28 / 58 % | 45 / 87 % | – | 69 / 87 % | 41 / 70 % | 75 / 88 % | 15 / 57 % | 17 / 42 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 33 / 59 % | 74 / 99 % | – | 54 / 81 % | 28 / 58 % | 70 / 86 % | 20 / 71 % | 25 / 53 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 34 / 70 % | 46 / 83 % | – | 62 / 84 % | 26 / 58 % | 67 / 84 % | 25 / 78 % | 26 / 54 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 19 / 49 % | 51 / 83 % | – | 56 / 79 % | 9 / 21 % | 59 / 77 % | 9 / 35 % | 24 / 50 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 52 / 91 % | – | 17 / 44 % | 5 / 13 % | 24 / 44 % | 2 / 14 % | 24 / 48 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 24 / 53 % | 47 / 92 % | – | 51 / 77 % | 11 / 33 % | 23 / 54 % | 6 / 32 % | 13 / 36 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 24 / 55 % | 41 / 82 % | – | 46 / 72 % | 13 / 31 % | 49 / 65 % | 7 / 32 % | 16 / 39 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 18 / 48 % | 46 / 74 % | – | 45 / 72 % | 6 / 16 % | 38 / 58 % | 8 / 29 % | 10 / 28 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 41 % | 44 / 85 % | – | 21 / 55 % | 1 / 10 % | 26 / 53 % | 2 / 16 % | 15 / 44 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 24 / 51 % | 22 / 79 % | – | 38 / 69 % | 8 / 27 % | 44 / 75 % | 9 / 40 % | 28 / 53 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 13 / 45 % | 43 / 95 % | – | 31 / 63 % | 5 / 17 % | 21 / 52 % | 5 / 28 % | 12 / 37 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 27 / 56 % | 13 / 89 % | – | 42 / 73 % | 7 / 25 % | 31 / 65 % | 5 / 39 % | 15 / 39 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 15 / 39 % | 21 / 48 % | – | 39 / 68 % | 9 / 23 % | 39 / 63 % | 5 / 36 % | 11 / 30 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 16 / 42 % | 36 / 72 % | – | 21 / 51 % | 6 / 17 % | 18 / 45 % | 3 / 15 % | 13 / 37 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 18 / 50 % | 3 / 10 % | 34 / 63 % | 4 / 20 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 31 / 70 % | – | 11 / 37 % | 2 / 8 % | 12 / 29 % | 1 / 7 % | 6 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 40 % | 24 / 54 % | – | 12 / 36 % | 3 / 12 % | 14 / 40 % | 1 / 9 % | 9 / 29 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 15 / 45 % | 24 / 57 % | – | 14 / 37 % | 5 / 15 % | 15 / 39 % | 3 / 19 % | 21 / 44 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 23 / 67 % | – | 8 / 24 % | 2 / 9 % | 9 / 21 % | 1 / 6 % | 11 / 31 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 19 / 50 % | – | 22 / 47 % | 2 / 6 % | 12 / 24 % | 1 / 5 % | 15 / 38 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 21 / 51 % | – | 9 / 27 % | 3 / 7 % | 11 / 24 % | 0 / 4 % | 12 / 35 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 17 / 47 % | 4 / 42 % | – | 20 / 52 % | 6 / 17 % | 17 / 37 % | 4 / 20 % | 6 / 22 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 4 / 46 % | – | 6 / 16 % | 0 / 0 % | 6 / 13 % | 0 / 3 % | 17 / 47 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 17 / 42 % | – | 7 / 21 % | 1 / 7 % | 7 / 20 % | 1 / 6 % | 13 / 35 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 3 / 29 % | – | 13 / 43 % | 2 / 9 % | 15 / 38 % | 1 / 8 % | 9 / 28 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 14 / 44 % | – | 7 / 22 % | 0 / 2 % | 7 / 17 % | 0 / 4 % | 9 / 27 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 10 / 25 % | 0 / 2 % | 10 / 24 % | 0 / 3 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 10 / 27 % | 1 / 6 % | 7 / 18 % | 0 / 3 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 1 / 6 % | 5 / 10 % | 0 / 1 % | 9 / 27 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 51 % | – | 9 / 30 % | 1 / 8 % | 6 / 18 % | 1 / 8 % | 8 / 28 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 8 / 24 % | 1 / 6 % | 5 / 14 % | 0 / 4 % | 3 / 18 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | – | 8 / 22 % | 1 / 4 % | 6 / 16 % | 0 / 2 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 8 / 51 % | – | 6 / 18 % | 2 / 8 % | 6 / 15 % | 0 / 2 % | 8 / 26 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 8 / 27 % | 1 / 5 % | 8 / 17 % | 0 / 0 % | 8 / 22 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 5 / 14 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 1 / 3 % | 7 / 14 % | 0 / 2 % | 4 / 16 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | 0 / 2 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 5 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 3 / 14 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
