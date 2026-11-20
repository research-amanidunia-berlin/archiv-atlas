[English](README.md) · [Deutsch](README.de.md)

# Building safer dialogue agents

Report Q002557 · Source deepmind.google · Date 2022-09-22 · [Open original](https://deepmind.google/blog/building-safer-dialogue-agents/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

DeepMind stellt Sparrow als Forschungsmodell vor, das durch menschliches Feedback hilfreiche Antworten lernen und mit vorläufigen Regeln riskantes Verhalten begrenzen soll. Laut den Teilnehmenden waren Faktenantworten in 78 Prozent der Fälle plausibel und belegt; dennoch blieben Fehler, Regelverstöße und offene Fragen zu Regeln sowie zur Übertragbarkeit auf andere Sprachen und Kulturen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 35 / 56 % | 86 / 94 % | 31 / 61 % | 99 / 100 % | 74 / 86 % | 64 / 78 % | 47 / 67 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 42 / 61 % | 88 / 99 % | 29 / 64 % | 99 / 100 % | 67 / 83 % | 56 / 77 % | 32 / 59 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 45 / 61 % | 98 / 100 % | 36 / 60 % | 97 / 99 % | 63 / 80 % | 50 / 68 % | 47 / 66 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 52 % | 31 / 66 % | 7 / 25 % | 97 / 99 % | 41 / 68 % | 38 / 59 % | 14 / 34 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 31 / 54 % | 52 / 91 % | 5 / 22 % | 96 / 99 % | 40 / 64 % | 14 / 32 % | 7 / 22 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 7 / 28 % | 39 / 86 % | 1 / 6 % | 90 / 95 % | 25 / 50 % | 15 / 32 % | 7 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 29 / 48 % | 53 / 87 % | 8 / 24 % | 87 / 95 % | 26 / 49 % | 19 / 41 % | 13 / 33 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 73 / 91 % | 0 / 2 % | 75 / 90 % | 9 / 31 % | 10 / 20 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 13 / 34 % | 37 / 77 % | 5 / 19 % | 73 / 89 % | 46 / 70 % | 11 / 27 % | 8 / 24 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 13 / 30 % | 24 / 81 % | 0 / 3 % | 63 / 80 % | 8 / 22 % | 10 / 22 % | 5 / 14 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 45 / 84 % | 1 / 6 % | 61 / 76 % | 29 / 54 % | 8 / 20 % | 7 / 23 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 59 / 76 % | 11 / 29 % | 4 / 9 % | 3 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 12 / 35 % | 37 / 93 % | 0 / 3 % | 33 / 67 % | 15 / 41 % | 6 / 14 % | 3 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 36 % | 35 / 74 % | 0 / 1 % | 27 / 53 % | 7 / 20 % | 5 / 9 % | 1 / 6 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 28 / 58 % | 0 / 0 % | 7 / 38 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 14 / 27 % | 17 / 48 % | 1 / 8 % | 26 / 56 % | 19 / 43 % | 8 / 19 % | 5 / 16 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 25 / 72 % | 1 / 4 % | 21 / 60 % | 7 / 17 % | 6 / 11 % | 2 / 8 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 10 / 26 % | 0 / 0 % | 0 / 0 % | 24 / 55 % | 8 / 24 % | 6 / 16 % | 4 / 16 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 33 % | 8 / 68 % | 0 / 4 % | 17 / 39 % | 8 / 26 % | 10 / 21 % | 3 / 10 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 12 / 75 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 30 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 7 / 14 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 10 / 36 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 3 / 8 % | 1 / 7 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 29 % | 9 / 67 % | 0 / 3 % | 0 / 0 % | 8 / 22 % | 7 / 20 % | 4 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 3 / 73 % | 0 / 0 % | 2 / 11 % | 5 / 12 % | 7 / 16 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 6 / 48 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 2 / 4 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 5 / 9 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 5 / 10 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 6 / 41 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 3 / 77 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 3 / 11 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 9 % | 1 / 5 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 5 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 1 / 23 % | 0 / 0 % | 0 / 2 % | 5 / 13 % | 0 / 0 % | 1 / 8 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 5 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 8 % | 0 / 0 % |
