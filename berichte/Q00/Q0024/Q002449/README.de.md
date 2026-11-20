[English](README.md) · [Deutsch](README.de.md)

# An early warning system for novel AI risks

Bericht Q002449 · Quelle deepmind.google · Datum 2023-05-25 · [Original öffnen](https://deepmind.google/blog/an-early-warning-system-for-novel-ai-risks/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag präsentiert einen vorgeschlagenen Rahmen, der KI-Modelle auf gefährliche Fähigkeiten und mögliche Fehlanpassung prüfen soll, damit Ergebnisse Entscheidungen über Training, Einsatz, Transparenz und Sicherheit unterstützen. Die Prüfungen können laut Text Risiken übersehen, vor allem wenn diese stark von Faktoren außerhalb des Modells abhängen, und müssen deshalb mit weiteren Maßnahmen ergänzt werden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 39 / 63 % | 89 / 99 % | 56 / 87 % | 98 / 100 % | 62 / 84 % | 30 / 57 % | 72 / 88 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 24 / 55 % | 94 / 99 % | 49 / 72 % | 78 / 92 % | 54 / 76 % | 34 / 56 % | 51 / 72 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 39 / 65 % | 73 / 98 % | 75 / 93 % | 93 / 98 % | 65 / 84 % | 38 / 65 % | 80 / 90 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 33 / 62 % | 86 / 99 % | 71 / 91 % | 75 / 97 % | 46 / 77 % | 58 / 79 % | 73 / 87 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 16 / 53 % | 83 / 99 % | 26 / 72 % | 45 / 92 % | 36 / 68 % | 20 / 44 % | 39 / 70 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 28 / 61 % | 50 / 91 % | 79 / 96 % | 48 / 94 % | 14 / 37 % | 58 / 79 % | 59 / 82 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 27 / 59 % | 31 / 81 % | 60 / 80 % | 61 / 87 % | 64 / 84 % | 60 / 79 % | 79 / 89 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 32 / 59 % | 77 / 96 % | 42 / 69 % | 72 / 96 % | 55 / 80 % | 49 / 73 % | 60 / 80 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 13 / 42 % | 17 / 78 % | 10 / 46 % | 76 / 93 % | 33 / 64 % | 9 / 30 % | 20 / 52 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 27 / 59 % | 74 / 94 % | 31 / 62 % | 69 / 90 % | 42 / 66 % | 31 / 57 % | 28 / 53 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 20 / 45 % | 66 / 97 % | 3 / 11 % | 71 / 90 % | 20 / 49 % | 5 / 16 % | 10 / 30 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 9 / 44 % | 69 / 87 % | 22 / 45 % | 14 / 51 % | 24 / 53 % | 8 / 21 % | 18 / 35 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 64 / 94 % | 1 / 11 % | 35 / 71 % | 10 / 29 % | 5 / 17 % | 10 / 38 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 38 / 83 % | 0 / 2 % | 58 / 80 % | 8 / 29 % | 0 / 0 % | 7 / 14 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 27 / 53 % | 55 / 93 % | 23 / 41 % | 23 / 61 % | 27 / 58 % | 18 / 39 % | 24 / 45 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 14 / 45 % | 36 / 84 % | 7 / 32 % | 47 / 84 % | 27 / 54 % | 7 / 21 % | 21 / 49 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 40 % | 45 / 91 % | 2 / 13 % | 22 / 52 % | 15 / 40 % | 5 / 21 % | 20 / 41 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 10 / 40 % | 45 / 90 % | 1 / 9 % | 28 / 73 % | 15 / 38 % | 6 / 14 % | 12 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 45 % | 45 / 94 % | 8 / 25 % | 23 / 66 % | 27 / 55 % | 11 / 29 % | 25 / 51 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 7 / 34 % | 45 / 89 % | 4 / 24 % | 2 / 40 % | 10 / 32 % | 6 / 20 % | 11 / 30 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 13 / 48 % | 31 / 80 % | 3 / 15 % | 42 / 70 % | 18 / 44 % | 7 / 20 % | 11 / 35 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 19 / 90 % | 11 / 44 % | 27 / 72 % | 41 / 70 % | 11 / 32 % | 9 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 38 / 78 % | 0 / 3 % | 6 / 24 % | 6 / 23 % | 4 / 13 % | 10 / 20 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 9 / 40 % | 37 / 85 % | 7 / 19 % | 14 / 46 % | 20 / 48 % | 4 / 16 % | 13 / 36 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 32 / 65 % | 1 / 5 % | 2 / 28 % | 10 / 32 % | 1 / 7 % | 11 / 27 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 26 / 86 % | 1 / 9 % | 5 / 53 % | 12 / 33 % | 3 / 12 % | 6 / 23 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 26 / 69 % | 0 / 0 % | 3 / 28 % | 6 / 20 % | 0 / 0 % | 7 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 32 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 16 / 47 % | 8 / 52 % | 6 / 25 % | 7 / 23 % | 9 / 31 % | 10 / 26 % | 15 / 45 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 16 / 71 % | 0 / 3 % | 6 / 36 % | 7 / 16 % | 1 / 6 % | 8 / 21 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 7 / 34 % | 16 / 84 % | 0 / 3 % | 12 / 31 % | 6 / 22 % | 3 / 12 % | 6 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 12 / 68 % | 1 / 6 % | 11 / 40 % | 11 / 34 % | 3 / 10 % | 9 / 26 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 33 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 7 / 22 % | 4 / 12 % | 11 / 26 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 11 / 50 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 3 % | 5 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 6 / 37 % | 2 / 43 % | 0 / 2 % | 10 / 41 % | 6 / 17 % | 2 / 9 % | 6 / 15 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 9 / 25 % | 2 / 7 % | 5 / 20 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 8 / 90 % | 0 / 3 % | 1 / 28 % | 7 / 21 % | 2 / 10 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 6 / 94 % | 0 / 3 % | 1 / 12 % | 6 / 16 % | 1 / 4 % | 5 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 13 % | 2 / 7 % | 6 / 13 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
