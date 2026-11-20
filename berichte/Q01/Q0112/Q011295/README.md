[English](README.md) · [Deutsch](README.de.md)

# Self-Validating Agents in Claude Code: Automated Quality at Every Step

Report Q011295 · Source medium.com · Date 2026-02-12 · [Open original](https://medium.com/coding-nexus/self-validating-agents-in-claude-code-automated-quality-at-every-step-80d70f95339f)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht schlägt drei Prüfstufen für Claude-Code-Agenten vor: automatische Prüfungen nach jeder Dateiänderung, eine Abschlusskontrolle auf strukturelle Vollständigkeit und einen separaten, nur lesenden Prüfagenten. Die behauptete Verringerung typischer Fehler um 90 Prozent wird nicht belegt; der Text bietet Konfigurationsbeispiele und Empfehlungen, aber keine Wirksamkeitsstudie.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 48 / 66 % | 92 / 100 % | 39 / 68 % | 100 / 100 % | 52 / 71 % | 24 / 43 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 15 / 72 % | 0 / 0 % | 94 / 98 % | 0 / 0 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 44 % | 36 / 73 % | 5 / 16 % | 92 / 96 % | 33 / 57 % | 19 / 38 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 28 / 59 % | 0 / 0 % | 79 / 91 % | 8 / 18 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 46 / 60 % | 5 / 11 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 31 % | 29 / 87 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 8 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 25 / 43 % | 6 / 10 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 47 % | 19 / 37 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 19 / 38 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | 21 / 39 % | 15 / 29 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 17 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 31 % | 12 / 22 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 11 / 30 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 29 % | 8 / 14 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 12 / 32 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 8 / 21 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 4 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 8 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 7 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
