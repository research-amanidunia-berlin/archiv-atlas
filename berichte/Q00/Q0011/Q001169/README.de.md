[English](README.md) · [Deutsch](README.de.md)

# Piloting the world's first double-blind AI evaluations

Bericht Q001169 · Quelle deepmind.google · Datum 2026-08-27 · [Original öffnen](https://deepmind.google/blog/piloting-the-worlds-first-double-blind-ai-evaluations/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google DeepMind beschreibt einen Pilotversuch, bei dem ein Gemini-Flash-Lite-Modell anhand vertraulicher Benchmarks doppelt verblindet geprüft werden soll. Kryptografische Kontrollen in Google Cloud sollen laut Beitrag sowohl die Testfragen als auch die Modellgewichte vor der jeweils anderen Seite schützen. Konkrete Ergebnisse und Details zur Umsetzung enthält der vorliegende Text nicht; er verweist dafür auf einen technischen Bericht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 50 / 68 % | 40 / 86 % | 62 / 79 % | 99 / 100 % | 50 / 73 % | 77 / 86 % | 62 / 72 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 58 / 74 % | 95 / 99 % | 94 / 98 % | 99 / 100 % | 71 / 85 % | 90 / 95 % | 86 / 91 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 49 / 68 % | 79 / 93 % | 68 / 85 % | 99 / 100 % | 67 / 81 % | 65 / 78 % | 35 / 51 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 43 / 67 % | 67 / 89 % | 60 / 83 % | 91 / 98 % | 17 / 31 % | 69 / 81 % | 79 / 87 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 43 % | 53 / 83 % | 6 / 22 % | 76 / 90 % | 25 / 46 % | 14 / 28 % | 27 / 46 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 25 / 45 % | 35 / 79 % | 6 / 20 % | 75 / 91 % | 18 / 45 % | 6 / 19 % | 17 / 40 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 20 / 42 % | 51 / 85 % | 1 / 4 % | 75 / 86 % | 20 / 42 % | 5 / 14 % | 8 / 18 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 26 / 58 % | 0 / 0 % | 73 / 85 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 21 / 44 % | 69 / 85 % | 6 / 12 % | 31 / 47 % | 36 / 57 % | 8 / 20 % | 21 / 36 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 21 / 45 % | 44 / 79 % | 6 / 25 % | 62 / 88 % | 29 / 55 % | 10 / 25 % | 24 / 44 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 30 / 59 % | 49 / 87 % | 1 / 5 % | 0 / 0 % | 10 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 30 / 53 % | 25 / 95 % | 16 / 43 % | 47 / 76 % | 46 / 70 % | 27 / 43 % | 17 / 38 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 35 / 89 % | 0 / 0 % | 47 / 66 % | 6 / 20 % | 2 / 8 % | 4 / 12 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 45 / 93 % | 1 / 6 % | 0 / 0 % | 9 / 32 % | 0 / 0 % | 10 / 25 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 8 / 51 % | 0 / 0 % | 0 / 0 % | 34 / 55 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 11 / 32 % | 0 / 0 % | 0 / 0 % | 33 / 70 % | 7 / 22 % | 2 / 10 % | 6 / 16 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 31 / 58 % | 0 / 0 % | 21 / 47 % | 8 / 18 % | 2 / 10 % | 5 / 13 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 17 / 56 % | 8 / 25 % | 0 / 0 % | 20 / 48 % | 23 / 42 % | 27 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 23 / 84 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 5 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 23 / 74 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 22 / 76 % | 0 / 0 % | 1 / 14 % | 9 / 25 % | 0 / 0 % | 6 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 18 / 44 % | 0 / 0 % | 20 / 47 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 15 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 9 % | 9 / 19 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 11 / 52 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 7 / 17 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 2 / 6 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 6 / 15 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
