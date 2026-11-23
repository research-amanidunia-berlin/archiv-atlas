[English](README.md) · [Deutsch](README.de.md)

# Introducing Mistral Large 4

Bericht Q000848 · Quelle mistral.ai · Datum 2026-10-06 · [Original öffnen](https://mistral.ai/news/mistral-large-4/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Mistral kündigt ML4 als großes multimodales Modell mit starken, vom Unternehmen berichteten Ergebnissen für Programmierung, Cybersicherheit, Bildverständnis und professionelle Aufgaben an. Die Vorschau ist verfügbar, die Gewichte sollen später folgen; Architektur und weitere Evaluationsdetails stehen laut Bericht noch aus.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 58 / 71 % | 98 / 99 % | 99 / 100 % | 59 / 71 % | 54 / 69 % | 82 / 89 % | 85 / 92 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 30 / 49 % | 87 / 98 % | 98 / 99 % | 41 / 67 % | 14 / 32 % | 27 / 53 % | 13 / 30 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 81 / 96 % | 96 / 97 % | 72 / 86 % | 27 / 45 % | 71 / 84 % | 22 / 39 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 47 % | 87 / 98 % | 96 / 98 % | 57 / 77 % | 13 / 31 % | 46 / 72 % | 18 / 43 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 34 / 57 % | 94 / 99 % | 89 / 96 % | 51 / 71 % | 21 / 41 % | 49 / 64 % | 38 / 60 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 34 / 52 % | 64 / 94 % | 93 / 96 % | 54 / 77 % | 27 / 46 % | 73 / 87 % | 41 / 57 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 38 % | 92 / 99 % | 78 / 86 % | 19 / 45 % | 1 / 7 % | 15 / 37 % | 3 / 13 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 92 / 99 % | 89 / 96 % | 35 / 64 % | 9 / 25 % | 35 / 57 % | 6 / 16 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 28 / 90 % | 90 / 95 % | 50 / 71 % | 9 / 20 % | 10 / 29 % | 5 / 12 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 31 / 50 % | 88 / 99 % | 90 / 93 % | 56 / 77 % | 20 / 37 % | 40 / 70 % | 18 / 33 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 28 / 56 % | 82 / 97 % | 75 / 90 % | 44 / 69 % | 6 / 15 % | 41 / 59 % | 10 / 20 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 52 / 84 % | 81 / 87 % | 24 / 47 % | 6 / 11 % | 25 / 44 % | 6 / 13 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 52 / 86 % | 76 / 87 % | 10 / 30 % | 2 / 8 % | 8 / 24 % | 1 / 4 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 56 / 87 % | 67 / 87 % | 38 / 61 % | 7 / 19 % | 22 / 44 % | 4 / 15 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 24 / 61 % | 66 / 82 % | 6 / 14 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 63 / 78 % | 11 / 30 % | 1 / 3 % | 5 / 13 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 26 / 72 % | 58 / 73 % | 34 / 58 % | 6 / 14 % | 22 / 41 % | 5 / 14 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 45 % | 44 / 81 % | 49 / 64 % | 40 / 63 % | 5 / 10 % | 24 / 43 % | 8 / 15 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 47 / 66 % | 11 / 32 % | 3 / 10 % | 7 / 21 % | 1 / 6 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 33 % | 38 / 84 % | 0 / 0 % | 16 / 38 % | 6 / 17 % | 14 / 31 % | 2 / 6 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 6 / 41 % | 37 / 49 % | 16 / 40 % | 7 / 14 % | 26 / 48 % | 7 / 13 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 34 / 80 % | 0 / 0 % | 21 / 49 % | 4 / 10 % | 9 / 29 % | 1 / 4 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 33 / 66 % | 2 / 8 % | 15 / 34 % | 3 / 10 % | 9 / 21 % | 1 / 4 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 26 / 79 % | 10 / 45 % | 25 / 49 % | 6 / 14 % | 9 / 26 % | 3 / 11 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 22 / 71 % | 11 / 33 % | 9 / 23 % | 2 / 5 % | 7 / 15 % | 0 / 2 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 15 / 33 % | 12 / 34 % | 2 / 8 % | 10 / 22 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 2 / 41 % | 14 / 28 % | 9 / 24 % | 2 / 9 % | 6 / 16 % | 0 / 2 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 13 / 35 % | 0 / 0 % | 0 / 0 % | 11 / 32 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 8 / 50 % | 10 / 24 % | 11 / 28 % | 3 / 9 % | 6 / 15 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 2 % | 5 / 10 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 25 % | 0 / 2 % | 5 / 16 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 2 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 0 / 1 % | 5 / 15 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 2 / 5 % | 5 / 15 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 7 / 14 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 14 % | 0 / 0 % | 6 / 11 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 1 % | 2 / 5 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 2 / 5 % | 0 / 0 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 2 / 13 % | 0 / 0 % | 3 / 7 % | 0 / 0 % | 0 / 0 % | – |
