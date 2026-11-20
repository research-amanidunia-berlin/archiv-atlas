[English](README.md) · [Deutsch](README.de.md)

# Codex-Orchestrator: Run OpenAI Codex Agents in Parallel Using tmux

Bericht Q011312 · Quelle medium.com · Datum 2026-01-20 · [Original öffnen](https://medium.com/coding-nexus/codex-orchestrator-run-openai-codex-agents-in-parallel-using-tmux-8e89edc6f6bd)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt ein Werkzeug, das Codex-Aufgaben in tmux-Sitzungen im Hintergrund und parallel ausführen soll; Jobs seien beobachtbar, nachträglich steuerbar und als strukturierte Daten abrufbar. Die Vorteile für den Arbeitsfluss beruhen auf der Einschätzung des Autors, systematische oder unabhängige Prüfungen nennt der Bericht nicht.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 24 / 39 % | 5 / 56 % | 0 / 0 % | 84 / 93 % | 15 / 36 % | 8 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 84 / 91 % | 4 / 10 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 18 / 39 % | 56 / 90 % | 2 / 13 % | 72 / 85 % | 20 / 42 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 46 / 66 % | 6 / 15 % | 5 / 9 % |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 33 / 52 % | 27 / 53 % | 0 / 0 % | 43 / 57 % | 29 / 51 % | 12 / 25 % |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 35 % | 1 / 14 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 6 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 7 / 30 % | 0 / 0 % | 0 / 0 % | 9 / 31 % | 7 / 24 % | 4 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 6 / 14 % |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 6 / 12 % |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 1 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
