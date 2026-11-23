[English](README.md) · [Deutsch](README.de.md)

# Expanding on how Voice Engine works and our safety research

Bericht Q001951 · Quelle openai.com · Datum 2024-06-07 · [Original öffnen](https://openai.com/index/expanding-on-how-voice-engine-works-and-our-safety-research/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI zufolge kann Voice Engine aus einer 15-sekündigen Sprachprobe und Text eine ähnlich klingende Stimme erzeugen; das Verfahren werde nicht für einzelne Personen nachtrainiert. Das Unternehmen beschreibt begrenzte Einsätze und Schutzvorgaben wie Zustimmung, Offenlegung und Wasserzeichen, räumt Risiken synthetischer Stimmen ein und kündigt für GPT‑4o zunächst nur vorgegebene Stimmen an. Die Wirksamkeit der Maßnahmen wird im Bericht nicht unabhängig belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 43 % | 72 / 93 % | 99 / 100 % | 54 / 75 % | 24 / 45 % | 47 / 67 % | 27 / 46 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 21 / 39 % | 75 / 91 % | 97 / 99 % | 29 / 51 % | 12 / 26 % | 26 / 45 % | 11 / 23 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 68 / 93 % | 95 / 98 % | 31 / 57 % | 18 / 33 % | 40 / 54 % | 11 / 19 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 70 / 91 % | 95 / 97 % | 12 / 35 % | 5 / 15 % | 14 / 30 % | 1 / 5 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 27 / 59 % | 92 / 97 % | 20 / 44 % | 6 / 17 % | 10 / 23 % | 6 / 15 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 70 / 90 % | 92 / 97 % | 19 / 43 % | 11 / 27 % | 19 / 38 % | 18 / 27 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 23 / 43 % | 85 / 99 % | 91 / 97 % | 28 / 56 % | 16 / 37 % | 31 / 57 % | 10 / 23 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 45 / 59 % | 89 / 98 % | 91 / 96 % | 74 / 85 % | 66 / 78 % | 72 / 81 % | 86 / 91 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 22 / 41 % | 63 / 84 % | 85 / 92 % | 27 / 52 % | 9 / 25 % | 11 / 26 % | 6 / 15 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 40 / 74 % | 84 / 94 % | 10 / 27 % | 4 / 11 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 52 / 95 % | 84 / 93 % | 11 / 35 % | 2 / 13 % | 7 / 22 % | 1 / 4 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 22 / 51 % | 83 / 93 % | 26 / 50 % | 9 / 24 % | 15 / 28 % | 10 / 21 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 78 / 94 % | 9 / 27 % | 4 / 17 % | 8 / 22 % | 2 / 7 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 31 % | 0 / 0 % | 77 / 84 % | 15 / 43 % | 4 / 15 % | 12 / 29 % | 2 / 7 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 52 / 83 % | 73 / 89 % | 6 / 13 % | 1 / 4 % | 5 / 11 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 41 / 73 % | 72 / 84 % | 10 / 28 % | 2 / 8 % | 7 / 16 % | 0 / 0 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 72 / 84 % | 4 / 19 % | 8 / 18 % | 2 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 54 / 89 % | 25 / 50 % | 6 / 13 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 51 / 93 % | 47 / 66 % | 6 / 18 % | 2 / 11 % | 5 / 13 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 45 / 81 % | 25 / 63 % | 10 / 25 % | 4 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 38 / 92 % | 29 / 73 % | 11 / 32 % | 3 / 15 % | 7 / 23 % | 1 / 4 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 34 / 67 % | 15 / 35 % | 5 / 15 % | 8 / 19 % | 1 / 4 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 21 / 52 % | 33 / 59 % | 12 / 34 % | 5 / 15 % | 7 / 17 % | 2 / 7 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 32 / 77 % | 15 / 49 % | 12 / 30 % | 3 / 11 % | 8 / 19 % | 1 / 4 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 20 / 87 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 19 / 43 % | 10 / 27 % | 2 / 7 % | 6 / 15 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 26 % | 11 / 23 % | 11 / 20 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 23 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 2 / 7 % | 7 / 17 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 7 % | 7 / 16 % | 1 / 4 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | – |
