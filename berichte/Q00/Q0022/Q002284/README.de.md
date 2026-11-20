[English](README.md) · [Deutsch](README.de.md)

# Announcing Inspect Evals | AISI Work

Bericht Q002284 · Quelle aisi.gov.uk · Datum 2024-11-13 · [Original öffnen](https://www.aisi.gov.uk/blog/inspect-evals)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Inspect Evals ist laut Bericht eine gemeinschaftliche Sammlung quelloffener Sprachmodell-Benchmarks, die verschiedene Themen von Programmierung bis Sicherheit abdeckt und auf dem Framework Inspect AI aufbaut. Das Projekt soll Evaluationen leichter ausführbar und gemeinschaftliche Beiträge einfacher machen; unabhängige Qualitäts- oder Vergleichsdaten liefert die Ankündigung nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 46 / 69 % | 79 / 96 % | – | 95 / 100 % | 18 / 31 % | 74 / 85 % | 76 / 88 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 27 / 53 % | 78 / 93 % | – | 71 / 81 % | 42 / 63 % | 29 / 48 % | 9 / 23 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 14 / 40 % | 48 / 91 % | – | 71 / 87 % | 11 / 31 % | 7 / 17 % | 3 / 11 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 53 % | 51 / 95 % | – | 45 / 91 % | 33 / 64 % | 44 / 69 % | 41 / 63 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 40 / 81 % | – | 9 / 41 % | 47 / 70 % | 17 / 42 % | 15 / 33 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 14 / 36 % | 39 / 69 % | – | 45 / 81 % | 16 / 34 % | 14 / 30 % | 7 / 17 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 13 / 40 % | 35 / 66 % | – | 1 / 25 % | 23 / 51 % | 14 / 35 % | 6 / 16 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 28 / 79 % | – | 22 / 41 % | 18 / 40 % | 6 / 14 % | 3 / 11 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 7 / 40 % | 26 / 56 % | – | 0 / 0 % | 8 / 23 % | 5 / 10 % | 1 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 45 % | 0 / 0 % | – | 26 / 69 % | 21 / 48 % | 10 / 23 % | 6 / 17 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 13 / 43 % | – | 10 / 38 % | 23 / 56 % | 21 / 45 % | 8 / 21 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 23 / 45 % | 21 / 70 % | – | 18 / 63 % | 21 / 50 % | 20 / 49 % | 6 / 21 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 21 / 50 % | 14 / 64 % | – | 0 / 0 % | 13 / 44 % | 8 / 23 % | 2 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 19 / 68 % | – | 2 / 17 % | 10 / 33 % | 9 / 20 % | 3 / 12 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 17 / 38 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 13 / 41 % | 0 / 0 % | – | 0 / 0 % | 16 / 45 % | 9 / 25 % | 3 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 16 / 32 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 15 / 47 % | 0 / 0 % | – | 11 / 36 % | 14 / 36 % | 9 / 18 % | 3 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 0 / 8 % | 9 / 23 % | 3 / 8 % | 1 / 5 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 22 % | 4 / 10 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 5 / 28 % | 8 / 24 % | 5 / 12 % | 2 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 7 / 17 % | 1 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 5 / 14 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 5 / 12 % | 1 / 7 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 1 / 14 % | 5 / 11 % | 0 / 0 % | 0 / 2 % |
