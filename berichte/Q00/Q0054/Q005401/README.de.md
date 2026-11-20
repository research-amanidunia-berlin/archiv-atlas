[English](README.md) · [Deutsch](README.de.md)

# When AI builds itself

Bericht Q005401 · Quelle anthropic.com · Datum – · [Original öffnen](https://www.anthropic.com/institute/recursive-self-improvement)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic berichtet, dass Claude bereits viel Code schreibe, Experimente beschleunige und bei manchen Forschungsentscheidungen besser werde; dadurch werde die menschliche Arbeit an der KI-Entwicklung schneller und verlagere sich stärker auf Zielwahl und Bewertung. Der Bericht sieht vollständige Selbstverbesserung als mögliche, aber nicht sichere Zukunft und nennt sowohl erhebliche Chancen als auch Kontrollrisiken. Die Zahlen stammen teilweise aus internen Daten, und mehrere Messungen sowie Vergleiche haben ausdrücklich benannte Grenzen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 74 / 84 % | 98 / 99 % | – | 100 / 100 % | 93 / 95 % | 94 / 97 % | 94 / 96 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 30 / 58 % | 98 / 100 % | – | 81 / 87 % | 46 / 74 % | 20 / 43 % | 69 / 83 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 40 % | 87 / 97 % | – | 97 / 99 % | 32 / 62 % | 23 / 47 % | 31 / 54 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 71 / 95 % | – | 96 / 98 % | 17 / 45 % | 3 / 14 % | 22 / 45 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 13 / 44 % | 86 / 98 % | – | 29 / 68 % | 59 / 82 % | 27 / 53 % | 65 / 80 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 18 / 45 % | 12 / 53 % | – | 83 / 94 % | 34 / 64 % | 15 / 38 % | 20 / 59 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 18 / 51 % | 56 / 95 % | – | 82 / 93 % | 41 / 67 % | 19 / 41 % | 27 / 45 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 41 % | 81 / 98 % | – | 29 / 56 % | 33 / 59 % | 7 / 28 % | 17 / 41 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 30 / 56 % | 79 / 97 % | – | 79 / 93 % | 77 / 89 % | 62 / 78 % | 74 / 86 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 24 / 58 % | 63 / 97 % | – | 76 / 90 % | 44 / 70 % | 15 / 46 % | 40 / 69 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 25 / 54 % | 75 / 98 % | – | 37 / 54 % | 52 / 76 % | 33 / 53 % | 40 / 67 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 25 / 58 % | 74 / 91 % | – | 57 / 85 % | 49 / 72 % | 37 / 61 % | 49 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 19 / 52 % | 55 / 99 % | – | 72 / 91 % | 43 / 67 % | 11 / 38 % | 29 / 57 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 31 / 60 % | 54 / 97 % | – | 72 / 92 % | 59 / 79 % | 45 / 68 % | 69 / 82 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 35 / 94 % | – | 69 / 83 % | 9 / 25 % | 0 / 0 % | 5 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 13 / 38 % | 66 / 99 % | – | 52 / 75 % | 12 / 35 % | 8 / 26 % | 12 / 27 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 15 / 43 % | 64 / 97 % | – | 14 / 38 % | 25 / 54 % | 5 / 15 % | 38 / 61 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 24 / 90 % | – | 50 / 72 % | 31 / 59 % | 9 / 25 % | 17 / 36 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 17 / 50 % | 28 / 96 % | – | 44 / 67 % | 29 / 51 % | 12 / 28 % | 47 / 63 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 43 / 87 % | – | 16 / 59 % | 21 / 48 % | 14 / 24 % | 26 / 44 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 24 / 56 % | 23 / 92 % | – | 19 / 40 % | 41 / 68 % | 13 / 36 % | 41 / 66 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 16 / 33 % | 38 / 98 % | – | 20 / 57 % | 21 / 46 % | 4 / 19 % | 10 / 25 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 12 / 45 % | 15 / 78 % | – | 0 / 0 % | 36 / 64 % | 10 / 30 % | 32 / 62 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 50 % | 33 / 97 % | – | 0 / 0 % | 11 / 30 % | 4 / 12 % | 11 / 24 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 17 / 45 % | – | 25 / 48 % | 7 / 18 % | 0 / 0 % | 7 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 7 / 24 % | 25 / 84 % | – | 1 / 16 % | 8 / 22 % | 5 / 18 % | 9 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 23 / 80 % | – | 3 / 23 % | 0 / 0 % | 2 / 7 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 23 / 56 % | – | 0 / 0 % | 8 / 22 % | 1 / 5 % | 10 / 22 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 16 / 93 % | – | 12 / 48 % | 22 / 54 % | 4 / 22 % | 16 / 47 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 22 / 74 % | – | 1 / 23 % | 0 / 0 % | 0 / 0 % | 5 / 16 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 5 / 48 % | – | 0 / 0 % | 20 / 45 % | 0 / 0 % | 18 / 33 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 11 / 94 % | – | 2 / 16 % | 16 / 47 % | 1 / 6 % | 18 / 31 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 29 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 4 / 49 % | – | 0 / 0 % | 9 / 27 % | 0 / 0 % | 10 / 16 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 10 / 85 % | – | 0 / 0 % | 7 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 10 / 18 % | 3 / 46 % | – | 0 / 0 % | 9 / 22 % | 1 / 5 % | 9 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 10 / 94 % | – | 0 / 0 % | 0 / 0 % | 0 / 3 % | 7 / 12 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 2 % | 9 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 9 / 28 % | 5 / 66 % | – | 1 / 14 % | 8 / 25 % | 4 / 13 % | 8 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 5 / 43 % | – | 9 / 38 % | 6 / 14 % | 1 / 5 % | 5 / 9 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 27 % | 4 / 10 % | 7 / 21 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 46 % | – | 0 / 0 % | 8 / 19 % | 1 / 3 % | 6 / 19 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 7 / 47 % | – | 0 / 0 % | 6 / 21 % | 0 / 0 % | 7 / 16 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 5 / 53 % | – | 0 / 0 % | 6 / 13 % | 1 / 3 % | 0 / 0 % |
