[English](README.md) · [Deutsch](README.de.md)

# Language modelling at scale: Gopher, ethical considerations, and retrieval

Report Q003143 · Source deepmind.google · Date 2021-12-08 · [Open original](https://deepmind.google/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

DeepMind berichtet, dass Gopher bei manchen Sprachaufgaben Fortschritte erzielt, aber weiterhin Stereotype spiegeln und falsche Antworten selbstsicher verbreiten kann; bestehende Prüfverfahren erfassten laut Bericht manche Risiken nicht ausreichend. Die Retrieval-Architektur RETRO soll mit deutlich weniger Parametern vergleichbare Leistung erreichen und durch abgerufene Textpassagen Einblicke in die Herkunft von Vorhersagen ermöglichen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 42 / 64 % | 99 / 100 % | 64 / 76 % | 93 / 98 % | 71 / 85 % | 58 / 74 % | 45 / 67 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 49 % | 45 / 89 % | 8 / 30 % | 96 / 99 % | 23 / 57 % | 23 / 57 % | 10 / 29 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 50 / 85 % | 1 / 10 % | 93 / 98 % | 14 / 43 % | 14 / 45 % | 3 / 20 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 52 % | 73 / 96 % | 14 / 52 % | 83 / 97 % | 35 / 66 % | 34 / 66 % | 11 / 38 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 12 / 59 % | 1 / 7 % | 76 / 92 % | 16 / 42 % | 5 / 14 % | 2 / 13 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 15 / 42 % | 33 / 82 % | 7 / 28 % | 66 / 92 % | 12 / 34 % | 12 / 41 % | 6 / 23 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 44 % | 21 / 62 % | 3 / 14 % | 66 / 85 % | 17 / 44 % | 15 / 40 % | 8 / 22 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 18 / 73 % | 5 / 21 % | 63 / 87 % | 26 / 58 % | 24 / 56 % | 7 / 23 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 52 / 94 % | 2 / 14 % | 38 / 83 % | 12 / 34 % | 11 / 26 % | 6 / 17 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 19 / 40 % | 12 / 74 % | 3 / 15 % | 51 / 83 % | 18 / 50 % | 8 / 39 % | 4 / 19 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 32 % | 45 / 86 % | 0 / 4 % | 10 / 41 % | 7 / 27 % | 5 / 12 % | 1 / 8 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 13 / 33 % | 35 / 82 % | 1 / 9 % | 30 / 77 % | 8 / 29 % | 8 / 31 % | 2 / 12 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 28 / 70 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 7 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 24 / 77 % | 1 / 10 % | 4 / 45 % | 9 / 26 % | 5 / 16 % | 2 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 22 / 82 % | 1 / 9 % | 2 / 32 % | 14 / 39 % | 8 / 24 % | 3 / 14 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 9 / 95 % | 2 / 10 % | 20 / 60 % | 11 / 29 % | 17 / 42 % | 9 / 24 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 16 / 38 % | 12 / 40 % | 1 / 5 % | 2 / 17 % | 19 / 47 % | 13 / 27 % | 2 / 11 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 6 % | 18 / 67 % | 7 / 23 % | 5 / 16 % | 2 / 10 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 17 / 81 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 5 / 10 % | 1 / 6 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 9 / 30 % | 17 / 97 % | 0 / 4 % | 16 / 50 % | 7 / 26 % | 7 / 22 % | 2 / 11 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 9 / 34 % | 16 / 83 % | 0 / 5 % | 11 / 66 % | 11 / 36 % | 7 / 21 % | 1 / 15 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 16 / 82 % | 1 / 6 % | 0 / 0 % | 6 / 20 % | 7 / 20 % | 1 / 7 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 16 / 57 % | 0 / 5 % | 3 / 19 % | 6 / 19 % | 4 / 15 % | 1 / 10 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 16 / 66 % | 0 / 3 % | 0 / 0 % | 9 / 24 % | 7 / 16 % | 2 / 9 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 16 / 56 % | 0 / 4 % | 3 / 26 % | 6 / 21 % | 4 / 13 % | 1 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 33 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 13 / 53 % | 0 / 2 % | 0 / 0 % | 5 / 12 % | 5 / 11 % | 1 / 6 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 12 / 34 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 7 / 21 % | 7 / 21 % | 1 / 9 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 6 / 30 % | 12 / 73 % | 0 / 4 % | 1 / 24 % | 6 / 18 % | 5 / 18 % | 1 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 3 / 11 % | 0 / 3 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 27 % | 5 / 15 % | 3 / 10 % | 1 / 5 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 7 / 26 % | 4 / 12 % | 1 / 8 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 23 % | 6 / 16 % | 6 / 19 % | 1 / 7 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 5 / 14 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 3 / 8 % | 1 / 5 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 3 / 9 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 2 / 5 % | 0 / 4 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 5 / 13 % | 1 / 6 % |
