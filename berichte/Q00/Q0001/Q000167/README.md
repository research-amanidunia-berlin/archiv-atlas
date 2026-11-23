[English](README.md) · [Deutsch](README.de.md)

# GLM-5.3 and the spread of advanced cyber capabilities

Report Q000167 · Source anthropic.com · Date 2026-09-29 · [Open original](https://www.anthropic.com/research/glm-5-3-and-the-spread-of-advanced-cyber-capabilities)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge kann GLM-5.3 selbstständig Exploits entwickeln, und seine Schutzmechanismen lassen sich in Tests häufig umgehen oder durch eine Modelländerung weitgehend entfernen. Die Befunde stammen aus Benchmarks und kurzen, isolierten beziehungsweise simulierten Versuchen; laut Anthropic bilden diese reale Bedingungen nur unvollkommen ab.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 64 / 74 % | 96 / 98 % | 100 / 100 % | 34 / 47 % | 76 / 86 % | 90 / 93 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 59 / 72 % | 99 / 100 % | 100 / 100 % | 78 / 87 % | 41 / 57 % | 53 / 71 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 49 / 72 % | 97 / 100 % | 100 / 100 % | 80 / 89 % | 63 / 78 % | 81 / 90 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 42 / 59 % | 94 / 99 % | 100 / 100 % | 77 / 88 % | 29 / 53 % | 74 / 86 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 44 / 63 % | 88 / 98 % | 99 / 100 % | 86 / 91 % | 64 / 78 % | 81 / 89 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 58 % | 82 / 94 % | 95 / 97 % | 47 / 73 % | 43 / 62 % | 66 / 84 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 83 / 93 % | 94 / 96 % | 79 / 88 % | 22 / 37 % | 75 / 85 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 21 / 42 % | 0 / 0 % | 93 / 96 % | 23 / 51 % | 11 / 28 % | 18 / 38 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 53 % | 69 / 96 % | 92 / 96 % | 35 / 58 % | 20 / 41 % | 30 / 57 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 32 / 54 % | 69 / 92 % | 91 / 94 % | 45 / 66 % | 9 / 22 % | 23 / 41 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 45 % | 85 / 98 % | 90 / 94 % | 28 / 52 % | 12 / 23 % | 52 / 72 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 31 / 56 % | 72 / 99 % | 82 / 91 % | 58 / 80 % | 12 / 30 % | 33 / 60 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 17 / 92 % | 82 / 88 % | 15 / 36 % | 9 / 22 % | 12 / 25 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 40 / 59 % | 54 / 85 % | 72 / 75 % | 67 / 81 % | 34 / 50 % | 61 / 72 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 26 / 47 % | 15 / 63 % | 56 / 79 % | 69 / 85 % | 24 / 42 % | 70 / 82 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 55 / 87 % | 70 / 84 % | 10 / 25 % | 3 / 13 % | 6 / 14 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 52 / 79 % | 64 / 82 % | 15 / 36 % | 2 / 8 % | 11 / 22 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 56 / 98 % | 20 / 60 % | 14 / 32 % | 1 / 6 % | 8 / 18 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 49 / 64 % | 10 / 24 % | 0 / 0 % | 6 / 10 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 16 / 60 % | 46 / 68 % | 11 / 28 % | 4 / 14 % | 11 / 27 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 44 / 95 % | 0 / 0 % | 20 / 46 % | 12 / 24 % | 29 / 53 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 35 / 93 % | 20 / 48 % | 10 / 28 % | 5 / 14 % | 8 / 17 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 16 / 41 % | 31 / 98 % | 26 / 77 % | 33 / 59 % | 15 / 31 % | 17 / 48 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 33 / 55 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 15 / 36 % | 8 / 57 % | 31 / 52 % | 24 / 47 % | 9 / 21 % | 26 / 44 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 30 / 60 % | 11 / 38 % | 13 / 30 % | 2 / 6 % | 10 / 23 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 26 / 44 % | 9 / 21 % | 5 / 11 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 42 % | 18 / 81 % | 0 / 0 % | 11 / 32 % | 4 / 11 % | 17 / 37 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 18 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 26 % | 5 / 15 % | 7 / 15 % | – | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 5 / 11 % | 9 / 17 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 6 / 74 % | 9 / 37 % | 7 / 18 % | 3 / 7 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 18 % | 0 / 0 % | 7 / 21 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 4 / 8 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 5 / 11 % | 7 / 14 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 1 / 4 % | 4 / 8 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 1 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
