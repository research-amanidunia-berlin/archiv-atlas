[English](README.md) · [Deutsch](README.de.md)

# A shared playbook for trustworthy third party evaluations

Bericht Q004558 · Quelle web.archive.org · Datum 2026-05-29 · [Original öffnen](https://web.archive.org/web/20260809065627/https://openai.com/index/trustworthy-third-party-evaluations-foundations/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht argumentiert, dass Evaluationsergebnisse fortgeschrittener KI stark vom Harness und Budget abhängen und deshalb nur zusammen mit diesen Bedingungen sowie dem geprüften Anspruch interpretiert werden sollten. Er empfiehlt passende Testaufbauten und systematische Prüfungen auf Verzerrungen wie Reward Hacking, Kontamination oder Sandbagging; Fehlanpassungs- und Neigungsbehauptungen behandelt er ausdrücklich nicht abschließend.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 60 / 75 % | 100 / 100 % | 99 / 100 % | 81 / 90 % | 84 / 92 % | 88 / 92 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 28 / 52 % | 100 / 100 % | 87 / 91 % | 66 / 80 % | 50 / 67 % | 64 / 78 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 65 / 79 % | 98 / 100 % | 98 / 100 % | 59 / 71 % | 83 / 91 % | 86 / 91 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 59 % | 91 / 99 % | 76 / 88 % | 54 / 78 % | 38 / 63 % | 50 / 72 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 33 / 54 % | 34 / 94 % | 73 / 84 % | 75 / 86 % | 56 / 75 % | 80 / 88 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 18 / 43 % | 35 / 73 % | 80 / 91 % | 27 / 54 % | 9 / 22 % | 17 / 39 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 37 / 61 % | 43 / 83 % | 76 / 90 % | 28 / 46 % | 49 / 68 % | 37 / 55 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 34 / 62 % | 39 / 85 % | 75 / 91 % | 72 / 86 % | 31 / 51 % | 36 / 61 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 36 / 56 % | 27 / 96 % | 72 / 86 % | 49 / 73 % | 27 / 53 % | 29 / 55 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 49 % | 30 / 90 % | 49 / 87 % | 50 / 74 % | 21 / 42 % | 68 / 81 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 17 / 46 % | 51 / 96 % | 57 / 89 % | 45 / 70 % | 7 / 23 % | 43 / 66 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 44 / 64 % | 30 / 96 % | 29 / 63 % | 42 / 70 % | 33 / 53 % | 50 / 66 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 20 / 43 % | 50 / 89 % | 21 / 28 % | 21 / 42 % | 10 / 22 % | 24 / 42 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 14 / 40 % | 45 / 94 % | 5 / 27 % | 22 / 51 % | 9 / 24 % | 21 / 38 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 14 / 48 % | 40 / 70 % | 10 / 24 % | 3 / 9 % | 8 / 15 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 36 / 80 % | 9 / 30 % | 8 / 21 % | 3 / 11 % | 6 / 15 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 30 / 84 % | 1 / 18 % | 12 / 30 % | 5 / 12 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 29 / 96 % | 12 / 35 % | 12 / 32 % | 6 / 15 % | 7 / 15 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 25 / 43 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 4 / 17 % | 21 / 37 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 39 % | 20 / 82 % | 0 / 0 % | 11 / 29 % | 2 / 10 % | 11 / 22 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 14 / 46 % | 19 / 37 % | 7 / 15 % | 2 / 6 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 1 / 21 % | 0 / 0 % | 9 / 20 % | 8 / 18 % | 18 / 31 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 17 / 75 % | 5 / 36 % | 12 / 28 % | 4 / 12 % | 7 / 18 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 15 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 28 % | 11 / 63 % | 0 / 0 % | 9 / 23 % | 4 / 13 % | 11 / 22 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 8 / 39 % | 0 / 0 % | 11 / 24 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 9 / 53 % | 2 / 16 % | 7 / 14 % | 0 / 0 % | 10 / 18 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 21 % | 0 / 0 % | 7 / 16 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 2 / 9 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 7 / 12 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 4 / 83 % | 0 / 0 % | 7 / 18 % | 3 / 9 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 8 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 4 / 9 % | 5 / 10 % | – | – |
