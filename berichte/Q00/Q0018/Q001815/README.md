[English](README.md) · [Deutsch](README.de.md)

# Measuring LLMs’ ability to develop exploits

Report Q001815 · Source anthropic.com · Date 2026-05-22 · [Open original](https://www.anthropic.com/research/exploit-evals)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic zufolge übertrifft Claude Mythos Preview andere getestete Modelle in Benchmarks für Exploit-Entwicklung deutlich, darunter bei V8- und Kernel-Angriffen sowie simulierten Smart-Contract-Exploits. Die Ergebnisse stammen aus begrenzten Testumgebungen; der Bericht leitet daraus ein wachsendes Risiko ab und fordert umfassendere Benchmarks und Schutzmaßnahmen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 83 / 89 % | 100 / 100 % | 100 / 100 % | 8 / 20 % | 92 / 94 % | 93 / 95 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 48 / 65 % | 92 / 98 % | 99 / 100 % | 64 / 81 % | 71 / 83 % | 80 / 89 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 35 / 78 % | 95 / 98 % | 73 / 85 % | 19 / 37 % | 29 / 55 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 77 / 96 % | 95 / 97 % | 38 / 63 % | 6 / 19 % | 23 / 47 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 75 / 96 % | 92 / 96 % | 27 / 53 % | 10 / 22 % | 33 / 54 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 47 % | 0 / 0 % | 82 / 89 % | 37 / 60 % | 13 / 28 % | 20 / 39 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 25 / 47 % | 16 / 61 % | 79 / 92 % | 22 / 41 % | 4 / 10 % | 22 / 36 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 28 / 53 % | 71 / 97 % | 23 / 58 % | 43 / 70 % | 8 / 20 % | 25 / 51 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 35 / 63 % | 66 / 76 % | 23 / 50 % | 17 / 31 % | 29 / 50 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 62 / 74 % | 6 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 61 / 73 % | 9 / 24 % | 2 / 9 % | 9 / 20 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 0 / 0 % | 49 / 69 % | 16 / 35 % | 0 / 0 % | 9 / 18 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 31 / 57 % | 40 / 60 % | 38 / 63 % | 8 / 21 % | 34 / 53 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 35 / 67 % | 38 / 66 % | 10 / 25 % | 1 / 7 % | 6 / 15 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 34 / 67 % | 8 / 23 % | 2 / 8 % | 4 / 11 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 31 / 54 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 55 % | 4 / 14 % | 28 / 50 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 26 / 75 % | 25 / 50 % | 8 / 21 % | 0 / 0 % | 6 / 12 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 25 / 91 % | 3 / 41 % | 17 / 37 % | 4 / 11 % | 8 / 26 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 25 % | 15 / 48 % | 24 / 46 % | 9 / 30 % | 2 / 8 % | 15 / 34 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 17 / 53 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 35 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 30 % | 0 / 0 % | 3 / 7 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 8 / 21 % | 12 / 30 % | 0 / 0 % | 10 / 20 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 10 / 75 % | 5 / 27 % | 8 / 18 % | 0 / 0 % | 6 / 14 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 7 / 41 % | 0 / 0 % | 9 / 24 % | 2 / 9 % | 7 / 15 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 2 / 13 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
