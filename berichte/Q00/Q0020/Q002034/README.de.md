[English](README.md) · [Deutsch](README.de.md)

# Evaluating social and ethical risks from generative AI

Bericht Q002034 · Quelle deepmind.google · Datum 2023-10-19 · [Original öffnen](https://deepmind.google/blog/evaluating-social-and-ethical-risks-from-generative-ai/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag schlägt vor, generative KI auf drei Ebenen zu prüfen: nach ihren Fähigkeiten, der Nutzung durch Menschen und ihren systemischen Folgen. Eine Sichtung bestehender Prüfungen zeige laut Autorinnen und Autoren Lücken bei Kontext, abgedeckten Risiken und nichttextlichen Modalitäten; sie empfehlen daher umfassendere, gemeinsam getragene Bewertungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 57 % | 58 / 96 % | 23 / 66 % | 91 / 98 % | 40 / 73 % | 17 / 46 % | 32 / 68 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 7 / 34 % | 85 / 99 % | 12 / 43 % | 15 / 64 % | 14 / 41 % | 8 / 31 % | 9 / 37 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 11 / 38 % | 69 / 99 % | 7 / 24 % | 54 / 90 % | 17 / 44 % | 8 / 22 % | 14 / 32 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 22 / 53 % | 60 / 98 % | 29 / 77 % | 52 / 93 % | 25 / 63 % | 18 / 51 % | 30 / 69 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 11 / 39 % | 9 / 87 % | 6 / 39 % | 57 / 89 % | 19 / 52 % | 8 / 31 % | 12 / 45 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 15 / 45 % | 50 / 92 % | 13 / 44 % | 57 / 90 % | 14 / 39 % | 11 / 38 % | 16 / 55 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 14 / 45 % | 54 / 95 % | 12 / 44 % | 45 / 77 % | 18 / 47 % | 8 / 30 % | 11 / 37 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 13 / 54 % | 31 / 95 % | 13 / 62 % | 52 / 87 % | 22 / 54 % | 14 / 48 % | 22 / 60 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 7 / 39 % | 43 / 95 % | 1 / 11 % | 20 / 80 % | 12 / 44 % | 3 / 16 % | 10 / 33 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 11 / 41 % | 39 / 94 % | 2 / 13 % | 24 / 66 % | 13 / 36 % | 7 / 20 % | 12 / 33 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 13 / 38 % | 34 / 91 % | 16 / 60 % | 25 / 84 % | 24 / 57 % | 9 / 33 % | 21 / 58 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 31 / 87 % | 0 / 3 % | 12 / 45 % | 8 / 25 % | 1 / 7 % | 5 / 13 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 13 / 41 % | 10 / 67 % | 7 / 31 % | 30 / 63 % | 20 / 57 % | 9 / 31 % | 25 / 56 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 29 / 83 % | 0 / 4 % | 1 / 9 % | 6 / 21 % | 0 / 7 % | 7 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 22 / 69 % | 0 / 0 % | 27 / 63 % | 6 / 18 % | 1 / 9 % | 6 / 13 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 12 / 46 % | 23 / 95 % | 3 / 14 % | 22 / 74 % | 10 / 47 % | 3 / 23 % | 12 / 41 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 23 / 83 % | 0 / 2 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 6 / 15 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 4 / 84 % | 3 / 18 % | 12 / 54 % | 18 / 52 % | 4 / 22 % | 5 / 14 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 18 / 47 % | 1 / 5 % | 0 / 0 % | 6 / 18 % | 2 / 8 % | 5 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 17 / 73 % | 0 / 4 % | 2 / 29 % | 7 / 28 % | 1 / 7 % | 5 / 16 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 6 / 35 % | 14 / 97 % | 0 / 4 % | 0 / 12 % | 6 / 21 % | 2 / 12 % | 7 / 22 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 10 / 40 % | 12 / 96 % | 1 / 11 % | 6 / 48 % | 11 / 34 % | 5 / 22 % | 14 / 42 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 40 % | 13 / 95 % | 1 / 11 % | 10 / 57 % | 6 / 25 % | 2 / 14 % | 5 / 20 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 34 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 12 / 39 % | 8 / 95 % | 5 / 23 % | 6 / 33 % | 8 / 35 % | 6 / 19 % | 11 / 33 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 9 / 38 % | 12 / 90 % | 1 / 8 % | 1 / 24 % | 7 / 22 % | 2 / 12 % | 6 / 17 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 12 / 49 % | 0 / 0 % | 0 / 10 % | 5 / 13 % | 1 / 7 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 9 / 48 % | 10 / 81 % | 7 / 29 % | 5 / 31 % | 11 / 38 % | 7 / 25 % | 8 / 21 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 28 % | 11 / 92 % | 0 / 5 % | 11 / 40 % | 7 / 27 % | 4 / 15 % | 5 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 71 % | 0 / 2 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 5 / 12 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 8 / 35 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 5 / 11 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 7 / 43 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 0 / 0 % | 5 / 14 % | 1 / 11 % | 6 / 16 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 18 % | 1 / 8 % | 6 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 9 % | 6 / 13 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 2 / 69 % | 0 / 3 % | 0 / 5 % | 5 / 15 % | 2 / 9 % | 6 / 14 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 14 % | 5 / 14 % | 1 / 10 % | 5 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 14 % | 2 / 8 % | 4 / 9 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 4 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 5 / 12 % | 1 / 8 % | 5 / 15 % |
