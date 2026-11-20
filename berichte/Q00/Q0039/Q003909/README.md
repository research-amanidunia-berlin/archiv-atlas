[English](README.md) · [Deutsch](README.de.md)

# A "diff" tool for AI models

Report Q003909 · Source anthropic.com · Date 2026-03-13 · [Open original](https://www.anthropic.com/research/diff-tool)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic stellt den DFC vor, ein Verfahren, das einzigartige Verhaltensmerkmale unterschiedlicher KI-Modelle auffinden und durch gezielte Veränderung auf ihre Wirkung prüfen soll. In Modellvergleichen identifizierte das Team nach eigener Darstellung Merkmale für parteinahe Rhetorik, amerikanische Überlegenheitsbehauptungen und die Ablehnung urheberrechtlich geschützter Inhalte. Die Methode ist ein Screening mit Grenzen: Viele Treffer dürften nicht relevant sein, die Ursache der Merkmale bleibt offen, und Frontier-Modelle wurden nicht untersucht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 48 / 67 % | 92 / 99 % | – | 99 / 100 % | 47 / 71 % | 45 / 65 % | 43 / 64 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 56 / 72 % | 71 / 94 % | – | 99 / 100 % | 81 / 89 % | 58 / 76 % | 69 / 81 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 36 / 56 % | 51 / 95 % | – | 96 / 98 % | 60 / 79 % | 10 / 25 % | 14 / 28 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 33 / 57 % | 42 / 89 % | – | 84 / 94 % | 30 / 59 % | 10 / 29 % | 21 / 49 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 61 % | 83 / 99 % | – | 66 / 88 % | 35 / 64 % | 33 / 57 % | 39 / 65 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 30 / 57 % | 56 / 97 % | – | 77 / 91 % | 6 / 15 % | 11 / 30 % | 28 / 55 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 36 / 59 % | 66 / 99 % | – | 77 / 91 % | 42 / 70 % | 18 / 36 % | 22 / 53 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 16 / 42 % | 27 / 70 % | – | 51 / 80 % | 10 / 29 % | 3 / 8 % | 7 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 7 / 53 % | – | 46 / 71 % | 10 / 24 % | 0 / 0 % | 5 / 9 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 27 / 78 % | – | 44 / 70 % | 7 / 15 % | 3 / 7 % | 6 / 12 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 40 / 84 % | – | 23 / 50 % | 8 / 21 % | 3 / 8 % | 9 / 20 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 19 / 38 % | 29 / 61 % | – | 10 / 48 % | 23 / 50 % | 4 / 17 % | 18 / 37 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 21 / 67 % | – | 1 / 6 % | 6 / 12 % | 1 / 5 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 20 / 52 % | 0 / 0 % | – | 0 / 0 % | 12 / 36 % | 5 / 15 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 20 / 54 % | – | 11 / 46 % | 6 / 17 % | 1 / 4 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 17 / 51 % | 5 / 16 % | 1 / 4 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 14 / 76 % | – | 12 / 50 % | 15 / 46 % | 6 / 18 % | 10 / 22 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 15 / 33 % | 9 / 23 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 23 % | 3 / 8 % | 5 / 8 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 2 / 7 % | 10 / 21 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 6 / 53 % | – | 2 / 16 % | 10 / 26 % | 2 / 9 % | 7 / 16 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 24 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 2 / 48 % | – | 0 / 0 % | 6 / 22 % | 3 / 10 % | 8 / 16 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 63 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 7 / 65 % | – | 0 / 0 % | 6 / 16 % | 1 / 6 % | 6 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 1 / 3 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 3 / 9 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 0 / 0 % | 3 / 5 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 1 / 4 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 5 / 16 % | 5 / 10 % | 1 / 3 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 5 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 4 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 5 / 62 % | – | 0 / 0 % | 5 / 12 % | 1 / 5 % | 4 / 8 % |
