[English](README.md) · [Deutsch](README.de.md)

# Frontier AI regulation: Managing emerging risks to public safety

Bericht Q008605 · Quelle openai.com · Datum 2023-07-06 · [Original öffnen](https://openai.com/index/frontier-ai-regulation/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Quelltext ist nur ein Auszug mit Abstract, Mitwirkendenangaben und Bildunterschriften. Der Abstract schlägt für besonders leistungsfähige KI-Modelle Sicherheitsstandards, Registrierungs- und Berichtspflichten sowie Aufsicht vor; genannt werden außerdem Prüfungen vor und nach der Einführung. Es handelt sich um Vorschläge, nicht um einen Bericht über belegte Umsetzungsergebnisse.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 52 / 70 % | 96 / 99 % | – | 99 / 100 % | 67 / 85 % | 58 / 83 % | 39 / 70 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 51 / 77 % | 79 / 99 % | – | 99 / 100 % | 73 / 87 % | 51 / 78 % | 24 / 55 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 54 % | 86 / 98 % | – | 64 / 91 % | 33 / 68 % | 48 / 77 % | 20 / 56 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 17 / 50 % | 82 / 99 % | – | 48 / 88 % | 28 / 61 % | 19 / 58 % | 9 / 33 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 14 / 39 % | 73 / 92 % | – | 81 / 93 % | 24 / 52 % | 20 / 61 % | 12 / 43 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 52 / 71 % | 68 / 93 % | – | 76 / 94 % | 60 / 81 % | 67 / 84 % | 28 / 60 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 16 / 44 % | 68 / 93 % | – | 27 / 72 % | 20 / 46 % | 12 / 31 % | 4 / 17 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 22 / 54 % | 61 / 98 % | – | 21 / 80 % | 36 / 64 % | 35 / 70 % | 15 / 46 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 28 / 61 % | 58 / 88 % | – | 28 / 73 % | 29 / 60 % | 30 / 60 % | 13 / 47 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 23 / 50 % | 54 / 91 % | – | 55 / 77 % | 28 / 52 % | 36 / 66 % | 13 / 37 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 21 / 42 % | 54 / 85 % | – | 14 / 41 % | 15 / 45 % | 18 / 43 % | 7 / 27 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 29 / 54 % | 51 / 85 % | – | 45 / 78 % | 30 / 59 % | 28 / 59 % | 10 / 31 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 16 / 47 % | 48 / 87 % | – | 9 / 53 % | 17 / 42 % | 20 / 50 % | 8 / 27 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 12 / 33 % | 43 / 87 % | – | 8 / 34 % | 8 / 29 % | 9 / 24 % | 2 / 11 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 16 / 51 % | 41 / 82 % | – | 16 / 69 % | 32 / 60 % | 19 / 64 % | 11 / 41 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 26 / 49 % | 40 / 81 % | – | 32 / 69 % | 18 / 49 % | 21 / 61 % | 5 / 19 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 29 / 65 % | 36 / 92 % | – | 38 / 70 % | 32 / 60 % | 24 / 57 % | 13 / 40 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 22 / 51 % | 37 / 94 % | – | 23 / 53 % | 10 / 39 % | 17 / 53 % | 7 / 29 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 15 / 46 % | 36 / 90 % | – | 19 / 57 % | 10 / 35 % | 11 / 41 % | 1 / 14 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 25 / 51 % | 31 / 95 % | – | 23 / 73 % | 29 / 60 % | 10 / 33 % | 9 / 33 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 11 / 38 % | 26 / 70 % | – | 4 / 33 % | 10 / 26 % | 11 / 28 % | 4 / 16 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 26 / 62 % | – | 0 / 0 % | 7 / 22 % | 7 / 23 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 15 / 46 % | 25 / 93 % | – | 7 / 35 % | 18 / 46 % | 11 / 29 % | 7 / 26 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 5 / 35 % | 25 / 87 % | – | 1 / 21 % | 7 / 25 % | 5 / 20 % | 2 / 13 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 25 / 88 % | – | 1 / 23 % | 10 / 28 % | 11 / 22 % | 1 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 36 % | 24 / 87 % | – | 1 / 14 % | 10 / 33 % | 13 / 34 % | 2 / 9 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 18 / 45 % | 18 / 67 % | – | 0 / 0 % | 24 / 58 % | 20 / 51 % | 7 / 27 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 21 / 52 % | – | 23 / 54 % | 7 / 19 % | 6 / 14 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 35 % | 21 / 96 % | – | 11 / 40 % | 12 / 35 % | 10 / 32 % | 5 / 21 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 9 / 36 % | 17 / 45 % | – | 3 / 18 % | 8 / 24 % | 8 / 24 % | 2 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 14 / 43 % | 7 / 57 % | – | 15 / 55 % | 16 / 49 % | 9 / 40 % | 1 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 16 / 34 % | 15 / 98 % | – | 3 / 41 % | 11 / 33 % | 10 / 32 % | 3 / 18 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 16 / 53 % | – | 0 / 0 % | 7 / 16 % | 7 / 17 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 12 / 30 % | 12 / 48 % | – | 0 / 0 % | 10 / 34 % | 10 / 33 % | 5 / 30 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 10 / 28 % | 4 / 46 % | – | 1 / 14 % | 11 / 29 % | 5 / 20 % | 3 / 11 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 4 % | 7 / 18 % | 9 / 18 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 7 / 19 % | 2 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 32 % | 5 / 53 % | – | 1 / 11 % | 8 / 21 % | 9 / 24 % | 2 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 6 / 15 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 4 / 39 % | – | 0 / 0 % | 7 / 17 % | 5 / 11 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 1 / 14 % | 0 / 0 % | 5 / 18 % | 3 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 22 % | – | 0 / 0 % | 5 / 12 % | 5 / 14 % | 0 / 0 % |
