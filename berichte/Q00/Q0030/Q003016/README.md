[English](README.md) · [Deutsch](README.de.md)

# Google DeepMind at NeurIPS 2024

Report Q003016 · Source deepmind.google · Date 2024-12-05 · [Open original](https://deepmind.google/blog/google-deepmind-at-neurips-2024/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind kündigt für NeurIPS 2024 mehr als 100 Arbeiten zu KI-Agenten, 3D-Erstellung und Sprachmodelltraining an. Der Beitrag beschreibt unter anderem neue Datensätze und Verfahren und berichtet teils erhebliche Leistungs- und Effizienzgewinne, liefert jedoch nur wenige ausführliche Versuchsdaten oder Einschränkungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 25 / 42 % | 36 / 79 % | 66 / 87 % | 24 / 53 % | 6 / 21 % | 14 / 40 % | 3 / 14 % | 20 / 39 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 41 % | 51 / 79 % | 65 / 89 % | 28 / 55 % | 6 / 23 % | 15 / 36 % | 9 / 34 % | 15 / 40 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 25 / 45 % | 23 / 70 % | 53 / 75 % | 26 / 55 % | 4 / 18 % | 16 / 43 % | 6 / 17 % | 12 / 28 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 15 / 43 % | 45 / 88 % | 19 / 43 % | 8 / 28 % | 1 / 7 % | 10 / 20 % | 1 / 4 % | 14 / 34 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 26 / 48 % | 44 / 63 % | 34 / 63 % | 8 / 24 % | 35 / 58 % | 6 / 19 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 29 / 72 % | 21 / 34 % | 12 / 38 % | 0 / 0 % | 13 / 29 % | 1 / 6 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 41 % | 2 / 23 % | 27 / 46 % | 10 / 35 % | 0 / 0 % | 11 / 31 % | 2 / 9 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 66 % | 27 / 46 % | 6 / 15 % | 1 / 8 % | 4 / 12 % | 0 / 0 % | 7 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 27 / 54 % | 22 / 52 % | 7 / 22 % | 1 / 8 % | 5 / 13 % | 0 / 1 % | 5 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 12 / 38 % | 26 / 51 % | 8 / 23 % | 1 / 5 % | 6 / 14 % | 0 / 2 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 30 % | 23 / 51 % | 2 / 20 % | 8 / 23 % | 3 / 15 % | 7 / 20 % | 0 / 2 % | 3 / 13 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 15 / 51 % | 2 / 16 % | 7 / 19 % | 1 / 5 % | 9 / 17 % | 0 / 2 % | 5 / 17 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 7 / 19 % | 14 / 32 % | 9 / 23 % | 4 / 13 % | 8 / 19 % | 1 / 5 % | 5 / 15 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 30 % | 4 / 21 % | 3 / 12 % | 8 / 26 % | 0 / 0 % | 6 / 13 % | 0 / 2 % | 7 / 19 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 1 / 19 % | 9 / 25 % | 1 / 7 % | 6 / 15 % | 0 / 2 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 30 % | 0 / 0 % | 8 / 21 % | 1 / 8 % | 7 / 17 % | 1 / 4 % | 8 / 24 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 2 / 10 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 1 / 7 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 56 % | 0 / 0 % | 6 / 15 % | 1 / 8 % | 2 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 2 / 16 % | 0 / 0 % | 6 / 14 % | 0 / 3 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 5 % | 5 / 12 % | 0 / 2 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 2 / 31 % | 3 / 13 % | 6 / 18 % | 1 / 10 % | 3 / 10 % | 0 / 2 % | 6 / 20 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 2 / 4 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 3 % | 6 / 15 % | 0 / 2 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 4 % | 4 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 4 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 2 / 5 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 3 / 5 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 13 % | 5 / 12 % | 1 / 7 % | 3 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 13 % |
