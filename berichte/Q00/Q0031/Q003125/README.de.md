[English](README.md) · [Deutsch](README.de.md)

# Reflections on our Responsible Scaling Policy

Bericht Q003125 · Quelle anthropic.com · Datum 2024-05-20 · [Original öffnen](https://www.anthropic.com/news/reflections-on-our-responsible-scaling-policy)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic berichtet, die Responsible Scaling Policy helfe, Sicherheitsprioritäten für fortgeschrittene KI-Modelle zu ordnen, sei aber an einigen Stellen unklar und müsse angesichts offener Forschungsfragen weiterentwickelt werden. Der Beitrag beschreibt Tests, Schutzmaßnahmen und Aufsicht für abgestufte Risikogrenzen, nennt zugleich methodische Grenzen und ungelöste Fragen; er bietet Anthropics eigene Einschätzung, keine unabhängige Bewertung der Wirksamkeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 67 / 84 % | 98 / 99 % | 100 / 100 % | 91 / 95 % | 77 / 89 % | 90 / 94 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 55 / 70 % | 99 / 100 % | 100 / 100 % | 85 / 92 % | 88 / 95 % | 95 / 97 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 46 / 63 % | 99 / 100 % | 100 / 100 % | 81 / 90 % | 65 / 86 % | 84 / 91 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 39 / 60 % | 100 / 100 % | 100 / 100 % | 81 / 89 % | 77 / 90 % | 85 / 91 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 28 / 48 % | 99 / 100 % | 84 / 97 % | 76 / 88 % | 41 / 61 % | 77 / 87 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 65 / 83 % | 87 / 98 % | 98 / 100 % | 20 / 44 % | 76 / 89 % | 86 / 92 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 62 / 77 % | 90 / 94 % | 97 / 98 % | 87 / 92 % | 89 / 94 % | 92 / 94 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 56 / 74 % | 96 / 98 % | 96 / 99 % | 86 / 92 % | 87 / 94 % | 94 / 96 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 38 / 60 % | 90 / 99 % | 92 / 97 % | 65 / 82 % | 69 / 86 % | 81 / 88 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 35 / 57 % | 76 / 91 % | 92 / 96 % | 59 / 77 % | 45 / 62 % | 76 / 85 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 15 / 42 % | 52 / 88 % | 87 / 96 % | 42 / 69 % | 14 / 37 % | 26 / 60 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 32 / 58 % | 56 / 94 % | 85 / 93 % | 53 / 75 % | 61 / 80 % | 85 / 91 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 44 % | 16 / 49 % | 39 / 59 % | 50 / 73 % | 38 / 65 % | 72 / 84 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 22 / 47 % | 69 / 95 % | 54 / 85 % | 34 / 58 % | 13 / 31 % | 35 / 57 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 56 / 81 % | 65 / 82 % | 28 / 52 % | 9 / 19 % | 21 / 38 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 26 % | 64 / 86 % | 46 / 75 % | 15 / 39 % | 7 / 23 % | 13 / 35 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 59 / 95 % | 20 / 57 % | 13 / 33 % | 7 / 24 % | 13 / 26 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 58 / 89 % | 50 / 82 % | 58 / 78 % | 22 / 47 % | 15 / 35 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 38 / 88 % | 58 / 83 % | 31 / 61 % | 12 / 43 % | 31 / 65 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 12 / 37 % | 46 / 95 % | 53 / 75 % | 26 / 53 % | 10 / 29 % | 16 / 38 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 53 / 75 % | 8 / 17 % | 0 / 0 % | 9 / 15 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 33 % | 13 / 60 % | 17 / 39 % | 35 / 61 % | 14 / 35 % | 48 / 67 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 26 / 53 % | 38 / 89 % | 42 / 74 % | 43 / 66 % | 46 / 69 % | 34 / 58 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 46 / 89 % | 11 / 28 % | 16 / 36 % | 6 / 19 % | 13 / 30 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 36 / 67 % | 43 / 70 % | 19 / 45 % | 5 / 13 % | 16 / 36 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 19 / 46 % | 40 / 80 % | 42 / 74 % | 33 / 59 % | 11 / 34 % | 38 / 62 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 33 / 86 % | 5 / 36 % | 12 / 29 % | 5 / 14 % | 7 / 25 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 25 % | 32 / 82 % | 28 / 50 % | 8 / 26 % | 4 / 15 % | 9 / 23 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 27 / 72 % | 0 / 0 % | 6 / 13 % | 2 / 6 % | 7 / 19 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 26 / 68 % | 21 / 51 % | 9 / 26 % | 3 / 13 % | 8 / 21 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 40 % | 6 / 16 % | 0 / 0 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 15 / 65 % | 2 / 20 % | 9 / 22 % | 1 / 5 % | 13 / 30 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 15 / 94 % | 1 / 15 % | 7 / 20 % | 2 / 8 % | 10 / 21 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 35 % | 11 / 23 % | 10 / 29 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 6 / 35 % | 10 / 31 % | 7 / 21 % | 4 / 13 % | 11 / 22 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 7 / 26 % | 8 / 20 % | 2 / 9 % | 11 / 27 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 9 / 93 % | 3 / 29 % | 8 / 21 % | 3 / 11 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 8 % | 8 / 14 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 4 / 10 % | 6 / 14 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 7 / 19 % | 1 / 6 % | 7 / 15 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 7 / 13 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 2 / 6 % | 6 / 14 % | – | – |
