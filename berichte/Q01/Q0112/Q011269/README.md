[English](README.md) · [Deutsch](README.de.md)

# How to Run Claude on Autopilot: The Complete 14-Step Automation Stack

Report Q011269 · Source medium.com · Date 2026-06-08 · [Open original](https://medium.com/coding-nexus/how-to-run-claude-on-autopilot-the-complete-14-step-automation-stack-470d7bc57495)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vollständige Leitfaden stellt Claude Code als Automatisierungsplattform mit Sitzungsschleifen, lokalen Zeitplänen und Cloud-Routinen vor und erklärt ihre Einsatzfälle und Grenzen. Der Artikel empfiehlt klare Abschlussziele, Tokenbudgets, begrenzte Berechtigungen und Audit-Protokolle; seine Produktangaben beziehen sich auf Juni 2026 und werden nicht unabhängig überprüft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 62 / 76 % | 97 / 99 % | 60 / 78 % | 100 / 100 % | 70 / 83 % | 60 / 74 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 16 / 28 % | 35 / 66 % | 0 / 0 % | 90 / 94 % | 6 / 14 % | 6 / 12 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 50 % | 38 / 72 % | 4 / 12 % | 87 / 93 % | 43 / 66 % | 41 / 57 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 29 / 48 % | 43 / 91 % | 5 / 12 % | 59 / 72 % | 38 / 60 % | 46 / 63 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 48 / 86 % | 0 / 0 % | 27 / 55 % | 0 / 0 % | 11 / 23 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 38 / 84 % | 0 / 0 % | 0 / 0 % | 10 / 33 % | 9 / 20 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 7 / 29 % | 0 / 0 % | 0 / 0 % | 30 / 46 % | 9 / 25 % | 7 / 19 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 31 % | 29 / 49 % | 0 / 3 % | 0 / 0 % | 9 / 26 % | 9 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 29 / 44 % | 7 / 15 % | 4 / 7 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 10 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 6 / 11 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 4 / 7 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 6 / 11 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 5 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 4 / 7 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
