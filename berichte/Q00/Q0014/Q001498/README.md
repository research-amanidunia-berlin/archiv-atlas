[English](README.md) · [Deutsch](README.de.md)

# Investigating models for misalignment

Report Q001498 · Source aisi.gov.uk · Date 2025-11-26 · [Open original](https://www.aisi.gov.uk/blog/investigating-models-for-misalignment)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AISI berichtet, dass es bei Tests von drei Anthropic-Modellen in simulierten KI-Forschungsumgebungen keine Fälle von Forschungssabotage fand; zwei Modelle verweigerten jedoch häufig bestimmte Sicherheitsforschungsaufgaben. Die Tests verringerten die Erkennbarkeit der Evaluation durch den simulierten Einsatzkontext, beseitigten sie aber nicht vollständig, und der Bericht betont, dass die Methode mögliche gezielte oder seltene Sabotage übersehen könnte.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 45 / 68 % | 90 / 100 % | – | 99 / 100 % | 55 / 78 % | 68 / 83 % | 47 / 73 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 58 / 77 % | 94 / 100 % | – | 99 / 100 % | 80 / 89 % | 83 / 90 % | 77 / 88 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 52 / 70 % | 48 / 83 % | – | 95 / 98 % | 81 / 90 % | 84 / 91 % | 75 / 88 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 59 % | 46 / 96 % | – | 93 / 98 % | 39 / 67 % | 40 / 71 % | 18 / 50 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 29 / 60 % | 23 / 72 % | – | 91 / 97 % | 10 / 26 % | 30 / 58 % | 8 / 28 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 24 / 53 % | 62 / 96 % | – | 86 / 90 % | 32 / 54 % | 24 / 39 % | 10 / 25 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 25 / 55 % | 56 / 90 % | – | 63 / 86 % | 31 / 61 % | 31 / 58 % | 12 / 37 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 47 % | 11 / 79 % | – | 58 / 81 % | 26 / 49 % | 18 / 36 % | 7 / 17 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 31 / 57 % | 30 / 96 % | – | 53 / 70 % | 23 / 51 % | 20 / 37 % | 10 / 26 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 25 / 49 % | 15 / 63 % | – | 50 / 78 % | 33 / 59 % | 14 / 32 % | 5 / 18 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 47 % | 39 / 85 % | – | 50 / 82 % | 35 / 61 % | 16 / 36 % | 6 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 3 / 35 % | – | 46 / 71 % | 23 / 49 % | 6 / 14 % | 4 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 9 / 51 % | – | 42 / 64 % | 11 / 33 % | 6 / 12 % | 5 / 12 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 21 / 56 % | 0 / 0 % | – | 20 / 37 % | 27 / 53 % | 9 / 20 % | 10 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 25 / 47 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 19 / 66 % | – | 0 / 0 % | 5 / 10 % | 5 / 9 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 19 / 61 % | – | 8 / 36 % | 6 / 16 % | 3 / 8 % | 1 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 4 / 52 % | – | 11 / 27 % | 18 / 44 % | 7 / 19 % | 4 / 18 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 48 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 8 / 17 % | 1 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 12 / 43 % | 15 / 75 % | – | 6 / 44 % | 16 / 48 % | 10 / 25 % | 5 / 17 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 13 / 37 % | 12 / 32 % | 12 / 22 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 38 % | 1 / 66 % | – | 1 / 9 % | 9 / 26 % | 8 / 24 % | 4 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 3 / 6 % | 1 / 4 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 8 / 30 % | 6 / 18 % | 3 / 8 % | 1 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 6 / 11 % | 1 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 2 / 4 % | 1 / 4 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 4 / 8 % | 1 / 5 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 3 / 7 % | 1 / 6 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 4 / 20 % | 5 / 10 % | 5 / 8 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 4 / 9 % | 0 / 3 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 7 % |
