[English](README.md) · [Deutsch](README.de.md)

# Claude Code Best Practices

Report Q000898 · Source anthropic.com · Date 2025-04-18 · [Open original](https://www.anthropic.com/research/claude-code-best-practices)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic empfiehlt für Claude Code unter anderem knappe Projektanweisungen, präzise Aufträge und iterative Abläufe mit Planung sowie Tests oder visuellen Vergleichen. Der nicht mehr gepflegte Beitrag stützt sich auf Erfahrungswerte statt auf systematische Messungen und verweist für aktuelle Hinweise auf die offizielle Dokumentation; das Umgehen von Berechtigungsprüfungen wird als riskant eingestuft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 36 / 56 % | 100 / 100 % | – | 100 / 100 % | 81 / 89 % | 61 / 73 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 43 % | 36 / 78 % | – | 82 / 89 % | 51 / 72 % | 34 / 52 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 24 / 47 % | – | 75 / 82 % | 5 / 12 % | 4 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 33 / 51 % | 37 / 67 % | – | 74 / 80 % | 70 / 84 % | 65 / 78 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 25 % | 11 / 54 % | – | 48 / 59 % | 24 / 47 % | 11 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 32 % | 28 / 50 % | – | 0 / 0 % | 8 / 25 % | 5 / 10 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 20 / 49 % | 5 / 11 % | 2 / 4 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 20 / 73 % | – | 0 / 0 % | 8 / 27 % | 7 / 14 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 18 / 30 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 14 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 17 / 55 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 23 % | 10 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 50 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 3 / 7 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 3 / 5 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 2 / 13 % | 0 / 0 % | 0 / 0 % |
