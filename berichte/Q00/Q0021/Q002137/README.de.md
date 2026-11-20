[English](README.md) · [Deutsch](README.de.md)

# Strengthening our safety ecosystem with external testing

Bericht Q002137 · Quelle openai.com · Datum 2025-11-19 · [Original öffnen](https://openai.com/index/strengthening-safety-with-external-testing/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI berichtet, dass externe Organisationen seine Modelle durch unabhängige Tests, Methodenprüfungen und praktische Aufgaben für Fachleute bewerten; die Ergebnisse sollen Sicherheitsbewertungen und Einsatzentscheidungen ergänzen. Der Beitrag beschreibt Zugangs- und Veröffentlichungsregeln, räumt aber keine unabhängige Gesamtbewertung der Wirksamkeit dieser Zusammenarbeit ein.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 55 / 70 % | 99 / 100 % | – | 100 / 100 % | 76 / 88 % | 89 / 94 % | 85 / 93 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 44 / 66 % | 99 / 100 % | – | 100 / 100 % | 69 / 84 % | 74 / 85 % | 63 / 78 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 40 / 65 % | 95 / 97 % | – | 99 / 100 % | 45 / 63 % | 78 / 86 % | 76 / 87 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 39 / 66 % | 82 / 95 % | – | 90 / 99 % | 71 / 84 % | 83 / 90 % | 71 / 86 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 37 / 59 % | 69 / 97 % | – | 90 / 97 % | 57 / 79 % | 58 / 75 % | 23 / 48 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 65 / 92 % | – | 85 / 94 % | 12 / 31 % | 10 / 21 % | 3 / 10 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 55 / 73 % | 81 / 95 % | – | 76 / 84 % | 74 / 86 % | 81 / 88 % | 84 / 92 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 17 / 49 % | 82 / 95 % | – | 29 / 69 % | 51 / 74 % | 44 / 63 % | 13 / 30 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 30 / 53 % | 54 / 87 % | – | 76 / 90 % | 66 / 82 % | 80 / 87 % | 48 / 68 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 18 / 43 % | 80 / 97 % | – | 27 / 34 % | 30 / 51 % | 36 / 51 % | 10 / 26 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 26 / 47 % | 78 / 98 % | – | 54 / 79 % | 37 / 62 % | 34 / 58 % | 13 / 32 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 26 / 58 % | 73 / 96 % | – | 34 / 68 % | 23 / 48 % | 22 / 45 % | 4 / 14 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 29 / 53 % | 49 / 88 % | – | 73 / 92 % | 38 / 66 % | 47 / 73 % | 17 / 42 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 27 / 52 % | 43 / 94 % | – | 67 / 88 % | 61 / 81 % | 24 / 49 % | 15 / 36 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 21 / 47 % | 66 / 95 % | – | 62 / 78 % | 30 / 56 % | 18 / 39 % | 7 / 24 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 17 / 48 % | 48 / 95 % | – | 14 / 58 % | 34 / 63 % | 31 / 58 % | 9 / 24 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 15 / 43 % | 46 / 81 % | – | 23 / 45 % | 29 / 53 % | 33 / 49 % | 7 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 45 / 80 % | – | 17 / 47 % | 11 / 29 % | 9 / 27 % | 4 / 17 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 17 / 87 % | – | 43 / 64 % | 8 / 24 % | 7 / 17 % | 3 / 15 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 13 / 39 % | 39 / 74 % | – | 10 / 38 % | 17 / 37 % | 14 / 29 % | 4 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 39 / 59 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 11 / 32 % | 9 / 43 % | – | 38 / 73 % | 17 / 45 % | 13 / 39 % | 5 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 31 % | 33 / 81 % | – | 0 / 0 % | 10 / 27 % | 15 / 31 % | 4 / 14 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 12 / 32 % | 25 / 67 % | – | 12 / 27 % | 14 / 38 % | 26 / 55 % | 10 / 30 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 26 / 73 % | – | 1 / 13 % | 11 / 27 % | 7 / 18 % | 3 / 8 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 6 / 40 % | – | 0 / 0 % | 11 / 25 % | 25 / 43 % | 9 / 23 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 23 / 66 % | – | 14 / 32 % | 8 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 17 / 43 % | – | 22 / 41 % | 7 / 15 % | 6 / 11 % | 1 / 5 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 21 / 58 % | – | 0 / 0 % | 8 / 17 % | 10 / 19 % | 1 / 5 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 21 / 60 % | – | 0 / 0 % | 6 / 12 % | 6 / 10 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 26 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 26 % | 11 / 24 % | 4 / 14 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 9 / 46 % | – | 0 / 0 % | 7 / 17 % | 7 / 13 % | 1 / 6 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 8 / 17 % | 1 / 5 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 7 / 32 % | – | 2 / 11 % | 7 / 15 % | 7 / 14 % | 4 / 12 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 17 % | 2 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 5 / 10 % | 2 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | – | 1 / 6 % | 6 / 17 % | 5 / 12 % | 1 / 8 % |
