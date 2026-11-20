[English](README.md) · [Deutsch](README.de.md)

# Details about METR's evaluation of OpenAI GPT-5

Bericht Q002327 · Quelle metr.org · Datum 2025-08-07 · [Original öffnen](https://metr.org/evaluations/gpt-5-report/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

METR schätzt GPT-5s 50-Prozent-Zeithorizont für die untersuchten Software- und KI-Forschungsaufgaben auf 2 Stunden und 17 Minuten und hält das Modell damit weit von den eigenen vorläufigen Schwellen für katastrophale Risiken durch Forschungsautomatisierung, Replikation oder Sabotage entfernt. Es fand zwar Situationsbewusstsein, aber keine überzeugenden Hinweise auf systematisches Sandbagging; die Einschätzung bleibt durch künstliche Tests, unvollkommene Überwachung und die begrenzte Aussagekraft der Messwerte eingeschränkt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 58 / 78 % | 99 / 100 % | – | 100 / 100 % | 89 / 94 % | 80 / 90 % | 89 / 94 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 47 / 65 % | 98 / 99 % | – | 99 / 100 % | 72 / 86 % | 72 / 86 % | 83 / 92 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 43 / 62 % | 99 / 100 % | – | 92 / 96 % | 61 / 81 % | 17 / 36 % | 54 / 74 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 47 / 65 % | 89 / 94 % | – | 99 / 100 % | 46 / 66 % | 54 / 70 % | 55 / 69 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 36 / 59 % | 98 / 99 % | – | 97 / 99 % | 56 / 77 % | 25 / 45 % | 43 / 59 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 51 / 69 % | 96 / 100 % | – | 95 / 97 % | 69 / 85 % | 54 / 69 % | 50 / 67 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 57 / 73 % | 96 / 99 % | – | 96 / 99 % | 79 / 88 % | 64 / 82 % | 68 / 83 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 37 / 59 % | 42 / 93 % | – | 96 / 98 % | 70 / 86 % | 37 / 63 % | 26 / 50 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 42 / 64 % | 86 / 96 % | – | 95 / 97 % | 80 / 89 % | 31 / 57 % | 87 / 93 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 33 / 58 % | 55 / 89 % | – | 94 / 97 % | 50 / 73 % | 8 / 23 % | 36 / 57 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 36 / 60 % | 90 / 100 % | – | 68 / 88 % | 77 / 89 % | 53 / 78 % | 78 / 90 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 34 / 57 % | 68 / 94 % | – | 90 / 95 % | 37 / 66 % | 16 / 39 % | 43 / 69 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 30 / 65 % | – | 74 / 83 % | 11 / 30 % | 1 / 3 % | 7 / 12 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 63 / 76 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 10 / 32 % | 30 / 58 % | 12 / 26 % | 61 / 73 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 42 / 75 % | – | 59 / 76 % | 12 / 35 % | 6 / 15 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 59 / 91 % | – | 17 / 47 % | 6 / 18 % | 1 / 5 % | 4 / 9 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 40 / 93 % | – | 57 / 72 % | 9 / 24 % | 0 / 0 % | 7 / 12 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 56 / 86 % | – | 0 / 0 % | 7 / 20 % | 2 / 6 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 28 / 55 % | 15 / 56 % | – | 0 / 0 % | 29 / 57 % | 7 / 18 % | 49 / 69 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 28 / 55 % | 41 / 81 % | – | 30 / 55 % | 45 / 70 % | 10 / 24 % | 33 / 53 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 28 / 93 % | – | 43 / 66 % | 6 / 16 % | 1 / 4 % | 9 / 15 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 36 / 77 % | – | 0 / 0 % | 6 / 17 % | 3 / 8 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 31 / 63 % | – | 0 / 0 % | 16 / 37 % | 0 / 0 % | 12 / 22 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 15 / 41 % | 13 / 70 % | – | 6 / 30 % | 25 / 52 % | 8 / 22 % | 20 / 35 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 21 / 88 % | – | 12 / 31 % | 17 / 45 % | 3 / 12 % | 9 / 22 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 21 / 33 % | 8 / 18 % | 0 / 0 % | 10 / 16 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 20 / 52 % | 7 / 24 % | 2 / 6 % | 4 / 9 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 19 / 75 % | – | 0 / 7 % | 11 / 25 % | 2 / 5 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 16 / 56 % | – | 1 / 18 % | 6 / 17 % | 2 / 4 % | 4 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 33 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 11 / 89 % | – | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 18 % | 1 / 3 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 8 / 60 % | – | 0 / 0 % | 4 / 12 % | 1 / 5 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 1 / 5 % | 5 / 8 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 2 / 4 % | 4 / 6 % |
