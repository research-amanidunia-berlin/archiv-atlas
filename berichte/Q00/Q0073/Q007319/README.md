[English](README.md) · [Deutsch](README.de.md)

# Advancing voice intelligence with new models in the API

Report Q007319 · Source openai.com · Date 2026-05-07 · [Open original](https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI stellt drei Realtime-Audiomodelle für Sprachinteraktionen, Liveübersetzung und Transkription vor und nennt neue Funktionen sowie Verbesserungen in ausgewählten Benchmarks. Die Leistungswerte und Praxisbeispiele stammen aus dem Bericht beziehungsweise zitierten Anbieterangaben; unabhängige Überprüfungen und ausführliche Testmethoden werden nicht vorgelegt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 25 / 41 % | 81 / 94 % | – | 96 / 98 % | 58 / 76 % | 48 / 66 % | 14 / 34 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 37 % | 69 / 95 % | – | 92 / 98 % | 49 / 70 % | 33 / 53 % | 11 / 28 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 21 / 53 % | – | 74 / 81 % | 18 / 45 % | 17 / 32 % | 5 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 69 / 86 % | 6 / 14 % | 3 / 5 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 20 / 36 % | 0 / 0 % | – | 62 / 72 % | 19 / 46 % | 17 / 36 % | 8 / 18 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 31 / 55 % | – | 61 / 73 % | 10 / 26 % | 11 / 24 % | 1 / 6 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 20 / 37 % | 30 / 60 % | – | 53 / 59 % | 49 / 68 % | 46 / 59 % | 25 / 41 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 46 / 56 % | 7 / 19 % | 10 / 20 % | 3 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 34 / 76 % | – | 45 / 59 % | 7 / 16 % | 3 / 6 % | 0 / 3 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 23 / 54 % | – | 41 / 58 % | 18 / 46 % | 8 / 23 % | 2 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 39 / 73 % | – | 11 / 32 % | 12 / 29 % | 10 / 21 % | 3 / 9 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 38 / 61 % | 6 / 14 % | 5 / 10 % | 1 / 7 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 38 / 54 % | 9 / 23 % | 5 / 8 % | 1 / 4 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 31 / 48 % | 15 / 23 % | 9 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 13 / 18 % | 18 / 35 % | 27 / 38 % | 7 / 24 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 28 % | 24 / 67 % | – | 0 / 0 % | 6 / 16 % | 2 / 4 % | 0 / 2 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 14 / 65 % | – | 22 / 41 % | 6 / 15 % | 3 / 9 % | 1 / 5 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 18 / 36 % | 11 / 26 % | 8 / 15 % | 5 / 13 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 18 / 31 % | 0 / 0 % | 3 / 7 % | 1 / 5 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 28 % | 10 / 18 % | 7 / 15 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 9 / 27 % | 12 / 29 % | 10 / 21 % | 2 / 7 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 26 % | 0 / 0 % | 1 / 3 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 22 % | 5 / 11 % | 1 / 3 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 7 / 51 % | – | 0 / 0 % | 0 / 0 % | 5 / 8 % | 0 / 2 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 2 / 6 % | 0 / 1 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 2 / 4 % | 0 / 1 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 5 / 12 % | 2 / 8 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 2 / 4 % | 0 / 2 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 2 / 5 % | 1 / 4 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 1 / 2 % | 1 / 4 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 8 % | 0 / 3 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 9 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 5 % |
