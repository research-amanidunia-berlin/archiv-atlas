[English](README.md) · [Deutsch](README.de.md)

# Recommendations to OSTP for the US AI Action Plan

Bericht Q004548 · Quelle anthropic.com · Datum 2025-03-06 · [Original öffnen](https://www.anthropic.com/news/anthropic-s-recommendations-ostp-u-s-ai-action-plan)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic hat dem OSTP Vorschläge für den US-KI-Aktionsplan vorgelegt und erwartet leistungsfähige, zunehmend autonome KI-Systeme bereits Ende 2026 oder Anfang 2027. Die sechs Vorschlagsfelder reichen von Sicherheitsprüfungen, Exportkontrollen und Laborschutz über zusätzliche Energie und KI-Nutzung in Behörden bis zur Vorbereitung auf wirtschaftliche Folgen; der Beitrag gibt Anthropic-Einschätzungen wieder und berichtet nicht über eine Umsetzung durch die Regierung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 40 / 66 % | 31 / 73 % | – | 96 / 98 % | 39 / 65 % | 15 / 39 % | 40 / 67 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 55 / 70 % | 95 / 99 % | – | 86 / 94 % | 76 / 87 % | 51 / 66 % | 73 / 81 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 36 / 59 % | 93 / 98 % | – | 50 / 82 % | 47 / 70 % | 36 / 58 % | 59 / 76 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 59 / 81 % | – | 90 / 95 % | 24 / 47 % | 10 / 22 % | 14 / 32 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 17 / 37 % | 62 / 85 % | – | 71 / 80 % | 24 / 47 % | 20 / 39 % | 32 / 53 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 25 / 49 % | 55 / 88 % | – | 70 / 87 % | 30 / 57 % | 16 / 39 % | 34 / 61 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 20 / 45 % | 68 / 94 % | – | 62 / 75 % | 20 / 45 % | 9 / 29 % | 16 / 45 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 15 / 41 % | 31 / 75 % | – | 67 / 87 % | 27 / 52 % | 4 / 14 % | 14 / 34 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 13 / 40 % | 64 / 89 % | – | 20 / 50 % | 15 / 47 % | 11 / 30 % | 25 / 57 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 63 / 82 % | 8 / 24 % | 1 / 7 % | 6 / 13 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 12 / 35 % | 61 / 91 % | – | 19 / 44 % | 18 / 39 % | 8 / 20 % | 18 / 36 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 43 % | 39 / 86 % | – | 56 / 84 % | 16 / 44 % | 2 / 18 % | 14 / 32 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 21 / 42 % | 39 / 65 % | – | 21 / 63 % | 50 / 72 % | 31 / 52 % | 55 / 70 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 11 / 36 % | 44 / 77 % | – | 49 / 76 % | 23 / 49 % | 31 / 54 % | 53 / 73 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 47 % | 49 / 79 % | – | 36 / 64 % | 34 / 59 % | 19 / 41 % | 34 / 54 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 39 % | 48 / 96 % | – | 11 / 50 % | 19 / 50 % | 7 / 22 % | 19 / 47 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 15 / 32 % | 42 / 80 % | – | 41 / 71 % | 26 / 54 % | 12 / 31 % | 15 / 39 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 10 / 33 % | 42 / 74 % | – | 34 / 65 % | 12 / 32 % | 5 / 21 % | 10 / 38 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 8 / 38 % | 41 / 72 % | – | 6 / 28 % | 13 / 37 % | 7 / 21 % | 12 / 27 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 16 / 42 % | 36 / 84 % | – | 27 / 58 % | 13 / 34 % | 6 / 23 % | 14 / 34 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 34 % | 35 / 73 % | – | 2 / 26 % | 10 / 27 % | 4 / 15 % | 12 / 31 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 36 % | 26 / 79 % | – | 14 / 42 % | 8 / 26 % | 2 / 13 % | 6 / 21 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 13 / 38 % | 24 / 64 % | – | 17 / 53 % | 18 / 40 % | 9 / 22 % | 12 / 33 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 21 / 35 % | – | 1 / 4 % | 9 / 27 % | 2 / 9 % | 8 / 21 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 10 / 31 % | 19 / 58 % | – | 2 / 11 % | 9 / 22 % | 4 / 10 % | 9 / 19 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 2 / 34 % | – | 0 / 0 % | 8 / 26 % | 3 / 15 % | 17 / 38 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 13 / 22 % | – | 15 / 24 % | 10 / 22 % | 1 / 6 % | 9 / 26 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 40 % | 5 / 42 % | – | 1 / 7 % | 8 / 22 % | 1 / 9 % | 9 / 22 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 10 / 54 % | – | 7 / 26 % | 10 / 30 % | 6 / 19 % | 11 / 31 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 11 / 49 % | – | 0 / 0 % | 7 / 18 % | 1 / 5 % | 7 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 3 / 37 % | – | 10 / 35 % | 7 / 16 % | 1 / 5 % | 6 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 47 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % | 6 / 12 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 3 / 8 % | 9 / 17 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 25 % | 1 / 8 % | 6 / 14 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 9 % | 7 / 15 % | 3 / 10 % | 8 / 20 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 1 / 6 % | 4 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 2 / 9 % | 6 / 14 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 2 / 19 % | – | 0 / 0 % | 7 / 21 % | 0 / 7 % | 3 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 1 / 6 % | 5 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 5 / 62 % | – | 0 / 5 % | 7 / 18 % | 1 / 6 % | 7 / 17 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 4 % | 5 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 1 / 5 % | 4 / 9 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 1 / 5 % | 4 / 7 % |
