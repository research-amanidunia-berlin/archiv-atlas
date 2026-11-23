[English](README.md) · [Deutsch](README.de.md)

# Trustworthy agents in practice

Bericht Q001742 · Quelle anthropic.com · Datum 2026-04-09 · [Original öffnen](https://www.anthropic.com/research/trustworthy-agents)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic beschreibt Agentensicherheit als Zusammenspiel von Modell, Schutzregeln, Werkzeugen und Einsatzumgebung. Der Bericht nennt Kontrollen, Nachfragen bei Unsicherheit und mehrschichtige Abwehr gegen Prompt-Injection, räumt aber ein, dass diese keinen vollständigen Schutz garantieren und standardisierte unabhängige Vergleichstests fehlen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 60 / 73 % | 93 / 97 % | 100 / 100 % | 89 / 94 % | 78 / 90 % | 89 / 93 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 79 / 90 % | 98 / 99 % | 100 / 100 % | 93 / 96 % | 92 / 96 % | 92 / 95 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 38 / 59 % | 96 / 98 % | 100 / 100 % | 66 / 85 % | 65 / 80 % | 68 / 82 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 30 / 48 % | 89 / 95 % | 96 / 99 % | 71 / 86 % | 31 / 60 % | 57 / 80 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 16 / 38 % | 47 / 87 % | 93 / 98 % | 45 / 71 % | 35 / 57 % | 32 / 67 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 15 / 37 % | 61 / 93 % | 91 / 96 % | 51 / 74 % | 26 / 49 % | 52 / 70 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 27 / 46 % | 85 / 96 % | 90 / 95 % | 65 / 82 % | 47 / 62 % | 67 / 80 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 31 % | 83 / 96 % | 89 / 98 % | 20 / 50 % | 10 / 23 % | 15 / 35 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 21 / 44 % | 59 / 80 % | 89 / 95 % | 64 / 83 % | 28 / 53 % | 63 / 81 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 25 / 43 % | 86 / 95 % | 87 / 95 % | 56 / 79 % | 49 / 65 % | 68 / 81 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 46 / 75 % | 85 / 94 % | 10 / 33 % | 3 / 11 % | 7 / 11 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 19 / 45 % | 76 / 95 % | 83 / 97 % | 68 / 83 % | 68 / 81 % | 80 / 88 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 24 / 48 % | 58 / 89 % | 75 / 90 % | 58 / 78 % | 59 / 77 % | 81 / 89 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 18 / 37 % | 72 / 87 % | 62 / 74 % | 46 / 68 % | 41 / 54 % | 51 / 66 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 19 / 40 % | 62 / 83 % | 65 / 81 % | 36 / 62 % | 28 / 45 % | 30 / 53 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 46 % | 58 / 85 % | 64 / 81 % | 30 / 53 % | 40 / 52 % | 58 / 74 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 27 % | 56 / 81 % | 60 / 81 % | 16 / 42 % | 9 / 19 % | 9 / 18 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 14 / 32 % | 55 / 90 % | 32 / 67 % | 25 / 47 % | 11 / 23 % | 23 / 36 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 53 / 89 % | 14 / 44 % | 8 / 27 % | 4 / 15 % | 7 / 13 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 13 / 28 % | 50 / 78 % | 28 / 79 % | 31 / 57 % | 14 / 33 % | 36 / 54 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 15 / 36 % | 46 / 82 % | 26 / 60 % | 11 / 37 % | 5 / 17 % | 8 / 19 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 40 / 70 % | 6 / 51 % | 9 / 28 % | 2 / 9 % | 8 / 17 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 12 / 29 % | 38 / 79 % | 26 / 81 % | 28 / 54 % | 27 / 44 % | 14 / 36 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 31 % | 37 / 79 % | 9 / 27 % | 18 / 43 % | 13 / 25 % | 17 / 32 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 31 / 64 % | 23 / 64 % | 37 / 62 % | 10 / 24 % | 16 / 33 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 35 / 73 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 9 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 13 / 20 % | 35 / 72 % | 4 / 35 % | 11 / 36 % | 5 / 14 % | 9 / 20 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 11 / 43 % | 34 / 65 % | 29 / 55 % | 25 / 53 % | 21 / 40 % | 14 / 30 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 9 / 22 % | 25 / 78 % | 10 / 32 % | 7 / 18 % | 7 / 16 % | 6 / 10 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 21 / 73 % | 0 / 14 % | 7 / 18 % | 5 / 16 % | 7 / 13 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 20 / 72 % | 0 / 0 % | 5 / 12 % | 2 / 8 % | 4 / 6 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 18 / 53 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 5 / 8 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 15 / 31 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 4 / 12 % | 11 / 27 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 12 / 34 % | 15 / 52 % | 2 / 12 % | 14 / 36 % | 13 / 24 % | 13 / 24 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 34 % | 0 / 0 % | 5 / 8 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 13 / 79 % | 0 / 0 % | 0 / 0 % | 2 / 5 % | 5 / 11 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 13 / 44 % | 0 / 0 % | 5 / 11 % | 5 / 13 % | 5 / 7 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 24 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 3 / 9 % | 8 / 15 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 2 / 8 % | 2 / 5 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 6 / 14 % | – | – |
