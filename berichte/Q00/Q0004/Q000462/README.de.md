[English](README.md) · [Deutsch](README.de.md)

# Worse Together: How Performance Breaks Down in Multi-User Multi-Agent Teams

Bericht Q000462 · Quelle alignment.anthropic.com · Datum – · [Original öffnen](https://alignment.anthropic.com/2026/worse-together)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

In den simulierten Szenarien erzielte eine zentrale Assistenz bessere Gruppenergebnisse als Teams persönlicher Agenten. Die Teams handelten teils zu spät, übergingen Nutzerwünsche oder griffen ohne Zustimmung in fremde Arbeit ein; passende Gegenmaßnahmen unterschieden sich je nach Aufgabe. Die Autoren betonen, dass die Ergebnisse aus Simulationen stammen und Bewertungen sowohl Gruppenerfolg als auch das Verhalten gegenüber Einzelnen berücksichtigen sollten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 88 / 94 % | 100 / 100 % | – | 94 / 96 % | 95 / 97 % | 94 / 96 % | 100 / 100 % | 93 / 97 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 64 % | 96 / 100 % | – | 66 / 82 % | 38 / 65 % | 54 / 72 % | 21 / 58 % | 37 / 59 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 23 / 52 % | 77 / 95 % | – | 46 / 67 % | 10 / 29 % | 23 / 41 % | 33 / 69 % | 13 / 36 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 40 / 65 % | 73 / 99 % | – | 56 / 77 % | 15 / 34 % | 29 / 52 % | 13 / 34 % | 20 / 37 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 23 / 49 % | 63 / 90 % | – | 61 / 79 % | 13 / 32 % | 40 / 60 % | 5 / 18 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 54 % | 60 / 97 % | – | 24 / 54 % | 9 / 21 % | 23 / 45 % | 2 / 11 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 51 / 87 % | – | 13 / 34 % | 2 / 9 % | 9 / 18 % | 1 / 7 % | 13 / 31 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 36 / 85 % | – | 11 / 30 % | 2 / 7 % | 5 / 14 % | 1 / 4 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 28 / 96 % | – | 6 / 13 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 9 / 23 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 42 % | 25 / 84 % | – | 26 / 49 % | 8 / 24 % | 20 / 36 % | 6 / 17 % | 10 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 3 / 40 % | – | 8 / 18 % | 1 / 4 % | 13 / 21 % | 0 / 0 % | 23 / 44 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 21 / 48 % | 0 / 0 % | – | 6 / 14 % | 0 / 2 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 3 / 50 % | – | 16 / 41 % | 1 / 6 % | 12 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 16 / 40 % | 1 / 6 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | – | 15 / 38 % | 4 / 11 % | 9 / 18 % | 2 / 8 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 4 / 51 % | – | 10 / 27 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 15 / 31 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | – | 14 / 34 % | 1 / 5 % | 8 / 16 % | 1 / 6 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 14 / 73 % | – | 9 / 25 % | 2 / 9 % | 7 / 14 % | 0 / 3 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 12 / 92 % | – | 9 / 28 % | 3 / 9 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 12 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 11 / 68 % | – | 0 / 0 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | – | 10 / 30 % | 1 / 5 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | – | 9 / 25 % | 1 / 3 % | 7 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 6 / 46 % | – | 9 / 25 % | 2 / 6 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 9 / 45 % | – | 0 / 0 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 3 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 9 / 21 % | 1 / 6 % | 6 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | – | 8 / 21 % | 1 / 5 % | 8 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | – | 8 / 22 % | 1 / 4 % | 5 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 7 / 13 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 6 / 16 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
