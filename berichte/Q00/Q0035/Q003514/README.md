[English](README.md) · [Deutsch](README.de.md)

# Identifying and eliminating bugs in learned predictive models

Report Q003514 · Source deepmind.google · Date 2019-03-28 · [Open original](https://deepmind.google/blog/identifying-and-eliminating-bugs-in-learned-predictive-models/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt adversariales Testen, robustes Training und formale Verifikation als Ansätze vor, um Fehler in lernenden Modellen aufzudecken oder einzudämmen. Er nennt schnellere Entdeckung seltener Fehler und Fortschritte bei robustem Training, betont aber auch Grenzen: Verifikation kann Eigenschaften mitunter nicht beweisen, und zuverlässige Werkzeuge für den Einsatz in der Praxis sind noch Forschungsbedarf.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 33 / 52 % | 72 / 97 % | 98 / 100 % | 33 / 64 % | 8 / 27 % | 28 / 61 % | 12 / 57 % | 60 / 79 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 32 / 54 % | 65 / 96 % | 76 / 94 % | 35 / 66 % | 20 / 47 % | 35 / 67 % | 16 / 66 % | 17 / 36 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 32 / 54 % | 37 / 92 % | 76 / 90 % | 28 / 61 % | 14 / 34 % | 27 / 64 % | 10 / 42 % | 38 / 61 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 21 / 47 % | 37 / 83 % | 61 / 85 % | 8 / 19 % | 8 / 27 % | 12 / 42 % | 8 / 49 % | 45 / 69 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 22 / 50 % | 54 / 77 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 29 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 18 / 57 % | 0 / 0 % | 33 / 65 % | 11 / 27 % | 39 / 68 % | 11 / 42 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 19 / 44 % | 32 / 94 % | 38 / 85 % | 27 / 57 % | 5 / 19 % | 11 / 30 % | 2 / 25 % | 24 / 50 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 37 / 85 % | 13 / 52 % | 15 / 40 % | 2 / 11 % | 6 / 19 % | 1 / 12 % | 10 / 33 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 33 / 80 % | 11 / 45 % | 7 / 18 % | 1 / 7 % | 6 / 15 % | 0 / 2 % | 9 / 25 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 2 / 8 % | 0 / 0 % | 0 / 3 % | 26 / 51 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 16 / 79 % | 26 / 58 % | 17 / 45 % | 3 / 12 % | 6 / 20 % | 1 / 8 % | 16 / 37 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 20 / 78 % | 7 / 54 % | 16 / 47 % | 3 / 12 % | 9 / 27 % | 1 / 12 % | 11 / 33 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 17 / 69 % | 0 / 0 % | 5 / 12 % | 1 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 16 / 64 % | 0 / 0 % | 7 / 17 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 15 / 88 % | 0 / 0 % | 8 / 24 % | 1 / 5 % | 11 / 29 % | 0 / 2 % | 6 / 22 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 15 / 55 % | 6 / 18 % | 5 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 10 / 75 % | 9 / 44 % | 6 / 16 % | 1 / 4 % | 7 / 15 % | 0 / 2 % | 15 / 41 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 36 % | 2 / 10 % | 6 / 13 % | 1 / 6 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 12 / 72 % | 0 / 6 % | 5 / 11 % | 2 / 8 % | 0 / 0 % | 0 / 2 % | 9 / 32 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 7 % | 6 / 20 % | 1 / 8 % | 3 / 11 % | 0 / 3 % | 10 / 30 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 10 / 63 % | 0 / 0 % | 9 / 28 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 25 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 34 % | 9 / 86 % | 0 / 0 % | 7 / 23 % | 2 / 11 % | 5 / 20 % | 0 / 4 % | 7 / 23 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 7 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 3 / 47 % | 0 / 0 % | 6 / 19 % | 1 / 7 % | 8 / 17 % | 1 / 7 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 4 % | 3 / 7 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 7 / 46 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 3 / 45 % | 0 / 0 % | 6 / 18 % | 2 / 7 % | 7 / 19 % | 0 / 3 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 3 / 40 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 5 / 87 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 26 % | 5 / 14 % | 1 / 9 % | 3 / 9 % | 0 / 3 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 65 % | 0 / 0 % | 5 / 11 % | 1 / 7 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 15 % |
