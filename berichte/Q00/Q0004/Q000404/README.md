[English](README.md) · [Deutsch](README.de.md)

# Introducing Inkling 2 Small

Report Q000404 · Source thinkingmachines.ai · Date 2026-11-05 · [Open original](https://thinkingmachines.ai/news/inkling-2-small/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Thinking Machines Lab präsentiert Inkling 2 Small als bildfähiges Modell, das laut eigenen Benchmarks in mehreren Bereichen stark, in anderen jedoch konkurrenzfähig oder unterlegen ist. Der Bericht beschreibt umfangreiches Training und Sicherheitsmaßnahmen, nennt aber auch Fehlverhalten früherer Trainingsstände, Alignment-Abstände zu geschlossenen Modellen und Schwächen im Chatgebrauch; die Leistungsangaben stammen vom Hersteller.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 55 / 71 % | 99 / 100 % | 100 / 100 % | 81 / 90 % | 65 / 78 % | 83 / 89 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 46 / 65 % | 94 / 97 % | 100 / 100 % | 75 / 87 % | 71 / 84 % | 82 / 91 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 52 / 70 % | 96 / 98 % | 100 / 100 % | 87 / 92 % | 79 / 89 % | 90 / 94 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 57 / 73 % | 100 / 100 % | 100 / 100 % | 86 / 92 % | 68 / 82 % | 80 / 89 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 40 / 57 % | 94 / 96 % | 100 / 100 % | 86 / 92 % | 61 / 77 % | 80 / 87 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 95 / 97 % | 99 / 100 % | 61 / 82 % | 0 / 0 % | 38 / 58 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 49 / 68 % | 95 / 98 % | 99 / 100 % | 78 / 89 % | 47 / 70 % | 77 / 89 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 23 / 44 % | 98 / 100 % | 67 / 83 % | 66 / 81 % | 14 / 33 % | 54 / 70 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 34 / 55 % | 98 / 99 % | 98 / 99 % | 70 / 84 % | 18 / 33 % | 73 / 83 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 44 / 64 % | 97 / 99 % | 93 / 97 % | 72 / 85 % | 28 / 43 % | 63 / 74 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 81 / 95 % | 90 / 93 % | 30 / 54 % | 9 / 17 % | 26 / 47 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 35 / 84 % | 89 / 92 % | 16 / 37 % | 3 / 8 % | 17 / 29 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 30 / 52 % | 67 / 92 % | 88 / 92 % | 80 / 89 % | 50 / 67 % | 84 / 90 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 31 / 60 % | 87 / 99 % | 71 / 84 % | 60 / 80 % | 14 / 25 % | 67 / 77 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 85 / 94 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 4 / 8 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 21 / 42 % | 78 / 90 % | 84 / 90 % | 57 / 78 % | 14 / 26 % | 45 / 59 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 38 / 67 % | 77 / 87 % | 13 / 34 % | 2 / 6 % | 10 / 23 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 75 / 84 % | 46 / 69 % | 10 / 20 % | 13 / 26 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 41 / 60 % | 67 / 81 % | 45 / 68 % | 13 / 25 % | 31 / 51 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 67 / 96 % | 30 / 46 % | 35 / 57 % | 0 / 0 % | 21 / 36 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 62 / 85 % | 43 / 65 % | 8 / 23 % | 1 / 5 % | 7 / 16 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 60 / 91 % | 49 / 62 % | 33 / 55 % | 10 / 21 % | 12 / 25 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 59 / 88 % | 48 / 58 % | 27 / 51 % | 5 / 12 % | 13 / 27 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 20 / 42 % | 44 / 83 % | 52 / 66 % | 26 / 52 % | 11 / 22 % | 29 / 48 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 54 % | 4 / 12 % | 43 / 64 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 21 / 32 % | 35 / 61 % | 5 / 10 % | 17 / 36 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 31 / 50 % | 6 / 17 % | 2 / 5 % | 4 / 9 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 30 / 53 % | 3 / 7 % | 17 / 38 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 47 % | 0 / 0 % | 0 / 0 % | 30 / 54 % | 7 / 15 % | 11 / 22 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 28 / 46 % | 10 / 28 % | 4 / 9 % | 14 / 27 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 25 / 66 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 6 / 10 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 28 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 3 / 16 % | 10 / 22 % | 3 / 9 % | 2 / 5 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 24 % | 0 / 0 % | 6 / 11 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 3 / 7 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 3 / 6 % | 4 / 9 % | – | – |
