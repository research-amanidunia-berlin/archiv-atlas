[English](README.md) · [Deutsch](README.de.md)

# Introducing ChatGPT agent

Bericht Q006682 · Quelle openai.com · Datum 2025-07-17 · [Original öffnen](https://openai.com/index/introducing-chatgpt-agent/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der inzwischen als veraltet gekennzeichnete Beitrag beschreibt den 2025 eingeführten ChatGPT-Agenten, der Recherche und Webaktionen mit Browsern, APIs, Terminal und verbundenen Apps kombinieren soll. OpenAI berichtet von guten Benchmark-Ergebnissen, weist aber auf unterschiedliche Testbedingungen, mögliche Fehler, Prompt-Injection-Risiken und noch unausgereifte Folienausgaben hin; Schutzmaßnahmen umfassen Aufsicht und Bestätigungen vor folgenreichen Aktionen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 68 / 79 % | 97 / 98 % | 100 / 100 % | 85 / 92 % | 40 / 54 % | 79 / 86 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 73 / 85 % | 90 / 92 % | 100 / 100 % | 90 / 94 % | 81 / 89 % | 88 / 92 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 43 / 58 % | 84 / 91 % | 100 / 100 % | 50 / 72 % | 42 / 57 % | 54 / 68 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 46 / 62 % | 89 / 98 % | 99 / 100 % | 81 / 89 % | 44 / 64 % | 75 / 85 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 53 / 67 % | 78 / 90 % | 96 / 98 % | 84 / 90 % | 70 / 82 % | 87 / 91 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 35 / 55 % | 25 / 65 % | 95 / 97 % | 52 / 75 % | 29 / 50 % | 61 / 77 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 28 / 47 % | 90 / 96 % | 40 / 65 % | 56 / 77 % | 11 / 24 % | 34 / 57 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 50 / 87 % | 89 / 95 % | 8 / 23 % | 0 / 0 % | 7 / 13 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 24 / 74 % | 86 / 92 % | 49 / 72 % | 8 / 17 % | 10 / 21 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 17 / 34 % | 57 / 74 % | 86 / 90 % | 44 / 70 % | 11 / 23 % | 48 / 68 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 26 / 44 % | 71 / 99 % | 86 / 93 % | 45 / 69 % | 8 / 25 % | 27 / 55 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 43 % | 84 / 96 % | 84 / 90 % | 26 / 50 % | 10 / 18 % | 29 / 47 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 33 / 59 % | 63 / 87 % | 83 / 92 % | 47 / 69 % | 16 / 34 % | 35 / 56 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 50 / 71 % | 81 / 89 % | 8 / 23 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 38 % | 65 / 93 % | 21 / 41 % | 10 / 32 % | 3 / 11 % | 10 / 21 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 58 / 93 % | 30 / 48 % | 7 / 20 % | 3 / 10 % | 6 / 14 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 52 / 70 % | 0 / 0 % | 11 / 27 % | 0 / 0 % | 11 / 23 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 51 / 82 % | 6 / 13 % | 9 / 23 % | 4 / 12 % | 7 / 15 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 35 / 50 % | 0 / 0 % | 41 / 61 % | 45 / 68 % | 0 / 0 % | 27 / 45 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 45 / 67 % | 34 / 47 % | 15 / 36 % | 4 / 10 % | 16 / 26 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 44 / 76 % | 0 / 0 % | 8 / 21 % | 2 / 6 % | 5 / 7 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 43 / 64 % | 10 / 28 % | 4 / 11 % | 8 / 18 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 37 / 69 % | 33 / 41 % | 19 / 41 % | 6 / 14 % | 10 / 19 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 36 / 46 % | 17 / 44 % | 5 / 12 % | 21 / 40 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 29 / 79 % | 13 / 27 % | 18 / 40 % | 10 / 21 % | 14 / 25 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 27 / 44 % | 8 / 18 % | 3 / 9 % | 9 / 16 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 21 / 55 % | 0 / 0 % | 0 / 0 % | 11 / 35 % | 2 / 6 % | 17 / 32 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 45 % | 0 / 0 % | 0 / 0 % | 18 / 42 % | 4 / 9 % | 11 / 21 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 7 / 63 % | 17 / 32 % | 9 / 20 % | 3 / 8 % | 8 / 14 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 36 % | 0 / 0 % | 11 / 20 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 25 % | 4 / 10 % | 7 / 14 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 1 / 6 % | 9 / 20 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 14 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 2 % | 5 / 12 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 8 / 55 % | 0 / 0 % | 6 / 13 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 6 / 11 % | 7 / 14 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 5 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 3 / 8 % | 6 / 11 % | – | – |
