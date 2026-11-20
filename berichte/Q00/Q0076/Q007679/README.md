[English](README.md) · [Deutsch](README.de.md)

# gpt-oss-120b & gpt-oss-20b Model Card

Report Q007679 · Source openai.com · Date 2025-08-05 · [Open original](https://openai.com/index/gpt-oss-model-card/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Text ist ein Auszug aus OpenAIs Model Card für zwei offene Reasoning-Modelle und beschreibt ihre vorgesehenen Fähigkeiten sowie Sicherheitsrisiken nach der Veröffentlichung. OpenAI berichtet, dass gpt-oss-120b in den genannten Tests auch nach adversarieller Feinabstimmung keine hohe Fähigkeit in Biologie/Chemie oder Cyber erreichte; Einzelheiten und Ergebnisse für gpt-oss-20b fehlen im Auszug.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 60 / 79 % | 99 / 100 % | – | 100 / 100 % | 82 / 91 % | 60 / 75 % | 80 / 88 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 50 % | 76 / 97 % | – | 97 / 99 % | 59 / 79 % | 16 / 39 % | 50 / 71 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 44 / 97 % | – | 96 / 98 % | 48 / 72 % | 16 / 34 % | 9 / 23 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 30 / 53 % | 93 / 96 % | – | 87 / 93 % | 60 / 81 % | 19 / 42 % | 50 / 67 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 53 % | 74 / 96 % | – | 93 / 97 % | 47 / 73 % | 28 / 51 % | 64 / 80 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 36 / 58 % | 64 / 90 % | – | 91 / 97 % | 40 / 68 % | 31 / 53 % | 58 / 75 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 26 / 44 % | 31 / 97 % | – | 90 / 97 % | 37 / 64 % | 10 / 30 % | 17 / 46 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 66 / 96 % | – | 85 / 91 % | 24 / 45 % | 10 / 20 % | 16 / 33 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 24 / 45 % | 40 / 86 % | – | 85 / 91 % | 19 / 43 % | 7 / 19 % | 17 / 32 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 31 / 55 % | 74 / 99 % | – | 71 / 88 % | 56 / 77 % | 19 / 38 % | 47 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 18 / 40 % | 20 / 63 % | – | 74 / 86 % | 32 / 61 % | 9 / 25 % | 30 / 59 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 14 / 35 % | 39 / 81 % | – | 70 / 88 % | 32 / 56 % | 8 / 22 % | 25 / 45 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 20 / 45 % | – | 70 / 85 % | 7 / 16 % | 1 / 4 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 43 / 73 % | – | 61 / 79 % | 10 / 30 % | 4 / 12 % | 7 / 19 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 55 / 92 % | – | 41 / 67 % | 11 / 30 % | 7 / 22 % | 14 / 31 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 28 % | 0 / 0 % | – | 52 / 73 % | 10 / 31 % | 3 / 11 % | 7 / 18 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 51 / 94 % | – | 23 / 39 % | 10 / 27 % | 3 / 10 % | 6 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 29 / 46 % | 33 / 58 % | – | 50 / 74 % | 43 / 67 % | 13 / 30 % | 27 / 56 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 23 / 46 % | 48 / 77 % | – | 35 / 53 % | 35 / 61 % | 12 / 34 % | 40 / 55 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 31 / 64 % | – | 1 / 6 % | 8 / 17 % | 2 / 6 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 30 / 76 % | – | 10 / 33 % | 12 / 30 % | 8 / 24 % | 11 / 24 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 28 / 52 % | 1 / 5 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 33 % | 25 / 63 % | – | 25 / 43 % | 26 / 50 % | 10 / 24 % | 20 / 39 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 16 / 34 % | 16 / 70 % | – | 18 / 31 % | 15 / 41 % | 7 / 16 % | 19 / 34 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 18 / 34 % | 9 / 18 % | 12 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 16 / 36 % | 5 / 12 % | 0 / 2 % | 6 / 15 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 13 / 44 % | 0 / 0 % | – | 0 / 0 % | 15 / 38 % | 3 / 10 % | 8 / 18 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 14 / 58 % | – | 3 / 13 % | 8 / 19 % | 1 / 6 % | 5 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 30 % | 0 / 0 % | – | 0 / 0 % | 7 / 21 % | 4 / 11 % | 13 / 26 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 27 % | 5 / 17 % | 13 / 33 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 5 / 21 % | 7 / 14 % | 1 / 5 % | 10 / 20 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 10 / 30 % | 2 / 37 % | – | 3 / 12 % | 7 / 18 % | 2 / 10 % | 6 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 0 / 2 % | 5 / 14 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 7 / 17 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 1 / 5 % | 6 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 1 / 3 % | 6 / 15 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
