[English](README.md) · [Deutsch](README.de.md)

# Understanding and addressing AI harms

Bericht Q002839 · Quelle anthropic.com · Datum 2025-04-21 · [Original öffnen](https://www.anthropic.com/news/our-approach-to-understanding-and-addressing-ai-harms)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic beschreibt einen sich weiterentwickelnden Rahmen zur Bewertung von KI-Schäden in fünf Bereichen und zur Wahl abgestufter Schutzmaßnahmen. Als Beispiel berichtet das Unternehmen, Claude 3.7 Sonnet weise 45 Prozent weniger harmlose Anfragen unnötig zurück; unabhängige Belege oder Messdetails nennt der Bericht nicht. Der Ansatz sei nur ein Teil der Sicherheitsstrategie und müsse mit neuen Risiken weiterentwickelt werden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 44 / 60 % | 99 / 100 % | – | 99 / 100 % | 72 / 87 % | 68 / 83 % | 28 / 56 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 25 / 49 % | 70 / 97 % | – | 89 / 97 % | 37 / 68 % | 48 / 73 % | 18 / 48 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 16 / 40 % | 84 / 97 % | – | 87 / 97 % | 19 / 43 % | 21 / 47 % | 7 / 21 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 18 / 69 % | – | 86 / 93 % | 33 / 65 % | 48 / 73 % | 8 / 27 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 15 / 35 % | 46 / 92 % | – | 80 / 92 % | 32 / 57 % | 23 / 40 % | 7 / 26 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 24 / 42 % | 73 / 94 % | – | 64 / 86 % | 40 / 67 % | 21 / 41 % | 10 / 28 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 23 / 46 % | 66 / 92 % | – | 71 / 90 % | 37 / 63 % | 28 / 52 % | 9 / 27 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 10 / 27 % | 7 / 61 % | – | 61 / 91 % | 11 / 38 % | 6 / 19 % | 4 / 15 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 20 / 40 % | 32 / 81 % | – | 58 / 91 % | 29 / 60 % | 23 / 60 % | 9 / 29 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 13 / 39 % | 31 / 96 % | – | 50 / 87 % | 18 / 45 % | 21 / 53 % | 12 / 34 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 11 / 35 % | 45 / 72 % | – | 14 / 42 % | 27 / 53 % | 18 / 37 % | 6 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 32 % | 45 / 87 % | – | 31 / 78 % | 11 / 35 % | 8 / 37 % | 5 / 16 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 11 / 41 % | 44 / 92 % | – | 17 / 73 % | 22 / 51 % | 16 / 45 % | 7 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 24 / 80 % | – | 43 / 73 % | 7 / 22 % | 6 / 14 % | 1 / 5 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 20 % | 42 / 77 % | – | 1 / 8 % | 6 / 13 % | 4 / 10 % | 1 / 7 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 7 / 25 % | 40 / 77 % | – | 8 / 36 % | 10 / 27 % | 6 / 20 % | 2 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 12 / 26 % | 35 / 69 % | – | 9 / 42 % | 13 / 40 % | 9 / 26 % | 2 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 9 / 25 % | 34 / 69 % | – | 15 / 62 % | 10 / 25 % | 6 / 15 % | 3 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 11 / 26 % | 32 / 80 % | – | 7 / 26 % | 10 / 31 % | 6 / 16 % | 2 / 9 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 37 % | 11 / 51 % | – | 4 / 27 % | 22 / 46 % | 27 / 49 % | 6 / 21 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 26 / 73 % | – | 27 / 45 % | 15 / 39 % | 6 / 18 % | 4 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 25 / 89 % | – | 5 / 33 % | 9 / 32 % | 8 / 22 % | 0 / 3 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 5 / 50 % | – | 13 / 52 % | 15 / 39 % | 5 / 13 % | 2 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 15 / 35 % | 0 / 0 % | 0 / 3 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 11 / 34 % | 1 / 26 % | – | 11 / 29 % | 9 / 27 % | 11 / 29 % | 1 / 6 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 7 / 29 % | 1 / 23 % | – | 11 / 39 % | 7 / 17 % | 6 / 15 % | 1 / 8 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 24 % | 11 / 86 % | – | 3 / 23 % | 5 / 21 % | 5 / 14 % | 3 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 10 / 28 % | 7 / 60 % | – | 3 / 17 % | 9 / 27 % | 10 / 27 % | 1 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 10 / 42 % | 0 / 0 % | – | 0 / 0 % | 10 / 30 % | 5 / 16 % | 1 / 8 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 32 % | 3 / 37 % | – | 2 / 16 % | 9 / 26 % | 7 / 17 % | 0 / 5 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 5 / 27 % | 6 / 89 % | – | 3 / 34 % | 9 / 27 % | 6 / 19 % | 2 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 4 / 10 % | 0 / 3 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 7 / 22 % | 1 / 6 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 3 / 41 % | – | 0 / 8 % | 7 / 19 % | 4 / 12 % | 1 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 3 / 21 % | – | 3 / 11 % | 6 / 17 % | 5 / 12 % | 1 / 4 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 3 / 67 % | – | 1 / 23 % | 6 / 17 % | 0 / 0 % | 0 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 2 / 9 % | 0 / 2 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 2 % | 6 / 13 % | 4 / 9 % | 1 / 5 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 2 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 5 / 8 % | 1 / 3 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 2 / 67 % | – | 0 / 4 % | 5 / 13 % | 4 / 9 % | 1 / 3 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 9 % | 4 / 12 % | 0 / 2 % |
