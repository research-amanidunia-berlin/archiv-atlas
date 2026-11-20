[English](README.md) · [Deutsch](README.de.md)

# Run Shell Command from Claude Code without Claude Code

Bericht Q009662 · Quelle medium.com · Datum 2026-08-29 · [Original öffnen](https://medium.com/@itsuki.enjoy/run-shell-command-from-claude-code-without-claude-code-a4e6c0b8c12e)

[Alle Berichte](../../../README.de.md) · Daten: [bericht.json](bericht.json)

## Zusammenfassung (von Luna, ungeprüft)

Itsuki beschreibt ein Claude-Code-Plugin, das mit dem Hook `UserPromptSubmit` Befehle nach dem Präfix `/bash` ausführt und deren Ausgabe zurückgibt, ohne den Prompt regulär ans Modell weiterzugeben. Die behauptete Tokenersparnis und das Verhalten der Hook-Antworten werden im Artikel anhand von Code erläutert, aber nicht unabhängig getestet.

## Sammelfragen

Je Zelle: Anteil Stufe 4–7 / Stufe 3–7 (4 = enthält zitierbare Belege … 7 = beantwortet direkt; 3 = nützlicher Hintergrund). Aufgeführt: Sammelfragen, bei denen mindestens ein Modell den Stufen 3–7 mindestens 10 % gibt. „–“ = Modell hat diesen Bericht nicht bewertet. Volle Verteilungen: [bericht.json](bericht.json).

| Frage | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Welche Befugnisse darf ein KI-Agent haben, also eine KI, die selbstständig mit Werkzeugen handelt? Wer entzieht sie ihm, und wie prüft man, dass er in seinem Auftrag bleibt? | 0 / 0 % | 89 / 94 % | 0 / 0 % | 93 / 96 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) Was soll heute für das Verhalten und den Betrieb von Modellen gelten? | 0 / 0 % | 52 / 78 % | 0 / 0 % | 62 / 74 % | 8 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) Welche Mitsprache haben die Menschen, die mit KI leben, bei Tempo und Grenzen, und welche Entscheidungen müssen bei ihnen bleiben? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 59 / 66 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
