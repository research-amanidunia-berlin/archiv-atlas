[English](README.md) · [Deutsch](README.de.md)

# Claude accelerates protein design and analytical chemistry

Bericht Q000859 · Quelle anthropic.com · Datum 2026-08-18 · [Original öffnen](https://www.anthropic.com/research/Claude-accelerates-protein-design)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic berichtet, Claude habe in Laborversuchen Binder gegen 14 von 15 auswertbaren Proteinzielen entworfen und Routineanalysen von NMR- und LC-MS-Daten in weniger als 25 Minuten erstellt, mit Ergebnissen nahe denen eines Labors. Die Resultate sind begrenzt: Bei einzelnen Zielen scheiterte das Modell, die Proteinmessungen sollen noch genauer bestätigt werden, und Binderentwurf ist nur ein früher Schritt der Arzneimittelentwicklung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 25 / 47 % | 81 / 96 % | 98 / 99 % | 68 / 82 % | 0 / 0 % | 48 / 64 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 21 / 44 % | 53 / 88 % | 90 / 94 % | 35 / 60 % | 3 / 10 % | 29 / 48 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 31 / 49 % | 85 / 94 % | 87 / 91 % | 49 / 69 % | 10 / 21 % | 56 / 68 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 17 / 84 % | 84 / 90 % | 8 / 19 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 33 / 53 % | 76 / 90 % | 73 / 81 % | 47 / 71 % | 0 / 0 % | 60 / 74 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 20 / 44 % | 74 / 93 % | 48 / 69 % | 17 / 42 % | 5 / 19 % | 24 / 44 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 21 / 45 % | 52 / 74 % | 70 / 81 % | 19 / 40 % | 8 / 16 % | 31 / 45 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 54 / 84 % | 67 / 77 % | 6 / 18 % | 1 / 4 % | 8 / 18 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 64 / 75 % | 18 / 39 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 31 / 64 % | 62 / 73 % | 24 / 46 % | 4 / 10 % | 21 / 34 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 26 / 50 % | 50 / 79 % | 49 / 63 % | 32 / 58 % | 5 / 13 % | 27 / 41 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 36 / 90 % | 49 / 62 % | 7 / 22 % | 2 / 7 % | 5 / 10 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 47 / 58 % | 23 / 48 % | 1 / 5 % | 16 / 29 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 38 / 66 % | 0 / 0 % | 23 / 49 % | 0 / 5 % | 11 / 23 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 37 / 50 % | 7 / 19 % | 1 / 5 % | 4 / 10 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 34 / 51 % | 9 / 25 % | 0 / 0 % | 14 / 22 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 41 % | 20 / 51 % | 0 / 0 % | 31 / 58 % | 2 / 7 % | 16 / 28 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 44 % | 3 / 9 % | 18 / 30 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 22 / 32 % | 6 / 13 % | 0 / 0 % | 3 / 5 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 36 % | 0 / 0 % | 0 / 0 % | 21 / 43 % | 4 / 11 % | 21 / 35 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 38 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 0 / 2 % | 14 / 26 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 16 / 62 % | 15 / 32 % | 12 / 36 % | 1 / 5 % | 9 / 22 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 5 / 14 % | 16 / 38 % | 5 / 11 % | 7 / 14 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 14 / 39 % | 0 / 0 % | 6 / 17 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 1 / 3 % | 12 / 21 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 23 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 16 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 6 % | 5 / 11 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 1 % | 8 / 12 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 6 / 9 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 4 / 8 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 1 % | 5 / 10 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 0 / 0 % | – | – |
