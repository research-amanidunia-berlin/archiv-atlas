[English](README.md) · [Deutsch](README.de.md)

# Sora 2 System Card

Bericht Q001012 · Quelle deploymentsafety.openai.com · Datum 2025-09-30 · [Original öffnen](https://deploymentsafety.openai.com/sora-2)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt Sora 2 als leistungsfähigeres Video- und Audiomodell und nennt Moderation, Einschränkungen bei Personenabbildungen, besonderen Jugendschutz und Herkunftshinweise als zentrale Schutzmaßnahmen. Die Tests berichten je nach Kategorie hohe, aber nicht vollständige Sicherheitswerte; laut Bericht können Verstöße die Schutzmaßnahmen weiterhin umgehen.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 38 / 58 % | 94 / 98 % | 52 / 70 % | 100 / 100 % | 64 / 82 % | 74 / 84 % | 54 / 71 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 43 / 58 % | 97 / 99 % | 64 / 80 % | 100 / 100 % | 76 / 87 % | 67 / 80 % | 32 / 54 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 60 / 73 % | 98 / 100 % | 97 / 98 % | 99 / 100 % | 82 / 89 % | 89 / 93 % | 81 / 89 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 87 / 97 % | 13 / 25 % | 98 / 99 % | 52 / 74 % | 45 / 66 % | 18 / 37 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 33 / 50 % | 97 / 99 % | 33 / 48 % | 92 / 96 % | 45 / 70 % | 68 / 80 % | 22 / 41 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 29 / 48 % | 84 / 98 % | 6 / 17 % | 97 / 98 % | 29 / 52 % | 27 / 48 % | 17 / 32 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 76 / 99 % | 12 / 24 % | 94 / 97 % | 52 / 75 % | 33 / 60 % | 19 / 42 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 83 / 99 % | 4 / 10 % | 88 / 97 % | 30 / 55 % | 14 / 32 % | 12 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 55 / 80 % | 0 / 0 % | 86 / 89 % | 35 / 58 % | 0 / 0 % | 11 / 19 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 29 / 44 % | 63 / 93 % | 13 / 28 % | 85 / 95 % | 41 / 64 % | 26 / 42 % | 8 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 29 / 43 % | 62 / 87 % | 13 / 23 % | 85 / 92 % | 16 / 34 % | 20 / 40 % | 11 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 17 / 72 % | 2 / 6 % | 83 / 90 % | 21 / 45 % | 8 / 15 % | 6 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 31 / 57 % | 6 / 11 % | 77 / 86 % | 28 / 53 % | 22 / 45 % | 8 / 19 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 30 / 51 % | 40 / 69 % | 16 / 28 % | 70 / 84 % | 31 / 55 % | 26 / 44 % | 10 / 26 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 38 / 75 % | 5 / 13 % | 65 / 79 % | 19 / 39 % | 13 / 28 % | 9 / 21 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 64 / 84 % | 7 / 19 % | 6 / 13 % | 2 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 53 / 88 % | 5 / 9 % | 60 / 81 % | 18 / 42 % | 14 / 29 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 19 / 44 % | 0 / 0 % | 60 / 80 % | 7 / 16 % | 0 / 0 % | 3 / 8 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 56 / 82 % | 0 / 0 % | 4 / 8 % | 7 / 15 % | 0 / 0 % | 3 / 8 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 52 / 78 % | 6 / 11 % | 28 / 56 % | 26 / 50 % | 19 / 35 % | 9 / 20 % |
| [SF-K1](../../../../fragen/SF-K1/) Wie stellt man sicher und weist nach, dass Entscheidungen über den Einsatz von Gewalt, vor allem über Atomwaffen, beim Menschen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 51 / 62 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 6 / 50 % | 8 / 15 % | 40 / 59 % | 20 / 45 % | 18 / 34 % | 10 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 12 / 29 % | 40 / 90 % | 2 / 7 % | 22 / 54 % | 16 / 36 % | 16 / 30 % | 9 / 23 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 34 / 54 % | 10 / 23 % | 7 / 14 % | 5 / 13 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 23 / 70 % | 0 / 2 % | 7 / 19 % | 9 / 25 % | 6 / 12 % | 4 / 12 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 2 / 7 % | 0 / 0 % | 19 / 44 % | 6 / 13 % | 5 / 14 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 17 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 42 % | 10 / 26 % | 8 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 21 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | 8 / 18 % | 6 / 13 % | 2 / 8 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 1 % | 10 / 28 % | 8 / 21 % | 11 / 23 % | 6 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 9 / 25 % | 9 / 18 % | 6 / 14 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 7 / 14 % | 3 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 9 / 56 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 6 / 11 % | 2 / 9 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 3 / 11 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 5 / 10 % | 1 / 5 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 7 / 53 % | 0 / 0 % | 0 / 0 % | 5 / 17 % | 5 / 12 % | 3 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 5 / 8 % | 1 / 3 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 5 / 12 % | 0 / 0 % | 1 / 6 % |
