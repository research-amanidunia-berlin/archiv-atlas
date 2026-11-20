[English](README.md) · [Deutsch](README.de.md)

# Addendum to GPT-6 Astra System Card: GPT-6.1 Sol

Bericht Q000065 · Quelle deploymentsafety.openai.com · Datum 2026-09-29 · [Original öffnen](https://deploymentsafety.openai.com/gpt-6-1-sol)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet, dass GPT-6.1 Sol GPT-6 Astra in vielen Sicherheits- und Gesundheitstests nahekommt oder GPT-6 Sol übertrifft; zugleich stuft es das Modell im Cyberbereich als „Critical“ und bei Bio-Chemie als „High“ ein. Einzelne Tests zeigen Schwächen und unerwünschte Beharrlichkeit; die oft adversarialen Ergebnisse sind laut Bericht nicht repräsentativ für durchschnittlichen Produktionsverkehr.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 64 / 80 % | 98 / 99 % | – | 100 / 100 % | 81 / 89 % | 80 / 88 % | 50 / 68 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 60 / 77 % | 100 / 100 % | – | 100 / 100 % | 84 / 90 % | 76 / 86 % | 64 / 78 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 56 / 73 % | 85 / 97 % | – | 100 / 100 % | 84 / 91 % | 72 / 86 % | 48 / 69 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 44 / 64 % | 78 / 97 % | – | 99 / 100 % | 82 / 90 % | 19 / 43 % | 26 / 42 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 68 / 81 % | 93 / 95 % | – | 98 / 99 % | 90 / 94 % | 67 / 81 % | 23 / 40 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 36 / 58 % | 96 / 99 % | – | 92 / 96 % | 72 / 85 % | 39 / 59 % | 17 / 36 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 50 / 68 % | 86 / 97 % | – | 94 / 96 % | 85 / 91 % | 89 / 93 % | 66 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 43 / 64 % | 93 / 99 % | – | 88 / 92 % | 71 / 85 % | 81 / 90 % | 55 / 72 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 52 / 71 % | 90 / 99 % | – | 79 / 91 % | 76 / 87 % | 70 / 84 % | 22 / 40 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 31 / 53 % | 85 / 97 % | – | 88 / 92 % | 40 / 66 % | 32 / 52 % | 13 / 26 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 43 / 66 % | 78 / 93 % | – | 31 / 43 % | 78 / 88 % | 80 / 88 % | 45 / 64 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 59 / 94 % | – | 71 / 85 % | 13 / 30 % | 9 / 20 % | 4 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 43 / 63 % | 34 / 79 % | – | 66 / 83 % | 66 / 83 % | 32 / 55 % | 10 / 24 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 65 / 79 % | 16 / 41 % | 5 / 12 % | 2 / 8 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 25 / 60 % | – | 60 / 74 % | 12 / 28 % | 8 / 15 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 58 / 87 % | – | 56 / 72 % | 27 / 54 % | 13 / 30 % | 5 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 19 / 36 % | 50 / 95 % | – | 38 / 58 % | 56 / 73 % | 33 / 47 % | 5 / 15 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 55 / 86 % | – | 34 / 58 % | 9 / 24 % | 5 / 10 % | 1 / 5 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 47 / 72 % | – | 20 / 40 % | 18 / 36 % | 9 / 19 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 39 / 70 % | – | 0 / 0 % | 8 / 20 % | 0 / 0 % | 2 / 8 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 38 / 75 % | – | 26 / 48 % | 12 / 29 % | 8 / 17 % | 3 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 38 / 91 % | – | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 16 / 42 % | 37 / 96 % | – | 4 / 16 % | 23 / 48 % | 28 / 50 % | 9 / 22 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 33 / 86 % | – | 5 / 29 % | 16 / 36 % | 6 / 13 % | 3 / 10 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 17 / 42 % | 32 / 90 % | – | 0 / 0 % | 15 / 40 % | 14 / 29 % | 6 / 14 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 31 / 66 % | – | 0 / 0 % | 6 / 14 % | 5 / 9 % | 1 / 5 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 21 / 53 % | 0 / 0 % | – | 0 / 0 % | 30 / 56 % | 12 / 24 % | 7 / 17 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 10 / 77 % | – | 28 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 25 / 61 % | 0 / 0 % | – | 0 / 0 % | 15 / 38 % | 22 / 50 % | 5 / 16 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 21 / 64 % | – | 0 / 0 % | 6 / 16 % | 4 / 9 % | 2 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 33 % | 10 / 51 % | – | 0 / 0 % | 10 / 28 % | 9 / 22 % | 4 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 28 % | 5 / 12 % | 1 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 11 / 51 % | – | 9 / 21 % | 9 / 24 % | 10 / 21 % | 3 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 19 % | 6 / 12 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 2 / 7 % |
