[English](README.md) · [Deutsch](README.de.md)

# How an assessor could investigate alignment of unreleased AI models

Bericht Q000102 · Quelle metr.org · Datum 2026-10-14 · [Original öffnen](https://metr.org/blog/2026-10-14-alignment-assessment-proposal/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

METR schlägt eine unabhängige Prüfung vor, die interne Fälle schwerer Fehlhandlungen leistungsfähiger KI-Agenten erfasst und mit Simulationen untersucht, ob diese Fälle mögliche Risiken unterschätzen. Der Bericht betont Grenzen wie lückenhafte Protokolle, mögliche Täuschung oder Erkennung von Tests und schätzt für eine gründliche zweimonatige Prüfung API-Kosten von über 10 Millionen US-Dollar; er präsentiert ein Prüfkonzept, keine abgeschlossene Gesamtbewertung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 56 / 72 % | 93 / 99 % | 89 / 96 % | 92 / 98 % | 78 / 90 % | 79 / 90 % | 87 / 93 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 53 / 72 % | 53 / 90 % | 86 / 94 % | 92 / 97 % | 88 / 94 % | 84 / 92 % | 91 / 94 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 45 / 68 % | 77 / 99 % | 77 / 91 % | 73 / 98 % | 81 / 91 % | 87 / 94 % | 83 / 90 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 55 / 74 % | 57 / 90 % | 69 / 90 % | 81 / 89 % | 64 / 80 % | 72 / 85 % | 66 / 78 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 40 / 64 % | 49 / 98 % | 35 / 70 % | 73 / 89 % | 45 / 73 % | 36 / 66 % | 60 / 80 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 31 / 53 % | 58 / 94 % | 19 / 35 % | 72 / 83 % | 59 / 80 % | 19 / 38 % | 45 / 66 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 61 / 96 % | 26 / 36 % | 69 / 85 % | 46 / 71 % | 24 / 44 % | 57 / 72 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 43 / 65 % | 58 / 99 % | 55 / 84 % | 65 / 83 % | 43 / 72 % | 42 / 67 % | 52 / 71 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 25 / 56 % | 65 / 92 % | 24 / 59 % | 46 / 77 % | 41 / 66 % | 10 / 30 % | 32 / 55 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 37 / 59 % | 42 / 75 % | 34 / 71 % | 55 / 80 % | 59 / 80 % | 19 / 44 % | 51 / 70 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 33 / 56 % | 59 / 83 % | 16 / 42 % | 42 / 71 % | 48 / 74 % | 24 / 49 % | 38 / 61 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 5 / 43 % | 6 / 23 % | 53 / 76 % | 34 / 63 % | 12 / 32 % | 13 / 26 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 22 / 46 % | 51 / 86 % | 6 / 24 % | 48 / 67 % | 15 / 42 % | 9 / 24 % | 20 / 42 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 23 / 53 % | 24 / 83 % | 14 / 48 % | 46 / 82 % | 6 / 19 % | 15 / 41 % | 46 / 70 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 17 / 45 % | 0 / 0 % | 6 / 18 % | 0 / 0 % | 14 / 40 % | 7 / 16 % | 33 / 52 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 44 % | 32 / 67 % | 0 / 4 % | 9 / 28 % | 10 / 36 % | 2 / 11 % | 12 / 24 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 30 / 65 % | 0 / 3 % | 14 / 40 % | 5 / 16 % | 2 / 8 % | 6 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 18 / 50 % | 0 / 0 % | 29 / 52 % | 8 / 24 % | 3 / 8 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 26 / 46 % | 25 / 68 % | 4 / 17 % | 23 / 47 % | 24 / 56 % | 8 / 23 % | 19 / 42 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 14 / 45 % | 25 / 90 % | 5 / 25 % | 6 / 30 % | 23 / 53 % | 7 / 20 % | 15 / 30 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 22 / 53 % | 1 / 6 % | 0 / 0 % | 11 / 31 % | 7 / 18 % | 12 / 25 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 21 / 63 % | 0 / 2 % | 1 / 8 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 19 / 47 % | 0 / 0 % | 1 / 8 % | 0 / 0 % | 9 / 31 % | 3 / 12 % | 18 / 35 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 9 / 39 % | 19 / 75 % | 1 / 7 % | 1 / 7 % | 11 / 31 % | 6 / 17 % | 14 / 31 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 17 / 40 % | 0 / 0 % | 1 / 9 % | 14 / 39 % | 6 / 20 % | 3 / 12 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 37 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 12 / 54 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 2 / 10 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 2 / 35 % | 0 / 2 % | 2 / 13 % | 8 / 24 % | 4 / 16 % | 11 / 23 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 11 / 43 % | 1 / 8 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 10 / 27 % | 1 / 5 % | 7 / 15 % |
| [SF-H6](../../../../fragen/SF-H6/) Welche Belege klären Vorwürfe von Spionage und Datenabfluss zwischen Staaten? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 9 / 15 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 19 % | 6 / 18 % | 1 / 3 % | 9 / 18 % |
| [SF-F5](../../../../fragen/SF-F5/) Wie gehen Staaten gemeinsam gegen KI-gestützte Cyberangriffe vor und verhindern Eskalation zwischen autonomen Systemen, ohne die Verteidigung zu behindern? | 9 / 24 % | 0 / 0 % | 0 / 3 % | 1 / 19 % | 9 / 26 % | 4 / 12 % | 5 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 3 / 55 % | 1 / 6 % | 2 / 17 % | 9 / 33 % | 5 / 17 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 8 / 15 % |
| [SF-M2](../../../../fragen/SF-M2/) Wie muss ein Meldekanal zwischen Staaten gebaut sein, damit er verlässlich arbeitet, auch in einer Krise? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) Wie weit gelten KI-Abkommen für Verbündete und Geheimdienste, und wie verhalten sie sich zu bestehenden Rüstungskontrollverträgen und -regimen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 4 / 61 % | 0 / 0 % | 0 / 0 % | 4 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 1 / 6 % | 0 / 0 % |
