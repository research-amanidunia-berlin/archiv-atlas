[English](README.md) · [Deutsch](README.de.md)

# Predictability and surprise in large generative models

Bericht Q001373 · Quelle anthropic.com · Datum 2022-02-15 · [Original öffnen](https://www.anthropic.com/research/predictability-and-surprise-in-large-generative-models)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Text ist ein Auszug aus dem Abstract, kein vollständiger Bericht. Laut den Autoren können große generative Modelle auf breiter Ebene berechenbar erscheinen, während konkrete Fähigkeiten und Ausgaben unvorhersehbar bleiben; das könne Entwicklung fördern und die Einschätzung von Einsatzfolgen erschweren. Details zu den angekündigten Beispielen, Experimenten und Maßnahmen fehlen im Auszug.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 25 / 53 % | 46 / 95 % | 89 / 98 % | 29 / 62 % | 6 / 27 % | 25 / 60 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 49 % | 20 / 78 % | 65 / 94 % | 14 / 45 % | 2 / 15 % | 11 / 42 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 38 / 72 % | 64 / 86 % | 7 / 24 % | 1 / 9 % | 8 / 19 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 42 % | 57 / 88 % | 35 / 82 % | 8 / 31 % | 2 / 13 % | 8 / 37 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 12 / 42 % | 48 / 85 % | 24 / 79 % | 12 / 37 % | 3 / 12 % | 10 / 26 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 22 / 48 % | 27 / 90 % | 44 / 82 % | 21 / 54 % | 3 / 17 % | 13 / 37 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 46 % | 42 / 82 % | 19 / 56 % | 8 / 33 % | 0 / 6 % | 11 / 26 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 32 / 84 % | 1 / 23 % | 6 / 17 % | 0 / 5 % | 5 / 16 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 27 / 64 % | 0 / 13 % | 5 / 16 % | 1 / 7 % | 6 / 18 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 6 / 37 % | 26 / 79 % | 2 / 41 % | 7 / 26 % | 1 / 11 % | 7 / 23 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 8 / 40 % | 25 / 67 % | 18 / 75 % | 12 / 42 % | 1 / 10 % | 14 / 43 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 21 / 83 % | 11 / 55 % | 10 / 31 % | 2 / 10 % | 10 / 28 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 20 / 68 % | 0 / 0 % | 5 / 17 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 17 / 44 % | 20 / 86 % | 3 / 21 % | 9 / 42 % | 2 / 13 % | 9 / 32 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 14 / 46 % | 20 / 69 % | 12 / 46 % | 14 / 42 % | 1 / 11 % | 13 / 34 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 20 / 77 % | 1 / 25 % | 5 / 14 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 20 / 50 % | 6 / 37 % | 7 / 24 % | 0 / 0 % | 5 / 14 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 19 / 77 % | 10 / 56 % | 9 / 33 % | 1 / 8 % | 6 / 15 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 18 / 45 % | 2 / 47 % | 9 / 34 % | 2 / 10 % | 9 / 24 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 18 / 86 % | 1 / 12 % | 6 / 20 % | 1 / 8 % | 5 / 16 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 18 / 79 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 16 / 73 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 6 / 12 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 14 / 50 % | 2 / 27 % | 6 / 18 % | 0 / 0 % | 7 / 18 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 14 / 52 % | 0 / 0 % | 7 / 20 % | 0 / 0 % | 6 / 16 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 6 / 52 % | 0 / 7 % | 8 / 32 % | 0 / 0 % | 10 / 24 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 10 / 39 % | 0 / 0 % | 7 / 27 % | 1 / 6 % | 10 / 24 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 10 / 40 % | 6 / 71 % | 4 / 51 % | 8 / 27 % | 2 / 12 % | 8 / 23 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 31 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 9 / 36 % | 4 / 23 % | 6 / 29 % | 0 / 0 % | 7 / 19 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 9 / 82 % | 2 / 29 % | 7 / 21 % | 0 / 0 % | 8 / 22 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 38 % | 8 / 87 % | 9 / 49 % | 7 / 26 % | 1 / 10 % | 6 / 22 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 37 % | 7 / 64 % | 4 / 46 % | 7 / 24 % | 1 / 8 % | 8 / 26 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 7 / 35 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 7 / 45 % | 0 / 0 % | 0 / 0 % | 6 / 25 % | 0 / 4 % | 6 / 14 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 7 / 16 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 1 / 13 % | 7 / 20 % | 1 / 6 % | 7 / 18 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 5 / 48 % | 6 / 23 % | 0 / 0 % | 6 / 19 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 4 / 9 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | – | – |
