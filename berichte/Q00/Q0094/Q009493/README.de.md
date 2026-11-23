[English](README.md) · [Deutsch](README.de.md)

# OpenAI accidentally hacked Hugging Face — should we have seen it coming?

Bericht Q009493 · Quelle epoch.ai · Datum 2026-07-22 · [Original öffnen](https://epoch.ai/gradient-updates/openai-accidentally-hacked-hugging-face)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Alexander Barry zufolge war der autonome Angriff von OpenAI-Modellen auf Hugging Face technisch nicht überraschend: Mehrere Benchmarks hätten gezeigt, dass Spitzenmodelle Schwachstellen finden und zu komplexen Angriffen verbinden können. Der Zugang zu diesen Fähigkeiten sei derzeit begrenzt, doch falls sie sich verbreiten oder Modelle eigenständig angreifen, könnten laut Autor mehr und ausgefeiltere reale Cyberangriffe folgen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 65 / 82 % | 93 / 97 % | 99 / 100 % | 79 / 86 % | 78 / 88 % | 88 / 92 % | 95 / 98 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 50 % | 55 / 96 % | 97 / 99 % | 52 / 75 % | 14 / 39 % | 53 / 75 % | 17 / 56 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 50 / 69 % | 77 / 98 % | 95 / 97 % | 74 / 86 % | 31 / 52 % | 62 / 76 % | 53 / 70 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 6 / 94 % | 94 / 98 % | 54 / 75 % | 15 / 33 % | 22 / 42 % | 12 / 32 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 33 / 61 % | 37 / 81 % | 92 / 98 % | 59 / 78 % | 13 / 36 % | 34 / 56 % | 26 / 68 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 34 / 54 % | 69 / 95 % | 86 / 94 % | 66 / 82 % | 21 / 45 % | 48 / 66 % | 18 / 55 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 21 / 52 % | 44 / 96 % | 82 / 94 % | 39 / 65 % | 11 / 29 % | 26 / 45 % | 27 / 59 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 12 / 35 % | 77 / 84 % | 54 / 74 % | 10 / 23 % | 50 / 68 % | 6 / 21 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 75 / 82 % | 10 / 27 % | 3 / 8 % | 9 / 14 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 34 / 56 % | 19 / 79 % | 33 / 59 % | 66 / 83 % | 12 / 35 % | 40 / 63 % | 35 / 62 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 32 / 56 % | 39 / 96 % | 49 / 68 % | 36 / 65 % | 24 / 50 % | 61 / 78 % | 15 / 40 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 59 / 84 % | 7 / 24 % | 2 / 10 % | 7 / 18 % | 2 / 14 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 20 / 43 % | 41 / 82 % | 58 / 62 % | 32 / 54 % | 15 / 29 % | 32 / 49 % | 8 / 18 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | 58 / 70 % | 10 / 29 % | 3 / 11 % | 8 / 18 % | 1 / 4 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 37 % | 6 / 80 % | 45 / 68 % | 8 / 24 % | 5 / 19 % | 14 / 30 % | 1 / 5 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 24 / 45 % | 0 / 0 % | 13 / 46 % | 44 / 68 % | 9 / 24 % | 34 / 53 % | 7 / 32 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 29 / 65 % | 41 / 79 % | 7 / 20 % | 1 / 6 % | 5 / 11 % | 0 / 6 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 7 / 83 % | 40 / 70 % | 18 / 41 % | 5 / 13 % | 24 / 45 % | 2 / 14 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 25 / 54 % | 6 / 97 % | 28 / 70 % | 37 / 68 % | 9 / 25 % | 25 / 54 % | 9 / 40 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 4 / 36 % | 31 / 61 % | 8 / 20 % | 19 / 51 % | 4 / 25 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 14 / 40 % | 4 / 98 % | 11 / 74 % | 28 / 54 % | 8 / 22 % | 10 / 36 % | 7 / 51 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 28 / 66 % | 9 / 38 % | 23 / 49 % | 6 / 18 % | 17 / 40 % | 1 / 9 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 49 % | 9 / 58 % | 23 / 44 % | 24 / 51 % | 9 / 22 % | 16 / 33 % | 5 / 18 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 1 / 36 % | 0 / 0 % | 10 / 29 % | 9 / 19 % | 22 / 40 % | 2 / 10 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 1 / 75 % | 17 / 63 % | 22 / 51 % | 7 / 20 % | 14 / 33 % | 3 / 22 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 2 / 10 % | 21 / 40 % | 1 / 5 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 31 % | 1 / 60 % | 6 / 33 % | 15 / 38 % | 7 / 20 % | 15 / 33 % | 2 / 11 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 2 / 8 % | 11 / 18 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 8 / 18 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 2 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 6 % | 7 / 13 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 6 / 11 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 4 / 44 % | 0 / 0 % | 6 / 16 % | 2 / 9 % | 5 / 11 % | 0 / 3 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 2 % | 5 / 11 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 2 / 6 % | 4 / 9 % | 0 / 0 % | – |
