[English](README.md) · [Deutsch](README.de.md)

# Trustworthy AI for the enterprise: How to train an LLM to follow a code of conduct

Bericht Q004742 · Quelle oecd.ai · Datum 2024-12-18 · [Original öffnen](https://oecd.ai/en/wonk/how-to-train-an-llm-to-follow-a-code-of-conduct)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

AI21 beschreibt, wie das Unternehmen OECD-KI-Prinzipien in 60 konkrete Verhaltensregeln überführt und seine Jamba-1.5-Modelle mit Angriffsprompts sowie menschlichem Feedback daran ausrichtet. Der Artikel stellt den Kodex als anpassbar dar, nennt aber keine zusammengefassten Testergebnisse oder unabhängigen Belege für seine Wirksamkeit; vorliegend ist der vollständige Artikel, kein Auszug oder eine Fehlerseite.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 63 / 75 % | 100 / 100 % | 100 / 100 % | 88 / 93 % | 73 / 86 % | 80 / 88 % | 84 / 94 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 39 / 59 % | 90 / 96 % | 99 / 100 % | 66 / 83 % | 58 / 76 % | 67 / 80 % | 56 / 80 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 47 / 64 % | 98 / 99 % | 99 / 100 % | 81 / 90 % | 65 / 81 % | 77 / 86 % | 77 / 89 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 33 / 51 % | 67 / 91 % | 95 / 98 % | 57 / 77 % | 12 / 30 % | 19 / 34 % | 8 / 27 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 41 / 61 % | 95 / 99 % | 94 / 98 % | 64 / 81 % | 58 / 76 % | 57 / 74 % | 52 / 76 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 87 / 98 % | 78 / 90 % | 25 / 51 % | 8 / 28 % | 15 / 30 % | 1 / 6 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 33 / 57 % | 53 / 85 % | 87 / 94 % | 16 / 38 % | 15 / 36 % | 20 / 42 % | 25 / 49 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 73 / 89 % | 83 / 91 % | 15 / 38 % | 5 / 17 % | 11 / 24 % | 1 / 8 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 41 / 76 % | 75 / 86 % | 9 / 24 % | 3 / 10 % | 10 / 19 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 22 / 46 % | 53 / 89 % | 68 / 88 % | 40 / 66 % | 9 / 29 % | 14 / 39 % | 3 / 15 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 30 / 50 % | 66 / 88 % | 32 / 51 % | 36 / 61 % | 21 / 37 % | 24 / 40 % | 10 / 24 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 13 / 30 % | 65 / 94 % | 35 / 63 % | 11 / 31 % | 4 / 18 % | 7 / 21 % | 1 / 5 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 58 / 84 % | 13 / 25 % | 7 / 15 % | 1 / 8 % | 7 / 12 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 18 / 37 % | 55 / 77 % | 45 / 64 % | 14 / 35 % | 6 / 15 % | 13 / 30 % | 1 / 6 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 13 / 40 % | 54 / 89 % | 39 / 72 % | 19 / 41 % | 3 / 9 % | 9 / 17 % | 0 / 4 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 17 / 38 % | 49 / 84 % | 33 / 66 % | 22 / 46 % | 7 / 24 % | 11 / 25 % | 4 / 19 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 48 / 81 % | 2 / 9 % | 9 / 21 % | 4 / 15 % | 7 / 17 % | 0 / 4 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 10 / 27 % | 41 / 76 % | 11 / 27 % | 9 / 24 % | 3 / 13 % | 6 / 15 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 37 / 73 % | 4 / 23 % | 11 / 28 % | 2 / 12 % | 6 / 14 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 32 / 82 % | 0 / 0 % | 7 / 14 % | 2 / 7 % | 6 / 14 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 18 / 43 % | 16 / 53 % | 31 / 49 % | 20 / 45 % | 7 / 19 % | 7 / 21 % | 2 / 8 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 28 % | 29 / 73 % | 1 / 5 % | 10 / 26 % | 5 / 18 % | 8 / 21 % | 0 / 4 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 25 / 58 % | 20 / 39 % | 11 / 35 % | 2 / 9 % | 8 / 20 % | 1 / 4 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 17 / 67 % | 17 / 30 % | 19 / 41 % | 5 / 13 % | 6 / 13 % | 1 / 4 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 18 / 80 % | 0 / 0 % | 9 / 18 % | 2 / 9 % | 5 / 11 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 38 % | 4 / 12 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 14 / 67 % | 0 / 0 % | 7 / 15 % | 1 / 4 % | 4 / 8 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 1 / 5 % | 10 / 21 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 10 / 47 % | 0 / 0 % | 9 / 18 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 7 / 17 % | 9 / 18 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 9 / 30 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 4 / 11 % | 6 / 11 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 3 / 14 % | 8 / 16 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 2 / 12 % | 6 / 12 % | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 7 / 61 % | 2 / 9 % | 7 / 14 % | 2 / 7 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 3 / 11 % | 5 / 14 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 2 / 6 % | 4 / 7 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 1 / 28 % | 0 / 3 % | 6 / 13 % | 1 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 4 / 10 % | 0 / 0 % | – |
