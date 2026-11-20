[English](README.md) · [Deutsch](README.de.md)

# Example autonomy evaluation protocol

Bericht Q002902 · Quelle metr.org · Datum 2024-03-15 · [Original öffnen](https://metr.org/blog/2024-03-15-example-autonomy-evaluation-protocol/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

METR schlägt ein vorläufiges Prüfverfahren für KI-Fähigkeiten vor, die autonome Risiken ermöglichen könnten: Aufgaben verschiedener Schwierigkeit werden getestet und zu einem „Zeithorizont“-Wert zusammengefasst, der zusammen mit einer Bedrohungsanalyse Schutzmaßnahmen informieren soll. Das Verfahren deckt andere Risikotypen nicht ab; seine Metrik, Aufgabenauswahl und Schwellenwerte sind laut Bericht noch unsicher und nicht ausreichend validiert.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 63 / 78 % | 100 / 100 % | 96 / 99 % | 99 / 100 % | 88 / 94 % | 91 / 94 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 57 / 73 % | 98 / 99 % | 91 / 97 % | 100 / 100 % | 72 / 87 % | 88 / 93 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 78 / 87 % | 92 / 94 % | 97 / 99 % | 99 / 100 % | 85 / 93 % | 86 / 91 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 25 / 46 % | 96 / 99 % | 11 / 36 % | 70 / 84 % | 41 / 68 % | 30 / 49 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 59 % | 87 / 97 % | 31 / 72 % | 93 / 97 % | 39 / 67 % | 56 / 75 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 49 % | 91 / 99 % | 16 / 32 % | 40 / 78 % | 44 / 71 % | 60 / 76 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 49 / 67 % | 83 / 96 % | 58 / 86 % | 86 / 94 % | 70 / 85 % | 81 / 89 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 26 / 46 % | 75 / 96 % | 8 / 22 % | 83 / 89 % | 29 / 58 % | 24 / 42 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 29 / 59 % | 49 / 82 % | 14 / 41 % | 78 / 90 % | 20 / 44 % | 22 / 44 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 44 / 63 % | 50 / 91 % | 23 / 61 % | 74 / 88 % | 61 / 81 % | 22 / 45 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 21 / 47 % | 73 / 95 % | 6 / 12 % | 48 / 78 % | 29 / 53 % | 16 / 29 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 30 / 53 % | 64 / 96 % | 11 / 40 % | 45 / 62 % | 33 / 61 % | 42 / 65 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 26 / 54 % | 60 / 92 % | 14 / 53 % | 37 / 77 % | 32 / 58 % | 41 / 62 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 33 % | 0 / 0 % | 2 / 16 % | 60 / 84 % | 10 / 35 % | 9 / 24 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 15 / 29 % | 58 / 89 % | 5 / 16 % | 56 / 77 % | 24 / 53 % | 12 / 27 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 15 / 43 % | 53 / 93 % | 9 / 26 % | 34 / 62 % | 30 / 57 % | 36 / 58 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 51 / 80 % | 2 / 9 % | 23 / 50 % | 20 / 45 % | 11 / 21 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 12 / 33 % | 45 / 80 % | 1 / 7 % | 41 / 59 % | 18 / 46 % | 7 / 19 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 10 / 42 % | 0 / 0 % | 40 / 62 % | 6 / 15 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 39 / 82 % | 5 / 15 % | 21 / 40 % | 18 / 47 % | 10 / 23 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 32 / 73 % | 0 / 5 % | 0 / 7 % | 6 / 17 % | 6 / 15 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 20 / 43 % | 0 / 0 % | 1 / 7 % | 9 / 22 % | 12 / 35 % | 26 / 48 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 25 / 67 % | 1 / 5 % | 1 / 20 % | 8 / 25 % | 5 / 12 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 19 / 40 % | 0 / 0 % | 3 / 13 % | 0 / 0 % | 17 / 43 % | 24 / 43 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 21 / 56 % | 0 / 1 % | 16 / 33 % | 9 / 24 % | 3 / 7 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 1 / 2 % | 14 / 34 % | 15 / 36 % | 10 / 18 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 12 / 66 % | 1 / 6 % | 0 / 0 % | 12 / 34 % | 15 / 39 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 10 / 26 % | 13 / 58 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 5 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 11 / 44 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 11 / 28 % | 7 / 22 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 10 / 51 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 72 % | 0 / 1 % | 1 / 9 % | 6 / 18 % | 6 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 8 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 6 / 12 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 7 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 6 / 17 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 5 / 9 % |
