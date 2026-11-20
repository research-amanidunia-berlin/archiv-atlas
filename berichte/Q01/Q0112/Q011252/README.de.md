[English](README.md) · [Deutsch](README.de.md)

# Claude’s Multi-Agent System: Why It’s Much Cheaper Than Running Opus for Everything

Bericht Q011252 · Quelle medium.com · Datum 2026-07-09 · [Original öffnen](https://medium.com/coding-nexus/claudes-multi-agent-system-why-it-s-much-cheaper-than-running-opus-for-everything-c1adf440b6f1)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Artikel beschreibt ein Advisor- und ein Orchestrator-Muster: Ein starkes Modell berät bei schwierigen Entscheidungen oder koordiniert günstigere, spezialisierte Agenten für die Ausführung. Laut den von Anthropic angeführten Benchmarks erreichen die Ansätze nahezu die Leistung des starken Einzelmodells bei deutlich geringeren Kosten; Testbedingungen und Übertragbarkeit werden im Text nicht näher erläutert.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 43 % | 57 / 93 % | 2 / 11 % | 100 / 100 % | 19 / 43 % | 11 / 25 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 28 / 51 % | 64 / 94 % | 34 / 62 % | 94 / 98 % | 49 / 70 % | 21 / 41 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 10 / 40 % | 12 / 86 % | 1 / 9 % | 45 / 62 % | 16 / 43 % | 6 / 19 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 13 / 40 % | 0 / 0 % | 44 / 65 % | 6 / 15 % | 4 / 7 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 7 / 46 % | 0 / 0 % | 25 / 45 % | 5 / 10 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 20 / 43 % | 21 / 48 % | 1 / 5 % | 0 / 0 % | 15 / 37 % | 10 / 25 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 12 / 37 % | 19 / 53 % | 0 / 1 % | 0 / 0 % | 6 / 14 % | 5 / 10 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 16 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 6 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) Wie lässt sich die Größe von Trainingsläufen überprüfen, ohne Modelldetails offenzulegen? | 10 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 8 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 10 / 19 % | 8 / 29 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 3 / 6 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 8 / 22 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 8 / 38 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 3 / 5 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 7 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 8 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 4 / 7 % |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 2 / 15 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 6 % |
| [SF-F2](../../../../fragen/SF-F2/) Wenn ein Staat ein Modell als Beleg für eine überschrittene Schwelle nennt oder ein Risiko an der Herkunft eines Modells festmacht: Wie wird das überprüfbar? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 4 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 4 / 7 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 3 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 4 % |
