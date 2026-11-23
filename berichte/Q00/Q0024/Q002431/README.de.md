[English](README.md) · [Deutsch](README.de.md)

# Guidelines on obligations for General-Purpose AI providers

Bericht Q002431 · Quelle digital-strategy.ec.europa.eu · Datum – · [Original öffnen](http://digital-strategy.ec.europa.eu/en/faqs/guidelines-obligations-general-purpose-ai-providers)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht erläutert die EU-Kommissionsleitlinien zu Pflichten für Anbieter allgemeiner KI-Modelle: Dokumentation, nachgelagerte Information, Urheberrecht und Transparenz; bei systemischem Risiko kommen Sicherheits- und Meldepflichten hinzu. Die Kriterien und Open-Source-Ausnahmen sind nicht absolut, und die Leitlinien selbst sind nicht rechtsverbindlich; die Pflichten gelten ab August 2025, mit späteren Fristen für Durchsetzung und bereits zuvor bereitgestellte Modelle.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 63 / 78 % | 100 / 100 % | – | 90 / 94 % | 86 / 94 % | 91 / 95 % | 98 / 99 % | 59 / 75 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 73 / 84 % | 95 / 99 % | – | 84 / 91 % | 74 / 84 % | 89 / 93 % | 98 / 99 % | 51 / 73 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 41 / 64 % | 95 / 98 % | – | 60 / 78 % | 28 / 48 % | 70 / 83 % | 37 / 53 % | 52 / 70 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 61 / 79 % | 90 / 96 % | – | 84 / 91 % | 66 / 81 % | 85 / 91 % | 93 / 97 % | 37 / 60 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 27 / 49 % | 83 / 98 % | – | 61 / 79 % | 27 / 49 % | 75 / 84 % | 70 / 82 % | 19 / 47 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 48 / 63 % | 83 / 93 % | – | 74 / 86 % | 45 / 62 % | 72 / 83 % | 69 / 76 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 57 / 76 % | 58 / 83 % | – | 78 / 88 % | 46 / 64 % | 81 / 89 % | 76 / 87 % | 30 / 57 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 34 / 49 % | 81 / 87 % | – | 54 / 77 % | 26 / 44 % | 56 / 79 % | 41 / 49 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 49 / 68 % | 75 / 96 % | – | 68 / 84 % | 63 / 81 % | 75 / 86 % | 75 / 89 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 21 / 49 % | 73 / 92 % | – | 22 / 48 % | 45 / 66 % | 69 / 84 % | 56 / 70 % | 40 / 65 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 70 / 89 % | – | 54 / 75 % | 21 / 38 % | 37 / 55 % | 31 / 42 % | 27 / 54 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 26 / 54 % | 32 / 60 % | – | 61 / 79 % | 28 / 51 % | 46 / 65 % | 68 / 83 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 44 / 66 % | 64 / 91 % | – | 65 / 81 % | 34 / 54 % | 67 / 81 % | 60 / 74 % | 29 / 57 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 49 / 72 % | 47 / 71 % | – | 66 / 83 % | 37 / 59 % | 65 / 83 % | 56 / 85 % | 15 / 37 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 41 / 63 % | 65 / 91 % | – | 65 / 80 % | 47 / 62 % | 59 / 73 % | 45 / 61 % | 37 / 61 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 12 / 39 % | 65 / 99 % | – | 23 / 49 % | 9 / 23 % | 16 / 47 % | 7 / 22 % | 22 / 48 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 49 % | 33 / 86 % | – | 59 / 81 % | 47 / 70 % | 61 / 79 % | 63 / 82 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 15 / 34 % | 61 / 86 % | – | 23 / 48 % | 12 / 26 % | 20 / 54 % | 8 / 26 % | 15 / 34 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 37 % | 60 / 86 % | – | 12 / 31 % | 7 / 19 % | 15 / 32 % | 4 / 14 % | 9 / 24 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 56 / 90 % | – | 15 / 35 % | 7 / 20 % | 10 / 20 % | 2 / 7 % | 11 / 31 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 52 / 71 % | 12 / 27 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 26 / 51 % | 51 / 84 % | – | 42 / 64 % | 35 / 60 % | 46 / 78 % | 33 / 56 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 47 / 95 % | – | 18 / 46 % | 7 / 26 % | 15 / 40 % | 2 / 10 % | 5 / 24 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 12 / 38 % | 42 / 87 % | – | 13 / 37 % | 7 / 20 % | 12 / 35 % | 2 / 9 % | 27 / 49 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 34 / 93 % | – | 8 / 18 % | 3 / 12 % | 11 / 39 % | 1 / 5 % | 13 / 35 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 33 / 69 % | – | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 12 / 29 % | 10 / 25 % | 29 / 55 % | 14 / 25 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 29 / 63 % | – | 8 / 19 % | 4 / 13 % | 10 / 21 % | 1 / 7 % | 8 / 26 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 26 / 68 % | – | 27 / 49 % | 10 / 23 % | 28 / 47 % | 26 / 37 % | 25 / 50 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 25 / 56 % | – | 10 / 27 % | 4 / 15 % | 11 / 25 % | 2 / 7 % | 17 / 37 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | – | 18 / 45 % | 6 / 17 % | 18 / 35 % | 4 / 12 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 15 / 36 % | 5 / 15 % | 8 / 24 % | 5 / 12 % | 6 / 18 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 15 / 35 % | 5 / 11 % | 12 / 31 % | 5 / 10 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 12 / 57 % | – | 11 / 35 % | 2 / 11 % | 7 / 29 % | 1 / 6 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | – | 12 / 32 % | 0 / 0 % | 11 / 39 % | 2 / 8 % | 7 / 23 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 11 / 27 % | 5 / 13 % | 12 / 24 % | 3 / 9 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | – | 11 / 31 % | 4 / 13 % | 9 / 21 % | 2 / 11 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 11 / 40 % | 4 / 38 % | – | 9 / 22 % | 6 / 13 % | 8 / 19 % | 1 / 7 % | 7 / 27 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 9 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 8 / 19 % | 3 / 9 % | 7 / 15 % | 0 / 3 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 4 / 10 % | 0 / 0 % | 0 / 3 % | 0 / 0 % |
