[English](README.md) · [Deutsch](README.de.md)

# Introducing the Frontier Safety Framework

Bericht Q002877 · Quelle deepmind.google · Datum 2024-05-17 · [Original öffnen](https://deepmind.google/blog/introducing-the-frontier-safety-framework/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Googles Frontier Safety Framework soll kritische KI-Fähigkeiten anhand festgelegter Schwellen und regelmäßiger Frühwarnprüfungen erkennen und bei Bedarf Schutzmaßnahmen auslösen. Die erste Fassung betrachtet vier Risikobereiche und bleibt laut Bericht vorläufig; die Forschung sei noch jung, und stärkere Schutzmaßnahmen könnten Innovation und Zugang einschränken.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 41 / 66 % | 98 / 100 % | 86 / 98 % | 73 / 86 % | 62 / 81 % | 80 / 88 % | 77 / 93 % | 61 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 57 % | 81 / 95 % | 93 / 99 % | 49 / 77 % | 41 / 69 % | 66 / 83 % | 47 / 80 % | 17 / 37 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 58 % | 93 / 99 % | 72 / 91 % | 57 / 78 % | 39 / 66 % | 67 / 82 % | 50 / 80 % | 39 / 64 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 49 / 69 % | 87 / 98 % | 92 / 99 % | 77 / 89 % | 47 / 72 % | 78 / 87 % | 72 / 88 % | 32 / 59 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 37 / 65 % | 63 / 90 % | 91 / 99 % | 28 / 53 % | 47 / 74 % | 69 / 83 % | 71 / 92 % | 39 / 69 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 41 % | 22 / 54 % | 88 / 96 % | 23 / 51 % | 7 / 29 % | 11 / 35 % | 7 / 33 % | 20 / 47 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 15 / 42 % | 60 / 90 % | 87 / 96 % | 23 / 49 % | 10 / 26 % | 22 / 43 % | 6 / 22 % | 13 / 33 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 25 / 51 % | 85 / 96 % | 84 / 94 % | 55 / 77 % | 32 / 63 % | 67 / 79 % | 22 / 39 % | 26 / 54 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 23 / 50 % | 76 / 92 % | 73 / 92 % | 57 / 78 % | 16 / 44 % | 51 / 68 % | 45 / 70 % | 30 / 56 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 18 / 48 % | 67 / 97 % | 57 / 85 % | 34 / 60 % | 18 / 43 % | 44 / 66 % | 20 / 48 % | 17 / 46 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 10 / 25 % | 62 / 94 % | 56 / 85 % | 12 / 32 % | 5 / 23 % | 9 / 28 % | 1 / 13 % | 19 / 44 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 41 / 78 % | 62 / 83 % | 7 / 21 % | 1 / 6 % | 9 / 15 % | 0 / 0 % | 17 / 36 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 43 % | 43 / 88 % | 61 / 83 % | 23 / 51 % | 13 / 31 % | 18 / 46 % | 6 / 27 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 21 / 49 % | 52 / 90 % | 61 / 91 % | 44 / 68 % | 12 / 34 % | 32 / 57 % | 12 / 40 % | 26 / 55 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 12 / 37 % | 58 / 87 % | 49 / 68 % | 24 / 50 % | 7 / 28 % | 11 / 27 % | 5 / 19 % | 11 / 34 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 14 / 44 % | 55 / 91 % | 42 / 80 % | 23 / 50 % | 7 / 29 % | 11 / 22 % | 5 / 22 % | 18 / 43 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 32 % | 50 / 95 % | 43 / 63 % | 9 / 31 % | 4 / 18 % | 7 / 19 % | 1 / 6 % | 15 / 39 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 35 / 82 % | 47 / 84 % | 47 / 71 % | 15 / 41 % | 9 / 23 % | 14 / 43 % | 16 / 44 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 9 / 31 % | 45 / 92 % | 7 / 27 % | 9 / 25 % | 3 / 18 % | 9 / 22 % | 2 / 14 % | 25 / 51 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 26 % | 41 / 91 % | 23 / 72 % | 14 / 34 % | 5 / 19 % | 8 / 23 % | 2 / 13 % | 16 / 45 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 18 / 48 % | 6 / 55 % | 9 / 35 % | 25 / 56 % | 13 / 39 % | 29 / 66 % | 2 / 12 % | 5 / 18 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 9 / 35 % | 21 / 85 % | 18 / 48 % | 8 / 25 % | 4 / 18 % | 7 / 20 % | 2 / 10 % | 21 / 50 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 14 / 73 % | 21 / 51 % | 10 / 27 % | 1 / 5 % | 6 / 15 % | 0 / 4 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 42 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 19 / 44 % | 18 / 83 % | 13 / 56 % | 15 / 47 % | 4 / 21 % | 12 / 49 % | 1 / 10 % | 10 / 32 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 19 / 58 % | 0 / 0 % | 8 / 19 % | 0 / 2 % | 6 / 14 % | 0 / 0 % | 8 / 28 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 50 % | 7 / 56 % | 12 / 49 % | 18 / 44 % | 5 / 19 % | 8 / 21 % | 5 / 21 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 15 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 17 / 42 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 37 % | 4 / 64 % | 9 / 33 % | 15 / 42 % | 6 / 18 % | 13 / 31 % | 6 / 23 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 14 / 63 % | 1 / 14 % | 7 / 18 % | 1 / 7 % | 8 / 16 % | 0 / 2 % | 3 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 34 % | 5 / 35 % | 0 / 0 % | 8 / 21 % | 3 / 11 % | 8 / 21 % | 1 / 5 % | 5 / 20 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 11 / 41 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 10 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 8 / 31 % | 10 / 26 % | 0 / 3 % | 8 / 17 % | 0 / 4 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 7 / 44 % | 8 / 27 % | 8 / 24 % | 1 / 7 % | 9 / 17 % | 0 / 3 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 7 % | 6 / 19 % | 0 / 3 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 2 / 31 % | 3 / 27 % | 7 / 18 % | 1 / 8 % | 8 / 18 % | 0 / 3 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 2 / 6 % | 5 / 9 % | 0 / 0 % | 7 / 22 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 7 / 44 % | 2 / 14 % | 6 / 15 % | 1 / 5 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 41 % | 1 / 21 % | 7 / 18 % | 1 / 5 % | 5 / 12 % | 0 / 2 % | 5 / 21 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 2 / 41 % | 0 / 4 % | 6 / 15 % | 2 / 7 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 11 % | 0 / 0 % | 4 / 10 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
