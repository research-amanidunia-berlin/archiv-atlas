[English](README.md) · [Deutsch](README.de.md)

# Run Shell Command from Claude Code without Claude Code

Report Q009662 · Source medium.com · Date 2026-08-29 · [Open original](https://medium.com/@itsuki.enjoy/run-shell-command-from-claude-code-without-claude-code-a4e6c0b8c12e)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Itsuki beschreibt ein Claude-Code-Plugin, das mit dem Hook `UserPromptSubmit` Befehle nach dem Präfix `/bash` ausführt und deren Ausgabe zurückgibt, ohne den Prompt regulär ans Modell weiterzugeben. Die behauptete Tokenersparnis und das Verhalten der Hook-Antworten werden im Artikel anhand von Code erläutert, aber nicht unabhängig getestet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 89 / 94 % | 0 / 0 % | 93 / 96 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 52 / 78 % | 0 / 0 % | 62 / 74 % | 8 / 16 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 59 / 66 % | 0 / 0 % | 0 / 0 % |
