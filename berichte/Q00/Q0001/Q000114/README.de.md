[English](README.md) · [Deutsch](README.de.md)

# Red-Teaming OpenAI's Internal Agent Monitoring Systems

Bericht Q000114 · Quelle metr.org · Datum 2026-10-22 · [Original öffnen](https://metr.org/blog/2026-10-22-red-teaming-openai-agent-monitoring/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der bereitgestellte Text ist ein Auszug: Er meldet mehrere Schwachstellen in OpenAIs damaligem internen Agenten-Monitoring, nennt aber keine konkreten Beispiele. METR und Redwood konnten spätere Änderungen und OpenAIs Angaben zu Reparaturen nicht überprüfen; ihre Empfehlungen betreffen unter anderem regelmäßige Überwachung, Protokollabgleich, Red-Team-Prüfungen und die Trennung von Agenten und Monitoren.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 50 / 68 % | 81 / 95 % | 99 / 100 % | 71 / 85 % | 54 / 76 % | 75 / 85 % | 40 / 67 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 37 / 59 % | 82 / 99 % | 99 / 100 % | 68 / 82 % | 50 / 68 % | 63 / 75 % | 32 / 60 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 57 / 75 % | 93 / 99 % | 97 / 99 % | 81 / 90 % | 83 / 91 % | 85 / 91 % | 85 / 94 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 51 / 72 % | 78 / 93 % | 95 / 99 % | 75 / 87 % | 28 / 54 % | 61 / 76 % | 69 / 87 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 50 / 71 % | 67 / 88 % | 95 / 97 % | 64 / 79 % | 62 / 78 % | 58 / 74 % | 46 / 73 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 60 / 78 % | 88 / 99 % | 93 / 97 % | 75 / 87 % | 67 / 82 % | 80 / 88 % | 48 / 77 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 22 / 41 % | 58 / 87 % | 84 / 91 % | 29 / 57 % | 9 / 23 % | 18 / 36 % | 2 / 10 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 42 / 62 % | 55 / 93 % | 81 / 92 % | 48 / 72 % | 35 / 58 % | 48 / 68 % | 7 / 28 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 18 / 40 % | 43 / 83 % | 74 / 90 % | 11 / 29 % | 8 / 19 % | 17 / 33 % | 3 / 13 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 38 / 88 % | 74 / 84 % | 55 / 76 % | 12 / 33 % | 30 / 54 % | 12 / 35 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 35 / 66 % | 71 / 81 % | 42 / 70 % | 17 / 38 % | 22 / 46 % | 13 / 28 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 35 / 55 % | 5 / 55 % | 0 / 0 % | 51 / 74 % | 33 / 57 % | 69 / 82 % | 7 / 24 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 27 / 52 % | 63 / 97 % | 29 / 53 % | 56 / 77 % | 28 / 55 % | 59 / 74 % | 29 / 55 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 62 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 40 / 92 % | 45 / 74 % | 19 / 45 % | 6 / 21 % | 13 / 29 % | 2 / 8 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 41 / 65 % | 19 / 43 % | 6 / 15 % | 18 / 32 % | 5 / 22 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 16 / 49 % | 37 / 75 % | 25 / 50 % | 12 / 34 % | 3 / 15 % | 13 / 30 % | 0 / 4 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 37 / 58 % | 7 / 13 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 23 / 53 % | 33 / 48 % | 10 / 25 % | 4 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 29 / 56 % | 16 / 45 % | 25 / 56 % | 0 / 0 % | 20 / 42 % | 3 / 16 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 29 / 54 % | 6 / 14 % | 1 / 6 % | 0 / 0 % | 0 / 2 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 25 / 61 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 5 / 12 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 31 % | 4 / 13 % | 19 / 39 % | 1 / 4 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 37 % | 1 / 5 % | 9 / 19 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 13 % | 13 / 25 % | 0 / 2 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 10 / 24 % | 13 / 33 % | 5 / 13 % | 11 / 21 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 0 / 0 % | 0 / 0 % | 1 / 13 % | 10 / 25 % | 1 / 5 % | 0 / 0 % | 0 / 3 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 31 % | 1 / 7 % | 0 / 0 % | 0 / 2 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 1 / 3 % | 7 / 16 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
