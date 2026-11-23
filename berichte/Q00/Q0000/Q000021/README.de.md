[English](README.md) · [Deutsch](README.de.md)

# Operationalizing U.S.-China AI Incident Notification

Bericht Q000021 · Quelle iaps.ai · Datum 2026-10-23 · [Original öffnen](https://www.iaps.ai/research/operationalizing-us-china-ai-incident-notification)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Das Memo schlägt einen zunächst freiwilligen, schriftlichen US-chinesischen Meldekanal für schwerwiegende KI-Vorfälle vor, der von den politischen Ansprechpartnern schrittweise auf zuständige Fachbehörden übergehen und durch eine gemeinsame Vorlage sowie Regeln zur Vertraulichkeit gestützt werden soll. Die Meldeschwellen müssten noch ausgehandelt werden; das Malware-Szenario ist hypothetisch, und die konkreten Formularfelder sind im bereitgestellten Text nicht sichtbar.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 83 / 89 % | 100 / 100 % | 100 / 100 % | 94 / 96 % | 97 / 98 % | 96 / 97 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 92 / 94 % | 100 / 100 % | 100 / 100 % | 93 / 94 % | 98 / 99 % | 99 / 99 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 57 / 72 % | 98 / 98 % | 100 / 100 % | 93 / 95 % | 96 / 98 % | 96 / 97 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 85 / 91 % | 99 / 100 % | 99 / 100 % | 91 / 95 % | 80 / 88 % | 88 / 92 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 38 / 54 % | 95 / 99 % | 38 / 79 % | 68 / 83 % | 62 / 78 % | 87 / 93 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 55 / 73 % | 85 / 95 % | 94 / 96 % | 76 / 87 % | 48 / 65 % | 79 / 87 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 19 / 47 % | 93 / 98 % | 81 / 86 % | 30 / 54 % | 14 / 36 % | 46 / 69 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 29 / 47 % | 87 / 99 % | 92 / 97 % | 57 / 79 % | 39 / 68 % | 66 / 84 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 37 / 64 % | 53 / 93 % | 88 / 94 % | 32 / 60 % | 10 / 26 % | 20 / 44 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 38 / 62 % | 83 / 96 % | 85 / 94 % | 70 / 85 % | 44 / 69 % | 67 / 82 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 83 / 95 % | 54 / 58 % | 25 / 48 % | 18 / 33 % | 39 / 51 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 44 / 67 % | 79 / 96 % | 74 / 87 % | 67 / 84 % | 40 / 57 % | 66 / 81 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 26 / 45 % | 75 / 94 % | 47 / 63 % | 42 / 64 % | 9 / 26 % | 28 / 44 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 74 / 92 % | 14 / 37 % | 14 / 32 % | 0 / 0 % | 8 / 17 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 42 / 64 % | 73 / 99 % | 69 / 84 % | 55 / 75 % | 16 / 33 % | 63 / 78 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 15 / 39 % | 64 / 90 % | 13 / 37 % | 21 / 43 % | 0 / 0 % | 18 / 33 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 27 / 56 % | 60 / 87 % | 38 / 56 % | 23 / 53 % | 21 / 51 % | 44 / 67 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 37 % | 56 / 93 % | 11 / 33 % | 22 / 46 % | 6 / 19 % | 21 / 38 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 23 / 47 % | 50 / 89 % | 21 / 47 % | 22 / 49 % | 9 / 23 % | 19 / 39 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 10 / 36 % | 47 / 73 % | 8 / 20 % | 19 / 44 % | 7 / 16 % | 12 / 25 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 44 / 89 % | 27 / 61 % | 30 / 57 % | 10 / 23 % | 20 / 39 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 42 % | 44 / 75 % | 14 / 29 % | 18 / 39 % | 6 / 20 % | 12 / 23 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 35 / 59 % | 43 / 90 % | 34 / 58 % | 24 / 49 % | 10 / 21 % | 34 / 61 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 23 / 79 % | 0 / 0 % | 39 / 63 % | 9 / 19 % | 29 / 45 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 23 / 47 % | 39 / 91 % | 17 / 30 % | 9 / 24 % | 3 / 11 % | 7 / 15 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 18 / 43 % | 36 / 77 % | 3 / 17 % | 10 / 26 % | 0 / 0 % | 20 / 43 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 35 / 80 % | 25 / 35 % | 27 / 51 % | 14 / 29 % | 35 / 53 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 35 / 81 % | 7 / 15 % | 15 / 40 % | 0 / 0 % | 18 / 31 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 8 / 31 % | 33 / 78 % | 5 / 34 % | 9 / 19 % | 8 / 19 % | 18 / 34 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 5 / 18 % | 1 / 3 % | 31 / 56 % | 7 / 20 % | 22 / 36 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 29 / 57 % | 5 / 23 % | 9 / 21 % | 0 / 0 % | 11 / 19 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 27 / 78 % | 0 / 0 % | 8 / 20 % | 1 / 7 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 8 / 81 % | 9 / 41 % | 17 / 40 % | 0 / 0 % | 24 / 42 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 23 / 68 % | 0 / 0 % | 8 / 20 % | 2 / 9 % | 6 / 12 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 9 / 35 % | 0 / 0 % | 21 / 45 % | 7 / 18 % | 20 / 37 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 5 / 59 % | 0 / 0 % | 18 / 44 % | 0 / 0 % | 6 / 15 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 5 / 15 % | 16 / 32 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 13 / 68 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 4 / 52 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 7 / 15 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 2 / 6 % | 0 / 0 % | – | – |
