[English](README.md) · [Deutsch](README.de.md)

# Amazon Nova Reel - AWS AI Service Cards

Bericht Q004873 · Quelle docs.aws.amazon.com · Datum 2025-07-16 · [Original öffnen](https://docs.aws.amazon.com/ai/responsible-ai/nova-reel/overview.html)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

AWS beschreibt Nova Reel als Bedrock-Modell, das aus englischen Textprompts und optionalen Bildern Videos von bis zu 120 Sekunden erzeugt. Der Anbieter berichtet über Sicherheitsprüfungen, betont aber, dass Kunden Wirksamkeit und Risiken selbst für ihren Einsatzfall bewerten müssen. Zu den Grenzen zählen mögliche unerwünschte oder fehlerhafte Inhalte, fehlende Audio- und 3D-Ausgabe sowie eingeschränkte Sprach- und Eingabeformate.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 46 / 64 % | 90 / 99 % | 59 / 79 % | 100 / 100 % | 81 / 90 % | 34 / 58 % | 77 / 88 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 29 / 48 % | 92 / 95 % | 20 / 38 % | 99 / 100 % | 64 / 82 % | 11 / 27 % | 52 / 68 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 24 / 43 % | 94 / 99 % | 5 / 13 % | 98 / 99 % | 21 / 47 % | 9 / 22 % | 20 / 47 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 24 / 44 % | 91 / 95 % | 62 / 68 % | 97 / 98 % | 60 / 79 % | 17 / 30 % | 65 / 75 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 62 / 77 % | 92 / 99 % | 97 / 98 % | 97 / 99 % | 88 / 93 % | 86 / 92 % | 89 / 93 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 95 / 98 % | 22 / 34 % | 96 / 99 % | 38 / 67 % | 28 / 48 % | 52 / 68 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 75 / 92 % | 24 / 42 % | 96 / 97 % | 60 / 81 % | 23 / 44 % | 60 / 79 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 22 / 47 % | 71 / 96 % | 19 / 36 % | 96 / 99 % | 53 / 77 % | 15 / 36 % | 39 / 66 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 35 / 54 % | 93 / 98 % | 58 / 75 % | 94 / 96 % | 65 / 84 % | 43 / 65 % | 80 / 89 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 47 / 77 % | 0 / 0 % | 91 / 96 % | 9 / 24 % | 1 / 8 % | 6 / 12 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 22 / 48 % | 74 / 94 % | 32 / 47 % | 88 / 94 % | 25 / 49 % | 15 / 33 % | 44 / 65 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 20 / 39 % | 77 / 93 % | 15 / 29 % | 82 / 90 % | 37 / 61 % | 15 / 30 % | 40 / 59 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 81 / 98 % | 4 / 10 % | 81 / 94 % | 25 / 55 % | 6 / 20 % | 14 / 42 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 30 / 66 % | 2 / 7 % | 75 / 88 % | 26 / 53 % | 6 / 16 % | 6 / 15 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 61 / 86 % | 5 / 9 % | 42 / 63 % | 26 / 51 % | 6 / 14 % | 17 / 33 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 58 / 81 % | 9 / 17 % | 59 / 71 % | 25 / 46 % | 10 / 18 % | 19 / 30 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 58 / 88 % | 25 / 33 % | 50 / 66 % | 35 / 61 % | 12 / 25 % | 22 / 39 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 15 / 36 % | 57 / 86 % | 6 / 14 % | 45 / 68 % | 21 / 45 % | 7 / 20 % | 24 / 43 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 54 / 85 % | 1 / 7 % | 7 / 18 % | 9 / 21 % | 2 / 8 % | 9 / 18 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 2 / 8 % | 53 / 71 % | 18 / 41 % | 3 / 10 % | 10 / 25 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 49 / 69 % | 10 / 27 % | 4 / 14 % | 6 / 15 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 44 / 83 % | 0 / 2 % | 0 / 0 % | 8 / 23 % | 1 / 6 % | 4 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 2 / 6 % | 41 / 65 % | 24 / 55 % | 3 / 9 % | 17 / 38 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 40 / 71 % | 0 / 2 % | 35 / 59 % | 8 / 24 % | 2 / 9 % | 6 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 28 / 45 % | 0 / 0 % | 0 / 0 % | 39 / 63 % | 21 / 32 % | 13 / 23 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 33 / 57 % | 2 / 7 % | 37 / 62 % | 13 / 32 % | 4 / 13 % | 10 / 21 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 31 / 73 % | 2 / 5 % | 0 / 0 % | 13 / 34 % | 1 / 6 % | 13 / 26 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 31 / 68 % | 6 / 9 % | 28 / 51 % | 29 / 50 % | 9 / 18 % | 21 / 31 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 30 / 64 % | 1 / 4 % | 17 / 31 % | 14 / 33 % | 3 / 10 % | 7 / 17 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 24 / 64 % | 0 / 2 % | 15 / 34 % | 7 / 19 % | 2 / 10 % | 5 / 14 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | 19 / 45 % | 4 / 14 % | 7 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 36 % | 0 / 0 % | 0 / 3 % | 1 / 12 % | 11 / 35 % | 4 / 11 % | 7 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 6 / 18 % | 14 / 38 % | 3 / 12 % | 7 / 16 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 27 % | 3 / 9 % | 11 / 23 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 10 / 28 % | 3 / 10 % | 11 / 29 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 10 / 24 % | 2 / 9 % | 6 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 7 % | 5 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 5 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 7 / 18 % | 2 / 7 % | 5 / 10 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 5 / 11 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 5 / 12 % |
