[English](README.md) · [Deutsch](README.de.md)

# Apollo Update May 2026

Bericht Q001416 · Quelle apolloresearch.ai · Datum – · [Original öffnen](https://apolloresearch.ai/blog/apollo-update-may-2026)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Apollo berichtet über den Ausbau seiner Forschung zu möglichem Scheming in künftigen KI-Systemen, über Überwachung von Coding-Agenten mit dem Produkt Watcher und über Governance-Arbeit zu Kontrollverlust, internem KI-Einsatz und automatisierter Forschung. Der Bericht enthält Unternehmensangaben, Einschätzungen und Pläne; ihre Wirksamkeit wird darin nicht unabhängig belegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 33 / 58 % | 88 / 98 % | 72 / 84 % | – | 65 / 82 % | 19 / 44 % | 54 / 70 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 37 / 58 % | 50 / 97 % | 27 / 63 % | – | 72 / 86 % | 45 / 69 % | 74 / 86 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 33 / 52 % | 72 / 97 % | 13 / 39 % | – | 50 / 74 % | 16 / 52 % | 54 / 79 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 45 / 66 % | 62 / 97 % | 19 / 60 % | – | 68 / 85 % | 48 / 69 % | 50 / 74 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 21 / 50 % | 64 / 89 % | 5 / 14 % | – | 29 / 56 % | 22 / 55 % | 48 / 65 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 31 / 53 % | 53 / 96 % | 11 / 33 % | – | 37 / 67 % | 17 / 42 % | 39 / 67 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 22 / 45 % | 51 / 94 % | 9 / 21 % | – | 37 / 61 % | 13 / 32 % | 42 / 63 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 50 / 92 % | 1 / 6 % | – | 27 / 50 % | 4 / 13 % | 26 / 45 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 13 / 40 % | 48 / 81 % | 1 / 8 % | – | 10 / 30 % | 3 / 14 % | 14 / 33 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 18 / 37 % | 37 / 87 % | 1 / 6 % | – | 12 / 37 % | 3 / 10 % | 16 / 32 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 21 / 37 % | 34 / 81 % | 1 / 4 % | – | 21 / 46 % | 3 / 10 % | 9 / 22 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 14 / 39 % | 34 / 74 % | 0 / 4 % | – | 11 / 30 % | 3 / 13 % | 11 / 26 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 33 / 91 % | 1 / 7 % | – | 9 / 23 % | 3 / 12 % | 14 / 31 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 31 / 83 % | 1 / 6 % | – | 11 / 31 % | 4 / 17 % | 10 / 23 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 17 / 42 % | 18 / 51 % | 4 / 15 % | – | 16 / 46 % | 9 / 35 % | 28 / 58 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 17 / 41 % | 13 / 62 % | 3 / 8 % | – | 24 / 48 % | 6 / 15 % | 26 / 38 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 11 / 35 % | 22 / 83 % | 1 / 7 % | – | 16 / 43 % | 5 / 18 % | 18 / 46 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 8 / 54 % | 1 / 5 % | – | 22 / 50 % | 5 / 15 % | 10 / 23 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 11 / 26 % | 7 / 42 % | 1 / 7 % | – | 21 / 50 % | 5 / 17 % | 19 / 39 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 20 / 43 % | 20 / 69 % | 4 / 16 % | – | 20 / 50 % | 5 / 18 % | 16 / 46 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 14 / 43 % | 14 / 61 % | 2 / 8 % | – | 18 / 45 % | 3 / 13 % | 15 / 31 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 17 / 71 % | 0 / 2 % | – | 6 / 15 % | 1 / 3 % | 10 / 19 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 15 / 64 % | 0 / 3 % | – | 8 / 24 % | 2 / 8 % | 10 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 15 / 29 % | 1 / 5 % | 5 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 11 / 75 % | 1 / 4 % | – | 14 / 39 % | 1 / 7 % | 12 / 27 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 10 / 50 % | 0 / 3 % | – | 14 / 41 % | 1 / 6 % | 9 / 27 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 14 / 51 % | 0 / 0 % | – | 11 / 35 % | 3 / 10 % | 10 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 9 / 25 % | 0 / 0 % | 0 / 2 % | – | 9 / 24 % | 1 / 5 % | 12 / 23 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 12 / 69 % | 0 / 3 % | – | 9 / 26 % | 2 / 8 % | 8 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 11 / 70 % | 0 / 1 % | – | 6 / 15 % | 0 / 0 % | 7 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 1 % | 10 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 1 / 4 % | – | 7 / 21 % | 2 / 7 % | 9 / 26 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | 1 / 2 % | 9 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 53 % | 0 / 0 % | – | 5 / 13 % | 0 / 0 % | 7 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 1 % | – | 9 / 30 % | 1 / 4 % | 6 / 16 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 8 / 22 % | 1 / 5 % | 9 / 23 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | 1 / 6 % | 8 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 11 % | 0 / 1 % | – | 7 / 17 % | 1 / 7 % | 7 / 15 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 7 / 15 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 5 / 52 % | 0 / 1 % | – | 7 / 23 % | 2 / 9 % | 7 / 15 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 7 / 79 % | 0 / 2 % | – | 7 / 22 % | 2 / 9 % | 6 / 15 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 1 / 2 % | 6 / 11 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 1 / 5 % | 6 / 17 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 1 / 3 % | 6 / 10 % |
