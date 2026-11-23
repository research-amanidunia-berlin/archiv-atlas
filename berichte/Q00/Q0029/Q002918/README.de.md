[English](README.md) · [Deutsch](README.de.md)

# Mapping the misuse of generative AI

Bericht Q002918 · Quelle deepmind.google · Datum 2024-08-02 · [Original öffnen](https://deepmind.google/blog/mapping-the-misuse-of-generative-ai/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Eine Untersuchung von knapp 200 Medienberichten aus Januar 2023 bis März 2024 ordnet KI-Missbrauch in die Ausnutzung von KI-Fähigkeiten und die Kompromittierung von Systemen ein; in dieser Auswahl überwogen Identitätsnachahmung, Betrug und andere Nutzungen frei zugänglicher Werkzeuge. Die Forschenden nennen Meinungsbeeinflussung und finanziellen Gewinn als häufige Ziele, betonen aber, dass die Medienauswahl keine repräsentative Gesamtschau ist und traditionelle Manipulation nicht direkt verglichen wurde.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 52 / 68 % | 96 / 100 % | 95 / 99 % | 78 / 88 % | 67 / 81 % | 80 / 88 % | 88 / 95 % | 61 / 84 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 47 % | 68 / 98 % | 95 / 99 % | 37 / 66 % | 11 / 31 % | 40 / 67 % | 13 / 47 % | 27 / 53 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 63 / 94 % | 77 / 89 % | 19 / 43 % | 11 / 29 % | 29 / 54 % | 5 / 14 % | 21 / 45 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 38 / 97 % | 70 / 93 % | 24 / 55 % | 8 / 26 % | 15 / 38 % | 14 / 39 % | 33 / 62 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 31 % | 4 / 71 % | 62 / 88 % | 15 / 44 % | 5 / 19 % | 9 / 34 % | 2 / 19 % | 8 / 33 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 23 / 45 % | 12 / 87 % | 51 / 71 % | 17 / 49 % | 11 / 30 % | 25 / 56 % | 4 / 15 % | 10 / 25 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 32 / 52 % | 6 / 36 % | 45 / 57 % | 27 / 51 % | 25 / 41 % | 11 / 21 % | 0 / 0 % | 21 / 41 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 15 / 65 % | 41 / 74 % | 11 / 35 % | 4 / 13 % | 8 / 22 % | 1 / 8 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 14 / 30 % | 35 / 96 % | 37 / 75 % | 10 / 31 % | 5 / 21 % | 11 / 45 % | 2 / 11 % | 12 / 35 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 36 / 55 % | 7 / 36 % | 8 / 21 % | 25 / 52 % | 14 / 29 % | 15 / 28 % | 6 / 14 % | 11 / 30 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 2 / 49 % | 34 / 65 % | 11 / 35 % | 0 / 0 % | 8 / 25 % | 0 / 4 % | 10 / 25 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 12 / 35 % | 22 / 74 % | 31 / 70 % | 14 / 39 % | 8 / 22 % | 17 / 40 % | 6 / 20 % | 17 / 47 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 30 / 78 % | 9 / 36 % | 12 / 35 % | 4 / 15 % | 12 / 27 % | 2 / 10 % | 6 / 22 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 26 / 70 % | 28 / 72 % | 13 / 44 % | 3 / 14 % | 8 / 38 % | 1 / 13 % | 8 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 8 / 87 % | 12 / 55 % | 8 / 25 % | 5 / 14 % | 8 / 15 % | 1 / 8 % | 26 / 52 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 1 / 26 % | 1 / 6 % | 6 / 20 % | 1 / 9 % | 5 / 16 % | 1 / 9 % | 26 / 51 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 11 / 30 % | 4 / 91 % | 23 / 47 % | 6 / 21 % | 3 / 12 % | 6 / 17 % | 0 / 2 % | 13 / 33 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 5 / 72 % | 23 / 52 % | 5 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 22 / 72 % | 4 / 25 % | 11 / 33 % | 3 / 14 % | 8 / 22 % | 0 / 4 % | 8 / 30 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 19 / 72 % | 1 / 14 % | 6 / 16 % | 3 / 13 % | 6 / 18 % | 0 / 5 % | 17 / 43 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 1 / 28 % | 18 / 46 % | 9 / 29 % | 3 / 11 % | 6 / 15 % | 1 / 6 % | 6 / 23 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 15 / 29 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 3 / 74 % | 14 / 55 % | 8 / 24 % | 2 / 10 % | 4 / 18 % | 0 / 4 % | 9 / 33 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 0 / 0 % | 14 / 30 % | 1 / 5 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 4 % | 5 / 13 % | 0 / 1 % | 11 / 29 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 9 / 63 % | 1 / 15 % | 8 / 25 % | 3 / 10 % | 6 / 17 % | 1 / 9 % | 6 / 24 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 1 / 42 % | 0 / 0 % | 7 / 23 % | 1 / 9 % | 8 / 22 % | 1 / 5 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 6 / 58 % | 3 / 20 % | 7 / 18 % | 2 / 9 % | 7 / 17 % | 1 / 5 % | 8 / 28 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 29 % | 2 / 10 % | 6 / 18 % | 1 / 6 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 7 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 7 / 52 % | 1 / 13 % | 6 / 18 % | 3 / 11 % | 7 / 21 % | 0 / 4 % | 6 / 25 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 71 % | 1 / 21 % | 7 / 23 % | 2 / 11 % | 6 / 21 % | 0 / 7 % | 4 / 21 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 2 / 7 % | 6 / 10 % | 0 / 2 % | 5 / 23 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 5 / 12 % | 1 / 7 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 7 % | 4 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | 0 / 0 % |
