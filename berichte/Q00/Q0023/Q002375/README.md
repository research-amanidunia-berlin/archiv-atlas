[English](README.md) · [Deutsch](README.de.md)

# Details about METR's preliminary evaluation of DeepSeek and Qwen models

Report Q002375 · Source metr.org · Date 2025-06-27 · [Open original](https://metr.org/evaluations/deepseek-qwen-report/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

METR berichtet vorläufig, dass DeepSeek-Modelle aus Mitte 2025 bei der autonomen Erledigung von Softwareaufgaben ungefähr das Niveau führender Modelle von Ende 2024 erreichen; Qwen2-72B und Qwen2.5-72B schneiden in den Zeithorizont-Schätzungen niedriger ab. Die Tests umfassten 1.048 Durchläufe pro Modell und ergaben je nach Modell 2 bis 15 erkannte Täuschungsversuche. Begrenzte Testzeit, Tokenbudgets, API-Zuverlässigkeit und fehlende Robustheit gegen absichtliches Zurückhalten schränken die Aussagekraft ein.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 40 / 62 % | 100 / 100 % | 15 / 39 % | 100 / 100 % | 43 / 69 % | 25 / 46 % | 50 / 69 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 50 % | 26 / 93 % | 9 / 32 % | 93 / 96 % | 29 / 56 % | 5 / 15 % | 20 / 45 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 18 / 45 % | 92 / 96 % | 50 / 74 % | 11 / 29 % | 13 / 30 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 29 / 52 % | 0 / 0 % | 13 / 25 % | 88 / 93 % | 59 / 76 % | 7 / 16 % | 23 / 40 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 46 / 61 % | 10 / 44 % | 9 / 17 % | 85 / 89 % | 47 / 67 % | 7 / 18 % | 19 / 35 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 41 / 80 % | 1 / 9 % | 83 / 90 % | 24 / 47 % | 8 / 17 % | 21 / 37 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 6 / 14 % | 80 / 84 % | 46 / 68 % | 0 / 0 % | 31 / 47 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 43 / 68 % | 63 / 91 % | 26 / 64 % | 37 / 55 % | 0 / 0 % | 27 / 51 % | 43 / 64 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 47 / 60 % | 12 / 36 % | 5 / 14 % | 14 / 28 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 46 / 66 % | 7 / 14 % | 0 / 0 % | 7 / 12 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 24 / 51 % | 0 / 0 % | 3 / 21 % | 23 / 46 % | 37 / 68 % | 0 / 0 % | 19 / 43 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 2 / 11 % | 0 / 0 % | 28 / 54 % | 3 / 10 % | 13 / 28 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 19 / 45 % | 9 / 47 % | 3 / 18 % | 10 / 38 % | 23 / 55 % | 0 / 0 % | 14 / 33 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 42 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 47 % | 0 / 0 % | 2 / 9 % | 0 / 0 % | 22 / 49 % | 4 / 11 % | 12 / 23 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 50 % | 0 / 0 % | 1 / 7 % | 0 / 0 % | 11 / 39 % | 1 / 6 % | 15 / 28 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 28 % | 6 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 40 % | 6 / 17 % | 0 / 2 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 32 % | 0 / 1 % | 10 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 1 / 5 % | 11 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 24 % | 2 / 8 % | 8 / 18 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 22 % | 1 / 4 % | 9 / 17 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 1 / 5 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 17 % | 0 / 2 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 5 / 9 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 4 / 7 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 2 % | 6 / 13 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 1 / 3 % | 6 / 12 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 1 % | 6 / 14 % |
