[English](README.md) · [Deutsch](README.de.md)

# BigCode: toward open AI governance processes in LLMs for coding

Report Q006044 · Source oecd.ai · Date 2023-08-08 · [Open original](https://oecd.ai/en/wonk/bigcode)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht schildert BigCodes offene Governance für Code-Sprachmodelle: Dazu gehören ein Datensatz mit Opt-out- und Wartungsverfahren, ein Werkzeug zur Prüfung möglicher Trainingsdaten-Übereinstimmungen sowie Datenschutzmaßnahmen und eine Lizenz mit Nutzungsauflagen. Er nennt außerdem Kennzahlen zur PII-Erkennung und zu Trainingsemissionen; diese beruhen auf den im Bericht beschriebenen Methoden und Annahmen. Eine Governance Card soll die Entscheidungen dokumentieren und anderen Projekten als Orientierung dienen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 74 / 85 % | 100 / 100 % | 94 / 97 % | 100 / 100 % | 90 / 94 % | 88 / 93 % | 88 / 93 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 61 / 79 % | 100 / 100 % | 74 / 88 % | 96 / 99 % | 77 / 87 % | 65 / 80 % | 78 / 88 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 42 / 64 % | 99 / 100 % | 35 / 64 % | 100 / 100 % | 61 / 78 % | 44 / 67 % | 48 / 70 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 35 / 56 % | 91 / 99 % | 27 / 58 % | 99 / 100 % | 51 / 74 % | 30 / 55 % | 50 / 72 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 38 / 58 % | 94 / 98 % | 19 / 46 % | 99 / 100 % | 48 / 69 % | 53 / 76 % | 38 / 63 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 69 / 94 % | 1 / 4 % | 94 / 96 % | 7 / 22 % | 4 / 13 % | 7 / 15 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 45 / 66 % | 87 / 96 % | 16 / 45 % | 91 / 96 % | 54 / 73 % | 36 / 60 % | 26 / 49 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 18 / 41 % | 28 / 97 % | 4 / 20 % | 87 / 96 % | 23 / 48 % | 13 / 37 % | 15 / 38 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 32 / 53 % | 85 / 99 % | 7 / 28 % | 72 / 85 % | 19 / 51 % | 41 / 65 % | 39 / 66 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 31 / 55 % | 85 / 99 % | 16 / 44 % | 79 / 88 % | 31 / 57 % | 41 / 64 % | 32 / 56 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 35 / 57 % | 82 / 97 % | 12 / 23 % | 44 / 65 % | 41 / 64 % | 10 / 24 % | 42 / 57 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 75 / 97 % | 20 / 31 % | 55 / 69 % | 31 / 56 % | 37 / 55 % | 36 / 52 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 73 / 93 % | 5 / 10 % | 0 / 0 % | 40 / 64 % | 11 / 24 % | 15 / 27 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 33 / 76 % | 0 / 3 % | 62 / 81 % | 7 / 18 % | 1 / 7 % | 2 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 60 / 98 % | 0 / 2 % | 29 / 62 % | 10 / 25 % | 3 / 14 % | 5 / 13 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 10 / 77 % | 9 / 18 % | 56 / 73 % | 22 / 41 % | 26 / 46 % | 40 / 55 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 33 / 93 % | 2 / 6 % | 53 / 79 % | 12 / 32 % | 6 / 17 % | 6 / 16 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 34 / 71 % | 0 / 0 % | 50 / 76 % | 6 / 13 % | 2 / 5 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 23 % | 45 / 92 % | 0 / 2 % | 31 / 59 % | 7 / 17 % | 1 / 8 % | 7 / 15 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 6 / 46 % | 1 / 4 % | 13 / 40 % | 45 / 66 % | 7 / 20 % | 8 / 18 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 45 / 77 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 27 / 81 % | 26 / 40 % | 10 / 31 % | 38 / 59 % | 26 / 48 % | 44 / 62 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 42 / 94 % | 3 / 10 % | 7 / 26 % | 11 / 29 % | 7 / 19 % | 8 / 18 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 16 / 45 % | 1 / 3 % | 40 / 64 % | 11 / 27 % | 2 / 8 % | 7 / 16 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 28 / 64 % | 0 / 2 % | 36 / 64 % | 9 / 21 % | 3 / 9 % | 5 / 12 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 34 / 72 % | 0 / 3 % | 9 / 29 % | 6 / 15 % | 4 / 12 % | 7 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 34 / 81 % | 1 / 5 % | 0 / 5 % | 7 / 15 % | 5 / 16 % | 6 / 14 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 33 % | 8 / 60 % | 2 / 6 % | 28 / 50 % | 7 / 20 % | 6 / 17 % | 11 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 21 / 57 % | 5 / 16 % | 25 / 45 % | 14 / 37 % | 14 / 34 % | 8 / 22 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 24 / 79 % | 1 / 7 % | 0 / 0 % | 7 / 18 % | 6 / 17 % | 7 / 17 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 8 / 21 % | 5 / 17 % | 11 / 24 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 3 / 10 % | 7 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 7 / 17 % | 6 / 18 % | 7 / 15 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 7 / 57 % | 0 / 0 % | 2 / 8 % | 5 / 14 % | 2 / 10 % | 4 / 11 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % | 7 / 20 % | 3 / 10 % | 6 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 7 % | 4 / 9 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 0 / 0 % |
