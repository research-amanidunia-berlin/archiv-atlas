[English](README.md) · [Deutsch](README.de.md)

# Advancing responsible AI across Europe

Bericht Q007950 · Quelle openai.com · Datum 2026-07-31 · [Original öffnen](https://openai.com/index/advancing-responsible-ai-across-europe/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt eigene Sicherheits-, Transparenz- und Governance-Maßnahmen zur Umsetzung des EU-KI-Gesetzes, darunter Prüfungen, interne Risikorahmen, Herkunftssignale für Inhalte und Kooperationen im Bereich Cybersicherheit. Zugleich räumt der Bericht Grenzen bei Herkunftskennzeichnungen ein und kündigt weitere Anpassungen an; die Wirksamkeit der Maßnahmen wird im Text nicht unabhängig bewertet.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 61 % | 89 / 98 % | – | 98 / 100 % | 71 / 87 % | 71 / 85 % | 55 / 81 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 30 / 54 % | 89 / 99 % | – | 97 / 100 % | 52 / 78 % | 81 / 91 % | 57 / 80 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 28 / 54 % | 92 / 98 % | – | 97 / 99 % | 38 / 63 % | 61 / 82 % | 28 / 56 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 49 / 75 % | 49 / 79 % | – | 97 / 100 % | 80 / 90 % | 74 / 87 % | 57 / 79 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 62 / 79 % | 89 / 98 % | – | 94 / 99 % | 85 / 92 % | 92 / 95 % | 85 / 93 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 17 / 44 % | 20 / 62 % | – | 90 / 94 % | 28 / 61 % | 36 / 66 % | 15 / 41 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 42 / 63 % | 80 / 95 % | – | 66 / 91 % | 64 / 83 % | 70 / 83 % | 44 / 66 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 44 / 76 % | – | 76 / 86 % | 39 / 61 % | 15 / 26 % | 45 / 66 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 23 / 49 % | 47 / 85 % | – | 71 / 95 % | 39 / 68 % | 74 / 88 % | 39 / 65 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 18 / 34 % | 59 / 87 % | – | 71 / 89 % | 22 / 50 % | 17 / 44 % | 6 / 25 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 29 / 57 % | 52 / 96 % | – | 69 / 86 % | 48 / 72 % | 43 / 67 % | 26 / 52 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 27 / 51 % | 57 / 79 % | – | 67 / 85 % | 24 / 52 % | 41 / 63 % | 31 / 56 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 28 / 47 % | 63 / 93 % | – | 44 / 91 % | 53 / 77 % | 67 / 83 % | 25 / 56 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 17 / 89 % | – | 64 / 89 % | 33 / 62 % | 18 / 52 % | 12 / 36 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 19 / 48 % | 64 / 88 % | – | 23 / 55 % | 29 / 54 % | 49 / 67 % | 20 / 41 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 20 / 52 % | 60 / 94 % | – | 40 / 74 % | 40 / 67 % | 26 / 57 % | 23 / 60 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 15 / 42 % | 54 / 91 % | – | 60 / 81 % | 14 / 40 % | 10 / 37 % | 5 / 26 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 15 / 42 % | 58 / 97 % | – | 54 / 83 % | 17 / 53 % | 8 / 30 % | 3 / 19 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 54 / 92 % | – | 17 / 62 % | 11 / 32 % | 11 / 27 % | 5 / 21 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 36 % | 50 / 83 % | – | 41 / 77 % | 17 / 43 % | 17 / 65 % | 10 / 41 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 12 / 43 % | 46 / 97 % | – | 13 / 71 % | 21 / 55 % | 13 / 54 % | 8 / 33 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 19 / 40 % | 43 / 82 % | – | 20 / 49 % | 24 / 53 % | 19 / 48 % | 18 / 40 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 38 / 82 % | – | 2 / 27 % | 12 / 32 % | 8 / 20 % | 5 / 18 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 36 / 95 % | – | 1 / 25 % | 11 / 35 % | 11 / 30 % | 5 / 26 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 13 / 24 % | 36 / 77 % | – | 26 / 55 % | 17 / 51 % | 16 / 52 % | 4 / 23 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 31 / 74 % | – | 5 / 26 % | 9 / 29 % | 10 / 29 % | 1 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 9 / 28 % | 30 / 60 % | – | 11 / 38 % | 9 / 32 % | 7 / 29 % | 1 / 17 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 39 % | 29 / 85 % | – | 8 / 51 % | 12 / 36 % | 16 / 42 % | 6 / 25 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 18 / 70 % | – | 23 / 54 % | 7 / 20 % | 6 / 10 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 19 / 71 % | – | 7 / 43 % | 10 / 26 % | 12 / 27 % | 4 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 14 / 31 % | 0 / 0 % | – | 11 / 26 % | 12 / 37 % | 18 / 60 % | 8 / 33 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 29 % | 18 / 66 % | – | 9 / 40 % | 7 / 24 % | 6 / 18 % | 2 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 30 % | 3 / 35 % | – | 1 / 12 % | 8 / 25 % | 9 / 23 % | 4 / 18 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 32 % | 7 / 32 % | 2 / 30 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 7 / 32 % | – | 3 / 14 % | 11 / 26 % | 9 / 19 % | 2 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 9 / 31 % | – | 0 / 0 % | 7 / 15 % | 6 / 11 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 7 / 66 % | – | 0 / 9 % | 7 / 19 % | 9 / 19 % | 2 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 30 % | 4 / 57 % | – | 0 / 5 % | 8 / 22 % | 6 / 16 % | 2 / 8 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 14 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 7 / 12 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 6 / 17 % | 1 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 3 / 28 % | – | 2 / 21 % | 6 / 16 % | 5 / 12 % | 3 / 15 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
