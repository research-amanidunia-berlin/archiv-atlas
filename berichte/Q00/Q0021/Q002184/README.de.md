[English](README.md) · [Deutsch](README.de.md)

# Responsible Scaling Policy Version 3.0

Bericht Q002184 · Quelle anthropic.com · Datum 2026-02-24 · [Original öffnen](https://www.anthropic.com/news/responsible-scaling-policy-v3)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic überarbeitet seine Responsible Scaling Policy, weil sie nach eigener Einschätzung zwar Schutzmaßnahmen und ähnliche Branchenrahmenwerke gefördert, aber keinen eindeutigen Konsens über Risiken geschaffen hat. Version 3.0 trennt eigene Vorhaben von Branchenempfehlungen und ergänzt öffentliche Sicherheitsziele, regelmäßige Risikoberichte sowie externe Prüfungen in bestimmten Fällen; die zugrunde liegenden Bewertungen und Tests bleiben teilweise uneindeutig.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 49 / 67 % | 86 / 92 % | – | 99 / 100 % | 75 / 88 % | 87 / 93 % | 87 / 95 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 63 % | 86 / 97 % | – | 99 / 100 % | 69 / 84 % | 80 / 90 % | 55 / 81 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 38 / 63 % | 95 / 97 % | – | 99 / 100 % | 78 / 87 % | 86 / 92 % | 76 / 88 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 47 / 68 % | 84 / 92 % | – | 95 / 99 % | 79 / 90 % | 82 / 90 % | 63 / 80 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 30 / 57 % | 55 / 91 % | – | 94 / 99 % | 61 / 82 % | 70 / 86 % | 36 / 64 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 16 / 36 % | 54 / 86 % | – | 87 / 96 % | 17 / 41 % | 10 / 22 % | 8 / 21 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 35 / 62 % | 85 / 97 % | – | 83 / 96 % | 66 / 83 % | 83 / 91 % | 75 / 88 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 38 / 59 % | 54 / 93 % | – | 67 / 90 % | 59 / 79 % | 80 / 90 % | 41 / 67 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 45 / 64 % | 79 / 91 % | – | 75 / 83 % | 66 / 81 % | 69 / 79 % | 70 / 81 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 24 / 46 % | 52 / 90 % | – | 74 / 93 % | 61 / 81 % | 28 / 60 % | 36 / 66 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 18 / 54 % | 47 / 79 % | – | 72 / 93 % | 25 / 53 % | 55 / 82 % | 38 / 71 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 25 / 53 % | 57 / 88 % | – | 41 / 66 % | 32 / 60 % | 68 / 82 % | 58 / 78 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 28 / 59 % | 67 / 99 % | – | 67 / 89 % | 38 / 63 % | 33 / 61 % | 19 / 47 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 16 / 32 % | 63 / 92 % | – | 65 / 87 % | 18 / 44 % | 17 / 51 % | 12 / 36 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 24 / 55 % | 51 / 77 % | – | 50 / 76 % | 48 / 71 % | 40 / 64 % | 60 / 79 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 50 / 83 % | – | 40 / 75 % | 26 / 57 % | 22 / 60 % | 6 / 28 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 29 % | 49 / 82 % | – | 28 / 54 % | 11 / 31 % | 9 / 25 % | 7 / 24 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 19 / 44 % | 24 / 63 % | – | 37 / 56 % | 36 / 65 % | 47 / 74 % | 18 / 48 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 42 % | 30 / 64 % | – | 42 / 71 % | 18 / 46 % | 22 / 55 % | 6 / 30 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 17 / 43 % | 38 / 70 % | – | 29 / 71 % | 18 / 40 % | 16 / 35 % | 8 / 30 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 41 % | 38 / 76 % | – | 7 / 36 % | 15 / 39 % | 21 / 46 % | 13 / 39 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 38 / 61 % | 8 / 19 % | 6 / 10 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 12 / 39 % | 36 / 76 % | – | 15 / 37 % | 17 / 40 % | 18 / 40 % | 16 / 40 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 35 / 63 % | – | 34 / 74 % | 15 / 34 % | 14 / 31 % | 4 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 38 % | 35 / 79 % | – | 18 / 58 % | 28 / 55 % | 11 / 37 % | 7 / 30 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 27 / 48 % | – | 34 / 55 % | 12 / 35 % | 13 / 22 % | 5 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 12 / 36 % | 28 / 78 % | – | 27 / 59 % | 13 / 34 % | 19 / 38 % | 8 / 27 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 41 % | 5 / 24 % | – | 0 / 0 % | 15 / 41 % | 27 / 50 % | 8 / 26 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 13 / 25 % | 26 / 59 % | – | 25 / 56 % | 14 / 37 % | 10 / 30 % | 2 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 46 % | 0 / 0 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 18 / 58 % | – | 0 / 0 % | 9 / 24 % | 10 / 25 % | 1 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 38 % | 17 / 60 % | – | 6 / 25 % | 7 / 22 % | 7 / 17 % | 4 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 16 / 59 % | – | 0 / 6 % | 8 / 19 % | 9 / 16 % | 2 / 10 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 9 / 52 % | – | 0 / 0 % | 16 / 42 % | 11 / 32 % | 8 / 20 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 15 / 81 % | – | 5 / 27 % | 11 / 31 % | 9 / 20 % | 2 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 22 % | 13 / 28 % | 3 / 10 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 8 / 16 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 7 / 51 % | – | 1 / 22 % | 8 / 21 % | 0 / 0 % | 3 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 7 / 11 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 7 / 44 % | – | 1 / 10 % | 8 / 24 % | 7 / 14 % | 4 / 11 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 7 / 13 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 7 / 16 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 12 % | 5 / 12 % |
