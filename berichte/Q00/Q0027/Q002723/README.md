[English](README.md) · [Deutsch](README.de.md)

# AI co-clinician: researching the path toward AI-augmented care

Report Q002723 · Source deepmind.google · Date 2026-04-30 · [Open original](https://deepmind.google/blog/ai-co-clinician/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind berichtet über Tests eines KI-Systems, das Ärzte bei Evidenzfragen unterstützen und in simulierten Telemedizin-Gesprächen Bild und Ton nutzen soll. Ärzte schnitten in den Gesamtsimulationen besser ab; die Ergebnisse stammen aus Forschungsszenarien und belegen keine Wirksamkeit in der Versorgung. Die Angaben zu den Darstellern der Simulationen sind im Bericht nicht einheitlich.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 48 % | 70 / 94 % | 10 / 20 % | 98 / 99 % | 45 / 70 % | 48 / 68 % | 17 / 34 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 41 % | 72 / 93 % | 0 / 0 % | 98 / 99 % | 56 / 76 % | 40 / 64 % | 16 / 36 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 26 / 45 % | 75 / 97 % | 37 / 49 % | 98 / 99 % | 67 / 82 % | 29 / 48 % | 16 / 35 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 46 / 94 % | 0 / 0 % | 93 / 96 % | 11 / 28 % | 9 / 22 % | 3 / 11 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 41 / 76 % | 0 / 0 % | 93 / 96 % | 8 / 24 % | 6 / 11 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 46 / 81 % | 0 / 0 % | 83 / 88 % | 36 / 63 % | 31 / 53 % | 7 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 20 / 39 % | 72 / 96 % | 0 / 0 % | 72 / 82 % | 17 / 43 % | 10 / 31 % | 7 / 31 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 42 / 96 % | 0 / 0 % | 59 / 77 % | 27 / 56 % | 17 / 41 % | 4 / 16 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 55 % | 0 / 0 % | 55 / 67 % | 11 / 31 % | 13 / 26 % | 5 / 13 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 50 / 69 % | 8 / 19 % | 0 / 0 % | 1 / 4 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 3 / 42 % | 0 / 0 % | 44 / 72 % | 12 / 33 % | 11 / 18 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 43 / 97 % | 0 / 0 % | 11 / 38 % | 7 / 19 % | 5 / 11 % | 2 / 13 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 39 / 92 % | 0 / 0 % | 25 / 59 % | 17 / 41 % | 7 / 22 % | 3 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 8 / 42 % | 0 / 0 % | 37 / 59 % | 7 / 15 % | 3 / 5 % | 0 / 1 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 9 / 55 % | 0 / 0 % | 34 / 65 % | 19 / 41 % | 7 / 16 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 17 / 39 % | 18 / 87 % | 3 / 6 % | 5 / 31 % | 30 / 54 % | 22 / 41 % | 16 / 33 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 28 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 53 % | 7 / 20 % | 4 / 12 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 37 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 7 % | 0 / 2 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 2 / 34 % | 0 / 0 % | 16 / 44 % | 5 / 11 % | 6 / 10 % | 1 / 4 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 31 % | 6 / 13 % | 4 / 12 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 34 % | 5 / 11 % | 3 / 10 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 21 % | 1 / 12 % | 0 / 0 % | 9 / 27 % | 7 / 18 % | 3 / 5 % | 0 / 3 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 5 / 11 % | 4 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 2 / 34 % | 0 / 0 % | 7 / 19 % | 7 / 18 % | 0 / 0 % | 2 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 5 / 9 % | 0 / 1 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 4 / 6 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 4 / 8 % | 0 / 2 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 79 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 7 % | 0 / 0 % |
