[English](README.md) · [Deutsch](README.de.md)

# Google DeepMind and Isomorphic Labs approach to bioresilience

Bericht Q001355 · Quelle deepmind.google · Datum 2026-07-16 · [Original öffnen](https://deepmind.google/blog/our-approach-to-bioresilience/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google DeepMind und Isomorphic Labs beschreiben ein Programm, das KI zur Prävention, Erkennung und Bekämpfung biologischer Gefahren einsetzen soll. Der Beitrag nennt Partnerschaften und konkrete Systeme, enthält aber keine unabhängige Wirksamkeitsbewertung; einige Anwendungen befinden sich noch in der Erkundung oder Entwicklung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 27 / 52 % | 79 / 92 % | 13 / 35 % | 96 / 99 % | 39 / 65 % | 36 / 61 % | 20 / 46 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 47 / 64 % | 91 / 97 % | 82 / 91 % | 91 / 98 % | 64 / 82 % | 71 / 83 % | 45 / 66 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 4 / 29 % | 0 / 0 % | 74 / 80 % | 11 / 32 % | 13 / 27 % | 2 / 8 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 19 / 42 % | 48 / 84 % | 5 / 14 % | 67 / 88 % | 27 / 52 % | 26 / 46 % | 12 / 31 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 43 / 83 % | 1 / 3 % | 65 / 78 % | 8 / 26 % | 5 / 13 % | 5 / 20 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 27 / 51 % | 63 / 86 % | 14 / 33 % | 58 / 81 % | 31 / 62 % | 42 / 70 % | 30 / 58 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 62 / 95 % | 2 / 7 % | 48 / 66 % | 19 / 43 % | 11 / 27 % | 7 / 23 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 51 / 75 % | 11 / 27 % | 59 / 84 % | 43 / 67 % | 24 / 53 % | 17 / 40 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 45 / 76 % | 3 / 9 % | 57 / 80 % | 21 / 48 % | 10 / 27 % | 8 / 21 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 40 % | 5 / 31 % | 2 / 9 % | 56 / 81 % | 15 / 41 % | 9 / 26 % | 6 / 23 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 15 / 36 % | 0 / 0 % | 53 / 72 % | 6 / 12 % | 0 / 0 % | 0 / 2 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 52 / 89 % | 2 / 8 % | 8 / 31 % | 12 / 32 % | 10 / 25 % | 6 / 19 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 21 / 91 % | 0 / 2 % | 49 / 74 % | 9 / 33 % | 8 / 23 % | 1 / 8 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 22 / 45 % | 23 / 27 % | 46 / 56 % | 32 / 53 % | 43 / 56 % | 44 / 65 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 45 % | 45 / 81 % | 8 / 19 % | 30 / 70 % | 21 / 49 % | 13 / 32 % | 9 / 29 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 14 / 42 % | 19 / 44 % | 8 / 19 % | 44 / 75 % | 11 / 28 % | 15 / 46 % | 15 / 37 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 19 / 60 % | 0 / 2 % | 42 / 61 % | 10 / 29 % | 10 / 24 % | 1 / 11 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 42 / 74 % | 0 / 3 % | 42 / 68 % | 9 / 26 % | 7 / 22 % | 4 / 16 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 41 / 77 % | 1 / 5 % | 41 / 70 % | 16 / 35 % | 8 / 17 % | 7 / 19 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 5 / 54 % | 1 / 3 % | 39 / 69 % | 12 / 34 % | 6 / 15 % | 5 / 13 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 33 / 59 % | 2 / 8 % | 22 / 52 % | 18 / 39 % | 11 / 23 % | 5 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 31 / 74 % | 3 / 7 % | 16 / 60 % | 9 / 27 % | 8 / 20 % | 2 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 28 / 84 % | 1 / 5 % | 14 / 58 % | 14 / 42 % | 11 / 35 % | 7 / 27 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 3 / 5 % | 7 / 18 % | 11 / 27 % | 18 / 28 % | 24 / 41 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 22 / 53 % | 1 / 4 % | 4 / 33 % | 12 / 33 % | 12 / 31 % | 6 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 35 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 17 / 53 % | 0 / 0 % | 4 / 17 % | 7 / 18 % | 6 / 16 % | 3 / 7 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 3 / 51 % | 2 / 7 % | 6 / 20 % | 10 / 30 % | 12 / 29 % | 5 / 17 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 11 / 26 % | 6 / 17 % | 3 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 25 % | 9 / 29 % | 7 / 22 % | 1 / 8 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 25 % | 5 / 16 % | 2 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 8 / 18 % | 2 / 7 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 4 / 31 % | 0 / 3 % | 0 / 0 % | 7 / 19 % | 8 / 26 % | 2 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 10 % | 0 / 0 % | 2 / 12 % | 7 / 14 % | 8 / 18 % | 2 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 4 / 13 % | 1 / 6 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 6 / 14 % | 1 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 1 / 25 % | 7 / 20 % | 0 / 0 % | 1 / 8 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 1 / 26 % | 0 / 2 % | 2 / 11 % | 6 / 16 % | 4 / 13 % | 2 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 1 / 30 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 5 / 8 % | 1 / 4 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 5 / 11 % | 1 / 6 % |
