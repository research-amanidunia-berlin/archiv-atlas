[English](README.md) · [Deutsch](README.de.md)

# Practices for Governing Agentic AI Systems

Bericht Q008578 · Quelle openai.com · Datum 2023-12-14 · [Original öffnen](https://openai.com/index/practices-for-governing-agentic-ai-systems/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Auszug aus OpenAIs Bericht argumentiert, agentische KI könne Menschen unterstützen, zugleich aber Risiken schaffen. Er fordert gemeinsame Zuständigkeiten und Sicherheitspraktiken und kündigt erste Vorschläge sowie mögliche zusätzliche Governance-Rahmen an. Die konkreten Praktiken und Auswirkungen sind im vorliegenden Auszug nicht enthalten.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 18 / 46 % | 29 / 80 % | 89 / 96 % | 33 / 64 % | 6 / 33 % | 23 / 70 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 58 / 72 % | 81 / 99 % | 85 / 94 % | 59 / 80 % | 20 / 58 % | 47 / 80 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 53 / 74 % | 20 / 68 % | 53 / 87 % | 35 / 60 % | 6 / 34 % | 25 / 65 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 47 % | 41 / 83 % | 24 / 67 % | 12 / 38 % | 2 / 16 % | 14 / 39 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 40 / 66 % | 25 / 63 % | 25 / 65 % | 26 / 54 % | 6 / 34 % | 20 / 63 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 26 / 47 % | 25 / 73 % | 40 / 71 % | 18 / 48 % | 3 / 14 % | 15 / 49 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 19 / 42 % | 30 / 73 % | 34 / 75 % | 15 / 40 % | 5 / 30 % | 12 / 62 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 10 / 36 % | 31 / 70 % | 10 / 47 % | 16 / 40 % | 4 / 28 % | 10 / 39 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 27 / 90 % | 29 / 70 % | 10 / 25 % | 2 / 7 % | 13 / 24 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 26 / 50 % | 15 / 76 % | 17 / 53 % | 15 / 49 % | 4 / 21 % | 18 / 63 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 13 / 41 % | 26 / 52 % | 10 / 26 % | 1 / 7 % | 8 / 22 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 19 / 46 % | 11 / 57 % | 25 / 74 % | 14 / 46 % | 1 / 13 % | 7 / 27 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 8 / 30 % | 21 / 67 % | 1 / 24 % | 9 / 25 % | 2 / 14 % | 9 / 31 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 16 / 39 % | 20 / 77 % | 13 / 40 % | 16 / 39 % | 4 / 17 % | 14 / 56 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 9 / 37 % | 10 / 77 % | 19 / 71 % | 15 / 43 % | 3 / 17 % | 10 / 41 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 19 / 37 % | 5 / 53 % | 0 / 0 % | 10 / 29 % | 1 / 8 % | 14 / 38 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 19 / 56 % | 0 / 0 % | 8 / 19 % | 1 / 5 % | 7 / 17 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 6 / 28 % | 18 / 62 % | 3 / 32 % | 13 / 38 % | 3 / 15 % | 9 / 27 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 18 / 35 % | 18 / 57 % | 8 / 36 % | 15 / 39 % | 1 / 9 % | 12 / 40 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 17 / 44 % | 4 / 33 % | 7 / 27 % | 12 / 32 % | 3 / 14 % | 12 / 32 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 17 / 42 % | 15 / 42 % | 9 / 24 % | 15 / 43 % | 1 / 9 % | 13 / 32 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 11 / 26 % | 13 / 60 % | 13 / 56 % | 12 / 34 % | 2 / 10 % | 16 / 45 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 15 / 40 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 2 / 10 % | 11 / 30 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 40 % | 7 / 82 % | 15 / 56 % | 13 / 38 % | 3 / 25 % | 8 / 46 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 13 / 31 % | 1 / 21 % | 0 / 0 % | 8 / 18 % | 1 / 6 % | 7 / 17 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 13 / 60 % | 0 / 13 % | 10 / 28 % | 1 / 6 % | 9 / 24 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 27 % | 0 / 0 % | 7 / 13 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 11 / 45 % | 12 / 36 % | 0 / 0 % | 11 / 33 % | 1 / 9 % | 6 / 18 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 10 / 28 % | 4 / 74 % | 0 / 14 % | 8 / 22 % | 1 / 6 % | 8 / 23 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 32 % | 10 / 80 % | 9 / 42 % | 9 / 31 % | 2 / 15 % | 8 / 35 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 3 / 30 % | 0 / 0 % | 7 / 21 % | 1 / 6 % | 9 / 21 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 8 / 42 % | 2 / 16 % | 9 / 26 % | 1 / 6 % | 5 / 15 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 31 % | 6 / 51 % | 1 / 17 % | 9 / 23 % | 1 / 6 % | 5 / 15 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 9 / 37 % | 0 / 0 % | 7 / 17 % | 1 / 4 % | 6 / 14 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 36 % | 0 / 0 % | 7 / 15 % | 0 / 4 % | 9 / 23 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 8 / 36 % | 0 / 0 % | 8 / 23 % | 0 / 0 % | 9 / 31 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 4 % | 5 / 19 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 8 / 31 % | 2 / 33 % | 0 / 6 % | 9 / 20 % | 1 / 9 % | 8 / 25 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 12 % | 0 / 0 % | 2 / 9 % | 7 / 19 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 3 % | 7 / 22 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 6 / 11 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 2 % | 6 / 12 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 5 / 10 % | – | – |
