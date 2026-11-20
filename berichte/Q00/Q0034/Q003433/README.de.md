[English](README.md) · [Deutsch](README.de.md)

# Key Concepts in AI Safety: An Overview

Bericht Q003433 · Quelle cset.georgetown.edu · Datum 2021-03-17 · [Original öffnen](https://cset.georgetown.edu/publication/key-concepts-in-ai-safety-an-overview/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug stellt KI-Sicherheit als technische Forschung zur Verringerung unbeabsichtigten Systemverhaltens vor und nennt fehlende Sicherheitsgarantien sowie mögliche Ausfälle in unbekannten Situationen als Herausforderung. Er unterscheidet Robustheit, Assurance und Spezifikation, behandelt aber Fragen der praktischen Einführung nicht weiter.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 27 / 60 % | 34 / 95 % | 12 / 64 % | 39 / 88 % | 19 / 58 % | 15 / 54 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 23 / 54 % | 38 / 92 % | 17 / 79 % | 32 / 90 % | 21 / 61 % | 12 / 54 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 32 / 84 % | 0 / 14 % | 0 / 29 % | 5 / 20 % | 5 / 14 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 25 / 80 % | 0 / 7 % | 1 / 30 % | 5 / 18 % | 4 / 13 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 24 / 90 % | 0 / 8 % | 0 / 6 % | 5 / 11 % | 3 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 23 / 69 % | 0 / 1 % | 0 / 15 % | 0 / 0 % | 4 / 8 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 18 / 56 % | 0 / 8 % | 23 / 64 % | 6 / 20 % | 4 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 22 / 66 % | 0 / 3 % | 0 / 0 % | 5 / 11 % | 1 / 5 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 20 / 54 % | 7 / 92 % | 2 / 35 % | 0 / 0 % | 11 / 44 % | 13 / 46 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 18 / 47 % | 19 / 91 % | 1 / 23 % | 0 / 0 % | 6 / 28 % | 6 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 41 % | 18 / 90 % | 0 / 6 % | 0 / 5 % | 5 / 16 % | 4 / 9 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 9 / 41 % | 17 / 96 % | 3 / 40 % | 1 / 37 % | 8 / 31 % | 5 / 17 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 7 / 38 % | 16 / 74 % | 1 / 20 % | 1 / 41 % | 6 / 17 % | 5 / 17 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 16 / 64 % | 0 / 4 % | 0 / 20 % | 5 / 16 % | 3 / 7 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 12 / 41 % | 15 / 67 % | 0 / 7 % | 1 / 20 % | 6 / 26 % | 6 / 19 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 15 / 59 % | 0 / 5 % | 0 / 0 % | 4 / 9 % | 3 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 15 / 91 % | 0 / 3 % | 0 / 0 % | 5 / 10 % | 3 / 5 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 14 / 80 % | 0 / 10 % | 0 / 18 % | 5 / 16 % | 4 / 10 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 14 / 83 % | 0 / 5 % | 0 / 21 % | 5 / 12 % | 3 / 7 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 14 / 75 % | 0 / 4 % | 0 / 0 % | 5 / 11 % | 3 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 12 / 58 % | 0 / 5 % | 0 / 0 % | 4 / 9 % | 4 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 43 % | 11 / 95 % | 1 / 22 % | 0 / 22 % | 7 / 28 % | 4 / 21 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 11 / 57 % | 0 / 6 % | 0 / 0 % | 5 / 17 % | 6 / 14 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 6 / 37 % | 10 / 93 % | 1 / 16 % | 1 / 38 % | 7 / 29 % | 5 / 14 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 10 / 49 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | 4 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 4 / 36 % | 8 / 95 % | 1 / 15 % | 0 / 21 % | 6 / 27 % | 4 / 21 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 8 / 46 % | 0 / 0 % | 0 / 6 % | 0 / 0 % | 5 / 15 % | 1 / 3 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 8 / 52 % | 0 / 3 % | 0 / 1 % | 5 / 11 % | 3 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 1 / 30 % | 0 / 4 % | 0 / 0 % | 5 / 11 % | 5 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 0 / 0 % | 5 / 11 % | 4 / 8 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 16 % | 5 / 11 % | 4 / 9 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 5 / 70 % | 0 / 3 % | 0 / 0 % | 4 / 10 % | 3 / 6 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 5 / 54 % | 0 / 4 % | 0 / 0 % | 5 / 13 % | 2 / 5 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 72 % | 0 / 3 % | 0 / 0 % | 5 / 12 % | 5 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 2 / 56 % | 0 / 4 % | 0 / 0 % | 5 / 15 % | 2 / 8 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 0 / 9 % | 1 / 23 % | 5 / 18 % | 4 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 3 / 79 % | 0 / 3 % | 0 / 6 % | 4 / 10 % | 3 / 8 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 3 / 75 % | 0 / 2 % | 0 / 0 % | 4 / 12 % | 3 / 9 % |
