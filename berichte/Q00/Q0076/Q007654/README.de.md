[English](README.md) · [Deutsch](README.de.md)

# Our approach to AI safety

Bericht Q007654 · Quelle openai.com · Datum 2023-04-05 · [Original öffnen](https://openai.com/index/our-approach-to-ai-safety/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt Tests vor der Veröffentlichung, schrittweise Einführung sowie Maßnahmen zu Kinderschutz, Datenschutz und Genauigkeit als zentrale Teile seines Sicherheitsansatzes. Das Unternehmen räumt ein, dass Missbrauch und falsche Antworten nicht vollständig vorhersehbar oder ausgeschlossen sind; die genannten Verbesserungswerte sind Behauptungen des Berichts und werden darin nicht unabhängig geprüft.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 45 / 65 % | 96 / 99 % | 100 / 100 % | 77 / 88 % | 51 / 79 % | 65 / 83 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 17 / 40 % | 39 / 89 % | 97 / 99 % | 37 / 65 % | 6 / 22 % | 23 / 53 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 21 / 46 % | 38 / 81 % | 96 / 98 % | 39 / 69 % | 11 / 46 % | 32 / 67 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 30 / 56 % | 91 / 96 % | 94 / 97 % | 53 / 75 % | 43 / 66 % | 58 / 80 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 21 / 40 % | 55 / 93 % | 92 / 99 % | 43 / 69 % | 17 / 43 % | 35 / 59 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 24 / 51 % | 92 / 99 % | 92 / 98 % | 39 / 68 % | 20 / 57 % | 44 / 74 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 24 / 46 % | 26 / 92 % | 92 / 98 % | 31 / 63 % | 8 / 38 % | 16 / 61 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 23 / 45 % | 91 / 98 % | 89 / 96 % | 28 / 60 % | 9 / 33 % | 30 / 56 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 16 / 44 % | 68 / 96 % | 85 / 96 % | 22 / 48 % | 9 / 31 % | 26 / 57 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 19 / 48 % | 31 / 82 % | 84 / 93 % | 49 / 75 % | 30 / 58 % | 37 / 70 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 50 / 79 % | 83 / 93 % | 7 / 22 % | 1 / 8 % | 7 / 14 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 25 % | 67 / 93 % | 6 / 36 % | 9 / 27 % | 6 / 25 % | 8 / 26 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 30 % | 66 / 94 % | 47 / 75 % | 9 / 27 % | 1 / 11 % | 7 / 17 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 10 / 35 % | 64 / 97 % | 34 / 56 % | 10 / 33 % | 3 / 24 % | 8 / 26 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 39 % | 58 / 99 % | 44 / 86 % | 17 / 47 % | 7 / 27 % | 13 / 42 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 15 / 83 % | 58 / 83 % | 13 / 39 % | 3 / 13 % | 6 / 17 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 11 / 39 % | 21 / 83 % | 43 / 84 % | 57 / 79 % | 12 / 43 % | 13 / 45 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 15 / 38 % | 57 / 85 % | 31 / 69 % | 22 / 48 % | 8 / 35 % | 18 / 45 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 19 / 51 % | 55 / 92 % | 56 / 79 % | 30 / 57 % | 24 / 52 % | 25 / 56 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 29 % | 43 / 78 % | 47 / 78 % | 15 / 38 % | 2 / 11 % | 10 / 25 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 14 / 38 % | 45 / 84 % | 20 / 59 % | 12 / 34 % | 4 / 16 % | 11 / 29 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 11 / 45 % | 42 / 79 % | 10 / 42 % | 13 / 39 % | 6 / 23 % | 7 / 26 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 41 / 78 % | 2 / 17 % | 6 / 19 % | 2 / 10 % | 6 / 14 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 33 / 74 % | 35 / 66 % | 15 / 44 % | 1 / 10 % | 11 / 35 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 13 / 32 % | 30 / 91 % | 15 / 43 % | 12 / 35 % | 6 / 19 % | 18 / 38 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 29 / 89 % | 6 / 29 % | 8 / 22 % | 1 / 8 % | 9 / 27 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 38 % | 28 / 88 % | 20 / 62 % | 16 / 41 % | 7 / 25 % | 14 / 40 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 21 / 90 % | 1 / 16 % | 6 / 15 % | 1 / 7 % | 5 / 10 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 18 / 59 % | 3 / 22 % | 6 / 16 % | 0 / 0 % | 7 / 20 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 15 / 73 % | 3 / 13 % | 8 / 20 % | 1 / 8 % | 8 / 16 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 8 / 32 % | 14 / 63 % | 2 / 27 % | 6 / 16 % | 2 / 12 % | 9 / 22 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 9 / 23 % | 5 / 72 % | 0 / 5 % | 7 / 22 % | 1 / 8 % | 10 / 23 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 10 / 35 % | 0 / 0 % | 5 / 14 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 10 / 94 % | 2 / 29 % | 6 / 15 % | 1 / 7 % | 5 / 17 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 9 / 41 % | 0 / 0 % | 8 / 23 % | 1 / 9 % | 6 / 20 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 7 / 57 % | 1 / 12 % | 7 / 19 % | 1 / 8 % | 5 / 15 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 7 / 27 % | 7 / 42 % | 1 / 10 % | 7 / 17 % | 1 / 7 % | 6 / 13 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 4 / 25 % | 5 / 75 % | 2 / 19 % | 6 / 18 % | 1 / 11 % | 5 / 16 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 6 / 13 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 6 / 34 % | 0 / 0 % | 4 / 9 % | 0 / 4 % | 5 / 13 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 5 / 11 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 2 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 4 % | 4 / 12 % | – | – |
