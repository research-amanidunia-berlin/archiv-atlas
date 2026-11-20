[English](README.md) · [Deutsch](README.de.md)

# New AILuminate Safety and Jailbreak Results, 27 Systems

Bericht Q000284 · Quelle mlcommons.org · Datum 2026-10-29 · [Original öffnen](https://mlcommons.org/2026/10/ailuminate-safety-1-2-1-and-jailbreak-1-1/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

MLCommons stellt Safety 1.2.1 und Jailbreak 1.1 vor, Benchmarks für schädliche Antworten und die Wirkung veröffentlichter Angriffstechniken; Safety-Ergebnisse für 27 Systeme sind bereits öffentlich. Laut Bericht nutzen die aktualisierten Tests einen deterministischen Klassifikator, Perzentilwerte und den Dienst Candela. Sie prüfen jedoch nur einzelne englische Textdialoge, decken nicht alle Angriffsarten ab und messen weder Nützlichkeit noch allgemeine Fähigkeiten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 58 / 74 % | 89 / 98 % | 95 / 98 % | 100 / 100 % | 33 / 54 % | 88 / 92 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 46 / 65 % | 100 / 100 % | 79 / 91 % | 100 / 100 % | 70 / 84 % | 84 / 90 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 41 / 58 % | 68 / 97 % | 60 / 83 % | 97 / 99 % | 79 / 89 % | 76 / 87 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 35 / 56 % | 71 / 89 % | 38 / 58 % | 95 / 97 % | 45 / 69 % | 49 / 63 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 23 / 84 % | 16 / 43 % | 93 / 98 % | 62 / 80 % | 17 / 34 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 32 / 52 % | 93 / 99 % | 25 / 39 % | 89 / 93 % | 59 / 76 % | 60 / 74 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 15 / 41 % | 58 / 95 % | 9 / 22 % | 89 / 96 % | 41 / 62 % | 57 / 70 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 47 / 64 % | 72 / 96 % | 40 / 62 % | 88 / 93 % | 67 / 82 % | 39 / 55 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 35 / 54 % | 47 / 78 % | 38 / 67 % | 86 / 92 % | 78 / 88 % | 75 / 86 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 35 / 58 % | 58 / 89 % | 47 / 75 % | 84 / 97 % | 80 / 89 % | 79 / 87 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 36 / 81 % | 1 / 4 % | 78 / 87 % | 17 / 40 % | 15 / 30 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 18 / 36 % | 24 / 84 % | 1 / 5 % | 77 / 89 % | 15 / 38 % | 16 / 32 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 34 / 56 % | 55 / 98 % | 18 / 44 % | 74 / 86 % | 65 / 81 % | 36 / 66 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 68 / 95 % | 2 / 9 % | 60 / 80 % | 30 / 55 % | 20 / 41 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 23 / 49 % | 22 / 67 % | 23 / 45 % | 67 / 78 % | 49 / 69 % | 33 / 52 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 59 / 90 % | 4 / 16 % | 6 / 21 % | 15 / 32 % | 11 / 24 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 50 / 93 % | 6 / 21 % | 20 / 59 % | 28 / 56 % | 14 / 33 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 32 % | 4 / 54 % | 3 / 17 % | 50 / 80 % | 21 / 45 % | 11 / 35 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 45 / 66 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 16 / 47 % | 44 / 80 % | 2 / 7 % | 7 / 22 % | 17 / 38 % | 8 / 15 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 24 / 38 % | 15 / 61 % | 3 / 9 % | 24 / 40 % | 29 / 54 % | 28 / 51 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 37 % | 8 / 18 % | 8 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 32 % | 16 / 34 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 8 / 17 % | 15 / 24 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 10 / 38 % | 0 / 0 % | 15 / 34 % | 14 / 31 % | 8 / 14 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 14 / 28 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 14 / 81 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 6 / 13 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 13 / 63 % | 1 / 6 % | 3 / 16 % | 11 / 26 % | 10 / 21 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 11 / 28 % | 2 / 43 % | 0 / 2 % | 2 / 9 % | 10 / 28 % | 8 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 10 / 22 % | 5 / 11 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 29 % | 5 / 68 % | 0 / 3 % | 0 / 0 % | 8 / 21 % | 10 / 21 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 78 % | 0 / 0 % | 0 / 5 % | 10 / 28 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 7 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 9 / 28 % | 0 / 0 % | 0 / 2 % | 1 / 9 % | 6 / 17 % | 4 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 5 / 39 % | 0 / 1 % | 0 / 0 % | 8 / 17 % | 6 / 15 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 1 / 14 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 7 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 3 / 76 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 7 / 13 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 4 / 8 % |
