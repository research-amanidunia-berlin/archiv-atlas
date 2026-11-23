[English](README.md) · [Deutsch](README.de.md)

# Language modelling at scale: Gopher, ethical considerations, and retrieval

Bericht Q003143 · Quelle deepmind.google · Datum 2021-12-08 · [Original öffnen](https://deepmind.google/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

DeepMind berichtet, dass Gopher bei manchen Sprachaufgaben Fortschritte erzielt, aber weiterhin Stereotype spiegeln und falsche Antworten selbstsicher verbreiten kann; bestehende Prüfverfahren erfassten laut Bericht manche Risiken nicht ausreichend. Die Retrieval-Architektur RETRO soll mit deutlich weniger Parametern vergleichbare Leistung erreichen und durch abgerufene Textpassagen Einblicke in die Herkunft von Vorhersagen ermöglichen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 42 / 64 % | 99 / 100 % | 93 / 98 % | 71 / 85 % | 45 / 67 % | 58 / 74 % | 64 / 76 % | 47 / 66 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 25 / 49 % | 45 / 89 % | 96 / 99 % | 23 / 57 % | 10 / 29 % | 23 / 57 % | 8 / 30 % | 14 / 32 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 50 / 85 % | 93 / 98 % | 14 / 43 % | 3 / 20 % | 14 / 45 % | 1 / 10 % | 38 / 59 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 29 / 52 % | 73 / 96 % | 83 / 97 % | 35 / 66 % | 11 / 38 % | 34 / 66 % | 14 / 52 % | 39 / 64 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 12 / 59 % | 76 / 92 % | 16 / 42 % | 2 / 13 % | 5 / 14 % | 1 / 7 % | 17 / 44 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 15 / 42 % | 33 / 82 % | 66 / 92 % | 12 / 34 % | 6 / 23 % | 12 / 41 % | 7 / 28 % | 30 / 57 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 44 % | 21 / 62 % | 66 / 85 % | 17 / 44 % | 8 / 22 % | 15 / 40 % | 3 / 14 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 18 / 73 % | 63 / 87 % | 26 / 58 % | 7 / 23 % | 24 / 56 % | 5 / 21 % | 14 / 38 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 52 / 94 % | 38 / 83 % | 12 / 34 % | 6 / 17 % | 11 / 26 % | 2 / 14 % | 38 / 63 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 19 / 40 % | 12 / 74 % | 51 / 83 % | 18 / 50 % | 4 / 19 % | 8 / 39 % | 3 / 15 % | 21 / 47 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 32 % | 45 / 86 % | 10 / 41 % | 7 / 27 % | 1 / 8 % | 5 / 12 % | 0 / 4 % | 13 / 40 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 16 / 57 % | 3 / 19 % | 6 / 19 % | 1 / 10 % | 4 / 15 % | 0 / 5 % | 40 / 64 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 33 % | 35 / 82 % | 30 / 77 % | 8 / 29 % | 2 / 12 % | 8 / 31 % | 1 / 9 % | 13 / 37 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 28 / 70 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 5 / 13 % | 0 / 3 % | 8 / 28 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 9 / 95 % | 20 / 60 % | 11 / 29 % | 9 / 24 % | 17 / 42 % | 2 / 10 % | 26 / 59 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 24 / 77 % | 4 / 45 % | 9 / 26 % | 2 / 11 % | 5 / 16 % | 1 / 10 % | 8 / 34 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 22 / 82 % | 2 / 32 % | 14 / 39 % | 3 / 14 % | 8 / 24 % | 1 / 9 % | 6 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 16 / 38 % | 12 / 40 % | 2 / 17 % | 19 / 47 % | 2 / 11 % | 13 / 27 % | 1 / 5 % | 10 / 32 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 18 / 67 % | 7 / 23 % | 2 / 10 % | 5 / 16 % | 0 / 6 % | 3 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 17 / 81 % | 0 / 0 % | 7 / 15 % | 1 / 6 % | 5 / 10 % | 0 / 0 % | 3 / 15 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 30 % | 17 / 97 % | 16 / 50 % | 7 / 26 % | 2 / 11 % | 7 / 22 % | 0 / 4 % | 15 / 40 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 34 % | 16 / 83 % | 11 / 66 % | 11 / 36 % | 1 / 15 % | 7 / 21 % | 0 / 5 % | 6 / 22 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 16 / 82 % | 0 / 0 % | 6 / 20 % | 1 / 7 % | 7 / 20 % | 1 / 6 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 16 / 66 % | 0 / 0 % | 9 / 24 % | 2 / 9 % | 7 / 16 % | 0 / 3 % | 5 / 24 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 16 / 56 % | 3 / 26 % | 6 / 21 % | 1 / 9 % | 4 / 13 % | 0 / 4 % | 4 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 13 / 53 % | 0 / 0 % | 5 / 12 % | 1 / 6 % | 5 / 11 % | 0 / 2 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 12 / 34 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 1 / 9 % | 7 / 21 % | 0 / 4 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 6 / 30 % | 12 / 73 % | 1 / 24 % | 6 / 18 % | 1 / 11 % | 5 / 18 % | 0 / 4 % | 6 / 24 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 3 % | 3 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 7 / 27 % | 5 / 15 % | 1 / 5 % | 3 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 26 % | 1 / 8 % | 4 / 12 % | 1 / 6 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 2 / 23 % | 6 / 16 % | 1 / 7 % | 6 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 3 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 4 % | 2 / 5 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 6 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
