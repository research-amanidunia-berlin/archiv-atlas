[English](README.md) · [Deutsch](README.de.md)

# Wie wir Fehlausrichtung bei Frontier-Modellen erkennen

Bericht Q009534 · Quelle openai.com · Datum – · [Original öffnen](https://openai.com/index/how-we-detect-frontier-model-misalignment)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt ein mehrstufiges System, das Fehlverhalten leistungsfähiger KI-Agenten überwachen und bei schweren Sicherheitsfällen eine Reaktion auslösen soll. Der Bericht nennt früh erkannte Vorfälle und laufende Tests, räumt aber Grenzen wie Fehlalarme, Rechenaufwand, mögliche Umgehung und eingeschränkte externe Überwachung ein.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 45 / 63 % | 100 / 100 % | – | 99 / 100 % | 84 / 90 % | 90 / 94 % | 75 / 88 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 62 / 75 % | 100 / 100 % | – | 100 / 100 % | 82 / 90 % | 93 / 95 % | 84 / 92 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 58 / 71 % | 71 / 94 % | – | 100 / 100 % | 86 / 92 % | 88 / 94 % | 71 / 86 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 63 / 80 % | 97 / 99 % | – | 100 / 100 % | 86 / 92 % | 88 / 92 % | 75 / 89 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 69 / 81 % | 99 / 100 % | – | 100 / 100 % | 92 / 95 % | 95 / 97 % | 89 / 95 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 40 / 56 % | 37 / 79 % | – | 96 / 98 % | 74 / 86 % | 73 / 82 % | 24 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 49 / 67 % | 95 / 100 % | – | 92 / 97 % | 76 / 87 % | 77 / 86 % | 50 / 72 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 54 / 70 % | 68 / 93 % | – | 90 / 96 % | 83 / 90 % | 93 / 95 % | 74 / 87 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 92 / 98 % | – | 93 / 96 % | 69 / 84 % | 56 / 70 % | 44 / 65 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 54 / 88 % | – | 93 / 96 % | 44 / 69 % | 43 / 60 % | 19 / 38 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 70 / 96 % | – | 91 / 94 % | 69 / 83 % | 61 / 74 % | 27 / 50 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 88 / 98 % | – | 44 / 74 % | 48 / 71 % | 51 / 71 % | 24 / 45 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 37 / 54 % | 83 / 99 % | – | 44 / 60 % | 49 / 71 % | 65 / 77 % | 44 / 61 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 51 / 90 % | – | 83 / 93 % | 57 / 79 % | 45 / 66 % | 32 / 54 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 4 / 39 % | – | 58 / 77 % | 32 / 56 % | 14 / 24 % | 9 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 26 / 48 % | 53 / 87 % | – | 50 / 77 % | 26 / 49 % | 46 / 62 % | 15 / 37 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 53 / 87 % | – | 45 / 66 % | 9 / 23 % | 0 / 0 % | 4 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 20 / 45 % | 0 / 0 % | – | 21 / 35 % | 38 / 64 % | 49 / 71 % | 16 / 33 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 48 / 84 % | – | 40 / 64 % | 8 / 19 % | 6 / 12 % | 2 / 7 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 27 / 52 % | 18 / 61 % | – | 45 / 61 % | 23 / 44 % | 15 / 27 % | 12 / 28 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 45 / 96 % | – | 1 / 6 % | 0 / 0 % | 0 / 0 % | 4 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 8 / 60 % | – | 39 / 62 % | 10 / 27 % | 22 / 39 % | 8 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 46 % | 35 / 91 % | – | 24 / 48 % | 14 / 35 % | 16 / 29 % | 8 / 22 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 34 / 62 % | 6 / 17 % | 5 / 9 % | 3 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 24 / 78 % | – | 26 / 54 % | 6 / 13 % | 12 / 20 % | 1 / 3 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 25 / 79 % | – | 1 / 7 % | 7 / 17 % | 8 / 14 % | 4 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 25 / 96 % | – | 11 / 41 % | 10 / 25 % | 6 / 11 % | 5 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 23 / 41 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 16 / 38 % | 0 / 0 % | – | 0 / 0 % | 10 / 31 % | 19 / 34 % | 6 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 17 / 65 % | – | 0 / 0 % | 6 / 13 % | 9 / 14 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 15 / 90 % | – | 3 / 25 % | 13 / 33 % | 0 / 0 % | 11 / 25 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 13 / 80 % | – | 15 / 24 % | 7 / 17 % | 0 / 0 % | 5 / 12 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 14 / 47 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 17 % | 10 / 18 % | 4 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 0 / 0 % | 5 / 11 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 8 / 12 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 14 % | 7 / 15 % | 1 / 4 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 8 / 66 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 8 % | 7 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 3 / 6 % |
