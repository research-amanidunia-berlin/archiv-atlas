[English](README.md) · [Deutsch](README.de.md)

# OpenAI safety practices

Bericht Q007646 · Quelle openai.com · Datum 2024-05-21 · [Original öffnen](https://openai.com/index/openai-safety-update/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt zehn eigene Sicherheitspraktiken, darunter Modelltests, Missbrauchsüberwachung, Schutzmaßnahmen für Kinder und Wahlen, Sicherheitsforschung und Aufsicht über Veröffentlichungsentscheidungen. Das Unternehmen sagt, die bisherigen Maßnahmen hätten sichere Bereitstellungen auf dem damaligen Fähigkeitsniveau ermöglicht, räumt aber weiteren Handlungsbedarf ein und kündigt für das nächste Frontier-Modell stärkere Abwehr und längere Testphasen an.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 45 / 67 % | 100 / 100 % | – | 100 / 100 % | 83 / 90 % | 63 / 80 % | 84 / 91 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 36 / 61 % | 99 / 100 % | – | 100 / 100 % | 66 / 84 % | 68 / 85 % | 81 / 90 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 53 / 72 % | 94 / 99 % | – | 100 / 100 % | 82 / 90 % | 71 / 86 % | 76 / 87 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 44 / 62 % | 85 / 95 % | – | 99 / 100 % | 77 / 88 % | 42 / 68 % | 65 / 78 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 33 / 56 % | 98 / 99 % | – | 99 / 100 % | 73 / 85 % | 45 / 69 % | 79 / 88 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 48 / 66 % | 95 / 99 % | – | 92 / 96 % | 80 / 88 % | 63 / 80 % | 80 / 87 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 19 / 48 % | 49 / 88 % | – | 94 / 97 % | 52 / 77 % | 37 / 67 % | 54 / 76 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 34 / 60 % | 51 / 85 % | – | 92 / 98 % | 36 / 61 % | 55 / 77 % | 65 / 82 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 27 / 53 % | 29 / 70 % | – | 90 / 97 % | 47 / 71 % | 16 / 44 % | 33 / 61 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 29 / 53 % | 72 / 95 % | – | 88 / 97 % | 50 / 75 % | 36 / 63 % | 51 / 76 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 26 / 54 % | 69 / 93 % | – | 86 / 93 % | 38 / 63 % | 14 / 39 % | 31 / 53 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 19 / 37 % | 61 / 88 % | – | 83 / 92 % | 30 / 56 % | 9 / 26 % | 27 / 54 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 47 % | 53 / 93 % | – | 81 / 88 % | 39 / 65 % | 20 / 48 % | 46 / 70 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 10 / 37 % | 81 / 90 % | – | 12 / 33 % | 15 / 36 % | 10 / 31 % | 15 / 38 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 18 / 46 % | 75 / 88 % | – | 66 / 82 % | 56 / 78 % | 26 / 55 % | 63 / 77 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 24 / 53 % | 49 / 78 % | – | 72 / 90 % | 41 / 66 % | 24 / 57 % | 48 / 67 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 13 / 36 % | 70 / 94 % | – | 37 / 61 % | 11 / 31 % | 5 / 22 % | 13 / 32 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 15 / 34 % | 70 / 93 % | – | 63 / 83 % | 19 / 47 % | 12 / 36 % | 21 / 55 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 33 / 83 % | – | 67 / 88 % | 54 / 76 % | 19 / 45 % | 16 / 40 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 26 / 46 % | 59 / 95 % | – | 47 / 74 % | 24 / 53 % | 13 / 36 % | 25 / 44 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 14 / 44 % | 59 / 95 % | – | 26 / 59 % | 33 / 57 % | 22 / 47 % | 35 / 58 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 54 / 95 % | – | 43 / 74 % | 17 / 39 % | 8 / 27 % | 18 / 43 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 33 / 67 % | – | 52 / 74 % | 7 / 18 % | 3 / 11 % | 7 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 17 / 39 % | 44 / 94 % | – | 16 / 46 % | 29 / 55 % | 10 / 30 % | 13 / 42 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 43 / 78 % | – | 24 / 46 % | 16 / 44 % | 9 / 31 % | 17 / 37 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 9 / 31 % | 35 / 80 % | – | 27 / 47 % | 9 / 25 % | 6 / 23 % | 9 / 21 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 33 / 78 % | – | 12 / 35 % | 9 / 23 % | 4 / 13 % | 8 / 21 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 32 / 72 % | – | 11 / 35 % | 13 / 35 % | 2 / 14 % | 12 / 33 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 30 / 74 % | – | 0 / 7 % | 7 / 16 % | 3 / 13 % | 7 / 16 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 28 / 71 % | – | 20 / 53 % | 14 / 34 % | 9 / 28 % | 15 / 33 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 31 % | 25 / 77 % | – | 20 / 49 % | 8 / 24 % | 4 / 17 % | 7 / 21 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 24 / 55 % | – | 21 / 46 % | 18 / 46 % | 5 / 19 % | 14 / 48 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 16 / 41 % | 21 / 69 % | – | 14 / 47 % | 13 / 34 % | 8 / 27 % | 17 / 36 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 6 / 36 % | – | 0 / 0 % | 19 / 46 % | 9 / 30 % | 11 / 49 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 8 / 26 % | – | 14 / 30 % | 16 / 36 % | 2 / 8 % | 17 / 32 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 16 / 80 % | – | 3 / 25 % | 11 / 28 % | 4 / 21 % | 11 / 27 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 16 / 36 % | 0 / 0 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 15 / 32 % | 5 / 14 % | 9 / 20 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 13 / 39 % | – | 0 / 0 % | 7 / 16 % | 2 / 11 % | 8 / 24 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 35 % | 8 / 57 % | – | 1 / 6 % | 9 / 25 % | 8 / 27 % | 11 / 25 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 29 % | 2 / 7 % | 11 / 24 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 3 / 10 % | 6 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 6 / 22 % | 7 / 58 % | – | 1 / 5 % | 6 / 14 % | 2 / 9 % | 4 / 10 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 13 % | 5 / 11 % |
