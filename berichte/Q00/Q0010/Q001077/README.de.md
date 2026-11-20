[English](README.md) · [Deutsch](README.de.md)

# A Causal Framework for AI Regulation and Auditing

Bericht Q001077 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/science/a-causal-framework-for-ai-regulation-and-auditing)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Auszug skizziert einen kausalen Rahmen für KI-Audits, der von den Auswirkungen eines Systems über seine Handlungsmöglichkeiten und Fähigkeiten bis zu Training, Sicherheit, Einsatz und Governance zurückverfolgt. Er empfiehlt insbesondere, Änderungen an den verfügbaren Handlungsmöglichkeiten zu prüfen, und nennt fünf Auditbereiche sowie mehrere Forschungsprioritäten; detaillierte Methoden oder empirische Ergebnisse enthält der Auszug nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 47 / 67 % | 88 / 98 % | 42 / 87 % | – | 50 / 78 % | 53 / 80 % | 55 / 82 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 39 / 64 % | 74 / 99 % | 76 / 92 % | – | 48 / 74 % | 42 / 70 % | 50 / 76 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 22 / 49 % | 72 / 96 % | 7 / 44 % | – | 19 / 56 % | 17 / 53 % | 36 / 66 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 24 / 49 % | 64 / 95 % | 4 / 11 % | – | 39 / 63 % | 25 / 41 % | 38 / 50 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 35 / 59 % | 62 / 93 % | 44 / 88 % | – | 32 / 70 % | 57 / 84 % | 48 / 79 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 34 / 60 % | 52 / 91 % | 34 / 85 % | – | 62 / 84 % | 39 / 71 % | 42 / 78 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 11 / 31 % | 61 / 92 % | 2 / 22 % | – | 11 / 34 % | 5 / 22 % | 8 / 55 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 36 / 60 % | 52 / 89 % | 31 / 82 % | – | 44 / 75 % | 44 / 72 % | 58 / 79 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 30 / 58 % | 49 / 97 % | 25 / 75 % | – | 40 / 70 % | 43 / 74 % | 54 / 77 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 13 / 44 % | 47 / 98 % | 6 / 45 % | – | 24 / 60 % | 15 / 48 % | 18 / 60 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 15 / 43 % | 45 / 97 % | 1 / 16 % | – | 13 / 43 % | 4 / 22 % | 13 / 40 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 19 / 45 % | 45 / 97 % | 8 / 42 % | – | 24 / 53 % | 17 / 44 % | 31 / 66 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 23 / 46 % | 42 / 95 % | 6 / 46 % | – | 26 / 60 % | 13 / 46 % | 12 / 38 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 20 / 51 % | 31 / 85 % | 9 / 42 % | – | 22 / 60 % | 15 / 55 % | 41 / 71 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 18 / 48 % | 37 / 93 % | 7 / 38 % | – | 32 / 62 % | 23 / 54 % | 35 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 50 % | 13 / 94 % | 5 / 29 % | – | 26 / 64 % | 11 / 52 % | 32 / 69 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 16 / 37 % | 32 / 83 % | 1 / 11 % | – | 13 / 40 % | 3 / 13 % | 8 / 27 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 13 / 45 % | 31 / 92 % | 7 / 51 % | – | 17 / 47 % | 13 / 45 % | 15 / 61 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 31 % | 31 / 92 % | 0 / 7 % | – | 8 / 29 % | 6 / 21 % | 8 / 29 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 9 / 43 % | 30 / 90 % | 3 / 23 % | – | 11 / 37 % | 6 / 17 % | 9 / 23 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 12 / 42 % | 18 / 89 % | 10 / 62 % | – | 16 / 46 % | 19 / 57 % | 26 / 70 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 20 / 49 % | 18 / 94 % | 9 / 44 % | – | 12 / 47 % | 8 / 43 % | 25 / 69 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 14 / 32 % | 25 / 71 % | 0 / 3 % | – | 8 / 24 % | 2 / 9 % | 6 / 16 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 19 / 45 % | 24 / 95 % | 6 / 40 % | – | 19 / 52 % | 12 / 38 % | 16 / 48 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 12 / 43 % | 23 / 91 % | 2 / 18 % | – | 13 / 38 % | 8 / 34 % | 11 / 50 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 19 / 47 % | 21 / 95 % | 3 / 20 % | – | 16 / 53 % | 4 / 32 % | 8 / 48 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 17 / 35 % | 21 / 82 % | 1 / 9 % | – | 11 / 40 % | 3 / 12 % | 9 / 35 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 34 % | 16 / 95 % | 1 / 10 % | – | 8 / 30 % | 4 / 22 % | 7 / 26 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 14 / 86 % | 0 / 6 % | – | 8 / 24 % | 3 / 13 % | 6 / 18 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 13 / 65 % | 0 / 3 % | – | 7 / 17 % | 2 / 8 % | 5 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 6 / 31 % | 12 / 48 % | 0 / 5 % | – | 8 / 21 % | 3 / 11 % | 5 / 17 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 7 / 24 % | 11 / 82 % | 0 / 7 % | – | 9 / 27 % | 3 / 10 % | 5 / 18 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 7 / 25 % | 10 / 64 % | 0 / 2 % | – | 7 / 18 % | 1 / 4 % | 6 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 10 / 24 % | 0 / 0 % | 1 / 11 % | – | 10 / 38 % | 4 / 22 % | 8 / 25 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 8 / 37 % | 1 / 29 % | 0 / 4 % | – | 9 / 29 % | 3 / 14 % | 6 / 19 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 9 / 21 % | 4 / 86 % | 0 / 5 % | – | 7 / 26 % | 1 / 10 % | 8 / 25 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 1 / 7 % | – | 9 / 33 % | 0 / 6 % | 8 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 7 / 18 % | 1 / 6 % | 5 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 7 / 53 % | 0 / 0 % | – | 7 / 21 % | 1 / 5 % | 7 / 13 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 5 / 79 % | 0 / 2 % | – | 0 / 0 % | 2 / 9 % | 6 / 17 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 3 / 59 % | 0 / 3 % | – | 6 / 16 % | 2 / 6 % | 4 / 10 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 2 % | 5 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 4 / 69 % | 0 / 2 % | – | 5 / 13 % | 1 / 4 % | 5 / 14 % |
