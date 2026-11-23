[English](README.md) · [Deutsch](README.de.md)

# How Third Moment Research runs 10,000 agents for 36+ hours

Bericht Q003195 · Quelle openai.com · Datum 2026-10-14 · [Original öffnen](https://openai.com/index/third-moment-research/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht schildert Third Moment Researchs Einsatz von OpenAI-Modellen, Codex und Daybreak, um bis zu 10.000 Agenten parallel an längeren Forschungsaufgaben arbeiten zu lassen. Das Unternehmen berichtet unter anderem von einem durch Codex beschleunigten Finanz-Backtest und plant den Ausbau auf Hunderttausende Teilagenten; die Erfolge und Kennzahlen sind im Text nicht unabhängig geprüft.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 40 / 60 % | 95 / 97 % | 100 / 100 % | 71 / 84 % | 35 / 62 % | 70 / 83 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 43 / 65 % | 96 / 99 % | 100 / 100 % | 80 / 89 % | 41 / 64 % | 74 / 84 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 24 / 43 % | 95 / 99 % | 82 / 90 % | 25 / 53 % | 15 / 32 % | 43 / 63 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 49 % | 26 / 90 % | 94 / 97 % | 38 / 64 % | 17 / 42 % | 40 / 64 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 19 / 47 % | 90 / 98 % | 92 / 96 % | 52 / 74 % | 24 / 50 % | 42 / 68 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 23 / 55 % | 92 / 96 % | 8 / 24 % | 0 / 0 % | 4 / 8 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 40 / 76 % | 75 / 82 % | 10 / 27 % | 1 / 5 % | 7 / 20 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 24 / 47 % | 22 / 75 % | 73 / 84 % | 51 / 72 % | 34 / 56 % | 59 / 74 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 22 / 69 % | 70 / 85 % | 27 / 51 % | 3 / 12 % | 10 / 22 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 18 / 41 % | 50 / 74 % | 38 / 60 % | 18 / 40 % | 13 / 31 % | 28 / 55 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 41 / 88 % | 37 / 63 % | 16 / 41 % | 3 / 10 % | 9 / 24 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 21 / 53 % | 0 / 0 % | 9 / 22 % | 0 / 2 % | 4 / 8 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 20 / 73 % | 0 / 0 % | 6 / 14 % | 0 / 2 % | 2 / 5 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 19 / 41 % | 13 / 44 % | 4 / 21 % | 10 / 32 % | 3 / 10 % | 7 / 18 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 11 / 34 % | 14 / 45 % | 0 / 0 % | 14 / 38 % | 6 / 15 % | 18 / 39 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 6 / 76 % | 0 / 0 % | 14 / 40 % | 4 / 16 % | 10 / 30 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 14 / 58 % | 0 / 0 % | 8 / 20 % | 1 / 6 % | 3 / 7 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 33 % | 0 / 0 % | 13 / 24 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 2 / 8 % | 4 / 9 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 10 / 47 % | 0 / 0 % | 0 / 0 % | 1 / 2 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 9 / 43 % | 0 / 0 % | 7 / 18 % | 1 / 5 % | 7 / 14 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | 4 / 9 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 2 / 7 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 8 / 64 % | 0 / 0 % | 6 / 17 % | 1 / 5 % | 3 / 9 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 1 % | 7 / 18 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 1 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 1 / 3 % | 4 / 7 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 1 % | 4 / 8 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 1 % | 0 / 0 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 2 % | 1 / 4 % | – | – |
