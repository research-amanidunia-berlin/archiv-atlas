[English](README.md) · [Deutsch](README.de.md)

# AI Accidents: An Emerging Threat

Bericht Q003942 · Quelle cset.georgetown.edu · Datum 2021-07-07 · [Original öffnen](https://cset.georgetown.edu/publication/ai-accidents-an-emerging-threat/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Text ist nur die Executive Summary des Berichts, ergänzt um einen Abbildungsplatzhalter. Die Autoren warnen, KI könne in kritischen Anwendungen unvorhersehbar versagen, und nennen Robustheits-, Spezifikations- und Absicherungsfehler sowie schnelles Betriebstempo, Komplexität und Wettbewerbsdruck als relevante Faktoren. Sie empfehlen mehr Informationsaustausch, Sicherheitsforschung, Standards und Prüfungen sowie internationale Zusammenarbeit; Details und Wirksamkeitsbelege stehen im Auszug nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 24 / 58 % | 37 / 92 % | 16 / 62 % | 83 / 96 % | 25 / 57 % | 20 / 58 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 27 / 53 % | 47 / 94 % | 16 / 65 % | 79 / 96 % | 24 / 60 % | 24 / 62 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 23 / 51 % | 49 / 71 % | 23 / 46 % | 70 / 81 % | 30 / 61 % | 31 / 60 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 18 / 42 % | 20 / 87 % | 12 / 59 % | 41 / 76 % | 18 / 55 % | 18 / 64 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 11 / 34 % | 38 / 81 % | 4 / 18 % | 30 / 47 % | 11 / 30 % | 19 / 42 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 7 / 34 % | 38 / 80 % | 2 / 17 % | 8 / 50 % | 8 / 27 % | 6 / 26 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 12 / 54 % | 35 / 82 % | 8 / 46 % | 2 / 44 % | 11 / 37 % | 17 / 53 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 10 / 37 % | 34 / 79 % | 1 / 10 % | 1 / 33 % | 11 / 37 % | 8 / 38 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 9 / 32 % | 33 / 79 % | 5 / 35 % | 1 / 55 % | 12 / 42 % | 11 / 35 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 32 / 86 % | 0 / 6 % | 2 / 40 % | 5 / 12 % | 6 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 12 / 37 % | 30 / 68 % | 1 / 5 % | 1 / 25 % | 6 / 25 % | 6 / 24 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 23 / 52 % | 27 / 93 % | 9 / 45 % | 5 / 68 % | 15 / 47 % | 13 / 43 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 10 / 41 % | 24 / 93 % | 1 / 18 % | 3 / 40 % | 7 / 25 % | 7 / 22 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 18 / 50 % | 20 / 86 % | 2 / 20 % | 23 / 74 % | 12 / 43 % | 9 / 27 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 49 % | 23 / 97 % | 8 / 49 % | 8 / 55 % | 12 / 45 % | 9 / 46 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 11 / 43 % | 23 / 89 % | 2 / 17 % | 3 / 25 % | 11 / 32 % | 9 / 28 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 8 / 38 % | 22 / 68 % | 1 / 7 % | 0 / 0 % | 5 / 15 % | 5 / 11 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 19 / 46 % | 20 / 90 % | 5 / 38 % | 5 / 50 % | 11 / 44 % | 11 / 37 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 36 % | 18 / 88 % | 2 / 15 % | 5 / 41 % | 9 / 30 % | 6 / 24 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 17 / 51 % | 0 / 4 % | 0 / 5 % | 6 / 18 % | 5 / 15 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 6 / 33 % | 15 / 56 % | 6 / 27 % | 9 / 59 % | 11 / 36 % | 13 / 47 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 41 % | 5 / 13 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 6 / 35 % | 14 / 78 % | 0 / 6 % | 2 / 29 % | 6 / 19 % | 6 / 16 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 14 / 45 % | 5 / 95 % | 7 / 35 % | 7 / 44 % | 10 / 41 % | 12 / 45 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 11 / 40 % | 13 / 52 % | 1 / 11 % | 0 / 0 % | 10 / 34 % | 9 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 45 % | 13 / 80 % | 2 / 20 % | 1 / 31 % | 7 / 29 % | 7 / 28 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 42 % | 11 / 54 % | 0 / 3 % | 0 / 7 % | 6 / 19 % | 4 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 8 / 54 % | 5 / 23 % | 7 / 26 % | 11 / 38 % | 10 / 31 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 9 / 50 % | 0 / 0 % | 3 / 17 % | 0 / 0 % | 7 / 27 % | 6 / 15 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 38 % | 3 / 36 % | 1 / 12 % | 3 / 21 % | 9 / 27 % | 8 / 24 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 6 / 38 % | 8 / 93 % | 1 / 12 % | 4 / 63 % | 8 / 32 % | 8 / 28 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 8 / 63 % | 1 / 9 % | 0 / 0 % | 6 / 16 % | 5 / 9 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 6 % | 0 / 0 % | 8 / 27 % | 5 / 15 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 34 % | 8 / 89 % | 0 / 5 % | 0 / 0 % | 7 / 29 % | 6 / 19 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 3 / 64 % | 1 / 9 % | 1 / 21 % | 7 / 24 % | 4 / 10 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 6 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 14 % | 6 / 11 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 11 % | 5 / 8 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 5 / 14 % | 4 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 8 % | 5 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 5 / 88 % | 0 / 2 % | 0 / 5 % | 5 / 11 % | 3 / 6 % |
