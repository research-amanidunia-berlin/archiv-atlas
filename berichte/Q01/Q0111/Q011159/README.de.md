[English](README.md) · [Deutsch](README.de.md)

# Fable 5.2 + Opus 5.5: How to Orchestrate a Team of AI Agents to Build Anything

Bericht Q011159 · Quelle medium.com · Datum 2026-11-15 · [Original öffnen](https://medium.com/coding-nexus/fable-5-2-opus-5-5-how-to-orchestrate-a-team-of-ai-agents-to-build-anything-7378326f4b97)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Beitrag schlägt vor, Fable 5.2 als Koordinator und Opus 5.5 als ausführende Unteragenten für Softwareprojekte einzusetzen, mit klar verteilten Aufgaben und vorheriger Abstimmung gemeinsamer Schnittstellen. Er erläutert zudem die Installation von Agenten-Fähigkeiten und nennt Koordination, Kontext, Tests, Ressourcen und Kosten als Herausforderungen; eigene Vergleichsmessungen führt er nicht an.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 20 / 38 % | 61 / 91 % | 1 / 9 % | 97 / 99 % | 16 / 39 % | 1 / 10 % | 7 / 18 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 11 / 39 % | 66 / 98 % | 8 / 22 % | 62 / 71 % | 22 / 53 % | 9 / 32 % | 13 / 41 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 18 / 42 % | 58 / 91 % | 7 / 35 % | 58 / 81 % | 22 / 46 % | 4 / 19 % | 7 / 18 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 22 / 44 % | 0 / 0 % | 52 / 65 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 5 / 29 % | 0 / 0 % | 49 / 71 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 17 / 41 % | 48 / 90 % | 4 / 13 % | 12 / 26 % | 11 / 33 % | 3 / 13 % | 13 / 29 % |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 8 / 74 % | 0 / 0 % | 5 / 23 % | 0 / 0 % | 0 / 2 % | 4 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 8 / 30 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 7 / 20 % | 2 / 12 % | 6 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 11 % | 5 / 10 % | 0 / 0 % | 2 / 5 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 10 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 4 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Wo endet die erlaubte Nutzung fremder Modellausgaben, und wo beginnt unerlaubte Destillation, also das Trainieren eines eigenen Modells mit diesen Ausgaben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % | 1 / 3 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 1 / 28 % | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | 0 / 0 % |
