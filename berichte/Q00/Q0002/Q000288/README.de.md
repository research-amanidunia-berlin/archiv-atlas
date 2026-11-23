[English](README.md) · [Deutsch](README.de.md)

# What affects chain-of-thought monitorability across the model lifecycle?

Bericht Q000288 · Quelle alignment.openai.com · Datum 2026-11-10 · [Original öffnen](https://alignment.openai.com/cot-monitorability-model-lifecycle/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt Zusammenhänge zwischen sinkender Basismodell-Perplexität, besseren Fähigkeiten ohne sichtbaren CoT und steigender CoT-Kontrollierbarkeit; auch RL und modellgenerierte Trainingsdaten können laut den Experimenten die Kontrollierbarkeit erhöhen. Die Autorinnen und Autoren folgern, dass CoT-Überwachung dadurch schwieriger werden könnte, betonen aber, dass die verwendeten Ersatzmaße unvollkommen sind und Kontrollierbarkeit in den berichteten Vergleichstests nicht zuverlässig mit tatsächlicher Monitor-Umgehung einherging.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 40 / 64 % | 97 / 99 % | – | 55 / 77 % | 20 / 41 % | 58 / 75 % | 39 / 71 % | 16 / 37 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 55 / 73 % | 43 / 88 % | – | 68 / 84 % | 36 / 59 % | 72 / 82 % | 34 / 68 % | 23 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 37 / 63 % | 66 / 99 % | – | 37 / 66 % | 13 / 29 % | 34 / 56 % | 3 / 16 % | 20 / 37 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 64 / 87 % | – | 39 / 61 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 52 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 22 / 48 % | 60 / 99 % | – | 28 / 59 % | 5 / 17 % | 14 / 31 % | 5 / 23 % | 12 / 39 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 31 / 55 % | 43 / 91 % | – | 25 / 50 % | 6 / 18 % | 27 / 43 % | 2 / 7 % | 13 / 32 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 36 / 59 % | 41 / 92 % | – | 35 / 64 % | 12 / 30 % | 37 / 61 % | 11 / 41 % | 30 / 52 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 26 / 57 % | 24 / 60 % | – | 35 / 62 % | 4 / 12 % | 23 / 45 % | 8 / 29 % | 27 / 46 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 8 / 65 % | – | 35 / 60 % | 3 / 11 % | 0 / 0 % | 1 / 5 % | 12 / 31 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 12 / 42 % | 35 / 97 % | – | 33 / 58 % | 3 / 11 % | 16 / 36 % | 4 / 25 % | 17 / 38 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 56 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 27 / 60 % | – | 12 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 24 / 50 % | 19 / 64 % | – | 18 / 42 % | 3 / 10 % | 16 / 30 % | 1 / 5 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 20 / 49 % | 0 / 0 % | – | 15 / 42 % | 4 / 11 % | 22 / 36 % | 0 / 3 % | 11 / 29 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | – | 22 / 46 % | 3 / 11 % | 18 / 36 % | 2 / 9 % | 6 / 18 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 20 / 77 % | – | 5 / 13 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 44 % | 0 / 0 % | – | 9 / 34 % | 2 / 10 % | 15 / 30 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 19 / 62 % | – | 14 / 39 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 47 % | 0 / 0 % | – | 18 / 43 % | 2 / 9 % | 0 / 0 % | 2 / 7 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 7 / 52 % | – | 9 / 27 % | 1 / 6 % | 12 / 24 % | 1 / 5 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | – | 9 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 0 / 0 % | – | 7 / 22 % | 2 / 10 % | 0 / 0 % | 1 / 6 % | 8 / 22 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 7 / 22 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | – | 7 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 5 / 15 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
