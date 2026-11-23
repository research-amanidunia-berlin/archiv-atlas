[English](README.md) · [Deutsch](README.de.md)

# Building safeguards for Claude

Bericht Q002194 · Quelle anthropic.com · Datum 2025-08-12 · [Original öffnen](https://www.anthropic.com/news/building-safeguards-for-claude)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic beschreibt ein Schutzkonzept für Claude aus Richtlinienarbeit, Training, Vorabtests, Echtzeit-Erkennung und fortlaufender Analyse möglicher Missbrauchsmuster. Der Bericht nennt Beispiele für daraus abgeleitete Maßnahmen, enthält aber keine Erfolgsquoten oder unabhängige Gesamtbewertung ihrer Wirksamkeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 55 / 71 % | 94 / 99 % | 100 / 100 % | 85 / 91 % | 74 / 88 % | 84 / 91 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 37 / 59 % | 92 / 97 % | 99 / 100 % | 68 / 86 % | 74 / 87 % | 78 / 88 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 24 / 47 % | 88 / 95 % | 97 / 99 % | 46 / 68 % | 27 / 47 % | 59 / 74 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 49 / 67 % | 53 / 84 % | 95 / 99 % | 73 / 87 % | 28 / 53 % | 47 / 64 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 39 / 63 % | 85 / 95 % | 94 / 99 % | 44 / 66 % | 53 / 74 % | 61 / 77 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 29 / 51 % | 93 / 100 % | 94 / 99 % | 67 / 85 % | 61 / 81 % | 64 / 82 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 16 / 39 % | 80 / 98 % | 92 / 97 % | 52 / 72 % | 10 / 33 % | 44 / 61 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 24 / 49 % | 72 / 98 % | 91 / 96 % | 71 / 86 % | 59 / 82 % | 77 / 89 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 25 / 47 % | 90 / 95 % | 84 / 92 % | 66 / 83 % | 30 / 48 % | 59 / 70 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 31 / 53 % | 81 / 93 % | 83 / 90 % | 67 / 82 % | 28 / 52 % | 52 / 67 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 25 / 47 % | 45 / 84 % | 80 / 87 % | 40 / 64 % | 15 / 30 % | 16 / 31 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 26 / 48 % | 66 / 93 % | 59 / 77 % | 65 / 81 % | 40 / 59 % | 78 / 86 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 16 / 40 % | 69 / 98 % | 46 / 89 % | 40 / 68 % | 19 / 52 % | 30 / 59 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 19 / 36 % | 45 / 86 % | 69 / 90 % | 28 / 52 % | 14 / 30 % | 33 / 54 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 28 / 59 % | 69 / 85 % | 9 / 28 % | 3 / 10 % | 9 / 18 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 22 / 37 % | 54 / 86 % | 59 / 77 % | 29 / 55 % | 13 / 27 % | 28 / 49 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 59 / 87 % | 6 / 22 % | 13 / 33 % | 5 / 17 % | 10 / 22 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 11 / 25 % | 0 / 0 % | 57 / 85 % | 12 / 33 % | 6 / 20 % | 11 / 26 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 41 / 87 % | 50 / 77 % | 22 / 52 % | 8 / 21 % | 20 / 47 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 26 % | 47 / 81 % | 12 / 30 % | 9 / 25 % | 5 / 19 % | 10 / 22 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 39 / 97 % | 44 / 68 % | 18 / 47 % | 10 / 24 % | 22 / 49 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 44 / 88 % | 41 / 77 % | 19 / 45 % | 4 / 15 % | 23 / 42 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 43 / 65 % | 0 / 0 % | 9 / 15 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 16 / 75 % | 40 / 71 % | 34 / 60 % | 11 / 27 % | 11 / 25 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 44 % | 0 / 0 % | 0 / 0 % | 38 / 63 % | 15 / 37 % | 23 / 47 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 10 / 75 % | 30 / 60 % | 12 / 37 % | 7 / 19 % | 11 / 21 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 29 / 79 % | 0 / 7 % | 6 / 15 % | 1 / 6 % | 6 / 12 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 10 / 26 % | 11 / 83 % | 4 / 26 % | 26 / 51 % | 8 / 22 % | 11 / 33 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 15 / 37 % | 0 / 0 % | 0 / 0 % | 13 / 34 % | 10 / 26 % | 25 / 56 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 16 / 56 % | 17 / 42 % | 10 / 27 % | 8 / 20 % | 15 / 38 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 24 % | 17 / 90 % | 10 / 29 % | 12 / 31 % | 7 / 19 % | 10 / 23 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 5 / 19 % | 12 / 28 % | 3 / 10 % | 17 / 32 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 25 % | 6 / 67 % | 16 / 35 % | 7 / 20 % | 4 / 15 % | 8 / 18 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 9 / 21 % | 0 / 7 % | 0 / 0 % | 8 / 22 % | 6 / 17 % | 12 / 26 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 8 / 63 % | 11 / 39 % | 11 / 28 % | 7 / 20 % | 11 / 23 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 10 / 22 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 1 / 15 % | 8 / 20 % | 4 / 15 % | 9 / 22 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 2 / 9 % | 6 / 15 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 5 / 13 % | 7 / 12 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 1 / 10 % | 0 / 0 % | 7 / 15 % | 7 / 16 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 2 % | 6 / 11 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 6 / 14 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 5 / 12 % | 5 / 11 % | – | – |
