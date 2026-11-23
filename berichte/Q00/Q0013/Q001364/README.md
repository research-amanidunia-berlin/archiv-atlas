[English](README.md) · [Deutsch](README.de.md)

# Introducing Gemini 3.5 Flash Cyber

Report Q001364 · Source deepmind.google · Date 2026-07-21 · [Open original](https://deepmind.google/blog/introducing-gemini-3-5-flash-cyber/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google beschreibt Gemini 3.5 Flash Cyber als schnelles und kostengünstiges Modell zur Schwachstellensuche und -behebung, das über CodeMender zunächst nur ausgewählten Regierungen und Partnern zugänglich sein soll. Der Bericht nennt unter anderem 55 bestätigte einzigartige Funde bei einer V8-Prüfung, weist aber auf Einschränkungen bei den Modellvergleichen hin; die angekündigten Benchmark-Grafiken enthalten im bereitgestellten Text keine konkreten Werte.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 47 / 65 % | 96 / 99 % | 97 / 99 % | 21 / 36 % | 42 / 61 % | 59 / 75 % | 62 / 78 % | 63 / 80 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 41 / 76 % | 93 / 96 % | 31 / 59 % | 0 / 0 % | 21 / 37 % | 3 / 8 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 46 % | 70 / 93 % | 93 / 96 % | 37 / 66 % | 20 / 40 % | 46 / 67 % | 11 / 24 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 72 / 93 % | 92 / 95 % | 35 / 60 % | 8 / 25 % | 22 / 43 % | 9 / 25 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 28 / 45 % | 33 / 59 % | 85 / 91 % | 51 / 70 % | 19 / 38 % | 14 / 25 % | 29 / 44 % | 14 / 31 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 32 / 77 % | 82 / 88 % | 10 / 30 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 46 / 74 % | 81 / 86 % | 13 / 35 % | 2 / 7 % | 10 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 15 / 84 % | 81 / 85 % | 9 / 28 % | 3 / 12 % | 9 / 18 % | 1 / 4 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 68 / 92 % | 76 / 83 % | 13 / 34 % | 7 / 15 % | 14 / 30 % | 2 / 5 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 74 / 84 % | 33 / 57 % | 6 / 14 % | 8 / 18 % | 2 / 7 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 51 / 84 % | 73 / 85 % | 26 / 49 % | 5 / 15 % | 16 / 32 % | 7 / 26 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 69 / 76 % | 7 / 22 % | 1 / 7 % | 6 / 13 % | 0 / 2 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 64 / 78 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 60 / 71 % | 7 / 21 % | 2 / 8 % | 5 / 11 % | 1 / 5 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 8 / 38 % | 50 / 63 % | 18 / 40 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 11 / 24 % | 0 / 0 % | 45 / 54 % | 12 / 33 % | 5 / 14 % | 14 / 28 % | 2 / 6 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 30 % | 43 / 76 % | 43 / 59 % | 9 / 28 % | 1 / 6 % | 11 / 23 % | 0 / 3 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 41 / 62 % | 31 / 57 % | 0 / 0 % | 14 / 27 % | 4 / 12 % | 15 / 32 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 39 / 56 % | 17 / 41 % | 5 / 14 % | 9 / 18 % | 2 / 7 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 37 / 88 % | 8 / 17 % | 10 / 30 % | 0 / 0 % | 10 / 22 % | 0 / 2 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 33 / 63 % | 0 / 0 % | 6 / 14 % | 2 / 7 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 18 / 36 % | 23 / 77 % | 24 / 52 % | 21 / 45 % | 7 / 19 % | 9 / 26 % | 4 / 19 % | 6 / 22 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 16 / 44 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 23 % | 8 / 39 % | 0 / 0 % | 9 / 24 % | 5 / 14 % | 8 / 18 % | 0 / 3 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 1 / 7 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 2 / 11 % | 7 / 16 % | 1 / 7 % | 8 / 21 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 5 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 6 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
