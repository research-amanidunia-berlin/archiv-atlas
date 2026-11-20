[English](README.md) · [Deutsch](README.de.md)

# RepliBench: measuring autonomous replication capabilities in AI systems

Report Q002540 · Source aisi.gov.uk · Date 2025-04-22 · [Open original](https://www.aisi.gov.uk/blog/replibench-measuring-autonomous-replication-capabilities-in-ai-systems)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

RepliBench prüft sieben Frontier-Modelle anhand von Teilaufgaben, die für autonome KI-Replikation nötig sein könnten; keines bestand alle Komponenten. Modelle bewältigten klar definierte Bedienaufgaben vergleichsweise gut, hatten aber Schwierigkeiten mit KYC-Prüfungen, dauerhaften Einsätzen und geschützten Modellgewichten. Der Bericht betont, dass der Benchmark keine durchgängige Replikation testet, und meldet eine intern ungeklärte Abweichung bei der Zahl der Einzelaufgaben: 65 oder 86.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 57 / 77 % | 98 / 100 % | – | 100 / 100 % | 11 / 25 % | 78 / 87 % | 61 / 78 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 27 / 56 % | 51 / 92 % | – | 92 / 97 % | 54 / 73 % | 49 / 66 % | 8 / 25 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 27 / 53 % | 69 / 99 % | – | 91 / 97 % | 40 / 67 % | 43 / 68 % | 16 / 42 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 31 / 55 % | 54 / 96 % | – | 83 / 90 % | 68 / 84 % | 48 / 67 % | 17 / 39 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 40 / 66 % | 76 / 98 % | – | 79 / 87 % | 45 / 68 % | 60 / 74 % | 30 / 54 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 40 / 63 % | 53 / 94 % | – | 77 / 91 % | 57 / 77 % | 54 / 72 % | 20 / 41 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 63 % | 66 / 97 % | – | 72 / 86 % | 40 / 68 % | 53 / 72 % | 31 / 56 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 27 / 52 % | 9 / 55 % | – | 64 / 81 % | 56 / 76 % | 60 / 75 % | 13 / 30 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 70 % | – | 50 / 77 % | 56 / 76 % | 14 / 30 % | 16 / 34 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 11 / 73 % | – | 51 / 70 % | 11 / 30 % | 7 / 12 % | 3 / 9 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 28 / 56 % | 22 / 97 % | – | 38 / 86 % | 50 / 74 % | 40 / 61 % | 15 / 36 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 20 / 47 % | 37 / 82 % | – | 50 / 60 % | 22 / 43 % | 13 / 30 % | 5 / 16 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 49 / 78 % | 12 / 34 % | 7 / 21 % | 3 / 11 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 46 / 94 % | – | 33 / 75 % | 8 / 18 % | 5 / 14 % | 1 / 7 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 40 / 59 % | – | 26 / 40 % | 8 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 7 / 61 % | – | 38 / 63 % | 13 / 35 % | 15 / 31 % | 6 / 16 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 24 / 58 % | – | 10 / 41 % | 34 / 57 % | 16 / 33 % | 7 / 18 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 17 / 49 % | 26 / 66 % | – | 21 / 49 % | 24 / 50 % | 9 / 20 % | 5 / 16 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 41 % | 24 / 89 % | – | 11 / 49 % | 24 / 49 % | 22 / 42 % | 8 / 26 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 23 / 96 % | – | 14 / 67 % | 18 / 40 % | 8 / 22 % | 5 / 13 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 52 % | 0 / 0 % | – | 0 / 0 % | 10 / 33 % | 17 / 35 % | 6 / 16 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 19 / 54 % | – | 6 / 36 % | 9 / 28 % | 8 / 18 % | 1 / 3 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 17 / 48 % | 4 / 48 % | – | 0 / 0 % | 9 / 27 % | 11 / 22 % | 3 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 13 / 60 % | – | 13 / 47 % | 8 / 21 % | 5 / 9 % | 1 / 5 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 12 / 44 % | 6 / 13 % | 6 / 10 % | 1 / 4 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 23 % | 7 / 14 % | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 19 % | 5 / 10 % | 1 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 5 / 54 % | – | 0 / 4 % | 7 / 16 % | 0 / 0 % | 2 / 9 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 10 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 4 / 47 % | – | 0 / 0 % | 5 / 10 % | 6 / 10 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 47 % | – | 0 / 0 % | 6 / 15 % | 3 / 7 % | 2 / 9 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 4 / 7 % | 1 / 6 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 4 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 12 % | 5 / 16 % | 0 / 0 % | 1 / 3 % |
