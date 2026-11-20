[English](README.md) · [Deutsch](README.de.md)

# Taking a responsible path to AGI

Bericht Q003066 · Quelle deepmind.google · Datum 2025-04-02 · [Original öffnen](https://deepmind.google/blog/taking-a-responsible-path-to-agi/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google DeepMind skizziert Maßnahmen für mögliche AGI-Risiken, insbesondere Missbrauch und Fehlanpassung: Dazu zählen Zugangsschutz, Modellprüfungen, menschliche Aufsicht, Überwachung und Forschung an verständlicheren Systemen. Der Beitrag beschreibt Unternehmenspositionen und geplante Arbeit, räumt offene Herausforderungen ein und belegt nicht, dass die Maßnahmen sämtliche Risiken lösen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 43 / 63 % | 95 / 99 % | 63 / 87 % | 96 / 99 % | 68 / 85 % | 49 / 76 % | 75 / 89 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 30 / 57 % | 86 / 99 % | 40 / 68 % | 94 / 99 % | 46 / 75 % | 36 / 66 % | 67 / 83 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 34 / 57 % | 89 / 99 % | 59 / 81 % | 90 / 99 % | 49 / 76 % | 35 / 66 % | 50 / 76 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 17 / 45 % | 79 / 96 % | 25 / 55 % | 86 / 97 % | 40 / 67 % | 20 / 53 % | 39 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 38 / 60 % | 49 / 93 % | 41 / 74 % | 62 / 90 % | 64 / 84 % | 51 / 75 % | 84 / 92 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 38 / 64 % | 56 / 87 % | 63 / 77 % | 82 / 97 % | 18 / 42 % | 56 / 73 % | 75 / 87 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 26 / 55 % | 81 / 96 % | 32 / 57 % | 69 / 86 % | 38 / 65 % | 20 / 44 % | 25 / 54 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 44 / 78 % | 1 / 9 % | 72 / 90 % | 13 / 39 % | 4 / 24 % | 12 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 31 % | 68 / 92 % | 6 / 22 % | 69 / 89 % | 14 / 39 % | 9 / 31 % | 15 / 46 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 16 / 47 % | 65 / 95 % | 15 / 41 % | 50 / 89 % | 35 / 64 % | 15 / 43 % | 28 / 64 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 18 / 48 % | 65 / 92 % | 8 / 33 % | 56 / 83 % | 19 / 46 % | 12 / 38 % | 24 / 58 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 11 / 42 % | 62 / 83 % | 16 / 25 % | 17 / 42 % | 32 / 59 % | 12 / 33 % | 26 / 51 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 12 / 41 % | 60 / 89 % | 1 / 8 % | 37 / 81 % | 11 / 31 % | 6 / 20 % | 9 / 23 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 34 % | 56 / 78 % | 8 / 23 % | 7 / 37 % | 12 / 30 % | 7 / 27 % | 13 / 32 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 47 % | 55 / 97 % | 2 / 15 % | 35 / 72 % | 19 / 48 % | 8 / 38 % | 22 / 55 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 44 % | 21 / 87 % | 12 / 35 % | 51 / 82 % | 41 / 69 % | 19 / 42 % | 22 / 64 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 22 / 42 % | 41 / 83 % | 30 / 56 % | 50 / 87 % | 45 / 69 % | 17 / 46 % | 49 / 68 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 12 / 30 % | 30 / 69 % | 0 / 4 % | 50 / 77 % | 10 / 34 % | 2 / 10 % | 6 / 19 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 46 % | 46 / 90 % | 10 / 31 % | 13 / 55 % | 24 / 51 % | 15 / 46 % | 29 / 59 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 13 / 38 % | 19 / 91 % | 1 / 9 % | 38 / 59 % | 12 / 37 % | 8 / 32 % | 11 / 46 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 10 / 33 % | 37 / 84 % | 9 / 34 % | 27 / 76 % | 24 / 52 % | 11 / 32 % | 10 / 42 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 37 / 81 % | 1 / 6 % | 2 / 22 % | 8 / 21 % | 2 / 11 % | 10 / 36 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 7 / 71 % | 5 / 19 % | 35 / 78 % | 30 / 58 % | 9 / 30 % | 10 / 27 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 25 / 45 % | 5 / 76 % | 17 / 37 % | 24 / 52 % | 19 / 48 % | 10 / 26 % | 22 / 42 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 33 % | 25 / 91 % | 2 / 16 % | 15 / 52 % | 9 / 30 % | 6 / 33 % | 9 / 33 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 23 / 75 % | 0 / 3 % | 0 / 3 % | 7 / 17 % | 1 / 6 % | 7 / 14 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 21 / 73 % | 0 / 3 % | 6 / 35 % | 9 / 26 % | 3 / 10 % | 7 / 19 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 14 / 40 % | 1 / 35 % | 1 / 6 % | 17 / 54 % | 11 / 30 % | 6 / 21 % | 19 / 43 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 48 % | 9 / 84 % | 7 / 24 % | 14 / 55 % | 19 / 47 % | 10 / 38 % | 13 / 39 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 40 % | 1 / 29 % | 2 / 12 % | 17 / 44 % | 11 / 35 % | 5 / 27 % | 11 / 53 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 15 / 75 % | 1 / 5 % | 4 / 43 % | 9 / 31 % | 1 / 6 % | 8 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 36 % | 0 / 0 % | 8 / 13 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 5 / 30 % | 1 / 5 % | 11 / 31 % | 12 / 40 % | 5 / 22 % | 11 / 23 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 30 % | 1 / 23 % | 0 / 3 % | 0 / 0 % | 7 / 20 % | 5 / 17 % | 8 / 21 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 10 / 62 % | 0 / 5 % | 6 / 37 % | 9 / 29 % | 1 / 5 % | 7 / 26 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 10 / 57 % | 0 / 0 % | 0 / 9 % | 5 / 14 % | 1 / 6 % | 5 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 9 / 29 % | 2 / 12 % | 6 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 8 % | 8 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 7 / 12 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 7 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 1 / 81 % | 0 / 4 % | 1 / 31 % | 7 / 22 % | 2 / 9 % | 6 / 25 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 18 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 7 % | 7 / 19 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 1 / 31 % | 0 / 0 % | 0 / 14 % | 0 / 0 % | 5 / 14 % | 6 / 16 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 5 % | 6 / 14 % | 3 / 10 % | 6 / 16 % |
