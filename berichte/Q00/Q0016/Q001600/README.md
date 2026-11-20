[English](README.md) · [Deutsch](README.de.md)

# Why we no longer evaluate SWE-bench Verified

Report Q001600 · Source openai.com · Date 2026-02-23 · [Open original](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, dass fehlerhafte oder unpassend enge Tests sowie mögliche Trainingsdaten-Kontamination SWE-bench Verified als Fortschrittsmaß unzuverlässig machen: In einer Prüfung von 138 schwierigen Aufgaben wiesen 59,4 Prozent erhebliche Mängel auf. Das Unternehmen empfiehlt SWE-bench Pro, betont aber, dass auch diese Benchmark nicht perfekt ist und die Befunde auf begrenzten eigenen Analysen beruhen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 57 % | 99 / 100 % | – | 100 / 100 % | 59 / 77 % | 41 / 61 % | 50 / 66 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 72 / 87 % | – | 92 / 95 % | 19 / 40 % | 7 / 15 % | 14 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 86 / 97 % | – | 79 / 88 % | 45 / 66 % | 0 / 0 % | 30 / 43 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 35 % | 0 / 0 % | – | 84 / 90 % | 8 / 27 % | 0 / 0 % | 12 / 23 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 72 / 94 % | – | 40 / 60 % | 11 / 29 % | 0 / 0 % | 12 / 24 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 68 / 95 % | – | 68 / 77 % | 10 / 32 % | 8 / 19 % | 9 / 18 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 36 / 58 % | 53 / 88 % | – | 0 / 0 % | 33 / 48 % | 29 / 49 % | 34 / 53 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 19 / 68 % | – | 46 / 59 % | 15 / 37 % | 0 / 0 % | 11 / 22 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 44 / 82 % | – | 0 / 0 % | 17 / 34 % | 0 / 0 % | 12 / 21 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 39 / 63 % | 7 / 17 % | 9 / 18 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 38 / 69 % | – | 0 / 0 % | 8 / 24 % | 0 / 0 % | 11 / 21 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 27 / 47 % | 33 / 56 % | 0 / 0 % | 13 / 27 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 33 / 55 % | 9 / 25 % | 4 / 10 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 23 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 20 / 42 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 16 / 39 % | 0 / 0 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 11 / 41 % | – | 0 / 0 % | 5 / 14 % | 1 / 5 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 9 / 15 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 14 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 1 / 5 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 1 / 4 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 1 / 4 % | 0 / 0 % |
