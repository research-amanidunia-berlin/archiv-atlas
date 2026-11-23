[English](README.md) · [Deutsch](README.de.md)

# GPT-6 Sol and GPT-6 Luna: October 2026 update

Bericht Q000082 · Quelle deploymentsafety.openai.com · Datum 2026-10-07 · [Original öffnen](https://deploymentsafety.openai.com/gpt-6-october)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet für GPT‑6 Sol und Luna von Verbesserungen bei mehreren Tests zu Jailbreaks, Faktenrichtigkeit und Gesundheit, zugleich aber von Rückgängen in einzelnen Sicherheits- und Jugendtests. Die Bewertungen beruhen vielfach auf gezielt schwierigen Fällen ohne systemweite Schutzmaßnahmen und sind laut Bericht keine Schätzung des typischen Produktbetriebs.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 62 / 76 % | 96 / 98 % | 100 / 100 % | 81 / 89 % | 44 / 65 % | 80 / 88 % | 91 / 96 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 63 / 77 % | 93 / 95 % | 100 / 100 % | 90 / 94 % | 36 / 56 % | 72 / 83 % | 91 / 95 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 48 / 67 % | 99 / 100 % | 100 / 100 % | 74 / 87 % | 64 / 80 % | 79 / 89 % | 49 / 76 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 48 / 66 % | 100 / 100 % | 98 / 99 % | 83 / 90 % | 56 / 76 % | 74 / 85 % | 71 / 84 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 53 / 69 % | 93 / 99 % | 100 / 100 % | 85 / 92 % | 55 / 75 % | 81 / 90 % | 80 / 90 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 38 / 58 % | 75 / 94 % | 97 / 98 % | 74 / 87 % | 26 / 45 % | 16 / 32 % | 24 / 41 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 48 / 66 % | 78 / 96 % | 95 / 97 % | 85 / 91 % | 65 / 82 % | 87 / 93 % | 61 / 79 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 32 / 54 % | 95 / 98 % | 93 / 96 % | 44 / 69 % | 14 / 28 % | 37 / 56 % | 8 / 19 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 53 / 70 % | 93 / 99 % | 91 / 96 % | 77 / 88 % | 22 / 42 % | 66 / 80 % | 30 / 53 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 28 / 48 % | 91 / 97 % | 93 / 95 % | 71 / 85 % | 10 / 24 % | 67 / 79 % | 60 / 73 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 41 / 59 % | 56 / 89 % | 86 / 93 % | 74 / 87 % | 17 / 38 % | 47 / 66 % | 22 / 46 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 40 / 60 % | 73 / 91 % | 50 / 62 % | 73 / 86 % | 47 / 64 % | 77 / 85 % | 15 / 20 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 66 / 86 % | 0 / 0 % | 9 / 24 % | 4 / 10 % | 6 / 13 % | 0 / 3 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 63 / 76 % | 14 / 36 % | 3 / 6 % | 7 / 13 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 59 / 77 % | 16 / 41 % | 4 / 11 % | 7 / 15 % | 1 / 5 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 54 / 88 % | 50 / 62 % | 27 / 56 % | 9 / 23 % | 18 / 38 % | 1 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 20 / 55 % | 54 / 72 % | 15 / 34 % | 5 / 14 % | 14 / 26 % | 1 / 6 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 13 / 35 % | 43 / 93 % | 3 / 11 % | 25 / 50 % | 9 / 23 % | 46 / 65 % | 5 / 12 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 43 / 68 % | 30 / 54 % | 13 / 36 % | 4 / 11 % | 8 / 18 % | 1 / 7 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 34 / 54 % | 9 / 26 % | 2 / 6 % | 5 / 13 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 28 / 65 % | 0 / 0 % | 0 / 0 % | 17 / 44 % | 9 / 20 % | 18 / 40 % | 1 / 4 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 18 / 42 % | 28 / 73 % | 0 / 0 % | 17 / 44 % | 5 / 12 % | 18 / 37 % | 3 / 10 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 45 % | 0 / 0 % | 0 / 0 % | 28 / 56 % | 4 / 11 % | 10 / 18 % | 2 / 8 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 27 / 57 % | 0 / 0 % | 12 / 32 % | 1 / 8 % | 9 / 18 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 8 / 57 % | 5 / 14 % | 14 / 34 % | 2 / 8 % | 6 / 13 % | 0 / 2 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 3 / 9 % | 11 / 22 % | 0 / 2 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 5 / 16 % | 9 / 25 % | 3 / 8 % | 11 / 23 % | 0 / 1 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 2 / 15 % | 11 / 27 % | 3 / 10 % | 6 / 16 % | 0 / 2 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 30 % | 1 / 3 % | 8 / 18 % | 0 / 1 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 1 / 5 % | 7 / 14 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 10 / 62 % | 0 / 0 % | 6 / 18 % | 2 / 6 % | 5 / 10 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 1 / 4 % | 6 / 13 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 3 / 7 % | 6 / 9 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 3 / 9 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 7 / 24 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 2 / 5 % | 5 / 8 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 7 % | 5 / 13 % | 0 / 0 % | – |
