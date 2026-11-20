[English](README.md) · [Deutsch](README.de.md)

# SIMA 2: A Gemini-Powered AI Agent for 3D Virtual Worlds

Report Q003947 · Source deepmind.google · Date 2025-11-13 · [Open original](https://deepmind.google/blog/sima-2-an-agent-that-plays-reasons-and-learns-with-you-in-virtual-3d-worlds/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind zufolge erweitert SIMA 2 einen auf Sprachbefehle ausgerichteten Spielagenten um Planung, Dialog und selbstständiges Lernen. Das Team berichtet über bessere Ergebnisse in unbekannten Spielen und einen Lernkreislauf aus eigenen Spielerfahrungen, doch der Blog nennt keine ausführlichen Testmethoden oder Zahlen; einige ergänzende Bildbeschriftungen sind abgeschnitten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 38 / 62 % | 99 / 100 % | 60 / 80 % | 100 / 100 % | 75 / 87 % | 62 / 74 % | 44 / 64 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 70 / 94 % | 2 / 6 % | 93 / 97 % | 27 / 54 % | 14 / 29 % | 5 / 16 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 20 / 43 % | 70 / 96 % | 3 / 10 % | 88 / 93 % | 19 / 51 % | 21 / 53 % | 8 / 22 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 18 / 50 % | 48 / 96 % | 6 / 35 % | 86 / 95 % | 38 / 63 % | 16 / 38 % | 3 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 32 / 85 % | 1 / 7 % | 84 / 92 % | 13 / 40 % | 10 / 24 % | 2 / 15 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 24 / 50 % | 74 / 98 % | 2 / 13 % | 45 / 71 % | 20 / 53 % | 13 / 34 % | 5 / 19 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 50 / 85 % | 1 / 3 % | 71 / 79 % | 10 / 27 % | 9 / 21 % | 1 / 6 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 18 / 46 % | 50 / 84 % | 4 / 15 % | 69 / 82 % | 26 / 54 % | 23 / 50 % | 7 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 47 / 87 % | 1 / 5 % | 69 / 80 % | 11 / 30 % | 7 / 22 % | 2 / 11 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 62 / 78 % | 8 / 21 % | 0 / 0 % | 1 / 4 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 15 / 76 % | 0 / 0 % | 62 / 68 % | 10 / 27 % | 5 / 13 % | 2 / 10 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 16 / 43 % | 51 / 85 % | 1 / 7 % | 56 / 72 % | 22 / 52 % | 16 / 36 % | 5 / 19 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 3 / 9 % | 54 / 72 % | 18 / 38 % | 10 / 20 % | 6 / 16 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 27 / 59 % | 0 / 0 % | 49 / 60 % | 18 / 35 % | 12 / 21 % | 2 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 15 / 83 % | 0 / 0 % | 36 / 50 % | 6 / 18 % | 4 / 12 % | 2 / 9 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 33 / 77 % | 1 / 4 % | 7 / 37 % | 11 / 34 % | 8 / 22 % | 2 / 8 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 19 / 38 % | 6 / 16 % | 3 / 9 % | 2 / 9 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 15 / 52 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 4 / 10 % | 1 / 6 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 30 % | 5 / 12 % | 3 / 10 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 37 % | 12 / 43 % | 1 / 5 % | 2 / 18 % | 11 / 29 % | 8 / 22 % | 3 / 13 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 27 % | 7 / 16 % | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 7 / 15 % | 1 / 5 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 30 % | 8 / 21 % | 1 / 5 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 9 / 23 % | 7 / 17 % | 1 / 5 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 2 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 25 % | 4 / 11 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 7 / 15 % | 1 / 6 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 2 / 55 % | 1 / 5 % | 1 / 5 % | 7 / 22 % | 3 / 10 % | 1 / 8 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 2 / 6 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 3 / 8 % | 0 / 1 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 2 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 53 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 11 % | 0 / 0 % |
