[English](README.md) · [Deutsch](README.de.md)

# https://arxiv.org/pdf/2109.07958

Report Q009455 · Source arxiv.org · Date – · [Open original](https://arxiv.org/pdf/2109.07958)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt TruthfulQA vor: 817 gezielt auf verbreitete Irrtümer ausgerichtete Fragen, mit denen die Wahrheitsgemäßheit von Sprachmodellen geprüft wird. Laut Studie erreichte das beste zentrale Modell 58 Prozent wahre Antworten gegenüber 94 Prozent bei einer menschlichen Vergleichsperson; größere Modelle waren oft weniger wahrheitsgemäß, aber informativer. Der Benchmark deckt weder Fachzuverlässigkeit noch lange oder interaktive Anwendungen ab.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 46 % | 62 / 94 % | – | 100 / 100 % | 39 / 68 % | 17 / 37 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 38 / 95 % | – | 90 / 94 % | 45 / 70 % | 19 / 42 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 0 / 0 % | – | 87 / 90 % | 34 / 60 % | 22 / 45 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 42 / 60 % | – | 80 / 88 % | 59 / 78 % | 34 / 54 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 39 / 69 % | – | 70 / 85 % | 11 / 30 % | 7 / 14 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 54 / 76 % | – | 68 / 84 % | 29 / 59 % | 7 / 18 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 16 / 70 % | – | 62 / 68 % | 9 / 28 % | 10 / 22 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 14 / 59 % | – | 58 / 77 % | 16 / 42 % | 6 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 39 / 77 % | – | 55 / 67 % | 10 / 33 % | 11 / 22 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 50 / 83 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 44 / 78 % | – | 34 / 54 % | 9 / 30 % | 8 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 39 / 69 % | – | 23 / 64 % | 7 / 24 % | 6 / 15 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 25 / 96 % | – | 38 / 67 % | 11 / 33 % | 10 / 26 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 28 / 82 % | – | 34 / 67 % | 7 / 22 % | 7 / 15 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 32 / 62 % | – | 0 / 0 % | 18 / 43 % | 8 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 26 / 77 % | – | 0 / 0 % | 6 / 20 % | 4 / 12 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 24 / 62 % | – | 0 / 0 % | 5 / 15 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | – | 22 / 49 % | 12 / 37 % | 9 / 21 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 20 / 77 % | – | 0 / 0 % | 7 / 18 % | 3 / 8 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 16 / 53 % | 6 / 22 % | 3 / 10 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 11 / 62 % | – | 1 / 10 % | 6 / 18 % | 3 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 23 % | 9 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 31 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 8 / 17 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 8 / 15 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 7 / 12 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 7 / 17 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 16 % | 4 / 7 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
