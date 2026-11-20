[English](README.md) · [Deutsch](README.de.md)

# Introducing Bloom: Automated behavioral evals

Report Q004198 · Source anthropic.com · Date 2025-12-19 · [Open original](https://www.anthropic.com/research/bloom)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic stellt Bloom vor, ein quelloffenes Framework, das Verhaltenstests für KI-Modelle automatisch erzeugt und bewertet. In den berichteten Validierungen trennte es auffällige Modellorganismen meist von Produktionsmodellen; die Übereinstimmung des besten Bewertungsmodells mit menschlichen Urteilen beruht auf 40 Transkripten. Der Beitrag verweist für technische Einzelheiten und Einschränkungen auf einen hier nicht enthaltenen Bericht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 47 / 69 % | 100 / 100 % | – | 99 / 100 % | 65 / 82 % | 67 / 80 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 34 / 61 % | 49 / 92 % | – | 95 / 98 % | 6 / 14 % | 41 / 62 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 57 / 74 % | 75 / 97 % | – | 95 / 97 % | 82 / 90 % | 81 / 88 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 46 / 67 % | 62 / 96 % | – | 85 / 92 % | 67 / 83 % | 64 / 78 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 29 / 59 % | – | 78 / 89 % | 47 / 72 % | 13 / 26 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 58 % | 40 / 95 % | – | 78 / 90 % | 39 / 68 % | 45 / 69 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 41 % | 48 / 85 % | – | 64 / 81 % | 18 / 40 % | 15 / 28 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 19 / 45 % | 63 / 92 % | – | 18 / 52 % | 22 / 51 % | 12 / 27 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 18 / 43 % | 48 / 94 % | – | 34 / 57 % | 12 / 37 % | 15 / 28 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 19 / 47 % | 0 / 0 % | – | 41 / 65 % | 11 / 29 % | 11 / 20 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 37 / 53 % | 6 / 17 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 18 / 41 % | 0 / 0 % | – | 18 / 40 % | 29 / 56 % | 17 / 31 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 13 / 38 % | 20 / 70 % | – | 26 / 50 % | 15 / 36 % | 9 / 19 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 19 / 42 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 17 / 48 % | 0 / 0 % | – | 0 / 0 % | 17 / 42 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 49 % | 8 / 41 % | – | 0 / 0 % | 8 / 21 % | 10 / 21 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 10 / 63 % | – | 15 / 33 % | 12 / 32 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 14 / 84 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 19 % | 10 / 19 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 1 / 5 % | 8 / 24 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 15 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 20 % | 5 / 11 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 7 / 38 % | – | 0 / 0 % | 7 / 19 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 6 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 4 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 5 / 24 % | 6 / 16 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
