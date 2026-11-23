[English](README.md) · [Deutsch](README.de.md)

# How to Run Claude on Autopilot: The Complete 14-Step Automation Stack

Report Q011269 · Source medium.com · Date 2026-06-08 · [Open original](https://medium.com/coding-nexus/how-to-run-claude-on-autopilot-the-complete-14-step-automation-stack-470d7bc57495)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Leitfaden stellt Claude Code als Automatisierungsplattform mit Sitzungsschleifen, lokalen Zeitplänen und Cloud-Routinen vor und erklärt ihre Einsatzfälle und Grenzen. Der Artikel empfiehlt klare Abschlussziele, Tokenbudgets, begrenzte Berechtigungen und Audit-Protokolle; seine Produktangaben beziehen sich auf Juni 2026 und werden nicht unabhängig überprüft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 62 / 76 % | 97 / 99 % | 100 / 100 % | 70 / 83 % | 32 / 53 % | 60 / 74 % | 60 / 78 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 16 / 28 % | 35 / 66 % | 90 / 94 % | 6 / 14 % | 1 / 3 % | 6 / 12 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 50 % | 38 / 72 % | 87 / 93 % | 43 / 66 % | 11 / 24 % | 41 / 57 % | 4 / 12 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 29 / 48 % | 43 / 91 % | 59 / 72 % | 38 / 60 % | 15 / 30 % | 46 / 63 % | 5 / 12 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 48 / 86 % | 27 / 55 % | 0 / 0 % | 0 / 0 % | 11 / 23 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 38 / 84 % | 0 / 0 % | 10 / 33 % | 0 / 1 % | 9 / 20 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 29 % | 0 / 0 % | 30 / 46 % | 9 / 25 % | 3 / 9 % | 7 / 19 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 31 % | 29 / 49 % | 0 / 0 % | 9 / 26 % | 1 / 4 % | 9 / 17 % | 0 / 3 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 29 / 44 % | 7 / 15 % | 0 / 0 % | 4 / 7 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 10 / 21 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 1 % | 6 / 11 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 1 % | 4 / 7 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 4 / 7 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 2 % | 6 / 12 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | – |
