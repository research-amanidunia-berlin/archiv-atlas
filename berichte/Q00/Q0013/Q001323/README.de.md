[English](README.md) · [Deutsch](README.de.md)

# The Evals Gap

Bericht Q001323 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/science/the-evals-gap)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Apollo Research argumentiert, dass es zu wenige und zu wenig belastbare Sicherheitsprüfungen für leistungsfähige KI-Modelle gibt; vorhandene Tests deckten Risiken oft nur punktuell ab und seien schwer zu entwickeln und auszuwerten. Der Bericht empfiehlt mehr Finanzierung für Testentwicklung und Forschung sowie bessere Anreize, weist aber darauf hin, dass Teile der Einschätzung auf nicht systematisch ausgewerteten Gesprächen beruhen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 36 / 65 % | 91 / 99 % | – | 58 / 81 % | 45 / 72 % | 62 / 81 % | 40 / 87 % | 21 / 48 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 25 / 57 % | 80 / 98 % | – | 66 / 84 % | 23 / 47 % | 62 / 77 % | 23 / 66 % | 28 / 60 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 26 / 52 % | 79 / 94 % | – | 33 / 59 % | 21 / 41 % | 47 / 67 % | 10 / 23 % | 30 / 59 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 43 / 74 % | 42 / 93 % | – | 62 / 81 % | 50 / 75 % | 68 / 84 % | 43 / 93 % | 28 / 58 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 33 / 61 % | 33 / 92 % | – | 68 / 86 % | 28 / 59 % | 43 / 68 % | 22 / 74 % | 21 / 51 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 33 / 60 % | 38 / 88 % | – | 59 / 81 % | 18 / 44 % | 64 / 79 % | 10 / 59 % | 18 / 49 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 18 / 43 % | 59 / 94 % | – | 15 / 40 % | 8 / 24 % | 17 / 37 % | 1 / 10 % | 33 / 60 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 19 / 47 % | 57 / 96 % | – | 43 / 68 % | 8 / 24 % | 31 / 50 % | 9 / 23 % | 19 / 42 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 16 / 43 % | 48 / 91 % | – | 52 / 74 % | 10 / 23 % | 38 / 55 % | 6 / 21 % | 15 / 37 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 21 / 50 % | 23 / 65 % | – | 40 / 70 % | 24 / 49 % | 48 / 69 % | 7 / 35 % | 16 / 41 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 57 % | 46 / 90 % | – | 33 / 63 % | 11 / 33 % | 34 / 62 % | 10 / 39 % | 29 / 54 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 20 / 51 % | 21 / 67 % | – | 41 / 69 % | 8 / 28 % | 30 / 60 % | 10 / 35 % | 19 / 47 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 41 / 89 % | – | 9 / 26 % | 2 / 10 % | 6 / 17 % | 0 / 4 % | 14 / 37 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 35 % | 33 / 79 % | – | 9 / 26 % | 4 / 12 % | 10 / 21 % | 0 / 3 % | 8 / 26 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 15 / 47 % | 33 / 73 % | – | 17 / 42 % | 4 / 15 % | 10 / 26 % | 2 / 10 % | 11 / 32 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 23 / 50 % | 17 / 98 % | – | 23 / 52 % | 11 / 27 % | 27 / 43 % | 3 / 18 % | 3 / 15 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 24 / 53 % | 15 / 91 % | – | 26 / 58 % | 13 / 30 % | 27 / 57 % | 2 / 15 % | 14 / 34 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 20 / 55 % | 16 / 85 % | – | 23 / 50 % | 10 / 28 % | 15 / 29 % | 4 / 23 % | 10 / 32 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 20 / 65 % | – | 6 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 6 / 21 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 10 / 38 % | 19 / 92 % | – | 16 / 41 % | 3 / 11 % | 9 / 19 % | 0 / 4 % | 12 / 39 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 49 % | 4 / 65 % | – | 12 / 37 % | 6 / 18 % | 14 / 29 % | 1 / 9 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 14 / 41 % | 0 / 0 % | – | 10 / 28 % | 3 / 10 % | 8 / 18 % | 1 / 5 % | 4 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 42 % | 0 / 0 % | – | 7 / 16 % | 0 / 0 % | 9 / 16 % | 1 / 4 % | 2 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 13 / 79 % | – | 10 / 30 % | 3 / 13 % | 7 / 16 % | 0 / 3 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 36 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 11 / 33 % | 2 / 10 % | 7 / 16 % | 1 / 5 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 9 / 46 % | – | 7 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 2 / 39 % | – | 8 / 24 % | 1 / 6 % | 4 / 9 % | 0 / 0 % | 5 / 22 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 8 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 8 / 18 % | 0 / 3 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 6 / 69 % | – | 7 / 19 % | 1 / 5 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 7 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 4 % | 7 / 14 % | 0 / 0 % | 4 / 17 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 1 / 5 % | 4 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 3 / 62 % | – | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 18 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | – | 5 / 14 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | 5 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 2 / 65 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 8 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
