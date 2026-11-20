[English](README.md) · [Deutsch](README.de.md)

# Introducing Claude Haiku 4.5

Report Q004785 · Source anthropic.com · Date 2025-10-15 · [Open original](https://www.anthropic.com/news/claude-haiku-4-5)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge bietet Haiku 4.5 bei Programmieraufgaben annähernd Sonnet-4-Leistung zu geringeren Kosten und mit höherer Geschwindigkeit; verfügbar sei es unter anderem in Claude, der API und bei Cloud-Anbietern. Das Unternehmen berichtet zudem von verbesserten Alignment-Ergebnissen und stuft das Modell nach ASL-2 ein, doch Benchmark- und Sicherheitsangaben stammen von Anthropic und beruhen auf jeweils unterschiedlichen Testmethoden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 27 / 42 % | 84 / 87 % | – | 100 / 100 % | 58 / 77 % | 42 / 54 % | 14 / 26 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 53 % | 69 / 89 % | – | 98 / 99 % | 40 / 68 % | 48 / 70 % | 15 / 34 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 50 % | 63 / 91 % | – | 97 / 98 % | 53 / 75 % | 41 / 63 % | 12 / 31 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 28 / 51 % | 69 / 88 % | – | 96 / 97 % | 54 / 77 % | 50 / 72 % | 21 / 45 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 30 / 72 % | – | 92 / 95 % | 19 / 43 % | 16 / 33 % | 6 / 15 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 28 / 46 % | 63 / 91 % | – | 85 / 91 % | 37 / 67 % | 16 / 46 % | 14 / 36 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 33 / 57 % | 52 / 83 % | – | 73 / 84 % | 17 / 37 % | 37 / 56 % | 9 / 25 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 71 / 79 % | 32 / 58 % | 0 / 0 % | 5 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 15 / 35 % | – | 64 / 80 % | 6 / 16 % | 4 / 7 % | 1 / 4 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 57 / 67 % | 7 / 25 % | 0 / 0 % | 1 / 5 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 32 / 52 % | 31 / 53 % | – | 55 / 74 % | 34 / 60 % | 17 / 28 % | 10 / 22 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 18 / 53 % | – | 48 / 62 % | 14 / 35 % | 8 / 17 % | 7 / 17 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 36 % | 47 / 69 % | – | 10 / 23 % | 8 / 28 % | 8 / 18 % | 1 / 4 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 0 / 0 % | – | 47 / 68 % | 15 / 35 % | 10 / 20 % | 2 / 8 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 46 / 67 % | 8 / 21 % | 4 / 9 % | 1 / 5 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 45 / 59 % | 5 / 12 % | 3 / 6 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 25 / 72 % | – | 38 / 65 % | 8 / 24 % | 0 / 0 % | 2 / 8 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 35 / 61 % | – | 7 / 12 % | 5 / 13 % | 0 / 0 % | 1 / 5 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 11 / 62 % | – | 33 / 50 % | 6 / 20 % | 0 / 0 % | 2 / 7 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 24 / 47 % | 11 / 55 % | – | 32 / 50 % | 26 / 55 % | 16 / 35 % | 4 / 11 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 21 / 45 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 18 / 45 % | 0 / 0 % | – | 0 / 0 % | 7 / 23 % | 8 / 18 % | 1 / 4 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 15 / 44 % | 0 / 0 % | – | 0 / 0 % | 12 / 34 % | 5 / 11 % | 1 / 7 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 35 % | 13 / 42 % | – | 0 / 0 % | 6 / 19 % | 5 / 12 % | 2 / 8 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 12 / 39 % | – | 12 / 27 % | 7 / 23 % | 3 / 9 % | 1 / 5 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 9 / 15 % | 5 / 13 % | 10 / 18 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 18 % | 7 / 14 % | 1 / 5 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 18 % | 6 / 13 % | 1 / 6 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 4 / 8 % | 1 / 4 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 2 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 1 / 3 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 5 / 10 % | 0 / 2 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 0 / 0 % | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 15 % | 5 / 8 % | 1 / 3 % |
