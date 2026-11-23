[English](README.md) · [Deutsch](README.de.md)

# The Loss of Control Playbook: Degrees, Dynamics, and Preparedness

Bericht Q000810 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/governance/loss-of-control)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht ordnet Kontrollverlust durch KI in drei ungefähre Stufen ein und empfiehlt mit DAP, Einsatzkontext, Handlungsmöglichkeiten und Berechtigungen systematisch zu prüfen und zu begrenzen. Die Autoren halten einen künftigen Zustand erhöhter Verwundbarkeit für möglich und raten, ihn zu vermeiden oder durch mehrschichtige Governance- und Technikmaßnahmen unter Kontrolle zu halten; ihre Zukunftsszenarien sind spekulativ, und die Maßnahmen beseitigen das Risiko nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 54 / 69 % | 100 / 100 % | – | 81 / 91 % | 78 / 89 % | 83 / 91 % | 73 / 91 % | 63 / 80 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 17 / 36 % | 97 / 100 % | – | 56 / 79 % | 44 / 66 % | 41 / 63 % | 25 / 39 % | 47 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 56 / 74 % | 92 / 98 % | – | 83 / 91 % | 75 / 88 % | 79 / 89 % | 90 / 97 % | 55 / 78 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 32 % | 74 / 96 % | – | 12 / 33 % | 9 / 25 % | 10 / 35 % | 2 / 14 % | 42 / 68 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 27 / 50 % | 39 / 95 % | – | 70 / 86 % | 21 / 48 % | 46 / 76 % | 34 / 77 % | 56 / 77 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 21 / 51 % | 65 / 95 % | – | 35 / 63 % | 19 / 43 % | 41 / 61 % | 7 / 25 % | 30 / 58 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 24 / 50 % | 64 / 98 % | – | 45 / 71 % | 44 / 70 % | 54 / 78 % | 24 / 57 % | 34 / 62 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 16 / 41 % | 53 / 98 % | – | 33 / 65 % | 23 / 52 % | 27 / 62 % | 21 / 61 % | 47 / 72 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 21 / 44 % | 3 / 97 % | – | 20 / 51 % | 8 / 36 % | 22 / 50 % | 4 / 26 % | 50 / 73 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 19 / 38 % | 44 / 87 % | – | 38 / 66 % | 14 / 42 % | 42 / 66 % | 13 / 43 % | 14 / 42 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 22 / 48 % | 40 / 97 % | – | 19 / 55 % | 19 / 43 % | 31 / 64 % | 9 / 35 % | 9 / 25 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 33 % | 36 / 97 % | – | 17 / 44 % | 10 / 32 % | 18 / 49 % | 6 / 28 % | 14 / 41 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 17 / 36 % | 33 / 76 % | – | 19 / 53 % | 10 / 33 % | 17 / 63 % | 6 / 21 % | 13 / 40 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 24 / 45 % | 29 / 96 % | – | 19 / 42 % | 9 / 24 % | 24 / 48 % | 3 / 14 % | 22 / 47 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 21 / 42 % | 10 / 82 % | – | 15 / 44 % | 6 / 22 % | 17 / 41 % | 2 / 11 % | 28 / 57 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 14 / 34 % | 28 / 89 % | – | 9 / 26 % | 5 / 13 % | 20 / 38 % | 1 / 8 % | 20 / 45 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 28 % | 26 / 97 % | – | 14 / 38 % | 7 / 20 % | 10 / 32 % | 1 / 12 % | 25 / 57 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 15 / 41 % | 7 / 51 % | – | 21 / 58 % | 9 / 29 % | 25 / 61 % | 1 / 6 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 24 / 50 % | 1 / 30 % | – | 8 / 25 % | 5 / 17 % | 10 / 27 % | 1 / 9 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 36 % | 23 / 80 % | – | 13 / 41 % | 9 / 29 % | 15 / 42 % | 1 / 7 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 6 / 23 % | 11 / 89 % | – | 6 / 15 % | 3 / 12 % | 5 / 10 % | 0 / 1 % | 20 / 40 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 8 / 29 % | 19 / 78 % | – | 17 / 41 % | 14 / 43 % | 20 / 53 % | 7 / 22 % | 11 / 30 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 1 / 62 % | – | 19 / 48 % | 9 / 30 % | 9 / 23 % | 2 / 10 % | 7 / 26 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 19 / 61 % | – | 6 / 13 % | 3 / 6 % | 6 / 11 % | 0 / 2 % | 10 / 31 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 17 / 41 % | 15 / 95 % | – | 18 / 55 % | 8 / 32 % | 13 / 57 % | 1 / 9 % | 11 / 28 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 18 / 59 % | – | 7 / 23 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | 15 / 34 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 14 / 66 % | – | 8 / 25 % | 4 / 13 % | 11 / 24 % | 1 / 7 % | 10 / 28 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 32 % | 0 / 0 % | – | 5 / 13 % | 0 / 0 % | 7 / 13 % | 0 / 1 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 12 / 41 % | 7 / 49 % | – | 12 / 39 % | 7 / 30 % | 10 / 34 % | 3 / 14 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 11 / 26 % | 1 / 74 % | – | 6 / 18 % | 4 / 12 % | 5 / 13 % | 0 / 4 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 7 / 27 % | 10 / 61 % | – | 10 / 29 % | 7 / 21 % | 9 / 23 % | 0 / 6 % | 10 / 29 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 9 / 34 % | 0 / 6 % | 6 / 21 % | 0 / 4 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 7 / 57 % | – | 5 / 15 % | 2 / 7 % | 7 / 16 % | 0 / 0 % | 9 / 28 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 28 % | 3 / 76 % | – | 7 / 23 % | 5 / 15 % | 6 / 15 % | 0 / 2 % | 9 / 26 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 8 / 20 % | 5 / 87 % | – | 0 / 0 % | 6 / 12 % | 7 / 16 % | 0 / 0 % | 8 / 28 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 8 / 26 % | 1 / 9 % | 8 / 34 % | 0 / 3 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 4 / 10 % | 6 / 12 % | 0 / 2 % | 2 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 5 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 4 / 81 % | – | 5 / 13 % | 0 / 0 % | 4 / 7 % | 0 / 2 % | 2 / 13 % |
