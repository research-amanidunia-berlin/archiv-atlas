[English](README.md) · [Deutsch](README.de.md)

# OpenAI Misalignment Monitor: Would Have Caught HF Breach

Report Q000250 · Source explainx.ai · Date 2026-10-29 · [Open original](https://www.explainx.ai/blog/openai-how-we-detect-frontier-model-misalignment-four-layer-monitor-hugging-face-replay-30-minutes-2026)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 48 / 66 % | 100 / 100 % | – | 99 / 100 % | 87 / 92 % | 81 / 91 % | 89 / 93 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 57 / 73 % | 100 / 100 % | – | 99 / 100 % | 85 / 92 % | 88 / 94 % | 89 / 92 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 66 / 79 % | 100 / 100 % | – | 100 / 100 % | 92 / 95 % | 87 / 94 % | 92 / 95 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 54 / 74 % | 93 / 97 % | – | 99 / 100 % | 86 / 92 % | 50 / 74 % | 75 / 84 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 62 / 75 % | 93 / 99 % | – | 98 / 99 % | 82 / 90 % | 83 / 93 % | 84 / 91 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 41 / 59 % | 51 / 77 % | – | 97 / 98 % | 81 / 90 % | 18 / 40 % | 72 / 81 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 48 / 68 % | 96 / 98 % | – | 93 / 97 % | 81 / 90 % | 78 / 90 % | 71 / 85 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 58 / 74 % | 76 / 90 % | – | 92 / 96 % | 89 / 93 % | 92 / 96 % | 91 / 94 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 89 / 98 % | – | 84 / 90 % | 67 / 83 % | 36 / 58 % | 40 / 61 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 70 / 97 % | – | 87 / 92 % | 47 / 71 % | 23 / 45 % | 48 / 67 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 34 / 59 % | 57 / 95 % | – | 83 / 94 % | 17 / 32 % | 38 / 61 % | 63 / 77 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 36 / 57 % | 76 / 98 % | – | 33 / 58 % | 31 / 60 % | 14 / 31 % | 39 / 56 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 28 / 77 % | – | 74 / 84 % | 57 / 77 % | 16 / 44 % | 29 / 50 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 73 / 95 % | – | 46 / 73 % | 55 / 76 % | 28 / 51 % | 40 / 63 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 67 / 97 % | – | 47 / 70 % | 9 / 22 % | 1 / 5 % | 6 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 49 % | 0 / 0 % | – | 65 / 79 % | 30 / 55 % | 14 / 29 % | 16 / 32 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 20 / 44 % | 0 / 0 % | – | 57 / 66 % | 42 / 69 % | 17 / 38 % | 60 / 77 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 34 / 52 % | 45 / 93 % | – | 59 / 79 % | 52 / 77 % | 36 / 61 % | 32 / 54 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 2 / 42 % | – | 56 / 75 % | 40 / 67 % | 8 / 18 % | 11 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 19 / 64 % | – | 47 / 65 % | 13 / 32 % | 3 / 10 % | 7 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 23 / 52 % | 45 / 94 % | – | 33 / 56 % | 23 / 50 % | 10 / 31 % | 19 / 36 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 41 / 64 % | 2 / 5 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 36 / 92 % | – | 3 / 26 % | 11 / 28 % | 6 / 15 % | 6 / 16 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 31 / 63 % | 6 / 19 % | 3 / 8 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 9 / 61 % | – | 29 / 52 % | 11 / 29 % | 7 / 19 % | 12 / 23 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 28 / 61 % | – | 0 / 0 % | 8 / 16 % | 2 / 5 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 22 / 54 % | – | 0 / 0 % | 8 / 20 % | 3 / 10 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 32 % | 6 / 14 % | 21 / 37 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 8 / 74 % | – | 17 / 40 % | 9 / 23 % | 3 / 6 % | 9 / 16 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 64 % | – | 3 / 20 % | 11 / 33 % | 5 / 17 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 0 / 1 % | 10 / 16 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 19 % | 2 / 4 % | 10 / 24 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 9 / 46 % | – | 0 / 0 % | 7 / 18 % | 1 / 2 % | 7 / 11 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 19 % | 0 / 3 % | 6 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 26 % | 3 / 9 % | 8 / 13 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 13 % | 7 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 1 / 5 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 7 / 74 % | – | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 3 / 6 % | 3 / 7 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 1 / 3 % | 0 / 0 % |
