[English](README.md) · [Deutsch](README.de.md)

# Google DeepMind strengthens the Frontier Safety Framework

Bericht Q003895 · Quelle deepmind.google · Datum 2025-09-22 · [Original öffnen](https://deepmind.google/blog/strengthening-our-frontier-safety-framework/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Google DeepMind beschreibt eine überarbeitete Fassung seines Sicherheitsrahmens für fortgeschrittene KI. Sie ergänzt Warnstufen für schädliche Manipulation, erweitert Prüfungen auf mögliche Fehlanpassung und interne Großeinsätze und führt Beobachtungsstufen für weniger extreme Risiken ein. Der Bericht gibt DeepMinds eigene Darstellung wieder; unabhängige Wirksamkeitsnachweise nennt er nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 34 / 56 % | 84 / 96 % | 43 / 79 % | 98 / 100 % | 57 / 78 % | 42 / 74 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 35 / 56 % | 95 / 99 % | 64 / 77 % | 95 / 99 % | 56 / 76 % | 68 / 81 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 32 / 60 % | 93 / 99 % | 48 / 74 % | 77 / 96 % | 63 / 80 % | 66 / 82 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 28 / 55 % | 92 / 100 % | 43 / 76 % | 93 / 99 % | 42 / 72 % | 51 / 76 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 36 / 56 % | 77 / 94 % | 32 / 64 % | 89 / 97 % | 56 / 78 % | 48 / 71 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 18 / 44 % | 69 / 92 % | 17 / 27 % | 40 / 61 % | 33 / 57 % | 32 / 53 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 14 / 40 % | 58 / 89 % | 5 / 22 % | 69 / 87 % | 17 / 42 % | 13 / 34 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 38 % | 0 / 0 % | 6 / 31 % | 68 / 89 % | 19 / 47 % | 10 / 32 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 60 / 92 % | 1 / 11 % | 31 / 67 % | 13 / 31 % | 6 / 21 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 11 / 44 % | 59 / 84 % | 4 / 19 % | 7 / 26 % | 17 / 42 % | 14 / 37 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 23 / 53 % | 53 / 90 % | 11 / 51 % | 54 / 87 % | 13 / 32 % | 27 / 64 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 29 / 54 % | 0 / 0 % | 52 / 77 % | 7 / 22 % | 5 / 10 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 16 / 39 % | 48 / 89 % | 7 / 27 % | 47 / 78 % | 20 / 42 % | 13 / 34 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 10 / 36 % | 41 / 82 % | 5 / 19 % | 23 / 44 % | 19 / 44 % | 7 / 21 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 45 % | 28 / 87 % | 4 / 21 % | 37 / 64 % | 17 / 43 % | 10 / 37 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 34 / 67 % | 1 / 8 % | 20 / 60 % | 13 / 32 % | 7 / 14 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 29 / 64 % | 8 / 28 % | 23 / 57 % | 31 / 59 % | 7 / 19 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 22 / 50 % | 5 / 37 % | 5 / 21 % | 0 / 0 % | 31 / 61 % | 26 / 53 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 16 / 42 % | 18 / 89 % | 3 / 17 % | 27 / 67 % | 23 / 53 % | 10 / 44 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 32 % | 26 / 72 % | 1 / 8 % | 10 / 31 % | 10 / 28 % | 6 / 17 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 25 / 61 % | 1 / 11 % | 1 / 7 % | 8 / 19 % | 6 / 15 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 24 / 61 % | 1 / 5 % | 8 / 31 % | 10 / 22 % | 16 / 32 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 20 / 80 % | 3 / 16 % | 9 / 28 % | 10 / 27 % | 8 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 13 / 30 % | 20 / 53 % | 0 / 4 % | 8 / 26 % | 10 / 26 % | 5 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 44 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 47 % | 0 / 0 % | 5 / 21 % | 5 / 28 % | 16 / 41 % | 6 / 19 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 12 / 45 % | 0 / 2 % | 0 / 2 % | 8 / 17 % | 5 / 8 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 11 / 35 % | 1 / 19 % | 1 / 5 % | 0 / 0 % | 7 / 19 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 10 / 35 % | 0 / 3 % | 0 / 0 % | 9 / 21 % | 5 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 7 / 26 % | 10 / 32 % | 5 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 0 / 0 % | 9 / 21 % | 5 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 9 / 20 % | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 1 / 33 % | 0 / 3 % | 6 / 30 % | 8 / 17 % | 6 / 14 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 2 / 23 % | 0 / 3 % | 1 / 15 % | 8 / 19 % | 5 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 23 % | 4 / 81 % | 0 / 2 % | 0 / 0 % | 7 / 21 % | 4 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 6 / 16 % | 6 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 3 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 12 % | 0 / 0 % | 5 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 4 / 9 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % |
