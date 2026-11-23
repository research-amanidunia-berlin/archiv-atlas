[English](README.md) · [Deutsch](README.de.md)

# From bugs to bypasses: adapting vulnerability disclosure for AI safeguards

Bericht Q002416 · Quelle aisi.gov.uk · Datum 2025-09-02 · [Original öffnen](https://www.aisi.gov.uk/blog/from-bugs-to-bypasses-adapting-vulnerability-disclosure-for-ai-safeguards)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Text ist ein Auszug, der öffentliche Schwachstellenprogramme als mögliche Ergänzung zur Prüfung von KI-Schutzmaßnahmen beschreibt: Sie könnten verantwortungsvolle Meldungen, Zusammenarbeit und praktische Sicherheitsforschung fördern. Der Beitrag warnt, dass sie gründliche Prüfungen und solide Sicherheitsgrundlagen nicht ersetzen und allein keine Systemsicherheit belegen; konkrete Untersuchungsmethoden oder Ergebnisse enthält der Auszug nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 23 / 39 % | 49 / 95 % | 73 / 91 % | 32 / 63 % | 8 / 28 % | 23 / 55 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 53 / 81 % | 67 / 91 % | 30 / 56 % | 15 / 34 % | 20 / 38 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 50 / 93 % | 24 / 41 % | 36 / 62 % | 15 / 34 % | 15 / 35 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 21 / 42 % | 28 / 87 % | 42 / 72 % | 23 / 59 % | 19 / 45 % | 25 / 59 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 7 / 61 % | 41 / 67 % | 10 / 29 % | 6 / 19 % | 9 / 22 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 18 / 41 % | 34 / 77 % | 12 / 58 % | 7 / 17 % | 8 / 29 % | 25 / 60 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 34 / 57 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 29 / 84 % | 21 / 35 % | 15 / 36 % | 3 / 12 % | 11 / 27 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 10 / 57 % | 26 / 58 % | 6 / 22 % | 1 / 8 % | 5 / 14 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 21 / 87 % | 25 / 67 % | 10 / 27 % | 4 / 14 % | 8 / 19 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 22 / 56 % | 13 / 48 % | 16 / 42 % | 7 / 22 % | 6 / 19 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 21 / 72 % | 2 / 26 % | 8 / 28 % | 1 / 8 % | 5 / 16 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 21 / 85 % | 10 / 25 % | 6 / 16 % | 1 / 7 % | 5 / 12 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 20 / 55 % | 0 / 0 % | 6 / 17 % | 1 / 6 % | 5 / 16 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 13 / 82 % | 3 / 38 % | 14 / 42 % | 5 / 17 % | 16 / 40 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 15 / 74 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 5 / 11 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 15 / 67 % | 1 / 18 % | 9 / 28 % | 3 / 11 % | 5 / 15 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 14 / 52 % | 0 / 0 % | 6 / 20 % | 1 / 7 % | 5 / 16 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 13 / 81 % | 0 / 0 % | 6 / 16 % | 1 / 6 % | 5 / 12 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 10 / 67 % | 13 / 43 % | 12 / 39 % | 7 / 20 % | 10 / 28 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 6 / 53 % | 1 / 9 % | 12 / 37 % | 2 / 11 % | 6 / 16 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 12 / 51 % | 0 / 0 % | 10 / 35 % | 1 / 6 % | 9 / 23 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 12 / 66 % | 0 / 0 % | 5 / 15 % | 1 / 7 % | 4 / 11 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 11 / 55 % | 0 / 0 % | 5 / 11 % | 1 / 6 % | 5 / 11 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 2 / 77 % | 6 / 30 % | 9 / 28 % | 5 / 17 % | 9 / 23 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 9 / 77 % | 1 / 15 % | 6 / 17 % | 0 / 6 % | 7 / 18 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 6 / 67 % | 0 / 0 % | 8 / 29 % | 0 / 0 % | 5 / 13 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 6 % | 6 / 14 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 6 / 14 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 4 / 42 % | 0 / 8 % | 6 / 19 % | 1 / 8 % | 4 / 15 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 57 % | 0 / 6 % | 6 / 18 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 5 % | 5 / 9 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 3 / 88 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 4 / 8 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 4 % | 5 / 12 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 3 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
