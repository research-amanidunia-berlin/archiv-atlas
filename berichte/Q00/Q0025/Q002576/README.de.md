[English](README.md) · [Deutsch](README.de.md)

# General-Purpose AI Models in the AI Act – Questions & Answers

Bericht Q002576 · Quelle digital-strategy.ec.europa.eu · Datum – · [Original öffnen](http://digital-strategy.ec.europa.eu/en/faqs/general-purpose-ai-models-ai-act-questions-answers)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht erläutert die Pflichten des EU-KI-Gesetzes für Anbieter allgemein verwendbarer KI-Modelle, darunter Dokumentation, Urheberrecht und öffentliche Angaben zu Trainingsinhalten; für Modelle mit systemischem Risiko gelten zusätzliche Prüf-, Melde- und Sicherheitsanforderungen. Er beschreibt Ausnahmen, Entwicklungs- und Änderungsfälle sowie die Rolle des Verhaltenskodex, dessen Befolgung als Nachweis dienen kann, aber keine automatische Konformität begründet. Die Kommission weist darauf hin, dass ihre Antworten keine offizielle Position darstellen und nur der Gerichtshof das Gesetz verbindlich auslegen kann.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 61 / 77 % | 99 / 100 % | – | 91 / 95 % | 82 / 91 % | 92 / 96 % | 94 / 97 % | 47 / 68 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 76 / 87 % | 99 / 100 % | – | 86 / 92 % | 74 / 85 % | 91 / 95 % | 98 / 99 % | 62 / 81 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 56 / 77 % | 93 / 99 % | – | 76 / 87 % | 51 / 68 % | 76 / 88 % | 81 / 90 % | 43 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 56 / 73 % | 91 / 99 % | – | 76 / 88 % | 61 / 78 % | 76 / 88 % | 74 / 91 % | 37 / 59 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 64 / 80 % | 82 / 97 % | – | 85 / 92 % | 57 / 76 % | 88 / 94 % | 88 / 97 % | 27 / 52 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 27 / 52 % | 82 / 94 % | – | 54 / 76 % | 39 / 58 % | 54 / 75 % | 39 / 70 % | 16 / 35 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 29 / 55 % | 82 / 97 % | – | 57 / 77 % | 34 / 48 % | 48 / 67 % | 28 / 49 % | 27 / 53 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 30 / 54 % | 65 / 94 % | – | 68 / 83 % | 35 / 57 % | 81 / 89 % | 69 / 83 % | 16 / 45 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 38 / 65 % | 80 / 96 % | – | 62 / 80 % | 28 / 49 % | 69 / 84 % | 24 / 47 % | 58 / 75 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 16 / 43 % | 77 / 95 % | – | 24 / 50 % | 8 / 21 % | 16 / 46 % | 7 / 25 % | 28 / 57 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 56 / 74 % | 58 / 88 % | – | 74 / 86 % | 53 / 70 % | 73 / 85 % | 57 / 81 % | 21 / 50 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 11 / 42 % | 68 / 77 % | – | 47 / 69 % | 15 / 31 % | 30 / 46 % | 12 / 31 % | 26 / 50 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 49 / 72 % | 55 / 86 % | – | 68 / 84 % | 27 / 50 % | 52 / 82 % | 61 / 89 % | 22 / 46 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 51 % | 47 / 84 % | – | 60 / 83 % | 49 / 71 % | 67 / 85 % | 55 / 83 % | 15 / 33 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 41 / 59 % | 67 / 87 % | – | 63 / 81 % | 25 / 44 % | 62 / 78 % | 27 / 50 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 26 / 58 % | 0 / 0 % | – | 66 / 82 % | 42 / 64 % | 52 / 70 % | 62 / 82 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 20 / 48 % | 61 / 86 % | – | 31 / 54 % | 21 / 38 % | 34 / 53 % | 20 / 36 % | 11 / 31 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 23 / 44 % | 0 / 0 % | – | 58 / 78 % | 14 / 28 % | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 56 / 85 % | – | 16 / 38 % | 7 / 19 % | 14 / 31 % | 2 / 13 % | 17 / 39 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 29 % | 55 / 81 % | – | 14 / 40 % | 7 / 20 % | 14 / 41 % | 3 / 12 % | 20 / 44 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 30 / 51 % | 0 / 0 % | – | 51 / 77 % | 16 / 34 % | 52 / 74 % | 11 / 23 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 15 / 48 % | 51 / 85 % | – | 19 / 44 % | 27 / 53 % | 51 / 79 % | 25 / 58 % | 29 / 57 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 28 / 50 % | 51 / 78 % | – | 48 / 72 % | 14 / 31 % | 25 / 42 % | 10 / 21 % | 16 / 44 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 44 % | 0 / 0 % | – | 17 / 43 % | 11 / 27 % | 50 / 67 % | 15 / 34 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 50 / 79 % | – | 7 / 21 % | 0 / 0 % | 7 / 13 % | 1 / 5 % | 26 / 44 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 36 / 73 % | – | 34 / 58 % | 17 / 36 % | 41 / 59 % | 17 / 33 % | 14 / 43 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 40 / 86 % | – | 17 / 45 % | 7 / 23 % | 17 / 33 % | 2 / 14 % | 6 / 29 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 14 / 26 % | 37 / 65 % | – | 20 / 45 % | 9 / 23 % | 13 / 46 % | 3 / 20 % | 21 / 44 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 10 / 41 % | 26 / 82 % | – | 17 / 44 % | 8 / 25 % | 12 / 34 % | 2 / 12 % | 23 / 47 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 17 / 45 % | 0 / 0 % | – | 23 / 54 % | 6 / 17 % | 17 / 40 % | 3 / 12 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 11 / 32 % | 20 / 59 % | – | 18 / 44 % | 11 / 22 % | 13 / 34 % | 3 / 16 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 2 / 31 % | – | 14 / 44 % | 2 / 10 % | 7 / 26 % | 1 / 6 % | 14 / 32 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 8 / 19 % | 0 / 0 % | – | 14 / 34 % | 6 / 16 % | 8 / 26 % | 3 / 12 % | 8 / 26 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 14 / 33 % | 7 / 16 % | 13 / 28 % | 5 / 14 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 5 / 67 % | – | 8 / 18 % | 0 / 0 % | 13 / 33 % | 1 / 6 % | 12 / 39 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | – | 11 / 31 % | 0 / 0 % | 13 / 32 % | 1 / 6 % | 6 / 22 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 12 / 42 % | 4 / 47 % | – | 13 / 32 % | 5 / 12 % | 10 / 24 % | 1 / 8 % | 6 / 24 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 11 / 25 % | 0 / 0 % | 11 / 26 % | 1 / 6 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | – | 10 / 23 % | 0 / 0 % | 7 / 15 % | 0 / 2 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 9 / 48 % | – | 9 / 22 % | 4 / 13 % | 7 / 19 % | 0 / 3 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 4 / 17 % |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 3 % | 6 / 18 % |
