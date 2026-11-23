[English](README.md) · [Deutsch](README.de.md)

# AI Behind Closed Doors: a Primer on The Governance of Internal Deployment

Bericht Q001475 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/governance/ai-behind-closed-doors-a-primer-on-the-governance-of-internal-deployment)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht warnt vor Risiken, wenn hochentwickelte KI-Systeme zunächst nur intern eingesetzt werden: schwächere Schutzvorkehrungen könnten Kontrollverlust oder eine schwer beobachtbare Konzentration von Macht begünstigen. Apollo Research schlägt dafür abgestufte Zugangsregeln, Prüfungen und Aufsicht, gezielte Transparenz sowie Notfallpläne vor; die beschriebenen Gefahren sind Szenarien, und die rechtliche Erfassung interner Nutzung hängt teils von der Auslegung ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 60 % | 100 / 100 % | – | 69 / 85 % | 65 / 84 % | 66 / 84 % | 42 / 76 % | 53 / 76 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 52 / 74 % | 98 / 100 % | – | 73 / 87 % | 74 / 87 % | 80 / 89 % | 71 / 89 % | 60 / 82 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 41 / 64 % | 98 / 100 % | – | 77 / 87 % | 72 / 85 % | 77 / 87 % | 75 / 85 % | 44 / 68 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 46 / 68 % | 97 / 99 % | – | 78 / 89 % | 72 / 87 % | 77 / 88 % | 79 / 90 % | 74 / 87 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 24 / 52 % | 93 / 99 % | – | 60 / 79 % | 46 / 72 % | 43 / 69 % | 50 / 77 % | 49 / 76 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 31 / 54 % | 92 / 99 % | – | 46 / 73 % | 31 / 53 % | 50 / 67 % | 25 / 48 % | 13 / 35 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 60 % | 92 / 100 % | – | 51 / 79 % | 58 / 80 % | 71 / 87 % | 58 / 85 % | 23 / 48 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 32 / 54 % | 89 / 98 % | – | 36 / 62 % | 24 / 44 % | 42 / 56 % | 11 / 23 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 34 / 56 % | 83 / 99 % | – | 67 / 83 % | 41 / 64 % | 76 / 87 % | 59 / 81 % | 14 / 42 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 25 / 53 % | 83 / 99 % | – | 27 / 57 % | 21 / 47 % | 23 / 53 % | 5 / 20 % | 33 / 62 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 29 % | 82 / 98 % | – | 16 / 45 % | 9 / 29 % | 15 / 54 % | 3 / 18 % | 35 / 63 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 15 / 44 % | 76 / 97 % | – | 48 / 70 % | 28 / 50 % | 35 / 62 % | 11 / 33 % | 41 / 70 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 15 / 46 % | 70 / 97 % | – | 18 / 44 % | 12 / 35 % | 17 / 45 % | 4 / 19 % | 26 / 51 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 47 % | 65 / 93 % | – | 36 / 62 % | 32 / 61 % | 39 / 64 % | 13 / 36 % | 20 / 53 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 20 / 45 % | 59 / 93 % | – | 31 / 61 % | 16 / 43 % | 16 / 50 % | 2 / 9 % | 21 / 44 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 28 / 55 % | 51 / 96 % | – | 57 / 79 % | 27 / 55 % | 45 / 73 % | 50 / 78 % | 47 / 73 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 20 / 53 % | 56 / 92 % | – | 36 / 63 % | 18 / 40 % | 46 / 69 % | 9 / 25 % | 30 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 24 / 56 % | 56 / 93 % | – | 30 / 57 % | 46 / 71 % | 41 / 61 % | 27 / 58 % | 12 / 34 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 14 / 45 % | 51 / 93 % | – | 19 / 44 % | 13 / 37 % | 21 / 47 % | 10 / 30 % | 24 / 53 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 25 / 48 % | 49 / 91 % | – | 38 / 60 % | 33 / 45 % | 50 / 59 % | 5 / 7 % | 23 / 51 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 17 / 37 % | 47 / 87 % | – | 16 / 43 % | 12 / 30 % | 19 / 46 % | 3 / 12 % | 11 / 33 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 40 / 85 % | – | 11 / 33 % | 4 / 15 % | 10 / 21 % | 1 / 3 % | 4 / 16 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 18 / 46 % | 19 / 87 % | – | 35 / 62 % | 16 / 37 % | 21 / 43 % | 1 / 6 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 6 / 30 % | 32 / 84 % | – | 16 / 41 % | 14 / 37 % | 17 / 47 % | 3 / 13 % | 7 / 28 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 29 / 85 % | – | 10 / 24 % | 0 / 0 % | 13 / 27 % | 1 / 6 % | 10 / 33 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 24 / 86 % | – | 8 / 23 % | 7 / 19 % | 14 / 28 % | 1 / 4 % | 3 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 39 % | 24 / 97 % | – | 13 / 38 % | 16 / 43 % | 23 / 60 % | 6 / 22 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 21 / 89 % | – | 18 / 45 % | 12 / 37 % | 20 / 37 % | 4 / 14 % | 9 / 34 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 20 / 86 % | – | 8 / 23 % | 3 / 11 % | 10 / 22 % | 1 / 4 % | 13 / 41 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 11 / 83 % | – | 18 / 41 % | 11 / 30 % | 12 / 26 % | 2 / 9 % | 8 / 30 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 17 / 72 % | – | 5 / 13 % | 4 / 11 % | 9 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 15 / 55 % | – | 5 / 13 % | 1 / 5 % | 11 / 24 % | 0 / 0 % | 7 / 23 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 14 / 36 % | 8 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 9 / 43 % | – | 12 / 39 % | 6 / 23 % | 9 / 26 % | 1 / 6 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 8 / 69 % | – | 7 / 22 % | 0 / 0 % | 8 / 12 % | 0 / 0 % | 12 / 29 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 11 / 50 % | – | 11 / 31 % | 11 / 27 % | 11 / 29 % | 1 / 6 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | 1 / 3 % | 10 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 3 / 86 % | – | 10 / 26 % | 5 / 15 % | 8 / 22 % | 1 / 5 % | 8 / 33 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 32 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 10 / 39 % | 5 / 66 % | – | 9 / 26 % | 7 / 15 % | 8 / 16 % | 1 / 5 % | 7 / 25 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 9 / 49 % | – | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 4 / 14 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 1 / 2 % | 8 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 8 / 94 % | – | 8 / 22 % | 2 / 8 % | 8 / 16 % | 1 / 5 % | 5 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 25 % |
