[English](README.md) · [Deutsch](README.de.md)

# How to Orchestrate Claude Code Models While Using 10x Fewer Tokens

Report Q011156 · Source medium.com · Date 2026-11-16 · [Open original](https://medium.com/@CodeCoup/how-to-orchestrate-claude-code-models-while-using-10x-fewer-tokens-7b81001451e1)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor empfiehlt, Modelle passend zur Aufgabe einzusetzen, Teilagenten eng umrissene Aufträge und knappe Antwortvorgaben zu geben sowie Ergebnisse anhand von Tests und Diffs zu überprüfen. Die Überschrift verspricht zehnfach weniger Tokens, doch der Bericht nennt keine Messwerte; seine Empfehlungen stützen sich auf eine erwähnte Reddit-Diskussion.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 22 / 39 % | 68 / 92 % | 99 / 100 % | 24 / 47 % | 4 / 14 % | 11 / 25 % | 2 / 10 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 94 / 97 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 22 / 45 % | 54 / 88 % | 94 / 96 % | 28 / 56 % | 7 / 22 % | 12 / 31 % | 2 / 9 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 28 / 52 % | 61 / 89 % | 90 / 95 % | 32 / 55 % | 7 / 21 % | 12 / 26 % | 19 / 42 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 44 / 80 % | 76 / 85 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 40 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 20 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 3 / 8 % | 9 / 16 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 33 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 33 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
