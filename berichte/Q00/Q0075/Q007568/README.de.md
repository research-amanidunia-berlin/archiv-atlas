[English](README.md) · [Deutsch](README.de.md)

# Continuously hardening ChatGPT Atlas against prompt injection

Bericht Q007568 · Quelle openai.com · Datum 2025-12-22 · [Original öffnen](https://openai.com/index/hardening-atlas-against-prompt-injection/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet, dass ein automatisierter, mit Reinforcement Learning trainierter Angreifer neue Prompt-Injection-Methoden für den Atlas-Browser-Agenten aufgedeckt habe. Ein daraufhin trainiertes Update sei ausgerollt worden und habe im gezeigten Beispiel eine manipulierte E-Mail erkannt. Prompt Injection bleibt laut OpenAI ein ungelöstes Risiko; begrenzter Zugriff, sorgfältige Bestätigungen und klare Aufgaben können es mindern, aber nicht beseitigen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 46 / 67 % | 99 / 100 % | 100 / 100 % | 74 / 86 % | 32 / 56 % | 70 / 81 % | 79 / 93 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 53 % | 72 / 96 % | 99 / 100 % | 62 / 80 % | 25 / 49 % | 52 / 73 % | 20 / 50 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 35 / 53 % | 96 / 100 % | 92 / 97 % | 56 / 76 % | 18 / 38 % | 42 / 67 % | 10 / 28 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 49 % | 60 / 94 % | 95 / 99 % | 52 / 75 % | 44 / 65 % | 64 / 77 % | 44 / 73 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 33 % | 68 / 93 % | 93 / 96 % | 19 / 42 % | 7 / 18 % | 24 / 39 % | 2 / 7 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 0 / 0 % | 82 / 90 % | 13 / 32 % | 7 / 13 % | 13 / 29 % | 1 / 5 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 23 / 45 % | 9 / 73 % | 79 / 93 % | 30 / 55 % | 19 / 40 % | 26 / 48 % | 14 / 35 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 29 / 43 % | 61 / 89 % | 78 / 87 % | 22 / 42 % | 8 / 18 % | 28 / 44 % | 5 / 12 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 15 / 50 % | 71 / 90 % | 38 / 62 % | 8 / 21 % | 16 / 30 % | 6 / 18 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 51 / 80 % | 65 / 77 % | 45 / 70 % | 10 / 25 % | 48 / 68 % | 4 / 15 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 28 % | 56 / 95 % | 5 / 20 % | 22 / 45 % | 10 / 26 % | 32 / 49 % | 3 / 12 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 16 / 29 % | 38 / 72 % | 48 / 72 % | 17 / 43 % | 7 / 17 % | 10 / 18 % | 1 / 4 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 45 / 65 % | 7 / 15 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 32 / 78 % | 24 / 69 % | 17 / 44 % | 0 / 0 % | 11 / 22 % | 1 / 7 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 31 / 84 % | 0 / 0 % | 0 / 0 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 29 / 90 % | 7 / 43 % | 15 / 38 % | 4 / 15 % | 11 / 24 % | 0 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 8 / 64 % | 19 / 34 % | 27 / 52 % | 8 / 23 % | 12 / 28 % | 6 / 20 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 22 / 45 % | 7 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 22 / 41 % | 12 / 31 % | 3 / 8 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 14 / 37 % | 18 / 47 % | 3 / 10 % | 9 / 19 % | 2 / 9 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 3 / 71 % | 17 / 31 % | 0 / 0 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 15 / 36 % | 0 / 0 % | 3 / 18 % | 7 / 17 % | 3 / 11 % | 10 / 18 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 29 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 2 / 9 % | 10 / 19 % | 1 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 14 / 36 % | 7 / 14 % | 1 / 3 % | 5 / 9 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 13 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 6 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 35 % | 3 / 8 % | 6 / 10 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 12 / 26 % | 10 / 47 % | 1 / 14 % | 9 / 24 % | 5 / 13 % | 5 / 12 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 11 / 31 % | 5 / 12 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 9 / 35 % | 0 / 0 % | 5 / 13 % | 3 / 9 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 7 % | 8 / 16 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 47 % | 0 / 0 % | 6 / 13 % | 1 / 6 % | 7 / 12 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 9 % | 7 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 2 / 14 % | 6 / 12 % | 2 / 6 % | 5 / 8 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 3 / 5 % | 0 / 0 % | – |
