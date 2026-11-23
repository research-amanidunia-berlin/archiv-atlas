[English](README.md) · [Deutsch](README.de.md)

# Embedded Evaluators are necessary for meaningful external testing

Bericht Q000954 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/blog/embedded-evaluators-are-necessary-for-meaningful-external-testing)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Apollo Research argumentiert, dass unabhängige KI-Prüfungen schon während Training und interner Nutzung mit weitreichendem Zugang stattfinden müssen; Prüfungen am fertigen Modell könnten frühe Risiken wie jene des geschilderten Hugging-Face-Vorfalls verpassen. Der Bericht nennt frühere Erkenntnisse aus vertieften Prüfungen, räumt aber ein, dass Evaluationen ungelöste Ausrichtungsprobleme nicht beheben und sicheres Verhalten unter Beobachtung schwer beurteilen können.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 88 / 93 % | 100 / 100 % | – | 90 / 93 % | 97 / 98 % | 96 / 97 % | 99 / 100 % | 74 / 89 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 58 / 72 % | 100 / 100 % | – | 86 / 93 % | 90 / 96 % | 91 / 95 % | 91 / 98 % | 71 / 86 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 56 / 74 % | 100 / 100 % | – | 90 / 94 % | 83 / 91 % | 88 / 93 % | 96 / 98 % | 59 / 77 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 40 / 60 % | 99 / 100 % | – | 73 / 84 % | 28 / 46 % | 65 / 77 % | 6 / 13 % | 34 / 56 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 55 / 74 % | 99 / 100 % | – | 88 / 93 % | 82 / 92 % | 75 / 87 % | 53 / 76 % | 43 / 65 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 63 / 79 % | 99 / 100 % | – | 46 / 63 % | 85 / 93 % | 73 / 85 % | 85 / 94 % | 60 / 77 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 49 / 67 % | 96 / 99 % | – | 85 / 92 % | 32 / 56 % | 69 / 82 % | 30 / 49 % | 36 / 57 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 56 / 77 % | 95 / 99 % | – | 89 / 93 % | 86 / 94 % | 90 / 94 % | 56 / 80 % | 44 / 68 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 37 % | 83 / 99 % | – | 40 / 69 % | 10 / 30 % | 32 / 57 % | 8 / 29 % | 25 / 52 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 32 / 54 % | 83 / 94 % | – | 55 / 75 % | 30 / 54 % | 52 / 71 % | 23 / 41 % | 15 / 32 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 49 % | 79 / 100 % | – | 16 / 41 % | 5 / 26 % | 17 / 46 % | 1 / 7 % | 26 / 48 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 47 / 72 % | 60 / 97 % | – | 70 / 86 % | 33 / 62 % | 76 / 88 % | 53 / 84 % | 28 / 55 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 34 / 60 % | 75 / 96 % | – | 57 / 80 % | 38 / 73 % | 58 / 83 % | 19 / 46 % | 41 / 62 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 41 % | 68 / 94 % | – | 30 / 56 % | 8 / 26 % | 33 / 53 % | 6 / 13 % | 10 / 28 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 23 / 53 % | 66 / 91 % | – | 44 / 68 % | 11 / 31 % | 34 / 57 % | 10 / 27 % | 12 / 34 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 28 / 50 % | 65 / 94 % | – | 40 / 69 % | 19 / 43 % | 39 / 65 % | 11 / 34 % | 23 / 49 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 32 / 56 % | 64 / 97 % | – | 59 / 79 % | 15 / 34 % | 53 / 73 % | 6 / 22 % | 20 / 45 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 20 / 53 % | 23 / 92 % | – | 25 / 51 % | 23 / 53 % | 58 / 82 % | 12 / 52 % | 22 / 47 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 14 / 42 % | 58 / 90 % | – | 20 / 47 % | 6 / 18 % | 14 / 36 % | 5 / 20 % | 21 / 46 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 43 % | 54 / 97 % | – | 27 / 56 % | 6 / 24 % | 47 / 66 % | 9 / 30 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 53 / 96 % | – | 19 / 41 % | 8 / 22 % | 17 / 34 % | 10 / 32 % | 42 / 66 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 9 / 78 % | – | 45 / 70 % | 12 / 32 % | 15 / 33 % | 2 / 10 % | 26 / 51 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 43 / 86 % | – | 15 / 40 % | 8 / 25 % | 13 / 24 % | 1 / 3 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 9 / 90 % | – | 40 / 65 % | 11 / 31 % | 24 / 43 % | 5 / 17 % | 25 / 52 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 37 / 86 % | – | 16 / 38 % | 7 / 22 % | 11 / 26 % | 1 / 8 % | 11 / 29 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 36 / 85 % | – | 10 / 24 % | 4 / 9 % | 17 / 29 % | 1 / 4 % | 21 / 45 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 38 % | 18 / 80 % | – | 25 / 54 % | 7 / 21 % | 33 / 58 % | 7 / 27 % | 21 / 48 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 24 / 63 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 45 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 21 / 47 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 17 / 57 % | – | 14 / 34 % | 5 / 14 % | 9 / 24 % | 2 / 8 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 9 / 19 % | 0 / 0 % | – | 15 / 37 % | 5 / 14 % | 13 / 35 % | 3 / 10 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 15 / 35 % | 0 / 0 % | – | 15 / 39 % | 7 / 22 % | 12 / 30 % | 6 / 23 % | 9 / 29 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 14 / 91 % | – | 8 / 21 % | 3 / 10 % | 8 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 29 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 11 / 27 % | 0 / 0 % | 12 / 24 % | 1 / 4 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 12 / 33 % | – | 9 / 23 % | 0 / 0 % | 10 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 9 / 24 % | 6 / 13 % | 10 / 18 % | 0 / 2 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 7 / 71 % | – | 5 / 11 % | 1 / 4 % | 9 / 15 % | 0 / 0 % | 2 / 11 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 7 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 6 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
