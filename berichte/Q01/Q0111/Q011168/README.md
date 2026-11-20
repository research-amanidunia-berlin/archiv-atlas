[English](README.md) · [Deutsch](README.de.md)

# My Claude Code Setup: A Planner, Workers, a Reviewer, and a Smarter Context Window

Report Q011168 · Source medium.com · Date 2026-10-24 · [Open original](https://medium.com/coding-nexus/my-claude-code-setup-a-planner-workers-a-reviewer-and-a-smarter-context-window-fe1ac2d24668)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor beschreibt einen Claude-Code-Ablauf, in dem Opus plant und prüft, Sonnet-Worker Teilaufgaben umsetzen und Herdr die Schritte koordiniert. Wiederverwendbare Skills und Kontextmanagement sollen wiederholte Anweisungen und irrelevante Gesprächsinhalte reduzieren. Die Darstellung ist ein persönlicher Erfahrungsbericht ohne vergleichende Messungen; Werkzeuge ersetzen laut Autor weder Tests noch menschliche Prüfung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 32 / 53 % | 62 / 98 % | 8 / 37 % | 93 / 98 % | 32 / 60 % | 10 / 28 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 38 % | 39 / 91 % | 1 / 9 % | 90 / 96 % | 22 / 49 % | 10 / 27 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 76 / 87 % | 4 / 11 % | 4 / 10 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 13 / 37 % | 25 / 89 % | 1 / 8 % | 41 / 63 % | 12 / 38 % | 6 / 24 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 54 % | 5 / 12 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 49 % | 5 / 10 % | 4 / 8 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 17 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 5 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 13 / 26 % | 3 / 29 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 5 / 9 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 25 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 33 % | 3 / 39 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 6 / 13 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 3 / 45 % | 0 / 0 % | 11 / 44 % | 0 / 0 % | 5 / 11 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 11 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 9 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 33 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 9 / 25 % | 7 / 21 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 11 / 18 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 4 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 21 % | 4 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
