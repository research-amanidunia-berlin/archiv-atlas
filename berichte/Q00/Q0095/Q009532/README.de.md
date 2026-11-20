[English](README.md) · [Deutsch](README.de.md)

# Demokratische Governance von Frontier-KI, Teil II: Cyberabwehrteams stärken

Bericht Q009532 · Quelle openai.com · Datum – · [Original öffnen](https://openai.com/index/empowering-cyber-defenders/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI stellt ein Konzept vor, das Cyberabwehrteams angesichts der Chancen und Risiken fortschrittlicher KI stärken soll. Es empfiehlt klarere Sicherheitszuständigkeiten für KI, modernisierte Abwehrfähigkeiten und widerstandsfähigere öffentliche Institutionen; der kurze Bericht erläutert die Vorschläge, belegt ihre Wirksamkeit aber nicht und verweist für Einzelheiten auf ein separates PDF.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 50 % | 79 / 95 % | – | 95 / 97 % | 56 / 78 % | 43 / 71 % | 41 / 71 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 37 / 62 % | 27 / 81 % | – | 95 / 98 % | 47 / 73 % | 29 / 70 % | 16 / 44 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 27 / 47 % | 45 / 86 % | – | 84 / 92 % | 38 / 69 % | 56 / 82 % | 49 / 72 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 21 / 45 % | 76 / 89 % | – | 69 / 77 % | 53 / 74 % | 50 / 67 % | 48 / 66 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 44 / 68 % | 51 / 98 % | – | 75 / 96 % | 47 / 72 % | 64 / 83 % | 47 / 70 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 15 / 44 % | 70 / 96 % | – | 19 / 59 % | 30 / 60 % | 33 / 68 % | 23 / 52 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 19 / 44 % | 67 / 89 % | – | 54 / 70 % | 23 / 48 % | 29 / 63 % | 14 / 37 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 29 / 49 % | 60 / 94 % | – | 66 / 84 % | 50 / 73 % | 56 / 76 % | 51 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 18 / 43 % | 46 / 87 % | – | 60 / 80 % | 33 / 59 % | 23 / 50 % | 12 / 33 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 31 % | 57 / 88 % | – | 45 / 71 % | 11 / 30 % | 11 / 47 % | 5 / 21 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 29 / 50 % | 52 / 92 % | – | 12 / 53 % | 38 / 66 % | 40 / 64 % | 46 / 67 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 21 / 54 % | 49 / 83 % | – | 29 / 70 % | 24 / 55 % | 21 / 60 % | 14 / 46 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 14 / 38 % | 47 / 87 % | – | 17 / 52 % | 11 / 30 % | 9 / 32 % | 5 / 23 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 22 / 47 % | 39 / 95 % | – | 29 / 64 % | 28 / 62 % | 41 / 73 % | 26 / 58 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 40 / 90 % | – | 23 / 59 % | 9 / 21 % | 7 / 15 % | 3 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 14 / 35 % | 38 / 70 % | – | 19 / 61 % | 27 / 56 % | 35 / 66 % | 20 / 49 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 10 / 30 % | 3 / 23 % | – | 38 / 49 % | 14 / 42 % | 7 / 19 % | 2 / 7 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 13 / 42 % | 20 / 83 % | – | 18 / 71 % | 15 / 40 % | 33 / 71 % | 22 / 53 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 28 / 68 % | – | 31 / 54 % | 17 / 44 % | 14 / 48 % | 13 / 40 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 15 / 33 % | 27 / 78 % | – | 4 / 22 % | 18 / 47 % | 18 / 44 % | 12 / 34 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 14 / 80 % | – | 24 / 60 % | 17 / 46 % | 7 / 21 % | 1 / 9 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 27 % | 24 / 89 % | – | 12 / 32 % | 8 / 28 % | 7 / 25 % | 5 / 22 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 36 % | 21 / 94 % | – | 23 / 51 % | 20 / 49 % | 12 / 47 % | 8 / 28 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 12 / 32 % | 21 / 78 % | – | 2 / 48 % | 10 / 35 % | 9 / 41 % | 4 / 18 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 32 % | 17 / 68 % | – | 8 / 31 % | 8 / 22 % | 5 / 17 % | 1 / 8 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 12 / 28 % | 6 / 83 % | – | 8 / 41 % | 17 / 46 % | 10 / 31 % | 7 / 25 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 16 / 71 % | – | 0 / 0 % | 10 / 35 % | 6 / 24 % | 2 / 11 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 15 / 75 % | – | 1 / 9 % | 7 / 18 % | 8 / 17 % | 1 / 6 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 15 / 61 % | – | 0 / 0 % | 5 / 12 % | 5 / 8 % | 1 / 4 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 5 / 28 % | – | 14 / 34 % | 5 / 11 % | 0 / 0 % | 0 / 3 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 12 / 80 % | – | 0 / 8 % | 7 / 17 % | 7 / 15 % | 4 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 29 % | 0 / 0 % | 1 / 4 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 34 % | 1 / 22 % | – | 0 / 0 % | 5 / 13 % | 7 / 18 % | 1 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 30 % | 3 / 82 % | – | 11 / 44 % | 9 / 31 % | 9 / 32 % | 4 / 20 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 9 / 38 % | 2 / 43 % | – | 2 / 13 % | 9 / 22 % | 9 / 31 % | 2 / 13 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 2 / 23 % | 0 / 0 % | 9 / 22 % | 4 / 10 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 2 / 35 % | – | 0 / 0 % | 7 / 20 % | 7 / 31 % | 2 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 7 / 19 % | 2 / 8 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 2 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 5 / 10 % | 1 / 4 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % | 1 / 4 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % |
