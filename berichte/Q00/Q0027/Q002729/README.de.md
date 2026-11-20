[English](README.md) · [Deutsch](README.de.md)

# Challenges in red teaming AI systems

Bericht Q002729 · Quelle anthropic.com · Datum 2024-06-12 · [Original öffnen](https://www.anthropic.com/news/challenges-in-red-teaming-ai-systems)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt ausgewählte Red-Teaming-Methoden von Anthropic – von fachgeleiteten und mehrsprachigen Tests bis zu automatisierten, multimodalen und gemeinschaftlichen Prüfungen – und plädiert für gemeinsame Standards. Er empfiehlt einen iterativen Übergang von qualitativen Tests zu automatisierten Auswertungen; vergleichende Wirksamkeitsdaten liefert der Text nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 24 / 54 % | 16 / 91 % | – | 93 / 97 % | 28 / 59 % | 17 / 46 % | 13 / 33 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 38 / 68 % | 85 / 99 % | – | 90 / 99 % | 47 / 72 % | 75 / 86 % | 64 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 56 % | 84 / 99 % | – | 89 / 99 % | 55 / 81 % | 61 / 81 % | 52 / 75 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 32 / 54 % | 54 / 95 % | – | 82 / 95 % | 46 / 75 % | 38 / 70 % | 20 / 46 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 21 / 52 % | 63 / 95 % | – | 81 / 91 % | 28 / 55 % | 16 / 41 % | 10 / 26 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 22 / 43 % | 54 / 97 % | – | 77 / 94 % | 54 / 78 % | 54 / 76 % | 24 / 48 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 13 / 44 % | 71 / 85 % | – | 36 / 76 % | 38 / 65 % | 27 / 42 % | 11 / 24 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 52 % | 65 / 98 % | – | 71 / 93 % | 40 / 67 % | 35 / 58 % | 25 / 50 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 29 / 56 % | 71 / 93 % | – | 44 / 69 % | 51 / 73 % | 54 / 72 % | 36 / 53 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 19 / 43 % | 66 / 90 % | – | 68 / 88 % | 23 / 49 % | 27 / 49 % | 14 / 31 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 31 % | 57 / 90 % | – | 20 / 39 % | 11 / 34 % | 11 / 29 % | 4 / 15 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 28 / 68 % | – | 56 / 80 % | 8 / 25 % | 5 / 12 % | 3 / 10 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 32 % | 55 / 92 % | – | 37 / 71 % | 16 / 42 % | 9 / 36 % | 8 / 23 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 24 / 53 % | 48 / 98 % | – | 31 / 69 % | 34 / 65 % | 30 / 54 % | 16 / 34 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 12 / 41 % | 45 / 98 % | – | 17 / 58 % | 28 / 60 % | 22 / 54 % | 10 / 24 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 15 / 87 % | – | 10 / 44 % | 44 / 71 % | 10 / 26 % | 10 / 25 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 25 / 52 % | 44 / 98 % | – | 36 / 80 % | 29 / 62 % | 26 / 63 % | 13 / 36 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 23 / 90 % | – | 30 / 56 % | 38 / 70 % | 43 / 69 % | 19 / 42 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 30 / 78 % | – | 6 / 41 % | 11 / 32 % | 5 / 19 % | 4 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 29 % | 17 / 96 % | – | 25 / 45 % | 7 / 23 % | 7 / 16 % | 3 / 14 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 20 / 88 % | – | 0 / 0 % | 9 / 28 % | 8 / 20 % | 2 / 10 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 19 / 54 % | – | 13 / 35 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 44 % | 3 / 63 % | – | 8 / 23 % | 12 / 43 % | 18 / 42 % | 6 / 16 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 17 / 52 % | – | 2 / 24 % | 6 / 21 % | 9 / 21 % | 3 / 8 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 14 / 85 % | – | 10 / 48 % | 7 / 21 % | 7 / 18 % | 2 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 14 / 52 % | – | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 30 % | 13 / 90 % | – | 0 / 5 % | 8 / 26 % | 10 / 27 % | 4 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 34 % | 0 / 0 % | – | 0 / 0 % | 6 / 18 % | 8 / 19 % | 4 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 12 / 68 % | – | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 10 / 60 % | – | 0 / 0 % | 7 / 18 % | 6 / 15 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 9 / 77 % | – | 1 / 10 % | 6 / 21 % | 4 / 13 % | 1 / 8 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 28 % | 5 / 14 % | 4 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 9 / 24 % | 7 / 20 % | 6 / 14 % | 2 / 8 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 25 % | 5 / 16 % | 1 / 6 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 7 / 70 % | – | 0 / 0 % | 5 / 12 % | 5 / 14 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 2 / 13 % | 5 / 14 % | 5 / 12 % | 3 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 0 / 10 % | 5 / 14 % | 0 / 0 % | 2 / 8 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 5 / 16 % | 1 / 5 % |
