[English](README.md) · [Deutsch](README.de.md)

# Fast Remediation Is the New Trust Model: JFrog and OpenAI Collaboration on Zero-Day Security Findings

Bericht Q004817 · Quelle jfrog.com · Datum 2026-07-27 · [Original öffnen](https://jfrog.com/blog/jfrog-and-openai-collaboration-on-zero-day-security-findings/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

JFrog zufolge fanden OpenAI-Modelle bislang unbekannte Schwachstellen in selbst gehostetem Artifactory; nach verantwortungsvoller Meldung habe JFrog Korrekturen für Cloud- und selbst gehostete Kunden bereitgestellt. Der Beitrag betont schnelle Behebung als entscheidenden Schutz und warnt, dass Agenten zugängliche Ressourcen wie liegengebliebene Zugangsdaten verwenden könnten; technische Einzelheiten und unabhängige Bestätigung fehlen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 47 / 69 % | 97 / 99 % | 99 / 99 % | 80 / 89 % | 66 / 79 % | 74 / 85 % | 75 / 87 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 28 / 50 % | 85 / 97 % | 97 / 99 % | 56 / 77 % | 23 / 50 % | 47 / 73 % | 22 / 68 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 35 / 55 % | 77 / 90 % | 97 / 99 % | 70 / 84 % | 55 / 74 % | 53 / 72 % | 61 / 86 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 58 / 80 % | 96 / 98 % | 9 / 24 % | 1 / 4 % | 6 / 9 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 27 / 48 % | 84 / 99 % | 95 / 98 % | 52 / 75 % | 25 / 48 % | 43 / 66 % | 19 / 63 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 21 / 48 % | 42 / 74 % | 87 / 95 % | 57 / 77 % | 15 / 38 % | 35 / 59 % | 40 / 73 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 34 % | 38 / 78 % | 75 / 86 % | 20 / 46 % | 7 / 22 % | 26 / 44 % | 1 / 7 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 30 / 52 % | 29 / 77 % | 75 / 88 % | 53 / 77 % | 53 / 73 % | 42 / 71 % | 45 / 83 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 25 / 48 % | 72 / 92 % | 70 / 82 % | 46 / 69 % | 36 / 53 % | 49 / 66 % | 25 / 56 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 32 / 52 % | 50 / 85 % | 51 / 73 % | 58 / 77 % | 19 / 38 % | 24 / 42 % | 9 / 30 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 53 / 78 % | 18 / 44 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 43 / 90 % | 48 / 77 % | 11 / 28 % | 3 / 8 % | 10 / 18 % | 1 / 8 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 48 / 69 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 43 / 58 % | 20 / 44 % | 5 / 16 % | 10 / 24 % | 7 / 28 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 38 / 64 % | 40 / 68 % | 7 / 22 % | 1 / 3 % | 4 / 12 % | 0 / 3 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 23 / 46 % | 7 / 65 % | 23 / 41 % | 25 / 57 % | 23 / 46 % | 39 / 67 % | 8 / 34 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 3 / 30 % | 35 / 54 % | 9 / 27 % | 2 / 7 % | 10 / 20 % | 1 / 8 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 32 / 89 % | 34 / 57 % | 7 / 18 % | 1 / 5 % | 5 / 10 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 57 % | 4 / 10 % | 20 / 34 % | 1 / 5 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 13 / 38 % | 25 / 72 % | 11 / 39 % | 30 / 56 % | 12 / 35 % | 26 / 51 % | 5 / 22 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 20 / 44 % | 27 / 75 % | 8 / 50 % | 25 / 52 % | 10 / 24 % | 11 / 32 % | 10 / 51 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 8 / 42 % | 26 / 55 % | 15 / 43 % | 6 / 18 % | 11 / 27 % | 1 / 8 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 14 / 45 % | 13 / 77 % | 14 / 55 % | 6 / 15 % | 8 / 28 % | 20 / 50 % | 7 / 45 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 13 / 30 % | 0 / 0 % | 9 / 27 % | 16 / 41 % | 0 / 0 % | 11 / 26 % | 2 / 14 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 15 / 40 % | 6 / 20 % | 1 / 6 % | 4 / 10 % | 0 / 7 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 34 % | 1 / 5 % | 14 / 24 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 7 / 52 % | 8 / 44 % | 13 / 43 % | 0 / 0 % | 14 / 28 % | 4 / 26 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 12 / 32 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 2 / 9 % | 12 / 22 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 4 / 11 % | 6 / 15 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 3 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 3 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 5 / 11 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 1 % | 3 / 6 % | 0 / 0 % | – |
