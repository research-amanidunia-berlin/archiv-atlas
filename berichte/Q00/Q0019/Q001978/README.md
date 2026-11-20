[English](README.md) · [Deutsch](README.de.md)

# Sora System Card

Report Q001978 · Source openai.com · Date 2024-12-09 · [Open original](https://openai.com/index/sora-system-card/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht beschreibt Sora, seine Trainingsgrundlagen und OpenAIs mehrschichtige Sicherheitsmaßnahmen, darunter Filter, Altersbeschränkung, Kinderschutz und Herkunftsnachweise. OpenAI berichtet von messbaren Erfolgen in Tests, räumt aber Fehlalarme, mögliche Verzerrungen, Umgehungsversuche und die Grenzen kontextabhängiger Moderation ein; die Kennzahlen sind Angaben des Unternehmens.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 57 % | 99 / 100 % | – | 100 / 100 % | 63 / 81 % | 73 / 85 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 45 / 58 % | 88 / 97 % | – | 100 / 100 % | 78 / 88 % | 70 / 82 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 69 / 81 % | 100 / 100 % | – | 99 / 100 % | 86 / 92 % | 89 / 93 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 34 / 50 % | 96 / 98 % | – | 97 / 99 % | 55 / 77 % | 69 / 80 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 80 / 92 % | – | 96 / 97 % | 47 / 70 % | 41 / 63 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 93 / 97 % | – | 96 / 98 % | 35 / 60 % | 30 / 49 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 88 / 97 % | – | 94 / 98 % | 30 / 57 % | 24 / 47 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 31 / 52 % | 93 / 99 % | – | 94 / 97 % | 55 / 76 % | 33 / 54 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 49 / 84 % | – | 90 / 96 % | 47 / 69 % | 31 / 47 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 26 / 46 % | 31 / 71 % | – | 88 / 93 % | 34 / 58 % | 22 / 42 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 32 / 65 % | – | 81 / 91 % | 29 / 55 % | 6 / 13 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 21 / 35 % | 62 / 83 % | – | 78 / 90 % | 25 / 50 % | 18 / 38 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 62 / 80 % | – | 73 / 76 % | 31 / 54 % | 15 / 24 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 47 / 76 % | – | 71 / 85 % | 8 / 20 % | 5 / 10 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 68 / 90 % | – | 59 / 78 % | 26 / 49 % | 17 / 30 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 65 / 82 % | – | 4 / 10 % | 8 / 17 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 22 / 43 % | 0 / 0 % | – | 62 / 68 % | 15 / 42 % | 19 / 37 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 62 / 81 % | 9 / 25 % | 5 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 35 / 68 % | – | 60 / 67 % | 31 / 53 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 42 / 68 % | – | 54 / 72 % | 28 / 53 % | 15 / 29 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 53 / 88 % | – | 53 / 73 % | 23 / 49 % | 21 / 36 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 43 / 71 % | – | 51 / 74 % | 25 / 49 % | 15 / 28 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 50 / 90 % | – | 34 / 50 % | 7 / 20 % | 5 / 9 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 47 / 82 % | – | 0 / 0 % | 15 / 36 % | 12 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 46 / 73 % | – | 45 / 66 % | 19 / 39 % | 14 / 22 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 44 / 75 % | – | 20 / 36 % | 14 / 34 % | 6 / 12 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 40 / 79 % | – | 23 / 52 % | 17 / 37 % | 22 / 38 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 17 / 42 % | – | 39 / 54 % | 13 / 27 % | 13 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 22 / 47 % | 9 / 18 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 15 / 47 % | – | 0 / 0 % | 16 / 35 % | 10 / 16 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 1 / 12 % | 12 / 33 % | 8 / 15 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 7 / 23 % | 8 / 19 % | 9 / 17 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 18 % | 5 / 9 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 67 % | – | 0 / 0 % | 7 / 15 % | 7 / 11 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 14 % | 6 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 5 / 8 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 4 / 9 % |
