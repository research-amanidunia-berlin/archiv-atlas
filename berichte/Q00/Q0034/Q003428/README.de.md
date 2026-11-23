[English](README.md) · [Deutsch](README.de.md)

# Key Concepts in AI Safety: Robustness and Adversarial Examples

Bericht Q003428 · Quelle cset.georgetown.edu · Datum 2021-03-17 · [Original öffnen](https://cset.georgetown.edu/publication/key-concepts-in-ai-safety-robustness-and-adversarial-examples/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Text ist nur ein Auszug: Er erklärt in der Einleitung, dass maschinelle Lernsysteme in sicherheitskritischen Anwendungen zuverlässig mit unterschiedlichen Eingaben umgehen müssen, und beschreibt Training sowie die begrenzte Verallgemeinerungsfähigkeit von Modellen. Die angekündigten Erläuterungen zu adversarialen Beispielen und zum Sicherheitsansatz fehlen im Auszug.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 63 / 87 % | 5 / 12 % | 0 / 4 % | 0 / 0 % | 0 / 3 % | 15 / 30 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 24 / 46 % | 13 / 83 % | 48 / 91 % | 13 / 41 % | 1 / 11 % | 8 / 34 % | 4 / 34 % | 30 / 60 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 24 / 48 % | 13 / 93 % | 27 / 67 % | 10 / 41 % | 1 / 11 % | 7 / 27 % | 3 / 27 % | 35 / 61 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 28 / 80 % | 0 / 0 % | 6 / 18 % | 0 / 4 % | 3 / 10 % | 0 / 6 % | 5 / 28 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 22 / 81 % | 1 / 18 % | 5 / 16 % | 0 / 2 % | 3 / 8 % | 0 / 4 % | 3 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 22 / 62 % | 0 / 0 % | 6 / 18 % | 1 / 6 % | 3 / 12 % | 0 / 6 % | 4 / 26 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 20 / 67 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 2 / 5 % | 0 / 3 % | 2 / 23 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 17 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 15 / 74 % | 1 / 36 % | 6 / 23 % | 0 / 3 % | 4 / 12 % | 0 / 8 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 13 / 52 % | 4 / 48 % | 5 / 11 % | 1 / 6 % | 4 / 14 % | 1 / 13 % | 6 / 24 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 12 / 84 % | 1 / 33 % | 6 / 21 % | 0 / 4 % | 5 / 14 % | 0 / 4 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 12 / 52 % | 0 / 0 % | 6 / 23 % | 1 / 6 % | 6 / 19 % | 0 / 10 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 8 / 60 % | 0 / 6 % | 5 / 19 % | 0 / 6 % | 3 / 10 % | 0 / 8 % | 12 / 42 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 10 / 48 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 5 / 10 % | 0 / 3 % | 4 / 22 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 10 / 61 % | 0 / 0 % | 6 / 23 % | 1 / 8 % | 7 / 21 % | 0 / 5 % | 9 / 30 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 5 % | 6 / 17 % | 0 / 3 % | 10 / 38 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 6 / 14 % | 0 / 3 % | 2 / 19 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 0 / 0 % | 5 / 79 % | 0 / 0 % | 5 / 24 % | 1 / 6 % | 6 / 18 % | 1 / 10 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 6 / 13 % | 0 / 4 % | 5 / 24 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 2 % | 3 / 9 % | 0 / 2 % | 4 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 1 % | 2 / 4 % | 0 / 2 % | 4 / 27 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 2 / 4 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 3 / 5 % | 0 / 0 % | 2 / 22 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 1 % | 2 / 4 % | 0 / 2 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 1 / 23 % | 5 / 11 % | 0 / 3 % | 2 / 6 % | 0 / 4 % | 2 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 1 % | 3 / 5 % | 0 / 1 % | 3 / 20 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 0 / 2 % | 1 / 4 % | 0 / 0 % | 4 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 3 / 5 % | 0 / 0 % | 1 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 1 / 13 % |
