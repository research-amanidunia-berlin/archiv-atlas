[English](README.md) · [Deutsch](README.de.md)

# Frontier Safety Roadmap

Bericht Q005358 · Quelle anthropic.com · Datum 2026-04-02 · [Original öffnen](https://www.anthropic.com/responsible-scaling-policy/roadmap)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic beschreibt Sicherheitsziele für interne Systeme, Schutz vor gefährlicher Modellnutzung, Ausrichtung und politische Maßnahmen und berichtet über Fortschritte bei automatisiertem Red-Teaming sowie Sicherheitsprototypen. Zugleich wurden Ziele verschoben oder eingestellt; das Unternehmen nennt Grenzen seiner Schutzgarantien und hält eine starke KI-Beschleunigung sicherheitsrelevanter Forschung ab Anfang 2027 für plausibel.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 50 / 68 % | 93 / 97 % | 100 / 100 % | 81 / 90 % | 69 / 87 % | 83 / 92 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 40 / 60 % | 97 / 99 % | 99 / 100 % | 84 / 92 % | 44 / 65 % | 78 / 87 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 40 / 62 % | 99 / 100 % | 99 / 100 % | 72 / 86 % | 72 / 87 % | 87 / 93 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 26 / 53 % | 83 / 94 % | 93 / 97 % | 45 / 68 % | 24 / 50 % | 67 / 81 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 36 / 61 % | 52 / 85 % | 91 / 97 % | 52 / 75 % | 17 / 44 % | 41 / 68 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 53 / 68 % | 90 / 96 % | 40 / 70 % | 70 / 85 % | 82 / 90 % | 87 / 91 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 46 / 68 % | 77 / 98 % | 86 / 92 % | 82 / 90 % | 78 / 90 % | 90 / 95 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 25 / 56 % | 85 / 98 % | 51 / 77 % | 57 / 78 % | 23 / 54 % | 72 / 85 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 34 / 54 % | 50 / 80 % | 85 / 93 % | 59 / 80 % | 21 / 51 % | 52 / 70 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 33 / 58 % | 79 / 97 % | 85 / 96 % | 65 / 84 % | 36 / 65 % | 56 / 85 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 24 / 50 % | 58 / 87 % | 85 / 93 % | 24 / 50 % | 12 / 36 % | 17 / 42 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 23 / 54 % | 77 / 92 % | 78 / 93 % | 47 / 72 % | 35 / 64 % | 76 / 87 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 76 / 96 % | 8 / 33 % | 15 / 37 % | 7 / 23 % | 17 / 41 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 23 / 51 % | 55 / 85 % | 75 / 91 % | 22 / 48 % | 16 / 46 % | 45 / 70 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 34 / 55 % | 61 / 84 % | 73 / 83 % | 33 / 59 % | 8 / 21 % | 22 / 35 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 23 / 51 % | 55 / 85 % | 70 / 87 % | 46 / 69 % | 15 / 44 % | 32 / 60 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 70 / 91 % | 52 / 78 % | 15 / 39 % | 7 / 24 % | 17 / 47 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 69 / 81 % | 0 / 0 % | 43 / 65 % | 5 / 15 % | 30 / 46 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 32 / 57 % | 53 / 80 % | 60 / 78 % | 68 / 84 % | 25 / 64 % | 54 / 71 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 17 / 43 % | 34 / 86 % | 63 / 80 % | 31 / 58 % | 7 / 31 % | 15 / 41 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 23 / 53 % | 53 / 87 % | 58 / 74 % | 23 / 52 % | 8 / 28 % | 50 / 73 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 17 / 33 % | 45 / 77 % | 56 / 77 % | 21 / 49 % | 4 / 12 % | 13 / 32 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 53 / 89 % | 34 / 73 % | 26 / 54 % | 2 / 10 % | 20 / 42 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 28 % | 51 / 89 % | 22 / 58 % | 25 / 51 % | 8 / 30 % | 9 / 36 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 20 / 45 % | 39 / 83 % | 51 / 77 % | 30 / 55 % | 11 / 36 % | 21 / 48 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 40 / 78 % | 43 / 65 % | 44 / 68 % | 10 / 36 % | 22 / 42 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 8 / 26 % | 40 / 84 % | 33 / 51 % | 9 / 27 % | 4 / 15 % | 7 / 18 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 36 / 66 % | 35 / 56 % | 11 / 32 % | 2 / 9 % | 8 / 15 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 35 / 88 % | 29 / 62 % | 13 / 32 % | 5 / 16 % | 11 / 23 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 15 / 42 % | 32 / 62 % | 18 / 34 % | 18 / 41 % | 5 / 16 % | 22 / 37 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 29 / 76 % | 2 / 19 % | 10 / 31 % | 2 / 9 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 17 / 39 % | 2 / 18 % | 20 / 42 % | 5 / 13 % | 15 / 29 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 19 / 71 % | 0 / 6 % | 10 / 24 % | 3 / 9 % | 7 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 12 / 21 % | 0 / 0 % | 15 / 38 % | 13 / 41 % | 2 / 10 % | 13 / 39 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 5 / 53 % | 14 / 40 % | 13 / 35 % | 4 / 17 % | 13 / 43 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 37 % | 5 / 20 % | 9 / 27 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 5 / 33 % | 0 / 0 % | 8 / 22 % | 3 / 9 % | 11 / 24 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 2 / 7 % | 0 / 0 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 5 / 59 % | 0 / 0 % | 7 / 21 % | 0 / 0 % | 8 / 17 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 5 / 46 % | 0 / 0 % | 8 / 17 % | 1 / 4 % | 5 / 12 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 7 / 20 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 8 / 41 % | 0 / 0 % | 7 / 20 % | 2 / 6 % | 7 / 18 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 8 / 54 % | 0 / 0 % | 7 / 18 % | 1 / 5 % | 4 / 8 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 8 % | 5 / 14 % | – | – |
