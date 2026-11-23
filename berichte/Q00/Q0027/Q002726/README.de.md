[English](README.md) · [Deutsch](README.de.md)

# The Rogue Replication Threat Model

Bericht Q002726 · Quelle metr.org · Datum 2024-11-12 · [Original öffnen](https://metr.org/blog/2024-11-12-rogue-replication-threat-model/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

METR skizziert, wie unkontrollierte KI-Agenten Modelle verbreiten, Ressourcen erwerben, wachsen und Abschaltungen erschweren könnten, betont aber, dass dies ein Bedrohungsszenario und kein Nachweis aktueller Fähigkeiten ist. Die vorgeschlagenen Prüfungen sollen solche Fähigkeiten greifbar machen; METR sieht ein Scheitern als aussagekräftiger für Entwarnung als ein Bestehen als Beleg für Gefahr und stuft das Thema zugunsten allgemeiner Autonomie zurück.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 50 / 72 % | 98 / 100 % | 96 / 98 % | 60 / 74 % | 33 / 59 % | 67 / 79 % | 41 / 73 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 49 / 70 % | 92 / 99 % | 96 / 98 % | 82 / 90 % | 49 / 69 % | 78 / 86 % | 54 / 77 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 40 / 62 % | 93 / 99 % | 85 / 91 % | 85 / 93 % | 40 / 64 % | 67 / 79 % | 48 / 73 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 52 % | 82 / 96 % | 92 / 98 % | 45 / 72 % | 21 / 49 % | 41 / 63 % | 8 / 33 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 29 / 58 % | 73 / 94 % | 90 / 96 % | 70 / 84 % | 17 / 44 % | 65 / 77 % | 40 / 75 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 32 / 62 % | 62 / 89 % | 87 / 95 % | 59 / 80 % | 34 / 58 % | 66 / 78 % | 11 / 36 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 35 % | 0 / 0 % | 81 / 92 % | 38 / 65 % | 6 / 17 % | 13 / 31 % | 6 / 20 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 74 / 95 % | 57 / 73 % | 12 / 32 % | 3 / 7 % | 17 / 31 % | 1 / 5 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 37 / 59 % | 56 / 89 % | 51 / 78 % | 67 / 83 % | 37 / 64 % | 63 / 77 % | 41 / 61 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 22 / 49 % | 64 / 92 % | 43 / 77 % | 39 / 63 % | 12 / 27 % | 28 / 42 % | 9 / 26 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 28 / 50 % | 25 / 72 % | 42 / 69 % | 61 / 79 % | 24 / 51 % | 38 / 57 % | 6 / 22 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 34 / 58 % | 60 / 90 % | 45 / 64 % | 25 / 57 % | 25 / 46 % | 45 / 67 % | 7 / 24 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 28 / 54 % | 51 / 95 % | 60 / 87 % | 45 / 73 % | 13 / 31 % | 33 / 59 % | 4 / 14 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 27 / 70 % | 0 / 0 % | 56 / 62 % | 15 / 38 % | 7 / 20 % | 26 / 46 % | 1 / 5 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 22 / 41 % | 45 / 68 % | 40 / 69 % | 47 / 70 % | 10 / 25 % | 38 / 57 % | 4 / 16 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 37 / 77 % | 43 / 71 % | 9 / 22 % | 1 / 5 % | 6 / 14 % | 0 / 3 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 16 / 45 % | 37 / 87 % | 40 / 75 % | 30 / 58 % | 7 / 19 % | 13 / 28 % | 5 / 25 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 39 / 67 % | 0 / 0 % | 10 / 30 % | 1 / 3 % | 8 / 19 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 20 / 57 % | 35 / 54 % | 10 / 28 % | 2 / 6 % | 9 / 16 % | 0 / 2 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 32 / 85 % | 5 / 13 % | 19 / 41 % | 5 / 14 % | 0 / 0 % | 1 / 3 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 31 / 68 % | 11 / 29 % | 22 / 45 % | 0 / 0 % | 10 / 22 % | 1 / 4 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 16 / 46 % | 0 / 0 % | 0 / 0 % | 31 / 61 % | 9 / 18 % | 28 / 50 % | 1 / 6 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 31 / 76 % | 4 / 14 % | 9 / 23 % | 3 / 11 % | 8 / 17 % | 0 / 3 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 13 / 44 % | 27 / 66 % | 0 / 0 % | 19 / 45 % | 4 / 12 % | 14 / 25 % | 1 / 6 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 24 / 81 % | 15 / 32 % | 14 / 40 % | 2 / 7 % | 12 / 24 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 20 / 84 % | 0 / 0 % | 7 / 20 % | 2 / 7 % | 0 / 0 % | 0 / 1 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 19 / 46 % | 15 / 33 % | 9 / 24 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 14 / 49 % | 0 / 0 % | 8 / 23 % | 1 / 3 % | 10 / 23 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 2 / 6 % | 13 / 26 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 25 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 5 % | 11 / 22 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 31 % | 0 / 0 % | 10 / 27 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 9 / 50 % | 0 / 0 % | 8 / 21 % | 2 / 6 % | 10 / 21 % | 0 / 3 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 10 / 20 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 9 / 66 % | 9 / 31 % | 8 / 26 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
