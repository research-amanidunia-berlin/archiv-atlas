[English](README.md) · [Deutsch](README.de.md)

# OpenAI o1 System Card

Bericht Q008641 · Quelle openai.com · Datum 2024-12-05 · [Original öffnen](https://openai.com/index/openai-o1-system-card/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet für o1 in vielen internen Sicherheitstests Verbesserungen gegenüber GPT-4o, nennt aber auch Risiken: In gezielten Szenarien zeigten externe Prüfende Täuschungs- und Überwachungsumgehungsverhalten, und das Modell kann Fachleute bei biologischen Bedrohungsplanungen unterstützen. Die Karte stuft o1 insgesamt als mittleres Risiko ein und betont, dass ihre Tests mögliche Risiken nur begrenzt abdecken und Produktionsleistungen abweichen können.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 65 / 79 % | 99 / 100 % | 100 / 100 % | 79 / 89 % | 54 / 72 % | 77 / 87 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 67 / 79 % | 100 / 100 % | 100 / 100 % | 89 / 94 % | 22 / 40 % | 77 / 87 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 62 / 75 % | 100 / 100 % | 100 / 100 % | 83 / 90 % | 62 / 78 % | 84 / 90 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 54 / 69 % | 97 / 100 % | 100 / 100 % | 83 / 90 % | 42 / 69 % | 80 / 89 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 57 / 75 % | 99 / 100 % | 95 / 98 % | 85 / 91 % | 32 / 52 % | 81 / 89 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 33 / 52 % | 99 / 100 % | 96 / 99 % | 59 / 80 % | 26 / 49 % | 50 / 67 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 51 / 67 % | 85 / 95 % | 99 / 100 % | 81 / 90 % | 15 / 36 % | 56 / 69 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 49 / 69 % | 99 / 100 % | 97 / 98 % | 75 / 87 % | 55 / 76 % | 82 / 91 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 41 / 64 % | 99 / 100 % | 94 / 97 % | 64 / 82 % | 12 / 30 % | 42 / 62 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 54 / 72 % | 98 / 99 % | 96 / 98 % | 85 / 91 % | 64 / 80 % | 90 / 94 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 29 / 53 % | 98 / 100 % | 91 / 95 % | 50 / 71 % | 11 / 25 % | 44 / 62 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 35 / 55 % | 66 / 97 % | 95 / 98 % | 71 / 85 % | 19 / 36 % | 15 / 32 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 23 / 41 % | 95 / 99 % | 72 / 76 % | 53 / 71 % | 17 / 29 % | 37 / 49 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 44 / 67 % | 93 / 98 % | 88 / 94 % | 80 / 89 % | 41 / 63 % | 73 / 85 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 80 / 97 % | 66 / 82 % | 19 / 42 % | 3 / 9 % | 7 / 14 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 77 / 98 % | 42 / 60 % | 13 / 32 % | 3 / 12 % | 12 / 23 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 24 / 48 % | 76 / 99 % | 16 / 35 % | 38 / 61 % | 8 / 20 % | 31 / 45 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 71 / 96 % | 43 / 69 % | 16 / 34 % | 4 / 13 % | 12 / 20 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 67 / 94 % | 39 / 62 % | 12 / 33 % | 3 / 12 % | 10 / 21 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 14 / 30 % | 4 / 22 % | 60 / 81 % | 20 / 44 % | 5 / 15 % | 10 / 20 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 33 / 54 % | 42 / 96 % | 58 / 75 % | 34 / 61 % | 10 / 23 % | 29 / 46 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 27 / 51 % | 53 / 83 % | 25 / 50 % | 20 / 42 % | 11 / 23 % | 22 / 39 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 29 / 51 % | 0 / 0 % | 0 / 0 % | 49 / 72 % | 12 / 31 % | 26 / 39 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 45 / 67 % | 0 / 0 % | 14 / 31 % | 0 / 0 % | 9 / 16 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 39 / 84 % | 16 / 27 % | 20 / 42 % | 5 / 13 % | 8 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 27 / 93 % | 24 / 46 % | 37 / 60 % | 5 / 13 % | 11 / 21 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 31 / 57 % | 0 / 0 % | 0 / 0 % | 24 / 52 % | 8 / 23 % | 34 / 55 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 33 / 94 % | 2 / 19 % | 11 / 25 % | 3 / 10 % | 6 / 12 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 32 / 97 % | 0 / 0 % | 7 / 16 % | 2 / 8 % | 5 / 8 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 30 / 72 % | 31 / 60 % | 11 / 28 % | 3 / 9 % | 9 / 20 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 19 / 51 % | 0 / 0 % | 14 / 39 % | 5 / 15 % | 12 / 20 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 29 % | 1 / 5 % | 7 / 15 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 25 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 0 / 0 % | 7 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 3 / 10 % | 6 / 13 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 7 / 23 % | 9 / 21 % | 3 / 11 % | 0 / 0 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 8 / 12 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 8 / 65 % | 0 / 0 % | 7 / 18 % | 2 / 10 % | 6 / 11 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 2 / 6 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 7 / 15 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 4 % | 7 / 11 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | – | – |
