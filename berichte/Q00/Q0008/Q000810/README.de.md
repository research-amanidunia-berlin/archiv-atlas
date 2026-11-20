[English](README.md) · [Deutsch](README.de.md)

# The Loss of Control Playbook: Degrees, Dynamics, and Preparedness

Bericht Q000810 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/governance/loss-of-control)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht ordnet Kontrollverlust durch KI in drei ungefähre Stufen ein und empfiehlt mit DAP, Einsatzkontext, Handlungsmöglichkeiten und Berechtigungen systematisch zu prüfen und zu begrenzen. Die Autoren halten einen künftigen Zustand erhöhter Verwundbarkeit für möglich und raten, ihn zu vermeiden oder durch mehrschichtige Governance- und Technikmaßnahmen unter Kontrolle zu halten; ihre Zukunftsszenarien sind spekulativ, und die Maßnahmen beseitigen das Risiko nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 54 / 69 % | 100 / 100 % | 73 / 91 % | – | 81 / 91 % | 78 / 89 % | 83 / 91 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 17 / 36 % | 97 / 100 % | 25 / 39 % | – | 56 / 79 % | 44 / 66 % | 41 / 63 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 56 / 74 % | 92 / 98 % | 90 / 97 % | – | 83 / 91 % | 75 / 88 % | 79 / 89 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 32 % | 74 / 96 % | 2 / 14 % | – | 12 / 33 % | 9 / 25 % | 10 / 35 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 27 / 50 % | 39 / 95 % | 34 / 77 % | – | 70 / 86 % | 21 / 48 % | 46 / 76 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 21 / 51 % | 65 / 95 % | 7 / 25 % | – | 35 / 63 % | 19 / 43 % | 41 / 61 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 24 / 50 % | 64 / 98 % | 24 / 57 % | – | 45 / 71 % | 44 / 70 % | 54 / 78 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 16 / 41 % | 53 / 98 % | 21 / 61 % | – | 33 / 65 % | 23 / 52 % | 27 / 62 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 19 / 38 % | 44 / 87 % | 13 / 43 % | – | 38 / 66 % | 14 / 42 % | 42 / 66 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 22 / 48 % | 40 / 97 % | 9 / 35 % | – | 19 / 55 % | 19 / 43 % | 31 / 64 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 33 % | 36 / 97 % | 6 / 28 % | – | 17 / 44 % | 10 / 32 % | 18 / 49 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 17 / 36 % | 33 / 76 % | 6 / 21 % | – | 19 / 53 % | 10 / 33 % | 17 / 63 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 24 / 45 % | 29 / 96 % | 3 / 14 % | – | 19 / 42 % | 9 / 24 % | 24 / 48 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 14 / 34 % | 28 / 89 % | 1 / 8 % | – | 9 / 26 % | 5 / 13 % | 20 / 38 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 28 % | 26 / 97 % | 1 / 12 % | – | 14 / 38 % | 7 / 20 % | 10 / 32 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 15 / 41 % | 7 / 51 % | 1 / 6 % | – | 21 / 58 % | 9 / 29 % | 25 / 61 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 24 / 50 % | 1 / 30 % | 1 / 9 % | – | 8 / 25 % | 5 / 17 % | 10 / 27 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 15 / 36 % | 23 / 80 % | 1 / 7 % | – | 13 / 41 % | 9 / 29 % | 15 / 42 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 21 / 44 % | 3 / 97 % | 4 / 26 % | – | 20 / 51 % | 8 / 36 % | 22 / 50 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 21 / 42 % | 10 / 82 % | 2 / 11 % | – | 15 / 44 % | 6 / 22 % | 17 / 41 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 8 / 29 % | 19 / 78 % | 7 / 22 % | – | 17 / 41 % | 14 / 43 % | 20 / 53 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 1 / 62 % | 2 / 10 % | – | 19 / 48 % | 9 / 30 % | 9 / 23 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 19 / 61 % | 0 / 2 % | – | 6 / 13 % | 3 / 6 % | 6 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 17 / 41 % | 15 / 95 % | 1 / 9 % | – | 18 / 55 % | 8 / 32 % | 13 / 57 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 18 / 59 % | 0 / 0 % | – | 7 / 23 % | 0 / 0 % | 7 / 12 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 14 / 66 % | 1 / 7 % | – | 8 / 25 % | 4 / 13 % | 11 / 24 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 32 % | 0 / 0 % | 0 / 1 % | – | 5 / 13 % | 0 / 0 % | 7 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 12 / 41 % | 7 / 49 % | 3 / 14 % | – | 12 / 39 % | 7 / 30 % | 10 / 34 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 11 / 26 % | 1 / 74 % | 0 / 4 % | – | 6 / 18 % | 4 / 12 % | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 6 / 23 % | 11 / 89 % | 0 / 1 % | – | 6 / 15 % | 3 / 12 % | 5 / 10 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 7 / 27 % | 10 / 61 % | 0 / 6 % | – | 10 / 29 % | 7 / 21 % | 9 / 23 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 4 % | – | 9 / 34 % | 0 / 6 % | 6 / 21 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 8 / 20 % | 5 / 87 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 7 / 16 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 3 % | – | 8 / 26 % | 1 / 9 % | 8 / 34 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 7 / 57 % | 0 / 0 % | – | 5 / 15 % | 2 / 7 % | 7 / 16 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 28 % | 3 / 76 % | 0 / 2 % | – | 7 / 23 % | 5 / 15 % | 6 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 5 / 13 % | 4 / 10 % | 6 / 12 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 2 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 5 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 4 / 81 % | 0 / 2 % | – | 5 / 13 % | 0 / 0 % | 4 / 7 % |
