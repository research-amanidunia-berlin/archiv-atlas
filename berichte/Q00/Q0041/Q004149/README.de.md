[English](README.md) · [Deutsch](README.de.md)

# Techniques to Make Large Language Models Smaller: An Explainer

Bericht Q004149 · Quelle cset.georgetown.edu · Datum 2023-10-11 · [Original öffnen](https://cset.georgetown.edu/publication/techniques-to-make-large-language-models-smaller-an-explainer/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Textauszug beschreibt drei Wege, große Sprachmodelle zu verkleinern: Parameter mit weniger Bits darstellen, Wissen durch Ausgaben eines großen Modells auf ein kleineres übertragen und wenig wichtige Parameter entfernen. Kleinere offene Modelle seien meist weniger leistungsfähig, könnten aber Forschung und Zugang erleichtern; zugleich könnten ihre zunehmende Verbreitung und die unklare Übertragbarkeit allgemeiner Fähigkeiten Kontrolle und Regulierung erschweren. Vier zusätzlich angekündigte Effizienzverfahren werden im Auszug nicht erläutert.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 28 / 53 % | 83 / 99 % | 15 / 58 % | 98 / 100 % | 25 / 57 % | 13 / 39 % | 9 / 29 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 14 / 37 % | 50 / 95 % | 10 / 22 % | 24 / 61 % | 34 / 61 % | 16 / 34 % | 14 / 25 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 24 / 52 % | 41 / 87 % | 19 / 51 % | 6 / 52 % | 36 / 64 % | 19 / 42 % | 5 / 19 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 23 / 52 % | 31 / 90 % | 7 / 46 % | 39 / 85 % | 23 / 51 % | 11 / 37 % | 7 / 23 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 33 / 77 % | 0 / 3 % | 14 / 51 % | 6 / 21 % | 7 / 20 % | 0 / 5 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 3 / 15 % | 28 / 70 % | 7 / 29 % | 5 / 18 % | 3 / 16 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 13 / 34 % | 17 / 90 % | 2 / 11 % | 27 / 69 % | 9 / 28 % | 6 / 21 % | 2 / 12 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 27 / 78 % | 0 / 0 % | 0 / 3 % | 5 / 11 % | 4 / 9 % | 1 / 9 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 9 / 99 % | 1 / 9 % | 26 / 78 % | 11 / 35 % | 5 / 18 % | 4 / 16 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 24 / 73 % | 0 / 3 % | 18 / 63 % | 8 / 24 % | 4 / 14 % | 2 / 14 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 18 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 15 / 68 % | 1 / 7 % | 16 / 46 % | 9 / 35 % | 7 / 19 % | 2 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 16 / 73 % | 0 / 4 % | 3 / 24 % | 6 / 17 % | 2 / 8 % | 1 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 36 % | 5 / 57 % | 1 / 7 % | 1 / 15 % | 7 / 22 % | 7 / 14 % | 1 / 7 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 12 / 43 % | 0 / 0 % | 14 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 13 / 68 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 2 / 8 % | 1 / 6 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 1 / 6 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 4 / 67 % | 0 / 5 % | 1 / 22 % | 7 / 21 % | 8 / 18 % | 2 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 7 / 35 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 3 / 8 % | 1 / 7 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 5 / 65 % | 0 / 2 % | 0 / 0 % | 6 / 17 % | 4 / 12 % | 1 / 5 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 5 / 12 % | 6 / 13 % | 0 / 3 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 3 / 65 % | 0 / 4 % | 4 / 30 % | 6 / 18 % | 4 / 9 % | 2 / 9 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 1 / 9 % | 0 / 0 % | 6 / 17 % | 4 / 10 % | 2 / 9 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 6 / 66 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 4 / 11 % | 0 / 1 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 6 / 16 % | 1 / 5 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 10 % | 4 / 10 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 3 / 6 % | 1 / 4 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 5 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 5 / 13 % | 3 / 6 % | 0 / 4 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 49 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % |
