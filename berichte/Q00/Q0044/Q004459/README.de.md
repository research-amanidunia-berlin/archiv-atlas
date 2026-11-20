[English](README.md) · [Deutsch](README.de.md)

# Our framework for safe and trustworthy agents

Bericht Q004459 · Quelle anthropic.com · Datum 2025-08-04 · [Original öffnen](https://www.anthropic.com/news/our-framework-for-developing-safe-and-trustworthy-agents)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic beschreibt einen vorläufigen Rahmen für Agenten, der menschliche Aufsicht, Transparenz, Werteausrichtung, Datenschutz und Sicherheit bei Interaktionen betont. Das Unternehmen nennt Maßnahmen in Claude Code und im Model Context Protocol, räumt aber ein, dass Fehlanpassungen schwer messbar sind und der Rahmen weiterentwickelt werden soll.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 64 / 77 % | 98 / 99 % | – | 100 / 100 % | 88 / 93 % | 83 / 90 % | 81 / 91 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 76 / 88 % | 100 / 100 % | – | 100 / 100 % | 91 / 94 % | 86 / 91 % | 89 / 95 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 37 / 54 % | 99 / 100 % | – | 100 / 100 % | 48 / 71 % | 55 / 74 % | 37 / 63 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 41 / 58 % | 87 / 98 % | – | 99 / 100 % | 76 / 87 % | 81 / 88 % | 74 / 87 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 31 / 50 % | 93 / 99 % | – | 94 / 99 % | 68 / 84 % | 64 / 80 % | 53 / 72 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 16 / 37 % | 76 / 97 % | – | 90 / 95 % | 56 / 76 % | 73 / 84 % | 46 / 67 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 40 / 74 % | – | 76 / 91 % | 10 / 35 % | 6 / 14 % | 4 / 14 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 25 / 47 % | 57 / 97 % | – | 73 / 93 % | 59 / 80 % | 61 / 79 % | 41 / 67 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 27 / 47 % | 29 / 89 % | – | 61 / 78 % | 31 / 62 % | 39 / 63 % | 17 / 35 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 28 % | 43 / 91 % | – | 58 / 90 % | 11 / 33 % | 7 / 20 % | 5 / 20 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 26 % | 6 / 43 % | – | 58 / 89 % | 11 / 34 % | 7 / 17 % | 5 / 16 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 9 / 28 % | 32 / 71 % | – | 31 / 74 % | 56 / 76 % | 10 / 25 % | 7 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 31 % | 34 / 89 % | – | 34 / 70 % | 11 / 36 % | 10 / 21 % | 6 / 24 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 34 / 77 % | – | 0 / 0 % | 7 / 22 % | 7 / 15 % | 6 / 16 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 14 / 22 % | 32 / 79 % | – | 18 / 41 % | 10 / 28 % | 6 / 12 % | 1 / 5 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 10 / 83 % | – | 27 / 46 % | 11 / 32 % | 15 / 34 % | 7 / 16 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 23 / 83 % | – | 0 / 4 % | 5 / 12 % | 4 / 10 % | 3 / 10 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 22 / 70 % | – | 1 / 8 % | 5 / 13 % | 4 / 8 % | 1 / 5 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 22 / 77 % | – | 12 / 27 % | 10 / 29 % | 6 / 13 % | 6 / 18 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 20 / 75 % | – | 19 / 64 % | 13 / 36 % | 11 / 23 % | 3 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 14 / 23 % | 20 / 52 % | – | 4 / 25 % | 11 / 37 % | 8 / 18 % | 1 / 4 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 10 / 19 % | 14 / 86 % | – | 18 / 45 % | 8 / 24 % | 6 / 14 % | 4 / 14 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 6 / 64 % | – | 17 / 50 % | 11 / 25 % | 14 / 23 % | 1 / 4 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 16 / 44 % | – | 0 / 0 % | 7 / 23 % | 3 / 10 % | 2 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 28 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 4 / 11 % | 0 / 4 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 13 / 81 % | – | 0 / 0 % | 5 / 11 % | 1 / 2 % | 1 / 4 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 30 % | 0 / 0 % | 0 / 3 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 10 / 20 % | 1 / 74 % | – | 0 / 0 % | 6 / 17 % | 3 / 6 % | 1 / 4 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 10 / 51 % | – | 0 / 0 % | 5 / 16 % | 6 / 12 % | 1 / 7 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 7 / 24 % | 1 / 34 % | – | 10 / 34 % | 6 / 14 % | 5 / 10 % | 1 / 6 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 10 / 24 % | 6 / 90 % | – | 5 / 42 % | 10 / 28 % | 5 / 14 % | 2 / 9 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 9 / 56 % | – | 9 / 28 % | 7 / 23 % | 4 / 9 % | 1 / 6 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 3 / 80 % | – | 3 / 27 % | 8 / 28 % | 7 / 16 % | 0 / 4 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 24 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 5 / 10 % | 3 / 9 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 5 / 10 % | 0 / 4 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 1 / 42 % | – | 3 / 26 % | 0 / 0 % | 3 / 8 % | 5 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 68 % | – | 0 / 0 % | 5 / 12 % | 4 / 8 % | 1 / 4 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 59 % | – | 0 / 4 % | 5 / 14 % | 0 / 0 % | 0 / 3 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 6 % | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 1 / 4 % | 0 / 3 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 11 % | 0 / 2 % |
