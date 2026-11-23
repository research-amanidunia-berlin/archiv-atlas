[English](README.md) · [Deutsch](README.de.md)

# Meta’s New Local AI Agent Hallucinates 82% of the Time

Bericht Q011016 · Quelle medium.com · Datum 2026-08-15 · [Original öffnen](https://medium.com/data-science-collective/metas-new-local-ai-agent-hallucinates-82-of-the-time-04cf80c09013)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht würdigt Muse Glimmers kompakte Bauweise und seine guten Ergebnisse bei der Werkzeugauswahl, kritisiert aber eine laut Artificial Analysis sehr hohe Halluzinationsrate von 82 Prozent. Der Autor hält das Modell deshalb für unbeaufsichtigte Arbeit mit persönlichen Dateien für zu riskant, räumt jedoch ein, dass der Bericht keine Tests mit Abrufsystemen und strenger Werkzeugvalidierung enthält.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 29 / 49 % | 77 / 97 % | 100 / 100 % | 52 / 75 % | 20 / 50 % | 46 / 68 % | 26 / 67 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 31 / 50 % | 18 / 70 % | 93 / 95 % | 35 / 62 % | 14 / 38 % | 25 / 52 % | 12 / 32 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 18 / 40 % | 40 / 75 % | 92 / 97 % | 42 / 68 % | 10 / 26 % | 15 / 30 % | 3 / 12 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 28 / 48 % | 51 / 86 % | 92 / 96 % | 36 / 63 % | 25 / 49 % | 41 / 66 % | 9 / 31 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 25 / 47 % | 77 / 95 % | 91 / 97 % | 58 / 78 % | 18 / 45 % | 29 / 55 % | 26 / 67 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 15 / 32 % | 3 / 36 % | 90 / 92 % | 26 / 51 % | 9 / 22 % | 27 / 45 % | 2 / 8 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 14 / 34 % | 57 / 84 % | 90 / 95 % | 11 / 30 % | 2 / 8 % | 7 / 15 % | 1 / 5 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 62 / 91 % | 88 / 93 % | 12 / 33 % | 4 / 15 % | 16 / 28 % | 0 / 2 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 28 / 52 % | 55 / 90 % | 86 / 95 % | 46 / 69 % | 13 / 33 % | 35 / 47 % | 12 / 28 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 24 / 77 % | 84 / 90 % | 7 / 14 % | 2 / 7 % | 6 / 11 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 83 / 88 % | 20 / 43 % | 3 / 10 % | 8 / 15 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 22 / 41 % | 25 / 69 % | 81 / 87 % | 13 / 33 % | 4 / 14 % | 11 / 20 % | 2 / 5 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 26 / 45 % | 43 / 80 % | 75 / 84 % | 49 / 73 % | 17 / 45 % | 43 / 65 % | 11 / 31 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 31 % | 0 / 0 % | 48 / 54 % | 8 / 19 % | 2 / 8 % | 11 / 21 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 22 / 47 % | 8 / 32 % | 43 / 65 % | 18 / 45 % | 10 / 27 % | 24 / 51 % | 9 / 30 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 35 % | 30 / 87 % | 14 / 38 % | 22 / 47 % | 11 / 30 % | 14 / 28 % | 2 / 8 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 6 / 36 % | 26 / 41 % | 14 / 36 % | 8 / 18 % | 16 / 32 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 20 / 40 % | 7 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 13 / 29 % | 0 / 0 % | 8 / 26 % | 19 / 42 % | 4 / 12 % | 8 / 18 % | 1 / 7 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 40 % | 4 / 10 % | 10 / 17 % | 1 / 4 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 3 / 8 % | 11 / 19 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 30 % | 4 / 31 % | 0 / 0 % | 7 / 16 % | 1 / 4 % | 8 / 15 % | 0 / 1 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 12 / 23 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 12 / 19 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 10 / 22 % | 10 / 25 % | 4 / 14 % | 6 / 13 % | 1 / 4 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 9 / 16 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 28 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 5 % | 5 / 8 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 5 / 8 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
