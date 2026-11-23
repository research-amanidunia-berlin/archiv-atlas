[English](README.md) · [Deutsch](README.de.md)

# Better language models and their implications

Bericht Q008626 · Quelle openai.com · Datum 2019-02-14 · [Original öffnen](https://openai.com/index/better-language-models/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet, GPT‑2 könne aus großen Mengen Webtext kohärente Fortsetzungen erzeugen und einige Sprachaufgaben ohne spezielles Training bearbeiten, mache dabei aber weiterhin deutliche Fehler und liege bei spezialisierten Aufgaben zurück. Wegen möglicher Anwendungen für Desinformation und missbräuchliche Inhalte beschreibt der Bericht zunächst eine eingeschränkte, später eine gestufte Veröffentlichung; die tatsächlichen gesellschaftlichen Auswirkungen bleiben darin offen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 99 / 100 % | 98 / 99 % | 37 / 64 % | 6 / 18 % | 26 / 43 % | 5 / 14 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 64 / 79 % | 99 / 99 % | 99 / 100 % | 80 / 89 % | 47 / 65 % | 73 / 81 % | 94 / 97 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 49 % | 73 / 94 % | 94 / 98 % | 36 / 64 % | 11 / 27 % | 45 / 65 % | 16 / 41 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 48 % | 54 / 91 % | 93 / 96 % | 16 / 47 % | 7 / 18 % | 37 / 62 % | 3 / 11 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 49 / 73 % | 93 / 97 % | 7 / 19 % | 0 / 5 % | 6 / 14 % | 0 / 4 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 63 / 99 % | 91 / 96 % | 13 / 37 % | 5 / 15 % | 14 / 30 % | 3 / 9 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 87 / 96 % | 87 / 93 % | 33 / 59 % | 14 / 28 % | 29 / 49 % | 10 / 21 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 40 / 76 % | 85 / 92 % | 9 / 24 % | 1 / 5 % | 6 / 14 % | 0 / 2 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 14 / 33 % | 75 / 91 % | 85 / 94 % | 14 / 40 % | 7 / 20 % | 19 / 47 % | 6 / 23 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 27 / 76 % | 83 / 94 % | 17 / 45 % | 4 / 10 % | 7 / 17 % | 2 / 7 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 16 / 47 % | 82 / 88 % | 17 / 46 % | 4 / 12 % | 26 / 45 % | 2 / 7 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 28 / 50 % | 81 / 96 % | 66 / 90 % | 57 / 78 % | 24 / 51 % | 59 / 77 % | 41 / 66 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 42 / 73 % | 75 / 85 % | 8 / 24 % | 3 / 10 % | 8 / 18 % | 1 / 5 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 15 / 33 % | 68 / 91 % | 74 / 86 % | 19 / 43 % | 6 / 17 % | 16 / 37 % | 4 / 12 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 74 / 95 % | 1 / 16 % | 9 / 26 % | 3 / 11 % | 11 / 26 % | 1 / 6 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 26 % | 72 / 91 % | 47 / 75 % | 8 / 27 % | 2 / 9 % | 11 / 24 % | 0 / 3 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 70 / 95 % | 67 / 89 % | 17 / 48 % | 4 / 13 % | 15 / 37 % | 2 / 8 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 70 / 84 % | 12 / 37 % | 3 / 10 % | 12 / 26 % | 3 / 9 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 32 % | 5 / 42 % | 68 / 85 % | 17 / 45 % | 7 / 18 % | 18 / 46 % | 5 / 17 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 55 / 88 % | 0 / 0 % | 6 / 14 % | 3 / 7 % | 6 / 14 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 15 / 33 % | 54 / 90 % | 20 / 48 % | 20 / 51 % | 3 / 11 % | 22 / 37 % | 1 / 5 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 45 / 80 % | 22 / 50 % | 12 / 31 % | 3 / 12 % | 16 / 30 % | 1 / 5 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 15 / 37 % | 44 / 81 % | 44 / 77 % | 15 / 39 % | 5 / 14 % | 12 / 29 % | 3 / 13 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 44 / 82 % | 16 / 59 % | 9 / 26 % | 0 / 0 % | 7 / 20 % | 1 / 6 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 41 / 93 % | 14 / 35 % | 23 / 45 % | 7 / 18 % | 19 / 30 % | 3 / 7 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 11 / 43 % | 40 / 61 % | 9 / 26 % | 1 / 8 % | 7 / 21 % | 1 / 6 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 31 / 61 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 7 / 15 % | 0 / 3 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 28 / 72 % | 0 / 0 % | 6 / 14 % | 2 / 8 % | 11 / 21 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 24 / 63 % | 0 / 0 % | 12 / 34 % | 4 / 12 % | 13 / 29 % | 2 / 9 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 24 / 56 % | 0 / 0 % | 9 / 23 % | 1 / 4 % | 6 / 15 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 23 / 52 % | 2 / 16 % | 8 / 22 % | 2 / 9 % | 6 / 15 % | 0 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 23 / 73 % | 2 / 13 % | 7 / 20 % | 2 / 10 % | 7 / 18 % | 1 / 4 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 16 / 65 % | 0 / 0 % | 6 / 16 % | 1 / 5 % | 8 / 19 % | 1 / 4 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 16 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 10 / 49 % | 0 / 0 % | 6 / 16 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 17 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 2 / 9 % | 6 / 13 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 4 % | 7 / 18 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 4 % | 5 / 11 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 6 / 11 % | 0 / 0 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
