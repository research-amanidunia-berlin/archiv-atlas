[English](README.md) · [Deutsch](README.de.md)

# Dario Amodei — We Must Pace the Frontier

Bericht Q004494 · Quelle darioamodei.com · Datum 2026-09-12 · [Original öffnen](https://darioamodei.com/post/we-must-pace-the-frontier)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Amodei fordert, das Tempo der KI-Entwicklung so zu steuern, dass Sicherheitsprüfungen, Ausrichtung und öffentliche Beratung mithalten können. Er schlägt unabhängige Prüfer, gemeinsame Standards und internationale Absprachen vor; Anthropic sagt im Essay den ersten Schritt zu. Die erwarteten Sicherheitswirkungen sind nicht belegt, und der Autor betont erhebliche Hürden bei Kontrolle und internationaler Zusammenarbeit.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 43 / 65 % | 98 / 99 % | 96 / 99 % | 100 / 100 % | 86 / 93 % | 93 / 95 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 80 / 88 % | 100 / 100 % | 100 / 100 % | 100 / 100 % | 90 / 94 % | 95 / 96 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 50 / 67 % | 96 / 97 % | 96 / 99 % | 100 / 100 % | 82 / 90 % | 91 / 95 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 67 / 81 % | 95 / 96 % | 93 / 98 % | 100 / 100 % | 80 / 89 % | 93 / 95 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 60 / 78 % | 90 / 96 % | 84 / 96 % | 100 / 100 % | 86 / 93 % | 87 / 94 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 34 / 63 % | 98 / 99 % | 92 / 98 % | 99 / 100 % | 80 / 90 % | 93 / 96 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 47 / 64 % | 88 / 93 % | 88 / 96 % | 99 / 100 % | 83 / 91 % | 94 / 96 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 39 / 62 % | 96 / 98 % | 70 / 91 % | 99 / 100 % | 77 / 89 % | 81 / 90 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 59 / 74 % | 87 / 92 % | 70 / 83 % | 98 / 99 % | 85 / 92 % | 71 / 85 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 46 / 65 % | 96 / 97 % | 87 / 94 % | 98 / 99 % | 78 / 88 % | 89 / 94 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 55 / 74 % | 97 / 99 % | 95 / 98 % | 93 / 97 % | 87 / 93 % | 89 / 93 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 13 / 30 % | 95 / 99 % | 3 / 15 % | 39 / 59 % | 17 / 40 % | 28 / 52 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 18 / 42 % | 93 / 96 % | 27 / 40 % | 88 / 94 % | 50 / 77 % | 73 / 86 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 41 / 65 % | 91 / 97 % | 19 / 53 % | 87 / 92 % | 38 / 65 % | 51 / 73 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 16 / 34 % | 88 / 96 % | 43 / 57 % | 55 / 70 % | 54 / 75 % | 55 / 68 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 32 / 57 % | 67 / 97 % | 25 / 55 % | 87 / 96 % | 70 / 85 % | 43 / 72 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 32 / 62 % | 62 / 92 % | 64 / 84 % | 75 / 89 % | 80 / 90 % | 86 / 93 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 28 / 50 % | 65 / 83 % | 11 / 30 % | 86 / 92 % | 39 / 66 % | 40 / 60 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 21 / 51 % | 68 / 83 % | 55 / 83 % | 84 / 98 % | 48 / 74 % | 74 / 92 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 36 / 56 % | 65 / 81 % | 61 / 85 % | 82 / 97 % | 69 / 86 % | 84 / 92 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 41 / 62 % | 59 / 94 % | 34 / 68 % | 77 / 93 % | 58 / 80 % | 41 / 68 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 33 / 58 % | 66 / 88 % | 23 / 50 % | 77 / 91 % | 50 / 71 % | 41 / 67 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 25 / 42 % | 43 / 72 % | 11 / 31 % | 76 / 88 % | 37 / 65 % | 28 / 56 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 18 / 50 % | 76 / 89 % | 26 / 55 % | 34 / 65 % | 40 / 66 % | 44 / 74 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 28 / 58 % | 1 / 5 % | 76 / 88 % | 15 / 40 % | 15 / 26 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 15 / 34 % | 63 / 93 % | 2 / 10 % | 75 / 87 % | 23 / 49 % | 24 / 57 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 33 / 60 % | 60 / 95 % | 24 / 53 % | 74 / 89 % | 62 / 83 % | 56 / 83 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 25 / 53 % | 47 / 83 % | 40 / 70 % | 53 / 85 % | 39 / 64 % | 69 / 84 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 31 / 56 % | 68 / 95 % | 44 / 72 % | 69 / 81 % | 64 / 85 % | 64 / 85 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 23 / 43 % | 66 / 87 % | 23 / 28 % | 68 / 78 % | 50 / 71 % | 48 / 59 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 16 / 41 % | 57 / 91 % | 23 / 45 % | 36 / 66 % | 44 / 71 % | 67 / 81 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 24 / 45 % | 59 / 89 % | 13 / 38 % | 59 / 86 % | 41 / 66 % | 62 / 79 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 12 / 23 % | 40 / 63 % | 13 / 17 % | 6 / 16 % | 45 / 66 % | 56 / 67 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 47 / 77 % | 4 / 18 % | 45 / 71 % | 31 / 60 % | 25 / 50 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 43 / 82 % | 3 / 11 % | 26 / 51 % | 17 / 46 % | 32 / 58 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 40 / 83 % | 1 / 5 % | 10 / 41 % | 10 / 26 % | 16 / 34 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 28 / 49 % | 32 / 90 % | 7 / 26 % | 24 / 64 % | 30 / 59 % | 29 / 49 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 2 / 17 % | 19 / 41 % | 22 / 48 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 20 / 51 % | 0 / 2 % | 0 / 0 % | 8 / 22 % | 12 / 27 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 15 / 75 % | 1 / 7 % | 20 / 45 % | 11 / 30 % | 16 / 42 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 36 % | 13 / 21 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 16 / 77 % | 0 / 2 % | 0 / 4 % | 6 / 13 % | 9 / 16 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 2 / 23 % | 8 / 20 % | 10 / 22 % |
