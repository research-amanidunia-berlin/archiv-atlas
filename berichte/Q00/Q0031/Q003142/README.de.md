[English](README.md) · [Deutsch](README.de.md)

# Dario Amodei's remarks at the AI Safety Summit

Bericht Q003142 · Quelle anthropic.com · Datum 2023-11-01 · [Original öffnen](https://www.anthropic.com/news/uk-ai-safety-summit)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Amodei stellt Anthropics RSP als stufenbasierten Plan vor, der KI-Modelle regelmäßig auf gefährliche Fähigkeiten prüft und je nach Risikostufe Schutzmaßnahmen oder Einsatzbeschränkungen vorsieht. Er fordert Führungseinbindung und Rechenschaft und versteht solche Unternehmensrichtlinien als Ausgangspunkt für bessere staatliche Regulierung; die Rede weist die Wirksamkeit der geplanten Maßnahmen nicht nach.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 59 / 78 % | 100 / 100 % | – | 100 / 100 % | 88 / 93 % | 91 / 94 % | 84 / 93 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 54 / 68 % | 100 / 100 % | – | 100 / 100 % | 90 / 94 % | 86 / 92 % | 64 / 81 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 46 / 66 % | 100 / 100 % | – | 100 / 100 % | 80 / 89 % | 75 / 87 % | 73 / 88 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 40 / 62 % | 83 / 96 % | – | 98 / 100 % | 66 / 84 % | 79 / 89 % | 69 / 86 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 60 / 77 % | 91 / 98 % | – | 97 / 99 % | 86 / 93 % | 83 / 90 % | 61 / 81 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 36 / 63 % | 82 / 97 % | – | 95 / 99 % | 69 / 85 % | 52 / 76 % | 38 / 63 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 18 / 45 % | 88 / 97 % | – | 92 / 97 % | 33 / 57 % | 36 / 62 % | 18 / 46 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 48 / 62 % | 86 / 94 % | – | 87 / 91 % | 80 / 87 % | 84 / 88 % | 70 / 79 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 20 / 49 % | 85 / 98 % | – | 46 / 72 % | 27 / 52 % | 15 / 38 % | 13 / 36 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 12 / 25 % | 85 / 98 % | – | 72 / 89 % | 15 / 37 % | 15 / 39 % | 9 / 33 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 28 / 56 % | 64 / 95 % | – | 84 / 93 % | 41 / 67 % | 52 / 71 % | 26 / 50 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 31 / 61 % | 51 / 97 % | – | 75 / 95 % | 19 / 44 % | 47 / 74 % | 37 / 67 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 30 / 51 % | 74 / 91 % | – | 51 / 73 % | 31 / 58 % | 40 / 59 % | 30 / 53 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 41 / 68 % | – | 72 / 87 % | 10 / 29 % | 7 / 15 % | 2 / 10 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 68 / 97 % | – | 41 / 73 % | 16 / 36 % | 10 / 21 % | 6 / 14 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 17 / 48 % | 48 / 97 % | – | 67 / 85 % | 25 / 54 % | 11 / 43 % | 8 / 28 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 18 / 29 % | 61 / 83 % | – | 67 / 83 % | 17 / 43 % | 11 / 26 % | 7 / 16 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 19 / 45 % | 58 / 95 % | – | 66 / 85 % | 41 / 64 % | 51 / 69 % | 30 / 55 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 63 / 96 % | – | 40 / 69 % | 13 / 33 % | 13 / 25 % | 6 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 19 / 51 % | 61 / 94 % | – | 58 / 79 % | 25 / 51 % | 25 / 56 % | 17 / 46 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 48 / 97 % | – | 58 / 87 % | 40 / 66 % | 12 / 31 % | 13 / 40 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 36 % | 58 / 86 % | – | 6 / 41 % | 17 / 39 % | 12 / 34 % | 9 / 29 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 47 % | 55 / 86 % | – | 13 / 50 % | 30 / 59 % | 21 / 46 % | 17 / 46 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 48 % | 47 / 95 % | – | 45 / 61 % | 48 / 73 % | 54 / 74 % | 26 / 53 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 20 / 43 % | 43 / 83 % | – | 36 / 73 % | 22 / 44 % | 16 / 33 % | 10 / 26 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 43 / 82 % | – | 0 / 0 % | 16 / 45 % | 11 / 34 % | 12 / 39 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 6 / 28 % | 31 / 91 % | – | 0 / 0 % | 9 / 25 % | 7 / 20 % | 4 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 27 / 51 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 25 / 72 % | – | 4 / 27 % | 7 / 18 % | 6 / 13 % | 1 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 24 / 87 % | – | 17 / 34 % | 15 / 41 % | 16 / 32 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 23 / 55 % | – | 0 / 0 % | 7 / 15 % | 6 / 17 % | 1 / 4 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 22 / 68 % | – | 1 / 12 % | 8 / 19 % | 6 / 13 % | 1 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 40 % | 10 / 65 % | – | 8 / 35 % | 21 / 50 % | 21 / 43 % | 7 / 26 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 19 / 96 % | – | 5 / 32 % | 14 / 33 % | 6 / 21 % | 4 / 13 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 6 / 29 % | 17 / 95 % | – | 4 / 20 % | 7 / 22 % | 5 / 15 % | 3 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 11 / 35 % | 9 / 24 % | 13 / 28 % | 3 / 11 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 9 / 18 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 7 / 56 % | – | 0 / 0 % | 7 / 22 % | 8 / 16 % | 1 / 5 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 8 / 96 % | – | 4 / 37 % | 7 / 18 % | 5 / 12 % | 1 / 6 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 1 / 9 % | 7 / 15 % | 6 / 11 % | 3 / 8 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 9 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 6 / 19 % | 1 / 4 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 28 % | – | 0 / 0 % | 5 / 10 % | 5 / 13 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 5 / 10 % | 0 / 0 % |
