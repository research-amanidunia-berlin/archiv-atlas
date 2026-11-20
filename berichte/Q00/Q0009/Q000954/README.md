[English](README.md) · [Deutsch](README.de.md)

# Embedded Evaluators are necessary for meaningful external testing

Report Q000954 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/blog/embedded-evaluators-are-necessary-for-meaningful-external-testing)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Apollo Research argumentiert, dass unabhängige KI-Prüfungen schon während Training und interner Nutzung mit weitreichendem Zugang stattfinden müssen; Prüfungen am fertigen Modell könnten frühe Risiken wie jene des geschilderten Hugging-Face-Vorfalls verpassen. Der Bericht nennt frühere Erkenntnisse aus vertieften Prüfungen, räumt aber ein, dass Evaluationen ungelöste Ausrichtungsprobleme nicht beheben und sicheres Verhalten unter Beobachtung schwer beurteilen können.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 88 / 93 % | 100 / 100 % | 99 / 100 % | – | 90 / 93 % | – | 97 / 98 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 58 / 72 % | 100 / 100 % | 91 / 98 % | – | 86 / 93 % | – | 90 / 96 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 56 / 74 % | 100 / 100 % | 96 / 98 % | – | 90 / 94 % | – | 83 / 91 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 40 / 60 % | 99 / 100 % | 6 / 13 % | – | 73 / 84 % | – | 28 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 55 / 74 % | 99 / 100 % | 53 / 76 % | – | 88 / 93 % | – | 82 / 92 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 63 / 79 % | 99 / 100 % | 85 / 94 % | – | 46 / 63 % | – | 85 / 93 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 49 / 67 % | 96 / 99 % | 30 / 49 % | – | 85 / 92 % | – | 32 / 56 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 56 / 77 % | 95 / 99 % | 56 / 80 % | – | 89 / 93 % | – | 86 / 94 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 10 / 37 % | 83 / 99 % | 8 / 29 % | – | 40 / 69 % | – | 10 / 30 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 32 / 54 % | 83 / 94 % | 23 / 41 % | – | 55 / 75 % | – | 30 / 54 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 49 % | 79 / 100 % | 1 / 7 % | – | 16 / 41 % | – | 5 / 26 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 60 % | 75 / 96 % | 19 / 46 % | – | 57 / 80 % | – | 38 / 73 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 47 / 72 % | 60 / 97 % | 53 / 84 % | – | 70 / 86 % | – | 33 / 62 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 41 % | 68 / 94 % | 6 / 13 % | – | 30 / 56 % | – | 8 / 26 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 23 / 53 % | 66 / 91 % | 10 / 27 % | – | 44 / 68 % | – | 11 / 31 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 28 / 50 % | 65 / 94 % | 11 / 34 % | – | 40 / 69 % | – | 19 / 43 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 32 / 56 % | 64 / 97 % | 6 / 22 % | – | 59 / 79 % | – | 15 / 34 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 14 / 42 % | 58 / 90 % | 5 / 20 % | – | 20 / 47 % | – | 6 / 18 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 43 % | 54 / 97 % | 9 / 30 % | – | 27 / 56 % | – | 6 / 24 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 53 / 96 % | 10 / 32 % | – | 19 / 41 % | – | 8 / 22 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 9 / 78 % | 2 / 10 % | – | 45 / 70 % | – | 12 / 32 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 43 / 86 % | 1 / 3 % | – | 15 / 40 % | – | 8 / 25 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 9 / 90 % | 5 / 17 % | – | 40 / 65 % | – | 11 / 31 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 37 / 86 % | 1 / 8 % | – | 16 / 38 % | – | 7 / 22 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 36 / 85 % | 1 / 4 % | – | 10 / 24 % | – | 4 / 9 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 38 % | 18 / 80 % | 7 / 27 % | – | 25 / 54 % | – | 7 / 21 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 20 / 53 % | 23 / 92 % | 12 / 52 % | – | 25 / 51 % | – | 23 / 53 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 24 / 63 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 21 / 47 % | – | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 17 / 57 % | 2 / 8 % | – | 14 / 34 % | – | 5 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 9 / 19 % | 0 / 0 % | 3 / 10 % | – | 15 / 37 % | – | 5 / 14 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 15 / 35 % | 0 / 0 % | 6 / 23 % | – | 15 / 39 % | – | 7 / 22 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 14 / 91 % | 0 / 0 % | – | 8 / 21 % | – | 3 / 10 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 12 / 33 % | 0 / 0 % | – | 9 / 23 % | – | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 1 / 4 % | – | 11 / 27 % | – | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 9 / 24 % | – | 6 / 13 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 13 % | – | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 7 / 71 % | 0 / 0 % | – | 5 / 11 % | – | 1 / 4 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 11 % | – | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | – | 0 / 0 % |
