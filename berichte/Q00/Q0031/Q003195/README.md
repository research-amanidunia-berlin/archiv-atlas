[English](README.md) · [Deutsch](README.de.md)

# How Third Moment Research runs 10,000 agents for 36+ hours

Report Q003195 · Source openai.com · Date 2026-10-14 · [Open original](https://openai.com/index/third-moment-research/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht schildert Third Moment Researchs Einsatz von OpenAI-Modellen, Codex und Daybreak, um bis zu 10.000 Agenten parallel an längeren Forschungsaufgaben arbeiten zu lassen. Das Unternehmen berichtet unter anderem von einem durch Codex beschleunigten Finanz-Backtest und plant den Ausbau auf Hunderttausende Teilagenten; die Erfolge und Kennzahlen sind im Text nicht unabhängig geprüft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 40 / 60 % | 95 / 97 % | – | 100 / 100 % | 71 / 84 % | 35 / 62 % | 70 / 83 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 43 / 65 % | 96 / 99 % | – | 100 / 100 % | 80 / 89 % | 41 / 64 % | 74 / 84 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 24 / 43 % | 95 / 99 % | – | 82 / 90 % | 25 / 53 % | 15 / 32 % | 43 / 63 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 49 % | 26 / 90 % | – | 94 / 97 % | 38 / 64 % | 17 / 42 % | 40 / 64 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 19 / 47 % | 90 / 98 % | – | 92 / 96 % | 52 / 74 % | 24 / 50 % | 42 / 68 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 23 / 55 % | – | 92 / 96 % | 8 / 24 % | 0 / 0 % | 4 / 8 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 40 / 76 % | – | 75 / 82 % | 10 / 27 % | 1 / 5 % | 7 / 20 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 24 / 47 % | 22 / 75 % | – | 73 / 84 % | 51 / 72 % | 34 / 56 % | 59 / 74 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 22 / 69 % | – | 70 / 85 % | 27 / 51 % | 3 / 12 % | 10 / 22 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 41 % | 50 / 74 % | – | 38 / 60 % | 18 / 40 % | 13 / 31 % | 28 / 55 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 41 / 88 % | – | 37 / 63 % | 16 / 41 % | 3 / 10 % | 9 / 24 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 21 / 53 % | – | 0 / 0 % | 9 / 22 % | 0 / 2 % | 4 / 8 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 20 / 73 % | – | 0 / 0 % | 6 / 14 % | 0 / 2 % | 2 / 5 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 19 / 41 % | 13 / 44 % | – | 4 / 21 % | 10 / 32 % | 3 / 10 % | 7 / 18 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 11 / 34 % | 14 / 45 % | – | 0 / 0 % | 14 / 38 % | 6 / 15 % | 18 / 39 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 6 / 76 % | – | 0 / 0 % | 14 / 40 % | 4 / 16 % | 10 / 30 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 14 / 58 % | – | 0 / 0 % | 8 / 20 % | 1 / 6 % | 3 / 7 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 33 % | 0 / 0 % | 13 / 24 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 27 % | 2 / 8 % | 4 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 10 / 47 % | – | 0 / 0 % | 0 / 0 % | 1 / 2 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 9 / 43 % | – | 0 / 0 % | 7 / 18 % | 1 / 5 % | 7 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 21 % | 0 / 0 % | 4 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 0 / 0 % | 2 / 7 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 64 % | – | 0 / 0 % | 6 / 17 % | 1 / 5 % | 3 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 0 / 1 % | 7 / 18 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 0 / 1 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 21 % | 1 / 3 % | 4 / 7 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 1 % | 4 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 1 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 2 % | 1 / 4 % |
