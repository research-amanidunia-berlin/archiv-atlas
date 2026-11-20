[English](README.md) · [Deutsch](README.de.md)

# Pioneering an AI clinical copilot with Penda Health

Report Q008786 · Source openai.com · Date 2025-07-22 · [Open original](https://openai.com/index/ai-clinical-copilot-penda-health/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Laut einer gemeinsamen Untersuchung von OpenAI und Penda Health war die Nutzung des klinischen Copiloten AI Consult bei 39.849 Besuchen mit weniger Fehlern bei Anamnese, Untersuchungen, Diagnosen und Behandlungen verbunden. Eine aktive Einführung mit Coaching ging mit weniger unbeachteten roten Warnungen einher. Bei den gemessenen Patientenergebnissen zeigte sich kein statistisch signifikanter Unterschied; weitere Forschung ist nötig.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 46 % | 87 / 99 % | – | 97 / 98 % | 48 / 72 % | 10 / 28 % | 34 / 57 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 39 / 55 % | 94 / 99 % | – | 91 / 93 % | 49 / 70 % | 26 / 45 % | 48 / 67 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 59 / 97 % | – | 93 / 95 % | 45 / 66 % | 0 / 0 % | 15 / 28 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 57 / 90 % | – | 89 / 93 % | 19 / 39 % | 5 / 14 % | 24 / 42 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 76 / 93 % | – | 83 / 90 % | 16 / 42 % | 1 / 6 % | 6 / 13 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 15 / 60 % | – | 80 / 89 % | 7 / 17 % | 1 / 4 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 19 / 73 % | – | 68 / 77 % | 7 / 19 % | 0 / 0 % | 9 / 16 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 30 / 69 % | – | 64 / 73 % | 17 / 43 % | 1 / 5 % | 10 / 21 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 44 / 76 % | – | 59 / 66 % | 21 / 42 % | 3 / 12 % | 22 / 37 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 49 / 83 % | – | 57 / 62 % | 38 / 59 % | 6 / 17 % | 17 / 30 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 2 / 23 % | – | 0 / 0 % | 55 / 74 % | 3 / 11 % | 6 / 13 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 55 / 72 % | 8 / 22 % | 1 / 6 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 30 / 56 % | – | 44 / 68 % | 18 / 41 % | 1 / 6 % | 9 / 18 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 27 / 44 % | 18 / 54 % | – | 0 / 0 % | 41 / 68 % | 16 / 37 % | 38 / 61 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 24 / 89 % | – | 39 / 55 % | 15 / 44 % | 1 / 5 % | 7 / 16 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 36 / 58 % | 9 / 25 % | 3 / 11 % | 8 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 33 / 48 % | 30 / 58 % | 6 / 14 % | 15 / 30 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 32 / 83 % | – | 0 / 0 % | 7 / 16 % | 0 / 3 % | 3 / 5 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 10 / 85 % | – | 31 / 60 % | 12 / 31 % | 3 / 11 % | 5 / 13 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 26 / 82 % | – | 30 / 61 % | 19 / 44 % | 2 / 10 % | 10 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 33 % | 23 / 68 % | – | 13 / 38 % | 26 / 51 % | 8 / 25 % | 15 / 31 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 43 % | 0 / 3 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 5 / 47 % | – | 21 / 43 % | 6 / 14 % | 1 / 3 % | 6 / 11 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 19 / 43 % | 3 / 10 % | 7 / 14 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 4 / 30 % | – | 0 / 0 % | 17 / 39 % | 8 / 20 % | 13 / 25 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 56 % | – | 0 / 0 % | 14 / 34 % | 3 / 11 % | 7 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 27 % | 0 / 0 % | 8 / 16 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 1 / 4 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 5 % | 7 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 12 % | 0 / 2 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 2 % | 6 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 3 % | 0 / 0 % |
