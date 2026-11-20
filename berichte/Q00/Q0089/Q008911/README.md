[English](README.md) · [Deutsch](README.de.md)

# Function calling and other API updates

Report Q008911 · Source openai.com · Date 2023-06-13 · [Open original](https://openai.com/index/function-calling-and-other-api-updates/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht kündigt für 2023 Function Calling, längere Kontexte, besser steuerbare Modelle und niedrigere Preise für Teile der API an. Er benennt zugleich Sicherheitsrisiken durch nicht vertrauenswürdige Tool-Ausgaben sowie Grenzen der Modellbewertung: Einzelne Aufgaben können sich verschlechtern, auch wenn die meisten Kennzahlen steigen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 22 / 40 % | 93 / 99 % | – | 99 / 100 % | 41 / 66 % | 31 / 49 % | 6 / 17 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 29 / 44 % | 93 / 96 % | – | 79 / 88 % | 52 / 72 % | 27 / 36 % | 14 / 27 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 26 / 46 % | 78 / 89 % | – | 88 / 96 % | 51 / 71 % | 41 / 60 % | 12 / 28 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 23 / 40 % | 52 / 83 % | – | 84 / 91 % | 25 / 57 % | 29 / 51 % | 7 / 15 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 52 / 76 % | – | 84 / 90 % | 14 / 32 % | 15 / 27 % | 4 / 11 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 49 / 84 % | – | 81 / 88 % | 10 / 27 % | 12 / 26 % | 3 / 8 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 28 / 66 % | – | 69 / 78 % | 17 / 47 % | 20 / 43 % | 2 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 29 % | 42 / 81 % | – | 63 / 77 % | 20 / 42 % | 36 / 53 % | 9 / 19 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 35 / 95 % | – | 54 / 69 % | 7 / 19 % | 0 / 0 % | 2 / 7 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 49 / 71 % | 5 / 12 % | 0 / 0 % | 0 / 2 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 30 % | 41 / 73 % | – | 12 / 27 % | 8 / 17 % | 7 / 12 % | 1 / 4 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 10 / 23 % | 41 / 71 % | – | 0 / 0 % | 10 / 24 % | 8 / 16 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 10 / 32 % | 26 / 65 % | – | 36 / 65 % | 13 / 31 % | 16 / 31 % | 5 / 11 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 18 / 45 % | – | 32 / 46 % | 21 / 40 % | 27 / 37 % | 7 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 14 / 28 % | 0 / 0 % | – | 28 / 60 % | 17 / 41 % | 14 / 26 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 10 / 27 % | 19 / 45 % | – | 19 / 29 % | 24 / 46 % | 7 / 16 % | 3 / 10 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 21 / 48 % | – | 0 / 0 % | 11 / 26 % | 14 / 22 % | 4 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 9 / 36 % | – | 19 / 38 % | 8 / 22 % | 0 / 0 % | 2 / 7 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 18 / 52 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 16 / 46 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 28 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 7 / 13 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 12 / 30 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 7 / 14 % | 1 / 4 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 9 / 48 % | – | 0 / 0 % | 12 / 39 % | 9 / 27 % | 1 / 5 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 31 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 11 / 25 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 10 / 20 % | 1 / 2 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 28 % | 6 / 12 % | 3 / 6 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 9 / 27 % | 6 / 37 % | – | 0 / 0 % | 10 / 29 % | 8 / 18 % | 1 / 4 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 25 % | 8 / 16 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 5 / 8 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % | 1 / 3 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 5 / 8 % | 1 / 3 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 2 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 2 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 6 / 11 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 5 / 10 % | 0 / 0 % |
