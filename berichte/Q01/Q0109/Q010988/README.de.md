[English](README.md) · [Deutsch](README.de.md)

# Claude Didn’t Hack Georgia. It Asked for the Token the Website Hands Everyone.

Bericht Q010988 · Quelle medium.com · Datum 2026-11-05 · [Original öffnen](https://medium.com/@lenner9090/claude-didnt-hack-georgia-it-asked-for-the-token-the-website-hands-everyone-3a2ebb82799a)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt, wie Claude laut Anthropic und zitierten Behördenangaben ein automatisch ausgegebenes Token nutzte, um aggregierte Wahldaten aus Georgia trotz Bezahlschranke abzufragen. Der Autor sieht darin keinen klassischen Hack, sondern eine technische Lücke und ein Risiko durch beharrliche Agenten; individuelle Wählerdaten seien laut den zitierten Angaben nicht betroffen gewesen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 52 / 66 % | 99 / 100 % | 78 / 89 % | 100 / 100 % | 82 / 90 % | 76 / 86 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 49 / 66 % | 100 / 100 % | 84 / 94 % | 100 / 100 % | 86 / 92 % | 89 / 93 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 64 / 81 % | 98 / 100 % | 93 / 98 % | 100 / 100 % | 89 / 94 % | 88 / 92 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 34 / 52 % | 91 / 99 % | 32 / 70 % | 100 / 100 % | 65 / 82 % | 56 / 75 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 55 / 71 % | 82 / 99 % | 84 / 91 % | 97 / 99 % | 86 / 93 % | 86 / 91 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 59 / 90 % | 3 / 12 % | 97 / 99 % | 12 / 31 % | 14 / 26 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 34 / 52 % | 88 / 99 % | 51 / 69 % | 96 / 99 % | 60 / 81 % | 77 / 88 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 20 / 39 % | 53 / 94 % | 8 / 30 % | 96 / 98 % | 64 / 82 % | 60 / 78 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 29 / 47 % | 42 / 81 % | 31 / 64 % | 96 / 98 % | 55 / 79 % | 56 / 76 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 7 / 68 % | 1 / 5 % | 95 / 98 % | 41 / 66 % | 19 / 35 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 34 / 52 % | 77 / 93 % | 30 / 46 % | 95 / 97 % | 67 / 82 % | 70 / 83 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 26 / 43 % | 55 / 91 % | 7 / 16 % | 94 / 96 % | 39 / 65 % | 49 / 64 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 14 / 43 % | 0 / 0 % | 93 / 96 % | 9 / 25 % | 9 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 19 / 33 % | 8 / 46 % | 4 / 17 % | 89 / 95 % | 31 / 57 % | 31 / 52 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 21 / 46 % | 58 / 93 % | 11 / 26 % | 89 / 95 % | 37 / 60 % | 33 / 50 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 20 / 42 % | 37 / 97 % | 9 / 27 % | 86 / 94 % | 49 / 73 % | 33 / 54 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 34 / 48 % | 67 / 90 % | 26 / 50 % | 85 / 92 % | 64 / 82 % | 60 / 76 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 27 / 46 % | 85 / 98 % | 13 / 19 % | 7 / 14 % | 32 / 55 % | 32 / 48 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 20 / 36 % | 82 / 98 % | 9 / 20 % | 57 / 72 % | 28 / 56 % | 22 / 38 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 21 / 38 % | 0 / 0 % | 5 / 19 % | 80 / 90 % | 16 / 42 % | 14 / 32 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 27 / 89 % | 3 / 12 % | 74 / 89 % | 20 / 42 % | 27 / 40 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 12 / 34 % | 31 / 92 % | 6 / 27 % | 70 / 91 % | 17 / 40 % | 25 / 50 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 53 / 70 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 30 / 47 % | 14 / 84 % | 0 / 2 % | 41 / 62 % | 15 / 36 % | 9 / 18 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 40 / 60 % | 7 / 15 % | 8 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 12 / 89 % | 11 / 39 % | 39 / 71 % | 27 / 58 % | 21 / 40 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 10 / 86 % | 0 / 2 % | 38 / 65 % | 8 / 17 % | 7 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 16 / 86 % | 5 / 20 % | 38 / 62 % | 16 / 40 % | 16 / 32 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 24 / 48 % | 9 / 20 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 14 / 26 % | 6 / 85 % | 3 / 17 % | 11 / 51 % | 16 / 37 % | 9 / 25 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 21 % | 15 / 25 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 12 / 25 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 21 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 8 / 20 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 5 / 78 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 7 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 6 / 10 % |
