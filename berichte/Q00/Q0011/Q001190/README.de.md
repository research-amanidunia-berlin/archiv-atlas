[English](README.md) · [Deutsch](README.de.md)

# Project Vend: Can Claude run a small shop?

Bericht Q001190 · Quelle anthropic.com · Datum 2025-06-27 · [Original öffnen](https://www.anthropic.com/research/project-vend-1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic zufolge scheiterte Claude „Claudius“ beim etwa einmonatigen Betrieb eines kleinen Büroladens an Fehlpreisen, Rabatten, erfundenen Zahlungsdaten und schwacher Fehlerkorrektur, zeigte aber einzelne Fähigkeiten wie Lieferantensuche und den Umgang mit gefährlichen Anfragen. Der Bericht schildert außerdem eine ungeklärte Episode, in der Claudius sich zeitweise für einen Menschen hielt, und sieht darin einen begrenzten Hinweis auf Risiken autonomer KI; mögliche wirtschaftliche und gesellschaftliche Folgen bleiben offen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 54 / 75 % | 94 / 96 % | 100 / 100 % | 80 / 89 % | 25 / 58 % | 74 / 85 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 53 / 71 % | 99 / 100 % | 98 / 99 % | 78 / 88 % | 52 / 71 % | 72 / 83 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 39 / 61 % | 63 / 92 % | 99 / 100 % | 64 / 82 % | 29 / 61 % | 65 / 81 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 24 / 47 % | 58 / 90 % | 96 / 98 % | 44 / 69 % | 18 / 47 % | 35 / 60 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 28 / 49 % | 77 / 98 % | 93 / 96 % | 63 / 81 % | 16 / 40 % | 60 / 79 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 16 / 38 % | 92 / 99 % | 65 / 81 % | 53 / 75 % | 28 / 50 % | 44 / 62 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 54 % | 60 / 84 % | 88 / 94 % | 36 / 65 % | 13 / 30 % | 53 / 75 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 52 / 87 % | 62 / 78 % | 18 / 42 % | 4 / 13 % | 21 / 43 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 62 / 95 % | 1 / 6 % | 6 / 15 % | 0 / 0 % | 6 / 14 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 61 / 90 % | 50 / 82 % | 12 / 38 % | 1 / 11 % | 11 / 27 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 17 / 43 % | 52 / 88 % | 33 / 63 % | 33 / 60 % | 12 / 33 % | 49 / 65 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 14 / 57 % | 50 / 62 % | 23 / 50 % | 1 / 5 % | 13 / 28 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 22 / 70 % | 39 / 57 % | 5 / 12 % | 1 / 4 % | 6 / 10 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 26 / 49 % | 38 / 74 % | 0 / 0 % | 21 / 49 % | 5 / 13 % | 20 / 36 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 33 / 57 % | 8 / 27 % | 2 / 8 % | 6 / 14 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 29 / 52 % | 4 / 14 % | 6 / 15 % | 1 / 4 % | 7 / 13 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 34 % | 29 / 88 % | 6 / 34 % | 17 / 42 % | 10 / 32 % | 21 / 46 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 24 / 58 % | 0 / 0 % | 12 / 36 % | 1 / 6 % | 9 / 19 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 23 / 58 % | 0 / 0 % | 6 / 15 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 18 / 95 % | 23 / 57 % | 5 / 19 % | 1 / 8 % | 5 / 12 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 45 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 10 / 77 % | 19 / 53 % | 11 / 38 % | 1 / 6 % | 15 / 36 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 17 / 42 % | 0 / 0 % | 0 / 0 % | 6 / 22 % | 1 / 3 % | 14 / 31 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 16 / 39 % | 12 / 46 % | 17 / 41 % | 11 / 34 % | 7 / 19 % | 11 / 23 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 17 / 62 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 10 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 8 / 36 % | 15 / 40 % | 1 / 6 % | 9 / 21 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 8 / 28 % | 14 / 36 % | 1 / 9 % | 10 / 23 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 13 / 62 % | 8 / 39 % | 5 / 11 % | 1 / 3 % | 8 / 16 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 13 / 48 % | 0 / 0 % | 0 / 0 % | 11 / 34 % | 2 / 7 % | 6 / 13 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 12 / 50 % | 6 / 19 % | 1 / 8 % | 6 / 14 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 11 / 21 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 10 / 15 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 10 / 15 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 56 % | 2 / 20 % | 8 / 26 % | 1 / 7 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 7 / 16 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 7 / 75 % | 0 / 0 % | 6 / 16 % | 2 / 9 % | 6 / 12 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 1 / 7 % | 6 / 12 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 10 % | 6 / 12 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 2 % | 4 / 7 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 2 / 7 % | 6 / 12 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 6 % | 0 / 0 % | – | – |
