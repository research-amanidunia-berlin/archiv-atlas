[English](README.md) · [Deutsch](README.de.md)

# OpenAI’s Approach to Frontier Risk

Bericht Q002791 · Quelle openai.com · Datum 2023-10-26 · [Original öffnen](https://openai.com/global-affairs/our-approach-to-frontier-risk/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet über Sicherheitsprüfungen und freiwillige Maßnahmen für fortgeschrittene KI und stellt ein geplantes Framework zur Überwachung und Begrenzung von Risiken vor. Die beschriebenen Tests lieferten laut Unternehmen gemischte Befunde; OpenAI räumt ein, dass Wissen über katastrophale Risiken begrenzt ist und Labortests späteren Missbrauch nicht vollständig vorhersagen können.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 39 / 61 % | 99 / 100 % | 100 / 100 % | 65 / 84 % | 70 / 85 % | 84 / 92 % | 73 / 90 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 49 / 66 % | 98 / 100 % | 100 / 100 % | 77 / 89 % | 57 / 80 % | 78 / 88 % | 77 / 92 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 30 / 52 % | 99 / 100 % | 100 / 100 % | 73 / 85 % | 64 / 79 % | 78 / 88 % | 78 / 89 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 49 / 65 % | 99 / 100 % | 99 / 100 % | 79 / 89 % | 58 / 74 % | 84 / 90 % | 89 / 95 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 53 / 72 % | 88 / 97 % | 99 / 100 % | 83 / 91 % | 59 / 79 % | 78 / 87 % | 85 / 95 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 39 / 62 % | 97 / 99 % | 98 / 99 % | 58 / 79 % | 68 / 82 % | 86 / 93 % | 83 / 90 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 51 / 70 % | 94 / 98 % | 98 / 100 % | 30 / 56 % | 64 / 80 % | 79 / 89 % | 88 / 96 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 31 / 49 % | 95 / 98 % | 98 / 99 % | 66 / 82 % | 47 / 65 % | 58 / 73 % | 68 / 81 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 42 / 63 % | 92 / 98 % | 91 / 97 % | 77 / 88 % | 80 / 90 % | 84 / 90 % | 97 / 98 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 30 % | 96 / 98 % | 9 / 23 % | 13 / 30 % | 7 / 21 % | 15 / 30 % | 10 / 26 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 34 % | 19 / 79 % | 93 / 98 % | 26 / 54 % | 9 / 30 % | 18 / 47 % | 10 / 34 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 52 / 92 % | 90 / 97 % | 51 / 74 % | 17 / 45 % | 18 / 42 % | 16 / 39 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 48 % | 41 / 82 % | 89 / 94 % | 48 / 74 % | 23 / 48 % | 57 / 77 % | 9 / 27 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 17 / 50 % | 79 / 93 % | 87 / 95 % | 34 / 61 % | 19 / 50 % | 22 / 52 % | 20 / 44 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 22 / 52 % | 83 / 99 % | 71 / 94 % | 58 / 78 % | 34 / 57 % | 59 / 78 % | 36 / 72 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 22 / 44 % | 39 / 94 % | 83 / 94 % | 39 / 68 % | 8 / 34 % | 30 / 70 % | 10 / 31 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 22 / 45 % | 83 / 98 % | 79 / 89 % | 34 / 59 % | 12 / 30 % | 22 / 46 % | 13 / 34 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 21 / 46 % | 81 / 95 % | 76 / 89 % | 35 / 60 % | 18 / 40 % | 30 / 56 % | 15 / 35 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 23 / 44 % | 76 / 98 % | 75 / 89 % | 34 / 62 % | 13 / 34 % | 30 / 56 % | 22 / 46 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 20 / 33 % | 54 / 85 % | 75 / 90 % | 33 / 62 % | 19 / 44 % | 25 / 64 % | 18 / 36 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 21 / 46 % | 71 / 94 % | 69 / 83 % | 43 / 66 % | 16 / 39 % | 41 / 61 % | 6 / 17 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 11 / 39 % | 70 / 96 % | 35 / 76 % | 24 / 49 % | 16 / 40 % | 34 / 58 % | 14 / 35 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 23 / 45 % | 67 / 93 % | 69 / 86 % | 41 / 64 % | 13 / 34 % | 26 / 50 % | 12 / 29 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 13 / 31 % | 67 / 98 % | 69 / 81 % | 11 / 31 % | 6 / 21 % | 11 / 28 % | 2 / 7 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 26 % | 68 / 94 % | 63 / 87 % | 17 / 42 % | 8 / 28 % | 20 / 55 % | 9 / 29 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 39 / 76 % | 63 / 81 % | 10 / 24 % | 1 / 9 % | 11 / 18 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 44 % | 45 / 91 % | 62 / 83 % | 23 / 51 % | 20 / 49 % | 34 / 69 % | 10 / 36 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 57 / 99 % | 18 / 56 % | 18 / 40 % | 9 / 24 % | 10 / 31 % | 6 / 18 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 9 / 27 % | 44 / 91 % | 24 / 49 % | 7 / 21 % | 4 / 15 % | 10 / 24 % | 1 / 6 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 41 / 74 % | 16 / 47 % | 13 / 34 % | 5 / 20 % | 15 / 35 % | 5 / 12 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 13 / 33 % | 37 / 84 % | 23 / 50 % | 14 / 34 % | 12 / 28 % | 15 / 43 % | 2 / 8 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 37 / 93 % | 17 / 56 % | 15 / 38 % | 11 / 38 % | 16 / 33 % | 6 / 17 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 30 % | 31 / 92 % | 5 / 31 % | 15 / 43 % | 9 / 29 % | 21 / 46 % | 2 / 8 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 26 / 44 % | 13 / 31 % | 5 / 27 % | 13 / 29 % | 2 / 7 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 23 / 67 % | 20 / 53 % | 13 / 33 % | 6 / 18 % | 14 / 34 % | 1 / 3 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 21 / 90 % | 6 / 32 % | 7 / 19 % | 2 / 11 % | 10 / 22 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 10 / 27 % | 0 / 0 % | 20 / 41 % | 0 / 0 % | 13 / 22 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 20 / 90 % | 1 / 16 % | 8 / 19 % | 5 / 18 % | 9 / 21 % | 1 / 3 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 37 % | 8 / 23 % | 13 / 38 % | 2 / 12 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 11 / 68 % | 0 / 0 % | 10 / 23 % | 8 / 21 % | 10 / 20 % | 1 / 4 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 9 / 18 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 9 / 68 % | 1 / 8 % | 7 / 14 % | 3 / 10 % | 7 / 16 % | 0 / 2 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 6 % | 8 / 16 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 2 / 11 % | 7 / 13 % | 0 / 0 % | – |
