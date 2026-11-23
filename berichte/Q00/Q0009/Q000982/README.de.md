[English](README.md) · [Deutsch](README.de.md)

# Addendum to GPT-5.2 System Card: GPT-5.2-Codex

Bericht Q000982 · Quelle deploymentsafety.openai.com · Datum 2025-12-18 · [Original öffnen](https://deploymentsafety.openai.com/gpt-5-2-codex)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet von deutlichen Fortschritten bei GPT-5.2-Codex, stuft seine Cyberfähigkeiten aber trotz starker Einzelergebnisse unterhalb der eigenen Hoch-Schwelle ein; im biologisch-chemischen Bereich gilt es als Hochrisiko. Die Ergebnisse fallen je nach Test unterschiedlich aus, und der Bericht schränkt ein, dass Benchmarks reale Einsatzbedingungen und durchschnittlichen Produktverkehr nur begrenzt abbilden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 71 / 82 % | 97 / 98 % | 100 / 100 % | 85 / 92 % | 78 / 88 % | 87 / 91 % | 98 / 100 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 59 / 75 % | 99 / 100 % | 100 / 100 % | 91 / 95 % | 25 / 43 % | 79 / 89 % | 80 / 89 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 50 / 66 % | 98 / 100 % | 100 / 100 % | 88 / 93 % | 54 / 74 % | 79 / 89 % | 77 / 90 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 62 / 77 % | 97 / 98 % | 100 / 100 % | 92 / 95 % | 78 / 89 % | 88 / 92 % | 98 / 99 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 54 / 96 % | 98 / 99 % | 80 / 90 % | 33 / 51 % | 26 / 43 % | 24 / 47 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 51 / 69 % | 97 / 100 % | 78 / 91 % | 78 / 89 % | 25 / 48 % | 68 / 81 % | 38 / 66 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 42 / 58 % | 58 / 92 % | 97 / 98 % | 75 / 87 % | 67 / 81 % | 86 / 92 % | 58 / 81 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 31 / 52 % | 91 / 97 % | 95 / 97 % | 44 / 68 % | 10 / 20 % | 33 / 49 % | 5 / 18 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 40 / 57 % | 91 / 99 % | 93 / 96 % | 80 / 89 % | 41 / 61 % | 70 / 83 % | 17 / 37 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 77 / 96 % | 93 / 95 % | 14 / 33 % | 4 / 9 % | 18 / 29 % | 8 / 14 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 27 / 46 % | 58 / 84 % | 92 / 95 % | 76 / 87 % | 22 / 40 % | 67 / 83 % | 11 / 31 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 46 / 64 % | 82 / 98 % | 81 / 88 % | 85 / 92 % | 56 / 74 % | 87 / 93 % | 82 / 91 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 46 / 65 % | 81 / 100 % | 52 / 73 % | 70 / 84 % | 64 / 80 % | 82 / 88 % | 40 / 52 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 43 / 62 % | 63 / 95 % | 78 / 90 % | 73 / 87 % | 17 / 35 % | 57 / 71 % | 20 / 49 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 5 / 63 % | 68 / 80 % | 8 / 17 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 12 / 55 % | 67 / 82 % | 11 / 31 % | 5 / 14 % | 9 / 17 % | 0 / 1 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 63 / 81 % | 13 / 35 % | 3 / 9 % | 6 / 13 % | 1 / 6 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 44 / 79 % | 59 / 76 % | 13 / 30 % | 5 / 12 % | 14 / 23 % | 2 / 7 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 42 / 55 % | 26 / 51 % | 10 / 20 % | 28 / 45 % | 7 / 15 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 41 / 76 % | 0 / 0 % | 9 / 20 % | 3 / 9 % | 7 / 13 % | 0 / 3 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 38 / 92 % | 9 / 45 % | 19 / 41 % | 8 / 18 % | 8 / 20 % | 2 / 9 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 42 % | 0 / 0 % | 0 / 0 % | 32 / 58 % | 5 / 12 % | 17 / 31 % | 4 / 12 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 24 / 53 % | 0 / 0 % | 0 / 0 % | 19 / 45 % | 6 / 16 % | 27 / 46 % | 1 / 5 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 6 / 64 % | 27 / 48 % | 20 / 44 % | 9 / 22 % | 12 / 23 % | 2 / 6 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 25 / 65 % | 17 / 40 % | 10 / 25 % | 3 / 9 % | 6 / 15 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 23 / 67 % | 8 / 30 % | 9 / 23 % | 1 / 4 % | 8 / 14 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 17 / 51 % | 0 / 0 % | 11 / 27 % | 1 / 5 % | 8 / 15 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 24 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 4 / 11 % | 11 / 21 % | 0 / 1 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 3 / 9 % | 11 / 20 % | 0 / 1 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 8 / 14 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 3 / 8 % | 6 / 10 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 7 / 44 % | 0 / 0 % | 8 / 21 % | 3 / 10 % | 6 / 12 % | 0 / 2 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 7 / 56 % | 0 / 0 % | 0 / 0 % | 2 / 5 % | 7 / 12 % | 0 / 0 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 3 / 9 % | 6 / 11 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 4 / 10 % | 0 / 0 % | – |
