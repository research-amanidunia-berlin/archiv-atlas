[English](README.md) · [Deutsch](README.de.md)

# How our Control Red Team is stress-testing frontier monitors

Bericht Q001170 · Quelle aisi.gov.uk · Datum 2026-07-23 · [Original öffnen](https://www.aisi.gov.uk/blog/how-our-new-control-red-team-is-stress-testing-frontier-monitors)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

AISI beschreibt Tests seines neuen Control Red Teams an internen Monitoren bei Google DeepMind und Anthropic und berichtet von Schwachstellen, die in Verbesserungen eingeflossen seien. Eine frühe automatisierte Suche fand laut Bericht deutlich niedrigere Verdachtswerte als eine Best-of-N-Methode, doch die Experimente sind begrenzt und werfen offene Fragen zur Realitätsnähe der Angriffe und zur Gesamtbewertung der Sicherheit auf.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 30 / 55 % | 65 / 94 % | 97 / 100 % | 75 / 87 % | 27 / 59 % | 61 / 78 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 33 / 55 % | 65 / 83 % | 95 / 97 % | 50 / 68 % | 30 / 48 % | 39 / 53 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 59 % | 57 / 92 % | 93 / 98 % | 66 / 83 % | 42 / 70 % | 64 / 80 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 39 / 58 % | 68 / 94 % | 89 / 97 % | 52 / 74 % | 45 / 70 % | 57 / 74 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 42 / 62 % | 72 / 98 % | 88 / 96 % | 65 / 82 % | 31 / 58 % | 60 / 75 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 27 / 52 % | 30 / 75 % | 83 / 94 % | 9 / 19 % | 24 / 52 % | 50 / 71 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 43 % | 23 / 76 % | 77 / 89 % | 27 / 50 % | 9 / 19 % | 22 / 36 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 34 / 55 % | 20 / 59 % | 38 / 64 % | 59 / 79 % | 21 / 47 % | 72 / 83 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 19 / 42 % | 16 / 57 % | 61 / 89 % | 42 / 66 % | 12 / 31 % | 24 / 39 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 42 / 91 % | 41 / 81 % | 19 / 48 % | 7 / 19 % | 16 / 32 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 33 / 55 % | 25 / 83 % | 38 / 62 % | 29 / 58 % | 16 / 33 % | 27 / 44 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 25 / 51 % | 0 / 0 % | 36 / 59 % | 31 / 55 % | 10 / 26 % | 16 / 25 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 39 % | 22 / 77 % | 33 / 59 % | 25 / 51 % | 12 / 37 % | 30 / 51 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 51 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 24 / 51 % | 9 / 21 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 17 / 40 % | 21 / 61 % | 23 / 55 % | 13 / 33 % | 3 / 11 % | 12 / 26 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 9 / 29 % | 23 / 49 % | 5 / 14 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 30 % | 0 / 0 % | 18 / 52 % | 6 / 15 % | 3 / 10 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 38 % | 6 / 21 % | 17 / 40 % | 5 / 18 % | 8 / 18 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 17 / 50 % | 10 / 36 % | 7 / 14 % | 2 / 7 % | 0 / 0 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 12 / 65 % | 0 / 0 % | 11 / 29 % | 2 / 6 % | 9 / 18 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 2 / 7 % | 5 / 9 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 8 / 17 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 5 / 39 % | 8 / 21 % | 2 / 9 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 7 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 3 % | 5 / 11 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 4 / 11 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 3 / 9 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 3 / 25 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | – | – |
