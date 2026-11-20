[English](README.md) · [Deutsch](README.de.md)

# Artificial Intelligence, Values and Alignment

Bericht Q004849 · Quelle deepmind.google · Datum 2020-01-13 · [Original öffnen](https://deepmind.google/blog/artificial-intelligence-values-and-alignment/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht fragt, welche Werte KI leiten sollten, und argumentiert, dass technische Umsetzung oder die Übernahme menschlicher Präferenzen allein dafür nicht ausreichen. Gabriel skizziert drei vorläufige Wege zu breit akzeptierten Prinzipien: gemeinsamen moralischen Konsens, unparteiige Wahl unter einem „Schleier des Nichtwissens“ und demokratische Verfahren; der Quelltext endet in einer unvollständigen Bildbeschreibung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 36 / 59 % | 91 / 99 % | 25 / 79 % | 64 / 96 % | 48 / 78 % | 20 / 56 % | 34 / 73 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 26 / 52 % | 82 / 95 % | 20 / 62 % | 65 / 93 % | 38 / 67 % | 13 / 41 % | 20 / 55 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 20 / 49 % | 70 / 98 % | 4 / 37 % | 68 / 95 % | 30 / 65 % | 7 / 31 % | 10 / 44 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 21 / 48 % | 60 / 88 % | 35 / 74 % | 57 / 91 % | 37 / 71 % | 24 / 58 % | 25 / 67 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 15 / 46 % | 56 / 92 % | 4 / 23 % | 33 / 88 % | 25 / 55 % | 6 / 28 % | 9 / 31 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 5 / 24 % | 9 / 54 % | 0 / 3 % | 0 / 0 % | 44 / 71 % | 1 / 7 % | 3 / 8 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 9 / 36 % | 20 / 78 % | 5 / 29 % | 44 / 72 % | 16 / 46 % | 7 / 36 % | 19 / 56 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 30 % | 38 / 91 % | 1 / 6 % | 3 / 22 % | 9 / 34 % | 4 / 18 % | 7 / 22 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 24 / 52 % | 30 / 79 % | 6 / 41 % | 15 / 59 % | 22 / 58 % | 13 / 43 % | 25 / 61 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 10 / 38 % | 29 / 77 % | 0 / 3 % | 0 / 12 % | 6 / 19 % | 0 / 2 % | 4 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 13 / 30 % | 28 / 88 % | 0 / 0 % | 3 / 33 % | 6 / 18 % | 0 / 0 % | 4 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 21 / 52 % | 0 / 4 % | 0 / 6 % | 5 / 13 % | 1 / 8 % | 4 / 12 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 9 / 36 % | 20 / 90 % | 4 / 29 % | 12 / 59 % | 12 / 41 % | 4 / 22 % | 7 / 26 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 35 % | 20 / 92 % | 1 / 6 % | 0 / 12 % | 8 / 31 % | 2 / 15 % | 6 / 19 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 14 / 40 % | 8 / 45 % | 0 / 5 % | 0 / 0 % | 5 / 20 % | 1 / 6 % | 4 / 11 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 12 / 67 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 3 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | 4 / 8 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 11 / 86 % | 0 / 0 % | 1 / 25 % | 5 / 14 % | 0 / 1 % | 4 / 8 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 10 / 30 % | 1 / 47 % | 0 / 3 % | 0 / 0 % | 5 / 12 % | 0 / 1 % | 3 / 5 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 8 / 26 % | 10 / 66 % | 0 / 4 % | 0 / 0 % | 5 / 13 % | 0 / 3 % | 5 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 9 / 90 % | 0 / 2 % | 0 / 6 % | 5 / 15 % | 1 / 8 % | 3 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 8 / 44 % | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | 1 / 3 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 8 / 42 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 5 / 16 % | 0 / 3 % | 1 / 2 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 7 / 73 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 0 / 2 % | 2 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 7 / 42 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 4 / 23 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 6 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 6 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 3 / 7 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 6 / 63 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 6 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 3 / 7 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 5 / 30 % | 2 / 69 % | 0 / 3 % | 0 / 24 % | 5 / 18 % | 0 / 4 % | 2 / 6 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 3 / 7 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 2 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 4 / 45 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 4 / 8 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 2 / 4 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 77 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % |
