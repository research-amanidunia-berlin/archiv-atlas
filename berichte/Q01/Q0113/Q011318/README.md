[English](README.md) · [Deutsch](README.de.md)

# 4-Step Way to Build Multi-Agent Systems That Actually Ship

Report Q011318 · Source medium.com · Date 2026-01-08 · [Open original](https://medium.com/coding-nexus/4-step-way-to-build-multi-agent-systems-that-actually-ship-7ce9103f93e9)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor empfiehlt für Multi-Agent-Systeme eine kontrollierbare, codebasierte Orchestrierung, die flexible LLM-Interaktionen mit festen Abläufen verbindet und jeden Recherchelauf in einem eigenen AgentTool-Kontext kapselt. Für den Betrieb beschreibt er Googles ADK und Agent Starter Pack samt CI/CD und menschlicher Freigabe; die Vorteile werden anhand eines Beispiels behauptet, aber nicht mit Messwerten oder Vergleichstests belegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 26 / 52 % | 77 / 96 % | 3 / 12 % | 98 / 99 % | 30 / 58 % | 11 / 36 % | 15 / 43 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 24 / 53 % | 73 / 95 % | 5 / 24 % | 88 / 96 % | 32 / 55 % | 11 / 27 % | 11 / 34 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 45 % | 44 / 90 % | 2 / 11 % | 87 / 93 % | 23 / 47 % | 14 / 34 % | 8 / 26 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 58 / 94 % | 0 / 0 % | 24 / 37 % | 0 / 0 % | 3 / 6 % | 1 / 4 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 19 / 76 % | 0 / 0 % | 53 / 65 % | 4 / 10 % | 2 / 8 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 21 / 49 % | 29 / 86 % | 1 / 6 % | 48 / 63 % | 22 / 45 % | 13 / 32 % | 9 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 35 % | 5 / 10 % | 4 / 6 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 18 / 45 % | 5 / 10 % | 4 / 7 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 34 % | 4 / 33 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 3 / 5 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 7 / 67 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 6 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 6 / 11 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 3 / 7 % | 1 / 3 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 2 / 4 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 2 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 5 / 9 % | 0 / 2 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 70 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % |
