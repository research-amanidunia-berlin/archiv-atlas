[English](README.md) · [Deutsch](README.de.md)

# What are the tools for implementing trustworthy AI? A comparative framework and database

Bericht Q006625 · Quelle oecd.ai · Datum 2021-05-25 · [Original öffnen](https://oecd.ai/en/wonk/tools-for-trustworthy-ai)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt einen OECD-Rahmen, der technische, verfahrensbezogene und bildungsorientierte Werkzeuge zur Umsetzung vertrauenswürdiger KI anhand von sieben Dimensionen vergleichbar machen soll. Er wurde mit vier unterschiedlichen Beispielen erprobt; die angekündigte Datenbank sollte Werkzeuge zugänglich machen, doch der Rahmen bewertet ausdrücklich weder deren Qualität noch Vollständigkeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 34 / 57 % | 64 / 97 % | 72 / 96 % | 55 / 79 % | 23 / 51 % | 41 / 71 % | 31 / 74 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 27 / 57 % | 63 / 94 % | 67 / 92 % | 62 / 83 % | 21 / 51 % | 40 / 73 % | 24 / 67 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 13 / 30 % | 25 / 84 % | 54 / 73 % | 9 / 25 % | 0 / 0 % | 4 / 12 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 13 / 35 % | 47 / 82 % | 0 / 0 % | 9 / 31 % | 2 / 10 % | 12 / 41 % | 1 / 8 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 10 / 33 % | 47 / 95 % | 14 / 51 % | 16 / 44 % | 7 / 32 % | 13 / 55 % | 2 / 13 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 20 / 47 % | 43 / 86 % | 23 / 58 % | 28 / 57 % | 9 / 30 % | 24 / 54 % | 3 / 19 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 10 / 28 % | 27 / 59 % | 2 / 39 % | 16 / 46 % | 5 / 17 % | 11 / 33 % | 3 / 18 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 27 / 70 % | 2 / 24 % | 9 / 29 % | 0 / 0 % | 6 / 22 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 26 / 87 % | 3 / 27 % | 10 / 30 % | 1 / 5 % | 6 / 13 % | 0 / 3 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 30 % | 23 / 91 % | 2 / 19 % | 11 / 34 % | 8 / 28 % | 10 / 37 % | 3 / 19 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 29 % | 22 / 95 % | 14 / 43 % | 10 / 33 % | 3 / 14 % | 8 / 35 % | 0 / 5 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 21 / 54 % | 4 / 16 % | 8 / 32 % | 2 / 12 % | 7 / 22 % | 0 / 5 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 21 / 68 % | 3 / 35 % | 8 / 21 % | 2 / 10 % | 7 / 19 % | 1 / 7 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 19 / 81 % | 2 / 41 % | 8 / 26 % | 1 / 7 % | 5 / 13 % | 0 / 3 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 7 / 29 % | 8 / 61 % | 5 / 38 % | 18 / 47 % | 6 / 24 % | 10 / 43 % | 4 / 18 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 16 / 37 % | 6 / 62 % | 0 / 0 % | 13 / 49 % | 8 / 25 % | 11 / 40 % | 5 / 25 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 15 / 87 % | 7 / 29 % | 10 / 33 % | 2 / 10 % | 5 / 12 % | 1 / 6 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 14 / 53 % | 14 / 38 % | 13 / 48 % | 8 / 27 % | 15 / 43 % | 2 / 12 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 13 / 62 % | 0 / 9 % | 0 / 0 % | 2 / 7 % | 5 / 12 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 13 / 81 % | 0 / 0 % | 6 / 18 % | 0 / 2 % | 4 / 9 % | 0 / 2 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 12 / 64 % | 8 / 48 % | 8 / 42 % | 2 / 14 % | 6 / 24 % | 1 / 8 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 9 / 39 % | 6 / 46 % | 0 / 0 % | 10 / 33 % | 2 / 9 % | 6 / 17 % | 2 / 10 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 9 / 70 % | 0 / 0 % | 5 / 15 % | 1 / 5 % | 2 / 4 % | 0 / 2 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 6 / 31 % | 8 / 81 % | 1 / 21 % | 6 / 22 % | 1 / 9 % | 6 / 23 % | 0 / 4 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 1 / 5 % | 6 / 17 % | 0 / 3 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 1 / 11 % | 7 / 16 % | 1 / 5 % | 4 / 8 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 34 % | 0 / 0 % | 5 / 14 % | 1 / 8 % | 7 / 21 % | 0 / 3 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 7 / 33 % | 0 / 0 % | 0 / 3 % | 6 / 18 % | 1 / 6 % | 5 / 13 % | 0 / 3 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 3 / 17 % | 6 / 20 % | 1 / 5 % | 7 / 16 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 5 / 45 % | 0 / 0 % | 6 / 19 % | 1 / 6 % | 5 / 11 % | 0 / 5 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 4 / 38 % | 0 / 0 % | 6 / 18 % | 1 / 5 % | 4 / 9 % | 0 / 2 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 2 / 18 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 5 / 10 % | 0 / 2 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 4 / 10 % | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 7 % | 4 / 9 % | 0 / 1 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 5 / 79 % | 0 / 7 % | 5 / 18 % | 1 / 7 % | 3 / 13 % | 0 / 3 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 3 / 8 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 3 / 6 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | – |
