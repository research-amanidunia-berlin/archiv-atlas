[English](README.md) · [Deutsch](README.de.md)

# Inside our approach to the Model Spec

Bericht Q001880 · Quelle openai.com · Datum 2026-03-25 · [Original öffnen](https://openai.com/index/our-approach-to-the-model-spec/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt die Model Spec als öffentliches, fortlaufend überarbeitetes Zielbild dafür, wie seine Modelle Anweisungen, Konflikte, Nutzerfreiheit und Sicherheit behandeln sollen. Das Unternehmen räumt ein, dass die Modelle dieses Ziel noch nicht durchgehend erreichen; die Spec, interne und öffentliche Rückmeldungen sowie Tests sollen die Umsetzung verbessern, wobei der Bericht OpenAIs eigene Darstellung wiedergibt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 72 / 81 % | 99 / 99 % | 100 / 100 % | 90 / 94 % | 84 / 93 % | 90 / 93 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 42 / 64 % | 91 / 96 % | 99 / 100 % | 61 / 80 % | 67 / 83 % | 74 / 86 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 37 / 59 % | 71 / 96 % | 98 / 100 % | 62 / 82 % | 66 / 84 % | 67 / 83 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 27 / 53 % | 88 / 100 % | 96 / 100 % | 57 / 81 % | 43 / 71 % | 52 / 79 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 27 / 54 % | 87 / 98 % | 96 / 98 % | 50 / 72 % | 45 / 69 % | 43 / 64 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 36 / 56 % | 65 / 91 % | 94 / 98 % | 57 / 77 % | 18 / 44 % | 45 / 66 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 61 / 89 % | 93 / 97 % | 20 / 48 % | 0 / 0 % | 17 / 30 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 35 / 58 % | 73 / 96 % | 92 / 97 % | 72 / 86 % | 61 / 84 % | 71 / 85 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 35 / 58 % | 66 / 96 % | 92 / 98 % | 44 / 68 % | 22 / 50 % | 40 / 67 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 27 / 50 % | 60 / 94 % | 86 / 93 % | 57 / 77 % | 38 / 60 % | 33 / 54 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 56 / 87 % | 75 / 90 % | 10 / 32 % | 3 / 14 % | 8 / 15 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 36 % | 69 / 96 % | 39 / 67 % | 11 / 33 % | 2 / 11 % | 5 / 13 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 12 / 40 % | 39 / 90 % | 54 / 87 % | 68 / 83 % | 15 / 42 % | 15 / 37 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 28 % | 16 / 81 % | 54 / 83 % | 20 / 46 % | 8 / 31 % | 11 / 36 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 52 / 85 % | 32 / 69 % | 20 / 45 % | 5 / 16 % | 13 / 27 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 18 / 43 % | 34 / 88 % | 51 / 87 % | 38 / 64 % | 12 / 33 % | 25 / 46 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 17 / 44 % | 50 / 98 % | 50 / 80 % | 25 / 48 % | 8 / 29 % | 18 / 35 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 8 / 64 % | 0 / 0 % | 48 / 69 % | 13 / 30 % | 13 / 24 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 14 / 37 % | 40 / 86 % | 13 / 33 % | 11 / 32 % | 8 / 21 % | 11 / 27 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 4 / 55 % | 37 / 65 % | 18 / 43 % | 7 / 22 % | 6 / 15 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 10 / 34 % | 33 / 90 % | 4 / 29 % | 14 / 37 % | 8 / 29 % | 15 / 33 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 29 / 66 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 6 / 15 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 16 / 29 % | 28 / 88 % | 22 / 47 % | 10 / 27 % | 0 / 0 % | 10 / 21 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 28 / 91 % | 0 / 3 % | 6 / 17 % | 0 / 5 % | 4 / 6 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 6 / 21 % | 26 / 95 % | 2 / 8 % | 7 / 15 % | 0 / 0 % | 5 / 13 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 15 / 76 % | 22 / 57 % | 18 / 42 % | 12 / 34 % | 25 / 43 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 50 % | 0 / 0 % | 0 / 0 % | 9 / 33 % | 6 / 23 % | 10 / 29 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 17 / 50 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 7 / 11 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 11 / 43 % | 0 / 0 % | 0 / 0 % | 17 / 42 % | 12 / 28 % | 8 / 21 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 10 / 34 % | 13 / 92 % | 16 / 61 % | 14 / 41 % | 7 / 25 % | 12 / 35 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 14 / 28 % | 0 / 0 % | 13 / 41 % | 14 / 43 % | 0 / 0 % | 9 / 22 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 13 / 91 % | 5 / 19 % | 6 / 14 % | 1 / 3 % | 6 / 13 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 25 % | 5 / 42 % | 0 / 0 % | 8 / 21 % | 3 / 12 % | 8 / 18 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 0 % | 4 / 13 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 5 / 23 % | 8 / 67 % | 3 / 20 % | 7 / 22 % | 3 / 16 % | 6 / 16 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 6 / 14 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 7 / 32 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 7 / 18 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 7 % | 4 / 9 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | – | – |
