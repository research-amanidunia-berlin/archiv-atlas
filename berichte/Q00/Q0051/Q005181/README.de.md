[English](README.md) · [Deutsch](README.de.md)

# A framework for AI development transparency

Bericht Q005181 · Quelle anthropic.com · Datum 2025-07-07 · [Original öffnen](https://www.anthropic.com/news/the-need-for-transparency-in-frontier-ai)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic schlägt flexible Transparenzpflichten für die größten KI-Entwickler vor: Sie sollen Sicherheitsrahmen und Systemkarten veröffentlichen, Risiken und Gegenmaßnahmen dokumentieren und wesentliche Änderungen nachtragen. Das Unternehmen will kleinere Entwickler ausnehmen und meint, solche Offenlegungen könnten Politik und Öffentlichkeit informieren; der Bericht ist ein Vorschlag, kein Nachweis seiner Wirksamkeit oder einer beschlossenen Regelung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 65 / 79 % | 100 / 100 % | – | 96 / 98 % | 85 / 91 % | 78 / 87 % | 82 / 90 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 64 / 83 % | 86 / 97 % | – | 100 / 100 % | 89 / 94 % | 72 / 85 % | 85 / 91 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 69 / 84 % | 90 / 95 % | – | 99 / 100 % | 87 / 93 % | 77 / 88 % | 89 / 93 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 35 / 61 % | 98 / 100 % | – | 87 / 94 % | 58 / 79 % | 56 / 76 % | 58 / 79 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 38 / 62 % | 97 / 100 % | – | 97 / 100 % | 70 / 86 % | 79 / 90 % | 82 / 90 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 21 / 44 % | 91 / 96 % | – | 93 / 97 % | 65 / 81 % | 45 / 60 % | 59 / 71 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 19 / 51 % | 80 / 93 % | – | 90 / 95 % | 40 / 65 % | 25 / 47 % | 43 / 62 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 56 / 70 % | 82 / 89 % | – | 77 / 83 % | 84 / 90 % | 80 / 87 % | 89 / 92 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 20 / 38 % | 67 / 91 % | – | 88 / 95 % | 13 / 34 % | 9 / 18 % | 12 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 24 / 54 % | 71 / 91 % | – | 82 / 95 % | 39 / 65 % | 43 / 70 % | 43 / 67 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 43 % | 77 / 97 % | – | 7 / 18 % | 14 / 38 % | 14 / 32 % | 29 / 54 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 20 / 47 % | 71 / 88 % | – | 75 / 90 % | 28 / 56 % | 18 / 41 % | 33 / 59 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 15 / 42 % | 62 / 93 % | – | 75 / 89 % | 18 / 45 % | 19 / 45 % | 42 / 70 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 13 / 35 % | 62 / 92 % | – | 44 / 65 % | 12 / 34 % | 7 / 20 % | 12 / 36 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 26 / 47 % | 51 / 86 % | – | 59 / 86 % | 37 / 64 % | 21 / 46 % | 12 / 33 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 50 / 77 % | – | 56 / 83 % | 24 / 48 % | 9 / 23 % | 14 / 29 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 8 / 33 % | 53 / 96 % | – | 4 / 35 % | 13 / 34 % | 9 / 33 % | 12 / 37 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 19 / 32 % | 45 / 81 % | – | 44 / 71 % | 14 / 38 % | 4 / 12 % | 11 / 28 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 18 / 44 % | 44 / 83 % | – | 8 / 34 % | 24 / 53 % | 14 / 37 % | 39 / 63 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 44 / 81 % | – | 5 / 22 % | 10 / 29 % | 6 / 20 % | 6 / 26 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 35 / 73 % | – | 42 / 73 % | 11 / 34 % | 14 / 36 % | 9 / 23 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 8 / 30 % | 40 / 67 % | – | 16 / 48 % | 9 / 28 % | 5 / 21 % | 10 / 28 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 33 / 70 % | – | 0 / 0 % | 7 / 15 % | 0 / 4 % | 4 / 14 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 32 / 56 % | 8 / 18 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 6 / 33 % | 30 / 69 % | – | 2 / 22 % | 9 / 25 % | 5 / 17 % | 10 / 25 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 9 / 37 % | 18 / 80 % | – | 28 / 68 % | 26 / 53 % | 18 / 46 % | 20 / 62 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 12 / 73 % | – | 24 / 60 % | 10 / 34 % | 2 / 10 % | 4 / 18 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 24 / 64 % | – | 7 / 30 % | 7 / 19 % | 4 / 13 % | 8 / 28 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 23 / 57 % | – | 11 / 39 % | 13 / 32 % | 6 / 18 % | 10 / 22 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 21 / 79 % | – | 1 / 12 % | 10 / 25 % | 3 / 10 % | 5 / 20 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 10 / 40 % | – | 0 / 0 % | 19 / 50 % | 8 / 23 % | 20 / 44 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 20 / 81 % | – | 0 / 10 % | 7 / 17 % | 2 / 9 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 16 / 39 % | 6 / 14 % | 1 / 5 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 15 / 45 % | – | 1 / 9 % | 6 / 16 % | 1 / 9 % | 5 / 14 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 12 / 53 % | – | 3 / 25 % | 9 / 24 % | 4 / 12 % | 6 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 33 % | 10 / 27 % | 7 / 21 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 33 % | 6 / 43 % | – | 0 / 5 % | 7 / 19 % | 2 / 7 % | 5 / 10 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 1 / 4 % | 5 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 1 / 6 % | 6 / 15 % | 2 / 6 % | 5 / 16 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 4 / 7 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 3 / 44 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 5 % | 3 / 11 % |
