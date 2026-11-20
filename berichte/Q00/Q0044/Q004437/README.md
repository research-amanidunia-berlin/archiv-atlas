[English](README.md) · [Deutsch](README.de.md)

# Automated researchers can reliably mitigate alignment failures

Report Q004437 · Source anthropic.com · Date 2026-08-28 · [Open original](https://www.anthropic.com/research/automated-researchers-mitigate-alignment-failures)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge konnte Claude in Experimenten zehn Arten von Alignment-Fehlern verringern und erzielte auch bei zurückgehaltenen Tests sowie größeren Modellen Erfolge. Der Bericht betont jedoch, dass die Benchmarks nur einen begrenzten Ausschnitt abdecken und weder reale Fehlanpassung noch die dauerhafte Wirkung nach weiterem Training vollständig geprüft wurden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 42 / 62 % | 100 / 100 % | – | 100 / 100 % | 68 / 83 % | 35 / 56 % | 59 / 79 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 32 / 54 % | 51 / 87 % | – | 100 / 100 % | 65 / 80 % | 14 / 30 % | 24 / 43 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 50 / 68 % | 95 / 99 % | – | 93 / 97 % | 72 / 85 % | 50 / 69 % | 66 / 81 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 93 / 97 % | – | 34 / 61 % | 25 / 54 % | 5 / 14 % | 15 / 39 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 37 / 57 % | 69 / 96 % | – | 92 / 96 % | 44 / 69 % | 14 / 35 % | 45 / 71 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 38 / 58 % | 63 / 93 % | – | 90 / 93 % | 63 / 80 % | 33 / 58 % | 68 / 81 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 28 / 51 % | 75 / 96 % | – | 86 / 90 % | 15 / 40 % | 8 / 18 % | 15 / 33 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 22 / 49 % | 14 / 48 % | – | 86 / 93 % | 8 / 19 % | 9 / 25 % | 26 / 54 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 48 / 66 % | 75 / 96 % | – | 77 / 86 % | 77 / 87 % | 45 / 65 % | 82 / 89 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 16 / 41 % | 22 / 52 % | – | 72 / 84 % | 23 / 42 % | 1 / 5 % | 13 / 23 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 25 / 43 % | 63 / 85 % | – | 42 / 49 % | 57 / 73 % | 6 / 17 % | 24 / 36 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 49 / 78 % | – | 51 / 65 % | 21 / 45 % | 4 / 11 % | 15 / 31 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 47 / 62 % | 31 / 58 % | 3 / 9 % | 9 / 22 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 15 / 57 % | – | 46 / 67 % | 21 / 46 % | 0 / 0 % | 11 / 23 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 44 / 85 % | – | 40 / 60 % | 9 / 25 % | 1 / 5 % | 6 / 11 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 12 / 55 % | – | 38 / 49 % | 9 / 22 % | 1 / 5 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 12 / 43 % | – | 36 / 44 % | 21 / 48 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 29 / 59 % | – | 30 / 55 % | 9 / 23 % | 1 / 4 % | 6 / 15 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 36 % | 26 / 66 % | – | 0 / 0 % | 14 / 33 % | 7 / 16 % | 10 / 23 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 23 / 46 % | 3 / 10 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 20 / 42 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 12 / 40 % | 0 / 0 % | – | 0 / 0 % | 19 / 44 % | 4 / 12 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 31 % | 0 / 0 % | 13 / 25 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 32 % | 0 / 0 % | 10 / 22 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 12 / 35 % | 5 / 17 % | 1 / 4 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 23 % | 1 / 5 % | 10 / 33 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 10 / 41 % | – | 0 / 0 % | 6 / 15 % | 1 / 5 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 23 % | 1 / 3 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 5 / 13 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 8 / 46 % | – | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 0 / 0 % | 5 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 2 / 6 % | 6 / 14 % | 1 / 4 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 2 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 1 / 3 % | 3 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 2 % | 4 / 10 % |
