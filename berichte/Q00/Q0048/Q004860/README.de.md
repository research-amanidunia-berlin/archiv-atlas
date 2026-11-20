[English](README.md) · [Deutsch](README.de.md)

# Amazon Nova Micro, Lite, Pro, and Premier - AWS AI Service Cards

Bericht Q004860 · Quelle docs.aws.amazon.com · Datum 2025-04-30 · [Original öffnen](https://docs.aws.amazon.com/ai/responsible-ai/nova-micro-lite-pro/overview.html)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Die AWS-Servicekarte beschreibt vier Nova-Modelle mit unterschiedlichen Text- und Multimodalfähigkeiten sowie Einsatzmöglichkeiten von Zusammenfassungen bis zu RAG und agentischen Abläufen. AWS weist auf variable, teils fehlerhafte Ausgaben hin und empfiehlt eigene Tests, klare Kriterien und menschliche Aufsicht bei sensiblen Anwendungen; die genannten Leistungs- und Sicherheitswerte stammen aus AWS-Prüfungen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 35 / 53 % | 100 / 100 % | 37 / 58 % | 100 / 100 % | 72 / 86 % | 57 / 70 % | 15 / 32 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 53 / 71 % | 96 / 99 % | 76 / 89 % | 100 / 100 % | 82 / 91 % | 78 / 88 % | 37 / 61 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 46 / 64 % | 98 / 99 % | 93 / 96 % | 99 / 100 % | 24 / 49 % | 77 / 86 % | 36 / 56 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 29 / 50 % | 93 / 94 % | 79 / 84 % | 98 / 99 % | 73 / 86 % | 59 / 70 % | 18 / 32 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 22 / 42 % | 90 / 99 % | 5 / 14 % | 97 / 99 % | 19 / 43 % | 19 / 41 % | 10 / 24 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 23 / 45 % | 87 / 100 % | 44 / 69 % | 96 / 98 % | 70 / 86 % | 70 / 84 % | 36 / 62 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 51 / 81 % | 1 / 4 % | 94 / 98 % | 13 / 39 % | 9 / 19 % | 4 / 12 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 29 / 52 % | 75 / 99 % | 37 / 61 % | 93 / 98 % | 61 / 82 % | 44 / 75 % | 26 / 55 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 36 / 56 % | 91 / 97 % | 79 / 90 % | 92 / 95 % | 69 / 86 % | 78 / 89 % | 40 / 62 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 42 % | 83 / 96 % | 23 / 42 % | 85 / 92 % | 37 / 64 % | 34 / 54 % | 20 / 37 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 84 / 97 % | 9 / 24 % | 80 / 95 % | 32 / 63 % | 30 / 58 % | 11 / 35 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 83 / 99 % | 12 / 25 % | 58 / 90 % | 53 / 76 % | 21 / 47 % | 8 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 22 / 62 % | 10 / 20 % | 80 / 91 % | 56 / 77 % | 8 / 20 % | 11 / 23 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 19 / 39 % | 77 / 97 % | 39 / 46 % | 40 / 56 % | 58 / 79 % | 49 / 63 % | 10 / 29 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 64 / 85 % | 11 / 25 % | 72 / 89 % | 41 / 66 % | 26 / 50 % | 9 / 30 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 60 / 84 % | 1 / 8 % | 7 / 17 % | 10 / 25 % | 8 / 18 % | 4 / 14 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 23 / 90 % | 30 / 40 % | 59 / 74 % | 32 / 59 % | 26 / 43 % | 17 / 29 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 25 / 41 % | 58 / 84 % | 5 / 9 % | 41 / 67 % | 44 / 64 % | 31 / 45 % | 10 / 31 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 56 / 90 % | 10 / 21 % | 44 / 64 % | 29 / 52 % | 27 / 44 % | 13 / 34 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 53 / 76 % | 10 / 25 % | 8 / 17 % | 4 / 12 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 42 % | 52 / 94 % | 8 / 19 % | 36 / 61 % | 22 / 49 % | 29 / 53 % | 9 / 29 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 45 / 90 % | 0 / 2 % | 40 / 66 % | 9 / 26 % | 7 / 16 % | 4 / 12 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 2 / 10 % | 44 / 66 % | 16 / 38 % | 10 / 24 % | 4 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 42 / 92 % | 0 / 2 % | 13 / 27 % | 13 / 37 % | 11 / 20 % | 2 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 40 / 77 % | 4 / 9 % | 39 / 60 % | 18 / 43 % | 17 / 34 % | 4 / 13 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 62 % | 0 / 0 % | 1 / 6 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 27 % | 31 / 83 % | 1 / 4 % | 21 / 48 % | 9 / 26 % | 6 / 17 % | 2 / 11 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 29 / 63 % | 1 / 4 % | 12 / 28 % | 10 / 27 % | 7 / 16 % | 3 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 27 / 50 % | 20 / 50 % | 13 / 32 % | 2 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 22 / 45 % | 13 / 32 % | 13 / 27 % | 4 / 10 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 22 / 93 % | 2 / 7 % | 11 / 39 % | 10 / 25 % | 12 / 32 % | 3 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 45 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 22 / 48 % | 6 / 13 % | 4 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 36 % | 5 / 27 % | 1 / 4 % | 1 / 18 % | 12 / 38 % | 10 / 23 % | 4 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 2 / 7 % | 0 / 0 % | 12 / 35 % | 13 / 35 % | 4 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 1 / 7 % | 11 / 25 % | 6 / 14 % | 3 / 10 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 8 / 19 % | 2 / 6 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 4 / 11 % | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 5 % | 9 / 20 % | 7 / 14 % | 2 / 7 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 3 / 9 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 4 % | 7 / 18 % | 0 / 0 % | 2 / 7 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 1 / 4 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 4 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 6 / 13 % | 1 / 4 % |
