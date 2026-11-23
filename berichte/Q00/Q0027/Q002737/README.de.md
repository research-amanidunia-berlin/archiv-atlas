[English](README.md) · [Deutsch](README.de.md)

# Issue Brief: Early Best Practices for Frontier AI Safety Evaluations

Bericht Q002737 · Quelle frontiermodelforum.org · Datum 2024-07-31 · [Original öffnen](https://www.frontiermodelforum.org/updates/early-best-practices-for-frontier-ai-safety-evaluations/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Frontier Model Forum skizziert vorläufige Empfehlungen für Sicherheitsprüfungen fortgeschrittener KI: Fachwissen einbeziehen, Modelle und Gesamtsysteme prüfen, Risiken passend zum Kontext vergleichen sowie unterschiedliche Prompts und normale wie feindliche Nutzungsszenarien berücksichtigen. Bei der Veröffentlichung soll Transparenz unabhängige Prüfung ermöglichen, ohne gefährliche Informationen oder vollständige Testsätze ungeschützt offenzulegen; der Bericht versteht seine Punkte als nicht vollständigen Ausgangspunkt für weitere Arbeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 42 / 62 % | 99 / 100 % | 98 / 99 % | 68 / 83 % | 48 / 69 % | 52 / 72 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 39 / 63 % | 98 / 100 % | 97 / 100 % | 56 / 81 % | 64 / 84 % | 69 / 86 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 42 / 62 % | 85 / 97 % | 93 / 97 % | 41 / 71 % | 15 / 39 % | 49 / 74 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 34 / 70 % | 51 / 99 % | 88 / 99 % | 9 / 28 % | 38 / 70 % | 51 / 78 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 53 / 84 % | 15 / 36 % | 11 / 34 % | 3 / 11 % | 6 / 19 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 21 / 45 % | 52 / 96 % | 17 / 73 % | 26 / 59 % | 9 / 31 % | 23 / 54 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 15 / 43 % | 8 / 47 % | 19 / 44 % | 21 / 57 % | 15 / 40 % | 50 / 74 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 11 / 47 % | 46 / 92 % | 9 / 51 % | 12 / 39 % | 3 / 14 % | 9 / 23 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 17 / 45 % | 39 / 80 % | 33 / 72 % | 13 / 39 % | 6 / 15 % | 7 / 15 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 16 / 41 % | 16 / 88 % | 36 / 77 % | 17 / 51 % | 12 / 37 % | 22 / 59 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 17 / 53 % | 12 / 93 % | 35 / 74 % | 18 / 47 % | 20 / 50 % | 12 / 32 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 20 / 85 % | 18 / 62 % | 29 / 62 % | 12 / 35 % | 7 / 23 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 13 / 35 % | 27 / 95 % | 17 / 46 % | 15 / 44 % | 13 / 33 % | 12 / 30 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 9 / 33 % | 24 / 67 % | 3 / 29 % | 8 / 28 % | 1 / 10 % | 5 / 18 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 11 / 48 % | 23 / 51 % | 7 / 19 % | 1 / 6 % | 3 / 9 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 30 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 9 / 35 % | 17 / 56 % | 3 / 32 % | 6 / 20 % | 1 / 7 % | 9 / 22 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 15 / 39 % | 8 / 27 % | 17 / 60 % | 7 / 29 % | 1 / 8 % | 6 / 19 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 7 / 40 % | 13 / 87 % | 2 / 39 % | 11 / 41 % | 4 / 17 % | 8 / 33 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 9 / 31 % | 13 / 93 % | 0 / 5 % | 6 / 14 % | 1 / 8 % | 5 / 15 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 12 / 36 % | 5 / 12 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 2 / 33 % | 0 / 0 % | 7 / 24 % | 5 / 17 % | 9 / 22 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 2 / 33 % | 0 / 0 % | 7 / 19 % | 2 / 12 % | 8 / 23 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 8 / 37 % | 7 / 46 % | 0 / 0 % | 6 / 21 % | 0 / 5 % | 4 / 9 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 3 / 12 % | 7 / 27 % | 2 / 11 % | 8 / 18 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 6 / 31 % | 8 / 43 % | 0 / 0 % | 6 / 22 % | 1 / 7 % | 6 / 19 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 7 / 26 % | 0 / 0 % | 1 / 14 % | 5 / 13 % | 1 / 6 % | 5 / 12 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 27 % | 2 / 45 % | 0 / 0 % | 4 / 18 % | 1 / 8 % | 4 / 13 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 1 / 6 % | 5 / 14 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 3 / 37 % | 0 / 0 % | 6 / 18 % | 0 / 0 % | 6 / 17 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 4 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 5 / 15 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 10 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 5 / 23 % | 4 / 36 % | 0 / 5 % | 5 / 16 % | 1 / 6 % | 4 / 13 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 6 % | 5 / 12 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 5 / 12 % | 1 / 5 % | 5 / 15 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 14 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 4 % | 4 / 14 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 3 / 32 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 4 / 8 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 6 % | 4 / 9 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 4 / 12 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 4 / 57 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | – | – |
