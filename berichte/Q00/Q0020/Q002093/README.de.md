[English](README.md) · [Deutsch](README.de.md)

# Common Elements of Frontier AI Safety Policies (December 2025 Update)

Bericht Q002093 · Quelle metr.org · Datum 2025-12-09 · [Original öffnen](https://metr.org/blog/2025-12-09-common-elements-of-frontier-ai-safety-policies/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Text ist ein Auszug aus METRs Bericht von Dezember 2025, keine vollständige Einzelanalyse der zwölf veröffentlichten Richtlinien. METR zufolge umfassen gemeinsame Ansätze Fähigkeitsschwellen und regelmäßige Modellprüfungen, Schutz der Modellgewichte, Einsatzsicherungen, mögliche Stopps bei unzureichenden Schutzmaßnahmen sowie Aufsicht und spätere Überarbeitungen; die Wirksamkeit wird im Auszug nicht belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 64 % | 87 / 97 % | 40 / 80 % | 91 / 97 % | 59 / 80 % | 60 / 81 % | 55 / 78 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 32 / 62 % | 88 / 98 % | 77 / 91 % | 77 / 94 % | 78 / 88 % | 86 / 92 % | 77 / 87 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 58 / 81 % | 81 / 93 % | 88 / 95 % | 85 / 96 % | 85 / 93 % | 87 / 93 % | 73 / 87 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 21 / 51 % | 72 / 88 % | 13 / 49 % | 86 / 95 % | 36 / 61 % | 45 / 68 % | 32 / 57 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 28 / 56 % | 82 / 97 % | 62 / 86 % | 80 / 96 % | 55 / 80 % | 70 / 86 % | 66 / 84 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 21 / 52 % | 16 / 44 % | 14 / 54 % | 82 / 93 % | 34 / 61 % | 24 / 54 % | 16 / 43 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 17 / 46 % | 81 / 93 % | 29 / 54 % | 41 / 61 % | 56 / 77 % | 51 / 67 % | 30 / 50 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 17 / 55 % | 61 / 96 % | 15 / 48 % | 74 / 88 % | 33 / 60 % | 34 / 60 % | 24 / 47 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 44 % | 74 / 94 % | 14 / 27 % | 60 / 77 % | 49 / 71 % | 59 / 69 % | 36 / 60 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 23 / 49 % | 49 / 85 % | 28 / 54 % | 69 / 81 % | 49 / 70 % | 49 / 65 % | 34 / 57 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 21 / 53 % | 46 / 84 % | 31 / 71 % | 48 / 83 % | 20 / 43 % | 54 / 78 % | 40 / 68 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 49 / 79 % | 2 / 12 % | 35 / 72 % | 18 / 42 % | 11 / 27 % | 7 / 22 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 47 / 78 % | 1 / 6 % | 20 / 53 % | 12 / 34 % | 6 / 20 % | 3 / 13 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 9 / 31 % | 47 / 77 % | 4 / 21 % | 6 / 18 % | 13 / 34 % | 13 / 35 % | 6 / 22 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 16 / 47 % | 44 / 87 % | 4 / 19 % | 38 / 56 % | 17 / 42 % | 10 / 30 % | 8 / 28 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 20 / 46 % | 39 / 88 % | 10 / 35 % | 15 / 35 % | 27 / 56 % | 16 / 45 % | 20 / 42 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 29 % | 36 / 66 % | 2 / 14 % | 38 / 67 % | 13 / 32 % | 8 / 31 % | 5 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 36 / 77 % | 10 / 42 % | 12 / 58 % | 37 / 65 % | 10 / 36 % | 19 / 44 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 34 / 78 % | 1 / 9 % | 5 / 34 % | 12 / 31 % | 5 / 18 % | 4 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 33 / 81 % | 1 / 8 % | 1 / 21 % | 11 / 31 % | 6 / 17 % | 4 / 15 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 17 / 50 % | 22 / 51 % | 11 / 39 % | 23 / 57 % | 31 / 58 % | 16 / 39 % | 20 / 48 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 12 / 40 % | 23 / 50 % | 2 / 12 % | 0 / 0 % | 25 / 56 % | 27 / 58 % | 10 / 36 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 16 / 43 % | 24 / 51 % | 3 / 18 % | 27 / 59 % | 19 / 43 % | 11 / 28 % | 6 / 22 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 28 % | 27 / 81 % | 0 / 3 % | 0 / 0 % | 8 / 24 % | 5 / 16 % | 3 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 51 % | 5 / 13 % | 0 / 0 % | 1 / 3 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 15 / 33 % | 21 / 56 % | 1 / 6 % | 21 / 49 % | 16 / 44 % | 10 / 31 % | 5 / 15 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 19 / 81 % | 1 / 6 % | 5 / 18 % | 7 / 23 % | 5 / 17 % | 4 / 15 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 17 / 52 % | 1 / 7 % | 16 / 42 % | 16 / 45 % | 6 / 26 % | 5 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 39 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 16 / 44 % | 0 / 0 % | 1 / 17 % | 7 / 18 % | 5 / 17 % | 2 / 8 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 11 / 40 % | 14 / 50 % | 1 / 5 % | 12 / 36 % | 13 / 35 % | 9 / 26 % | 6 / 17 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 3 / 14 % | 0 / 0 % | 13 / 36 % | 8 / 25 % | 11 / 29 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 9 / 27 % | 3 / 24 % | 1 / 8 % | 0 / 0 % | 10 / 34 % | 9 / 28 % | 6 / 20 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 9 / 29 % | 8 / 20 % | 5 / 16 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 8 / 19 % | 6 / 13 % | 2 / 7 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 5 / 11 % | 1 / 5 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 1 / 4 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 7 / 16 % | 5 / 13 % | 1 / 6 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 1 / 12 % | 7 / 21 % | 0 / 0 % | 2 / 10 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 6 / 20 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 19 % | 5 / 13 % | 2 / 7 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 4 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % |
