[English](README.md) · [Deutsch](README.de.md)

# Path to Astra: critical capabilities and frontier safeguards

Bericht Q007551 · Quelle openai.com · Datum 2026-09-01 · [Original öffnen](https://openai.com/index/path-to-astra/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI zufolge erreicht Astra nach Benchmarks und fachgeleiteten Tests die kritische Schwelle für Cybersicherheitsfähigkeiten: Es habe unter anderem bislang unbekannte Schwachstellen gefunden und zu Exploit-Ketten verbunden. Das Unternehmen beschreibt verstärkte Schutzmaßnahmen und einen zunächst begrenzten Zugang, räumt aber mögliche Fehlalarme und Unterbrechungen legitimer Arbeit ein; die Leistungsangaben stammen aus OpenAIs eigenen Prüfungen und sind teils ausdrücklich an Daybreak-Blue-Zugang gebunden.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 63 / 76 % | 100 / 100 % | – | 99 / 100 % | 14 / 36 % | 85 / 90 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 60 / 76 % | 100 / 100 % | – | 100 / 100 % | 88 / 93 % | 86 / 92 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 58 / 73 % | 100 / 100 % | – | 100 / 100 % | 90 / 94 % | 87 / 92 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 62 / 78 % | 93 / 98 % | – | 100 / 100 % | 87 / 93 % | 86 / 91 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 27 / 47 % | 100 / 100 % | – | 99 / 100 % | 45 / 68 % | 33 / 57 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 30 / 51 % | 86 / 99 % | – | 99 / 100 % | 81 / 90 % | 83 / 89 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 44 / 61 % | 35 / 81 % | – | 99 / 100 % | 81 / 90 % | 37 / 54 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 41 / 64 % | 99 / 100 % | – | 99 / 100 % | 72 / 86 % | 86 / 92 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 51 / 69 % | 97 / 99 % | – | 99 / 100 % | 87 / 92 % | 93 / 96 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 61 / 78 % | 98 / 100 % | – | 85 / 95 % | 88 / 93 % | 93 / 96 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 52 / 69 % | 91 / 97 % | – | 98 / 99 % | 88 / 93 % | 92 / 95 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 45 / 62 % | 64 / 94 % | – | 93 / 98 % | 80 / 89 % | 69 / 80 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 20 / 47 % | 91 / 100 % | – | 48 / 67 % | 18 / 43 % | 38 / 55 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 58 / 84 % | – | 85 / 91 % | 10 / 27 % | 7 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 47 / 89 % | – | 75 / 86 % | 36 / 59 % | 18 / 34 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 72 / 90 % | – | 64 / 83 % | 12 / 32 % | 9 / 20 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | – | 62 / 82 % | 12 / 34 % | 6 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 45 / 90 % | – | 47 / 65 % | 56 / 76 % | 29 / 50 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 52 / 86 % | – | 0 / 0 % | 8 / 17 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 13 / 71 % | – | 50 / 60 % | 8 / 21 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 48 / 69 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | – | 43 / 67 % | 10 / 29 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 39 / 79 % | – | 34 / 59 % | 26 / 50 % | 25 / 43 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 25 / 59 % | – | 38 / 63 % | 31 / 57 % | 27 / 49 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 30 / 47 % | 21 / 62 % | – | 37 / 63 % | 34 / 63 % | 31 / 52 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 35 / 97 % | – | 7 / 44 % | 17 / 37 % | 11 / 25 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 17 / 47 % | 7 / 41 % | – | 7 / 26 % | 20 / 45 % | 29 / 42 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 13 / 38 % | 0 / 0 % | – | 26 / 45 % | 25 / 49 % | 12 / 26 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 9 / 51 % | – | 22 / 42 % | 15 / 39 % | 20 / 40 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 22 / 52 % | – | 4 / 11 % | 10 / 25 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | – | 7 / 25 % | 8 / 19 % | 12 / 24 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 10 / 40 % | – | 1 / 16 % | 8 / 17 % | 7 / 13 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | – | 3 / 19 % | 10 / 30 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 16 % | 5 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 6 / 54 % | – | 0 / 0 % | 0 / 0 % | 4 / 7 % |
