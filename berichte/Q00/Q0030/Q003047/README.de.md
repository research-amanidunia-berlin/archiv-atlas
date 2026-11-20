[English](README.md) · [Deutsch](README.de.md)

# Update on ARC's recent eval efforts

Bericht Q003047 · Quelle metr.org · Datum 2023-03-17 · [Original öffnen](https://metr.org/blog/2023-03-18-update-on-recent-evals/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

ARC zufolge konnten die getesteten Claude- und GPT-4-Versionen keinen vollständigen Plan zur autonomen Selbstreplikation zuverlässig entwickeln und ausführen, beherrschten aber mehrere dafür relevante Teilaufgaben und konnten Menschen einbeziehen. Der Bericht ist ein vorläufiger Überblick mit menschlicher Aufsicht und simulierten Versuchsteilen; METR fordert daher systematische Prüfungen künftiger, leistungsfähigerer Modelle.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 34 / 58 % | 95 / 100 % | 38 / 76 % | 99 / 100 % | 54 / 79 % | 59 / 78 % | 28 / 61 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 46 / 70 % | 85 / 96 % | 42 / 79 % | 99 / 100 % | 70 / 85 % | 60 / 76 % | 17 / 53 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 36 / 60 % | 93 / 100 % | 45 / 82 % | 97 / 99 % | 51 / 77 % | 67 / 82 % | 43 / 72 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 51 / 71 % | 90 / 100 % | 69 / 91 % | 95 / 99 % | 17 / 41 % | 64 / 80 % | 48 / 74 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 46 % | 75 / 99 % | 8 / 30 % | 89 / 96 % | 30 / 56 % | 24 / 43 % | 9 / 21 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 44 / 61 % | 88 / 99 % | 18 / 45 % | 81 / 90 % | 56 / 78 % | 42 / 64 % | 18 / 45 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 52 / 88 % | 14 / 42 % | 77 / 86 % | 60 / 79 % | 63 / 77 % | 16 / 42 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 24 / 60 % | 1 / 5 % | 76 / 87 % | 10 / 29 % | 10 / 21 % | 2 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 29 / 47 % | 42 / 92 % | 14 / 52 % | 72 / 93 % | 58 / 79 % | 51 / 66 % | 11 / 33 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 27 / 54 % | 71 / 99 % | 37 / 71 % | 50 / 88 % | 55 / 80 % | 57 / 77 % | 27 / 55 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 22 / 50 % | 57 / 94 % | 3 / 21 % | 68 / 89 % | 20 / 49 % | 28 / 52 % | 13 / 42 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 24 / 52 % | 64 / 89 % | 6 / 28 % | 53 / 77 % | 28 / 55 % | 12 / 26 % | 10 / 30 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 62 / 91 % | 1 / 7 % | 50 / 79 % | 9 / 28 % | 7 / 20 % | 2 / 11 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 25 / 61 % | 3 / 15 % | 60 / 83 % | 35 / 63 % | 8 / 18 % | 8 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 18 / 43 % | 60 / 89 % | 9 / 29 % | 26 / 60 % | 39 / 65 % | 41 / 61 % | 16 / 45 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 36 / 60 % | 44 / 94 % | 13 / 43 % | 47 / 70 % | 44 / 70 % | 48 / 65 % | 23 / 44 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 41 / 97 % | 6 / 29 % | 45 / 70 % | 23 / 52 % | 13 / 28 % | 6 / 31 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 29 / 63 % | 0 / 3 % | 40 / 67 % | 14 / 39 % | 10 / 21 % | 2 / 8 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 35 / 91 % | 1 / 12 % | 1 / 13 % | 9 / 24 % | 8 / 19 % | 3 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 32 / 80 % | 0 / 2 % | 17 / 59 % | 5 / 13 % | 5 / 9 % | 1 / 5 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 32 / 77 % | 0 / 3 % | 2 / 15 % | 7 / 21 % | 6 / 14 % | 4 / 16 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 29 / 66 % | 1 / 7 % | 4 / 28 % | 8 / 23 % | 8 / 16 % | 3 / 10 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 48 % | 0 / 0 % | 0 / 3 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 9 / 47 % | 1 / 12 % | 26 / 59 % | 9 / 31 % | 6 / 19 % | 3 / 16 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 24 / 69 % | 0 / 0 % | 0 / 0 % | 10 / 27 % | 9 / 19 % | 0 / 2 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 23 / 72 % | 0 / 2 % | 7 / 25 % | 7 / 16 % | 9 / 20 % | 1 / 4 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 13 / 35 % | 21 / 88 % | 2 / 13 % | 19 / 49 % | 15 / 45 % | 16 / 37 % | 5 / 18 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 18 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 18 / 54 % | 0 / 3 % | 3 / 30 % | 7 / 20 % | 6 / 14 % | 4 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 16 / 57 % | 0 / 3 % | 0 / 0 % | 11 / 31 % | 9 / 20 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 12 / 37 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 21 % | 12 / 24 % | 2 / 9 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 10 / 85 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 5 / 13 % | 2 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 6 / 93 % | 0 / 6 % | 2 / 30 % | 9 / 26 % | 5 / 12 % | 2 / 9 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 6 / 92 % | 0 / 0 % | 8 / 47 % | 6 / 20 % | 0 / 0 % | 1 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 24 % | 7 / 20 % | 7 / 16 % | 1 / 8 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 5 / 14 % | 0 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 10 % | 1 / 4 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 2 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 2 / 6 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 4 / 88 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 5 / 8 % | 1 / 3 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 4 / 10 % | 0 / 1 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 3 / 6 % | 1 / 6 % |
