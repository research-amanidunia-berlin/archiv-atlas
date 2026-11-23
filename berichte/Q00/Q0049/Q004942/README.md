[English](README.md) · [Deutsch](README.de.md)

# Question decomposition improves reasoning faithfulness

Report Q004942 · Source anthropic.com · Date 2023-07-18 · [Open original](https://www.anthropic.com/research/question-decomposition-improves-the-faithfulness-of-model-generated-reasoning)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Text ist nur der Abstract eines Berichts. Darin heißt es, dass das Zerlegen von Fragen in getrennt beantwortete Teilfragen die Treue modellgenerierter Begründungen gegenüber Chain-of-Thought verbessern könne, während die Leistung bei Frage-Antwort-Aufgaben teilweise ähnlich bleibe. Konkrete Versuchsdaten oder Messwerte enthält der Auszug nicht.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 47 % | 33 / 79 % | 87 / 95 % | 15 / 44 % | 6 / 16 % | 12 / 29 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 47 / 66 % | 32 / 80 % | 36 / 76 % | 60 / 80 % | 38 / 55 % | 59 / 72 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 50 % | 35 / 76 % | 48 / 76 % | 17 / 46 % | 4 / 13 % | 14 / 31 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 36 / 62 % | 7 / 21 % | 2 / 5 % | 0 / 0 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 27 / 51 % | 11 / 61 % | 10 / 39 % | 21 / 54 % | 13 / 25 % | 10 / 22 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 13 / 37 % | 6 / 22 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 11 / 32 % | 0 / 0 % | 2 / 28 % | 0 / 0 % | 1 / 3 % | 5 / 11 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 3 / 33 % | 6 / 20 % | 0 / 0 % | 5 / 12 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 1 % | 6 / 13 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 1 / 2 % | 6 / 10 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 21 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 3 % | 5 / 13 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 5 / 40 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 5 / 11 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 3 / 33 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 20 % | 0 / 0 % | 0 / 1 % | 0 / 0 % | – | – |
