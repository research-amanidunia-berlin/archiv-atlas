[English](README.md) · [Deutsch](README.de.md)

# Our approach to EU text provenance rules

Bericht Q007906 · Quelle openai.com · Datum 2026-10-05 · [Original öffnen](https://openai.com/index/eu-text-provenance/)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

OpenAI kündigt Text-Wasserzeichen für ausgewählte API-Modelle und geeignete ChatGPT- und Codex-Ausgaben in der EU an; den Detektor sollen zunächst nur zugelassene Forschende und Fachorganisationen nutzen können. Laut den vom Unternehmen berichteten Tests hängt die Erkennung stark von Textlänge und Bearbeitung ab, und ein Treffer sagt weder etwas Sicheres über menschlichen Beitrag, Urheberschaft oder Richtigkeit aus noch beweist ein fehlender Treffer menschliche Autorschaft.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-I1](../../../../fragen/SF-I1/) Wie erkennt man KI-erzeugte Inhalte und KI-erzeugte Einflussnahme, ohne die Meinungsfreiheit zu beschneiden? | 69 / 83 % | 99 / 100 % | – | 100 / 100 % | 88 / 93 % | 92 / 94 % | 91 / 94 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 33 / 50 % | 48 / 89 % | – | 95 / 97 % | 29 / 49 % | 7 / 15 % | 8 / 20 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 92 / 97 % | – | 95 / 97 % | 27 / 50 % | 20 / 40 % | 7 / 23 % |
| [SF-O2](../../../../fragen/SF-O2/) Was sollten Regierungen, Labore und Prüfer über ihre Gespräche, Zusagen, Prüfungen und Eingriffe offenlegen? | 0 / 0 % | 76 / 94 % | – | 95 / 97 % | 36 / 58 % | 30 / 52 % | 12 / 29 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 29 / 45 % | 92 / 99 % | – | 94 / 97 % | 31 / 59 % | 30 / 55 % | 19 / 42 % |
| [SF-E2](../../../../fragen/SF-E2/) In welchem Rahmen sollen Staaten KI regeln, und wo liegt eine gemeinsame Untergrenze? | 23 / 42 % | 0 / 0 % | – | 91 / 96 % | 40 / 63 % | 15 / 38 % | 6 / 17 % |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 88 / 96 % | – | 72 / 86 % | 17 / 38 % | 9 / 17 % | 8 / 20 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 85 / 98 % | – | 36 / 59 % | 0 / 0 % | 0 / 0 % | 2 / 8 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 26 / 59 % | – | 82 / 86 % | 8 / 16 % | 6 / 11 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Unter welchen Bedingungen lassen Staaten und Labore sich gegenseitig prüfen: mit welchem Zugang, welchen Daten und welchen öffentlichen Ergebnissen? | 15 / 44 % | 80 / 89 % | – | 58 / 72 % | 30 / 53 % | 10 / 22 % | 13 / 30 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 17 / 34 % | 62 / 85 % | – | 79 / 88 % | 15 / 36 % | 15 / 34 % | 5 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Welcher Text gilt, und wie beweist man, dass ein Dokument nicht verändert wurde? | 0 / 0 % | 45 / 82 % | – | 75 / 85 % | 40 / 63 % | 35 / 47 % | 52 / 67 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 31 / 46 % | 43 / 82 % | – | 73 / 84 % | 34 / 58 % | 36 / 47 % | 21 / 35 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 33 / 60 % | – | 65 / 80 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 0 / 0 % | 43 / 72 % | – | 63 / 77 % | 30 / 51 % | 15 / 23 % | 6 / 12 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 18 / 52 % | – | 60 / 77 % | 11 / 25 % | 6 / 13 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 45 / 85 % | – | 58 / 72 % | 11 / 28 % | 8 / 16 % | 3 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | – | 57 / 70 % | 16 / 33 % | 9 / 18 % | 4 / 13 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | – | 50 / 63 % | 0 / 0 % | 2 / 4 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) Welche echte Stimme bekommen weitere Staaten, kleine Labore, Hochschulen und Zivilgesellschaft bei den Regeln für KI? | 18 / 40 % | 45 / 81 % | – | 43 / 61 % | 28 / 51 % | 15 / 32 % | 4 / 14 % |
| [SF-M5](../../../../fragen/SF-M5/) Was muss vor und nach einem Vorfall geschehen, damit Verantwortliche einstehen, man daraus lernt, Beweise bleiben und Betroffene auch über Grenzen hinweg zu ihrem Recht kommen? | 0 / 0 % | 20 / 61 % | – | 29 / 55 % | 11 / 28 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Welche Stellen sind in einem Staat für KI-Sicherheit und Prüfungen zuständig, und was davon gibt es schon? | 0 / 0 % | 28 / 63 % | – | 1 / 6 % | 8 / 18 % | 7 / 16 % | 3 / 11 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 25 % | 6 / 12 % | 2 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) Woran erkennen andere, dass ein Labor wirklich bremst? | 10 / 18 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 7 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 25 % | 6 / 14 % | 4 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) Wie überprüft man, ob Zusagen zwischen Staaten eingehalten werden, auch über Jahre und Regierungswechsel hinweg? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 19 % | 0 / 0 % | 1 / 6 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 5 / 10 % | 0 / 3 % |
| [SF-W2](../../../../fragen/SF-W2/) Wie wirken sich Wettbewerbsrecht und öffentliche Beschaffung auf die KI-Sicherheit aus? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
