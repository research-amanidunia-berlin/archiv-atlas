[English](README.md) · [Deutsch](README.de.md)

# Addendum to GPT-4o System Card: Native image generation

Bericht Q001026 · Quelle deploymentsafety.openai.com · Datum 2025-03-25 · [Original öffnen](https://deploymentsafety.openai.com/4o-native-image-generation)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI beschreibt die native Bildgenerierung von GPT‑4o als vielseitiger und fotorealistischer als frühere Systeme und führt neue Schutzmaßnahmen sowie Tests zu mehreren Risikobereichen an. Die berichteten Evaluationen zeigen Fortschritte bei Sicherheit und Vielfalt, lassen aber Zielkonflikte, demografische Verzerrungen und mögliche Fehlklassifikationen erkennen; OpenAI stellt die Ergebnisse als vorläufige Momentaufnahme dar.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 38 / 58 % | 99 / 100 % | 41 / 66 % | 100 / 100 % | 67 / 83 % | 78 / 87 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 46 / 61 % | 97 / 99 % | 62 / 77 % | 100 / 100 % | 81 / 89 % | 75 / 85 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 92 / 97 % | 8 / 20 % | 98 / 99 % | 63 / 81 % | 63 / 78 % |
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 47 / 62 % | 98 / 100 % | 87 / 90 % | 89 / 93 % | 75 / 85 % | 76 / 84 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 28 / 46 % | 97 / 99 % | 5 / 14 % | 97 / 98 % | 36 / 60 % | 30 / 48 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 35 / 54 % | 96 / 99 % | 10 / 23 % | 94 / 97 % | 64 / 82 % | 50 / 72 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 31 / 46 % | 41 / 81 % | 10 / 23 % | 89 / 93 % | 51 / 72 % | 31 / 46 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 86 / 97 % | 2 / 6 % | 53 / 85 % | 26 / 53 % | 16 / 34 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 24 / 58 % | 1 / 4 % | 85 / 91 % | 24 / 47 % | 7 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 82 / 95 % | 13 / 17 % | 46 / 62 % | 37 / 61 % | 39 / 49 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 49 / 78 % | 11 / 24 % | 79 / 87 % | 36 / 58 % | 21 / 37 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 34 / 65 % | 2 / 7 % | 70 / 82 % | 31 / 52 % | 15 / 26 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 23 / 38 % | 57 / 88 % | 7 / 14 % | 69 / 83 % | 22 / 45 % | 15 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 44 / 60 % | 0 / 0 % | 60 / 66 % | 25 / 49 % | 12 / 20 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 57 / 77 % | 8 / 20 % | 6 / 12 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 53 / 71 % | 0 / 0 % | 31 / 53 % | 14 / 32 % | 16 / 26 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 21 / 72 % | 4 / 9 % | 51 / 66 % | 23 / 47 % | 26 / 44 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 47 / 80 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 8 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 46 / 73 % | 0 / 0 % | 47 / 64 % | 9 / 18 % | 7 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 43 / 78 % | 0 / 0 % | 25 / 48 % | 23 / 46 % | 14 / 25 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 0 / 0 % | 37 / 89 % | 0 / 0 % | 12 / 22 % | 13 / 32 % | 7 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 33 / 85 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 28 / 72 % | 1 / 5 % | 30 / 49 % | 14 / 29 % | 14 / 22 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 24 / 42 % | 21 / 43 % | 14 / 29 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 0 / 0 % | 15 / 51 % | 2 / 6 % | 7 / 20 % | 21 / 42 % | 23 / 37 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 22 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 12 / 24 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 22 / 92 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 5 / 10 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 20 / 44 % | 8 / 16 % |
| [SF-F3](../../../../fragen/SF-F3/) Welche Regeln gelten für gefährliche Fähigkeiten jenseits von Cyber, etwa in Biologie, Chemie, bei radioaktiven Stoffen oder in der Nukleartechnik? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 29 % | 11 / 18 % |
| [SF-H4](../../../../fragen/SF-H4/) Was geschieht mit Modellen und Sicherheitspflichten, wenn ein Labor verkauft, aufgelöst oder ein Modell stillgelegt wird? | 0 / 0 % | 13 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 23 % | 7 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 9 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) Wie können Mitarbeitende Sicherheitsbedenken melden, ohne alles zu riskieren? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 7 / 14 % | 9 / 18 % |
| [SF-M1](../../../../fragen/SF-M1/) Ab wann ist ein KI-Vorfall so ernst, dass Staaten ihn einander melden müssen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 14 % | 7 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % |
