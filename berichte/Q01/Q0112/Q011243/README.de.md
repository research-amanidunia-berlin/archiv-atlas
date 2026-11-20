[English](README.md) · [Deutsch](README.de.md)

# I Stopped “Prompting” AI to Write Code. I Built an Agentic Coding System Instead.

Bericht Q011243 · Quelle medium.com · Datum 2026-07-18 · [Original öffnen](https://medium.com/coding-nexus/i-stopped-prompting-ai-to-write-code-i-built-an-agentic-coding-system-instead-0e59c0d1664b)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht empfiehlt, Coding-Agenten mit Projektdokumentation, festen Abläufen, Tests, unabhängigen Reviews, Automatisierung und Feedbackschleifen in eine strukturierte Arbeitsumgebung einzubetten. Der Autor behauptet, dies mache sie verlässlicher und teamähnlicher, belegt die Vorteile im Text aber nicht mit Messungen oder Fallstudien.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 41 % | 63 / 91 % | 3 / 14 % | 98 / 99 % | 33 / 58 % | 9 / 23 % | 19 / 41 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 31 / 51 % | 52 / 95 % | 7 / 35 % | 93 / 98 % | 31 / 56 % | 11 / 34 % | 19 / 41 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 38 / 82 % | 0 / 0 % | 85 / 94 % | 7 / 17 % | 0 / 0 % | 6 / 13 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 6 / 36 % | 0 / 0 % | 76 / 85 % | 5 / 13 % | 0 / 0 % | 5 / 8 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 18 / 37 % | 72 / 95 % | 1 / 4 % | 29 / 46 % | 10 / 30 % | 5 / 14 % | 10 / 20 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 18 / 33 % | 59 / 86 % | 0 / 0 % | 56 / 63 % | 6 / 18 % | 6 / 15 % | 9 / 19 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 54 / 91 % | 0 / 0 % | 47 / 78 % | 8 / 20 % | 2 / 7 % | 6 / 12 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 18 / 42 % | 0 / 0 % | 54 / 70 % | 4 / 9 % | 1 / 4 % | 3 / 9 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 15 / 37 % | 7 / 49 % | 1 / 4 % | 2 / 12 % | 11 / 27 % | 6 / 23 % | 12 / 29 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 12 / 31 % | 3 / 43 % | 0 / 2 % | 14 / 31 % | 8 / 26 % | 3 / 14 % | 6 / 16 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 10 / 20 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 1 / 23 % | 0 / 0 % | 0 / 0 % | 8 / 25 % | 0 / 0 % | 5 / 13 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) Wie bleiben Prüfer, die in einem Labor arbeiten, wirklich unabhängig? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 2 % | 4 / 7 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 7 % | 5 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 2 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % |
