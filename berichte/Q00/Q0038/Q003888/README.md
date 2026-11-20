[English](README.md) · [Deutsch](README.de.md)

# Gemini Robotics 1.5 brings AI agents into the physical world

Report Q003888 · Source deepmind.google · Date 2025-09-25 · [Open original](https://deepmind.google/blog/gemini-robotics-15-brings-ai-agents-into-the-physical-world/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind beschreibt zwei zusammenwirkende Robotikmodelle: ER 1.5 soll planen, die Umgebung verstehen und Werkzeuge nutzen; Robotics 1.5 soll die geplanten Schritte in Bewegungen umsetzen, vor dem Handeln nachdenken und Fähigkeiten zwischen Robotertypen übertragen. Das Unternehmen meldet Spitzenwerte in Benchmarks und Fortschritte bei Sicherheitsfunktionen, doch der Beitrag erläutert die Messwerte und Testbedingungen nur begrenzt und stellt keine unabhängige Prüfung dar.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 29 / 50 % | 65 / 90 % | 15 / 46 % | 95 / 99 % | 59 / 77 % | 31 / 53 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 27 / 47 % | 85 / 98 % | 15 / 26 % | 93 / 96 % | 37 / 65 % | 47 / 68 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 48 % | 65 / 87 % | 12 / 29 % | 91 / 95 % | 58 / 78 % | 45 / 68 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 18 / 39 % | 61 / 89 % | 10 / 20 % | 88 / 93 % | 47 / 72 % | 43 / 64 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 24 / 44 % | 70 / 98 % | 9 / 20 % | 83 / 92 % | 35 / 66 % | 24 / 53 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 60 / 89 % | 0 / 2 % | 75 / 89 % | 20 / 47 % | 11 / 21 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 21 / 74 % | 1 / 3 % | 75 / 84 % | 10 / 31 % | 14 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 10 / 57 % | 0 / 0 % | 72 / 86 % | 9 / 29 % | 9 / 17 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 10 / 63 % | 0 / 0 % | 69 / 81 % | 14 / 34 % | 6 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 17 / 46 % | 0 / 0 % | 67 / 82 % | 19 / 40 % | 11 / 19 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 11 / 29 % | 54 / 92 % | 0 / 2 % | 15 / 35 % | 7 / 27 % | 8 / 15 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 36 % | 46 / 76 % | 4 / 9 % | 53 / 69 % | 19 / 45 % | 17 / 34 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 42 / 75 % | 0 / 0 % | 9 / 19 % | 10 / 25 % | 7 / 14 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 39 / 74 % | 1 / 4 % | 29 / 57 % | 9 / 27 % | 8 / 22 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 34 / 64 % | 3 / 9 % | 12 / 33 % | 18 / 43 % | 11 / 23 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 40 % | 0 / 0 % | 34 / 48 % | 8 / 21 % | 5 / 11 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 37 % | 33 / 69 % | 3 / 8 % | 6 / 26 % | 26 / 50 % | 21 / 40 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 27 / 83 % | 2 / 5 % | 16 / 50 % | 13 / 36 % | 8 / 22 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 21 / 59 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 16 / 32 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 9 / 28 % | 12 / 25 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 14 / 27 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 14 / 64 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 27 % | 6 / 18 % | 4 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 11 / 24 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 7 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 30 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 10 / 79 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 5 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 9 / 41 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 5 / 9 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 19 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 28 % | 5 / 11 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 4 / 59 % | 0 / 3 % | 3 / 13 % | 7 / 19 % | 5 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 5 / 10 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 5 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 5 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % |
