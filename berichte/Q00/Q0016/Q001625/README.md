[English](README.md) · [Deutsch](README.de.md)

# Evaluating LLM Calibration for Coding-Agent Monitoring

Report Q001625 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/monitoring/evaluating-llm-calibration-for-coding-agent-monitoring)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Auszug berichtet, dass 16 Modelle die Schwere gezielt eingefügter Fehler in 2.904 Coding-Agent-Verläufen sehr unterschiedlich einschätzten; laut Autoren verbesserten Ensembles aus verschiedenen Modellfamilien die Übereinstimmung mit ihrer modellgestützten Referenz meist stärker als Wiederholungen eines einzelnen Modells. Die Ergebnisse bleiben durch die nicht objektive Referenz, synthetische Fehler, wenige Extremfälle und Unterschiede zwischen Fehlertypen begrenzt; der Auszug endet im Anhang und enthält anschließend überwiegend Abbildungsplatzhalter.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 54 % | 83 / 100 % | 29 / 70 % | – | 44 / 71 % | – | 23 / 49 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 27 / 48 % | 66 / 91 % | 13 / 37 % | – | 37 / 64 % | – | 11 / 32 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 49 % | 65 / 92 % | 8 / 26 % | – | 40 / 68 % | – | 9 / 28 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 18 / 42 % | 63 / 91 % | 10 / 36 % | – | 37 / 64 % | – | 7 / 25 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 20 / 41 % | 57 / 93 % | 5 / 19 % | – | 29 / 59 % | – | 4 / 17 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 3 / 37 % | 3 / 12 % | – | 38 / 67 % | – | 7 / 20 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 9 / 40 % | 0 / 3 % | – | 28 / 55 % | – | 3 / 10 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 23 / 45 % | 1 / 26 % | 2 / 8 % | – | 25 / 57 % | – | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 24 / 68 % | 1 / 7 % | – | 22 / 48 % | – | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 1 / 5 % | – | 11 / 31 % | – | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 1 / 5 % | – | 10 / 30 % | – | 1 / 7 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 10 / 27 % | – | 1 / 3 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 10 / 31 % | – | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 52 % | 1 / 8 % | – | 9 / 33 % | – | 3 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 7 / 30 % | 5 / 38 % | 1 / 6 % | – | 9 / 27 % | – | 2 / 10 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 26 % | – | 1 / 6 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 8 / 28 % | – | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 20 % | – | 1 / 6 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 15 % | – | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | – | 0 / 1 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | – | 1 / 5 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | – | 2 / 4 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 14 % | – | 1 / 4 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | – | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 19 % | 0 / 0 % | – | 0 / 0 % | – | 1 / 4 % |
