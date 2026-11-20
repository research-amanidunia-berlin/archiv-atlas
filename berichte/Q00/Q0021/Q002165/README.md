[English](README.md) · [Deutsch](README.de.md)

# HiBayES: Improving LLM evaluation with hierarchical Bayesian modelling

Report Q002165 · Source aisi.gov.uk · Date 2025-05-12 · [Open original](https://www.aisi.gov.uk/blog/hibayes-improving-llm-evaluation-with-hierarchical-bayesian-modelling)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt HiBayES vor, ein hierarchisches bayessches Verfahren, das laut den Autorinnen und Autoren LLM-Leistung in komplexen und kleinen Benchmarks differenzierter schätzt und Unsicherheit über mehrere Datenebenen erfasst. Die berichteten Beispiele betreffen einzelne Modelle, Modellvergleiche und agentische GAIA-Aufgaben; die Ergebnisse beruhen auf öffentlichen Benchmarks mit Inspect und bestätigen ausdrücklich keine Herstellerangaben zu Modellfähigkeiten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 53 % | 68 / 97 % | – | 49 / 77 % | 26 / 59 % | 31 / 57 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 27 / 52 % | 57 / 96 % | – | 20 / 67 % | 6 / 15 % | 25 / 50 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 40 / 88 % | – | 0 / 0 % | 6 / 20 % | 8 / 18 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 4 / 60 % | – | 30 / 62 % | 11 / 33 % | 10 / 28 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 10 / 94 % | – | 22 / 49 % | 26 / 57 % | 9 / 25 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 17 / 78 % | – | 22 / 28 % | 13 / 30 % | 7 / 17 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 21 / 82 % | – | 0 / 0 % | 6 / 19 % | 5 / 11 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 39 % | 14 / 30 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 1 / 11 % | 12 / 38 % | 8 / 21 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 3 / 65 % | – | 0 / 0 % | 11 / 34 % | 9 / 23 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 35 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 9 / 40 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 7 / 80 % | – | 0 / 0 % | 6 / 17 % | 8 / 18 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 7 / 14 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 5 / 68 % | – | 0 / 0 % | 7 / 27 % | 5 / 14 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 7 / 68 % | – | 0 / 0 % | 7 / 18 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 23 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 4 / 8 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 3 / 25 % | 5 / 14 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 36 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
