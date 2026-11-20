[English](README.md) · [Deutsch](README.de.md)

# Lessons From Red-teaming Auto-review, OpenAI's Blocking Monitor

Report Q000281 · Source lesswrong.com · Date 2026-10-30 · [Open original](https://www.lesswrong.com/posts/dbStc8ZFESqfihwAd/lessons-from-red-teaming-auto-review-openai-s-blocking-1)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 51 / 66 % | 90 / 100 % | – | 100 / 100 % | 81 / 90 % | 75 / 86 % | 52 / 76 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 72 / 84 % | 100 / 100 % | – | 100 / 100 % | 90 / 94 % | 79 / 88 % | 59 / 80 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 30 / 51 % | 36 / 91 % | – | 95 / 98 % | 31 / 57 % | 55 / 77 % | 23 / 52 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 58 % | 91 / 99 % | – | 94 / 98 % | 59 / 80 % | 67 / 83 % | 52 / 76 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 33 / 51 % | 83 / 98 % | – | 41 / 68 % | 35 / 63 % | 46 / 66 % | 19 / 44 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 16 / 34 % | 51 / 93 % | – | 70 / 83 % | 59 / 77 % | 18 / 44 % | 8 / 26 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 31 / 49 % | 30 / 60 % | – | 0 / 0 % | 54 / 76 % | 65 / 80 % | 18 / 43 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 63 / 96 % | – | 65 / 78 % | 28 / 52 % | 0 / 0 % | 7 / 15 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 21 / 40 % | 64 / 99 % | – | 22 / 46 % | 41 / 65 % | 54 / 76 % | 22 / 50 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 58 % | 62 / 98 % | – | 48 / 72 % | 55 / 76 % | 47 / 73 % | 22 / 44 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 24 / 42 % | 52 / 95 % | – | 62 / 74 % | 35 / 59 % | 23 / 43 % | 10 / 21 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 23 / 38 % | 19 / 80 % | – | 58 / 86 % | 43 / 68 % | 26 / 46 % | 8 / 24 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 47 % | 20 / 51 % | – | 57 / 77 % | 37 / 63 % | 15 / 31 % | 15 / 41 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 55 / 90 % | – | 32 / 63 % | 9 / 24 % | 6 / 15 % | 3 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 50 / 98 % | – | 24 / 57 % | 24 / 50 % | 15 / 33 % | 7 / 18 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 38 % | 41 / 96 % | – | 19 / 44 % | 22 / 46 % | 24 / 45 % | 7 / 22 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 26 / 71 % | – | 41 / 60 % | 11 / 28 % | 0 / 0 % | 6 / 16 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 39 / 64 % | 10 / 23 % | 0 / 0 % | 3 / 7 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 38 / 88 % | – | 12 / 42 % | 18 / 42 % | 13 / 28 % | 2 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 30 / 53 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 24 / 69 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 23 / 47 % | 0 / 0 % | 6 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 19 / 28 % | 14 / 65 % | – | 0 / 0 % | 18 / 42 % | 0 / 0 % | 4 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 16 / 40 % | 7 / 21 % | 0 / 0 % | 4 / 13 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 10 / 22 % | 3 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 9 / 22 % | 10 / 28 % | 0 / 0 % | 5 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 26 % | 0 / 0 % | 4 / 13 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 8 / 51 % | – | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 5 / 11 % | 1 / 5 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % | 3 / 8 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 0 / 0 % | 2 / 7 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 40 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 2 / 6 % |
