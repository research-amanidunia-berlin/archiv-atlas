[English](README.md) · [Deutsch](README.de.md)

# How we think about safety and alignment

Bericht Q009304 · Quelle openai.com · Datum – · [Original öffnen](https://openai.com/safety/how-we-think-about-safety-alignment/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt Sicherheit als fortlaufende Arbeit: Risiken sollen durch Tests, schrittweise Einführung, mehrere Schutzschichten und menschliche Aufsicht erkannt und begrenzt werden. Der Bericht nennt Missbrauch, Fehlanpassung und gesellschaftliche Umbrüche als mögliche Gefahren, betont aber, dass wichtige Fragen offen sind und die Wirksamkeit der dargestellten Ansätze hier nicht unabhängig geprüft wird.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 60 / 77 % | 100 / 100 % | 99 / 100 % | 89 / 94 % | 83 / 93 % | 88 / 94 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 38 / 64 % | 97 / 98 % | 99 / 100 % | 62 / 82 % | 74 / 87 % | 79 / 91 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 33 / 58 % | 97 / 100 % | 97 / 100 % | 63 / 84 % | 70 / 86 % | 74 / 88 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 36 / 64 % | 84 / 93 % | 94 / 98 % | 60 / 80 % | 63 / 79 % | 55 / 76 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 23 / 53 % | 93 / 99 % | 48 / 91 % | 56 / 79 % | 31 / 60 % | 38 / 70 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 90 / 99 % | 93 / 98 % | 22 / 51 % | 8 / 31 % | 18 / 44 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 21 / 47 % | 92 / 99 % | 77 / 94 % | 60 / 80 % | 29 / 58 % | 42 / 69 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 31 / 56 % | 91 / 100 % | 86 / 99 % | 62 / 83 % | 52 / 80 % | 63 / 86 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 27 / 52 % | 91 / 98 % | 90 / 97 % | 64 / 81 % | 71 / 83 % | 77 / 88 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 30 / 54 % | 89 / 96 % | 77 / 93 % | 69 / 84 % | 40 / 60 % | 67 / 78 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 33 / 55 % | 63 / 93 % | 85 / 97 % | 69 / 86 % | 32 / 61 % | 63 / 80 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 31 / 63 % | 69 / 89 % | 84 / 98 % | 73 / 87 % | 64 / 83 % | 73 / 87 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 21 / 47 % | 62 / 98 % | 84 / 96 % | 47 / 72 % | 27 / 51 % | 48 / 76 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 38 / 62 % | 66 / 96 % | 75 / 94 % | 73 / 87 % | 73 / 90 % | 83 / 92 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 26 / 51 % | 82 / 95 % | 71 / 83 % | 64 / 82 % | 43 / 65 % | 69 / 82 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 48 % | 79 / 99 % | 52 / 80 % | 38 / 64 % | 9 / 40 % | 28 / 54 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 31 / 50 % | 78 / 97 % | 61 / 71 % | 56 / 74 % | 41 / 57 % | 63 / 77 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 17 / 42 % | 76 / 98 % | 69 / 84 % | 25 / 53 % | 20 / 46 % | 29 / 71 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 74 / 97 % | 15 / 53 % | 20 / 44 % | 6 / 19 % | 23 / 48 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 10 / 41 % | 66 / 93 % | 13 / 44 % | 41 / 67 % | 15 / 37 % | 33 / 57 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 30 % | 61 / 85 % | 51 / 69 % | 28 / 57 % | 11 / 34 % | 20 / 51 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 39 / 83 % | 53 / 80 % | 15 / 41 % | 4 / 15 % | 11 / 29 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 21 / 44 % | 48 / 82 % | 12 / 41 % | 30 / 57 % | 10 / 27 % | 15 / 41 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 15 / 41 % | 44 / 88 % | 40 / 71 % | 19 / 47 % | 14 / 45 % | 19 / 60 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 30 / 89 % | 39 / 79 % | 42 / 70 % | 20 / 48 % | 13 / 38 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 51 % | 38 / 82 % | 35 / 69 % | 33 / 61 % | 35 / 61 % | 19 / 48 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 33 % | 37 / 97 % | 30 / 64 % | 18 / 48 % | 13 / 33 % | 15 / 36 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 8 / 29 % | 35 / 96 % | 12 / 52 % | 19 / 45 % | 8 / 27 % | 10 / 42 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 31 / 77 % | 21 / 46 % | 12 / 34 % | 8 / 26 % | 11 / 22 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 12 / 25 % | 26 / 95 % | 18 / 59 % | 15 / 46 % | 3 / 10 % | 8 / 30 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 26 / 69 % | 4 / 23 % | 6 / 19 % | 3 / 13 % | 7 / 18 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 8 / 22 % | 22 / 74 % | 2 / 15 % | 10 / 30 % | 7 / 26 % | 11 / 27 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 20 / 60 % | 0 / 16 % | 0 / 0 % | 5 / 13 % | 6 / 18 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 42 % | 7 / 20 % | 8 / 16 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 7 / 45 % | 0 / 0 % | 17 / 46 % | 7 / 23 % | 9 / 34 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 9 / 27 % | 16 / 64 % | 15 / 62 % | 11 / 30 % | 7 / 22 % | 11 / 31 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 16 / 65 % | 0 / 0 % | 13 / 29 % | 6 / 20 % | 9 / 17 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 16 / 90 % | 0 / 13 % | 7 / 19 % | 4 / 20 % | 5 / 14 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 1 / 7 % | 10 / 20 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 9 / 19 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 3 / 90 % | 3 / 39 % | 7 / 22 % | 3 / 13 % | 8 / 24 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 8 / 85 % | 3 / 36 % | 8 / 31 % | 1 / 8 % | 8 / 23 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 7 / 35 % | 7 / 82 % | 0 / 6 % | 7 / 23 % | 7 / 17 % | 6 / 17 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 7 % | 6 / 19 % | – | – |
