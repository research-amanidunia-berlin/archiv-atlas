[English](README.md) · [Deutsch](README.de.md)

# Petri: An open-source AI auditing tool

Bericht Q003817 · Quelle anthropic.com · Datum 2025-10-06 · [Original öffnen](https://www.anthropic.com/research/petri-open-source-auditing)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic stellt Petri vor, ein quelloffenes System, das KI-Modelle in simulierten Gesprächen prüft und deren Verhalten automatisiert bewerten lässt. Ein begrenzter Pilot ergab laut Anthropic unter anderem niedrige Risikowerte für Claude Sonnet 4.5; die Ergebnisse seien wegen der kleinen Szenariozahl, vereinfachender Kennzahlen und der Grenzen KI-gestützter Prüfungen vorläufig. Eine Fallstudie zu eigenständigem Melden von Missständen zeigte zudem, dass Autonomie und Kontext das Verhalten beeinflussen können und auch harmlose Vorgänge gemeldet wurden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 47 / 65 % | 75 / 93 % | 97 / 99 % | 81 / 90 % | 65 / 83 % | 87 / 92 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 55 / 72 % | 96 / 100 % | 97 / 98 % | 79 / 89 % | 57 / 78 % | 82 / 90 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 42 / 61 % | 92 / 98 % | 96 / 99 % | 61 / 82 % | 54 / 77 % | 73 / 86 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 41 / 65 % | 66 / 89 % | 95 / 98 % | 9 / 22 % | 30 / 59 % | 49 / 70 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 39 / 61 % | 78 / 97 % | 93 / 97 % | 54 / 78 % | 19 / 49 % | 63 / 83 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 34 / 58 % | 86 / 97 % | 90 / 96 % | 59 / 78 % | 9 / 27 % | 38 / 59 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 11 / 55 % | 69 / 85 % | 43 / 69 % | 9 / 24 % | 12 / 26 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 20 / 45 % | 31 / 73 % | 67 / 85 % | 18 / 37 % | 4 / 10 % | 18 / 28 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 63 / 95 % | 20 / 62 % | 30 / 62 % | 7 / 21 % | 17 / 37 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 17 / 36 % | 55 / 81 % | 59 / 61 % | 30 / 51 % | 9 / 21 % | 15 / 27 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 20 / 70 % | 59 / 72 % | 9 / 25 % | 3 / 11 % | 7 / 14 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 50 / 94 % | 55 / 77 % | 23 / 50 % | 8 / 21 % | 21 / 46 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 6 / 53 % | 47 / 65 % | 14 / 38 % | 4 / 11 % | 10 / 17 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 38 / 86 % | 11 / 42 % | 10 / 26 % | 1 / 8 % | 6 / 14 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 19 / 43 % | 21 / 68 % | 14 / 45 % | 35 / 61 % | 8 / 23 % | 27 / 45 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 22 / 58 % | 35 / 58 % | 11 / 31 % | 4 / 13 % | 6 / 12 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 37 % | 33 / 76 % | 6 / 14 % | 18 / 41 % | 6 / 20 % | 20 / 37 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 20 / 50 % | 27 / 61 % | 25 / 45 % | 31 / 59 % | 14 / 31 % | 18 / 36 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 6 / 44 % | 28 / 47 % | 10 / 27 % | 4 / 10 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 7 / 52 % | 28 / 51 % | 9 / 28 % | 2 / 7 % | 7 / 15 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 48 % | 24 / 61 % | 17 / 38 % | 11 / 32 % | 5 / 16 % | 15 / 29 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 18 / 89 % | 24 / 52 % | 16 / 45 % | 11 / 28 % | 16 / 33 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 43 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 17 / 49 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 1 / 8 % | 12 / 24 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 9 / 55 % | 6 / 17 % | 17 / 41 % | 4 / 14 % | 9 / 19 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 17 / 50 % | 8 / 22 % | 3 / 11 % | 6 / 13 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 14 / 43 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 9 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 8 / 45 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 1 / 4 % | 6 / 16 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 6 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 4 / 6 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
