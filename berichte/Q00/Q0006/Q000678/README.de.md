[English](README.md) · [Deutsch](README.de.md)

# Brief #32: Tencent, DeepSeek and Alibaba on AI safety and open-source

Bericht Q000678 · Quelle aisafetychina.substack.com · Datum 2026-11-11 · [Original öffnen](https://aisafetychina.substack.com/p/brief-32-tencent-deepseek-and-alibaba)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt eine zunehmend öffentliche Debatte chinesischer KI-Labore über Sicherheitsrisiken offener Modellgewichte. Tencent zufolge habe Hy4 bei internen Tests kein erhöhtes Cyberrisiko gezeigt und bei einem Biosecurity-Benchmark deutlich unter der Hochrisikoschwelle gelegen; die Messmethode ist öffentlich jedoch kaum beschrieben. Alibaba und DeepSeek benennen Risiken offener Gewichte, während die Unternehmen weiter an offenen Veröffentlichungen festhalten und zugleich Schutzmaßnahmen erwägen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 49 % | 98 / 100 % | – | 42 / 66 % | 27 / 48 % | 56 / 73 % | 15 / 37 % | 35 / 60 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 63 / 84 % | 95 / 99 % | – | 78 / 89 % | 79 / 89 % | 84 / 92 % | 91 / 97 % | 60 / 80 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 32 / 55 % | 88 / 98 % | – | 55 / 77 % | 26 / 54 % | 62 / 82 % | 37 / 70 % | 51 / 73 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 24 / 52 % | 86 / 100 % | – | 36 / 61 % | 11 / 30 % | 31 / 57 % | 15 / 38 % | 36 / 68 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 51 / 74 % | 86 / 98 % | – | 63 / 83 % | 35 / 57 % | 78 / 89 % | 55 / 78 % | 23 / 53 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 28 / 50 % | 81 / 92 % | – | 60 / 80 % | 35 / 56 % | 55 / 72 % | 61 / 74 % | 24 / 48 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 42 / 66 % | 80 / 99 % | – | 38 / 64 % | 33 / 54 % | 59 / 75 % | 33 / 55 % | 32 / 59 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 44 / 67 % | 78 / 98 % | – | 45 / 69 % | 24 / 43 % | 57 / 72 % | 25 / 50 % | 33 / 61 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 29 / 55 % | 76 / 98 % | – | 38 / 64 % | 39 / 55 % | 71 / 83 % | 22 / 44 % | 52 / 75 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 18 / 45 % | 74 / 98 % | – | 46 / 71 % | 18 / 45 % | 36 / 63 % | 13 / 39 % | 36 / 65 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 28 / 53 % | 71 / 92 % | – | 19 / 43 % | 44 / 66 % | 69 / 83 % | 72 / 89 % | 38 / 69 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 34 / 56 % | 57 / 99 % | – | 60 / 81 % | 30 / 58 % | 72 / 87 % | 27 / 62 % | 36 / 65 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 72 / 93 % | – | 18 / 46 % | 12 / 29 % | 18 / 45 % | 3 / 16 % | 26 / 51 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 26 / 49 % | 71 / 91 % | – | 47 / 74 % | 43 / 69 % | 63 / 80 % | 50 / 78 % | 26 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 48 % | 69 / 95 % | – | 27 / 55 % | 12 / 35 % | 17 / 44 % | 9 / 31 % | 19 / 44 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 21 / 41 % | 39 / 64 % | – | 42 / 66 % | 33 / 55 % | 51 / 64 % | 8 / 14 % | 27 / 50 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 50 / 93 % | – | 19 / 49 % | 9 / 29 % | 24 / 45 % | 2 / 9 % | 10 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 48 / 96 % | – | 42 / 68 % | 11 / 29 % | 9 / 27 % | 4 / 15 % | 14 / 41 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 48 / 89 % | – | 17 / 43 % | 5 / 18 % | 10 / 31 % | 1 / 6 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 38 / 78 % | – | 10 / 25 % | 4 / 10 % | 7 / 17 % | 1 / 6 % | 7 / 24 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 33 % | 37 / 86 % | – | 14 / 38 % | 8 / 23 % | 20 / 38 % | 3 / 11 % | 20 / 47 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 31 / 91 % | – | 10 / 33 % | 4 / 13 % | 5 / 16 % | 2 / 11 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 26 / 80 % | – | 11 / 30 % | 1 / 9 % | 8 / 14 % | 0 / 0 % | 14 / 31 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 24 / 86 % | – | 11 / 38 % | 2 / 9 % | 9 / 30 % | 1 / 5 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 39 % | 7 / 91 % | – | 9 / 29 % | 3 / 14 % | 8 / 21 % | 1 / 6 % | 23 / 48 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 22 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 20 / 56 % | – | 15 / 42 % | 4 / 13 % | 15 / 32 % | 1 / 7 % | 7 / 24 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 9 / 58 % | – | 6 / 14 % | 1 / 6 % | 6 / 16 % | 0 / 1 % | 20 / 50 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | 2 / 9 % | 6 / 12 % | 0 / 2 % | 16 / 35 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 16 / 95 % | – | 13 / 40 % | 2 / 12 % | 8 / 29 % | 1 / 6 % | 14 / 31 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 7 / 67 % | – | 11 / 33 % | 7 / 24 % | 14 / 49 % | 2 / 11 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 8 / 19 % | 4 / 11 % | 7 / 15 % | 0 / 1 % | 13 / 38 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 11 / 84 % | – | 10 / 27 % | 5 / 16 % | 11 / 22 % | 1 / 7 % | 12 / 36 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 12 / 39 % | – | 12 / 33 % | 3 / 11 % | 10 / 28 % | 0 / 2 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 12 / 79 % | – | 12 / 37 % | 7 / 20 % | 12 / 40 % | 2 / 10 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 3 / 95 % | – | 10 / 30 % | 5 / 19 % | 10 / 28 % | 1 / 5 % | 8 / 29 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 10 / 71 % | – | 7 / 18 % | 1 / 9 % | 6 / 17 % | 0 / 1 % | 8 / 25 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 7 / 19 % | 4 / 12 % | 8 / 19 % | 0 / 2 % | 4 / 18 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 8 / 23 % | 2 / 7 % | 7 / 15 % | 0 / 1 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 4 / 59 % | – | 8 / 21 % | 5 / 18 % | 6 / 15 % | 0 / 2 % | 7 / 25 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 1 / 5 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 3 / 8 % | 6 / 10 % | 0 / 2 % | 4 / 17 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 2 / 6 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
