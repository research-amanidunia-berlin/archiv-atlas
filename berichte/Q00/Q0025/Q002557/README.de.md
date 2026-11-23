[English](README.md) · [Deutsch](README.de.md)

# Building safer dialogue agents

Bericht Q002557 · Quelle deepmind.google · Datum 2022-09-22 · [Original öffnen](https://deepmind.google/blog/building-safer-dialogue-agents/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

DeepMind stellt Sparrow als Forschungsmodell vor, das durch menschliches Feedback hilfreiche Antworten lernen und mit vorläufigen Regeln riskantes Verhalten begrenzen soll. Laut den Teilnehmenden waren Faktenantworten in 78 Prozent der Fälle plausibel und belegt; dennoch blieben Fehler, Regelverstöße und offene Fragen zu Regeln sowie zur Übertragbarkeit auf andere Sprachen und Kulturen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 35 / 56 % | 86 / 94 % | 99 / 100 % | 74 / 86 % | 47 / 67 % | 64 / 78 % | 31 / 61 % | 25 / 52 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 42 / 61 % | 88 / 99 % | 99 / 100 % | 67 / 83 % | 32 / 59 % | 56 / 77 % | 29 / 64 % | 29 / 55 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 45 / 61 % | 98 / 100 % | 97 / 99 % | 63 / 80 % | 47 / 66 % | 50 / 68 % | 36 / 60 % | 19 / 46 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 52 % | 31 / 66 % | 97 / 99 % | 41 / 68 % | 14 / 34 % | 38 / 59 % | 7 / 25 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 31 / 54 % | 52 / 91 % | 96 / 99 % | 40 / 64 % | 7 / 22 % | 14 / 32 % | 5 / 22 % | 23 / 53 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 7 / 28 % | 39 / 86 % | 90 / 95 % | 25 / 50 % | 7 / 25 % | 15 / 32 % | 1 / 6 % | 23 / 43 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 29 / 48 % | 53 / 87 % | 87 / 95 % | 26 / 49 % | 13 / 33 % | 19 / 41 % | 8 / 24 % | 16 / 41 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 73 / 91 % | 75 / 90 % | 9 / 31 % | 0 / 0 % | 10 / 20 % | 0 / 2 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 13 / 34 % | 37 / 77 % | 73 / 89 % | 46 / 70 % | 8 / 24 % | 11 / 27 % | 5 / 19 % | 21 / 49 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 13 / 30 % | 24 / 81 % | 63 / 80 % | 8 / 22 % | 5 / 14 % | 10 / 22 % | 0 / 3 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 45 / 84 % | 61 / 76 % | 29 / 54 % | 7 / 23 % | 8 / 20 % | 1 / 6 % | 9 / 27 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 59 / 76 % | 11 / 29 % | 3 / 10 % | 4 / 9 % | 0 / 0 % | 5 / 21 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 12 / 35 % | 37 / 93 % | 33 / 67 % | 15 / 41 % | 3 / 13 % | 6 / 14 % | 0 / 3 % | 15 / 37 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 36 % | 35 / 74 % | 27 / 53 % | 7 / 20 % | 1 / 6 % | 5 / 9 % | 0 / 1 % | 10 / 29 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 28 / 58 % | 7 / 38 % | 7 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 14 / 27 % | 17 / 48 % | 26 / 56 % | 19 / 43 % | 5 / 16 % | 8 / 19 % | 1 / 8 % | 11 / 28 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 3 / 73 % | 2 / 11 % | 5 / 12 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 26 / 54 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 25 / 72 % | 21 / 60 % | 7 / 17 % | 2 / 8 % | 6 / 11 % | 1 / 4 % | 7 / 26 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 10 / 26 % | 0 / 0 % | 24 / 55 % | 8 / 24 % | 4 / 16 % | 6 / 16 % | 0 / 0 % | 3 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 33 % | 8 / 68 % | 17 / 39 % | 8 / 26 % | 3 / 10 % | 10 / 21 % | 0 / 4 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 12 / 75 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 30 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 4 / 18 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 10 / 36 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 1 / 7 % | 3 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 29 % | 9 / 67 % | 0 / 0 % | 8 / 22 % | 4 / 15 % | 7 / 20 % | 0 / 3 % | 5 / 19 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 1 / 23 % | 0 / 2 % | 5 / 13 % | 1 / 8 % | 0 / 0 % | 0 / 0 % | 9 / 27 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 6 / 48 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 2 / 4 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 6 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 13 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 3 / 77 % | 0 / 0 % | 6 / 14 % | 3 / 11 % | 0 / 0 % | 0 / 0 % | 5 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 5 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 8 % | 0 / 0 % | 0 / 0 % |
