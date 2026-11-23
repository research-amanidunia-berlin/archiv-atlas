[English](README.md) · [Deutsch](README.de.md)

# When the Agent Is the Incident: NIST, NSA, and CISA's 10 Key Practices for SI Incident Response

Bericht Q000035 · Quelle cybersecurityos.net · Datum 2026-10-25 · [Original öffnen](https://www.cybersecurityos.net/posts/ai-devsecops/nist-cisa-nsa-si-incident-response-key-practices/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht stellt eine freiwillige NIST-, NSA- und CISA-Leitlinie mit zehn Praktiken vor, die nicht angewiesenes Fehlverhalten eines SI-Agenten als eigene Vorfallskategorie behandelt. Sie empfiehlt unter anderem beschränkte Zugriffe, geschützte Überwachung, umfassende Beweissicherung, vorab festgelegte Abschaltungen und geprüfte Wiederherstellung; Standards für Schweregrade, sichere Trainingskorrekturen und die Veröffentlichung von Agentenkennungen bleiben offen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 74 / 87 % | 95 / 97 % | 100 / 100 % | 93 / 96 % | 90 / 95 % | 92 / 94 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 78 / 88 % | 97 / 99 % | 100 / 100 % | 93 / 95 % | 94 / 97 % | 94 / 96 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 62 / 77 % | 96 / 99 % | 100 / 100 % | 89 / 94 % | 93 / 96 % | 91 / 95 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 60 / 73 % | 91 / 98 % | 98 / 99 % | 90 / 94 % | 81 / 90 % | 89 / 93 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 43 / 59 % | 93 / 98 % | 97 / 99 % | 68 / 84 % | 56 / 73 % | 74 / 86 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 52 / 70 % | 92 / 97 % | 95 / 98 % | 83 / 90 % | 80 / 89 % | 87 / 92 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 26 / 43 % | 83 / 97 % | 94 / 96 % | 79 / 89 % | 61 / 78 % | 84 / 91 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 45 / 63 % | 74 / 91 % | 92 / 95 % | 79 / 87 % | 60 / 72 % | 71 / 80 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 29 / 52 % | 88 / 98 % | 76 / 92 % | 69 / 84 % | 49 / 69 % | 51 / 67 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 52 / 67 % | 79 / 93 % | 88 / 94 % | 84 / 91 % | 88 / 94 % | 86 / 92 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 26 / 49 % | 87 / 94 % | 54 / 62 % | 65 / 80 % | 67 / 79 % | 70 / 81 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 38 / 68 % | 82 / 91 % | 8 / 19 % | 0 / 0 % | 9 / 15 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 80 / 95 % | 49 / 69 % | 12 / 27 % | 7 / 16 % | 8 / 18 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 78 / 90 % | 30 / 57 % | 12 / 26 % | 12 / 24 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 73 / 97 % | 18 / 37 % | 19 / 46 % | 10 / 24 % | 23 / 40 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 49 / 80 % | 64 / 82 % | 67 / 83 % | 42 / 69 % | 73 / 83 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 30 / 53 % | 61 / 97 % | 71 / 93 % | 48 / 75 % | 22 / 48 % | 38 / 66 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 63 / 82 % | 27 / 49 % | 30 / 54 % | 16 / 32 % | 22 / 33 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 36 / 53 % | 26 / 92 % | 61 / 89 % | 39 / 62 % | 15 / 31 % | 18 / 38 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 48 / 64 % | 48 / 85 % | 21 / 66 % | 57 / 77 % | 60 / 77 % | 52 / 69 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 19 / 49 % | 35 / 79 % | 60 / 79 % | 42 / 63 % | 15 / 35 % | 31 / 50 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 57 / 73 % | 10 / 18 % | 21 / 32 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 34 / 58 % | 40 / 66 % | 55 / 76 % | 14 / 32 % | 51 / 68 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 50 / 80 % | 40 / 74 % | 18 / 41 % | 12 / 31 % | 21 / 37 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 49 / 85 % | 17 / 35 % | 14 / 33 % | 13 / 25 % | 12 / 21 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 43 / 72 % | 5 / 13 % | 8 / 16 % | 4 / 9 % | 7 / 12 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 42 / 86 % | 18 / 36 % | 10 / 21 % | 9 / 21 % | 11 / 21 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 28 / 64 % | 0 / 0 % | 9 / 20 % | 4 / 7 % | 10 / 17 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 26 / 65 % | 21 / 42 % | 23 / 47 % | 8 / 17 % | 15 / 29 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 44 % | 7 / 21 % | 24 / 44 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 10 / 30 % | 17 / 81 % | 13 / 47 % | 13 / 33 % | 14 / 32 % | 22 / 42 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 44 % | 22 / 41 % | 22 / 44 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 11 / 59 % | 18 / 45 % | 13 / 28 % | 3 / 7 % | 16 / 27 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 25 % | 0 / 0 % | 2 / 10 % | 11 / 27 % | 6 / 15 % | 16 / 29 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 15 / 50 % | 6 / 33 % | 10 / 20 % | 0 / 0 % | 7 / 14 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 4 / 75 % | 0 / 0 % | 8 / 18 % | 4 / 10 % | 15 / 24 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 5 / 10 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 29 % | 2 / 9 % | 7 / 16 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 4 / 6 % | 10 / 18 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 10 / 73 % | 0 / 0 % | 8 / 17 % | 6 / 14 % | 5 / 11 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 4 % | 8 / 12 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 8 / 14 % | 6 / 12 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
