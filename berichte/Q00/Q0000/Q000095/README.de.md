[English](README.md) · [Deutsch](README.de.md)

# Developing Gemini 4 Argon responsibly and safely

Bericht Q000095 · Quelle blog.google · Datum 2026-10-13 · [Original öffnen](https://blog.google/innovation-and-ai/technology/safety-security/gemini-4-model-safety-security/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google stellt Gemini 4 Argon als leistungsfähigeres Modell für Cybersicherheit und andere komplexe Aufgaben vor und beschreibt Schutzmaßnahmen gegen Missbrauch, Fehlanpassung und Prompt Injection. Die genannten Testergebnisse und Beispiele stammen aus Googles eigener Darstellung; der Beitrag räumt ein, dass seltene Fehltritte bei sehr vielen Aufgaben weiterhin vorkommen können.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 41 / 60 % | 95 / 98 % | 64 / 83 % | 100 / 100 % | 74 / 87 % | 72 / 84 % | 80 / 87 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 51 / 67 % | 99 / 100 % | 90 / 94 % | 100 / 100 % | 85 / 91 % | 75 / 86 % | 85 / 91 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 58 / 71 % | 98 / 100 % | 85 / 93 % | 100 / 100 % | 88 / 93 % | 81 / 91 % | 88 / 93 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 66 / 80 % | 97 / 99 % | 91 / 96 % | 100 / 100 % | 89 / 94 % | 80 / 90 % | 80 / 87 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 46 / 62 % | 82 / 94 % | 61 / 79 % | 99 / 100 % | 41 / 58 % | 41 / 61 % | 74 / 84 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 50 / 66 % | 95 / 97 % | 75 / 86 % | 99 / 100 % | 89 / 93 % | 78 / 88 % | 94 / 96 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 34 / 53 % | 94 / 98 % | 73 / 82 % | 98 / 99 % | 81 / 90 % | 29 / 48 % | 66 / 77 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 30 / 51 % | 97 / 99 % | 25 / 44 % | 82 / 96 % | 66 / 82 % | 23 / 44 % | 48 / 66 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 21 / 41 % | 57 / 89 % | 7 / 18 % | 92 / 96 % | 36 / 60 % | 10 / 18 % | 32 / 49 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 38 / 71 % | 0 / 0 % | 87 / 93 % | 10 / 26 % | 3 / 9 % | 9 / 14 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 3 / 9 % | 84 / 93 % | 45 / 69 % | 10 / 20 % | 9 / 17 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 30 / 45 % | 50 / 80 % | 15 / 35 % | 82 / 93 % | 55 / 77 % | 11 / 25 % | 26 / 41 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 82 / 98 % | 2 / 7 % | 62 / 78 % | 17 / 38 % | 6 / 13 % | 11 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 39 / 58 % | 66 / 88 % | 74 / 82 % | 74 / 86 % | 79 / 88 % | 64 / 79 % | 81 / 87 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 54 / 89 % | 5 / 13 % | 71 / 89 % | 22 / 42 % | 11 / 26 % | 16 / 26 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 57 / 87 % | 1 / 5 % | 15 / 43 % | 19 / 43 % | 2 / 7 % | 12 / 25 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 17 / 40 % | 47 / 88 % | 1 / 7 % | 24 / 48 % | 15 / 38 % | 6 / 21 % | 16 / 34 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 24 % | 0 / 0 % | 0 / 4 % | 46 / 78 % | 12 / 33 % | 4 / 10 % | 6 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 18 / 30 % | 32 / 88 % | 1 / 4 % | 39 / 55 % | 23 / 47 % | 5 / 12 % | 13 / 22 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 15 / 50 % | 0 / 2 % | 37 / 58 % | 9 / 25 % | 4 / 10 % | 11 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 58 % | 1 / 4 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 15 / 53 % | 9 / 20 % | 34 / 55 % | 12 / 33 % | 4 / 9 % | 18 / 30 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 12 / 24 % | 33 / 85 % | 1 / 7 % | 13 / 55 % | 16 / 36 % | 4 / 11 % | 9 / 22 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 30 / 51 % | 8 / 18 % | 5 / 11 % | 11 / 20 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 30 / 89 % | 0 / 2 % | 1 / 6 % | 6 / 15 % | 3 / 8 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 28 / 40 % | 12 / 36 % | 4 / 13 % | 17 / 36 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 19 / 42 % | 17 / 44 % | 3 / 8 % | 12 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 2 / 8 % | 0 / 0 % | 19 / 42 % | 5 / 13 % | 10 / 19 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 42 % | 1 / 6 % | 16 / 40 % | 17 / 39 % | 10 / 21 % | 12 / 24 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 37 % | 0 / 0 % | 0 / 2 % | 2 / 9 % | 9 / 24 % | 3 / 11 % | 14 / 26 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 12 / 52 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 2 % | 5 / 9 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 11 / 63 % | 0 / 0 % | 8 / 16 % | 8 / 22 % | 5 / 12 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 6 / 10 % | 10 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 9 / 47 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 3 / 9 % | 6 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 53 % | 0 / 0 % | 2 / 14 % | 7 / 19 % | 2 / 5 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 3 % | 3 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 10 % | 0 / 0 % | 4 / 7 % | 6 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 4 / 8 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 3 / 6 % | 4 / 8 % |
