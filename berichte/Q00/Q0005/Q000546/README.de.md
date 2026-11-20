[English](README.md) · [Deutsch](README.de.md)

# GPT-6 Cyber System Card

Bericht Q000546 · Quelle deploymentsafety.openai.com · Datum 2026-11-05 · [Original öffnen](https://deploymentsafety.openai.com/gpt-6-cyber)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI zufolge verbessert GPT-6 Cyber die Leistung bei autorisierten Sicherheitsaufgaben deutlich und erzielt in mehreren Cyber-Benchmarks höhere Werte als GPT-6 Astra. Der Bericht nennt zugleich Schwächen bei einzelnen Sicherheits- und Ausrichtungsprüfungen, beschreibt Zugangsbeschränkungen und Schutzmechanismen und weist auf schwierige, ungelöste Tests sowie Grenzen der Benchmark-Vergleichbarkeit hin.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 71 / 80 % | 100 / 100 % | 96 / 98 % | 100 / 100 % | 80 / 87 % | 90 / 93 % | 78 / 87 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 56 / 71 % | 95 / 99 % | 92 / 96 % | 100 / 100 % | 90 / 94 % | 88 / 93 % | 68 / 83 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 77 / 86 % | 100 / 100 % | 97 / 98 % | 100 / 100 % | 94 / 96 % | 90 / 93 % | 76 / 86 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 51 / 66 % | 87 / 97 % | 68 / 81 % | 99 / 100 % | 90 / 94 % | 91 / 94 % | 76 / 87 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 54 / 70 % | 99 / 100 % | 84 / 91 % | 99 / 100 % | 86 / 92 % | 80 / 88 % | 63 / 79 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 42 / 62 % | 97 / 98 % | 71 / 80 % | 98 / 99 % | 87 / 93 % | 72 / 83 % | 38 / 58 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 48 / 65 % | 98 / 100 % | 75 / 86 % | 96 / 97 % | 78 / 88 % | 88 / 93 % | 74 / 85 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 46 / 64 % | 97 / 100 % | 37 / 53 % | 73 / 88 % | 74 / 86 % | 60 / 75 % | 28 / 49 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 50 / 64 % | 64 / 99 % | 93 / 95 % | 96 / 98 % | 85 / 92 % | 91 / 94 % | 68 / 81 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 52 / 94 % | 1 / 4 % | 95 / 98 % | 14 / 34 % | 9 / 15 % | 4 / 11 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 31 / 48 % | 80 / 97 % | 11 / 27 % | 92 / 95 % | 48 / 70 % | 39 / 56 % | 13 / 24 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 39 / 57 % | 41 / 89 % | 38 / 56 % | 90 / 95 % | 75 / 87 % | 27 / 44 % | 28 / 46 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 68 / 92 % | 4 / 11 % | 89 / 93 % | 14 / 31 % | 12 / 23 % | 1 / 4 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 33 / 55 % | 49 / 93 % | 6 / 14 % | 26 / 40 % | 64 / 82 % | 73 / 83 % | 39 / 58 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 43 / 60 % | 35 / 73 % | 27 / 50 % | 72 / 88 % | 71 / 86 % | 44 / 58 % | 15 / 33 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 17 / 30 % | 0 / 0 % | 1 / 6 % | 68 / 81 % | 14 / 35 % | 8 / 15 % | 3 / 8 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 10 / 42 % | 0 / 0 % | 63 / 76 % | 8 / 18 % | 8 / 12 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 51 / 90 % | 7 / 14 % | 24 / 31 % | 34 / 54 % | 23 / 35 % | 6 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 48 / 77 % | 9 / 15 % | 47 / 64 % | 36 / 60 % | 22 / 33 % | 8 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 19 / 42 % | 14 / 49 % | 18 / 30 % | 0 / 0 % | 44 / 67 % | 27 / 41 % | 16 / 31 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 40 / 85 % | 0 / 2 % | 42 / 58 % | 11 / 24 % | 11 / 19 % | 4 / 10 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 28 / 69 % | 3 / 9 % | 41 / 58 % | 24 / 41 % | 13 / 23 % | 6 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 41 / 74 % | 2 / 6 % | 0 / 0 % | 20 / 40 % | 15 / 27 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 6 / 60 % | 10 / 21 % | 40 / 59 % | 29 / 55 % | 28 / 44 % | 10 / 19 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 6 / 46 % | 0 / 0 % | 40 / 49 % | 8 / 18 % | 5 / 10 % | 1 / 5 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 13 / 20 % | 38 / 96 % | 3 / 10 % | 7 / 30 % | 16 / 33 % | 10 / 21 % | 6 / 15 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 19 / 75 % | 9 / 16 % | 33 / 51 % | 33 / 56 % | 24 / 39 % | 2 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 26 / 63 % | 7 / 11 % | 0 / 0 % | 13 / 25 % | 17 / 26 % | 15 / 25 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 15 / 36 % | 25 / 47 % | 5 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 26 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 9 / 23 % | 19 / 31 % | 4 / 10 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 19 / 56 % | 1 / 3 % | 0 / 0 % | 11 / 26 % | 8 / 13 % | 3 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 17 / 80 % | 0 / 2 % | 18 / 32 % | 11 / 26 % | 8 / 15 % | 6 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 44 % | 0 / 0 % | 2 / 6 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 1 / 4 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 8 / 61 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 12 / 18 % | 2 / 4 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 16 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 9 / 22 % | 0 / 0 % | 1 / 7 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 7 / 11 % | 1 / 3 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 6 / 13 % | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 4 / 7 % | 3 / 6 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 5 / 7 % | 2 / 4 % |
