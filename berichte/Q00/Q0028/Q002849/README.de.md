[English](README.md) · [Deutsch](README.de.md)

# Frontier AI Taskforce: second progress report

Bericht Q002849 · Quelle aisi.gov.uk · Datum 2023-10-30 · [Original öffnen](https://www.aisi.gov.uk/blog/second-progress-report)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Die britische Frontier AI Taskforce berichtet über den Ausbau ihres Forschungsteams, ein auf elf Organisationen erweitertes Partnernetzwerk und den geplanten Supercomputer Isambard-AI. Sie warnt vor möglichen zusätzlichen Risiken durch leistungsfähigere Modelle, beschreibt Summit-Präsentationen und ein geplantes AI Safety Institute, berichtet aber überwiegend über Aufbau und Vorhaben statt über abgeschlossene Sicherheitsprüfungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 77 / 91 % | 97 / 98 % | 100 / 100 % | 90 / 94 % | 66 / 81 % | 81 / 90 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 49 % | 75 / 97 % | 86 / 94 % | 30 / 54 % | 14 / 37 % | 30 / 53 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 25 / 59 % | 78 / 94 % | 85 / 96 % | 58 / 79 % | 26 / 56 % | 48 / 67 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 12 / 36 % | 62 / 93 % | 80 / 90 % | 15 / 40 % | 8 / 28 % | 9 / 33 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 23 / 55 % | 53 / 86 % | 79 / 96 % | 30 / 59 % | 13 / 43 % | 18 / 56 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 23 / 54 % | 76 / 97 % | 44 / 74 % | 20 / 50 % | 10 / 31 % | 16 / 40 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 35 % | 62 / 85 % | 54 / 84 % | 13 / 36 % | 9 / 39 % | 8 / 38 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 31 / 62 % | 58 / 92 % | 61 / 82 % | 33 / 60 % | 12 / 39 % | 17 / 48 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 20 / 53 % | 57 / 86 % | 48 / 76 % | 17 / 51 % | 16 / 44 % | 22 / 54 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 22 / 52 % | 54 / 87 % | 57 / 92 % | 33 / 62 % | 14 / 44 % | 28 / 62 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 10 / 43 % | 50 / 91 % | 7 / 28 % | 19 / 47 % | 7 / 25 % | 9 / 32 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 35 % | 29 / 87 % | 50 / 78 % | 11 / 32 % | 2 / 9 % | 7 / 20 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 15 / 41 % | 46 / 90 % | 41 / 73 % | 17 / 46 % | 5 / 27 % | 13 / 42 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 20 / 44 % | 45 / 86 % | 8 / 51 % | 39 / 68 % | 12 / 41 % | 36 / 63 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 13 / 44 % | 45 / 82 % | 15 / 53 % | 13 / 39 % | 3 / 20 % | 8 / 29 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 40 / 91 % | 23 / 66 % | 13 / 38 % | 6 / 21 % | 7 / 26 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 12 / 48 % | 37 / 81 % | 35 / 81 % | 15 / 42 % | 13 / 49 % | 23 / 63 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 43 % | 36 / 92 % | 8 / 54 % | 15 / 47 % | 7 / 27 % | 14 / 45 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 33 / 73 % | 2 / 27 % | 11 / 31 % | 6 / 20 % | 8 / 22 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 33 / 84 % | 11 / 42 % | 10 / 30 % | 1 / 5 % | 7 / 21 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 28 / 77 % | 31 / 64 % | 7 / 22 % | 1 / 7 % | 6 / 13 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 30 / 91 % | 12 / 49 % | 22 / 53 % | 9 / 38 % | 9 / 28 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 32 % | 29 / 79 % | 5 / 29 % | 8 / 26 % | 3 / 17 % | 6 / 20 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 28 / 82 % | 5 / 40 % | 7 / 21 % | 1 / 7 % | 8 / 17 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 42 % | 28 / 93 % | 1 / 22 % | 11 / 32 % | 5 / 22 % | 10 / 31 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 25 / 66 % | 2 / 18 % | 8 / 22 % | 1 / 5 % | 7 / 20 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 14 / 46 % | 23 / 73 % | 0 / 0 % | 18 / 49 % | 6 / 23 % | 17 / 47 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 33 % | 18 / 82 % | 2 / 12 % | 8 / 19 % | 2 / 8 % | 6 / 14 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 15 / 41 % | 0 / 0 % | 9 / 25 % | 2 / 9 % | 6 / 17 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 15 / 62 % | 0 / 0 % | 12 / 39 % | 7 / 29 % | 12 / 36 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 44 % | 5 / 38 % | 1 / 17 % | 11 / 36 % | 5 / 17 % | 11 / 26 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 6 / 32 % | 0 / 0 % | 8 / 23 % | 4 / 18 % | 14 / 33 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 14 / 81 % | 0 / 5 % | 7 / 15 % | 1 / 3 % | 6 / 12 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 12 / 59 % | 0 / 0 % | 8 / 18 % | 1 / 6 % | 6 / 16 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 10 / 37 % | 0 / 0 % | 8 / 29 % | 2 / 9 % | 10 / 22 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 8 / 34 % | 2 / 23 % | 1 / 14 % | 8 / 20 % | 3 / 14 % | 9 / 18 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 5 / 51 % | 0 / 0 % | 8 / 31 % | 0 / 0 % | 8 / 20 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 7 / 55 % | 2 / 18 % | 5 / 11 % | 0 / 0 % | 5 / 14 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 5 / 84 % | 0 / 12 % | 6 / 16 % | 1 / 6 % | 5 / 15 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 6 % | 6 / 17 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 5 / 55 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
