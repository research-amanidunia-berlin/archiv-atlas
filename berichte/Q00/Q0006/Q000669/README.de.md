[English](README.md) · [Deutsch](README.de.md)

# Towards embedded evaluations for scheming propensities

Bericht Q000669 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/blog/towards-embedded-evaluations-for-scheming-propensities)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Apollo Research fordert unabhängige, fortlaufende Prüfungen, um festzustellen, ob KI-Modelle im Training oder im Einsatz versuchen, ihre Entwickler und deren Sicherheitsmechanismen zu unterlaufen. Dafür seien vier Nachweise nötig und Prüfer müssten tiefen Zugang zu Trainingsdaten, Tests, interner Überwachung und Vorfällen erhalten; negative Testergebnisse allein reichten nicht, und der Beitrag ist ein Vorschlag statt einer abgeschlossenen Modellprüfung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 51 / 68 % | 98 / 100 % | – | 89 / 94 % | 87 / 94 % | 91 / 94 % | 93 / 97 % | 68 / 83 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 39 / 62 % | 95 / 100 % | – | 70 / 86 % | 48 / 77 % | 80 / 90 % | 56 / 81 % | 54 / 73 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 61 / 77 % | 92 / 97 % | – | 65 / 79 % | 82 / 90 % | 58 / 73 % | 73 / 88 % | 53 / 72 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 55 / 72 % | 85 / 99 % | – | 88 / 93 % | 88 / 95 % | 91 / 94 % | 87 / 95 % | 49 / 73 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 89 / 98 % | – | 38 / 67 % | 13 / 37 % | 34 / 57 % | 9 / 20 % | 17 / 35 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 27 / 50 % | 86 / 99 % | – | 69 / 85 % | 9 / 26 % | 41 / 63 % | 20 / 31 % | 33 / 54 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 54 / 74 % | 81 / 94 % | – | 74 / 87 % | 79 / 89 % | 85 / 90 % | 47 / 83 % | 46 / 68 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 44 / 65 % | 80 / 96 % | – | 78 / 89 % | 77 / 89 % | 79 / 89 % | 58 / 86 % | 44 / 71 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 33 / 54 % | 68 / 98 % | – | 74 / 87 % | 21 / 46 % | 78 / 88 % | 47 / 75 % | 30 / 54 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 27 / 51 % | 69 / 95 % | – | 47 / 71 % | 26 / 44 % | 46 / 63 % | 9 / 29 % | 32 / 53 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 64 / 97 % | – | 42 / 70 % | 13 / 28 % | 23 / 45 % | 8 / 21 % | 30 / 53 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 20 / 47 % | 26 / 92 % | – | 24 / 52 % | 12 / 33 % | 63 / 76 % | 10 / 27 % | 21 / 44 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 50 % | 62 / 97 % | – | 20 / 49 % | 6 / 22 % | 17 / 47 % | 1 / 8 % | 24 / 52 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 15 / 43 % | 54 / 92 % | – | 23 / 47 % | 6 / 19 % | 17 / 39 % | 4 / 19 % | 12 / 34 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 51 / 92 % | – | 13 / 33 % | 4 / 16 % | 10 / 22 % | 0 / 4 % | 7 / 21 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 45 / 83 % | – | 26 / 52 % | 7 / 18 % | 19 / 37 % | 2 / 7 % | 13 / 31 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 21 / 36 % | 43 / 76 % | – | 38 / 68 % | 12 / 27 % | 21 / 40 % | 10 / 19 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 40 / 92 % | – | 9 / 26 % | 5 / 16 % | 8 / 19 % | 1 / 8 % | 15 / 42 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 15 / 44 % | 23 / 60 % | – | 19 / 40 % | 13 / 35 % | 38 / 69 % | 9 / 29 % | 19 / 41 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 37 / 98 % | – | 30 / 61 % | 11 / 28 % | 23 / 44 % | 7 / 25 % | 22 / 55 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 14 / 75 % | – | 36 / 62 % | 13 / 31 % | 14 / 28 % | 1 / 8 % | 14 / 34 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 22 / 47 % | 36 / 91 % | – | 22 / 50 % | 11 / 26 % | 16 / 37 % | 1 / 6 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 35 % | 35 / 87 % | – | 12 / 34 % | 5 / 18 % | 15 / 37 % | 2 / 11 % | 6 / 21 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 4 / 41 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 54 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 12 / 42 % | – | 13 / 42 % | 6 / 21 % | 30 / 54 % | 2 / 8 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 7 / 63 % | – | 12 / 34 % | 6 / 15 % | 9 / 20 % | 0 / 3 % | 20 / 39 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 20 / 66 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 20 / 66 % | – | 12 / 32 % | 0 / 0 % | 9 / 16 % | 0 / 0 % | 15 / 33 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 18 / 47 % | 6 / 19 % | 11 / 35 % | 2 / 13 % | 10 / 27 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 16 / 79 % | – | 8 / 22 % | 0 / 0 % | 9 / 18 % | 1 / 2 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 3 / 74 % | – | 14 / 40 % | 5 / 17 % | 0 / 0 % | 1 / 5 % | 5 / 18 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 13 / 29 % | 5 / 16 % | 13 / 26 % | 0 / 3 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 8 / 17 % | 0 / 0 % | 10 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 10 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 94 % | – | 7 / 14 % | 0 / 0 % | 7 / 11 % | 0 / 0 % | 2 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 9 / 81 % | – | 6 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 6 / 46 % | – | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | 8 / 24 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 8 / 20 % | 3 / 9 % | 5 / 12 % | 0 / 2 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 7 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
