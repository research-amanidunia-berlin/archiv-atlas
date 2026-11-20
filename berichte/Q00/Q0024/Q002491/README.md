[English](README.md) · [Deutsch](README.de.md)

# Building interactive agents in video game worlds

Report Q002491 · Source deepmind.google · Date 2022-11-23 · [Open original](https://deepmind.google/blog/building-interactive-agents-in-video-game-worlds/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

DeepMind beschreibt ein Training von Spielwelt-Agenten, das menschliche Nachahmung mit menschlichem Feedback und Reinforcement Learning verbindet. Laut Bericht verbesserten sich die Agenten in den Tests gegenüber reiner Nachahmung; die Ergebnisse stammen jedoch aus einer eigens entwickelten Simulation und der Ansatz wird als frühe Forschungsarbeit eingeordnet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 46 % | 50 / 95 % | 0 / 0 % | 90 / 94 % | 16 / 45 % | 16 / 35 % | 4 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 36 / 87 % | 0 / 0 % | 89 / 96 % | 10 / 30 % | 8 / 19 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 13 / 36 % | 49 / 91 % | 2 / 19 % | 82 / 93 % | 20 / 44 % | 7 / 19 % | 3 / 12 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 69 / 98 % | 1 / 10 % | 77 / 88 % | 29 / 59 % | 25 / 48 % | 4 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 18 / 47 % | 0 / 5 % | 71 / 87 % | 8 / 27 % | 6 / 15 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 30 % | 49 / 83 % | 1 / 7 % | 64 / 80 % | 9 / 27 % | 6 / 16 % | 1 / 6 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 44 % | 44 / 90 % | 1 / 10 % | 64 / 81 % | 17 / 45 % | 14 / 36 % | 4 / 17 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 22 / 91 % | 0 / 0 % | 58 / 80 % | 8 / 23 % | 7 / 19 % | 2 / 9 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 14 / 97 % | 1 / 9 % | 39 / 74 % | 15 / 48 % | 11 / 30 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 24 / 70 % | 0 / 0 % | 15 / 34 % | 6 / 13 % | 6 / 12 % | 1 / 3 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 21 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 29 % | 14 / 63 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 5 / 14 % | 2 / 10 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 14 / 66 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 6 / 12 % | 1 / 6 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 27 % | 6 / 13 % | 2 / 7 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 6 / 14 % | 1 / 5 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 8 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 3 / 7 % | 1 / 4 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 6 / 13 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 1 / 4 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 8 % | 6 / 16 % | 4 / 11 % | 1 / 6 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 21 % | 0 / 0 % | 5 / 9 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 29 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 5 % |
