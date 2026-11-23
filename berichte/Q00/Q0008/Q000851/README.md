[English](README.md) · [Deutsch](README.de.md)

# Reflections from red-teaming Codex auto-review

Report Q000851 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/monitoring/reflections-from-red-teaming-codex-auto-review)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Text ist ein Auszug und enthält keine detaillierten Testergebnisse. Apollo beschreibt einen Red-Team-Pilotversuch mit OpenAI zu Codex Auto-Review und betont Fragen zur Herkunft von Genehmigungen, zur Bedeutung ausdrücklicher Verbote, zu organisatorischen Zuständigkeiten und zu informierter Zustimmung bei Datenweitergaben. Laut Apollo wurden Schwachstellen gefunden; künftig sollen eingebettete Evaluierungen stärker in den Mittelpunkt rücken.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 57 / 73 % | 93 / 98 % | – | 82 / 91 % | 75 / 86 % | 76 / 85 % | 87 / 94 % | 47 / 71 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 36 / 53 % | 86 / 96 % | – | 30 / 53 % | 14 / 25 % | 22 / 38 % | 7 / 16 % | 17 / 37 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 40 / 54 % | 77 / 99 % | – | 60 / 80 % | 39 / 60 % | 48 / 67 % | 16 / 43 % | 25 / 45 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 57 % | 72 / 99 % | – | 50 / 75 % | 42 / 61 % | 53 / 72 % | 32 / 65 % | 15 / 38 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 21 / 43 % | 68 / 94 % | – | 35 / 60 % | 30 / 48 % | 35 / 54 % | 14 / 27 % | 21 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 30 / 50 % | 58 / 96 % | – | 31 / 57 % | 9 / 20 % | 26 / 44 % | 6 / 16 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 35 % | 51 / 78 % | – | 11 / 26 % | 3 / 8 % | 14 / 25 % | 1 / 4 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 17 / 37 % | 49 / 81 % | – | 26 / 48 % | 6 / 10 % | 20 / 34 % | 2 / 9 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 27 / 46 % | 26 / 97 % | – | 39 / 64 % | 27 / 44 % | 45 / 62 % | 8 / 20 % | 14 / 38 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 43 / 79 % | – | 9 / 23 % | 0 / 0 % | 8 / 17 % | 1 / 4 % | 13 / 35 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 41 / 66 % | – | 0 / 0 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 6 / 20 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 40 / 79 % | – | 28 / 56 % | 6 / 14 % | 28 / 44 % | 2 / 9 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 17 / 37 % | 0 / 0 % | – | 38 / 61 % | 8 / 17 % | 17 / 33 % | 4 / 13 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 14 / 33 % | 35 / 94 % | – | 12 / 33 % | 4 / 10 % | 12 / 27 % | 2 / 7 % | 15 / 45 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 26 / 62 % | – | 12 / 35 % | 1 / 2 % | 0 / 0 % | 1 / 3 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 25 / 51 % | – | 6 / 14 % | 3 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 24 / 45 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 15 / 72 % | – | 23 / 47 % | 6 / 15 % | 6 / 14 % | 8 / 20 % | 11 / 28 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 20 / 44 % | 0 / 0 % | – | 22 / 48 % | 7 / 16 % | 9 / 19 % | 1 / 6 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 21 / 92 % | – | 5 / 12 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 17 / 30 % | 0 / 0 % | – | 16 / 39 % | 3 / 7 % | 12 / 24 % | 2 / 9 % | 14 / 35 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 17 / 51 % | – | 10 / 26 % | 1 / 3 % | 7 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | 12 / 29 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 9 / 26 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 6 / 24 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 4 % | 7 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 5 / 40 % | – | 7 / 16 % | 1 / 3 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 7 / 14 % | 0 / 1 % | 4 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 7 / 15 % | 0 / 1 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 1 / 4 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 1 / 3 % | 3 / 5 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
