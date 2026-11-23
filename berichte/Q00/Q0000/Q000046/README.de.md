[English](README.md) · [Deutsch](README.de.md)

# Simulated Control Evaluations

Bericht Q000046 · Quelle redwoodresearch.org · Datum 2026-10-24 · [Original öffnen](https://www.redwoodresearch.org/blog/simulated-control-evaluations)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt SCEs vor: Angriffe werden anhand realer Agentenprotokolle weitergedacht, während ein Sprachmodell die Umgebung simuliert und ein weiteres den möglichen Erfolg bewertet. In LinuxArena stimmen die Ergebnisse laut den Autoren oft gut mit realen Durchläufen überein und sagen Sicherheitswerte besser voraus als BashArena. Die Übertragung auf echte Einsätze bleibt jedoch teilweise ungeprüft; unter anderem fehlen Belege für unbekannte Umgebungen und lang laufende Angriffe mehrerer Agenten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 43 / 63 % | 99 / 100 % | 90 / 95 % | 72 / 85 % | 69 / 83 % | 70 / 84 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 43 / 65 % | 77 / 93 % | 96 / 98 % | 10 / 19 % | 55 / 72 % | 78 / 87 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 37 / 56 % | 59 / 92 % | 89 / 94 % | 48 / 74 % | 22 / 47 % | 52 / 74 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 32 / 57 % | 66 / 93 % | 85 / 95 % | 59 / 79 % | 11 / 32 % | 44 / 68 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 20 / 41 % | 79 / 92 % | 73 / 82 % | 52 / 74 % | 13 / 29 % | 47 / 67 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 59 / 90 % | 72 / 76 % | 16 / 40 % | 11 / 26 % | 14 / 29 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 32 / 53 % | 0 / 0 % | 0 / 0 % | 64 / 82 % | 20 / 42 % | 66 / 81 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 17 / 44 % | 0 / 0 % | 59 / 68 % | 19 / 45 % | 9 / 23 % | 8 / 18 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 38 / 58 % | 44 / 94 % | 40 / 67 % | 46 / 73 % | 14 / 38 % | 47 / 71 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 44 / 68 % | 9 / 22 % | 11 / 24 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 20 / 62 % | 40 / 54 % | 11 / 34 % | 8 / 18 % | 9 / 19 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 32 / 77 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 11 / 24 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 31 / 90 % | 17 / 50 % | 24 / 55 % | 8 / 20 % | 15 / 31 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 18 / 39 % | 0 / 0 % | 15 / 48 % | 31 / 58 % | 10 / 24 % | 18 / 34 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 20 / 50 % | 28 / 55 % | 0 / 0 % | 18 / 39 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 36 % | 26 / 62 % | 1 / 9 % | 16 / 41 % | 6 / 21 % | 23 / 48 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 39 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 39 % | 4 / 12 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 13 / 64 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 13 / 63 % | 0 / 0 % | 5 / 13 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 8 / 21 % | 2 / 7 % | 9 / 19 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 7 / 42 % | 2 / 18 % | 9 / 25 % | 3 / 10 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 8 / 20 % | 5 / 12 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 5 / 11 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 7 / 24 % | 4 / 11 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 6 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 6 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 4 / 24 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | – | – |
