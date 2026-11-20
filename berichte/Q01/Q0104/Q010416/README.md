[English](README.md) · [Deutsch](README.de.md)

# AI Agent: OpenAI AgentSDK vs Amazon Bedrock

Report Q010416 · Source medium.com · Date 2025-03-25 · [Open original](https://medium.com/gitconnected/ai-agent-openai-agentsdk-vs-amazon-bedrock-cb42a513c796)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Autor bevorzugt Amazon Bedrock Agents gegenüber dem OpenAI Agents SDK, vor allem wegen der aus seiner Sicht besseren Ablaufübersicht, des eingebauten sitzungsbezogenen und konfigurierbaren sitzungsübergreifenden Gedächtnisses sowie der Werkzeuggruppen und Versionsverwaltung. Das Urteil beruht auf persönlichen Beispielen; die KI-Modelle vergleicht er ausdrücklich nicht, und ein systematischer Leistungsvergleich wird nicht gezeigt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 22 / 43 % | 99 / 100 % | 5 / 25 % | 97 / 99 % | 34 / 60 % | 20 / 47 % | 5 / 23 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 23 / 61 % | 0 / 0 % | 67 / 77 % | 7 / 20 % | 0 / 0 % | 2 / 8 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 20 / 37 % | 24 / 87 % | 1 / 6 % | 66 / 81 % | 19 / 43 % | 13 / 37 % | 4 / 15 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 13 / 33 % | 52 / 88 % | 1 / 4 % | 54 / 60 % | 23 / 47 % | 21 / 40 % | 8 / 21 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 14 / 31 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 8 / 20 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 35 % | 0 / 0 % | 13 / 25 % | 5 / 11 % | 0 / 0 % | 1 / 4 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 5 / 39 % | 0 / 0 % | 0 / 0 % | 6 / 24 % | 9 / 20 % | 1 / 3 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 6 / 15 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 5 / 24 % | 5 / 44 % | 0 / 3 % | 6 / 22 % | 7 / 23 % | 5 / 15 % | 1 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 4 / 7 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 4 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 9 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 5 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 10 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
