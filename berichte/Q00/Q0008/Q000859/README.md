[English](README.md) · [Deutsch](README.de.md)

# Claude accelerates protein design and analytical chemistry

Report Q000859 · Source anthropic.com · Date 2026-08-18 · [Open original](https://www.anthropic.com/research/Claude-accelerates-protein-design)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic berichtet, Claude habe in Laborversuchen Binder gegen 14 von 15 auswertbaren Proteinzielen entworfen und Routineanalysen von NMR- und LC-MS-Daten in weniger als 25 Minuten erstellt, mit Ergebnissen nahe denen eines Labors. Die Resultate sind begrenzt: Bei einzelnen Zielen scheiterte das Modell, die Proteinmessungen sollen noch genauer bestätigt werden, und Binderentwurf ist nur ein früher Schritt der Arzneimittelentwicklung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 25 / 47 % | 81 / 96 % | – | 98 / 99 % | 68 / 82 % | 0 / 0 % | 48 / 64 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 21 / 44 % | 53 / 88 % | – | 90 / 94 % | 35 / 60 % | 3 / 10 % | 29 / 48 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 31 / 49 % | 85 / 94 % | – | 87 / 91 % | 49 / 69 % | 10 / 21 % | 56 / 68 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 17 / 84 % | – | 84 / 90 % | 8 / 19 % | 0 / 0 % | 5 / 10 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 53 % | 76 / 90 % | – | 73 / 81 % | 47 / 71 % | 0 / 0 % | 60 / 74 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 20 / 44 % | 74 / 93 % | – | 48 / 69 % | 17 / 42 % | 5 / 19 % | 24 / 44 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 21 / 45 % | 52 / 74 % | – | 70 / 81 % | 19 / 40 % | 8 / 16 % | 31 / 45 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 54 / 84 % | – | 67 / 77 % | 6 / 18 % | 1 / 4 % | 8 / 18 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 64 / 75 % | 18 / 39 % | 1 / 5 % | 5 / 10 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 31 / 64 % | – | 62 / 73 % | 24 / 46 % | 4 / 10 % | 21 / 34 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 26 / 50 % | 50 / 79 % | – | 49 / 63 % | 32 / 58 % | 5 / 13 % | 27 / 41 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 36 / 90 % | – | 49 / 62 % | 7 / 22 % | 2 / 7 % | 5 / 10 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 47 / 58 % | 23 / 48 % | 1 / 5 % | 16 / 29 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 38 / 66 % | – | 0 / 0 % | 23 / 49 % | 0 / 5 % | 11 / 23 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 37 / 50 % | 7 / 19 % | 1 / 5 % | 4 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 34 / 51 % | 9 / 25 % | 0 / 0 % | 14 / 22 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 15 / 41 % | 20 / 51 % | – | 0 / 0 % | 31 / 58 % | 2 / 7 % | 16 / 28 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 44 % | 3 / 9 % | 18 / 30 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 22 / 32 % | 6 / 13 % | 0 / 0 % | 3 / 5 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 12 / 36 % | 0 / 0 % | – | 0 / 0 % | 21 / 43 % | 4 / 11 % | 21 / 35 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 38 % | 0 / 0 % | – | 0 / 0 % | 9 / 27 % | 0 / 2 % | 14 / 26 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 16 / 62 % | – | 15 / 32 % | 12 / 36 % | 1 / 5 % | 9 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 5 / 14 % | 16 / 38 % | 5 / 11 % | 7 / 14 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 14 / 39 % | – | 0 / 0 % | 6 / 17 % | 1 / 6 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 1 / 3 % | 12 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 24 % | 1 / 6 % | 5 / 11 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 1 % | 8 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 0 / 0 % | 6 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 13 % | 0 / 0 % | 4 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 0 / 1 % | 5 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 1 / 3 % | 0 / 0 % |
