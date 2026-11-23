[English](README.md) · [Deutsch](README.de.md)

# New report: Evaluating Language-Model Agents on Realistic Autonomous Tasks

Report Q003017 · Source metr.org · Date 2023-07-31 · [Open original](https://metr.org/blog/2023-08-01-new-report/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

ARC Evals prüfte vier Claude- und GPT-4-Agenten in zwölf Aufgaben, die von Informationssuche bis zu Fine-Tuning und simuliertem Phishing reichten. Laut Beitrag schafften sie nur die einfachsten Aufgaben vollständig; die Forschenden warnen jedoch, dass Agentenaufbau und Fine-Tuning die Fähigkeiten beeinflussen und die getesteten Systeme keine Obergrenze darstellen. Konkrete Aufgabenzahlen sind im bereitgestellten Text nicht lesbar, weil sie nur als Abbildung referenziert werden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 57 / 77 % | 89 / 98 % | 98 / 100 % | 20 / 39 % | 59 / 81 % | 72 / 84 % | 81 / 93 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 38 / 61 % | 88 / 99 % | 97 / 99 % | 74 / 87 % | 50 / 76 % | 75 / 85 % | 50 / 79 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 41 / 67 % | 68 / 95 % | 95 / 99 % | 67 / 83 % | 11 / 36 % | 62 / 77 % | 41 / 78 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 32 / 54 % | 61 / 96 % | 90 / 96 % | 33 / 63 % | 12 / 40 % | 33 / 62 % | 9 / 36 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 60 % | 75 / 97 % | 87 / 94 % | 46 / 74 % | 42 / 72 % | 67 / 82 % | 39 / 75 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 33 / 88 % | 83 / 93 % | 51 / 74 % | 11 / 31 % | 14 / 33 % | 6 / 26 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 44 % | 65 / 97 % | 64 / 83 % | 29 / 55 % | 7 / 18 % | 23 / 42 % | 2 / 12 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 32 / 54 % | 58 / 90 % | 39 / 62 % | 24 / 54 % | 8 / 27 % | 19 / 40 % | 3 / 16 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 25 / 53 % | 53 / 97 % | 53 / 87 % | 55 / 78 % | 19 / 48 % | 48 / 68 % | 30 / 69 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 53 / 88 % | 0 / 8 % | 8 / 23 % | 2 / 11 % | 7 / 18 % | 1 / 8 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 50 / 84 % | 21 / 59 % | 8 / 23 % | 1 / 9 % | 6 / 17 % | 0 / 3 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 25 / 44 % | 42 / 96 % | 21 / 68 % | 46 / 72 % | 9 / 27 % | 40 / 59 % | 10 / 39 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 21 / 53 % | 44 / 81 % | 32 / 58 % | 26 / 53 % | 7 / 23 % | 15 / 31 % | 4 / 20 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 41 / 93 % | 29 / 60 % | 9 / 22 % | 2 / 8 % | 7 / 13 % | 0 / 2 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 28 / 62 % | 36 / 56 % | 6 / 18 % | 1 / 6 % | 5 / 11 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 28 / 53 % | 15 / 85 % | 14 / 29 % | 26 / 54 % | 10 / 26 % | 33 / 51 % | 3 / 16 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 23 / 46 % | 24 / 55 % | 0 / 0 % | 32 / 61 % | 10 / 28 % | 25 / 43 % | 4 / 16 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 32 / 88 % | 4 / 24 % | 8 / 23 % | 3 / 12 % | 5 / 14 % | 0 / 3 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 39 % | 0 / 0 % | 32 / 63 % | 13 / 42 % | 4 / 15 % | 7 / 23 % | 1 / 10 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 37 % | 31 / 82 % | 1 / 13 % | 16 / 40 % | 6 / 19 % | 16 / 37 % | 1 / 8 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 29 / 68 % | 6 / 30 % | 10 / 29 % | 1 / 4 % | 4 / 9 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 52 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 11 / 36 % | 27 / 80 % | 21 / 48 % | 16 / 43 % | 5 / 21 % | 11 / 26 % | 3 / 15 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 23 / 50 % | 0 / 0 % | 8 / 24 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 22 / 91 % | 1 / 11 % | 7 / 18 % | 3 / 9 % | 0 / 0 % | 0 / 4 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 21 / 33 % | 6 / 18 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 20 / 52 % | 4 / 68 % | 0 / 0 % | 10 / 34 % | 3 / 12 % | 15 / 30 % | 1 / 6 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 17 / 70 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 5 / 10 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 35 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 2 / 9 % | 10 / 21 % | 0 / 3 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 2 / 26 % | 9 / 27 % | 3 / 8 % | 5 / 13 % | 0 / 4 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 0 / 1 % | 5 / 11 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 57 % | 0 / 0 % | 6 / 16 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 2 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 0 / 3 % | 4 / 10 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 10 % | 6 / 17 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 4 / 8 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 5 % | 3 / 7 % | 0 / 0 % | – |
