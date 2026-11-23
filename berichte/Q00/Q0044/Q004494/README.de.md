[English](README.md) · [Deutsch](README.de.md)

# Dario Amodei — We Must Pace the Frontier

Bericht Q004494 · Quelle darioamodei.com · Datum 2026-09-12 · [Original öffnen](https://darioamodei.com/post/we-must-pace-the-frontier)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Amodei fordert, das Tempo der KI-Entwicklung so zu steuern, dass Sicherheitsprüfungen, Ausrichtung und öffentliche Beratung mithalten können. Er schlägt unabhängige Prüfer, gemeinsame Standards und internationale Absprachen vor; Anthropic sagt im Essay den ersten Schritt zu. Die erwarteten Sicherheitswirkungen sind nicht belegt, und der Autor betont erhebliche Hürden bei Kontrolle und internationaler Zusammenarbeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 43 / 65 % | 98 / 99 % | 100 / 100 % | 86 / 93 % | 96 / 98 % | 93 / 95 % | 96 / 99 % | 19 / 37 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 80 / 88 % | 100 / 100 % | 100 / 100 % | 90 / 94 % | 97 / 98 % | 95 / 96 % | 100 / 100 % | 78 / 89 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 50 / 67 % | 96 / 97 % | 100 / 100 % | 82 / 90 % | 94 / 97 % | 91 / 95 % | 96 / 99 % | 63 / 78 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 67 / 81 % | 95 / 96 % | 100 / 100 % | 80 / 89 % | 88 / 95 % | 93 / 95 % | 93 / 98 % | 69 / 83 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 60 / 78 % | 90 / 96 % | 100 / 100 % | 86 / 93 % | 74 / 89 % | 87 / 94 % | 84 / 96 % | 62 / 80 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 34 / 63 % | 98 / 99 % | 99 / 100 % | 80 / 90 % | 86 / 94 % | 93 / 96 % | 92 / 98 % | 69 / 85 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 47 / 64 % | 88 / 93 % | 99 / 100 % | 83 / 91 % | 84 / 93 % | 94 / 96 % | 88 / 96 % | 74 / 88 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 39 / 62 % | 96 / 98 % | 99 / 100 % | 77 / 89 % | 70 / 88 % | 81 / 90 % | 70 / 91 % | 59 / 76 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 59 / 74 % | 87 / 92 % | 98 / 99 % | 85 / 92 % | 39 / 62 % | 71 / 85 % | 70 / 83 % | 61 / 78 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 46 / 65 % | 96 / 97 % | 98 / 99 % | 78 / 88 % | 79 / 90 % | 89 / 94 % | 87 / 94 % | 66 / 81 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 55 / 74 % | 97 / 99 % | 93 / 97 % | 87 / 93 % | 76 / 86 % | 89 / 93 % | 95 / 98 % | 61 / 78 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 13 / 30 % | 95 / 99 % | 39 / 59 % | 17 / 40 % | 12 / 35 % | 28 / 52 % | 3 / 15 % | 35 / 63 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 18 / 42 % | 93 / 96 % | 88 / 94 % | 50 / 77 % | 61 / 82 % | 73 / 86 % | 27 / 40 % | 59 / 80 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 41 / 65 % | 91 / 97 % | 87 / 92 % | 38 / 65 % | 45 / 73 % | 51 / 73 % | 19 / 53 % | 28 / 54 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 16 / 34 % | 88 / 96 % | 55 / 70 % | 54 / 75 % | 31 / 48 % | 55 / 68 % | 43 / 57 % | 26 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 32 / 57 % | 67 / 97 % | 87 / 96 % | 70 / 85 % | 26 / 55 % | 43 / 72 % | 25 / 55 % | 21 / 45 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 32 / 62 % | 62 / 92 % | 75 / 89 % | 80 / 90 % | 80 / 91 % | 86 / 93 % | 64 / 84 % | 24 / 45 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 28 / 50 % | 65 / 83 % | 86 / 92 % | 39 / 66 % | 22 / 50 % | 40 / 60 % | 11 / 30 % | 16 / 36 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 21 / 51 % | 68 / 83 % | 84 / 98 % | 48 / 74 % | 46 / 75 % | 74 / 92 % | 55 / 83 % | 42 / 67 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 36 / 56 % | 65 / 81 % | 82 / 97 % | 69 / 86 % | 49 / 75 % | 84 / 92 % | 61 / 85 % | 14 / 37 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 41 / 62 % | 59 / 94 % | 77 / 93 % | 58 / 80 % | 29 / 60 % | 41 / 68 % | 34 / 68 % | 40 / 65 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 33 / 58 % | 66 / 88 % | 77 / 91 % | 50 / 71 % | 16 / 43 % | 41 / 67 % | 23 / 50 % | 24 / 53 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 25 / 42 % | 43 / 72 % | 76 / 88 % | 37 / 65 % | 15 / 39 % | 28 / 56 % | 11 / 31 % | 15 / 36 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 18 / 50 % | 76 / 89 % | 34 / 65 % | 40 / 66 % | 27 / 59 % | 44 / 74 % | 26 / 55 % | 32 / 61 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 28 / 58 % | 76 / 88 % | 15 / 40 % | 7 / 19 % | 15 / 26 % | 1 / 5 % | 17 / 37 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 15 / 34 % | 63 / 93 % | 75 / 87 % | 23 / 49 % | 15 / 37 % | 24 / 57 % | 2 / 10 % | 30 / 52 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 33 / 60 % | 60 / 95 % | 74 / 89 % | 62 / 83 % | 54 / 82 % | 56 / 83 % | 24 / 53 % | 29 / 56 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 25 / 53 % | 47 / 83 % | 53 / 85 % | 39 / 64 % | 50 / 74 % | 69 / 84 % | 40 / 70 % | 50 / 71 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 31 / 56 % | 68 / 95 % | 69 / 81 % | 64 / 85 % | 65 / 86 % | 64 / 85 % | 44 / 72 % | 30 / 50 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 23 / 43 % | 66 / 87 % | 68 / 78 % | 50 / 71 % | 24 / 36 % | 48 / 59 % | 23 / 28 % | 19 / 41 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 16 / 41 % | 57 / 91 % | 36 / 66 % | 44 / 71 % | 26 / 55 % | 67 / 81 % | 23 / 45 % | 36 / 60 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 24 / 45 % | 59 / 89 % | 59 / 86 % | 41 / 66 % | 36 / 55 % | 62 / 79 % | 13 / 38 % | 33 / 61 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 12 / 23 % | 40 / 63 % | 6 / 16 % | 45 / 66 % | 16 / 41 % | 56 / 67 % | 13 / 17 % | 22 / 41 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 47 / 77 % | 45 / 71 % | 31 / 60 % | 5 / 21 % | 25 / 50 % | 4 / 18 % | 20 / 48 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 43 / 82 % | 26 / 51 % | 17 / 46 % | 11 / 37 % | 32 / 58 % | 3 / 11 % | 13 / 29 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 40 / 83 % | 10 / 41 % | 10 / 26 % | 7 / 19 % | 16 / 34 % | 1 / 5 % | 19 / 40 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 28 / 49 % | 32 / 90 % | 24 / 64 % | 30 / 59 % | 14 / 42 % | 29 / 49 % | 7 / 26 % | 13 / 37 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 2 / 17 % | 19 / 41 % | 8 / 19 % | 22 / 48 % | 1 / 4 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 20 / 51 % | 0 / 0 % | 8 / 22 % | 0 / 0 % | 12 / 27 % | 0 / 2 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 15 / 75 % | 20 / 45 % | 11 / 30 % | 8 / 24 % | 16 / 42 % | 1 / 7 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 39 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 36 % | 0 / 0 % | 13 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 16 / 77 % | 0 / 4 % | 6 / 13 % | 3 / 12 % | 9 / 16 % | 0 / 2 % | 2 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 2 / 23 % | 8 / 20 % | 8 / 17 % | 10 / 22 % | 0 / 4 % | 15 / 40 % |
