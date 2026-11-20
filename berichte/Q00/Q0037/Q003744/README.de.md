[English](README.md) · [Deutsch](README.de.md)

# Computer use, Claude 3.5 Sonnet, and Claude 3.5 Haiku

Bericht Q003744 · Quelle anthropic.com · Datum 2024-10-22 · [Original öffnen](https://www.anthropic.com/news/3-5-models-and-computer-use)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic stellt ein leistungsverbessertes Claude 3.5 Sonnet, das schnellere Claude 3.5 Haiku und eine Beta zur Computerbedienung durch Claude vor. Die veröffentlichten Benchmarkwerte sind Unternehmensangaben; Anthropic räumt ein, dass Computer use noch experimentell und fehleranfällig ist und zunächst nur für risikoarme Aufgaben empfohlen wird.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 49 % | 49 / 87 % | – | 97 / 99 % | 43 / 68 % | 40 / 64 % | 6 / 21 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 32 / 51 % | 97 / 98 % | – | 87 / 89 % | 62 / 78 % | 46 / 58 % | 12 / 21 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 51 % | 61 / 89 % | – | 96 / 98 % | 40 / 69 % | 52 / 72 % | 16 / 35 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 34 / 56 % | 85 / 98 % | – | 96 / 99 % | 49 / 71 % | 29 / 50 % | 12 / 33 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 12 / 30 % | 34 / 65 % | – | 85 / 91 % | 16 / 46 % | 20 / 41 % | 4 / 13 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 28 / 44 % | 32 / 73 % | – | 80 / 91 % | 45 / 69 % | 28 / 44 % | 10 / 21 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 40 % | 61 / 90 % | – | 79 / 88 % | 26 / 50 % | 27 / 42 % | 5 / 12 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 22 / 47 % | – | 75 / 88 % | 7 / 20 % | 5 / 8 % | 0 / 3 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 25 / 50 % | 73 / 96 % | – | 73 / 89 % | 34 / 62 % | 46 / 65 % | 9 / 23 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 31 % | 64 / 94 % | – | 18 / 40 % | 14 / 39 % | 13 / 26 % | 2 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 22 / 45 % | 63 / 96 % | – | 22 / 57 % | 41 / 68 % | 31 / 52 % | 6 / 17 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 15 / 36 % | 13 / 75 % | – | 57 / 79 % | 11 / 40 % | 7 / 22 % | 1 / 7 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 21 % | 51 / 85 % | – | 48 / 71 % | 9 / 26 % | 7 / 19 % | 1 / 6 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 7 / 40 % | – | 46 / 67 % | 35 / 60 % | 10 / 22 % | 5 / 16 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 20 / 46 % | – | 46 / 66 % | 17 / 37 % | 11 / 21 % | 5 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 20 / 44 % | 0 / 0 % | – | 44 / 57 % | 39 / 63 % | 14 / 29 % | 9 / 20 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 41 / 82 % | – | 0 / 0 % | 14 / 33 % | 9 / 18 % | 2 / 7 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 23 % | 12 / 78 % | – | 41 / 62 % | 8 / 21 % | 5 / 11 % | 2 / 8 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 18 / 68 % | – | 39 / 63 % | 8 / 21 % | 0 / 0 % | 1 / 5 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 9 / 21 % | 29 / 70 % | – | 0 / 0 % | 18 / 35 % | 13 / 25 % | 4 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 14 / 26 % | 26 / 72 % | – | 27 / 46 % | 9 / 24 % | 6 / 13 % | 1 / 5 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 26 / 76 % | – | 13 / 21 % | 11 / 29 % | 7 / 14 % | 2 / 7 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 31 % | 0 / 0 % | – | 26 / 47 % | 11 / 31 % | 7 / 15 % | 2 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 24 / 46 % | 0 / 0 % | 1 / 4 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 21 / 43 % | 13 / 57 % | – | 17 / 32 % | 17 / 45 % | 14 / 28 % | 5 / 12 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 35 % | 17 / 53 % | – | 2 / 16 % | 13 / 33 % | 14 / 30 % | 6 / 18 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 11 / 34 % | 0 / 0 % | – | 0 / 0 % | 10 / 32 % | 12 / 28 % | 2 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 29 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 10 / 20 % | 1 / 5 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 26 % | 0 / 0 % | – | 3 / 13 % | 11 / 30 % | 7 / 16 % | 3 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 11 / 19 % | 0 / 0 % | – | 0 / 0 % | 10 / 27 % | 6 / 17 % | 1 / 4 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 25 % | 9 / 20 % | 0 / 2 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 20 % | 5 / 10 % | 2 / 7 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 20 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 5 / 9 % | 1 / 4 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 13 % | 5 / 9 % | 1 / 5 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 4 / 7 % | 1 / 3 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 6 / 12 % | 1 / 3 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 1 / 4 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 9 % | 1 / 2 % |
