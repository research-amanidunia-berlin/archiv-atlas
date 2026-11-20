[English](README.md) · [Deutsch](README.de.md)

# METR’s GPT-4.5 pre-deployment evaluations

Report Q002575 · Source metr.org · Date 2025-02-27 · [Open original](https://metr.org/blog/2025-02-27-gpt-4-5-evals/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR zufolge lag GPT-4.5 in vorläufigen Autonomie- und RE-Bench-Prüfungen zwischen GPT-4o und o1, wobei das eingesetzte Agentengerüst für o1 optimiert war. METR hält große Risiken vorläufig für unwahrscheinlich, erklärt aber, dass die kurzen Tests sie nicht ausschließen und mögliche Fähigkeitssteigerungen durch Nachtraining oder absichtliches Unterbieten offenbleiben. Der bereitgestellte Auszug endet mit einer abgeschnittenen Bildbeschreibung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 64 % | 97 / 100 % | 85 / 94 % | 95 / 99 % | 58 / 80 % | 80 / 90 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 48 % | 95 / 100 % | 29 / 56 % | 96 / 99 % | 41 / 68 % | 48 / 69 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 42 / 66 % | 69 / 87 % | 45 / 71 % | 94 / 97 % | 36 / 56 % | 41 / 60 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 41 / 63 % | 89 / 99 % | 54 / 78 % | 83 / 96 % | 55 / 78 % | 68 / 81 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 20 / 92 % | 8 / 27 % | 89 / 96 % | 36 / 64 % | 9 / 21 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 49 % | 49 / 97 % | 10 / 37 % | 89 / 96 % | 26 / 57 % | 31 / 59 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 34 / 65 % | 36 / 83 % | 22 / 55 % | 67 / 92 % | 10 / 23 % | 45 / 67 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 53 / 95 % | 1 / 5 % | 66 / 83 % | 11 / 32 % | 8 / 17 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 30 / 50 % | 20 / 82 % | 10 / 27 % | 64 / 83 % | 50 / 74 % | 65 / 79 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 51 % | 56 / 94 % | 5 / 16 % | 65 / 88 % | 30 / 59 % | 36 / 61 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 45 / 96 % | 0 / 4 % | 61 / 76 % | 12 / 33 % | 6 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 13 / 72 % | 0 / 0 % | 48 / 69 % | 8 / 23 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 47 / 86 % | 0 / 4 % | 41 / 69 % | 9 / 24 % | 6 / 16 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 46 % | 28 / 99 % | 6 / 27 % | 46 / 86 % | 27 / 58 % | 25 / 47 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 12 / 38 % | 19 / 61 % | 6 / 17 % | 46 / 68 % | 22 / 48 % | 24 / 41 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 28 % | 0 / 0 % | 45 / 64 % | 9 / 28 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 46 % | 44 / 92 % | 12 / 45 % | 32 / 72 % | 37 / 64 % | 39 / 59 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 39 / 62 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 9 % | 39 / 68 % | 7 / 23 % | 6 / 15 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 32 / 79 % | 1 / 5 % | 0 / 0 % | 17 / 38 % | 9 / 16 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 30 / 61 % | 7 / 17 % | 9 / 19 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 12 / 38 % | 30 / 82 % | 1 / 8 % | 21 / 57 % | 23 / 46 % | 10 / 20 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 4 / 40 % | 0 / 3 % | 29 / 61 % | 9 / 23 % | 7 / 17 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 39 % | 8 / 64 % | 4 / 13 % | 8 / 32 % | 20 / 50 % | 27 / 47 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 5 / 83 % | 3 / 13 % | 0 / 0 % | 9 / 32 % | 24 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 45 % | 16 / 90 % | 1 / 6 % | 24 / 56 % | 13 / 36 % | 14 / 32 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 83 % | 0 / 2 % | 22 / 46 % | 6 / 17 % | 5 / 12 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 20 / 79 % | 1 / 8 % | 1 / 7 % | 8 / 19 % | 7 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 16 / 77 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 7 / 15 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 38 % | 9 / 26 % | 8 / 20 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 10 / 73 % | 0 / 2 % | 0 / 0 % | 6 / 15 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 8 / 18 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 28 % | 8 / 22 % | 5 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 20 % | 0 / 2 % | 0 / 5 % | 6 / 15 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 16 % | 6 / 14 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 4 / 8 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 4 / 9 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 5 / 14 % |
