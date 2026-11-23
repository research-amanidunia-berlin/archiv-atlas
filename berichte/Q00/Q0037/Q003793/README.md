[English](README.md) · [Deutsch](README.de.md)

# A global workspace in language models

Report Q003793 · Source anthropic.com · Date 2026-07-06 · [Open original](https://www.anthropic.com/research/global-workspace)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic beschreibt den J-space als interne, mit einer speziellen Methode untersuchbare Muster, die Claude laut Experimenten für manche Schlussfolgerungen und mehrere Aufgaben nutzen kann. Die Forschenden sehen mögliche Anwendungen bei der Überwachung verborgener Absichten, betonen aber Grenzen der Methode und sagen ausdrücklich, dass die Ergebnisse nicht belegen, Claude habe subjektive Erlebnisse.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 67 / 79 % | 94 / 98 % | 100 / 100 % | 88 / 92 % | 82 / 90 % | 88 / 92 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 61 % | 99 / 100 % | 70 / 81 % | 55 / 76 % | 28 / 47 % | 53 / 70 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 58 / 74 % | 99 / 100 % | 97 / 99 % | 82 / 90 % | 71 / 83 % | 71 / 83 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 41 / 65 % | 93 / 96 % | 98 / 99 % | 69 / 86 % | 48 / 75 % | 72 / 86 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 38 / 61 % | 52 / 91 % | 94 / 98 % | 38 / 66 % | 13 / 35 % | 36 / 66 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 37 / 61 % | 67 / 86 % | 92 / 95 % | 21 / 48 % | 0 / 0 % | 9 / 17 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 6 / 68 % | 69 / 83 % | 19 / 42 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 66 / 93 % | 0 / 0 % | 10 / 30 % | 1 / 5 % | 12 / 21 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 37 / 85 % | 64 / 77 % | 11 / 28 % | 0 / 0 % | 9 / 19 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 18 / 44 % | 37 / 70 % | 52 / 72 % | 11 / 27 % | 0 / 0 % | 8 / 15 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 46 / 73 % | 41 / 61 % | 39 / 64 % | 8 / 16 % | 13 / 25 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 14 / 40 % | 45 / 70 % | 38 / 69 % | 31 / 54 % | 2 / 9 % | 8 / 18 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 40 / 78 % | 43 / 72 % | 8 / 26 % | 0 / 0 % | 7 / 16 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 28 / 78 % | 33 / 55 % | 13 / 33 % | 2 / 8 % | 12 / 22 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 47 % | 28 / 60 % | 27 / 62 % | 12 / 28 % | 4 / 11 % | 8 / 18 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 27 / 66 % | 0 / 0 % | 17 / 39 % | 5 / 14 % | 9 / 21 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 19 / 46 % | 22 / 83 % | 15 / 46 % | 8 / 24 % | 1 / 10 % | 6 / 12 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 20 / 51 % | 5 / 15 % | 1 / 4 % | 3 / 8 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 15 / 48 % | 0 / 0 % | 6 / 16 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 14 / 41 % | 13 / 38 % | 2 / 10 % | 6 / 15 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 33 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 29 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 26 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 23 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 0 / 0 % | 6 / 13 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 22 % | 0 / 0 % | 5 / 11 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 1 / 5 % | 7 / 15 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % | – | – |
