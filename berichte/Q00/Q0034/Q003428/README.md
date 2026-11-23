[English](README.md) · [Deutsch](README.de.md)

# Key Concepts in AI Safety: Robustness and Adversarial Examples

Report Q003428 · Source cset.georgetown.edu · Date 2021-03-17 · [Open original](https://cset.georgetown.edu/publication/key-concepts-in-ai-safety-robustness-and-adversarial-examples/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Text ist nur ein Auszug: Er erklärt in der Einleitung, dass maschinelle Lernsysteme in sicherheitskritischen Anwendungen zuverlässig mit unterschiedlichen Eingaben umgehen müssen, und beschreibt Training sowie die begrenzte Verallgemeinerungsfähigkeit von Modellen. Die angekündigten Erläuterungen zu adversarialen Beispielen und zum Sicherheitsansatz fehlen im Auszug.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 63 / 87 % | 5 / 12 % | 0 / 4 % | 0 / 0 % | 0 / 3 % | 15 / 30 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 46 % | 13 / 83 % | 48 / 91 % | 13 / 41 % | 1 / 11 % | 8 / 34 % | 4 / 34 % | 30 / 60 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 24 / 48 % | 13 / 93 % | 27 / 67 % | 10 / 41 % | 1 / 11 % | 7 / 27 % | 3 / 27 % | 35 / 61 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 28 / 80 % | 0 / 0 % | 6 / 18 % | 0 / 4 % | 3 / 10 % | 0 / 6 % | 5 / 28 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 22 / 81 % | 1 / 18 % | 5 / 16 % | 0 / 2 % | 3 / 8 % | 0 / 4 % | 3 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 22 / 62 % | 0 / 0 % | 6 / 18 % | 1 / 6 % | 3 / 12 % | 0 / 6 % | 4 / 26 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 20 / 67 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 2 / 5 % | 0 / 3 % | 2 / 23 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 17 / 50 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 15 / 74 % | 1 / 36 % | 6 / 23 % | 0 / 3 % | 4 / 12 % | 0 / 8 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 13 / 52 % | 4 / 48 % | 5 / 11 % | 1 / 6 % | 4 / 14 % | 1 / 13 % | 6 / 24 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 12 / 84 % | 1 / 33 % | 6 / 21 % | 0 / 4 % | 5 / 14 % | 0 / 4 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 12 / 52 % | 0 / 0 % | 6 / 23 % | 1 / 6 % | 6 / 19 % | 0 / 10 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 8 / 60 % | 0 / 6 % | 5 / 19 % | 0 / 6 % | 3 / 10 % | 0 / 8 % | 12 / 42 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 10 / 48 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 5 / 10 % | 0 / 3 % | 4 / 22 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 10 / 61 % | 0 / 0 % | 6 / 23 % | 1 / 8 % | 7 / 21 % | 0 / 5 % | 9 / 30 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 5 % | 6 / 17 % | 0 / 3 % | 10 / 38 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 6 / 14 % | 0 / 3 % | 2 / 19 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 5 / 79 % | 0 / 0 % | 5 / 24 % | 1 / 6 % | 6 / 18 % | 1 / 10 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 6 / 13 % | 0 / 4 % | 5 / 24 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 2 % | 3 / 9 % | 0 / 2 % | 4 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 1 % | 2 / 4 % | 0 / 2 % | 4 / 27 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 2 / 4 % | 0 / 0 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 3 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 3 / 5 % | 0 / 0 % | 2 / 22 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 1 % | 2 / 4 % | 0 / 2 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 23 % | 5 / 11 % | 0 / 3 % | 2 / 6 % | 0 / 4 % | 2 / 14 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 9 % | 0 / 1 % | 3 / 5 % | 0 / 1 % | 3 / 20 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | 3 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 0 / 2 % | 1 / 4 % | 0 / 0 % | 4 / 18 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 3 / 5 % | 0 / 0 % | 1 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | 1 / 13 % |
