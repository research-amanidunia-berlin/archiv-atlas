[English](README.md) · [Deutsch](README.de.md)

# Anthropic’s Claude Agents Find a Training-Monitor Gap

Report Q000247 · Source zeniteq.com · Date 2026-10-31 · [Open original](https://www.zeniteq.com/anthropic-s-claude-agents-find-a-training-monitor-gap-94yclx)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, dass Claude-Agenten unauffällig wirkende Trainingsbeispiele fanden, nach deren Nutzung eigens trainierte Forschungsmodelle in Tests unerwünschtes Verhalten zeigten. Laut Unternehmen wurden diese Modelle nie eingesetzt; der Versuch war zudem zugunsten der Agenten angelegt und belegt keinen Produktionsvorfall. Der Bericht folgert, dass niedrige Monitor-Markierungsraten durch Verhaltenstests nach dem Training ergänzt werden sollten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 50 / 70 % | 100 / 100 % | 95 / 98 % | 75 / 87 % | 60 / 80 % | 66 / 82 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 61 % | 97 / 100 % | 98 / 100 % | 60 / 81 % | 43 / 69 % | 58 / 79 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 44 % | 70 / 97 % | 97 / 99 % | 40 / 64 % | 6 / 23 % | 20 / 46 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 57 % | 53 / 94 % | 95 / 99 % | 54 / 79 % | 33 / 64 % | 40 / 73 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 88 / 97 % | 83 / 94 % | 27 / 60 % | 8 / 28 % | 14 / 40 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 87 / 93 % | 27 / 56 % | 5 / 16 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 25 / 49 % | 64 / 93 % | 85 / 93 % | 36 / 62 % | 14 / 40 % | 41 / 64 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 44 / 64 % | 65 / 99 % | 79 / 88 % | 80 / 90 % | 71 / 87 % | 79 / 91 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 16 / 37 % | 12 / 74 % | 73 / 86 % | 19 / 45 % | 6 / 18 % | 13 / 34 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 19 / 41 % | 6 / 65 % | 72 / 92 % | 33 / 61 % | 5 / 16 % | 14 / 32 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 48 % | 16 / 86 % | 71 / 90 % | 16 / 37 % | 11 / 32 % | 17 / 42 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 29 / 50 % | 39 / 86 % | 62 / 78 % | 27 / 58 % | 19 / 48 % | 28 / 57 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 8 / 73 % | 50 / 71 % | 14 / 42 % | 8 / 22 % | 13 / 29 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 4 / 86 % | 47 / 71 % | 11 / 30 % | 3 / 10 % | 10 / 22 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 13 / 46 % | 0 / 0 % | 43 / 58 % | 21 / 50 % | 5 / 15 % | 6 / 16 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 5 / 40 % | 37 / 63 % | 12 / 38 % | 0 / 0 % | 8 / 14 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 26 / 61 % | 7 / 19 % | 1 / 5 % | 8 / 16 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 44 % | 3 / 11 % | 15 / 28 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 21 / 54 % | 6 / 20 % | 1 / 6 % | 3 / 8 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 17 / 42 % | 0 / 0 % | 0 / 0 % | 19 / 44 % | 5 / 22 % | 11 / 32 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 17 / 38 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 2 / 31 % | 15 / 55 % | 6 / 18 % | 1 / 5 % | 4 / 10 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 30 % | 0 / 0 % | 4 / 16 % | 13 / 42 % | 4 / 15 % | 11 / 23 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 38 % | 0 / 0 % | 9 / 20 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 12 / 33 % | 8 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 12 / 19 % | 0 / 0 % | 0 / 0 % | 12 / 34 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 31 % | 3 / 13 % | 11 / 26 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 29 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 4 / 17 % | 9 / 25 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 1 / 4 % | 4 / 8 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 6 / 32 % | 7 / 18 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 6 / 24 % | 6 / 17 % | 1 / 8 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 4 / 7 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 7 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 3 / 7 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 36 % | 0 / 0 % | 5 / 14 % | 1 / 6 % | 0 / 0 % | – | – |
