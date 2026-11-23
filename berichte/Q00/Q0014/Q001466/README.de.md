[English](README.md) · [Deutsch](README.de.md)

# Theories of Change for AI Auditing

Bericht Q001466 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/blog/theories-of-change-for-ai-auditing)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Apollo Research beschreibt fünf Arten von KI-Prüfungen, die Risiken erkennen, sichere Entwicklung fördern und Aufsicht unterstützen könnten. Der Nutzen ist laut Bericht jedoch unsicher: Tests können falsche Sicherheit schaffen und garantieren nicht, dass ein System ungefährlich ist; wirksame Prüfungen erfordern bessere Methoden, unabhängige Prüfer und durchsetzbare Regeln.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 41 / 64 % | 97 / 99 % | – | 65 / 86 % | 78 / 92 % | 81 / 92 % | 84 / 97 % | 42 / 67 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 57 / 73 % | 73 / 93 % | – | 78 / 89 % | 84 / 91 % | 88 / 92 % | 93 / 98 % | 22 / 50 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 17 / 45 % | 86 / 96 % | – | 45 / 77 % | 28 / 58 % | 45 / 82 % | 26 / 69 % | 19 / 47 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 32 / 56 % | 54 / 95 % | – | 61 / 84 % | 33 / 68 % | 86 / 94 % | 56 / 90 % | 20 / 46 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 26 / 57 % | 83 / 99 % | – | 52 / 78 % | 43 / 76 % | 48 / 74 % | 45 / 88 % | 21 / 46 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 31 / 56 % | 51 / 91 % | – | 69 / 87 % | 75 / 90 % | 76 / 90 % | 48 / 82 % | 12 / 34 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 24 / 46 % | 46 / 88 % | – | 56 / 79 % | 46 / 69 % | 75 / 85 % | 73 / 82 % | 7 / 32 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 28 / 54 % | 73 / 90 % | – | 55 / 79 % | 35 / 69 % | 63 / 84 % | 74 / 92 % | 27 / 57 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 39 % | 69 / 89 % | – | 22 / 55 % | 8 / 32 % | 19 / 58 % | 6 / 35 % | 23 / 52 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 23 / 49 % | 59 / 92 % | – | 52 / 76 % | 41 / 66 % | 66 / 83 % | 51 / 78 % | 21 / 46 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 22 / 55 % | 60 / 90 % | – | 35 / 73 % | 42 / 77 % | 65 / 89 % | 50 / 90 % | 21 / 51 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 25 / 50 % | 51 / 86 % | – | 34 / 67 % | 27 / 57 % | 64 / 78 % | 42 / 55 % | 15 / 36 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 27 / 53 % | 63 / 96 % | – | 53 / 80 % | 46 / 76 % | 37 / 76 % | 18 / 60 % | 13 / 35 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 37 / 59 % | 63 / 95 % | – | 54 / 81 % | 39 / 74 % | 62 / 85 % | 45 / 89 % | 32 / 57 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 17 / 43 % | 35 / 74 % | – | 48 / 71 % | 15 / 31 % | 59 / 70 % | 3 / 4 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 47 % | 28 / 85 % | – | 26 / 61 % | 15 / 43 % | 56 / 78 % | 31 / 65 % | 11 / 30 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 41 % | 56 / 93 % | – | 15 / 45 % | 5 / 26 % | 24 / 58 % | 3 / 20 % | 13 / 34 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 17 / 45 % | 50 / 82 % | – | 41 / 70 % | 31 / 60 % | 56 / 80 % | 23 / 52 % | 21 / 47 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 17 / 41 % | 51 / 90 % | – | 19 / 48 % | 8 / 24 % | 23 / 49 % | 7 / 25 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 15 / 47 % | 51 / 97 % | – | 23 / 54 % | 13 / 46 % | 28 / 65 % | 25 / 74 % | 23 / 55 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 19 / 40 % | 50 / 81 % | – | 35 / 59 % | 7 / 24 % | 36 / 56 % | 13 / 28 % | 23 / 50 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 24 / 53 % | 38 / 87 % | – | 44 / 74 % | 18 / 53 % | 23 / 61 % | 16 / 55 % | 12 / 35 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 19 / 48 % | 34 / 90 % | – | 42 / 75 % | 21 / 54 % | 33 / 79 % | 20 / 69 % | 10 / 35 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 10 / 32 % | 39 / 95 % | – | 15 / 44 % | 6 / 26 % | 15 / 47 % | 3 / 13 % | 8 / 26 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 14 / 42 % | 35 / 86 % | – | 21 / 51 % | 12 / 40 % | 20 / 59 % | 6 / 40 % | 12 / 40 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 30 % | 34 / 84 % | – | 15 / 43 % | 6 / 25 % | 10 / 29 % | 1 / 10 % | 12 / 37 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 9 / 46 % | 32 / 78 % | – | 13 / 38 % | 6 / 19 % | 12 / 31 % | 2 / 11 % | 8 / 29 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 19 / 41 % | 26 / 68 % | – | 23 / 58 % | 8 / 22 % | 24 / 65 % | 6 / 18 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 22 / 97 % | – | 11 / 33 % | 5 / 17 % | 8 / 29 % | 1 / 9 % | 6 / 29 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 14 / 62 % | – | 11 / 37 % | 2 / 11 % | 20 / 41 % | 2 / 10 % | 13 / 33 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 11 / 86 % | – | 16 / 45 % | 3 / 15 % | 19 / 33 % | 1 / 3 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 11 / 36 % | 18 / 58 % | – | 14 / 39 % | 6 / 18 % | 14 / 27 % | 1 / 7 % | 10 / 32 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 17 / 87 % | – | 6 / 20 % | 2 / 7 % | 9 / 22 % | 0 / 2 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 17 / 53 % | – | 10 / 28 % | 0 / 0 % | 10 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 31 % | – | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 2 % | 14 / 40 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 9 / 25 % | 0 / 0 % | – | 13 / 43 % | 7 / 35 % | 14 / 47 % | 3 / 14 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 4 / 78 % | – | 8 / 29 % | 4 / 14 % | 12 / 31 % | 1 / 7 % | 1 / 12 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | 2 / 8 % | 12 / 32 % | 1 / 5 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 8 / 91 % | – | 8 / 24 % | 3 / 14 % | 12 / 23 % | 1 / 6 % | 2 / 16 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 8 / 22 % | 0 / 0 % | 11 / 25 % | 1 / 5 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 11 / 44 % | – | 0 / 0 % | 5 / 15 % | 9 / 19 % | 0 / 2 % | 7 / 21 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 11 / 43 % | – | 7 / 22 % | 2 / 5 % | 10 / 26 % | 0 / 3 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | 3 / 10 % | 10 / 19 % | 0 / 2 % | 6 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 8 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
