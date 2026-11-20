[English](README.md) · [Deutsch](README.de.md)

# Towards algorithm auditing: A research overview

Bericht Q005375 · Quelle oecd.ai · Datum 2024-07-04 · [Original öffnen](https://oecd.ai/en/wonk/algorithm-auditing-research-overview)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag schlägt wiederkehrende Algorithmus-Audits vor, die Systeme dokumentieren und auf Bias, Wirksamkeit, Robustheit, Datenschutz und Erklärbarkeit prüfen; erkannte Risiken sollen durch passende Maßnahmen verringert und erneut bewertet werden. Eine Prüfung bestätigt laut Text nur die Einhaltung der konkret zugrunde gelegten Vorgaben, weshalb Audits auf einzelne Rechtsrahmen zugeschnitten sein müssen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 23 / 47 % | 98 / 100 % | 31 / 61 % | 88 / 95 % | 43 / 72 % | 32 / 65 % | 47 / 72 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 45 / 62 % | 73 / 99 % | 47 / 83 % | 98 / 100 % | 62 / 83 % | 35 / 64 % | 55 / 79 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 39 / 59 % | 81 / 98 % | 59 / 83 % | 96 / 99 % | 73 / 87 % | 60 / 77 % | 76 / 87 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 30 / 58 % | 31 / 95 % | 16 / 59 % | 82 / 96 % | 46 / 73 % | 15 / 43 % | 35 / 70 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 32 / 53 % | 54 / 91 % | 6 / 22 % | 74 / 92 % | 38 / 69 % | 7 / 20 % | 36 / 65 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 32 / 53 % | 58 / 97 % | 49 / 86 % | 48 / 75 % | 41 / 72 % | 48 / 74 % | 58 / 81 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 14 / 40 % | 43 / 93 % | 23 / 62 % | 49 / 83 % | 18 / 46 % | 17 / 49 % | 30 / 68 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 18 / 38 % | 45 / 87 % | 5 / 26 % | 48 / 74 % | 20 / 47 % | 13 / 41 % | 23 / 56 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 16 / 41 % | 48 / 94 % | 6 / 35 % | 17 / 59 % | 20 / 48 % | 14 / 39 % | 18 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 31 / 97 % | 4 / 16 % | 47 / 85 % | 17 / 54 % | 5 / 26 % | 16 / 55 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 19 / 86 % | 8 / 30 % | 42 / 70 % | 23 / 58 % | 15 / 40 % | 28 / 61 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 11 / 34 % | 39 / 96 % | 4 / 18 % | 32 / 86 % | 16 / 49 % | 7 / 29 % | 11 / 36 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 20 / 42 % | 39 / 95 % | 7 / 32 % | 16 / 48 % | 23 / 52 % | 13 / 34 % | 23 / 45 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 39 / 97 % | 2 / 9 % | 14 / 60 % | 19 / 46 % | 6 / 16 % | 14 / 31 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 34 % | 37 / 83 % | 2 / 16 % | 25 / 72 % | 14 / 40 % | 7 / 32 % | 12 / 52 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 18 / 68 % | 0 / 0 % | 32 / 61 % | 6 / 16 % | 0 / 0 % | 5 / 11 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 27 / 90 % | 4 / 22 % | 31 / 75 % | 20 / 50 % | 9 / 34 % | 8 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 36 % | 26 / 94 % | 1 / 10 % | 2 / 32 % | 11 / 35 % | 5 / 21 % | 11 / 33 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 25 / 94 % | 1 / 9 % | 10 / 51 % | 9 / 25 % | 4 / 15 % | 6 / 18 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 29 % | 22 / 79 % | 0 / 6 % | 24 / 64 % | 11 / 34 % | 3 / 11 % | 8 / 20 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 24 / 96 % | 0 / 4 % | 1 / 21 % | 11 / 31 % | 3 / 15 % | 8 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 23 / 51 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 19 / 49 % | 13 / 76 % | 13 / 46 % | 10 / 36 % | 23 / 53 % | 17 / 46 % | 13 / 33 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 20 / 94 % | 1 / 6 % | 2 / 32 % | 10 / 27 % | 4 / 12 % | 6 / 19 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 20 / 62 % | 1 / 6 % | 0 / 0 % | 9 / 31 % | 0 / 0 % | 9 / 23 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 14 / 41 % | 19 / 87 % | 1 / 10 % | 5 / 30 % | 14 / 38 % | 6 / 27 % | 10 / 40 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 18 / 69 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 2 / 6 % | 5 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 26 % | 15 / 94 % | 0 / 5 % | 16 / 52 % | 8 / 30 % | 5 / 19 % | 6 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 14 / 91 % | 0 / 2 % | 5 / 23 % | 5 / 15 % | 2 / 9 % | 6 / 13 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 13 / 28 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 6 / 15 % | 3 / 16 % | 11 / 29 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 7 / 48 % | 1 / 7 % | 0 / 0 % | 9 / 23 % | 4 / 16 % | 9 / 22 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 80 % | 0 / 4 % | 2 / 18 % | 8 / 22 % | 4 / 18 % | 9 / 29 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 9 / 25 % | 2 / 14 % | 7 / 21 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 34 % | 5 / 68 % | 0 / 6 % | 0 / 6 % | 9 / 25 % | 4 / 12 % | 7 / 20 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 8 / 78 % | 0 / 2 % | 0 / 0 % | 6 / 15 % | 3 / 10 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 32 % | 7 / 91 % | 1 / 6 % | 1 / 21 % | 8 / 29 % | 2 / 13 % | 4 / 17 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 7 / 29 % | 1 / 44 % | 0 / 2 % | 2 / 26 % | 7 / 19 % | 2 / 9 % | 5 / 13 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 4 / 51 % | 0 / 2 % | 0 / 0 % | 7 / 19 % | 2 / 8 % | 5 / 15 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 1 / 71 % | 0 / 3 % | 0 / 6 % | 7 / 19 % | 0 / 0 % | 5 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
