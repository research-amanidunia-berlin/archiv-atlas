[English](README.md) · [Deutsch](README.de.md)

# Precursory Capabilities: A Refinement to Pre-deployment Information Sharing and Tripwire Capabilities

Bericht Q001566 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/governance/precursory-capabilities-a-refinement-to-pre-deployment-information-sharing-and-tripwire-capabilities)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der vorliegende Textauszug beschreibt Apollo Researchs Vorschlag, mit einer abgestuften Taxonomie vorbereitender KI-Fähigkeiten frühere Warnungen und genauere Auslöser für Informationsaustausch sowie Sicherheitsrichtlinien zu schaffen. Die erwarteten Vorteile sind Behauptungen der Autorinnen und Autoren; die Abbildung ist ausdrücklich nur beispielhaft, und nach der Überschrift „Our findings“ folgen im Auszug keine weiteren Ergebnisse.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 32 / 56 % | 99 / 100 % | – | 66 / 82 % | 67 / 83 % | 75 / 87 % | 60 / 80 % | 29 / 55 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 51 / 70 % | 98 / 99 % | – | 69 / 84 % | 69 / 83 % | 65 / 80 % | 59 / 78 % | 20 / 43 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 30 / 59 % | 91 / 99 % | – | 79 / 89 % | 64 / 80 % | 81 / 89 % | 81 / 94 % | 44 / 71 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 35 / 55 % | 78 / 95 % | – | 53 / 73 % | 40 / 58 % | 72 / 83 % | 72 / 82 % | 34 / 57 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 48 % | 70 / 95 % | – | 32 / 61 % | 13 / 34 % | 34 / 60 % | 8 / 30 % | 27 / 52 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 28 / 55 % | 67 / 92 % | – | 38 / 64 % | 33 / 65 % | 61 / 79 % | 41 / 69 % | 10 / 32 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 23 / 48 % | 65 / 96 % | – | 23 / 48 % | 10 / 25 % | 19 / 40 % | 6 / 20 % | 9 / 29 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 61 / 96 % | – | 10 / 26 % | 5 / 15 % | 7 / 23 % | 1 / 9 % | 14 / 38 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 23 / 51 % | 22 / 79 % | – | 16 / 40 % | 22 / 48 % | 60 / 78 % | 30 / 71 % | 10 / 32 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 26 / 48 % | 24 / 90 % | – | 24 / 59 % | 35 / 65 % | 59 / 80 % | 31 / 65 % | 6 / 22 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 26 / 46 % | 41 / 79 % | – | 38 / 64 % | 15 / 38 % | 56 / 75 % | 11 / 45 % | 3 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 55 / 94 % | – | 19 / 48 % | 13 / 36 % | 34 / 61 % | 8 / 28 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 31 / 53 % | 25 / 86 % | – | 55 / 77 % | 27 / 54 % | 43 / 67 % | 27 / 63 % | 11 / 39 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 49 / 90 % | – | 32 / 58 % | 15 / 31 % | 26 / 55 % | 24 / 39 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 32 / 59 % | 40 / 85 % | – | 46 / 72 % | 18 / 39 % | 37 / 65 % | 14 / 44 % | 15 / 41 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 43 % | 44 / 89 % | – | 20 / 49 % | 7 / 23 % | 19 / 40 % | 4 / 20 % | 27 / 54 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 31 / 80 % | – | 8 / 20 % | 2 / 9 % | 6 / 13 % | 0 / 4 % | 14 / 39 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 28 / 95 % | – | 12 / 33 % | 6 / 13 % | 8 / 19 % | 3 / 14 % | 6 / 20 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 26 / 74 % | – | 7 / 18 % | 3 / 10 % | 6 / 16 % | 0 / 0 % | 8 / 25 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 24 / 91 % | – | 19 / 45 % | 9 / 22 % | 20 / 40 % | 7 / 22 % | 17 / 44 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 23 / 58 % | – | 9 / 22 % | 0 / 0 % | 7 / 18 % | 0 / 4 % | 7 / 28 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 9 / 41 % | – | 15 / 43 % | 12 / 30 % | 19 / 39 % | 5 / 17 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 18 / 76 % | – | 11 / 31 % | 4 / 14 % | 11 / 29 % | 1 / 9 % | 5 / 19 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 1 / 31 % | – | 7 / 15 % | 3 / 9 % | 7 / 15 % | 0 / 0 % | 16 / 36 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 16 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | – | 15 / 42 % | 4 / 16 % | 11 / 22 % | 1 / 5 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 14 / 51 % | – | 8 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 11 / 37 % | – | 8 / 18 % | 5 / 13 % | 13 / 28 % | 1 / 5 % | 2 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 13 / 33 % | 4 / 10 % | 8 / 22 % | 1 / 5 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 11 / 28 % | 3 / 7 % | 5 / 13 % | 1 / 5 % | 4 / 19 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 2 / 33 % | – | 10 / 32 % | 0 / 0 % | 5 / 13 % | 0 / 2 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 5 / 49 % | – | 9 / 22 % | 6 / 18 % | 9 / 20 % | 1 / 6 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 7 / 19 % | 2 / 4 % | 8 / 17 % | 0 / 0 % | 4 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 6 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 24 % | – | 6 / 18 % | 0 / 0 % | 4 / 13 % | 0 / 3 % | 4 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 21 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
