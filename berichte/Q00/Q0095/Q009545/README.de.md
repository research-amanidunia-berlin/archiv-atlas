[English](README.md) · [Deutsch](README.de.md)

# Auf dem Weg zu Sicherheitsnachweisen für das Training von Frontier-KI

Bericht Q009545 · Quelle openai.com · Datum – · [Original öffnen](https://openai.com/index/towards-safety-cases-for-frontier-ai-training/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI schlägt technische und operative Leitlinien für Sicherheitsnachweise beim Reinforcement-Learning-Training von Frontier-KI vor: Dazu zählen Alignment-Tests, gehärtete Sandboxes, Echtzeitüberwachung, unabhängige Prüfungen und klare Pausen- und Eskalationsverfahren. Der Bericht kennzeichnet sie als vorläufige Empfehlungen und langfristiges Ziel; er belegt nicht, dass alle Maßnahmen bereits umgesetzt oder wirksam sind.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 61 / 77 % | 99 / 100 % | 100 / 100 % | 89 / 94 % | 89 / 95 % | 87 / 93 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 74 / 84 % | 97 / 98 % | 100 / 100 % | 90 / 94 % | 92 / 97 % | 89 / 93 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 58 / 72 % | 90 / 96 % | 100 / 100 % | 81 / 90 % | 71 / 84 % | 68 / 83 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 46 / 67 % | 99 / 100 % | 97 / 99 % | 83 / 90 % | 89 / 95 % | 90 / 93 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 53 / 69 % | 97 / 99 % | 99 / 100 % | 81 / 90 % | 90 / 95 % | 88 / 94 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 32 / 53 % | 81 / 96 % | 97 / 99 % | 67 / 84 % | 18 / 43 % | 37 / 57 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 30 / 51 % | 96 / 99 % | 83 / 90 % | 53 / 73 % | 62 / 77 % | 47 / 68 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 33 / 54 % | 95 / 99 % | 92 / 95 % | 66 / 83 % | 38 / 60 % | 53 / 74 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 33 / 54 % | 71 / 90 % | 92 / 96 % | 33 / 57 % | 34 / 56 % | 60 / 75 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 32 / 56 % | 91 / 99 % | 82 / 92 % | 42 / 69 % | 38 / 57 % | 44 / 62 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 41 / 63 % | 90 / 98 % | 90 / 96 % | 63 / 80 % | 38 / 64 % | 52 / 72 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 44 / 64 % | 89 / 99 % | 67 / 95 % | 71 / 86 % | 70 / 86 % | 73 / 86 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 50 / 67 % | 56 / 91 % | 66 / 87 % | 83 / 90 % | 85 / 93 % | 87 / 93 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 81 / 90 % | 50 / 56 % | 45 / 66 % | 24 / 45 % | 20 / 32 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 14 / 44 % | 80 / 97 % | 43 / 64 % | 24 / 51 % | 12 / 38 % | 21 / 42 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 33 / 49 % | 78 / 90 % | 75 / 85 % | 43 / 68 % | 28 / 54 % | 30 / 48 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 75 / 91 % | 75 / 85 % | 22 / 49 % | 12 / 30 % | 16 / 29 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 20 / 52 % | 43 / 83 % | 72 / 92 % | 19 / 41 % | 18 / 46 % | 30 / 58 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 32 / 59 % | 72 / 95 % | 56 / 81 % | 36 / 61 % | 42 / 68 % | 22 / 41 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 65 / 89 % | 41 / 66 % | 8 / 22 % | 4 / 10 % | 6 / 16 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 54 / 87 % | 26 / 44 % | 11 / 28 % | 8 / 19 % | 6 / 12 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 52 / 84 % | 8 / 25 % | 5 / 15 % | 5 / 13 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 24 / 48 % | 9 / 34 % | 51 / 71 % | 29 / 55 % | 33 / 61 % | 35 / 63 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 48 / 85 % | 43 / 65 % | 9 / 23 % | 4 / 12 % | 7 / 11 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 23 / 72 % | 27 / 64 % | 45 / 71 % | 16 / 44 % | 43 / 64 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 43 / 92 % | 27 / 62 % | 29 / 55 % | 13 / 33 % | 8 / 18 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 41 / 78 % | 2 / 12 % | 7 / 16 % | 4 / 12 % | 6 / 13 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 37 / 86 % | 3 / 17 % | 8 / 19 % | 6 / 13 % | 7 / 14 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 35 / 69 % | 29 / 60 % | 8 / 17 % | 3 / 6 % | 11 / 19 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 9 / 57 % | 5 / 42 % | 21 / 45 % | 8 / 22 % | 12 / 24 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 19 / 75 % | 1 / 8 % | 9 / 18 % | 3 / 8 % | 7 / 12 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 14 / 39 % | 17 / 63 % | 8 / 27 % | 15 / 40 % | 16 / 38 % | 15 / 30 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 4 / 12 % | 5 / 11 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 2 / 6 % | 5 / 12 % | – | – |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 3 / 10 % | 9 / 17 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 4 / 13 % | 9 / 20 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 1 / 20 % | 0 / 0 % | 5 / 12 % | 5 / 11 % | 4 / 9 % | – | – |
