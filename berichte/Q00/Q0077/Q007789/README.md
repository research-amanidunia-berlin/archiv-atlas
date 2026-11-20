[English](README.md) · [Deutsch](README.de.md)

# CLIP: Connecting text and images

Report Q007789 · Source openai.com · Date 2021-01-05 · [Open original](https://openai.com/index/clip/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt CLIP als Bild-Text-Modell vor, das laut OpenAI viele Klassifikationsaufgaben durch sprachliche Kategorien ohne zusätzliche aufgabenspezifische Trainingsbeispiele lösen kann. Die berichteten Tests zeigen Vorteile auf mehreren Datensätzen außerhalb von ImageNet, aber Schwächen bei Zählen, feinen Unterscheidungen und handgeschriebenen Ziffern sowie eine Abhängigkeit von der Formulierung und Risiken durch Verzerrungen und mögliche Überwachung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 97 / 100 % | – | 89 / 95 % | 20 / 47 % | 8 / 19 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 46 / 86 % | – | 97 / 98 % | 13 / 36 % | 9 / 26 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 68 / 97 % | – | 88 / 90 % | 8 / 25 % | 6 / 16 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 52 / 94 % | – | 88 / 94 % | 10 / 30 % | 8 / 23 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 20 / 57 % | – | 74 / 81 % | 8 / 23 % | 6 / 16 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 71 / 82 % | 6 / 18 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 30 / 58 % | – | 71 / 85 % | 6 / 13 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 34 / 75 % | – | 70 / 84 % | 10 / 28 % | 8 / 17 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | – | 36 / 52 % | 6 / 14 % | 8 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 33 / 51 % | – | 32 / 60 % | 6 / 17 % | 5 / 13 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 22 / 83 % | – | 29 / 50 % | 6 / 15 % | 3 / 9 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 25 / 81 % | – | 28 / 40 % | 21 / 44 % | 8 / 15 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | – | 23 / 41 % | 6 / 16 % | 4 / 11 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 9 / 45 % | – | 0 / 0 % | 6 / 11 % | 6 / 13 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 9 / 27 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 8 / 16 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 49 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 6 / 46 % | – | 0 / 0 % | 5 / 13 % | 5 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 5 / 12 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 4 / 50 % | – | 0 / 0 % | 0 / 0 % | 4 / 9 % |
