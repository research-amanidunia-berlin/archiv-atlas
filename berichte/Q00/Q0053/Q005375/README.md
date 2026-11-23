[English](README.md) · [Deutsch](README.de.md)

# Towards algorithm auditing: A research overview

Report Q005375 · Source oecd.ai · Date 2024-07-04 · [Open original](https://oecd.ai/en/wonk/algorithm-auditing-research-overview)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag schlägt wiederkehrende Algorithmus-Audits vor, die Systeme dokumentieren und auf Bias, Wirksamkeit, Robustheit, Datenschutz und Erklärbarkeit prüfen; erkannte Risiken sollen durch passende Maßnahmen verringert und erneut bewertet werden. Eine Prüfung bestätigt laut Text nur die Einhaltung der konkret zugrunde gelegten Vorgaben, weshalb Audits auf einzelne Rechtsrahmen zugeschnitten sein müssen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 23 / 47 % | 98 / 100 % | 88 / 95 % | 43 / 72 % | 32 / 65 % | 47 / 72 % | 31 / 61 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 45 / 62 % | 73 / 99 % | 98 / 100 % | 62 / 83 % | 35 / 64 % | 55 / 79 % | 47 / 83 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 39 / 59 % | 81 / 98 % | 96 / 99 % | 73 / 87 % | 60 / 77 % | 76 / 87 % | 59 / 83 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 30 / 58 % | 31 / 95 % | 82 / 96 % | 46 / 73 % | 15 / 43 % | 35 / 70 % | 16 / 59 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 32 / 53 % | 54 / 91 % | 74 / 92 % | 38 / 69 % | 7 / 20 % | 36 / 65 % | 6 / 22 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 32 / 53 % | 58 / 97 % | 48 / 75 % | 41 / 72 % | 48 / 74 % | 58 / 81 % | 49 / 86 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 14 / 40 % | 43 / 93 % | 49 / 83 % | 18 / 46 % | 17 / 49 % | 30 / 68 % | 23 / 62 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 18 / 38 % | 45 / 87 % | 48 / 74 % | 20 / 47 % | 13 / 41 % | 23 / 56 % | 5 / 26 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 16 / 41 % | 48 / 94 % | 17 / 59 % | 20 / 48 % | 14 / 39 % | 18 / 46 % | 6 / 35 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 31 / 97 % | 47 / 85 % | 17 / 54 % | 5 / 26 % | 16 / 55 % | 4 / 16 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 19 / 86 % | 42 / 70 % | 23 / 58 % | 15 / 40 % | 28 / 61 % | 8 / 30 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 11 / 34 % | 39 / 96 % | 32 / 86 % | 16 / 49 % | 7 / 29 % | 11 / 36 % | 4 / 18 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 20 / 42 % | 39 / 95 % | 16 / 48 % | 23 / 52 % | 13 / 34 % | 23 / 45 % | 7 / 32 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 39 / 97 % | 14 / 60 % | 19 / 46 % | 6 / 16 % | 14 / 31 % | 2 / 9 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 34 % | 37 / 83 % | 25 / 72 % | 14 / 40 % | 7 / 32 % | 12 / 52 % | 2 / 16 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 18 / 68 % | 32 / 61 % | 6 / 16 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 27 / 90 % | 31 / 75 % | 20 / 50 % | 9 / 34 % | 8 / 25 % | 4 / 22 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 36 % | 26 / 94 % | 2 / 32 % | 11 / 35 % | 5 / 21 % | 11 / 33 % | 1 / 10 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 25 / 94 % | 10 / 51 % | 9 / 25 % | 4 / 15 % | 6 / 18 % | 1 / 9 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 15 / 29 % | 22 / 79 % | 24 / 64 % | 11 / 34 % | 3 / 11 % | 8 / 20 % | 0 / 6 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 24 / 96 % | 1 / 21 % | 11 / 31 % | 3 / 15 % | 8 / 19 % | 0 / 4 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 23 / 51 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 49 % | 13 / 76 % | 10 / 36 % | 23 / 53 % | 17 / 46 % | 13 / 33 % | 13 / 46 % | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 20 / 94 % | 2 / 32 % | 10 / 27 % | 4 / 12 % | 6 / 19 % | 1 / 6 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 20 / 62 % | 0 / 0 % | 9 / 31 % | 0 / 0 % | 9 / 23 % | 1 / 6 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 14 / 41 % | 19 / 87 % | 5 / 30 % | 14 / 38 % | 6 / 27 % | 10 / 40 % | 1 / 10 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 18 / 69 % | 0 / 0 % | 7 / 17 % | 2 / 6 % | 5 / 10 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 8 / 26 % | 15 / 94 % | 16 / 52 % | 8 / 30 % | 5 / 19 % | 6 / 20 % | 0 / 5 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 14 / 91 % | 5 / 23 % | 5 / 15 % | 2 / 9 % | 6 / 13 % | 0 / 2 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 13 / 28 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 3 / 16 % | 11 / 29 % | 1 / 6 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 7 / 48 % | 0 / 0 % | 9 / 23 % | 4 / 16 % | 9 / 22 % | 1 / 7 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 80 % | 2 / 18 % | 8 / 22 % | 4 / 18 % | 9 / 29 % | 0 / 4 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 25 % | 2 / 14 % | 7 / 21 % | 0 / 4 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 9 / 34 % | 5 / 68 % | 0 / 6 % | 9 / 25 % | 4 / 12 % | 7 / 20 % | 0 / 6 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 8 / 78 % | 0 / 0 % | 6 / 15 % | 3 / 10 % | 5 / 11 % | 0 / 2 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 6 / 32 % | 7 / 91 % | 1 / 21 % | 8 / 29 % | 2 / 13 % | 4 / 17 % | 1 / 6 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 7 / 29 % | 1 / 44 % | 2 / 26 % | 7 / 19 % | 2 / 9 % | 5 / 13 % | 0 / 2 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 4 / 51 % | 0 / 0 % | 7 / 19 % | 2 / 8 % | 5 / 15 % | 0 / 2 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 1 / 71 % | 0 / 6 % | 7 / 19 % | 0 / 0 % | 5 / 14 % | 0 / 3 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
