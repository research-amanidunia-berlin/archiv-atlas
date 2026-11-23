[English](README.md) · [Deutsch](README.de.md)

# Measuring the performance of our models on real-world tasks

Report Q006943 · Source openai.com · Date 2025-09-25 · [Open original](https://openai.com/index/gdpval/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI stellt GDPval als Benchmark für realitätsnahe Wissensarbeit vor und berichtet, dass führende Modelle bei einem Teil der Aufgaben bereits Fachleuten nahekommen. Die Evaluation ist jedoch ein Ein-Durchgang-Test; zudem widerspricht sich der Bericht bei der Leistungssteigerung von GPT-4o zu GPT-5: Im Text steht mehr als eine Verdopplung, in der Bildunterschrift mehr als eine Verdreifachung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 32 / 51 % | 66 / 87 % | 99 / 100 % | 38 / 67 % | 23 / 45 % | 45 / 67 % | 39 / 65 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 57 / 91 % | 95 / 98 % | 22 / 45 % | 7 / 19 % | 17 / 34 % | 2 / 7 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 39 / 80 % | 91 / 95 % | 7 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 84 / 96 % | 15 / 37 % | 12 / 34 % | 1 / 9 % | 7 / 16 % | 1 / 5 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 49 / 80 % | 83 / 89 % | 10 / 33 % | 8 / 18 % | 10 / 22 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 67 / 82 % | 13 / 38 % | 3 / 11 % | 6 / 13 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 42 / 88 % | 54 / 73 % | 13 / 34 % | 5 / 18 % | 11 / 27 % | 2 / 8 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 48 / 65 % | 18 / 37 % | 4 / 10 % | 10 / 20 % | 0 / 0 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 36 / 78 % | 47 / 72 % | 13 / 37 % | 4 / 15 % | 10 / 27 % | 1 / 8 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 40 / 64 % | 16 / 40 % | 5 / 17 % | 8 / 18 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 39 / 77 % | 20 / 47 % | 10 / 32 % | 2 / 10 % | 8 / 23 % | 0 / 0 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 37 / 59 % | 0 / 0 % | 7 / 21 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 23 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 41 % | 4 / 13 % | 8 / 17 % | 0 / 0 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 35 % | 4 / 10 % | 6 / 15 % | 0 / 0 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 6 / 32 % | 0 / 0 % | 9 / 26 % | 6 / 20 % | 7 / 19 % | 2 / 11 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 9 / 54 % | 0 / 0 % | 7 / 24 % | 2 / 9 % | 5 / 12 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 24 % | 1 / 7 % | 5 / 14 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 2 / 7 % | 7 / 15 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 4 % | 7 / 16 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 2 / 36 % | 0 / 0 % | 7 / 25 % | 1 / 7 % | 3 / 10 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 2 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 5 / 27 % | 6 / 17 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
