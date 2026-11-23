[English](README.md) · [Deutsch](README.de.md)

# Build a Self-Improving AI Agent System with Claude Fable 5: A Complete 14-Step Guide

Report Q011255 · Source medium.com · Date 2026-07-06 · [Open original](https://medium.com/coding-nexus/build-a-self-improving-ai-agent-system-with-claude-fable-5-a-complete-14-step-guide-e3db04647c78)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht empfiehlt, Agentensysteme durch gespeicherte Erkenntnisse, fortgeschriebene Skills und unabhängige Prüfungen über mehrere Durchläufe zu verbessern; eine Veränderung der Modellgewichte sei damit nicht gemeint. Die berichteten Bench-Ergebnisse gelten für die dargestellten Experimente, und der Ansatz setzt gepflegtes Gedächtnis, geeignete Laufzeitumgebungen sowie einen Umgang mit den genannten Sicherheitsgrenzen voraus.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 39 / 61 % | 74 / 91 % | 99 / 100 % | 66 / 82 % | 14 / 37 % | 58 / 75 % | 53 / 81 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 28 / 47 % | 98 / 99 % | 91 / 95 % | 53 / 75 % | 21 / 41 % | 57 / 71 % | 13 / 31 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 50 % | 79 / 95 % | 97 / 98 % | 60 / 79 % | 17 / 40 % | 56 / 75 % | 29 / 63 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 93 / 97 % | 93 / 96 % | 30 / 53 % | 6 / 13 % | 25 / 37 % | 13 / 23 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 15 / 35 % | 59 / 88 % | 91 / 94 % | 38 / 64 % | 6 / 20 % | 24 / 47 % | 3 / 11 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 19 / 32 % | 86 / 92 % | 90 / 93 % | 40 / 62 % | 5 / 13 % | 22 / 32 % | 7 / 13 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 47 % | 88 / 96 % | 0 / 0 % | 38 / 66 % | 13 / 27 % | 40 / 60 % | 6 / 19 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 87 / 92 % | 7 / 18 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 54 / 79 % | 81 / 91 % | 23 / 50 % | 8 / 17 % | 22 / 38 % | 1 / 6 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 78 / 85 % | 14 / 34 % | 1 / 3 % | 5 / 9 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 31 / 47 % | 75 / 89 % | 22 / 47 % | 4 / 9 % | 15 / 25 % | 2 / 8 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 42 / 68 % | 70 / 80 % | 8 / 22 % | 1 / 4 % | 6 / 13 % | 0 / 2 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 29 / 57 % | 56 / 67 % | 52 / 74 % | 16 / 32 % | 53 / 70 % | 6 / 16 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 22 / 45 % | 47 / 86 % | 50 / 65 % | 47 / 71 % | 11 / 30 % | 56 / 73 % | 8 / 22 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 30 / 72 % | 45 / 63 % | 23 / 54 % | 6 / 18 % | 18 / 39 % | 5 / 17 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 44 / 66 % | 10 / 30 % | 2 / 6 % | 10 / 16 % | 0 / 1 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 39 / 56 % | 11 / 26 % | 2 / 8 % | 11 / 17 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 11 / 30 % | 37 / 52 % | 13 / 32 % | 11 / 28 % | 5 / 13 % | 13 / 27 % | 3 / 9 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 33 / 49 % | 9 / 20 % | 29 / 46 % | 4 / 9 % | 22 / 28 % | 2 / 4 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 17 / 29 % | 0 / 0 % | 0 / 0 % | 14 / 36 % | 0 / 1 % | 9 / 16 % | 0 / 0 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 27 % | 1 / 4 % | 13 / 25 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 36 % | 0 / 0 % | 6 / 10 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 26 % | 1 / 3 % | 12 / 19 % | 0 / 1 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 1 / 3 % | 10 / 22 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 28 % | 1 / 3 % | 6 / 10 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 10 / 55 % | 0 / 0 % | 7 / 19 % | 1 / 5 % | 6 / 10 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 2 % | 5 / 8 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 1 / 3 % | 5 / 7 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 1 % | 5 / 12 % | 0 / 0 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 6 / 9 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 3 % | 5 / 8 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 3 % | 5 / 9 % | 0 / 0 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 1 / 2 % | 3 / 5 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | – |
