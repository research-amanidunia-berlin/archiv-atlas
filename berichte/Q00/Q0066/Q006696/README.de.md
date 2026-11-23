[English](README.md) · [Deutsch](README.de.md)

# Testing frameworks for the classification of AI systems

Bericht Q006696 · Quelle oecd.ai · Datum 2021-12-14 · [Original öffnen](https://oecd.ai/en/wonk/cset-test-classification-ai-systems)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

CSET testete mehrere Rahmen, mit denen Menschen KI-Systeme anhand von Merkmalen wie Autonomie und Auswirkungen einordnen sollen. Die Rahmen C und D sowie eine zusammenfassende Rubrik führten laut Bericht zu mehr korrekten und übereinstimmenden Einstufungen; technische Merkmale und Autonomie waren schwieriger zu bewerten. Die Ergebnisse hängen wesentlich davon ab, ob ausreichend zugängliche Informationen über den Einsatz und die Technik vorliegen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 20 / 49 % | 37 / 98 % | 93 / 98 % | 55 / 78 % | 15 / 41 % | 36 / 64 % | 13 / 62 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 15 / 65 % | 57 / 67 % | 10 / 36 % | 6 / 18 % | 12 / 31 % | 1 / 8 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 21 / 46 % | 25 / 95 % | 42 / 80 % | 25 / 56 % | 8 / 26 % | 22 / 50 % | 5 / 26 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 38 / 96 % | 26 / 52 % | 14 / 37 % | 6 / 20 % | 14 / 33 % | 2 / 13 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 10 / 85 % | 37 / 65 % | 6 / 17 % | 1 / 4 % | 6 / 11 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 13 / 38 % | 26 / 85 % | 20 / 48 % | 29 / 56 % | 6 / 20 % | 20 / 42 % | 3 / 11 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 23 / 86 % | 26 / 47 % | 9 / 31 % | 2 / 11 % | 8 / 20 % | 0 / 3 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 25 / 90 % | 2 / 20 % | 8 / 26 % | 1 / 8 % | 7 / 15 % | 0 / 2 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 8 / 34 % | 25 / 80 % | 5 / 47 % | 12 / 37 % | 3 / 14 % | 9 / 23 % | 2 / 17 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 10 / 33 % | 24 / 72 % | 17 / 56 % | 16 / 42 % | 5 / 18 % | 11 / 28 % | 2 / 10 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 10 / 83 % | 24 / 63 % | 20 / 49 % | 5 / 18 % | 6 / 13 % | 2 / 13 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 16 / 37 % | 24 / 91 % | 5 / 30 % | 18 / 46 % | 5 / 18 % | 14 / 32 % | 3 / 15 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 8 / 24 % | 23 / 97 % | 11 / 55 % | 13 / 36 % | 3 / 19 % | 13 / 41 % | 1 / 8 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 17 / 71 % | 0 / 0 % | 9 / 27 % | 3 / 12 % | 13 / 36 % | 1 / 5 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 8 / 17 % | 10 / 83 % | 15 / 51 % | 8 / 19 % | 1 / 4 % | 3 / 7 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 15 / 78 % | 0 / 0 % | 5 / 11 % | 0 / 2 % | 5 / 9 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 31 % | 12 / 93 % | 2 / 29 % | 11 / 40 % | 1 / 9 % | 8 / 21 % | 0 / 4 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 12 / 32 % | 10 / 44 % | 4 / 28 % | 6 / 20 % | 1 / 5 % | 7 / 16 % | 0 / 2 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 9 / 35 % | 6 / 51 % | 0 / 0 % | 12 / 37 % | 3 / 11 % | 11 / 25 % | 1 / 7 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 11 / 90 % | 0 / 0 % | 9 / 19 % | 0 / 3 % | 4 / 9 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 10 / 80 % | 1 / 14 % | 6 / 14 % | 1 / 4 % | 6 / 9 % | 0 / 1 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 25 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 9 / 56 % | 0 / 16 % | 6 / 14 % | 1 / 5 % | 5 / 10 % | 0 / 1 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 1 / 6 % | 5 / 12 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 2 / 7 % | 8 / 15 % | 0 / 2 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 0 / 0 % | 8 / 18 % | 0 / 3 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 23 % | 4 / 79 % | 2 / 23 % | 8 / 23 % | 1 / 8 % | 6 / 15 % | 0 / 2 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 7 / 14 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 2 / 40 % | 0 / 0 % | 7 / 16 % | 0 / 3 % | 5 / 12 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 7 / 12 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 7 % | 5 / 11 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 5 / 26 % | 6 / 80 % | 0 / 7 % | 6 / 20 % | 2 / 10 % | 6 / 18 % | 0 / 3 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 7 % | 6 / 12 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 6 % | 4 / 7 % | 0 / 2 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 5 % | 5 / 9 % | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 5 / 10 % | 0 / 2 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 3 / 50 % | 0 / 0 % | 5 / 14 % | 1 / 6 % | 4 / 9 % | 0 / 1 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 2 / 81 % | 0 / 6 % | 5 / 14 % | 1 / 6 % | 4 / 9 % | 0 / 2 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 95 % | 0 / 3 % | 5 / 13 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 4 / 10 % | 0 / 0 % | – |
