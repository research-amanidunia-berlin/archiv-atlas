[English](README.md) · [Deutsch](README.de.md)

# Key Practices for Incident Readiness and Response in Super Intelligence Training and Evaluation

Bericht Q000147 · Quelle go.dhs.gov · Datum 2026-10-16 · [Original öffnen](https://go.dhs.gov/5rZ)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Text beschreibt eine freiwillige Anleitung von NIST, NSA SISC und CISA zur Vorbereitung auf Kontrollvorfälle mit leistungsfähigen Super-Intelligence-Agenten. Sie behandelt unter anderem Zugriffsbeschränkung, Überwachung, Beweissicherung, Eindämmung und Meldung von Vorfällen. Der vorliegende Text ist nur eine kurze Vorstellung der Anleitung; die zehn Praktiken werden nicht einzeln erläutert.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 47 / 61 % | 94 / 99 % | – | 66 / 83 % | 61 / 81 % | 61 / 80 % | 64 / 83 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 49 / 65 % | 88 / 97 % | – | 73 / 87 % | 84 / 92 % | 85 / 92 % | 85 / 94 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 42 / 63 % | 71 / 93 % | – | 73 / 86 % | 66 / 83 % | 76 / 85 % | 86 / 93 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 37 / 58 % | 82 / 92 % | – | 62 / 78 % | 49 / 63 % | 64 / 76 % | 86 / 91 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 55 / 73 % | 72 / 91 % | – | 77 / 88 % | 73 / 86 % | 83 / 90 % | 85 / 93 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 42 / 61 % | 67 / 83 % | – | 72 / 85 % | 72 / 84 % | 80 / 88 % | 64 / 75 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 30 / 53 % | 52 / 89 % | – | 35 / 61 % | 24 / 49 % | 65 / 79 % | 32 / 61 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 24 / 41 % | 35 / 53 % | – | 55 / 76 % | 19 / 39 % | 57 / 73 % | 26 / 56 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 25 / 49 % | 54 / 88 % | – | 42 / 71 % | 28 / 56 % | 48 / 71 % | 24 / 58 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 43 / 61 % | 39 / 74 % | – | 43 / 66 % | 45 / 66 % | 53 / 70 % | 43 / 68 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 30 % | 43 / 89 % | – | 19 / 47 % | 9 / 29 % | 16 / 47 % | 7 / 22 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 17 / 44 % | 42 / 91 % | – | 38 / 65 % | 21 / 49 % | 28 / 53 % | 20 / 48 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 39 / 76 % | – | 28 / 52 % | 21 / 40 % | 36 / 55 % | 9 / 23 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 33 / 81 % | – | 16 / 45 % | 2 / 10 % | 5 / 16 % | 2 / 10 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 32 / 61 % | – | 9 / 22 % | 7 / 15 % | 10 / 20 % | 1 / 5 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 12 / 35 % | 27 / 69 % | – | 13 / 31 % | 12 / 29 % | 31 / 61 % | 7 / 23 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 30 / 51 % | 26 / 91 % | – | 31 / 55 % | 13 / 30 % | 21 / 46 % | 14 / 34 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 30 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 24 / 48 % | – | 8 / 23 % | 2 / 6 % | 7 / 16 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 24 / 44 % | 0 / 0 % | – | 20 / 47 % | 7 / 19 % | 9 / 23 % | 8 / 23 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 23 / 58 % | – | 6 / 15 % | 2 / 5 % | 5 / 10 % | 1 / 3 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 22 / 55 % | – | 8 / 19 % | 4 / 12 % | 0 / 0 % | 1 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 19 / 78 % | – | 6 / 14 % | 0 / 1 % | 7 / 15 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 16 / 40 % | 18 / 39 % | 13 / 35 % | 9 / 23 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 12 / 43 % | 0 / 0 % | – | 18 / 44 % | 7 / 18 % | 8 / 20 % | 7 / 20 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 9 / 26 % | 4 / 15 % | 15 / 33 % | 2 / 10 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | – | 15 / 43 % | 3 / 8 % | 9 / 20 % | 1 / 5 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 14 / 40 % | – | 8 / 22 % | 4 / 14 % | 8 / 17 % | 1 / 5 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | – | 14 / 35 % | 5 / 12 % | 7 / 17 % | 2 / 8 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 29 % | 0 / 0 % | – | 7 / 20 % | 2 / 8 % | 7 / 15 % | 0 / 3 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 11 / 56 % | – | 5 / 12 % | 1 / 4 % | 5 / 10 % | 0 / 2 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 9 / 62 % | – | 9 / 28 % | 4 / 11 % | 7 / 17 % | 1 / 8 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 9 / 21 % | 0 / 3 % | 4 / 8 % | 1 / 3 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 8 / 19 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | – | 8 / 17 % | 2 / 7 % | 5 / 13 % | 1 / 5 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 7 / 18 % | 1 / 3 % | 5 / 13 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | 4 / 10 % | 4 / 8 % | 0 / 0 % | – |
