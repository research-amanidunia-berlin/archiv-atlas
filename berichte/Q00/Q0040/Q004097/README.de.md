[English](README.md) · [Deutsch](README.de.md)

# Updating the Frontier Safety Framework

Bericht Q004097 · Quelle deepmind.google · Datum 2025-02-04 · [Original öffnen](https://deepmind.google/blog/updating-the-frontier-safety-framework/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google DeepMind aktualisiert sein Frontier Safety Framework mit Mindestempfehlungen für Sicherheitsstufen, einem Prüfverfahren vor der allgemeinen Bereitstellung kritischer Modelle und ersten Ansätzen gegen mögliche Täuschung durch autonome Systeme. Das Unternehmen betont, dass die Wahrscheinlichkeit solcher Fähigkeiten unklar sei, automatisierte Überwachung langfristig womöglich nicht genüge und gemeinsame Forschung nötig bleibe; konkrete Schwellenwerte und Wirksamkeitsdaten nennt der Bericht nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 43 / 60 % | 99 / 100 % | 69 / 88 % | 100 / 100 % | 68 / 83 % | 42 / 67 % | 67 / 83 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 39 / 60 % | 77 / 93 % | 47 / 76 % | 98 / 99 % | 66 / 83 % | 27 / 54 % | 63 / 79 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 30 / 54 % | 90 / 99 % | 38 / 72 % | 94 / 99 % | 44 / 73 % | 31 / 59 % | 57 / 79 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 23 / 49 % | 34 / 80 % | 14 / 41 % | 91 / 97 % | 49 / 72 % | 15 / 40 % | 31 / 59 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 31 / 54 % | 90 / 97 % | 52 / 66 % | 69 / 88 % | 57 / 77 % | 34 / 56 % | 70 / 82 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 30 / 57 % | 87 / 99 % | 30 / 62 % | 84 / 96 % | 61 / 80 % | 33 / 59 % | 69 / 84 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 45 % | 83 / 97 % | 21 / 43 % | 77 / 88 % | 39 / 63 % | 19 / 40 % | 48 / 67 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 27 / 56 % | 40 / 82 % | 22 / 68 % | 78 / 96 % | 26 / 51 % | 25 / 55 % | 51 / 77 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 27 / 47 % | 54 / 82 % | 11 / 23 % | 76 / 85 % | 33 / 58 % | 14 / 29 % | 24 / 45 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 21 / 48 % | 67 / 95 % | 13 / 34 % | 72 / 85 % | 35 / 60 % | 15 / 38 % | 25 / 50 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 32 % | 68 / 94 % | 3 / 19 % | 72 / 85 % | 20 / 47 % | 9 / 30 % | 24 / 49 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 30 / 52 % | 42 / 89 % | 14 / 32 % | 69 / 90 % | 46 / 70 % | 19 / 41 % | 19 / 53 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 17 / 40 % | 62 / 88 % | 4 / 17 % | 50 / 78 % | 20 / 44 % | 7 / 22 % | 15 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 42 / 82 % | 0 / 0 % | 59 / 79 % | 10 / 29 % | 2 / 8 % | 8 / 14 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 33 / 53 % | 19 / 60 % | 15 / 36 % | 24 / 51 % | 58 / 78 % | 24 / 48 % | 55 / 74 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 17 / 39 % | 58 / 95 % | 12 / 30 % | 49 / 79 % | 25 / 48 % | 8 / 24 % | 18 / 42 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 11 / 37 % | 56 / 92 % | 9 / 26 % | 24 / 60 % | 21 / 46 % | 12 / 37 % | 23 / 51 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 56 / 92 % | 2 / 9 % | 20 / 51 % | 14 / 37 % | 6 / 19 % | 11 / 26 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 55 / 87 % | 3 / 14 % | 4 / 21 % | 13 / 31 % | 6 / 21 % | 10 / 26 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 14 / 48 % | 53 / 90 % | 8 / 32 % | 16 / 54 % | 29 / 56 % | 10 / 29 % | 22 / 52 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 47 % | 28 / 82 % | 4 / 18 % | 49 / 71 % | 13 / 39 % | 9 / 27 % | 15 / 46 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 11 / 29 % | 48 / 96 % | 1 / 7 % | 33 / 56 % | 13 / 37 % | 5 / 18 % | 11 / 33 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 34 / 80 % | 11 / 35 % | 38 / 75 % | 41 / 67 % | 15 / 42 % | 13 / 36 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 37 / 84 % | 2 / 9 % | 30 / 65 % | 16 / 37 % | 5 / 16 % | 7 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 46 % | 15 / 71 % | 8 / 25 % | 35 / 64 % | 22 / 49 % | 10 / 28 % | 14 / 38 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 34 / 61 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 9 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 34 / 57 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 15 / 29 % | 27 / 83 % | 6 / 18 % | 11 / 25 % | 11 / 33 % | 5 / 16 % | 11 / 28 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 18 / 55 % | 0 / 0 % | 3 / 23 % | 10 / 25 % | 1 / 7 % | 10 / 25 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 33 % | 16 / 80 % | 1 / 7 % | 14 / 37 % | 10 / 28 % | 4 / 17 % | 8 / 23 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 15 / 52 % | 0 / 0 % | 8 / 24 % | 8 / 20 % | 1 / 5 % | 6 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 32 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 8 / 19 % | 4 / 13 % | 8 / 20 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 14 / 43 % | 1 / 8 % | 0 / 0 % | 14 / 38 % | 1 / 10 % | 11 / 37 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 12 / 45 % | 1 / 5 % | 13 / 35 % | 13 / 35 % | 4 / 12 % | 12 / 34 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 12 / 25 % | 0 / 0 % | 7 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 11 / 31 % | 9 / 28 % | 0 / 0 % | 9 / 18 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 5 / 13 % | 8 / 22 % | 3 / 12 % | 11 / 35 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 10 / 51 % | 0 / 0 % | 10 / 31 % | 7 / 17 % | 0 / 0 % | 7 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 10 / 18 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 3 / 36 % | 0 / 2 % | 6 / 25 % | 9 / 20 % | 3 / 14 % | 8 / 18 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 8 / 77 % | 0 / 3 % | 0 / 7 % | 9 / 22 % | 3 / 11 % | 9 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 8 / 17 % | 3 / 8 % | 5 / 13 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % |
