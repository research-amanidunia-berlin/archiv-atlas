[English](README.md) · [Deutsch](README.de.md)

# OpenAI Codex SDK for Creating Our Own Codex Agent

Bericht Q010053 · Quelle medium.com · Datum 2025-11-05 · [Original öffnen](https://medium.com/stackademic/openai-codex-sdk-for-creating-our-own-codex-agent-bee5ad08fe57)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Bericht beschreibt das Codex SDK als TypeScript-Wrapper um die lokale Codex-CLI und führt Beispiele für Threads, Text- und Bildeingaben, strukturierte Ausgaben sowie Ereignis-Streaming an. Der Autor kritisiert fehlende Möglichkeiten für menschliche Freigaben während der Ausführung und zum programmgesteuerten Hinzufügen von MCP-Servern; diese Einschätzungen beruhen auf seiner eigenen Erkundung.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 29 / 48 % | 97 / 99 % | 98 / 99 % | 42 / 65 % | 9 / 23 % | 17 / 33 % | 10 / 28 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 29 / 44 % | 83 / 87 % | 6 / 12 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 22 / 44 % | 16 / 38 % | 82 / 86 % | 27 / 50 % | 10 / 25 % | 17 / 34 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 20 / 34 % | 19 / 68 % | 55 / 71 % | 21 / 42 % | 0 / 0 % | 13 / 27 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 11 / 31 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 4 / 9 % | 0 / 0 % | – |
