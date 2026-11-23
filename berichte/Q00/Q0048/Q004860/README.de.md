[English](README.md) · [Deutsch](README.de.md)

# Amazon Nova Micro, Lite, Pro, and Premier - AWS AI Service Cards

Bericht Q004860 · Quelle docs.aws.amazon.com · Datum 2025-04-30 · [Original öffnen](https://docs.aws.amazon.com/ai/responsible-ai/nova-micro-lite-pro/overview.html)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Die AWS-Servicekarte beschreibt vier Nova-Modelle mit unterschiedlichen Text- und Multimodalfähigkeiten sowie Einsatzmöglichkeiten von Zusammenfassungen bis zu RAG und agentischen Abläufen. AWS weist auf variable, teils fehlerhafte Ausgaben hin und empfiehlt eigene Tests, klare Kriterien und menschliche Aufsicht bei sensiblen Anwendungen; die genannten Leistungs- und Sicherheitswerte stammen aus AWS-Prüfungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 35 / 53 % | 100 / 100 % | 100 / 100 % | 72 / 86 % | 15 / 32 % | 57 / 70 % | 37 / 58 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 53 / 71 % | 96 / 99 % | 100 / 100 % | 82 / 91 % | 37 / 61 % | 78 / 88 % | 76 / 89 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 46 / 64 % | 98 / 99 % | 99 / 100 % | 24 / 49 % | 36 / 56 % | 77 / 86 % | 93 / 96 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 29 / 50 % | 93 / 94 % | 98 / 99 % | 73 / 86 % | 18 / 32 % | 59 / 70 % | 79 / 84 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 22 / 42 % | 90 / 99 % | 97 / 99 % | 19 / 43 % | 10 / 24 % | 19 / 41 % | 5 / 14 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 23 / 45 % | 87 / 100 % | 96 / 98 % | 70 / 86 % | 36 / 62 % | 70 / 84 % | 44 / 69 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 51 / 81 % | 94 / 98 % | 13 / 39 % | 4 / 12 % | 9 / 19 % | 1 / 4 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 29 / 52 % | 75 / 99 % | 93 / 98 % | 61 / 82 % | 26 / 55 % | 44 / 75 % | 37 / 61 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 36 / 56 % | 91 / 97 % | 92 / 95 % | 69 / 86 % | 40 / 62 % | 78 / 89 % | 79 / 90 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 42 % | 83 / 96 % | 85 / 92 % | 37 / 64 % | 20 / 37 % | 34 / 54 % | 23 / 42 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 84 / 97 % | 80 / 95 % | 32 / 63 % | 11 / 35 % | 30 / 58 % | 9 / 24 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 83 / 99 % | 58 / 90 % | 53 / 76 % | 8 / 23 % | 21 / 47 % | 12 / 25 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 22 / 62 % | 80 / 91 % | 56 / 77 % | 11 / 23 % | 8 / 20 % | 10 / 20 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 19 / 39 % | 77 / 97 % | 40 / 56 % | 58 / 79 % | 10 / 29 % | 49 / 63 % | 39 / 46 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 64 / 85 % | 72 / 89 % | 41 / 66 % | 9 / 30 % | 26 / 50 % | 11 / 25 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 60 / 84 % | 7 / 17 % | 10 / 25 % | 4 / 14 % | 8 / 18 % | 1 / 8 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 23 / 90 % | 59 / 74 % | 32 / 59 % | 17 / 29 % | 26 / 43 % | 30 / 40 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 25 / 41 % | 58 / 84 % | 41 / 67 % | 44 / 64 % | 10 / 31 % | 31 / 45 % | 5 / 9 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 56 / 90 % | 44 / 64 % | 29 / 52 % | 13 / 34 % | 27 / 44 % | 10 / 21 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 53 / 76 % | 10 / 25 % | 4 / 12 % | 8 / 17 % | 1 / 3 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 42 % | 52 / 94 % | 36 / 61 % | 22 / 49 % | 9 / 29 % | 29 / 53 % | 8 / 19 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 45 / 90 % | 40 / 66 % | 9 / 26 % | 4 / 12 % | 7 / 16 % | 0 / 2 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 44 / 66 % | 16 / 38 % | 4 / 12 % | 10 / 24 % | 2 / 10 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 42 / 92 % | 13 / 27 % | 13 / 37 % | 2 / 9 % | 11 / 20 % | 0 / 2 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 40 / 77 % | 39 / 60 % | 18 / 43 % | 4 / 13 % | 17 / 34 % | 4 / 9 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 62 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 27 % | 31 / 83 % | 21 / 48 % | 9 / 26 % | 2 / 11 % | 6 / 17 % | 1 / 4 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 29 / 63 % | 12 / 28 % | 10 / 27 % | 3 / 12 % | 7 / 16 % | 1 / 4 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 27 / 50 % | 20 / 50 % | 2 / 8 % | 13 / 32 % | 1 / 5 % | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 22 / 45 % | 13 / 32 % | 4 / 10 % | 13 / 27 % | 1 / 4 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 22 / 93 % | 11 / 39 % | 10 / 25 % | 3 / 13 % | 12 / 32 % | 2 / 7 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 45 % | 0 / 0 % | 0 / 0 % | 22 / 48 % | 4 / 13 % | 6 / 13 % | 7 / 16 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 36 % | 5 / 27 % | 1 / 18 % | 12 / 38 % | 4 / 12 % | 10 / 23 % | 1 / 4 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 35 % | 4 / 14 % | 13 / 35 % | 2 / 7 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 11 / 25 % | 3 / 10 % | 6 / 14 % | 1 / 4 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 2 / 6 % | 8 / 19 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 1 / 5 % | 4 / 11 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 9 / 20 % | 2 / 7 % | 7 / 14 % | 0 / 2 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 7 / 16 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 7 / 18 % | 2 / 7 % | 0 / 0 % | 0 / 2 % | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 10 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 15 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 6 / 13 % | 0 / 0 % | – |
