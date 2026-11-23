[English](README.md) · [Deutsch](README.de.md)

# Frontier AI safety regulations: A reference for lab staff

Bericht Q002028 · Quelle metr.org · Datum 2026-01-29 · [Original öffnen](https://metr.org/notes/2026-01-29-frontier-ai-safety-regulations/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

METR fasst Anforderungen an Risikomanagement, Sicherheit, Modellberichte, Vorfallmeldungen und Hinweisgeberschutz für KI-Entwickler nach US-Bundesstaatengesetzen und dem EU-Rahmen zusammen. Fristen und Pflichten unterscheiden sich; Illinois’ ab 2028 vorgesehene unabhängige Prüfung kontrolliert laut Bericht Verfahren, nicht die tatsächliche Modellsicherheit. Die Darstellung ist eine Übersicht und ersetzt keine offiziellen Gesetzestexte.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 90 / 94 % | 98 / 98 % | 100 / 100 % | 96 / 97 % | 96 / 97 % | 98 / 99 % | 100 / 100 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 43 / 62 % | 100 / 100 % | 100 / 100 % | 88 / 93 % | 82 / 90 % | 91 / 95 % | 91 / 95 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 83 / 90 % | 98 / 99 % | 100 / 100 % | 94 / 96 % | 89 / 95 % | 96 / 97 % | 99 / 100 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 75 / 83 % | 95 / 97 % | 100 / 100 % | 90 / 94 % | 87 / 93 % | 95 / 97 % | 99 / 100 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 57 / 70 % | 99 / 100 % | 95 / 99 % | 86 / 93 % | 89 / 95 % | 92 / 96 % | 93 / 97 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 61 / 75 % | 92 / 96 % | 99 / 100 % | 88 / 94 % | 82 / 91 % | 92 / 97 % | 96 / 98 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 59 / 79 % | 87 / 97 % | 99 / 100 % | 63 / 81 % | 49 / 66 % | 75 / 87 % | 80 / 95 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 54 / 67 % | 97 / 99 % | 92 / 97 % | 75 / 87 % | 82 / 91 % | 72 / 86 % | 77 / 92 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 33 / 58 % | 96 / 99 % | 78 / 92 % | 44 / 66 % | 28 / 47 % | 39 / 67 % | 15 / 37 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 48 / 65 % | 96 / 97 % | 92 / 96 % | 90 / 94 % | 81 / 92 % | 87 / 93 % | 80 / 91 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 65 / 78 % | 96 / 98 % | 86 / 92 % | 88 / 93 % | 81 / 90 % | 91 / 95 % | 95 / 98 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 58 / 75 % | 95 / 98 % | 95 / 98 % | 74 / 85 % | 61 / 75 % | 84 / 91 % | 88 / 94 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 58 / 74 % | 84 / 98 % | 86 / 94 % | 86 / 92 % | 76 / 87 % | 93 / 96 % | 94 / 97 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 52 / 68 % | 69 / 94 % | 33 / 75 % | 79 / 88 % | 44 / 60 % | 66 / 81 % | 92 / 97 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 29 / 56 % | 84 / 99 % | 84 / 92 % | 18 / 41 % | 13 / 27 % | 14 / 33 % | 3 / 22 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 60 / 87 % | 72 / 92 % | 40 / 61 % | 8 / 21 % | 29 / 54 % | 3 / 14 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 29 / 47 % | 41 / 75 % | 3 / 26 % | 48 / 71 % | 18 / 41 % | 66 / 83 % | 14 / 35 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 41 / 61 % | 32 / 75 % | 45 / 78 % | 65 / 81 % | 38 / 63 % | 61 / 82 % | 18 / 43 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 16 / 40 % | 65 / 90 % | 36 / 64 % | 15 / 36 % | 9 / 21 % | 15 / 43 % | 4 / 25 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 19 / 42 % | 48 / 91 % | 7 / 33 % | 45 / 68 % | 16 / 34 % | 60 / 79 % | 19 / 37 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 25 % | 52 / 77 % | 59 / 87 % | 26 / 47 % | 9 / 24 % | 10 / 32 % | 5 / 24 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 21 / 45 % | 48 / 79 % | 45 / 83 % | 30 / 53 % | 56 / 78 % | 58 / 83 % | 39 / 72 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 54 / 83 % | 56 / 74 % | 25 / 50 % | 13 / 31 % | 33 / 58 % | 4 / 12 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 13 / 36 % | 53 / 83 % | 6 / 26 % | 15 / 38 % | 8 / 21 % | 18 / 42 % | 3 / 15 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 26 % | 49 / 79 % | 15 / 37 % | 16 / 40 % | 7 / 20 % | 9 / 27 % | 1 / 5 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 47 / 92 % | 0 / 0 % | 18 / 40 % | 11 / 28 % | 26 / 62 % | 10 / 26 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 42 / 94 % | 11 / 37 % | 16 / 39 % | 11 / 25 % | 21 / 52 % | 1 / 8 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 41 / 75 % | 0 / 0 % | 18 / 39 % | 7 / 17 % | 18 / 34 % | 2 / 11 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 41 / 83 % | 0 / 0 % | 9 / 22 % | 5 / 12 % | 9 / 22 % | 0 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 40 / 75 % | 13 / 39 % | 10 / 30 % | 4 / 13 % | 9 / 27 % | 1 / 7 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 18 / 39 % | 32 / 55 % | 15 / 29 % | 25 / 54 % | 23 / 40 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 32 / 54 % | 17 / 31 % | 0 / 0 % | 4 / 10 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 30 / 58 % | 10 / 22 % | 18 / 42 % | 3 / 10 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 20 / 36 % | 29 / 55 % | 18 / 45 % | 15 / 33 % | 11 / 25 % | 23 / 51 % | 2 / 8 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 22 / 56 % | 0 / 0 % | 29 / 53 % | 19 / 37 % | 20 / 46 % | 13 / 28 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 19 / 65 % | 19 / 49 % | 17 / 44 % | 0 / 0 % | 9 / 24 % | 1 / 5 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 11 / 44 % | 18 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 14 / 27 % | 1 / 3 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 4 / 9 % | 12 / 21 % | 1 / 6 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 23 % | 6 / 12 % | 11 / 25 % | 0 / 4 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 10 / 54 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 9 / 23 % | 0 / 1 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 22 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 5 / 9 % | 7 / 14 % | 0 / 3 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
