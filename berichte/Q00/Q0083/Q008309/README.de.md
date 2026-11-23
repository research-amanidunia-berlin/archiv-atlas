[English](README.md) · [Deutsch](README.de.md)

# Improving verifiability in AI development

Bericht Q008309 · Quelle openai.com · Datum 2020-04-16 · [Original öffnen](https://openai.com/index/improving-verifiability/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Text fasst zehn vorgeschlagene Ansätze zusammen, mit denen sich Aussagen über Sicherheit, Fairness und Datenschutz von KI-Systemen besser prüfen lassen sollen – von externen Audits und Vorfallmeldungen bis zu sicheren Hardwarelösungen und mehr Rechenleistung für akademische Forschung. Er ist eine Zusammenfassung, nicht der vollständige Bericht; Belege, Wirksamkeitsvergleiche und dort erwähnte Einschränkungen werden nicht ausgeführt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 32 / 58 % | 88 / 98 % | 93 / 99 % | 59 / 82 % | 65 / 84 % | 70 / 84 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 42 / 64 % | 89 / 97 % | 58 / 76 % | 70 / 85 % | 57 / 73 % | 74 / 84 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 26 / 59 % | 48 / 97 % | 86 / 96 % | 40 / 67 % | 9 / 35 % | 34 / 65 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 35 / 58 % | 67 / 96 % | 85 / 95 % | 41 / 72 % | 12 / 42 % | 53 / 76 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 24 / 50 % | 36 / 74 % | 80 / 92 % | 23 / 57 % | 13 / 34 % | 30 / 63 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 24 / 56 % | 43 / 86 % | 76 / 92 % | 48 / 77 % | 45 / 71 % | 50 / 73 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 17 / 45 % | 53 / 97 % | 73 / 86 % | 15 / 42 % | 5 / 20 % | 15 / 45 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 27 / 55 % | 37 / 82 % | 69 / 86 % | 43 / 71 % | 32 / 59 % | 48 / 70 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 21 / 49 % | 65 / 92 % | 68 / 83 % | 35 / 61 % | 35 / 59 % | 44 / 66 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 31 / 60 % | 53 / 93 % | 65 / 93 % | 55 / 79 % | 46 / 72 % | 52 / 75 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 22 / 49 % | 62 / 92 % | 46 / 77 % | 31 / 61 % | 19 / 43 % | 36 / 56 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 45 % | 61 / 96 % | 28 / 52 % | 16 / 44 % | 12 / 32 % | 43 / 65 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 15 / 41 % | 7 / 43 % | 57 / 85 % | 17 / 48 % | 6 / 30 % | 16 / 47 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 25 / 54 % | 36 / 90 % | 53 / 83 % | 37 / 68 % | 22 / 50 % | 21 / 52 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 39 % | 44 / 84 % | 38 / 72 % | 22 / 52 % | 8 / 33 % | 28 / 62 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 22 / 46 % | 37 / 64 % | 43 / 71 % | 32 / 60 % | 16 / 37 % | 37 / 57 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 13 / 41 % | 42 / 93 % | 9 / 54 % | 15 / 42 % | 9 / 30 % | 20 / 44 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 12 / 44 % | 30 / 78 % | 41 / 80 % | 22 / 51 % | 14 / 38 % | 35 / 62 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 14 / 45 % | 38 / 81 % | 23 / 65 % | 17 / 52 % | 3 / 17 % | 11 / 37 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 24 / 48 % | 35 / 75 % | 16 / 55 % | 19 / 52 % | 7 / 25 % | 22 / 54 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 32 / 69 % | 31 / 60 % | 8 / 23 % | 5 / 16 % | 8 / 22 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 32 / 78 % | 9 / 42 % | 10 / 29 % | 3 / 12 % | 12 / 26 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 8 / 35 % | 31 / 89 % | 17 / 65 % | 14 / 43 % | 2 / 16 % | 12 / 33 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 16 / 41 % | 29 / 88 % | 27 / 78 % | 27 / 59 % | 8 / 28 % | 23 / 49 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 7 / 32 % | 28 / 82 % | 0 / 0 % | 9 / 30 % | 0 / 8 % | 7 / 22 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 23 / 70 % | 15 / 47 % | 7 / 23 % | 3 / 11 % | 9 / 22 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 38 % | 23 / 76 % | 1 / 10 % | 8 / 25 % | 3 / 13 % | 12 / 30 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 21 / 77 % | 1 / 24 % | 15 / 43 % | 9 / 26 % | 14 / 29 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 20 / 50 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 11 / 40 % | 3 / 19 % | 12 / 33 % | 2 / 10 % | 13 / 31 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 12 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 38 % | 12 / 33 % | 12 / 30 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 11 / 37 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 31 % | 1 / 5 % | 10 / 22 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 10 / 54 % | 0 / 0 % | 6 / 19 % | 1 / 6 % | 6 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 9 / 54 % | 2 / 14 % | 6 / 22 % | 2 / 10 % | 6 / 17 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 5 / 58 % | 0 / 0 % | 6 / 15 % | 2 / 7 % | 9 / 24 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 4 / 14 % | 7 / 17 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 8 / 17 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 6 / 75 % | 0 / 0 % | 6 / 15 % | 1 / 7 % | 8 / 16 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 7 / 18 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 4 / 27 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 6 / 12 % | – | – |
