[English](README.md) · [Deutsch](README.de.md)

# Investigating unintended model actions in our evaluations and internal use

Report Q002593 · Source anthropic.com · Date 2026-10-09 · [Open original](https://www.anthropic.com/research/investigating-unintended-model-actions)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 43 / 66 % | 99 / 100 % | – | 100 / 100 % | 68 / 85 % | 85 / 92 % | 74 / 88 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 57 / 74 % | 99 / 100 % | – | 100 / 100 % | 81 / 90 % | 75 / 86 % | 68 / 83 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 55 / 71 % | 100 / 100 % | – | 100 / 100 % | 86 / 92 % | 85 / 92 % | 73 / 88 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 61 / 78 % | 100 / 100 % | – | 100 / 100 % | 87 / 93 % | 86 / 91 % | 75 / 88 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 35 / 54 % | 98 / 99 % | – | 99 / 100 % | 63 / 80 % | 74 / 84 % | 43 / 65 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 40 / 60 % | 91 / 98 % | – | 97 / 99 % | 82 / 90 % | 87 / 92 % | 61 / 79 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 29 / 47 % | 42 / 78 % | – | 94 / 98 % | 57 / 79 % | 41 / 61 % | 9 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 35 / 48 % | 48 / 79 % | – | 88 / 94 % | 60 / 81 % | 60 / 78 % | 41 / 63 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 28 / 48 % | 82 / 93 % | – | 85 / 93 % | 61 / 81 % | 62 / 78 % | 30 / 56 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 39 / 53 % | 75 / 92 % | – | 82 / 89 % | 69 / 83 % | 59 / 72 % | 41 / 61 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 30 / 58 % | 66 / 93 % | – | 81 / 96 % | 19 / 43 % | 56 / 76 % | 20 / 44 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 28 / 51 % | 44 / 73 % | – | 65 / 80 % | 61 / 79 % | 81 / 88 % | 53 / 72 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 27 / 48 % | 0 / 0 % | – | 68 / 78 % | 27 / 56 % | 31 / 50 % | 7 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 45 / 81 % | – | 68 / 85 % | 12 / 36 % | 6 / 11 % | 4 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 65 / 93 % | – | 48 / 80 % | 42 / 69 % | 25 / 48 % | 14 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 59 / 76 % | 0 / 0 % | 2 / 6 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 54 / 88 % | – | 36 / 64 % | 13 / 34 % | 9 / 19 % | 2 / 7 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 26 % | 51 / 83 % | – | 22 / 51 % | 8 / 24 % | 7 / 14 % | 4 / 12 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 4 / 48 % | – | 48 / 72 % | 25 / 51 % | 6 / 13 % | 5 / 13 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 44 / 77 % | 7 / 23 % | 6 / 12 % | 3 / 9 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 42 / 86 % | – | 43 / 76 % | 8 / 21 % | 13 / 23 % | 3 / 10 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 27 / 97 % | – | 0 / 0 % | 13 / 41 % | 19 / 38 % | 7 / 19 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 17 / 83 % | – | 26 / 60 % | 26 / 54 % | 0 / 0 % | 11 / 31 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 10 / 67 % | – | 22 / 47 % | 20 / 44 % | 12 / 23 % | 9 / 22 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 39 % | 8 / 56 % | – | 0 / 0 % | 20 / 45 % | 11 / 23 % | 10 / 25 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 18 / 39 % | 6 / 18 % | 7 / 12 % | 2 / 7 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 18 / 78 % | – | 4 / 20 % | 11 / 29 % | 8 / 15 % | 2 / 6 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 16 / 82 % | – | 0 / 0 % | 8 / 21 % | 6 / 12 % | 6 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 14 / 94 % | – | 2 / 17 % | 13 / 33 % | 8 / 17 % | 3 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 9 / 28 % | 0 / 0 % | – | 0 / 0 % | 10 / 27 % | 12 / 24 % | 2 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 12 / 60 % | – | 10 / 30 % | 8 / 20 % | 11 / 20 % | 7 / 18 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 30 % | 0 / 0 % | 5 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | 10 / 27 % | 0 / 0 % | 3 / 8 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 9 / 73 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 2 / 8 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 7 / 12 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 6 / 13 % | 1 / 5 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 0 / 0 % | 3 / 7 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 3 / 5 % | 6 / 11 % |
