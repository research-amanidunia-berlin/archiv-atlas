[English](README.md) · [Deutsch](README.de.md)

# OpenAI o1 System Card

Report Q009438 · Source arxiv.org · Date – · [Open original](https://arxiv.org/pdf/2412.16720)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, dass o1 bei vielen Sicherheitstests besser abschnitt als frühere Vergleichsmodelle, zugleich aber in gezielten Szenarien Risiken wie überzeugende Manipulation, Täuschung und Unterstützung bei biologischer Bedrohungsplanung zeigte. Das Unternehmen stuft o1 insgesamt als mittleres Risiko ein und betont, dass die Tests nur bestimmte Modellstände und eine Untergrenze möglicher Risiken abbilden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 59 / 75 % | 100 / 100 % | – | – | 86 / 92 % | – | 76 / 86 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 57 / 75 % | 99 / 100 % | – | – | 87 / 92 % | – | 41 / 60 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 65 / 79 % | 99 / 100 % | – | – | 82 / 90 % | – | 74 / 85 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 49 / 68 % | 97 / 99 % | – | – | 77 / 88 % | – | 73 / 85 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 42 / 63 % | 97 / 100 % | – | – | 70 / 85 % | – | 12 / 27 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 66 / 78 % | 96 / 97 % | – | – | 91 / 95 % | – | 34 / 54 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 31 / 49 % | 95 / 99 % | – | – | 60 / 80 % | – | 31 / 52 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 39 / 62 % | 90 / 97 % | – | – | 76 / 88 % | – | 25 / 47 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 49 / 67 % | 90 / 98 % | – | – | 81 / 90 % | – | 16 / 38 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 30 / 52 % | 90 / 100 % | – | – | 48 / 71 % | – | 18 / 33 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 30 / 49 % | 90 / 99 % | – | – | 56 / 74 % | – | 16 / 29 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 52 / 71 % | 85 / 94 % | – | – | 86 / 92 % | – | 82 / 92 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 53 / 69 % | 82 / 97 % | – | – | 84 / 91 % | – | 57 / 77 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 33 / 55 % | 77 / 95 % | – | – | 73 / 87 % | – | 20 / 39 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 59 / 93 % | – | – | 12 / 29 % | – | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 33 / 54 % | 0 / 0 % | – | – | 56 / 76 % | – | 13 / 28 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 21 / 44 % | 55 / 96 % | – | – | 31 / 55 % | – | 10 / 23 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 54 / 88 % | – | – | 12 / 31 % | – | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 54 / 88 % | – | – | 21 / 45 % | – | 5 / 12 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 53 / 85 % | – | – | 18 / 44 % | – | 6 / 15 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 49 / 92 % | – | – | 14 / 31 % | – | 5 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 33 / 56 % | 42 / 82 % | – | – | 35 / 63 % | – | 15 / 32 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 38 / 69 % | – | – | 17 / 40 % | – | 4 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 37 / 72 % | – | – | 7 / 17 % | – | 3 / 6 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 35 / 70 % | – | – | 13 / 32 % | – | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 33 / 58 % | 0 / 0 % | – | – | 26 / 51 % | – | 11 / 33 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 32 / 68 % | – | – | 14 / 31 % | – | 1 / 4 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 24 / 94 % | – | – | 23 / 45 % | – | 3 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | – | 24 / 48 % | – | 7 / 18 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 19 / 30 % | 0 / 0 % | – | – | 14 / 29 % | – | 2 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 19 / 80 % | – | – | 9 / 21 % | – | 3 / 9 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 16 / 47 % | – | – | 11 / 23 % | – | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | – | 15 / 33 % | – | 3 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | – | 14 / 33 % | – | 8 / 19 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 9 / 48 % | – | – | 13 / 30 % | – | 5 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 11 / 26 % | 0 / 0 % | – | – | 11 / 25 % | – | 6 / 15 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | – | 11 / 20 % | – | 2 / 8 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | – | 8 / 17 % | – | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | – | 7 / 16 % | – | 1 / 4 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | – | 6 / 12 % | – | 0 / 0 % |
