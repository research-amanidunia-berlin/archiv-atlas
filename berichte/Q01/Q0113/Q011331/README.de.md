[English](README.md) · [Deutsch](README.de.md)

# I Wired Claude Code to WhatsApp — Now I Run My Entire Development Workflow From My Phone

Bericht Q011331 · Quelle medium.com · Datum 2025-12-19 · [Original öffnen](https://medium.com/coding-nexus/i-wired-claude-code-to-whatsapp-now-i-run-my-entire-development-workflow-from-my-phone-b573716bdf36)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Der Autor beschreibt einen improvisierten WhatsApp-Zugang zu Claude Code, mit Projektgruppen als Kontext, Nachrichten als Unterbrechungen und Zugriff auf seinen angemeldeten Browser. Er berichtet von Einsätzen für Recherche, Programmierung und Fehlerbehebung sowie von einem Monitor für Sitzungen und Freigaben. Es handelt sich um einen persönlichen Bericht über unfertigen Code; eine unabhängige Leistungs- oder Sicherheitsprüfung wird nicht vorgelegt.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 35 / 56 % | 97 / 99 % | 100 / 100 % | 44 / 66 % | 6 / 25 % | 24 / 47 % | 15 / 54 % | – |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 22 / 41 % | 67 / 92 % | 94 / 96 % | 9 / 24 % | 2 / 10 % | 5 / 13 % | 1 / 5 % | – |
| [SF-T3](../../../../fragen/SF-T3/) Woran erkennt man, dass KI beginnt, ihre eigene Weiterentwicklung voranzutreiben, und wer darf das erlauben? | 25 / 45 % | 90 / 97 % | 83 / 88 % | 22 / 44 % | 4 / 17 % | 16 / 31 % | 3 / 13 % | – |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 27 / 46 % | 13 / 86 % | 85 / 92 % | 23 / 48 % | 3 / 17 % | 15 / 33 % | 2 / 15 % | – |
| [SF-V4](../../../../fragen/SF-V4/) Was für ein Wesen ist ein Modell, und was folgt daraus für den Umgang mit ihm und für den Wert des Menschseins? | 0 / 0 % | 0 / 0 % | 69 / 77 % | 10 / 27 % | 0 / 0 % | 7 / 15 % | 0 / 3 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Welche Gefahren entstehen, wenn viele KI-Systeme zusammenwirken oder dieselbe Infrastruktur teilen? | 9 / 31 % | 8 / 46 % | 68 / 76 % | 11 / 33 % | 3 / 15 % | 7 / 20 % | 1 / 7 % | – |
| [SF-E4](../../../../fragen/SF-E4/) Wie bleibt KI ein gemeinsames Gut, statt Abhängigkeit und Marktmacht zu vertiefen? | 0 / 0 % | 3 / 36 % | 61 / 70 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Lassen sich KI-Systeme sicher anhalten, zurücksetzen, abschotten oder drosseln, und wer darf das anordnen? | 32 / 53 % | 29 / 61 % | 50 / 66 % | 30 / 54 % | 8 / 25 % | 20 / 42 % | 2 / 10 % | – |
| [SF-M4](../../../../fragen/SF-M4/) Wie kommen Meldungen von Laboren, Betreibern und Nutzern schnell und geschützt zu den Stellen, die handeln müssen, auch über Grenzen hinweg? | 0 / 0 % | 24 / 48 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 2 / 5 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Welche messbaren Schwellen sollen eine Pause auslösen, und wer prüft sie? | 0 / 0 % | 19 / 58 % | 21 / 37 % | 8 / 19 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) Woran erkennt man, dass ein Labor sich ehrlich selbst überwacht und dass seine Prüfungen gültig sind? | 16 / 33 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Halten die Werte eines Modells, wenn niemand zusieht oder die Lage neu ist? | 0 / 0 % | 3 / 38 % | 0 / 0 % | 9 / 28 % | 0 / 0 % | 6 / 15 % | 0 / 3 % | – |
| [SF-F1](../../../../fragen/SF-F1/) Wie misst man gefährliche Fähigkeiten eines Modells, vor allem im Cyberbereich, mit gemeinsam anerkannten, wiederholbaren Tests, die keine Sprache, Kultur oder Seite bevorzugen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) Wie lässt sich nachverfolgen, woraus ein Modell entstanden ist und was in ihm steckt? | 0 / 0 % | 7 / 38 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) Was zählt als Beleg für die Werte eines Modells, wenn sein sichtbares Denken und seine Selbstauskünfte allein nicht genügen? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 18 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) Wie stellt man fest, ob ein Vorfall gewollt oder versehentlich war, und ob KI oder herkömmliche Mittel dahinterstecken? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Für welche Modelle, Entwickler und Einsätze gelten Prüfregeln, und wann muss neu geprüft werden? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 3 / 5 % | 0 / 0 % | – |
