[English](README.md) · [Deutsch](README.de.md)

# National Standard of the People's Republic of China: Cybersecurity Technology—Safety Specifications for Generative Artificial Intelligence Pre-Training and Fine-Tuning Data (Draft for Feedback)

Bericht Q002140 · Quelle cset.georgetown.edu · Datum 2025-11-07 · [Original öffnen](https://cset.georgetown.edu/publication/china-gen-ai-training-data-safety-standard-draft/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug beschreibt einen chinesischen Entwurfstandard zu Sicherheitsanforderungen und Bewertungen für Vortrainings- und Feinabstimmungsdaten generativer KI. Die Einleitung zählt auch politische Zensur zum Sicherheitsverständnis; konkrete Regeln fehlen im Auszug, der für den restlichen Text auf ein PDF verweist.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 36 / 58 % | 18 / 46 % | 93 / 98 % | 26 / 53 % | 10 / 33 % | 13 / 42 % | 19 / 55 % | 9 / 27 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 55 / 81 % | 10 / 26 % | 4 / 18 % | 8 / 21 % | 2 / 12 % | 9 / 25 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 29 / 50 % | 46 / 81 % | 31 / 68 % | 20 / 51 % | 14 / 40 % | 37 / 67 % | 10 / 37 % | 9 / 24 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 54 % | 39 / 87 % | 40 / 73 % | 39 / 65 % | 22 / 46 % | 36 / 64 % | 29 / 62 % | 23 / 47 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 5 / 32 % | 39 / 54 % | 18 / 38 % | 8 / 19 % | 12 / 23 % | 0 / 0 % | 25 / 43 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 34 / 52 % | 0 / 0 % | 14 / 44 % | 35 / 60 % | 22 / 45 % | 36 / 59 % | 20 / 55 % | 29 / 54 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 20 / 44 % | 35 / 65 % | 17 / 46 % | 15 / 36 % | 9 / 28 % | 15 / 41 % | 5 / 20 % | 19 / 42 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 33 / 72 % | 17 / 65 % | 14 / 33 % | 4 / 17 % | 7 / 18 % | 2 / 13 % | 9 / 26 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 24 / 41 % | 22 / 57 % | 0 / 0 % | 18 / 48 % | 15 / 38 % | 30 / 60 % | 9 / 31 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 25 / 61 % | 30 / 67 % | 10 / 24 % | 6 / 17 % | 6 / 14 % | 2 / 10 % | 8 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 27 / 77 % | 14 / 36 % | 14 / 34 % | 4 / 17 % | 6 / 18 % | 3 / 12 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 14 / 60 % | 22 / 43 % | 5 / 12 % | 0 / 6 % | 3 / 7 % | 0 / 2 % | 7 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 18 / 41 % | 22 / 61 % | 17 / 52 % | 16 / 38 % | 8 / 26 % | 15 / 43 % | 7 / 24 % | 15 / 35 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 22 / 59 % | 0 / 0 % | 12 / 35 % | 6 / 20 % | 8 / 20 % | 7 / 19 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 20 / 50 % | 8 / 26 % | 2 / 10 % | 5 / 16 % | 1 / 6 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 12 / 39 % | 8 / 21 % | 11 / 28 % | 3 / 17 % | 16 / 41 % | 2 / 9 % | 11 / 31 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 15 / 53 % | 0 / 0 % | 6 / 13 % | 1 / 7 % | 5 / 10 % | 0 / 2 % | 3 / 12 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 24 % | 5 / 13 % | 13 / 29 % | 2 / 11 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 5 / 40 % | 6 / 39 % | 10 / 30 % | 3 / 14 % | 4 / 10 % | 1 / 6 % | 10 / 35 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 3 / 13 % | 8 / 18 % | 2 / 10 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 4 / 13 % | 8 / 17 % | 2 / 9 % | 8 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 5 / 16 % | 8 / 19 % | 3 / 8 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 3 / 12 % | 6 / 15 % | 1 / 5 % | 2 / 11 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 7 % | 3 / 7 % | 1 / 4 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 5 % | 3 / 9 % | 1 / 4 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 3 / 11 % | 6 / 12 % | 1 / 5 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 7 % | 5 / 13 % | 0 / 3 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 2 / 10 % | 5 / 11 % | 1 / 4 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 7 / 40 % | 0 / 0 % | 7 / 18 % | 2 / 11 % | 5 / 12 % | 0 / 3 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 2 / 7 % | 3 / 7 % | 0 / 2 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 9 % | 4 / 11 % | 0 / 2 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 6 % | 5 / 9 % | 0 / 2 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 3 / 9 % | 4 / 11 % | 1 / 5 % | 6 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 8 % | 5 / 15 % | 1 / 5 % | 6 / 19 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 8 % | 4 / 11 % | 0 / 2 % | 4 / 13 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 7 % | 0 / 0 % | 0 / 2 % | 3 / 11 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
