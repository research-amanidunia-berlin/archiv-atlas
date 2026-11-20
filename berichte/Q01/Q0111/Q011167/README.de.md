[English](README.md) · [Deutsch](README.de.md)

# I Made AI Agent Decisions 150x Cheaper With Jev and TrueForge

Bericht Q011167 · Quelle medium.com · Datum 2026-10-27 · [Original öffnen](https://medium.com/coding-nexus/i-made-ai-agent-decisions-150x-cheaper-with-jev-and-trueforge-5e5af0561899)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor berichtet, dass ein Agent mit Jev, TrueForge und Daytona in einem Test mit 40 Kundenanfragen dieselbe Zuordnungsgenauigkeit wie Claude Opus bei jeder Entscheidung erzielt habe, zu ungefähr 150-mal geringeren Entscheidungskosten. Unsichere Fälle wurden Opus zur Prüfung vorgelegt; dieser Schritt erkannte laut Beitrag fünf Fehlzuordnungen. Die kleine Stichprobe belegt keine allgemeine Leistung, weshalb der Autor größere Tests und eine sorgfältige Kalibrierung empfiehlt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 26 / 41 % | 61 / 96 % | 3 / 11 % | 100 / 100 % | 25 / 49 % | 18 / 36 % | 8 / 21 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 27 / 48 % | 82 / 95 % | 32 / 50 % | 91 / 94 % | 41 / 65 % | 28 / 48 % | 19 / 37 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 70 / 93 % | 0 / 0 % | 88 / 93 % | 10 / 24 % | 0 / 0 % | 2 / 7 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 54 / 65 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 54 / 71 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 5 / 68 % | 0 / 0 % | 35 / 53 % | 6 / 15 % | 0 / 0 % | 1 / 6 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 50 % | 8 / 20 % | 4 / 9 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 16 / 36 % | 26 / 69 % | 1 / 4 % | 12 / 20 % | 21 / 46 % | 12 / 26 % | 10 / 22 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 8 / 30 % | 13 / 85 % | 0 / 0 % | 21 / 34 % | 7 / 23 % | 4 / 10 % | 2 / 9 % |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 20 / 37 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 8 / 17 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) Was darf offen veröffentlicht werden, und wer ist verantwortlich, wenn ein offenes Modell anderswo Schaden anrichtet? | 12 / 32 % | 0 / 0 % | 0 / 0 % | 11 / 22 % | 11 / 26 % | 7 / 13 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 12 / 37 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 31 % | 11 / 54 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 6 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 10 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 7 / 13 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 7 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 5 / 11 % | 0 / 0 % |
