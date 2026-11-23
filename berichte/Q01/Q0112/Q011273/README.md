[English](README.md) · [Deutsch](README.de.md)

# Set Opus 4.8 + /ultracode and Watch Claude Code Go Fully Autonomous

Report Q011273 · Source medium.com · Date 2026-05-29 · [Open original](https://medium.com/@CodeCoup/set-opus-4-8-ultracode-and-watch-claude-code-go-fully-autonomous-ca754b97833e)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag schildert Claude Codes experimentelle „Dynamic Workflows“, die laut Autor große Programmieraufgaben in Teilaufgaben aufteilen und mehrere KI-Agenten parallel koordinieren können. Er nennt mögliche Anwendungen, belegt aber weder Zuverlässigkeit noch Leistungsgewinne; zudem könne der Tokenverbrauch schnell steigen, weshalb die Vorschau zu kleinen Aufgaben rät.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 26 / 51 % | 38 / 92 % | 90 / 97 % | 33 / 61 % | 4 / 22 % | 9 / 27 % | 6 / 44 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 19 / 39 % | 26 / 75 % | 84 / 94 % | 13 / 38 % | 2 / 15 % | 8 / 24 % | 1 / 11 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 12 / 40 % | 61 / 93 % | 74 / 83 % | 21 / 51 % | 5 / 27 % | 8 / 36 % | 3 / 21 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 42 % | 67 / 96 % | 59 / 82 % | 19 / 46 % | 6 / 24 % | 20 / 46 % | 4 / 27 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 65 / 83 % | 7 / 22 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 18 / 59 % | 50 / 76 % | 4 / 15 % | 0 / 4 % | 2 / 9 % | 0 / 4 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 33 / 53 % | 4 / 9 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 9 / 41 % | 7 / 30 % | 7 / 20 % | 1 / 7 % | 6 / 17 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 37 % | 7 / 29 % | 1 / 15 % | 8 / 24 % | 2 / 15 % | 6 / 18 % | 0 / 4 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 51 % | 8 / 32 % | 5 / 12 % | 0 / 4 % | 2 / 8 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 20 % | 0 / 3 % | 5 / 11 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 3 / 14 % | 5 / 12 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 3 % | 5 / 10 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 1 / 5 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 2 / 4 % | 0 / 0 % | – |
