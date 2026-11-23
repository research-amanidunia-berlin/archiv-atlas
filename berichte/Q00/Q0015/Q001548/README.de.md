[English](README.md) · [Deutsch](README.de.md)

# Pacing model development in an era of cyber-critical capabilities

Bericht Q001548 · Quelle openai.com · Datum 2026-08-18 · [Original öffnen](https://openai.com/index/pacing-model-development-cyber-capabilities/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt verschärfte Sicherheitsmaßnahmen, nachdem es Hinweise auf mögliche kritische Cyberfähigkeiten des Modells Astra und einen Sicherheitsvorfall gegeben habe. Dazu zählen pausierte Trainingsläufe, stärker abgesicherte Forschungsumgebungen, erweiterte Überwachung und zusätzliche Alignment-Arbeit; die Wirksamkeit wird im Bericht nicht unabhängig geprüft.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 48 / 69 % | 100 / 100 % | 100 / 100 % | 84 / 90 % | 80 / 89 % | 89 / 93 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 30 / 55 % | 99 / 100 % | 100 / 100 % | 71 / 86 % | 60 / 73 % | 74 / 84 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 46 / 64 % | 94 / 98 % | 100 / 100 % | 80 / 89 % | 27 / 51 % | 55 / 71 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 56 / 73 % | 100 / 100 % | 100 / 100 % | 87 / 92 % | 83 / 93 % | 82 / 90 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 68 / 82 % | 99 / 100 % | 100 / 100 % | 90 / 94 % | 84 / 93 % | 92 / 95 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 39 / 62 % | 99 / 100 % | 99 / 100 % | 67 / 83 % | 54 / 77 % | 74 / 85 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 46 / 67 % | 80 / 88 % | 99 / 100 % | 80 / 89 % | 61 / 81 % | 81 / 88 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 31 / 54 % | 81 / 99 % | 98 / 99 % | 66 / 83 % | 45 / 71 % | 68 / 83 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 45 % | 92 / 98 % | 94 / 97 % | 42 / 65 % | 13 / 27 % | 38 / 61 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 35 / 62 % | 92 / 100 % | 73 / 96 % | 53 / 78 % | 39 / 66 % | 64 / 84 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 79 / 94 % | 89 / 96 % | 51 / 75 % | 18 / 42 % | 13 / 27 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 46 / 66 % | 80 / 98 % | 79 / 93 % | 76 / 87 % | 76 / 89 % | 88 / 93 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 21 / 50 % | 87 / 98 % | 75 / 88 % | 27 / 51 % | 16 / 43 % | 45 / 60 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 80 / 92 % | 31 / 59 % | 32 / 57 % | 10 / 22 % | 19 / 39 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 50 / 79 % | 63 / 81 % | 9 / 26 % | 3 / 11 % | 0 / 0 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 24 / 54 % | 58 / 86 % | 58 / 90 % | 17 / 40 % | 28 / 53 % | 42 / 65 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 54 / 83 % | 34 / 71 % | 9 / 27 % | 4 / 12 % | 7 / 20 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 22 / 36 % | 17 / 58 % | 46 / 72 % | 31 / 61 % | 7 / 18 % | 21 / 43 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 40 / 86 % | 12 / 26 % | 14 / 36 % | 8 / 20 % | 7 / 17 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 31 % | 0 / 0 % | 39 / 72 % | 15 / 41 % | 6 / 19 % | 7 / 18 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 38 / 58 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 35 / 79 % | 0 / 0 % | 6 / 15 % | 4 / 11 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 1 / 24 % | 34 / 65 % | 13 / 32 % | 6 / 14 % | 19 / 35 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 10 / 27 % | 34 / 95 % | 9 / 53 % | 14 / 34 % | 7 / 20 % | 8 / 21 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 39 % | 14 / 53 % | 9 / 34 % | 21 / 50 % | 10 / 28 % | 32 / 50 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 20 / 47 % | 6 / 37 % | 20 / 48 % | 3 / 11 % | 25 / 45 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 13 / 46 % | 25 / 46 % | 15 / 41 % | 20 / 44 % | 9 / 26 % | 12 / 24 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 24 / 71 % | 3 / 21 % | 8 / 21 % | 1 / 5 % | 7 / 14 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 19 / 71 % | 16 / 35 % | 10 / 28 % | 3 / 11 % | 10 / 22 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 17 / 52 % | 2 / 23 % | 9 / 23 % | 6 / 15 % | 10 / 20 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 7 / 40 % | 11 / 32 % | 6 / 17 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 2 % | 10 / 17 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 2 / 7 % | 9 / 15 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 1 / 7 % | 8 / 21 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 8 / 42 % | 0 / 0 % | 6 / 20 % | 3 / 11 % | 8 / 14 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 8 / 17 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 1 / 5 % | 5 / 11 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 7 / 42 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 5 / 9 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 2 / 48 % | 0 / 0 % | 6 / 16 % | 3 / 10 % | 5 / 12 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 2 % | 4 / 7 % | – | – |
