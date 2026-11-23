[English](README.md) · [Deutsch](README.de.md)

# Initial policy considerations for generative artificial intelligence

Bericht Q005994 · Quelle oecd.ai · Datum 2023-09-18 · [Original öffnen](https://oecd.ai/en/ai-publications/initial-considerations-genai)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der OECD-Beitrag beschreibt Chancen generativer KI und politische Risiken für Informationsqualität, geistiges Eigentum, Arbeitsmärkte und gesellschaftliche Kontrolle. Er fordert frühzeitige Maßnahmen, betont aber, dass wichtige Rechtsfragen und langfristige Folgen ungewiss sind und manche Sicherheitsbedenken umstritten bleiben.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 39 / 85 % | 78 / 95 % | 12 / 38 % | 2 / 16 % | 7 / 21 % | 1 / 11 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 25 / 50 % | 77 / 96 % | 74 / 96 % | 34 / 67 % | 14 / 50 % | 22 / 64 % | 11 / 64 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 18 / 48 % | 8 / 90 % | 65 / 96 % | 23 / 57 % | 9 / 40 % | 12 / 57 % | 7 / 58 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 13 / 40 % | 60 / 93 % | 11 / 50 % | 11 / 44 % | 6 / 30 % | 14 / 41 % | 2 / 15 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 39 % | 57 / 94 % | 36 / 82 % | 13 / 41 % | 8 / 39 % | 13 / 55 % | 6 / 43 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 37 % | 54 / 90 % | 50 / 80 % | 13 / 43 % | 5 / 27 % | 9 / 33 % | 2 / 19 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 12 / 39 % | 16 / 91 % | 43 / 77 % | 16 / 47 % | 4 / 23 % | 7 / 26 % | 2 / 15 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 19 / 48 % | 39 / 97 % | 22 / 72 % | 40 / 71 % | 36 / 65 % | 41 / 73 % | 26 / 72 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 30 / 93 % | 10 / 61 % | 12 / 40 % | 5 / 22 % | 8 / 24 % | 1 / 11 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 25 % | 24 / 77 % | 1 / 29 % | 6 / 21 % | 5 / 24 % | 7 / 22 % | 1 / 13 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 21 / 48 % | 22 / 73 % | 10 / 56 % | 22 / 53 % | 6 / 28 % | 20 / 47 % | 13 / 47 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 20 / 75 % | 5 / 45 % | 7 / 27 % | 1 / 8 % | 3 / 9 % | 0 / 3 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 17 / 78 % | 2 / 38 % | 7 / 25 % | 0 / 6 % | 5 / 14 % | 0 / 3 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 11 / 41 % | 17 / 78 % | 2 / 29 % | 10 / 31 % | 5 / 29 % | 7 / 29 % | 1 / 15 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 11 / 38 % | 15 / 90 % | 17 / 66 % | 9 / 35 % | 5 / 31 % | 7 / 31 % | 1 / 15 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 5 / 24 % | 11 / 74 % | 2 / 43 % | 16 / 46 % | 3 / 18 % | 4 / 14 % | 1 / 7 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 7 / 28 % | 10 / 88 % | 7 / 43 % | 15 / 41 % | 5 / 26 % | 8 / 30 % | 3 / 21 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 15 / 62 % | 0 / 0 % | 6 / 18 % | 1 / 9 % | 4 / 9 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 6 / 32 % | 14 / 74 % | 1 / 35 % | 9 / 30 % | 4 / 22 % | 8 / 29 % | 1 / 10 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 13 / 38 % | 4 / 61 % | 0 / 0 % | 6 / 29 % | 3 / 17 % | 6 / 19 % | 0 / 7 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 12 / 35 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 1 / 7 % | 6 / 15 % | 0 / 4 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 11 / 79 % | 0 / 0 % | 5 / 12 % | 2 / 9 % | 5 / 10 % | 0 / 2 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 10 / 34 % | 2 / 65 % | 11 / 46 % | 11 / 42 % | 4 / 23 % | 9 / 21 % | 1 / 8 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 27 % | 0 / 17 % | 0 / 4 % | 5 / 16 % | 1 / 5 % | 5 / 11 % | 0 / 2 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 5 / 28 % | 10 / 89 % | 4 / 59 % | 9 / 30 % | 2 / 16 % | 3 / 14 % | 1 / 9 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 10 / 38 % | 9 / 94 % | 7 / 42 % | 10 / 33 % | 4 / 25 % | 6 / 27 % | 2 / 13 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 10 / 67 % | 0 / 6 % | 7 / 20 % | 2 / 11 % | 5 / 14 % | 0 / 3 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 10 / 28 % | 4 / 76 % | 0 / 0 % | 7 / 22 % | 3 / 16 % | 7 / 22 % | 1 / 10 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 9 / 71 % | 3 / 44 % | 7 / 29 % | 1 / 7 % | 4 / 16 % | 0 / 4 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 9 / 39 % | 1 / 31 % | 0 / 0 % | 5 / 20 % | 1 / 7 % | 1 / 6 % | 0 / 6 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 2 / 76 % | 8 / 54 % | 7 / 23 % | 1 / 11 % | 4 / 8 % | 0 / 5 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 32 % | 1 / 66 % | 0 / 8 % | 6 / 19 % | 1 / 9 % | 5 / 15 % | 0 / 5 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 6 / 13 % | 0 / 2 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 6 / 25 % | 1 / 26 % | 0 / 0 % | 5 / 14 % | 1 / 8 % | 5 / 11 % | 0 / 2 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 5 / 57 % | 1 / 33 % | 6 / 21 % | 2 / 14 % | 4 / 14 % | 0 / 9 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 7 % | 2 / 5 % | 0 / 4 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 2 / 94 % | 0 / 5 % | 5 / 15 % | 1 / 10 % | 4 / 10 % | 0 / 4 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 1 / 93 % | 0 / 11 % | 5 / 16 % | 1 / 9 % | 3 / 10 % | 0 / 2 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 4 % | 5 / 15 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 3 / 95 % | 0 / 4 % | 5 / 14 % | 1 / 8 % | 5 / 12 % | 0 / 2 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 0 / 3 % | 2 / 6 % | 0 / 3 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 4 / 40 % | 0 / 0 % | 5 / 10 % | 1 / 6 % | 4 / 10 % | 0 / 0 % | – |
