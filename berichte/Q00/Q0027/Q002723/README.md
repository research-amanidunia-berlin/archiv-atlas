[English](README.md) · [Deutsch](README.de.md)

# AI co-clinician: researching the path toward AI-augmented care

Report Q002723 · Source deepmind.google · Date 2026-04-30 · [Open original](https://deepmind.google/blog/ai-co-clinician/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind berichtet über Tests eines KI-Systems, das Ärzte bei Evidenzfragen unterstützen und in simulierten Telemedizin-Gesprächen Bild und Ton nutzen soll. Ärzte schnitten in den Gesamtsimulationen besser ab; die Ergebnisse stammen aus Forschungsszenarien und belegen keine Wirksamkeit in der Versorgung. Die Angaben zu den Darstellern der Simulationen sind im Bericht nicht einheitlich.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 48 % | 70 / 94 % | 10 / 20 % | 98 / 99 % | 45 / 70 % | 17 / 34 % | 48 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 41 % | 72 / 93 % | 0 / 0 % | 98 / 99 % | 56 / 76 % | 16 / 36 % | 40 / 64 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 26 / 45 % | 75 / 97 % | 37 / 49 % | 98 / 99 % | 67 / 82 % | 16 / 35 % | 29 / 48 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 46 / 94 % | 0 / 0 % | 93 / 96 % | 11 / 28 % | 3 / 11 % | 9 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 41 / 76 % | 0 / 0 % | 93 / 96 % | 8 / 24 % | 0 / 0 % | 6 / 11 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 46 / 81 % | 0 / 0 % | 83 / 88 % | 36 / 63 % | 7 / 19 % | 31 / 53 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 20 / 39 % | 72 / 96 % | 0 / 0 % | 72 / 82 % | 17 / 43 % | 7 / 31 % | 10 / 31 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 42 / 96 % | 0 / 0 % | 59 / 77 % | 27 / 56 % | 4 / 16 % | 17 / 41 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 55 % | 0 / 0 % | 55 / 67 % | 11 / 31 % | 5 / 13 % | 13 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 50 / 69 % | 8 / 19 % | 1 / 4 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 3 / 42 % | 0 / 0 % | 44 / 72 % | 12 / 33 % | 0 / 0 % | 11 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 43 / 97 % | 0 / 0 % | 11 / 38 % | 7 / 19 % | 2 / 13 % | 5 / 11 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 39 / 92 % | 0 / 0 % | 25 / 59 % | 17 / 41 % | 3 / 9 % | 7 / 22 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 8 / 42 % | 0 / 0 % | 37 / 59 % | 7 / 15 % | 0 / 1 % | 3 / 5 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 9 / 55 % | 0 / 0 % | 34 / 65 % | 19 / 41 % | 0 / 0 % | 7 / 16 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 17 / 39 % | 18 / 87 % | 3 / 6 % | 5 / 31 % | 30 / 54 % | 16 / 33 % | 22 / 41 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 28 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 53 % | 7 / 20 % | 0 / 0 % | 4 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 37 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 2 % | 3 / 7 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 2 / 34 % | 0 / 0 % | 16 / 44 % | 5 / 11 % | 1 / 4 % | 6 / 10 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 31 % | 4 / 12 % | 6 / 13 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 34 % | 3 / 10 % | 5 / 11 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 21 % | 1 / 12 % | 0 / 0 % | 9 / 27 % | 7 / 18 % | 0 / 3 % | 3 / 5 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 4 / 16 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 2 / 34 % | 0 / 0 % | 7 / 19 % | 7 / 18 % | 2 / 9 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 1 % | 5 / 9 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 4 / 6 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 4 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 79 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 7 % |
