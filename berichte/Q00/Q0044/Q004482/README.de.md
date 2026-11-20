[English](README.md) · [Deutsch](README.de.md)

# Securing internal systems against increasingly capable and imperfectly aligned AI

Bericht Q004482 · Quelle deepmind.google · Datum 2026-06-18 · [Original öffnen](https://deepmind.google/blog/securing-the-future-of-ai-agents/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

DeepMind beschreibt ein mehrschichtiges Kontrollkonzept, das interne KI-Agenten überwacht, ihre Berechtigungen schrittweise vergibt und riskante Handlungen je nach möglichem Schaden nachträglich prüft oder in Echtzeit blockiert. Das Unternehmen berichtet von einer Analyse einer Million Programmieragenten-Aufgaben; die meisten markierten Fälle seien durch Fehlinterpretationen oder Übereifer entstanden, doch der Beitrag bietet keine unabhängige Wirksamkeitsbewertung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 54 / 69 % | 99 / 100 % | 85 / 94 % | 100 / 100 % | 86 / 93 % | 84 / 93 % | 85 / 93 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 63 / 79 % | 100 / 100 % | 98 / 99 % | 100 / 100 % | 89 / 94 % | 87 / 94 % | 85 / 91 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 33 / 54 % | 95 / 99 % | 41 / 65 % | 82 / 96 % | 66 / 83 % | 33 / 57 % | 42 / 65 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 37 / 58 % | 88 / 96 % | 54 / 76 % | 94 / 98 % | 56 / 78 % | 44 / 65 % | 61 / 78 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 37 / 54 % | 93 / 100 % | 27 / 55 % | 82 / 96 % | 57 / 79 % | 42 / 65 % | 59 / 79 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 53 / 70 % | 73 / 92 % | 80 / 89 % | 92 / 98 % | 76 / 87 % | 76 / 87 % | 87 / 93 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 42 / 61 % | 71 / 94 % | 49 / 67 % | 91 / 96 % | 75 / 87 % | 71 / 84 % | 89 / 94 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 22 / 78 % | 12 / 32 % | 82 / 96 % | 44 / 69 % | 9 / 30 % | 24 / 44 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 25 / 50 % | 54 / 90 % | 17 / 47 % | 74 / 94 % | 11 / 25 % | 24 / 48 % | 41 / 69 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 73 / 89 % | 21 / 38 % | 71 / 88 % | 45 / 70 % | 10 / 23 % | 33 / 50 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 43 / 81 % | 0 / 0 % | 70 / 86 % | 10 / 30 % | 4 / 14 % | 8 / 15 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 15 / 30 % | 68 / 96 % | 6 / 19 % | 10 / 22 % | 9 / 26 % | 5 / 14 % | 7 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 22 / 45 % | 62 / 85 % | 17 / 33 % | 63 / 76 % | 52 / 75 % | 19 / 43 % | 54 / 74 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 30 % | 10 / 43 % | 4 / 17 % | 54 / 77 % | 21 / 49 % | 6 / 23 % | 12 / 33 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 14 / 33 % | 53 / 96 % | 7 / 30 % | 15 / 62 % | 26 / 51 % | 7 / 20 % | 12 / 36 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 17 / 31 % | 50 / 84 % | 4 / 13 % | 28 / 53 % | 23 / 50 % | 6 / 17 % | 15 / 30 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 48 / 93 % | 1 / 8 % | 18 / 36 % | 14 / 35 % | 8 / 22 % | 7 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 47 / 83 % | 1 / 7 % | 19 / 48 % | 9 / 24 % | 4 / 16 % | 6 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 15 / 40 % | 40 / 87 % | 1 / 8 % | 15 / 39 % | 13 / 34 % | 4 / 18 % | 11 / 24 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 13 / 71 % | 2 / 7 % | 36 / 68 % | 26 / 53 % | 6 / 20 % | 10 / 23 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 14 / 32 % | 22 / 71 % | 2 / 10 % | 36 / 58 % | 10 / 27 % | 5 / 12 % | 14 / 32 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 26 / 92 % | 0 / 5 % | 1 / 12 % | 6 / 15 % | 4 / 14 % | 6 / 15 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 22 / 76 % | 0 / 0 % | 11 / 43 % | 5 / 12 % | 1 / 5 % | 2 / 4 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 23 % | 22 / 89 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 3 / 15 % | 6 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 20 / 75 % | 3 / 13 % | 18 / 49 % | 21 / 52 % | 5 / 15 % | 14 / 31 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 19 / 76 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 2 / 7 % | 4 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 16 / 76 % | 3 / 12 % | 9 / 32 % | 13 / 35 % | 3 / 10 % | 5 / 13 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 1 / 5 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 10 / 69 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 10 / 60 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 4 / 10 % | 2 / 4 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 5 / 52 % | 2 / 7 % | 0 / 0 % | 9 / 25 % | 5 / 16 % | 8 / 28 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 9 / 77 % | 0 / 3 % | 1 / 13 % | 7 / 23 % | 2 / 9 % | 9 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 6 / 13 % | 2 / 8 % | 8 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 1 / 31 % | 0 / 0 % | 8 / 29 % | 7 / 16 % | 3 / 12 % | 6 / 13 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 7 / 91 % | 0 / 3 % | 2 / 17 % | 7 / 17 % | 3 / 12 % | 5 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 6 / 62 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 5 % | 2 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 2 % | 3 / 7 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 3 / 52 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 7 % | 5 / 8 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 21 % | 0 / 0 % | 5 / 12 % | 2 / 4 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 5 / 12 % |
