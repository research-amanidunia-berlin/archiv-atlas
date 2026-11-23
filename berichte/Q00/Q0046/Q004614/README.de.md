[English](README.md) · [Deutsch](README.de.md)

# Autonomous Cyber Defense

Bericht Q004614 · Quelle cset.georgetown.edu · Datum 2023-06-21 · [Original öffnen](https://cset.georgetown.edu/publication/autonomous-cyber-defense/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug aus der Executive Summary beschreibt RL als führenden, aber noch unreifen Ansatz für autonome Cyberabwehr. Für den Einsatz seien unter anderem Anpassungsfähigkeit, menschliche Steuerbarkeit, Prüfbarkeit und Übertragbarkeit in reale Netzwerke erforderlich; die Autoren sehen das Ziel als langfristig und nicht garantiert an. Sie empfehlen anhaltende Finanzierung und bessere Trainings- und Bewertungsgrundlagen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 28 / 50 % | 91 / 99 % | 92 / 99 % | 63 / 83 % | 27 / 54 % | 40 / 64 % | 52 / 79 % | 31 / 61 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 78 / 95 % | 85 / 92 % | 10 / 31 % | 6 / 20 % | 10 / 44 % | 3 / 11 % | 19 / 42 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 29 / 46 % | 77 / 96 % | 76 / 88 % | 38 / 67 % | 22 / 49 % | 34 / 64 % | 13 / 33 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 34 / 54 % | 75 / 91 % | 69 / 84 % | 64 / 82 % | 54 / 73 % | 56 / 72 % | 43 / 52 % | 31 / 58 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 73 / 93 % | 0 / 0 % | 7 / 21 % | 7 / 20 % | 14 / 34 % | 2 / 8 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 22 / 75 % | 58 / 85 % | 11 / 34 % | 4 / 16 % | 8 / 29 % | 1 / 11 % | 4 / 19 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 33 / 94 % | 56 / 88 % | 17 / 50 % | 6 / 19 % | 16 / 42 % | 2 / 8 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 19 / 44 % | 54 / 95 % | 44 / 84 % | 16 / 40 % | 10 / 29 % | 26 / 56 % | 6 / 24 % | 18 / 45 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 44 / 85 % | 42 / 68 % | 13 / 41 % | 1 / 7 % | 10 / 27 % | 3 / 9 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 26 / 48 % | 43 / 78 % | 33 / 60 % | 17 / 49 % | 14 / 37 % | 19 / 51 % | 5 / 14 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 40 / 74 % | 17 / 45 % | 10 / 30 % | 9 / 24 % | 14 / 33 % | 0 / 0 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 39 / 74 % | 0 / 0 % | 8 / 20 % | 4 / 10 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 37 / 66 % | 6 / 13 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 35 / 83 % | 1 / 11 % | 8 / 24 % | 4 / 14 % | 9 / 23 % | 1 / 8 % | 8 / 27 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 33 / 74 % | 6 / 48 % | 13 / 35 % | 5 / 14 % | 11 / 28 % | 2 / 10 % | 6 / 19 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 29 / 90 % | 21 / 69 % | 13 / 37 % | 5 / 16 % | 6 / 21 % | 3 / 8 % | 6 / 23 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 29 % | 18 / 88 % | 12 / 42 % | 7 / 19 % | 2 / 11 % | 5 / 12 % | 0 / 2 % | 25 / 51 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 22 / 65 % | 0 / 0 % | 16 / 44 % | 4 / 14 % | 18 / 40 % | 1 / 6 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 22 / 45 % | 13 / 99 % | 6 / 69 % | 20 / 48 % | 6 / 24 % | 21 / 53 % | 8 / 47 % | 17 / 58 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 19 / 73 % | 0 / 13 % | 11 / 36 % | 1 / 8 % | 14 / 32 % | 3 / 10 % | 12 / 37 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 18 / 74 % | 0 / 0 % | 8 / 23 % | 4 / 14 % | 7 / 21 % | 1 / 5 % | 2 / 11 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 17 / 67 % | 0 / 0 % | 7 / 18 % | 1 / 3 % | 7 / 14 % | 0 / 2 % | 9 / 26 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 15 / 56 % | 8 / 28 % | 8 / 24 % | 1 / 7 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 14 / 84 % | 4 / 20 % | 10 / 30 % | 3 / 13 % | 6 / 16 % | 1 / 5 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 13 / 51 % | 4 / 22 % | 11 / 36 % | 2 / 11 % | 9 / 22 % | 2 / 9 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 8 / 74 % | 8 / 34 % | 10 / 35 % | 6 / 22 % | 12 / 32 % | 3 / 14 % | 10 / 32 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 41 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 53 % | 0 / 5 % | 6 / 20 % | 1 / 8 % | 8 / 18 % | 0 / 3 % | 2 / 13 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 1 / 6 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 0 / 3 % | 4 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 6 / 82 % | 5 / 18 % | 7 / 25 % | 2 / 10 % | 6 / 17 % | 0 / 3 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 5 % | 6 / 14 % | 0 / 2 % | 3 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 6 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 6 % | 5 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 7 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 5 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 2 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 8 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
