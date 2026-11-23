[English](README.md) · [Deutsch](README.de.md)

# GLM-5.3

Report Q004650 · Source docs.z.ai · Date – · [Open original](https://docs.z.ai/guides/llm/glm-5.3)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Z.ai zufolge verbessert GLM-5.3 gegenüber GLM-5.2 die Leistungen bei Programmier-, Agenten- und Cybersicherheitsaufgaben; der Bericht nennt dazu Anbieterbenchmarks und Prüfungen realer Codebasen, betont aber auch verbleibende Abstände zu einigen Vergleichsmodellen und den weiterhin nötigen menschlichen Aufwand bei der Aufgabenerzeugung. Das Modell verarbeitet derzeit nur Text, hat ein Kontextfenster von einer Million Tokens und arbeitet stets mit aktiviertem Schlussfolgern; die genannten Ergebnisse werden im Bericht nicht unabhängig überprüft.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 50 / 67 % | 99 / 100 % | 99 / 100 % | 6 / 12 % | 29 / 44 % | 59 / 74 % | 77 / 87 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 79 / 95 % | 95 / 97 % | 15 / 40 % | 2 / 9 % | 10 / 24 % | 3 / 11 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 77 / 97 % | 93 / 96 % | 19 / 49 % | 0 / 0 % | 15 / 29 % | 3 / 8 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 46 % | 83 / 97 % | 92 / 96 % | 33 / 62 % | 14 / 26 % | 44 / 65 % | 9 / 21 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 78 / 96 % | 42 / 58 % | 39 / 65 % | 0 / 0 % | 30 / 49 % | 5 / 17 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 62 / 73 % | 42 / 66 % | 6 / 13 % | 12 / 25 % | 4 / 10 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 55 / 72 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 2 / 19 % | 53 / 66 % | 9 / 33 % | 2 / 6 % | 8 / 15 % | 1 / 5 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 30 / 61 % | 52 / 60 % | 11 / 31 % | 4 / 9 % | 15 / 27 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 43 / 51 % | 6 / 15 % | 0 / 0 % | 4 / 10 % | 0 / 0 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 15 / 44 % | 42 / 50 % | 6 / 15 % | 1 / 3 % | 8 / 15 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 34 / 64 % | 40 / 65 % | 25 / 49 % | 0 / 0 % | 13 / 26 % | 3 / 13 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 36 / 67 % | 29 / 47 % | 10 / 31 % | 2 / 8 % | 13 / 24 % | 3 / 9 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 34 / 51 % | 0 / 0 % | 11 / 32 % | 0 / 0 % | 6 / 12 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 26 / 66 % | 0 / 0 % | 10 / 26 % | 2 / 6 % | 6 / 15 % | 1 / 6 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 41 % | 0 / 0 % | 10 / 20 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 35 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 32 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 39 % | 0 / 0 % | 12 / 24 % | 1 / 5 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 32 % | 0 / 0 % | 7 / 15 % | 2 / 6 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 19 % | 1 / 4 % | 7 / 15 % | 0 / 0 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 7 / 64 % | 0 / 0 % | 6 / 27 % | 0 / 0 % | 4 / 8 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 2 / 6 % | 7 / 14 % | 0 / 2 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 4 / 11 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 17 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 23 % | 0 / 0 % | 6 / 18 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
