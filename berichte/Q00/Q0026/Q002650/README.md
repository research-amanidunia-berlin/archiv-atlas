[English](README.md) · [Deutsch](README.de.md)

# An update on our preliminary evaluations of Claude 3.5 Sonnet and o1

Report Q002650 · Source metr.org · Date 2025-01-31 · [Open original](https://metr.org/blog/2025-01-31-update-sonnet-o1-evals/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR fand in vorläufigen Tests von Claude 3.5 Sonnet (Oktober-Version) und einem Vorab-Checkpoint von o1 keine deutlichen Belege für gefährlich hohe Fähigkeiten. Wegen Einschränkungen bei Agentenaufbau, Testumfang, verfügbaren Informationen und Budgets kann die Organisation solche Fähigkeiten aber nicht ausschließen; sie plant weitere Bewertungen und neue Sicherheitsmethoden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 64 / 81 % | 99 / 100 % | 89 / 97 % | 98 / 100 % | 5 / 16 % | 71 / 82 % | 68 / 85 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 38 / 62 % | 99 / 100 % | 22 / 63 % | 97 / 99 % | 48 / 76 % | 56 / 76 % | 40 / 70 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 49 % | 37 / 95 % | 11 / 44 % | 87 / 94 % | 29 / 60 % | 27 / 60 % | 9 / 32 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 28 / 51 % | 32 / 96 % | 11 / 35 % | 81 / 92 % | 58 / 79 % | 9 / 20 % | 15 / 38 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 15 / 45 % | 67 / 94 % | 8 / 31 % | 75 / 90 % | 40 / 64 % | 19 / 38 % | 4 / 16 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 18 / 42 % | 53 / 93 % | 2 / 11 % | 75 / 88 % | 24 / 51 % | 18 / 36 % | 8 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 31 / 59 % | 49 / 93 % | 42 / 74 % | 52 / 76 % | 60 / 81 % | 55 / 74 % | 16 / 47 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 26 / 55 % | 23 / 92 % | 20 / 66 % | 44 / 82 % | 54 / 79 % | 43 / 68 % | 26 / 51 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 52 / 72 % | 7 / 20 % | 5 / 9 % | 1 / 6 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 21 / 45 % | 32 / 72 % | 8 / 35 % | 23 / 65 % | 44 / 70 % | 35 / 54 % | 7 / 27 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 22 / 48 % | 6 / 41 % | 3 / 12 % | 28 / 52 % | 40 / 67 % | 33 / 53 % | 17 / 41 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 53 % | 0 / 0 % | 5 / 19 % | 28 / 52 % | 28 / 59 % | 10 / 22 % | 9 / 24 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 27 / 60 % | 7 / 29 % | 4 / 12 % | 2 / 9 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 26 / 51 % | 4 / 54 % | 2 / 11 % | 0 / 0 % | 14 / 42 % | 15 / 33 % | 8 / 21 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 26 / 77 % | 0 / 2 % | 11 / 46 % | 6 / 15 % | 5 / 13 % | 1 / 6 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 3 / 37 % | 0 / 0 % | 23 / 42 % | 7 / 25 % | 0 / 0 % | 2 / 8 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 20 / 46 % | 19 / 91 % | 1 / 6 % | 13 / 33 % | 21 / 51 % | 15 / 42 % | 10 / 28 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 19 / 93 % | 0 / 4 % | 4 / 35 % | 10 / 31 % | 5 / 13 % | 2 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 4 / 34 % | 1 / 7 % | 0 / 0 % | 10 / 36 % | 16 / 34 % | 4 / 13 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 49 % | 5 / 12 % | 0 / 0 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 15 / 39 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 8 / 25 % | 13 / 25 % | 3 / 11 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 34 % | 7 / 56 % | 0 / 3 % | 0 / 0 % | 9 / 27 % | 7 / 18 % | 2 / 11 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 6 / 78 % | 1 / 4 % | 1 / 18 % | 8 / 23 % | 0 / 0 % | 2 / 8 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 24 % | 5 / 13 % | 0 / 0 % | 1 / 4 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 0 / 2 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 5 / 11 % | 0 / 3 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 6 / 22 % | 0 / 0 % | 1 / 8 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 21 % | 6 / 15 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 4 / 9 % | 1 / 4 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 1 / 7 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 2 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 4 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 5 / 47 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 1 / 6 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 5 % | 1 / 5 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 34 % | 0 / 0 % | 0 / 0 % | 4 / 12 % | 0 / 0 % | 1 / 6 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 10 % |
