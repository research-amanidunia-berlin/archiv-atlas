[English](README.md) · [Deutsch](README.de.md)

# Measurements for understanding the pace of AI development inside frontier labs

Bericht Q005392 · Quelle anthropic.com · Datum – · [Original öffnen](https://www.anthropic.com/institute/measuring-pace-of-ai-development)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic schlägt Messgrößen für den KI-Einsatz in der KI-Forschung, die Aufsicht über Agenten und die Verteilung von Rechenleistung vor. Das Unternehmen berichtet unter anderem, Claude habe im August 2026 26 Prozent der erfassten Forschungsaufgaben angeführt und etwa sechs Prozent der KI-Forschungs-Rechenleistung seien in einer untersuchten Woche Sicherheitsarbeit gewesen. Die Zahlen sind laut Bericht vorläufig und eingeschränkt: Sie beruhen teilweise auf modellgestützten Bewertungen, umfassen bei Agenten nur eine Plattform und belegen bei der Rechenleistung keinen längerfristigen Trend.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 57 / 74 % | 100 / 100 % | – | 96 / 99 % | 89 / 94 % | 92 / 96 % | 96 / 97 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 85 / 91 % | 100 / 100 % | – | 100 / 100 % | 93 / 95 % | 97 / 98 % | 96 / 97 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 63 / 78 % | 97 / 98 % | – | 100 / 100 % | 87 / 93 % | 90 / 95 % | 95 / 97 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 53 / 73 % | 97 / 100 % | – | 99 / 100 % | 84 / 91 % | 55 / 74 % | 81 / 89 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 36 / 60 % | 96 / 100 % | – | 99 / 100 % | 71 / 86 % | 42 / 68 % | 74 / 87 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 36 / 62 % | 98 / 100 % | – | 87 / 96 % | 68 / 84 % | 59 / 74 % | 84 / 93 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 42 / 64 % | 96 / 99 % | – | 97 / 99 % | 48 / 65 % | 72 / 85 % | 80 / 90 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 61 % | 82 / 99 % | – | 96 / 98 % | 62 / 81 % | 22 / 56 % | 66 / 85 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 35 / 58 % | 93 / 99 % | – | 89 / 93 % | 64 / 80 % | 49 / 69 % | 81 / 91 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 16 / 40 % | 28 / 86 % | – | 91 / 97 % | 26 / 54 % | 11 / 33 % | 17 / 44 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 44 / 68 % | 80 / 99 % | – | 41 / 70 % | 80 / 89 % | 72 / 85 % | 90 / 94 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 41 / 66 % | 79 / 98 % | – | 78 / 88 % | 72 / 85 % | 76 / 86 % | 87 / 92 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 18 / 39 % | 75 / 95 % | – | 83 / 95 % | 35 / 64 % | 17 / 46 % | 55 / 74 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 29 / 53 % | 41 / 89 % | – | 69 / 82 % | 69 / 83 % | 54 / 72 % | 78 / 86 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 12 / 36 % | 39 / 87 % | – | 75 / 94 % | 20 / 46 % | 10 / 29 % | 15 / 36 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 22 / 43 % | 49 / 94 % | – | 71 / 87 % | 29 / 54 % | 9 / 25 % | 17 / 37 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 22 / 46 % | 47 / 95 % | – | 69 / 89 % | 28 / 59 % | 8 / 24 % | 17 / 47 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 23 / 44 % | 43 / 80 % | – | 25 / 67 % | 44 / 68 % | 12 / 29 % | 53 / 72 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 10 / 74 % | – | 47 / 68 % | 7 / 17 % | 1 / 5 % | 7 / 11 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 32 / 55 % | 17 / 90 % | – | 41 / 73 % | 41 / 67 % | 16 / 38 % | 23 / 50 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 17 / 29 % | 18 / 79 % | – | 40 / 70 % | 22 / 48 % | 6 / 17 % | 16 / 37 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 37 / 96 % | – | 15 / 41 % | 19 / 43 % | 6 / 23 % | 18 / 31 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 19 / 47 % | 0 / 0 % | – | 25 / 46 % | 36 / 64 % | 13 / 35 % | 26 / 60 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 15 / 98 % | – | 30 / 64 % | 9 / 25 % | 6 / 18 % | 9 / 27 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 31 % | 29 / 76 % | – | 4 / 26 % | 12 / 30 % | 7 / 21 % | 11 / 25 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 23 / 52 % | 6 / 91 % | – | 20 / 61 % | 18 / 44 % | 14 / 37 % | 25 / 57 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 22 / 76 % | – | 0 / 0 % | 19 / 46 % | 0 / 0 % | 16 / 32 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 4 / 78 % | – | 19 / 44 % | 10 / 25 % | 6 / 19 % | 11 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 11 / 50 % | – | 17 / 52 % | 8 / 18 % | 2 / 8 % | 13 / 25 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 17 / 41 % | 8 / 20 % | 13 / 34 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 11 / 92 % | – | 3 / 27 % | 14 / 37 % | 5 / 16 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 30 % | 4 / 11 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 9 / 91 % | – | 0 / 0 % | 7 / 21 % | 1 / 4 % | 11 / 21 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 1 / 6 % | 11 / 23 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 7 / 87 % | – | 0 / 0 % | 10 / 24 % | 4 / 11 % | 6 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 68 % | – | 0 / 0 % | 6 / 11 % | 0 / 0 % | 6 / 11 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 16 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 6 / 47 % | – | 0 / 0 % | 7 / 15 % | 2 / 6 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 2 / 49 % | – | 0 / 0 % | 7 / 16 % | 2 / 7 % | 5 / 10 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 6 / 49 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 10 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 8 % |
