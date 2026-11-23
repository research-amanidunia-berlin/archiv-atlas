[English](README.md) · [Deutsch](README.de.md)

# Does Codex Train on Your Code? OpenAI Answered That Four Different Ways in Three Days.

Bericht Q011003 · Quelle medium.com · Datum 2026-09-15 · [Original öffnen](https://medium.com/ai-advances/does-codex-train-on-your-code-openai-answered-that-four-different-ways-in-three-days-3e32e3e6a002)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel kritisiert, dass OpenAI auf die Frage, ob Codex-Sitzungen ins Training einfließen, zunächst mit Aussagen über Datenzugriff und Suche geantwortet habe; später habe das Unternehmen einen Beitrag anonymisierter Nutzungsdaten nicht ausschließen können. Die Erklärung, Buckmasters spätere Prompts seien nach Trainingsbeginn eingegangen, kläre laut Autor weder frühere Sitzungen noch die fehlende unabhängige Prüfbarkeit. Er warnt außerdem, dass Codex-Vollumgebungen eine eigene Trainingseinstellung haben, die von der allgemeinen ChatGPT-Abwahl unberührt bleibe.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 42 / 60 % | 64 / 91 % | 100 / 100 % | 33 / 60 % | 15 / 31 % | 23 / 43 % | 11 / 28 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 39 / 63 % | 99 / 100 % | 98 / 100 % | 85 / 91 % | 81 / 90 % | 88 / 93 % | 98 / 99 % | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 70 / 93 % | 99 / 100 % | 26 / 50 % | 11 / 21 % | 17 / 31 % | 2 / 6 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 44 % | 99 / 100 % | 99 / 100 % | 32 / 60 % | 10 / 30 % | 39 / 57 % | 14 / 41 % | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 94 / 97 % | 24 / 49 % | 7 / 15 % | 14 / 28 % | 6 / 19 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 10 / 49 % | 89 / 93 % | 10 / 20 % | 1 / 6 % | 9 / 20 % | 0 / 2 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 86 / 92 % | 25 / 50 % | 0 / 0 % | 17 / 32 % | 5 / 14 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 21 / 41 % | 86 / 98 % | 74 / 83 % | 13 / 33 % | 5 / 15 % | 10 / 20 % | 1 / 7 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 17 / 56 % | 85 / 90 % | 12 / 26 % | 10 / 20 % | 15 / 28 % | 1 / 4 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 24 / 52 % | 44 / 84 % | 84 / 90 % | 26 / 50 % | 6 / 17 % | 24 / 46 % | 2 / 9 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 27 / 84 % | 82 / 90 % | 12 / 31 % | 0 / 0 % | 20 / 34 % | 1 / 4 % | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 33 / 57 % | 71 / 95 % | 74 / 86 % | 73 / 85 % | 68 / 81 % | 78 / 86 % | 72 / 83 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 33 / 55 % | 52 / 90 % | 75 / 84 % | 34 / 65 % | 61 / 77 % | 53 / 71 % | 23 / 49 % | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 31 / 53 % | 67 / 95 % | 74 / 81 % | 44 / 69 % | 38 / 54 % | 40 / 58 % | 22 / 43 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 34 / 59 % | 16 / 55 % | 73 / 85 % | 64 / 80 % | 40 / 56 % | 74 / 84 % | 56 / 78 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 66 / 82 % | 7 / 18 % | 3 / 11 % | 5 / 12 % | 1 / 5 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 27 / 52 % | 59 / 94 % | 63 / 75 % | 24 / 49 % | 8 / 20 % | 32 / 54 % | 1 / 7 % | – |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 0 / 0 % | 2 / 32 % | 59 / 78 % | 0 / 0 % | 0 / 0 % | 18 / 33 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 21 / 50 % | 45 / 72 % | 48 / 61 % | 36 / 61 % | 30 / 50 % | 22 / 36 % | 19 / 41 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 21 / 46 % | 46 / 79 % | 36 / 55 % | 26 / 49 % | 7 / 17 % | 20 / 37 % | 5 / 17 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 41 / 62 % | 10 / 23 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 37 / 61 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 18 / 72 % | 30 / 52 % | 9 / 23 % | 4 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 25 / 58 % | 27 / 46 % | 14 / 33 % | 6 / 17 % | 8 / 17 % | 1 / 4 % | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 13 / 35 % | 0 / 0 % | 0 / 0 % | 14 / 35 % | 17 / 27 % | 22 / 37 % | 1 / 4 % | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 45 % | 10 / 19 % | 14 / 26 % | 2 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 16 / 31 % | 12 / 27 % | 0 / 0 % | 17 / 32 % | 1 / 4 % | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 28 % | 0 / 0 % | 15 / 25 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 27 % | 5 / 11 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 25 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 4 / 38 % | 0 / 0 % | 11 / 29 % | 8 / 19 % | 10 / 20 % | 2 / 8 % | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 18 % | 5 / 11 % | 10 / 23 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 7 / 27 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 4 / 10 % | 10 / 21 % | 1 / 4 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % | 8 / 15 % | 1 / 4 % | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 16 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
