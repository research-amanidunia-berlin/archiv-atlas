[English](README.md) · [Deutsch](README.de.md)

# AI safety solutions mapping: An initiative for advanced AI governance

Bericht Q004721 · Quelle oecd.ai · Datum 2025-02-06 · [Original öffnen](https://oecd.ai/en/wonk/ai-safety-solutions-risk-mapping)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt GRASP als internationales Vorhaben vor, das acht Kategorien von KI-Risiken mit Sicherheitsmethoden, Forschungsempfehlungen und politischen Vorgaben verknüpfen soll. Er nennt Beispiele wie Audits, Red-Teaming und Überwachung, beschreibt eine geplante laufende Aktualisierung und führt mögliche Wirkungen auf Politik und Investitionen an, belegt diese Zukunftserwartungen aber nicht mit konkreten Ergebnissen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 36 / 63 % | 61 / 96 % | 25 / 68 % | 86 / 98 % | 56 / 79 % | 26 / 59 % | 52 / 80 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 11 / 27 % | 29 / 75 % | 1 / 6 % | 86 / 96 % | 11 / 30 % | 2 / 12 % | 7 / 23 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 32 / 62 % | 37 / 94 % | 26 / 68 % | 83 / 97 % | 57 / 80 % | 29 / 61 % | 49 / 79 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 33 / 56 % | 79 / 96 % | 40 / 55 % | 57 / 76 % | 49 / 72 % | 32 / 56 % | 46 / 64 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 17 / 47 % | 39 / 85 % | 19 / 52 % | 74 / 95 % | 24 / 49 % | 25 / 53 % | 52 / 76 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 18 / 46 % | 66 / 95 % | 14 / 41 % | 18 / 52 % | 24 / 50 % | 19 / 44 % | 41 / 67 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 30 / 62 % | 46 / 86 % | 10 / 43 % | 61 / 88 % | 31 / 58 % | 14 / 43 % | 26 / 60 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 10 / 34 % | 46 / 85 % | 11 / 30 % | 54 / 78 % | 27 / 53 % | 9 / 32 % | 17 / 43 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 42 % | 46 / 80 % | 1 / 9 % | 19 / 55 % | 17 / 43 % | 5 / 27 % | 10 / 33 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 12 / 35 % | 45 / 86 % | 1 / 11 % | 13 / 41 % | 12 / 33 % | 6 / 19 % | 13 / 44 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 21 / 47 % | 43 / 90 % | 13 / 47 % | 42 / 82 % | 28 / 61 % | 17 / 48 % | 35 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 16 / 44 % | 11 / 73 % | 6 / 19 % | 13 / 40 % | 32 / 62 % | 11 / 38 % | 37 / 67 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 13 / 33 % | 32 / 87 % | 6 / 33 % | 14 / 63 % | 30 / 58 % | 12 / 36 % | 34 / 66 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 34 / 82 % | 1 / 11 % | 15 / 65 % | 11 / 28 % | 7 / 27 % | 9 / 45 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 39 % | 33 / 88 % | 7 / 28 % | 19 / 69 % | 23 / 53 % | 9 / 35 % | 18 / 51 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 20 / 50 % | 23 / 91 % | 7 / 20 % | 23 / 71 % | 26 / 55 % | 11 / 37 % | 23 / 63 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 24 / 83 % | 1 / 7 % | 0 / 0 % | 9 / 23 % | 5 / 17 % | 6 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 23 / 84 % | 3 / 15 % | 5 / 32 % | 21 / 47 % | 8 / 29 % | 8 / 27 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 12 / 46 % | 19 / 87 % | 4 / 20 % | 16 / 63 % | 16 / 44 % | 9 / 26 % | 11 / 34 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 36 % | 11 / 92 % | 1 / 8 % | 19 / 47 % | 10 / 31 % | 7 / 24 % | 9 / 31 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 18 / 79 % | 0 / 5 % | 5 / 39 % | 9 / 24 % | 1 / 5 % | 9 / 22 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 18 / 63 % | 1 / 5 % | 1 / 15 % | 9 / 25 % | 1 / 9 % | 9 / 27 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 16 / 54 % | 1 / 6 % | 3 / 27 % | 9 / 27 % | 1 / 9 % | 6 / 29 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 8 / 90 % | 3 / 17 % | 6 / 39 % | 15 / 38 % | 7 / 25 % | 9 / 34 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 9 / 27 % | 14 / 58 % | 0 / 3 % | 1 / 20 % | 9 / 19 % | 3 / 11 % | 8 / 25 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 14 / 44 % | 1 / 8 % | 0 / 0 % | 10 / 30 % | 2 / 15 % | 8 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 14 / 53 % | 0 / 2 % | 8 / 33 % | 8 / 23 % | 2 / 8 % | 6 / 12 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 6 / 57 % | 1 / 10 % | 10 / 33 % | 12 / 28 % | 3 / 18 % | 13 / 33 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 11 / 29 % | 4 / 61 % | 1 / 8 % | 0 / 0 % | 9 / 22 % | 3 / 16 % | 12 / 36 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 4 / 26 % | 12 / 73 % | 2 / 12 % | 5 / 32 % | 9 / 28 % | 5 / 22 % | 8 / 27 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 33 % | 2 / 8 % | 6 / 14 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 2 / 55 % | 1 / 8 % | 1 / 11 % | 10 / 29 % | 4 / 16 % | 8 / 21 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 6 / 43 % | 0 / 4 % | 2 / 10 % | 8 / 25 % | 3 / 12 % | 10 / 25 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 33 % | 1 / 51 % | 0 / 4 % | 0 / 4 % | 9 / 20 % | 2 / 8 % | 6 / 15 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 6 / 40 % | 0 / 3 % | 0 / 2 % | 7 / 17 % | 2 / 10 % | 8 / 16 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 8 / 31 % | 0 / 1 % | 0 / 0 % | 7 / 16 % | 3 / 13 % | 6 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 7 / 14 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 2 % | 7 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 7 / 24 % | 3 / 28 % | 0 / 2 % | 1 / 11 % | 6 / 14 % | 3 / 11 % | 5 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 5 / 47 % | 0 / 4 % | 1 / 17 % | 7 / 18 % | 1 / 10 % | 6 / 23 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 7 / 42 % | 0 / 1 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 6 / 13 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 1 / 15 % | 0 / 2 % | 0 / 0 % | 6 / 13 % | 2 / 8 % | 4 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 6 / 67 % | 0 / 2 % | 0 / 3 % | 6 / 14 % | 1 / 4 % | 5 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 8 % | 6 / 15 % | 2 / 8 % | 6 / 17 % |
