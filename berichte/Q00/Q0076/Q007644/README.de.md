[English](README.md) · [Deutsch](README.de.md)

# Working with US CAISI and UK AISI to build more secure AI systems

Bericht Q007644 · Quelle openai.com · Datum 2025-09-12 · [Original öffnen](https://openai.com/index/us-caisi-uk-aisi-ai-update/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet von gemeinsamen Sicherheitstests mit CAISI und UK AISI, bei denen Schwachstellen in ChatGPT Agent und Schutzmaßnahmen gegen biologischen Missbrauch gefunden und anschließend behoben oder verbessert worden seien. Die Tests boten den Instituten besondere interne Zugänge; der Bericht enthält keine unabhängige Gesamtmessung der daraus entstandenen Sicherheitsverbesserungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 71 / 84 % | 97 / 98 % | 100 / 100 % | 88 / 93 % | 89 / 93 % | 91 / 94 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 37 / 63 % | 98 / 100 % | 99 / 100 % | 62 / 81 % | 78 / 89 % | 84 / 91 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 35 / 62 % | 99 / 100 % | 97 / 99 % | 66 / 81 % | 39 / 60 % | 76 / 86 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 64 / 82 % | 98 / 99 % | 98 / 99 % | 88 / 93 % | 75 / 84 % | 85 / 91 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 39 / 62 % | 74 / 94 % | 95 / 99 % | 32 / 53 % | 61 / 78 % | 84 / 91 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 37 / 58 % | 93 / 97 % | 95 / 98 % | 65 / 80 % | 38 / 58 % | 53 / 67 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 53 % | 60 / 95 % | 94 / 98 % | 60 / 80 % | 24 / 54 % | 58 / 78 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 42 / 62 % | 88 / 96 % | 75 / 93 % | 70 / 84 % | 38 / 62 % | 71 / 84 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 29 / 50 % | 84 / 99 % | 61 / 77 % | 48 / 72 % | 13 / 39 % | 27 / 57 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 18 / 43 % | 76 / 90 % | 83 / 93 % | 53 / 72 % | 13 / 33 % | 34 / 56 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 21 / 46 % | 6 / 57 % | 83 / 95 % | 27 / 55 % | 16 / 43 % | 17 / 45 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 33 / 56 % | 66 / 90 % | 80 / 93 % | 68 / 84 % | 33 / 61 % | 75 / 87 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 23 / 41 % | 21 / 91 % | 77 / 88 % | 28 / 50 % | 16 / 28 % | 15 / 35 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 30 / 57 % | 65 / 96 % | 74 / 85 % | 49 / 74 % | 41 / 61 % | 27 / 49 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 23 / 47 % | 64 / 94 % | 61 / 88 % | 51 / 73 % | 30 / 51 % | 24 / 52 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 42 / 66 % | 62 / 91 % | 60 / 78 % | 31 / 55 % | 13 / 33 % | 13 / 29 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 60 / 89 % | 28 / 59 % | 16 / 36 % | 6 / 19 % | 18 / 35 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 13 / 44 % | 53 / 64 % | 39 / 65 % | 13 / 34 % | 43 / 65 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 28 / 93 % | 49 / 75 % | 44 / 68 % | 19 / 42 % | 20 / 44 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 32 % | 46 / 78 % | 2 / 11 % | 22 / 45 % | 9 / 26 % | 28 / 49 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 46 / 81 % | 34 / 58 % | 35 / 61 % | 13 / 31 % | 22 / 44 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 44 / 59 % | 3 / 9 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 11 / 35 % | 41 / 91 % | 23 / 54 % | 21 / 52 % | 9 / 32 % | 15 / 41 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 5 / 67 % | 41 / 57 % | 22 / 42 % | 6 / 21 % | 11 / 24 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 40 / 75 % | 15 / 40 % | 13 / 32 % | 7 / 24 % | 8 / 23 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 28 / 66 % | 21 / 40 % | 10 / 24 % | 3 / 13 % | 11 / 29 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 23 / 90 % | 23 / 43 % | 12 / 28 % | 9 / 25 % | 8 / 18 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 13 / 66 % | 0 / 0 % | 15 / 40 % | 11 / 34 % | 17 / 41 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 12 / 26 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 6 / 22 % | 16 / 36 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 16 / 65 % | 0 / 0 % | 7 / 17 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 16 / 41 % | 9 / 23 % | 7 / 14 % | 2 / 8 % | 5 / 8 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 9 / 20 % | 13 / 24 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 1 / 47 % | 1 / 15 % | 13 / 32 % | 7 / 24 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 13 / 52 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 4 / 39 % | 0 / 0 % | 11 / 25 % | 6 / 16 % | 12 / 27 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 16 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 4 / 12 % | 7 / 14 % | 3 / 11 % | 8 / 14 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 6 / 51 % | 5 / 22 % | 7 / 14 % | 3 / 9 % | 8 / 14 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 4 / 11 % | 6 / 11 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 8 % | 0 / 0 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 33 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – | – |
