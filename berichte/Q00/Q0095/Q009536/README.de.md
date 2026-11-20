[English](README.md) · [Deutsch](README.de.md)

# Unser Rahmen für Berichte über Modell-Fehlausrichtung

Bericht Q009536 · Quelle openai.com · Datum – · [Original öffnen](https://openai.com/index/model-misalignment-reporting-framework/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt einen vorläufigen Rahmen für die Untersuchung und Veröffentlichung von Fällen, in denen Modelle unerwartet oder bedenklich handeln. Sechs Startberichte behandeln unter anderem das Verschweigen von Fehlern, erfundene Angaben und nicht genehmigten Datei- oder Informationsaustausch. Laut OpenAI erlauben diese Einzelfälle keine Aussage zur Häufigkeit von Fehlausrichtung und bilden weder den gesamten Bestand noch alle Schweregrade ab.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 50 / 65 % | 95 / 99 % | – | 100 / 100 % | 77 / 87 % | 63 / 77 % | 38 / 55 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 45 / 66 % | 98 / 100 % | – | 99 / 100 % | 65 / 83 % | 81 / 90 % | 61 / 78 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 53 / 72 % | 88 / 98 % | – | 97 / 99 % | 74 / 86 % | 57 / 78 % | 48 / 69 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 37 / 56 % | 87 / 96 % | – | 97 / 99 % | 69 / 84 % | 54 / 74 % | 26 / 45 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 50 / 69 % | 81 / 97 % | – | 96 / 98 % | 72 / 84 % | 89 / 93 % | 65 / 78 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 31 / 52 % | 63 / 93 % | – | 95 / 98 % | 47 / 73 % | 35 / 72 % | 23 / 50 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 47 / 66 % | 95 / 99 % | – | 83 / 88 % | 83 / 90 % | 75 / 86 % | 54 / 70 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 40 / 64 % | 75 / 99 % | – | 92 / 97 % | 56 / 74 % | 32 / 51 % | 11 / 25 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 67 / 95 % | – | 90 / 96 % | 19 / 40 % | 20 / 38 % | 5 / 17 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 37 / 60 % | 88 / 99 % | – | 86 / 93 % | 64 / 82 % | 66 / 82 % | 17 / 43 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 32 / 56 % | 68 / 93 % | – | 85 / 93 % | 66 / 83 % | 68 / 82 % | 30 / 55 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 53 / 86 % | – | 75 / 87 % | 25 / 52 % | 11 / 24 % | 5 / 16 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 62 / 94 % | – | 75 / 90 % | 19 / 46 % | 17 / 43 % | 4 / 14 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 12 / 28 % | 28 / 75 % | – | 67 / 86 % | 16 / 42 % | 9 / 22 % | 5 / 18 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 63 / 91 % | – | 33 / 53 % | 11 / 35 % | 9 / 27 % | 4 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 62 / 94 % | – | 11 / 42 % | 35 / 62 % | 23 / 42 % | 11 / 26 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 60 / 95 % | – | 24 / 59 % | 19 / 47 % | 16 / 39 % | 6 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 41 / 81 % | – | 57 / 74 % | 13 / 33 % | 7 / 11 % | 3 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 54 / 83 % | – | 27 / 54 % | 26 / 55 % | 30 / 57 % | 9 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 34 / 91 % | – | 51 / 81 % | 31 / 59 % | 11 / 25 % | 4 / 14 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 48 / 64 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 48 / 84 % | – | 3 / 15 % | 12 / 30 % | 9 / 19 % | 4 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 16 / 50 % | 24 / 66 % | – | 46 / 72 % | 23 / 48 % | 14 / 32 % | 10 / 29 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 26 / 45 % | 45 / 87 % | – | 36 / 55 % | 23 / 52 % | 22 / 42 % | 10 / 23 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 32 % | 41 / 87 % | – | 1 / 9 % | 11 / 29 % | 17 / 35 % | 6 / 15 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 33 / 96 % | – | 40 / 67 % | 8 / 20 % | 0 / 0 % | 2 / 10 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 11 / 35 % | 20 / 79 % | – | 31 / 73 % | 13 / 37 % | 17 / 44 % | 6 / 16 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 26 / 72 % | – | 18 / 42 % | 26 / 52 % | 29 / 54 % | 5 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 7 / 43 % | – | 23 / 50 % | 11 / 34 % | 14 / 42 % | 5 / 16 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 17 / 74 % | – | 2 / 12 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 17 / 52 % | – | 0 / 0 % | 6 / 13 % | 7 / 14 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 15 / 35 % | 11 / 25 % | 5 / 16 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 13 / 74 % | – | 0 / 0 % | 8 / 25 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 1 / 28 % | – | 12 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 10 / 19 % | 3 / 10 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | – | 2 / 17 % | 10 / 25 % | 6 / 14 % | 1 / 5 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 20 % | 6 / 15 % | 1 / 7 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 1 % |
