[English](README.md) · [Deutsch](README.de.md)

# Deep research System Card

Bericht Q009223 · Quelle openai.com · Datum 2025-02-25 · [Original öffnen](https://openai.com/index/deep-research-system-card/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Auszug beschreibt Deep research als webbasierten Recherche-Agenten und fasst OpenAIs Sicherheitsarbeit vor der Freigabe zusammen, darunter Schutz persönlicher Informationen und Widerstand gegen bösartige Anweisungen. Die Scorecard erlaubt laut Text den Einsatz nur bis zur Stufe „mittel“ nach Schutzmaßnahmen; konkrete Testergebnisse oder die Einstufung des Systems enthält der Auszug nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 32 / 50 % | 85 / 97 % | 99 / 100 % | 45 / 71 % | 9 / 27 % | 41 / 67 % | 22 / 62 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 30 / 51 % | 80 / 99 % | 96 / 99 % | 36 / 66 % | 19 / 40 % | 55 / 73 % | 32 / 67 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 21 / 43 % | 59 / 93 % | 94 / 98 % | 18 / 41 % | 7 / 15 % | 21 / 42 % | 2 / 13 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 45 % | 48 / 73 % | 93 / 97 % | 41 / 66 % | 10 / 26 % | 36 / 53 % | 19 / 53 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 23 / 46 % | 50 / 89 % | 93 / 98 % | 33 / 58 % | 5 / 17 % | 22 / 44 % | 11 / 42 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 34 / 55 % | 81 / 98 % | 91 / 96 % | 54 / 74 % | 13 / 30 % | 47 / 63 % | 26 / 54 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 17 / 38 % | 26 / 66 % | 85 / 93 % | 22 / 53 % | 4 / 15 % | 30 / 58 % | 2 / 17 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 48 / 80 % | 82 / 90 % | 11 / 31 % | 2 / 8 % | 0 / 0 % | 0 / 2 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 28 / 53 % | 50 / 88 % | 78 / 95 % | 16 / 41 % | 13 / 37 % | 39 / 63 % | 10 / 44 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 26 / 46 % | 52 / 95 % | 76 / 92 % | 19 / 48 % | 4 / 16 % | 18 / 46 % | 3 / 14 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 18 / 47 % | 0 / 0 % | 74 / 84 % | 23 / 49 % | 6 / 17 % | 23 / 49 % | 3 / 13 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 26 % | 64 / 82 % | 40 / 65 % | 9 / 27 % | 2 / 11 % | 13 / 24 % | 1 / 6 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 61 / 80 % | 6 / 15 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 20 / 39 % | 29 / 78 % | 59 / 83 % | 19 / 44 % | 5 / 14 % | 0 / 0 % | 2 / 11 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 7 / 29 % | 47 / 84 % | 1 / 5 % | 6 / 14 % | 1 / 5 % | 0 / 0 % | 0 / 5 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 45 / 76 % | 30 / 61 % | 7 / 23 % | 1 / 7 % | 6 / 17 % | 1 / 7 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 17 / 41 % | 37 / 74 % | 1 / 13 % | 10 / 27 % | 3 / 11 % | 10 / 20 % | 1 / 10 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 30 / 52 % | 8 / 23 % | 3 / 10 % | 10 / 20 % | 1 / 9 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 11 / 37 % | 27 / 65 % | 3 / 22 % | 13 / 34 % | 4 / 16 % | 16 / 37 % | 1 / 9 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 11 / 29 % | 0 / 0 % | 27 / 54 % | 7 / 25 % | 2 / 9 % | 6 / 15 % | 1 / 8 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 17 / 35 % | 13 / 62 % | 13 / 40 % | 10 / 32 % | 7 / 16 % | 19 / 31 % | 4 / 16 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 16 / 50 % | 1 / 8 % | 6 / 18 % | 1 / 6 % | 0 / 0 % | 0 / 3 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 12 / 24 % | 0 / 0 % | 9 / 32 % | 7 / 18 % | 0 / 3 % | 6 / 14 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 11 / 37 % | 0 / 0 % | 0 / 0 % | 12 / 36 % | 3 / 10 % | 9 / 20 % | 2 / 10 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 9 / 23 % | 0 / 0 % | 0 / 0 % | 5 / 17 % | 1 / 7 % | 8 / 16 % | 0 / 2 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 9 / 31 % | 0 / 0 % | 3 / 21 % | 6 / 16 % | 1 / 6 % | 7 / 15 % | 0 / 2 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 1 / 4 % | 6 / 17 % | 0 / 2 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 25 % | 3 / 47 % | 0 / 0 % | 6 / 16 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 26 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 8 % | 6 / 15 % | 1 / 5 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 6 / 46 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 6 / 22 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 5 / 10 % | 0 / 2 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 5 / 11 % | 0 / 0 % | – |
