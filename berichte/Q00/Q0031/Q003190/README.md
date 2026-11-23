[English](README.md) · [Deutsch](README.de.md)

# Cybersecurity Risks of AI-Generated Code

Report Q003190 · Source cset.georgetown.edu · Date 2024-11-01 · [Open original](https://cset.georgetown.edu/publication/cybersecurity-risks-of-ai-generated-code/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Auszug berichtet, dass in einer begrenzten Untersuchung mit fünf Sprachmodellen fast die Hälfte der erzeugten Codeausschnitte Fehler enthielt, die laut Bericht oft folgenreich und möglicherweise ausnutzbar sind. Er sieht Risiken für die Softwarelieferkette und fordert Sicherheitsprüfungen sowie geteilte Verantwortung, weist aber auf begrenzte Tests, ungeeignete Benchmarks und mangelnde Modelltransparenz hin.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 42 % | 67 / 94 % | 97 / 99 % | 33 / 62 % | 9 / 24 % | 33 / 61 % | 16 / 44 % | 42 / 65 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 39 / 63 % | 79 / 97 % | 87 / 95 % | 11 / 29 % | 33 / 59 % | 42 / 69 % | 45 / 78 % | 47 / 72 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 5 / 34 % | 59 / 81 % | 22 / 50 % | 7 / 20 % | 11 / 32 % | 6 / 22 % | 15 / 40 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 26 % | 49 / 96 % | 52 / 68 % | 11 / 35 % | 3 / 13 % | 8 / 23 % | 1 / 6 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 19 / 42 % | 50 / 72 % | 15 / 36 % | 33 / 63 % | 32 / 52 % | 27 / 48 % | 7 / 14 % | 7 / 21 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 49 / 84 % | 40 / 74 % | 14 / 37 % | 7 / 18 % | 13 / 27 % | 5 / 16 % | 21 / 47 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 47 / 83 % | 20 / 37 % | 11 / 32 % | 2 / 14 % | 12 / 32 % | 2 / 9 % | 19 / 43 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 47 / 73 % | 2 / 19 % | 13 / 36 % | 9 / 22 % | 13 / 33 % | 7 / 19 % | 19 / 47 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 15 / 35 % | 45 / 92 % | 30 / 82 % | 38 / 66 % | 13 / 29 % | 33 / 58 % | 15 / 50 % | 12 / 35 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 12 / 66 % | 18 / 41 % | 14 / 37 % | 6 / 23 % | 12 / 36 % | 7 / 27 % | 45 / 66 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 41 / 79 % | 44 / 68 % | 10 / 29 % | 3 / 12 % | 8 / 23 % | 1 / 7 % | 18 / 41 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 41 / 85 % | 16 / 51 % | 8 / 28 % | 2 / 6 % | 6 / 16 % | 0 / 3 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 35 / 73 % | 0 / 0 % | 15 / 36 % | 10 / 22 % | 14 / 40 % | 5 / 16 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 24 / 45 % | 27 / 74 % | 34 / 56 % | 19 / 53 % | 13 / 34 % | 18 / 52 % | 10 / 32 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 20 / 86 % | 33 / 81 % | 10 / 32 % | 1 / 6 % | 8 / 20 % | 0 / 4 % | 17 / 49 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 33 / 65 % | 1 / 25 % | 7 / 22 % | 0 / 0 % | 5 / 15 % | 1 / 5 % | 11 / 33 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 33 / 53 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 13 / 60 % | 23 / 62 % | 19 / 47 % | 3 / 11 % | 6 / 15 % | 2 / 8 % | 10 / 32 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 21 / 80 % | 2 / 12 % | 9 / 27 % | 3 / 13 % | 6 / 16 % | 1 / 4 % | 5 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 42 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 8 % | 13 / 28 % | 1 / 4 % | 17 / 40 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 15 / 53 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 4 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 14 / 65 % | 0 / 0 % | 10 / 37 % | 1 / 4 % | 6 / 19 % | 1 / 5 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 13 / 37 % | 8 / 75 % | 1 / 13 % | 11 / 32 % | 6 / 15 % | 6 / 20 % | 2 / 19 % | 6 / 27 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 11 / 50 % | 1 / 13 % | 9 / 22 % | 2 / 9 % | 7 / 14 % | 0 / 0 % | 3 / 18 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 35 % | 4 / 13 % | 6 / 16 % | 1 / 7 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 10 / 36 % | 0 / 0 % | 6 / 16 % | 2 / 8 % | 7 / 18 % | 0 / 3 % | 5 / 18 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 59 % | 0 / 0 % | 6 / 12 % | 1 / 4 % | 5 / 9 % | 0 / 0 % | 1 / 8 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 2 / 9 % | 9 / 22 % | 0 / 4 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 24 % | 2 / 9 % | 8 / 24 % | 0 / 2 % | 1 / 10 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 1 / 6 % | 6 / 15 % | 0 / 3 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 4 / 56 % | 0 / 0 % | 7 / 18 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 3 % | 6 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 2 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
