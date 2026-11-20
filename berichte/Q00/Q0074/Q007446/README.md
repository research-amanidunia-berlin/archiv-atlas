[English](README.md) · [Deutsch](README.de.md)

# Introducing EVMbench

Report Q007446 · Source openai.com · Date 2026-02-18 · [Open original](https://openai.com/index/introducing-evmbench/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI und Paradigm stellen EVMbench vor, einen Benchmark für KI-Agenten, die Smart-Contract-Schwachstellen erkennen, beheben oder ausnutzen sollen. GPT‑5.3‑Codex erreichte laut OpenAI 71 Prozent im Exploit-Modus; der Bericht betont zugleich, dass Erkennung und Behebung lückenhaft bleiben und der Benchmark reale Sicherheitsbedingungen nur teilweise abbildet.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 73 / 80 % | 98 / 99 % | – | 100 / 100 % | 7 / 16 % | 80 / 86 % | 80 / 89 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 41 / 57 % | 94 / 99 % | – | 100 / 100 % | 50 / 74 % | 61 / 74 % | 49 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 45 % | 67 / 87 % | – | 94 / 97 % | 41 / 66 % | 44 / 62 % | 8 / 25 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 55 / 83 % | – | 93 / 96 % | 27 / 48 % | 18 / 32 % | 4 / 12 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 25 / 45 % | 54 / 83 % | – | 90 / 95 % | 39 / 61 % | 24 / 43 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 45 / 89 % | – | 82 / 92 % | 31 / 48 % | 23 / 35 % | 6 / 14 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 5 / 29 % | – | 69 / 81 % | 46 / 68 % | 11 / 23 % | 7 / 17 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 11 / 66 % | – | 57 / 70 % | 9 / 26 % | 8 / 17 % | 2 / 8 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 54 / 89 % | – | 12 / 35 % | 20 / 47 % | 14 / 32 % | 5 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 53 / 65 % | 8 / 27 % | 12 / 25 % | 1 / 7 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 51 / 63 % | 13 / 34 % | 13 / 26 % | 3 / 10 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 46 / 79 % | – | 43 / 66 % | 9 / 25 % | 5 / 14 % | 1 / 6 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 43 / 64 % | 6 / 11 % | 0 / 0 % | 0 / 1 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 38 / 75 % | – | 25 / 47 % | 10 / 31 % | 11 / 24 % | 1 / 8 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 37 / 57 % | 31 / 56 % | 20 / 36 % | 6 / 17 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 19 / 51 % | – | 34 / 55 % | 9 / 25 % | 5 / 12 % | 1 / 5 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 29 / 50 % | 0 / 0 % | 0 / 2 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 11 / 27 % | 28 / 79 % | – | 10 / 47 % | 15 / 37 % | 8 / 24 % | 5 / 14 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 20 / 38 % | 26 / 56 % | – | 0 / 0 % | 27 / 51 % | 24 / 42 % | 8 / 23 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 23 / 41 % | 7 / 19 % | 4 / 10 % | 1 / 6 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 34 % | 19 / 32 % | 4 / 11 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 18 / 41 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % | 1 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 17 / 47 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 17 / 42 % | 7 / 17 % | 3 / 11 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 13 / 62 % | – | 0 / 0 % | 14 / 36 % | 11 / 25 % | 1 / 9 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 13 / 49 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 1 / 6 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 12 / 65 % | – | 2 / 20 % | 9 / 26 % | 6 / 15 % | 1 / 4 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 10 / 44 % | – | 6 / 18 % | 9 / 25 % | 7 / 19 % | 5 / 17 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 4 / 21 % | 9 / 25 % | 0 / 0 % | 2 / 8 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 27 % | 0 / 0 % | 0 / 3 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 13 % | 2 / 6 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % | 0 / 3 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 5 / 12 % | 0 / 2 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 4 / 8 % | 1 / 4 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 4 / 8 % | 1 / 4 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 1 / 3 % |
