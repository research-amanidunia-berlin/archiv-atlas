[English](README.md) · [Deutsch](README.de.md)

# Redeploying Claude Fable 5

Bericht Q003023 · Quelle anthropic.com · Datum 2026-06-30 · [Original öffnen](https://www.anthropic.com/news/redeploying-fable-5)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Anthropic erklärt, die Exportkontrollen für Fable 5 und Mythos 5 seien aufgehoben; Fable 5 solle ab 1. Juli wieder weltweit verfügbar sein. Nach einem Bericht über eine Umgehung seiner Schutzmaßnahmen habe Anthropic einen neuen Klassifikator eingeführt, der die beschriebene Methode laut Unternehmen in über 99 Prozent der Fälle blockiere, aber auch mehr harmlose Anfragen treffen könne. Zudem schlägt Anthropic mit Partnern einen Bewertungsrahmen für Jailbreaks vor und kündigt engere Zusammenarbeit mit US-Behörden an.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 59 % | 99 / 100 % | 100 / 100 % | 71 / 85 % | 32 / 56 % | 68 / 81 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 30 / 56 % | 99 / 100 % | 98 / 99 % | 70 / 83 % | 56 / 72 % | 82 / 90 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 48 / 69 % | 47 / 86 % | 99 / 100 % | 67 / 83 % | 34 / 53 % | 68 / 82 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 49 / 66 % | 99 / 100 % | 98 / 99 % | 79 / 88 % | 50 / 65 % | 85 / 91 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 37 / 58 % | 97 / 100 % | 98 / 100 % | 64 / 83 % | 67 / 83 % | 79 / 89 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 50 / 65 % | 93 / 97 % | 97 / 99 % | 79 / 88 % | 51 / 68 % | 84 / 91 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 46 / 65 % | 92 / 97 % | 95 / 99 % | 22 / 40 % | 51 / 71 % | 88 / 93 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 50 / 69 % | 54 / 97 % | 95 / 98 % | 79 / 88 % | 26 / 45 % | 58 / 73 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 35 / 53 % | 95 / 99 % | 83 / 95 % | 62 / 80 % | 27 / 44 % | 68 / 82 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 53 / 70 % | 85 / 98 % | 95 / 98 % | 53 / 69 % | 79 / 88 % | 89 / 93 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 40 / 59 % | 65 / 92 % | 93 / 96 % | 78 / 87 % | 49 / 65 % | 80 / 86 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 38 / 58 % | 55 / 96 % | 91 / 97 % | 74 / 86 % | 32 / 53 % | 79 / 88 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 28 / 52 % | 90 / 99 % | 75 / 92 % | 69 / 84 % | 41 / 65 % | 58 / 74 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 21 / 50 % | 81 / 86 % | 34 / 61 % | 10 / 22 % | 36 / 58 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 43 / 96 % | 78 / 86 % | 49 / 73 % | 16 / 34 % | 30 / 53 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) Wann sind Chip- und Exportkontrollen eine Sicherheitsmaßnahme, und wann ein dauerhafter Vorteil? | 44 / 65 % | 34 / 87 % | 76 / 88 % | 77 / 87 % | 48 / 62 % | 76 / 83 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 73 / 93 % | 70 / 86 % | 14 / 36 % | 6 / 16 % | 13 / 29 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 53 / 93 % | 69 / 85 % | 40 / 67 % | 13 / 30 % | 37 / 63 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 27 / 50 % | 67 / 93 % | 59 / 78 % | 35 / 59 % | 18 / 33 % | 29 / 47 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 64 / 98 % | 61 / 75 % | 16 / 35 % | 7 / 17 % | 11 / 23 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 17 / 47 % | 56 / 74 % | 7 / 15 % | 1 / 4 % | 7 / 10 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 45 / 77 % | 49 / 72 % | 24 / 46 % | 13 / 34 % | 29 / 50 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 0 / 0 % | 0 / 0 % | 46 / 58 % | 31 / 57 % | 13 / 31 % | 34 / 50 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 46 / 97 % | 25 / 44 % | 31 / 59 % | 21 / 41 % | 31 / 57 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 41 / 97 % | 42 / 79 % | 39 / 63 % | 21 / 41 % | 46 / 61 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 27 / 78 % | 46 / 65 % | 21 / 44 % | 8 / 15 % | 17 / 32 % | – | – |
| [SF-W3](../../../../fragen/SF-W3/) Wie schützt man Finanzmärkte vor Folgen von KI, von vertraulichen Entscheidungen über Pausen bis zu Kursstürzen in Sekunden? | 0 / 0 % | 45 / 70 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 33 / 65 % | 44 / 59 % | 22 / 46 % | 10 / 22 % | 29 / 54 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 40 / 92 % | 35 / 54 % | 10 / 21 % | 0 / 0 % | 8 / 16 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 34 / 80 % | 39 / 58 % | 27 / 52 % | 7 / 17 % | 20 / 43 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 9 / 54 % | 38 / 52 % | 8 / 16 % | 2 / 6 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 23 / 55 % | 21 / 44 % | 28 / 49 % | 12 / 27 % | 30 / 46 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 11 / 55 % | 0 / 0 % | 25 / 54 % | 16 / 44 % | 27 / 51 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 26 / 78 % | 3 / 16 % | 11 / 26 % | 6 / 12 % | 10 / 20 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 41 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 18 / 37 % | 13 / 29 % | 8 / 20 % | 19 / 36 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 29 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 15 / 26 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 15 / 49 % | 0 / 0 % | 6 / 12 % | 3 / 7 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 3 / 48 % | 0 / 0 % | 9 / 22 % | 4 / 11 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 5 / 59 % | 0 / 0 % | 7 / 16 % | 4 / 8 % | 9 / 15 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
