[English](README.md) · [Deutsch](README.de.md)

# Frontier model security

Bericht Q002638 · Quelle anthropic.com · Datum 2023-07-25 · [Original öffnen](https://www.anthropic.com/news/frontier-model-security)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic empfiehlt stärkere Sicherheitsvorkehrungen für Spitzenmodelle, darunter Zugangskontrollen mit Zustimmung zweier Personen, sichere Entwicklungsstandards und nachvollziehbare Herkunftsketten. Das Unternehmen spricht sich außerdem für staatliche Beschaffungsanforderungen und mehr Austausch zwischen KI-Laboren und Behörden aus; die Vorschläge werden als Empfehlungen dargestellt, nicht durch unabhängige Wirksamkeitsdaten belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 33 / 60 % | 51 / 94 % | 99 / 100 % | 69 / 85 % | 25 / 51 % | 54 / 76 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 49 / 68 % | 92 / 98 % | 97 / 99 % | 81 / 90 % | 73 / 85 % | 69 / 82 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 35 / 56 % | 96 / 98 % | 86 / 92 % | 56 / 77 % | 39 / 64 % | 55 / 77 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 35 / 56 % | 90 / 97 % | 86 / 93 % | 64 / 79 % | 43 / 59 % | 77 / 85 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 71 / 96 % | 74 / 90 % | 46 / 70 % | 20 / 40 % | 27 / 54 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 13 / 40 % | 64 / 96 % | 11 / 47 % | 20 / 45 % | 14 / 37 % | 38 / 63 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 16 / 46 % | 52 / 86 % | 49 / 74 % | 16 / 39 % | 9 / 25 % | 14 / 37 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 13 / 44 % | 47 / 94 % | 19 / 55 % | 13 / 37 % | 5 / 23 % | 13 / 37 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 16 / 35 % | 47 / 94 % | 45 / 73 % | 22 / 51 % | 10 / 26 % | 12 / 36 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 31 % | 47 / 96 % | 10 / 28 % | 9 / 28 % | 6 / 19 % | 8 / 25 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 17 / 50 % | 36 / 88 % | 40 / 80 % | 24 / 54 % | 21 / 46 % | 20 / 50 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 21 / 47 % | 34 / 92 % | 37 / 78 % | 36 / 63 % | 24 / 47 % | 39 / 66 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 38 / 85 % | 5 / 22 % | 11 / 25 % | 4 / 14 % | 8 / 18 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 9 / 22 % | 38 / 89 % | 14 / 37 % | 9 / 26 % | 4 / 15 % | 6 / 22 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 24 / 53 % | 37 / 93 % | 15 / 34 % | 14 / 47 % | 17 / 44 % | 18 / 59 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 15 / 41 % | 35 / 82 % | 9 / 22 % | 13 / 34 % | 11 / 26 % | 16 / 46 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 21 / 41 % | 34 / 83 % | 16 / 57 % | 23 / 48 % | 9 / 29 % | 19 / 39 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 7 / 46 % | 34 / 48 % | 7 / 17 % | 0 / 0 % | 5 / 11 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 11 / 38 % | 34 / 83 % | 6 / 31 % | 12 / 32 % | 7 / 21 % | 14 / 34 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 32 / 70 % | 32 / 49 % | 16 / 38 % | 12 / 23 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 31 / 67 % | 5 / 29 % | 10 / 26 % | 7 / 19 % | 14 / 25 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 35 % | 29 / 77 % | 2 / 14 % | 9 / 27 % | 4 / 14 % | 7 / 18 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 8 / 35 % | 27 / 86 % | 8 / 39 % | 9 / 29 % | 6 / 20 % | 7 / 21 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 22 / 69 % | 27 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 23 / 69 % | 1 / 19 % | 0 / 0 % | 5 / 12 % | 7 / 19 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 30 % | 20 / 61 % | 4 / 23 % | 6 / 17 % | 1 / 8 % | 4 / 9 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 20 / 92 % | 1 / 22 % | 7 / 22 % | 3 / 11 % | 7 / 18 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 19 / 77 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 4 / 9 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 19 / 73 % | 1 / 21 % | 10 / 32 % | 4 / 14 % | 18 / 38 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 6 / 47 % | 0 / 21 % | 10 / 28 % | 7 / 18 % | 18 / 36 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 16 / 84 % | 7 / 17 % | 7 / 16 % | 3 / 12 % | 8 / 18 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 16 / 56 % | 7 / 22 % | 9 / 21 % | 5 / 18 % | 10 / 23 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 14 / 43 % | 12 / 67 % | 8 / 47 % | 9 / 23 % | 7 / 25 % | 16 / 50 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 14 / 60 % | 0 / 0 % | 6 / 18 % | 5 / 11 % | 7 / 19 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 13 / 31 % | 3 / 51 % | 0 / 0 % | 6 / 18 % | 4 / 14 % | 5 / 19 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 89 % | 0 / 11 % | 11 / 30 % | 10 / 33 % | 12 / 25 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 8 / 46 % | 10 / 36 % | 11 / 31 % | 3 / 13 % | 6 / 25 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 10 / 86 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 6 / 22 % | 10 / 28 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 9 / 37 % | 0 / 0 % | 8 / 19 % | 4 / 11 % | 5 / 9 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 6 / 76 % | 1 / 8 % | 7 / 19 % | 3 / 10 % | 8 / 15 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 2 / 9 % | 7 / 23 % | – | – |
