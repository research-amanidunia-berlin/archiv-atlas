[English](README.md) · [Deutsch](README.de.md)

# METR’s GPT-4.5 pre-deployment evaluations

Report Q002575 · Source metr.org · Date 2025-02-27 · [Open original](https://metr.org/blog/2025-02-27-gpt-4-5-evals/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR zufolge lag GPT-4.5 in vorläufigen Autonomie- und RE-Bench-Prüfungen zwischen GPT-4o und o1, wobei das eingesetzte Agentengerüst für o1 optimiert war. METR hält große Risiken vorläufig für unwahrscheinlich, erklärt aber, dass die kurzen Tests sie nicht ausschließen und mögliche Fähigkeitssteigerungen durch Nachtraining oder absichtliches Unterbieten offenbleiben. Der bereitgestellte Auszug endet mit einer abgeschnittenen Bildbeschreibung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 64 % | 97 / 100 % | 95 / 99 % | 58 / 80 % | 64 / 84 % | 80 / 90 % | 85 / 94 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 21 / 48 % | 95 / 100 % | 96 / 99 % | 41 / 68 % | 14 / 33 % | 48 / 69 % | 29 / 56 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 42 / 66 % | 69 / 87 % | 94 / 97 % | 36 / 56 % | 47 / 69 % | 41 / 60 % | 45 / 71 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 41 / 63 % | 89 / 99 % | 83 / 96 % | 55 / 78 % | 50 / 70 % | 68 / 81 % | 54 / 78 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 20 / 92 % | 89 / 96 % | 36 / 64 % | 13 / 36 % | 9 / 21 % | 8 / 27 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 49 % | 49 / 97 % | 89 / 96 % | 26 / 57 % | 9 / 31 % | 31 / 59 % | 10 / 37 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 34 / 65 % | 36 / 83 % | 67 / 92 % | 10 / 23 % | 24 / 52 % | 45 / 67 % | 22 / 55 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 53 / 95 % | 66 / 83 % | 11 / 32 % | 1 / 6 % | 8 / 17 % | 1 / 5 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 30 / 50 % | 20 / 82 % | 64 / 83 % | 50 / 74 % | 11 / 27 % | 65 / 79 % | 10 / 27 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 51 % | 56 / 94 % | 65 / 88 % | 30 / 59 % | 7 / 22 % | 36 / 61 % | 5 / 16 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 45 / 96 % | 61 / 76 % | 12 / 33 % | 5 / 15 % | 6 / 15 % | 0 / 4 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 13 / 72 % | 48 / 69 % | 8 / 23 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 47 / 86 % | 41 / 69 % | 9 / 24 % | 1 / 7 % | 6 / 16 % | 0 / 4 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 46 % | 28 / 99 % | 46 / 86 % | 27 / 58 % | 5 / 20 % | 25 / 47 % | 6 / 27 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 12 / 38 % | 19 / 61 % | 46 / 68 % | 22 / 48 % | 12 / 32 % | 24 / 41 % | 6 / 17 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 4 / 28 % | 45 / 64 % | 9 / 28 % | 2 / 10 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 46 % | 44 / 92 % | 32 / 72 % | 37 / 64 % | 11 / 32 % | 39 / 59 % | 12 / 45 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 39 / 62 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 39 / 68 % | 7 / 23 % | 3 / 13 % | 6 / 15 % | 1 / 9 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 32 / 79 % | 0 / 0 % | 17 / 38 % | 1 / 7 % | 9 / 16 % | 1 / 5 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 30 / 61 % | 7 / 17 % | 2 / 10 % | 9 / 19 % | 0 / 3 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 12 / 38 % | 30 / 82 % | 21 / 57 % | 23 / 46 % | 3 / 12 % | 10 / 20 % | 1 / 8 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 4 / 40 % | 29 / 61 % | 9 / 23 % | 2 / 9 % | 7 / 17 % | 0 / 3 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 39 % | 8 / 64 % | 8 / 32 % | 20 / 50 % | 8 / 23 % | 27 / 47 % | 4 / 13 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 5 / 83 % | 0 / 0 % | 9 / 32 % | 3 / 13 % | 24 / 46 % | 3 / 13 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 45 % | 16 / 90 % | 24 / 56 % | 13 / 36 % | 1 / 9 % | 14 / 32 % | 1 / 6 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 6 / 83 % | 22 / 46 % | 6 / 17 % | 2 / 9 % | 5 / 12 % | 0 / 2 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 20 / 79 % | 1 / 7 % | 8 / 19 % | 4 / 12 % | 7 / 16 % | 1 / 8 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 16 / 77 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 11 / 38 % | 9 / 26 % | 0 / 3 % | 8 / 20 % | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 10 / 73 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 1 / 7 % | 8 / 18 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 7 / 28 % | 8 / 22 % | 0 / 3 % | 5 / 13 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 20 % | 0 / 5 % | 6 / 15 % | 1 / 6 % | 0 / 0 % | 0 / 2 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 1 / 16 % | 6 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 4 / 8 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 4 / 9 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 2 % | 5 / 14 % | 0 / 0 % | – |
