[English](README.md) · [Deutsch](README.de.md)

# Learning through human feedback

Report Q003399 · Source deepmind.google · Date 2017-06-12 · [Open original](https://deepmind.google/blog/learning-through-human-feedback/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt ein Verfahren vor, bei dem Menschen durch den Vergleich kurzer Verhaltensclips ein Belohnungsmodell trainieren, das wiederum einen Reinforcement-Learning-Agenten anleitet. Die Erfolge waren je nach Aufgabe unterschiedlich; zudem kann das System bei zu früh beendetem Feedback seine Belohnung „hacken“ und unerwünschte Strategien entwickeln.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 38 / 56 % | 85 / 99 % | 38 / 64 % | 99 / 100 % | 60 / 77 % | 39 / 61 % | 22 / 40 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 46 % | 22 / 89 % | 2 / 14 % | 86 / 94 % | 17 / 46 % | 15 / 41 % | 6 / 18 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 49 % | 26 / 90 % | 10 / 41 % | 82 / 94 % | 35 / 63 % | 28 / 59 % | 9 / 29 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 23 / 43 % | 71 / 94 % | 2 / 13 % | 81 / 93 % | 19 / 44 % | 12 / 35 % | 9 / 27 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 21 / 51 % | 0 / 3 % | 74 / 89 % | 8 / 19 % | 6 / 15 % | 1 / 7 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 31 / 50 % | 44 / 79 % | 10 / 36 % | 65 / 84 % | 54 / 75 % | 40 / 63 % | 14 / 36 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 13 / 37 % | 20 / 79 % | 10 / 45 % | 41 / 73 % | 40 / 64 % | 11 / 27 % | 7 / 25 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 8 / 35 % | 38 / 78 % | 0 / 4 % | 22 / 48 % | 9 / 24 % | 5 / 11 % | 1 / 7 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 37 / 62 % | 7 / 15 % | 0 / 0 % | 1 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 23 % | 0 / 0 % | 34 / 54 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 89 % | 0 / 3 % | 2 / 9 % | 6 / 14 % | 4 / 12 % | 1 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 82 % | 0 / 3 % | 32 / 50 % | 7 / 20 % | 5 / 16 % | 2 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 11 / 43 % | 1 / 6 % | 9 / 40 % | 30 / 55 % | 5 / 12 % | 3 / 10 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 27 / 72 % | 0 / 3 % | 11 / 26 % | 9 / 24 % | 0 / 0 % | 2 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 23 / 70 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 34 % | 19 / 79 % | 2 / 13 % | 1 / 16 % | 16 / 38 % | 10 / 28 % | 6 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 5 / 59 % | 0 / 0 % | 17 / 51 % | 5 / 12 % | 0 / 0 % | 1 / 3 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 14 / 70 % | 0 / 4 % | 0 / 0 % | 7 / 17 % | 9 / 22 % | 1 / 5 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 13 / 55 % | 0 / 5 % | 13 / 50 % | 11 / 34 % | 6 / 17 % | 2 / 9 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 12 / 30 % | 3 / 50 % | 1 / 5 % | 0 / 0 % | 8 / 20 % | 7 / 16 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 8 / 20 % | 5 / 12 % | 1 / 5 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 0 / 2 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 3 % | 7 / 16 % | 0 / 0 % | 1 / 8 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 3 / 7 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 20 % | 4 / 9 % | 0 / 4 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 5 / 30 % | 7 / 20 % | 5 / 14 % | 2 / 9 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 12 % | 6 / 13 % | 5 / 10 % | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 6 / 15 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 3 / 7 % | 0 / 3 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 2 / 5 % |
