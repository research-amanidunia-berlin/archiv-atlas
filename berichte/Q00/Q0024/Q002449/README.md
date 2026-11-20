[English](README.md) · [Deutsch](README.de.md)

# An early warning system for novel AI risks

Report Q002449 · Source deepmind.google · Date 2023-05-25 · [Open original](https://deepmind.google/blog/an-early-warning-system-for-novel-ai-risks/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag präsentiert einen vorgeschlagenen Rahmen, der KI-Modelle auf gefährliche Fähigkeiten und mögliche Fehlanpassung prüfen soll, damit Ergebnisse Entscheidungen über Training, Einsatz, Transparenz und Sicherheit unterstützen. Die Prüfungen können laut Text Risiken übersehen, vor allem wenn diese stark von Faktoren außerhalb des Modells abhängen, und müssen deshalb mit weiteren Maßnahmen ergänzt werden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 63 % | 89 / 99 % | 56 / 87 % | 98 / 100 % | 62 / 84 % | 72 / 88 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 24 / 55 % | 94 / 99 % | 49 / 72 % | 78 / 92 % | 54 / 76 % | 51 / 72 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 39 / 65 % | 73 / 98 % | 75 / 93 % | 93 / 98 % | 65 / 84 % | 80 / 90 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 62 % | 86 / 99 % | 71 / 91 % | 75 / 97 % | 46 / 77 % | 73 / 87 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 16 / 53 % | 83 / 99 % | 26 / 72 % | 45 / 92 % | 36 / 68 % | 39 / 70 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 28 / 61 % | 50 / 91 % | 79 / 96 % | 48 / 94 % | 14 / 37 % | 59 / 82 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 27 / 59 % | 31 / 81 % | 60 / 80 % | 61 / 87 % | 64 / 84 % | 79 / 89 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 32 / 59 % | 77 / 96 % | 42 / 69 % | 72 / 96 % | 55 / 80 % | 60 / 80 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 42 % | 17 / 78 % | 10 / 46 % | 76 / 93 % | 33 / 64 % | 20 / 52 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 27 / 59 % | 74 / 94 % | 31 / 62 % | 69 / 90 % | 42 / 66 % | 28 / 53 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 20 / 45 % | 66 / 97 % | 3 / 11 % | 71 / 90 % | 20 / 49 % | 10 / 30 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 9 / 44 % | 69 / 87 % | 22 / 45 % | 14 / 51 % | 24 / 53 % | 18 / 35 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 64 / 94 % | 1 / 11 % | 35 / 71 % | 10 / 29 % | 10 / 38 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 38 / 83 % | 0 / 2 % | 58 / 80 % | 8 / 29 % | 7 / 14 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 27 / 53 % | 55 / 93 % | 23 / 41 % | 23 / 61 % | 27 / 58 % | 24 / 45 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 14 / 45 % | 36 / 84 % | 7 / 32 % | 47 / 84 % | 27 / 54 % | 21 / 49 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 40 % | 45 / 91 % | 2 / 13 % | 22 / 52 % | 15 / 40 % | 20 / 41 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 10 / 40 % | 45 / 90 % | 1 / 9 % | 28 / 73 % | 15 / 38 % | 12 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 12 / 45 % | 45 / 94 % | 8 / 25 % | 23 / 66 % | 27 / 55 % | 25 / 51 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 7 / 34 % | 45 / 89 % | 4 / 24 % | 2 / 40 % | 10 / 32 % | 11 / 30 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 13 / 48 % | 31 / 80 % | 3 / 15 % | 42 / 70 % | 18 / 44 % | 11 / 35 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 19 / 90 % | 11 / 44 % | 27 / 72 % | 41 / 70 % | 9 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 38 / 78 % | 0 / 3 % | 6 / 24 % | 6 / 23 % | 10 / 20 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 40 % | 37 / 85 % | 7 / 19 % | 14 / 46 % | 20 / 48 % | 13 / 36 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 32 / 65 % | 1 / 5 % | 2 / 28 % | 10 / 32 % | 11 / 27 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 26 / 86 % | 1 / 9 % | 5 / 53 % | 12 / 33 % | 6 / 23 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 26 / 69 % | 0 / 0 % | 3 / 28 % | 6 / 20 % | 7 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 32 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 47 % | 8 / 52 % | 6 / 25 % | 7 / 23 % | 9 / 31 % | 15 / 45 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 16 / 71 % | 0 / 3 % | 6 / 36 % | 7 / 16 % | 8 / 21 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 7 / 34 % | 16 / 84 % | 0 / 3 % | 12 / 31 % | 6 / 22 % | 6 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 12 / 68 % | 1 / 6 % | 11 / 40 % | 11 / 34 % | 9 / 26 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 33 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 7 / 22 % | 11 / 26 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 11 / 50 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 6 / 37 % | 2 / 43 % | 0 / 2 % | 10 / 41 % | 6 / 17 % | 6 / 15 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 9 / 25 % | 5 / 20 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 8 / 90 % | 0 / 3 % | 1 / 28 % | 7 / 21 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 94 % | 0 / 3 % | 1 / 12 % | 6 / 16 % | 5 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 5 / 13 % | 6 / 13 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 5 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
