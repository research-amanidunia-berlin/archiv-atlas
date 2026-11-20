[English](README.md) · [Deutsch](README.de.md)

# Introducing GPT-5.2-Codex

Bericht Q005961 · Quelle openai.com · Datum 2025-12-18 · [Original öffnen](https://openai.com/index/introducing-gpt-5-2-codex/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI zufolge verbessert GPT‑5.2‑Codex die Unterstützung bei langen und komplexen Programmieraufgaben und bietet stärkere Fähigkeiten für defensive Cybersicherheitsarbeit. Das Unternehmen räumt Dual-Use-Risiken ein: Das Modell liege noch unter der „High“-Stufe seines eigenen Sicherheitsrahmens und werde mit Schutzmaßnahmen sowie schrittweisem Zugang eingeführt. Die angeführten Leistungsbehauptungen sind im Bericht nicht mit konkreten Benchmarkzahlen belegt; das React-Fallbeispiel betrifft GPT‑5.1‑Codex‑Max.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 27 / 47 % | 93 / 99 % | – | 99 / 100 % | 51 / 74 % | 50 / 68 % | 15 / 38 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 44 / 61 % | 87 / 98 % | – | 96 / 99 % | 10 / 27 % | 70 / 81 % | 49 / 68 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 28 / 85 % | – | 91 / 96 % | 53 / 75 % | 12 / 25 % | 17 / 34 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 3 / 46 % | – | 89 / 95 % | 9 / 27 % | 0 / 0 % | 2 / 9 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 43 / 87 % | – | 89 / 93 % | 10 / 31 % | 13 / 28 % | 2 / 9 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 30 / 50 % | 45 / 90 % | – | 83 / 92 % | 41 / 70 % | 59 / 77 % | 26 / 48 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 60 / 96 % | – | 83 / 90 % | 20 / 44 % | 20 / 40 % | 9 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 11 / 59 % | – | 80 / 89 % | 6 / 13 % | 5 / 9 % | 1 / 3 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 29 / 85 % | – | 79 / 91 % | 32 / 56 % | 16 / 28 % | 21 / 43 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 20 / 42 % | 34 / 87 % | – | 78 / 93 % | 39 / 63 % | 32 / 53 % | 9 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 68 / 94 % | – | 78 / 88 % | 11 / 29 % | 7 / 20 % | 2 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 18 / 33 % | 68 / 92 % | – | 67 / 81 % | 22 / 48 % | 14 / 29 % | 4 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 23 / 75 % | – | 64 / 76 % | 7 / 21 % | 7 / 17 % | 2 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 58 / 78 % | 11 / 34 % | 6 / 16 % | 2 / 9 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 29 / 51 % | 53 / 95 % | – | 47 / 81 % | 55 / 76 % | 36 / 61 % | 20 / 39 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 29 % | 51 / 94 % | – | 46 / 69 % | 11 / 35 % | 16 / 37 % | 3 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 27 / 44 % | 14 / 69 % | – | 51 / 79 % | 49 / 72 % | 29 / 50 % | 10 / 24 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 6 / 66 % | – | 49 / 70 % | 10 / 32 % | 5 / 14 % | 1 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 13 / 35 % | 36 / 90 % | – | 16 / 41 % | 17 / 40 % | 20 / 41 % | 9 / 25 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 29 / 67 % | – | 15 / 41 % | 13 / 35 % | 11 / 26 % | 1 / 5 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 29 / 71 % | – | 0 / 0 % | 16 / 43 % | 14 / 35 % | 2 / 8 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 29 / 76 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 2 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 15 / 31 % | 28 / 94 % | – | 11 / 48 % | 14 / 35 % | 10 / 31 % | 6 / 20 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 19 / 70 % | – | 22 / 33 % | 7 / 22 % | 0 / 0 % | 2 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 21 / 44 % | 0 / 0 % | 0 / 3 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 51 % | 0 / 0 % | – | 0 / 0 % | 16 / 39 % | 8 / 18 % | 3 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 35 % | 14 / 34 % | 5 / 14 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 9 / 62 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 3 / 9 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 39 % | – | 0 / 0 % | 5 / 11 % | 6 / 11 % | 1 / 4 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 8 / 16 % | 1 / 5 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 2 / 32 % | – | 0 / 0 % | 8 / 21 % | 8 / 17 % | 1 / 5 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 13 % | 0 / 1 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 7 / 21 % | 6 / 14 % | 6 / 12 % | 2 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 6 / 38 % | – | 4 / 15 % | 7 / 20 % | 6 / 16 % | 2 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 0 / 0 % | 1 / 5 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 2 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 1 / 4 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 6 / 13 % | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 3 / 6 % | 1 / 3 % |
