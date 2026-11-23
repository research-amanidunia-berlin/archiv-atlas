[English](README.md) · [Deutsch](README.de.md)

# Prompt Injection: I Hid One Sentence in a Web Page and the AI Agent Obeyed

Report Q011066 · Source medium.com · Date 2026-06-26 · [Open original](https://medium.com/gitconnected/prompt-injection-i-hid-one-sentence-in-a-web-page-and-the-ai-agent-obeyed-c9a2045f1c33)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht liegt nur als Auszug vor: Der Hauptartikel ist hinter einer Medium-Zugangsschranke, sodass Beispiele, Ergebnisse und Schutzmaßnahmen nicht vorliegen. Im sichtbaren Teil warnt Andrus vor Prompt Injection und behauptet, OWASP habe das Risiko 2025 an die Spitze seiner Liste für generative KI gesetzt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 27 / 46 % | 20 / 79 % | 68 / 89 % | 21 / 49 % | 3 / 15 % | 12 / 35 % | 3 / 25 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 22 / 46 % | 7 / 62 % | 61 / 81 % | 16 / 41 % | 4 / 14 % | 6 / 16 % | 2 / 14 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 14 / 45 % | 59 / 76 % | 6 / 14 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 45 % | 42 / 78 % | 47 / 78 % | 27 / 55 % | 3 / 18 % | 10 / 34 % | 7 / 57 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 26 / 59 % | 13 / 55 % | 4 / 12 % | 0 / 2 % | 3 / 8 % | 0 / 2 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 8 / 18 % | 23 / 57 % | 1 / 22 % | 6 / 16 % | 1 / 3 % | 5 / 10 % | 0 / 4 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 10 / 34 % | 2 / 38 % | 22 / 64 % | 6 / 17 % | 2 / 8 % | 6 / 15 % | 1 / 12 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 6 / 30 % | 22 / 66 % | 0 / 0 % | 6 / 20 % | 1 / 7 % | 4 / 13 % | 0 / 5 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 20 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 18 / 44 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 3 % | 6 / 14 % | 0 / 2 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 17 / 35 % | 10 / 33 % | 0 / 0 % | 9 / 24 % | 0 / 3 % | 6 / 14 % | 0 / 3 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 15 / 37 % | 5 / 14 % | 0 / 2 % | 4 / 7 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 15 / 40 % | 13 / 68 % | 12 / 34 % | 9 / 30 % | 2 / 13 % | 6 / 20 % | 2 / 15 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 15 / 50 % | 12 / 62 % | 7 / 19 % | 0 / 0 % | 7 / 13 % | 0 / 4 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 34 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 11 / 32 % | 0 / 0 % | 4 / 9 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 34 % | 2 / 26 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 3 / 5 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 9 / 30 % | 0 / 0 % | 6 / 23 % | 5 / 14 % | 0 / 2 % | 2 / 5 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 8 / 39 % | 0 / 0 % | 4 / 9 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 8 / 32 % | 0 / 0 % | 0 / 8 % | 6 / 17 % | 1 / 4 % | 4 / 7 % | 0 / 4 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 7 / 31 % | 7 / 54 % | 1 / 32 % | 7 / 19 % | 0 / 2 % | 5 / 11 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 1 % | 3 / 5 % | 0 / 0 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 5 / 28 % | 3 / 27 % | 5 / 9 % | 0 / 1 % | 3 / 5 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 39 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 11 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 2 / 4 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 1 % | 4 / 7 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 1 / 4 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 51 % | 0 / 0 % | 5 / 10 % | 0 / 3 % | 2 / 6 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 4 / 24 % | 0 / 0 % | 4 / 8 % | 0 / 1 % | 4 / 6 % | 0 / 0 % | – |
