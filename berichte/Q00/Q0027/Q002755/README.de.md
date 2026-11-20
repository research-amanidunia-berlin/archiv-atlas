[English](README.md) · [Deutsch](README.de.md)

# A sketch of an AI control safety case

Bericht Q002755 · Quelle aisi.gov.uk · Datum 2025-01-28 · [Original öffnen](https://www.aisi.gov.uk/research/a-sketch-of-an-ai-control-safety-case)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug skizziert einen strukturierten Sicherheitsnachweis dafür, dass ein LLM-Agent Kontrollmaßnahmen nicht umgehen kann, um etwa vertrauliche Daten nach außen zu geben. Er beruht auf Red-Team-Tests und setzt voraus, dass diese Fähigkeiten ausreichend aufdecken, die Kontrollen im Einsatz wirksam bleiben und Testergebnisse vorsichtig übertragen werden; konkrete Evaluationsergebnisse enthält der Auszug nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 41 / 62 % | 51 / 93 % | – | 77 / 96 % | 51 / 76 % | 55 / 73 % | 42 / 69 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 38 / 56 % | 29 / 84 % | – | 72 / 97 % | 43 / 70 % | 44 / 69 % | 38 / 67 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 32 / 56 % | 44 / 83 % | – | 58 / 92 % | 46 / 70 % | 31 / 55 % | 13 / 38 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 29 / 53 % | 32 / 88 % | – | 49 / 92 % | 5 / 11 % | 41 / 63 % | 28 / 55 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 31 / 52 % | 12 / 46 % | – | 0 / 0 % | 38 / 65 % | 48 / 67 % | 15 / 38 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 35 / 55 % | 31 / 85 % | – | 30 / 76 % | 29 / 59 % | 40 / 64 % | 14 / 38 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 17 / 42 % | 35 / 61 % | – | 5 / 32 % | 22 / 48 % | 21 / 43 % | 12 / 36 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 23 / 41 % | 0 / 0 % | – | 12 / 58 % | 27 / 55 % | 15 / 32 % | 8 / 20 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 15 / 39 % | 26 / 87 % | – | 11 / 64 % | 18 / 47 % | 15 / 35 % | 6 / 17 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 40 % | 26 / 63 % | – | 0 / 0 % | 7 / 18 % | 8 / 16 % | 1 / 7 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 13 / 32 % | 25 / 60 % | – | 25 / 59 % | 9 / 24 % | 12 / 27 % | 3 / 7 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 22 / 40 % | 18 / 71 % | – | 12 / 43 % | 13 / 35 % | 22 / 38 % | 11 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 22 / 44 % | 0 / 0 % | – | 13 / 41 % | 22 / 48 % | 0 / 0 % | 6 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 22 / 46 % | 0 / 0 % | – | 9 / 36 % | 18 / 44 % | 9 / 20 % | 6 / 16 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 19 / 49 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 4 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 15 / 38 % | 18 / 48 % | – | 2 / 8 % | 7 / 19 % | 0 / 0 % | 1 / 5 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 15 / 36 % | 0 / 0 % | – | 16 / 51 % | 6 / 19 % | 0 / 0 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 15 / 35 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 11 / 20 % | 3 / 9 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 14 / 34 % | 7 / 16 % | 0 / 0 % | 1 / 3 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 12 / 25 % | 3 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 12 / 26 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 0 / 0 % | 0 / 2 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 26 % | 0 / 0 % | 0 / 1 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 25 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 5 / 10 % | 1 / 5 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 5 / 29 % | 0 / 0 % | – | 3 / 16 % | 8 / 24 % | 0 / 0 % | 3 / 14 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 6 / 15 % | 1 / 3 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 2 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 1 / 12 % | 5 / 12 % | 6 / 13 % | 2 / 5 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 4 / 37 % | – | 4 / 31 % | 5 / 11 % | 6 / 11 % | 1 / 3 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 6 / 14 % | 1 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 3 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 2 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 7 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 4 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 4 / 11 % | 0 / 0 % | 1 / 4 % |
