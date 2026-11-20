[English](README.md) · [Deutsch](README.de.md)

# Planning for AGI and beyond

Bericht Q008567 · Quelle openai.com · Datum 2023-02-24 · [Original öffnen](https://openai.com/index/planning-for-agi-and-beyond/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI plädiert für einen schrittweisen, vorsichtigen Übergang zu AGI, breite und faire Teilhabe sowie internationale Regeln und unabhängige Sicherheitsprüfungen. Der Beitrag ist ein programmatisches Positionspapier ohne empirische Ergebnisse, betont die Unsicherheit der Entwicklung und weist darauf hin, dass seine Angaben zur Organisationsstruktur veraltet sind.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 32 / 60 % | 99 / 100 % | – | 99 / 100 % | 58 / 81 % | 67 / 85 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 50 / 74 % | 99 / 100 % | – | 99 / 100 % | 63 / 84 % | 61 / 82 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 33 / 64 % | 98 / 99 % | – | 99 / 100 % | 64 / 84 % | 66 / 84 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 44 % | 94 / 99 % | – | 58 / 88 % | 37 / 67 % | 44 / 71 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 24 / 54 % | 94 / 98 % | – | 74 / 92 % | 46 / 69 % | 38 / 56 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 6 / 39 % | 65 / 88 % | – | 94 / 98 % | 14 / 42 % | 14 / 39 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 18 / 57 % | 90 / 97 % | – | 88 / 97 % | 46 / 72 % | 35 / 63 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 19 / 51 % | 88 / 99 % | – | 80 / 94 % | 38 / 69 % | 57 / 77 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 14 / 50 % | 29 / 91 % | – | 86 / 93 % | 32 / 67 % | 25 / 62 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 24 / 56 % | 82 / 98 % | – | 85 / 97 % | 40 / 70 % | 49 / 67 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 18 / 51 % | 44 / 86 % | – | 84 / 97 % | 51 / 78 % | 34 / 69 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 54 % | 80 / 98 % | – | 76 / 90 % | 40 / 64 % | 60 / 78 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 51 % | 76 / 94 % | – | 79 / 92 % | 24 / 57 % | 38 / 61 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 43 % | 78 / 98 % | – | 43 / 66 % | 18 / 47 % | 19 / 43 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 48 % | 59 / 96 % | – | 77 / 90 % | 35 / 61 % | 45 / 66 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 17 / 52 % | 71 / 92 % | – | 14 / 34 % | 26 / 54 % | 37 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 53 % | 67 / 87 % | – | 54 / 77 % | 34 / 62 % | 28 / 53 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 12 / 46 % | 35 / 94 % | – | 65 / 89 % | 21 / 57 % | 12 / 65 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 46 / 92 % | – | 65 / 83 % | 9 / 30 % | 10 / 25 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 13 / 44 % | 56 / 96 % | – | 47 / 81 % | 31 / 60 % | 33 / 56 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 33 % | 54 / 98 % | – | 16 / 53 % | 12 / 36 % | 8 / 28 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 46 / 92 % | – | 4 / 30 % | 16 / 40 % | 13 / 23 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 5 / 32 % | 27 / 69 % | – | 28 / 70 % | 40 / 67 % | 13 / 40 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 13 / 43 % | 38 / 88 % | – | 35 / 77 % | 19 / 45 % | 14 / 39 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 7 / 47 % | 33 / 96 % | – | 0 / 0 % | 6 / 20 % | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 9 / 41 % | 5 / 52 % | – | 32 / 73 % | 7 / 21 % | 6 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 40 % | 31 / 96 % | – | 10 / 44 % | 10 / 35 % | 6 / 26 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 12 / 25 % | 16 / 64 % | – | 24 / 54 % | 10 / 31 % | 8 / 25 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 22 / 93 % | – | 23 / 63 % | 20 / 49 % | 7 / 21 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 23 / 59 % | – | 0 / 0 % | 7 / 18 % | 5 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 22 / 74 % | – | 3 / 25 % | 5 / 15 % | 5 / 15 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 8 / 20 % | 21 / 56 % | – | 0 / 0 % | 10 / 32 % | 9 / 24 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 14 / 70 % | – | 2 / 26 % | 6 / 14 % | 8 / 22 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 12 / 47 % | – | 0 / 0 % | 8 / 21 % | 5 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 11 / 80 % | – | 11 / 30 % | 5 / 12 % | 6 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 26 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 10 / 58 % | – | 3 / 29 % | 8 / 24 % | 5 / 17 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 10 / 75 % | – | 0 / 0 % | 5 / 16 % | 5 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 10 / 41 % | 9 / 90 % | – | 4 / 25 % | 7 / 22 % | 6 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 24 % | 9 / 20 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 6 / 32 % | – | 8 / 27 % | 6 / 19 % | 6 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 7 / 89 % | – | 8 / 39 % | 7 / 19 % | 7 / 20 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 5 / 81 % | – | 0 / 0 % | 5 / 11 % | 5 / 13 % |
