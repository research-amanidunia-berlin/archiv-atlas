[English](README.md) · [Deutsch](README.de.md)

# Operator System Card

Bericht Q009104 · Quelle openai.com · Datum 2025-01-23 · [Original öffnen](https://openai.com/index/operator-system-card/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Die Systemkarte beschreibt OpenAIs Tests zu Operator und Schutzmaßnahmen wie Ablehnungen, Bestätigungsabfragen und Überwachung. OpenAI berichtet von niedrigen Erfolgswerten in den untersuchten Risikoaufgaben, zugleich aber auch von Modellfehlern und verbleibender Prompt-Injection-Anfälligkeit; die Testergebnisse garantierten keine entsprechende Sicherheit im realen Einsatz.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 42 / 62 % | 98 / 100 % | – | 100 / 100 % | 70 / 84 % | 81 / 89 % | 66 / 82 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 39 / 58 % | 100 / 100 % | – | 99 / 100 % | 77 / 87 % | 69 / 83 % | 33 / 59 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 60 / 74 % | 96 / 99 % | – | 100 / 100 % | 89 / 93 % | 84 / 91 % | 62 / 81 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 72 / 84 % | 96 / 97 % | – | 100 / 100 % | 92 / 95 % | 89 / 93 % | 77 / 90 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 49 / 67 % | 99 / 100 % | – | 95 / 98 % | 74 / 86 % | 68 / 80 % | 20 / 42 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 52 / 70 % | 90 / 98 % | – | 99 / 100 % | 71 / 86 % | 59 / 73 % | 35 / 62 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 41 / 58 % | 99 / 100 % | – | 97 / 99 % | 80 / 90 % | 61 / 72 % | 11 / 26 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 38 / 51 % | 95 / 98 % | – | 99 / 100 % | 49 / 72 % | 51 / 70 % | 33 / 55 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 97 / 100 % | – | 98 / 99 % | 45 / 70 % | 39 / 54 % | 39 / 63 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 54 / 70 % | 72 / 91 % | – | 98 / 99 % | 88 / 93 % | 87 / 92 % | 63 / 81 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 33 / 52 % | 97 / 98 % | – | 94 / 96 % | 36 / 62 % | 30 / 47 % | 10 / 20 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 29 / 50 % | 93 / 98 % | – | 96 / 97 % | 75 / 87 % | 69 / 83 % | 25 / 48 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 45 / 60 % | 78 / 93 % | – | 95 / 98 % | 65 / 82 % | 48 / 61 % | 13 / 32 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 48 / 83 % | – | 93 / 96 % | 48 / 71 % | 8 / 16 % | 8 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 30 / 53 % | 75 / 98 % | – | 59 / 77 % | 74 / 86 % | 77 / 86 % | 18 / 36 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 27 / 61 % | – | 77 / 87 % | 8 / 20 % | 7 / 13 % | 3 / 8 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 28 / 57 % | 0 / 0 % | – | 71 / 79 % | 24 / 52 % | 28 / 49 % | 5 / 15 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 31 / 83 % | – | 62 / 77 % | 15 / 31 % | 20 / 31 % | 8 / 17 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 11 / 62 % | – | 57 / 70 % | 23 / 48 % | 29 / 46 % | 6 / 14 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 57 / 76 % | – | 55 / 67 % | 19 / 40 % | 15 / 25 % | 6 / 11 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 55 / 79 % | – | 1 / 5 % | 7 / 16 % | 6 / 13 % | 2 / 8 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 48 / 73 % | 10 / 30 % | 6 / 14 % | 4 / 11 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 23 % | 47 / 76 % | – | 32 / 56 % | 12 / 32 % | 9 / 22 % | 3 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 40 / 67 % | – | 15 / 41 % | 15 / 35 % | 10 / 25 % | 1 / 4 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 40 / 86 % | – | 0 / 0 % | 6 / 16 % | 8 / 16 % | 3 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 33 / 67 % | – | 7 / 16 % | 9 / 24 % | 0 / 0 % | 6 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 31 / 55 % | 21 / 46 % | 12 / 28 % | 4 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 29 / 79 % | – | 17 / 34 % | 17 / 38 % | 12 / 22 % | 9 / 21 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 27 / 55 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 26 / 68 % | – | 3 / 24 % | 9 / 21 % | 6 / 13 % | 4 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 26 / 68 % | – | 0 / 0 % | 6 / 13 % | 6 / 11 % | 2 / 6 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 21 / 46 % | 8 / 17 % | 5 / 12 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 26 % | 9 / 18 % | 3 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 10 / 29 % | 8 / 19 % | 11 / 19 % | 4 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 35 % | – | 0 / 0 % | 8 / 17 % | 9 / 18 % | 1 / 6 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 26 % | 0 / 0 % | 1 / 5 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 2 / 5 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 1 / 5 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 4 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % | 4 / 8 % |
