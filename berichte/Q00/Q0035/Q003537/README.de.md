[English](README.md) · [Deutsch](README.de.md)

# Claude Fable 5 and Claude Mythos 5

Bericht Q003537 · Quelle anthropic.com · Datum 2026-06-09 · [Original öffnen](https://www.anthropic.com/news/claude-fable-5-mythos-5)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic stellt Fable 5 als leistungsstarkes, allgemein verfügbares Modell mit vorsichtigen Schutzfiltern vor; Mythos 5 soll ausgewählten Partnern mit teilweise aufgehobenen Filtern zugänglich sein. Der Bericht nennt starke Ergebnisse in Programmierung und Forschung, räumt Risiken und falsch positive Filter ein und gibt Unternehmensangaben wieder, die im Text meist nicht unabhängig bestätigt sind. Zwei Hinweise am Anfang widersprechen sich dazu, ob der Zugang ausgesetzt oder wiederhergestellt wurde; der Haupttext löst das nicht auf.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 58 / 73 % | 98 / 99 % | – | 100 / 100 % | 88 / 93 % | 83 / 89 % | 50 / 67 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 48 / 62 % | 91 / 97 % | – | 100 / 100 % | 85 / 91 % | 82 / 90 % | 59 / 78 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 50 / 65 % | 94 / 99 % | – | 97 / 99 % | 70 / 83 % | 81 / 88 % | 37 / 56 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 42 % | 97 / 100 % | – | 91 / 95 % | 46 / 68 % | 60 / 73 % | 14 / 25 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 41 / 59 % | 74 / 93 % | – | 96 / 97 % | 80 / 89 % | 87 / 92 % | 73 / 85 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 37 / 57 % | 93 / 99 % | – | 96 / 98 % | 66 / 84 % | 54 / 76 % | 45 / 64 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 41 / 60 % | 95 / 99 % | – | 95 / 97 % | 69 / 84 % | 86 / 92 % | 54 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 37 / 56 % | 89 / 96 % | – | 90 / 96 % | 68 / 82 % | 51 / 66 % | 18 / 37 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 36 / 55 % | 62 / 91 % | – | 89 / 92 % | 75 / 86 % | 81 / 87 % | 35 / 53 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 47 / 72 % | – | 89 / 94 % | 11 / 28 % | 8 / 17 % | 5 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 76 / 95 % | – | 88 / 92 % | 14 / 37 % | 10 / 21 % | 5 / 14 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 20 / 89 % | – | 86 / 92 % | 58 / 79 % | 12 / 29 % | 12 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 29 / 50 % | 57 / 80 % | – | 86 / 93 % | 53 / 71 % | 48 / 70 % | 47 / 67 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 43 / 59 % | 73 / 85 % | – | 51 / 73 % | 77 / 87 % | 85 / 89 % | 48 / 66 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 68 / 88 % | – | 83 / 91 % | 15 / 39 % | 12 / 25 % | 6 / 15 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 23 / 47 % | 69 / 96 % | – | 78 / 88 % | 26 / 53 % | 29 / 48 % | 4 / 13 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 74 / 99 % | – | 43 / 76 % | 41 / 64 % | 17 / 42 % | 12 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 28 / 79 % | – | 71 / 85 % | 15 / 35 % | 12 / 23 % | 6 / 16 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 30 % | 0 / 0 % | – | 65 / 82 % | 12 / 34 % | 13 / 32 % | 6 / 15 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 26 / 48 % | 62 / 95 % | – | 50 / 71 % | 60 / 79 % | 48 / 68 % | 17 / 32 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 41 / 76 % | – | 62 / 76 % | 17 / 40 % | 12 / 23 % | 2 / 7 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 35 / 52 % | 30 / 74 % | – | 60 / 79 % | 60 / 79 % | 34 / 55 % | 15 / 33 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 51 / 96 % | – | 37 / 49 % | 21 / 44 % | 14 / 26 % | 6 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 42 % | 44 / 61 % | – | 35 / 52 % | 35 / 60 % | 29 / 48 % | 10 / 24 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 38 / 72 % | – | 0 / 0 % | 12 / 27 % | 14 / 28 % | 0 / 2 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 15 / 32 % | 37 / 79 % | – | 24 / 32 % | 28 / 49 % | 18 / 36 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 24 / 49 % | 0 / 0 % | – | 0 / 0 % | 30 / 55 % | 31 / 48 % | 4 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 23 / 77 % | – | 31 / 41 % | 19 / 44 % | 20 / 41 % | 8 / 17 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 20 / 47 % | – | 29 / 43 % | 13 / 32 % | 13 / 25 % | 2 / 6 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 25 % | 22 / 34 % | 3 / 5 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 22 / 68 % | – | 0 / 0 % | 8 / 17 % | 11 / 18 % | 5 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 21 / 82 % | – | 20 / 37 % | 14 / 34 % | 14 / 26 % | 5 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 19 / 40 % | 11 / 23 % | 1 / 4 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 19 / 36 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 28 % | 9 / 24 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 22 % | 12 / 21 % | 3 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 12 / 45 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 4 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 1 / 11 % | 11 / 24 % | 0 / 0 % | 4 / 8 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 26 % | 8 / 14 % | 2 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 21 % | 0 / 0 % | 1 / 5 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 2 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 7 / 20 % | 8 / 18 % | 8 / 14 % | 3 / 8 % |
