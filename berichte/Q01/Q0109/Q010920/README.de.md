[English](README.md) · [Deutsch](README.de.md)

# The Dark Side of Anthropic’s Growth

Bericht Q010920 · Quelle medium.com · Datum 2026-05-21 · [Original öffnen](https://medium.com/ai-in-plain-english/the-dark-side-of-anthropics-growth-573b9dec742f)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag beschreibt, wie Anthropics starkes Wachstum mit seinem Sicherheitsanspruch kollidiert: Laut Autor wurde die verbindliche Zusage, bei nicht nachweisbarer Sicherheit ein Modelltraining auszusetzen, 2026 aufgeweicht; zugleich bestünden enge finanzielle und infrastrukturelle Verbindungen zu Amazon und Google. Er würdigt Anthropics Widerstand gegen bestimmte Pentagon-Nutzungen und seine Sicherheitsforschung, kritisiert aber Lücken bei Energieauswirkungen und Arbeitsmarktfolgen und plädiert für Regeln, die Sicherheitszusagen unter kommerziellem Druck absichern.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 97 / 99 % | 1 / 6 % | 99 / 100 % | 11 / 38 % | 6 / 20 % | 5 / 16 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 42 / 65 % | 96 / 99 % | 32 / 63 % | 99 / 100 % | 54 / 76 % | 45 / 69 % | 22 / 43 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 50 % | 97 / 99 % | 24 / 54 % | 92 / 98 % | 46 / 73 % | 50 / 73 % | 24 / 47 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 38 / 61 % | 95 / 99 % | 48 / 70 % | 70 / 91 % | 59 / 80 % | 51 / 68 % | 52 / 68 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 30 / 51 % | 88 / 97 % | 41 / 61 % | 92 / 97 % | 57 / 77 % | 48 / 63 % | 49 / 67 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 47 % | 90 / 98 % | 8 / 23 % | 87 / 95 % | 23 / 49 % | 30 / 54 % | 8 / 22 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 32 / 62 % | 74 / 96 % | 9 / 26 % | 87 / 93 % | 34 / 61 % | 34 / 56 % | 17 / 36 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 24 / 49 % | 57 / 92 % | 12 / 26 % | 87 / 95 % | 28 / 55 % | 30 / 47 % | 9 / 18 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 63 / 93 % | 1 / 6 % | 85 / 89 % | 19 / 47 % | 20 / 34 % | 10 / 23 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 32 / 51 % | 82 / 94 % | 10 / 28 % | 82 / 91 % | 25 / 59 % | 31 / 58 % | 17 / 40 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 25 / 46 % | 79 / 95 % | 9 / 32 % | 76 / 91 % | 33 / 62 % | 32 / 59 % | 11 / 31 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 16 / 41 % | 29 / 77 % | 10 / 29 % | 77 / 90 % | 36 / 65 % | 21 / 55 % | 10 / 29 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 68 / 79 % | 5 / 8 % | 29 / 42 % | 15 / 35 % | 18 / 30 % | 7 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 8 / 25 % | 59 / 97 % | 1 / 4 % | 41 / 70 % | 10 / 31 % | 10 / 24 % | 5 / 16 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 19 / 40 % | 51 / 88 % | 5 / 19 % | 44 / 67 % | 25 / 52 % | 21 / 44 % | 8 / 25 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 16 / 29 % | 36 / 76 % | 0 / 0 % | 50 / 61 % | 10 / 27 % | 8 / 24 % | 3 / 8 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 39 % | 42 / 96 % | 0 / 3 % | 12 / 29 % | 7 / 24 % | 6 / 15 % | 4 / 13 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 32 / 81 % | 0 / 2 % | 0 / 0 % | 6 / 14 % | 5 / 10 % | 2 / 7 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 30 / 84 % | 0 / 0 % | 15 / 38 % | 7 / 20 % | 6 / 10 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 27 / 64 % | 1 / 8 % | 3 / 14 % | 9 / 26 % | 8 / 20 % | 4 / 15 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 26 / 50 % | 16 / 47 % | 4 / 11 % | 12 / 39 % | 10 / 24 % | 12 / 21 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 25 / 71 % | 0 / 2 % | 10 / 32 % | 6 / 12 % | 7 / 16 % | 4 / 11 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 19 / 76 % | 1 / 4 % | 22 / 38 % | 12 / 32 % | 7 / 15 % | 3 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 21 / 49 % | 16 / 52 % | 1 / 5 % | 0 / 0 % | 11 / 34 % | 9 / 20 % | 2 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 10 / 38 % | 1 / 5 % | 6 / 26 % | 21 / 45 % | 7 / 16 % | 5 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 13 / 84 % | 2 / 5 % | 20 / 55 % | 12 / 32 % | 14 / 27 % | 4 / 14 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 45 % | 0 / 0 % | 1 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 10 / 40 % | 19 / 76 % | 2 / 10 % | 6 / 22 % | 13 / 40 % | 9 / 20 % | 4 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 16 / 45 % | 3 / 11 % | 0 / 0 % | 17 / 44 % | 12 / 29 % | 4 / 13 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 17 / 49 % | 1 / 4 % | 0 / 0 % | 9 / 23 % | 8 / 16 % | 4 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 15 / 53 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 5 / 9 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 11 / 29 % | 7 / 19 % | 2 / 10 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 10 / 18 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 80 % | 0 / 3 % | 1 / 10 % | 8 / 22 % | 9 / 17 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 8 / 82 % | 2 / 9 % | 8 / 25 % | 9 / 27 % | 8 / 18 % | 3 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 9 / 64 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 5 / 9 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 5 / 11 % | 2 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 6 / 10 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 48 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 9 % | 0 / 0 % |
