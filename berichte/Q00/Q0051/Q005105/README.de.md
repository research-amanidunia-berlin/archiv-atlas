[English](README.md) · [Deutsch](README.de.md)

# Holistic Safety and Responsibility Evaluations of Advanced AI Models

Bericht Q005105 · Quelle deepmind.google · Datum 2024-04-22 · [Original öffnen](https://deepmind.google/research/publications/78149/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Text ist nur der Abstract eines Berichts über Sicherheitsbewertungen bei der Entwicklung von Gemini. Die Autorinnen und Autoren betonen den Nutzen theoretischer Rahmenwerke und der Zusammenarbeit und plädieren für bessere wissenschaftliche Standards sowie die Einbindung von Evaluationen in Unternehmens- und öffentliche Politik; konkrete Verfahren oder Modellergebnisse nennt der Auszug nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 59 % | 62 / 95 % | 21 / 71 % | 55 / 97 % | 29 / 66 % | 19 / 58 % | 32 / 69 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 30 / 55 % | 53 / 96 % | 14 / 59 % | 51 / 92 % | 32 / 67 % | 9 / 41 % | 27 / 65 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 16 / 42 % | 36 / 89 % | 3 / 25 % | 47 / 85 % | 19 / 47 % | 8 / 24 % | 13 / 41 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 36 / 77 % | 1 / 10 % | 11 / 46 % | 11 / 34 % | 2 / 17 % | 8 / 32 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 27 / 61 % | 33 / 77 % | 15 / 62 % | 23 / 81 % | 14 / 42 % | 17 / 55 % | 29 / 64 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 29 / 56 % | 17 / 98 % | 6 / 41 % | 25 / 79 % | 26 / 63 % | 7 / 31 % | 23 / 57 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 29 / 88 % | 1 / 8 % | 11 / 61 % | 8 / 24 % | 1 / 4 % | 7 / 19 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 41 % | 28 / 58 % | 4 / 27 % | 20 / 63 % | 17 / 51 % | 4 / 26 % | 9 / 37 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 15 / 40 % | 27 / 81 % | 6 / 42 % | 18 / 73 % | 18 / 52 % | 6 / 28 % | 13 / 41 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 12 / 44 % | 25 / 70 % | 4 / 23 % | 1 / 33 % | 12 / 41 % | 3 / 15 % | 9 / 22 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 25 / 71 % | 0 / 8 % | 2 / 36 % | 8 / 25 % | 1 / 11 % | 7 / 20 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 24 / 51 % | 20 / 86 % | 3 / 29 % | 9 / 68 % | 15 / 54 % | 2 / 25 % | 10 / 41 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 20 / 72 % | 6 / 41 % | 23 / 76 % | 22 / 54 % | 4 / 24 % | 8 / 27 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 49 % | 21 / 62 % | 3 / 24 % | 8 / 55 % | 11 / 39 % | 4 / 18 % | 7 / 21 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 11 / 44 % | 20 / 85 % | 3 / 28 % | 6 / 65 % | 14 / 51 % | 3 / 22 % | 12 / 42 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 20 / 44 % | 8 / 91 % | 4 / 26 % | 8 / 46 % | 14 / 43 % | 4 / 19 % | 16 / 38 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 49 % | 18 / 57 % | 1 / 11 % | 0 / 0 % | 9 / 34 % | 0 / 8 % | 7 / 16 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 18 / 58 % | 0 / 0 % | 11 / 38 % | 8 / 23 % | 1 / 5 % | 4 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 43 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 18 / 67 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 3 % | 5 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 10 / 38 % | 16 / 63 % | 1 / 7 % | 13 / 38 % | 8 / 32 % | 3 / 18 % | 9 / 33 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 41 % | 15 / 55 % | 0 / 6 % | 0 / 10 % | 6 / 24 % | 1 / 11 % | 6 / 21 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 45 % | 7 / 20 % | 0 / 3 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 14 / 75 % | 1 / 14 % | 1 / 19 % | 8 / 26 % | 2 / 16 % | 7 / 22 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 10 / 74 % | 1 / 11 % | 6 / 41 % | 12 / 36 % | 3 / 20 % | 7 / 23 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 3 / 27 % | 1 / 12 % | 0 / 0 % | 7 / 28 % | 1 / 8 % | 8 / 23 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 18 % | 7 / 22 % | 1 / 8 % | 8 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 2 / 24 % | 1 / 7 % | 0 / 0 % | 6 / 18 % | 1 / 8 % | 7 / 18 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 7 / 19 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 28 % | 7 / 22 % | 0 / 4 % | 4 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 7 / 19 % | 1 / 7 % | 4 / 11 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 7 / 18 % | 1 / 7 % | 5 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 0 / 0 % | 6 / 21 % | 1 / 7 % | 5 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 28 % | 5 / 62 % | 0 / 5 % | 0 / 17 % | 5 / 19 % | 1 / 9 % | 4 / 16 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 3 / 64 % | 0 / 4 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 6 / 17 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 3 % | 6 / 16 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 5 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 74 % | 0 / 0 % | 0 / 15 % | 5 / 14 % | 0 / 3 % | 3 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 4 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 4 / 8 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 5 / 11 % |
