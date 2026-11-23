[English](README.md) · [Deutsch](README.de.md)

# Gemini Robotics 1.5 brings AI agents into the physical world

Report Q003888 · Source deepmind.google · Date 2025-09-25 · [Open original](https://deepmind.google/blog/gemini-robotics-15-brings-ai-agents-into-the-physical-world/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind beschreibt zwei zusammenwirkende Robotikmodelle: ER 1.5 soll planen, die Umgebung verstehen und Werkzeuge nutzen; Robotics 1.5 soll die geplanten Schritte in Bewegungen umsetzen, vor dem Handeln nachdenken und Fähigkeiten zwischen Robotertypen übertragen. Das Unternehmen meldet Spitzenwerte in Benchmarks und Fortschritte bei Sicherheitsfunktionen, doch der Beitrag erläutert die Messwerte und Testbedingungen nur begrenzt und stellt keine unabhängige Prüfung dar.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 29 / 50 % | 65 / 90 % | 95 / 99 % | 59 / 77 % | 8 / 25 % | 31 / 53 % | 15 / 46 % | 30 / 57 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 27 / 47 % | 85 / 98 % | 93 / 96 % | 37 / 65 % | 10 / 23 % | 47 / 68 % | 15 / 26 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 48 % | 65 / 87 % | 91 / 95 % | 58 / 78 % | 12 / 30 % | 45 / 68 % | 12 / 29 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 18 / 39 % | 61 / 89 % | 88 / 93 % | 47 / 72 % | 10 / 25 % | 43 / 64 % | 10 / 20 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 24 / 44 % | 70 / 98 % | 83 / 92 % | 35 / 66 % | 7 / 23 % | 24 / 53 % | 9 / 20 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 60 / 89 % | 75 / 89 % | 20 / 47 % | 0 / 0 % | 11 / 21 % | 0 / 2 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 21 / 74 % | 75 / 84 % | 10 / 31 % | 3 / 10 % | 14 / 29 % | 1 / 3 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 10 / 57 % | 72 / 86 % | 9 / 29 % | 1 / 5 % | 9 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 10 / 63 % | 69 / 81 % | 14 / 34 % | 2 / 8 % | 6 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 17 / 46 % | 67 / 82 % | 19 / 40 % | 5 / 13 % | 11 / 19 % | 0 / 0 % | 16 / 32 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 29 % | 54 / 92 % | 15 / 35 % | 7 / 27 % | 0 / 3 % | 8 / 15 % | 0 / 2 % | 13 / 30 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 36 % | 46 / 76 % | 53 / 69 % | 19 / 45 % | 6 / 19 % | 17 / 34 % | 4 / 9 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 42 / 75 % | 9 / 19 % | 10 / 25 % | 2 / 9 % | 7 / 14 % | 0 / 0 % | 18 / 32 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 39 / 74 % | 29 / 57 % | 9 / 27 % | 1 / 8 % | 8 / 22 % | 1 / 4 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 34 / 64 % | 12 / 33 % | 18 / 43 % | 3 / 10 % | 11 / 23 % | 3 / 9 % | 13 / 29 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 40 % | 34 / 48 % | 8 / 21 % | 1 / 8 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 37 % | 33 / 69 % | 6 / 26 % | 26 / 50 % | 9 / 23 % | 21 / 40 % | 3 / 8 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 27 / 83 % | 16 / 50 % | 13 / 36 % | 2 / 11 % | 8 / 22 % | 2 / 5 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 21 / 59 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 16 / 32 % | 0 / 0 % | 0 / 0 % | 9 / 28 % | 1 / 6 % | 12 / 25 % | 5 / 10 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 1 / 8 % | 14 / 27 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 14 / 64 % | 0 / 0 % | 6 / 17 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 12 / 27 % | 6 / 18 % | 1 / 7 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 24 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 1 / 4 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 30 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 79 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 9 / 41 % | 0 / 0 % | 6 / 14 % | 0 / 3 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 28 % | 1 / 7 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 4 / 59 % | 3 / 13 % | 7 / 19 % | 1 / 8 % | 5 / 13 % | 0 / 3 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 2 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 4 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 4 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
