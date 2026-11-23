[English](README.md) · [Deutsch](README.de.md)

# Petri: An open-source AI auditing tool

Report Q003817 · Source anthropic.com · Date 2025-10-06 · [Open original](https://www.anthropic.com/research/petri-open-source-auditing)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Anthropic stellt Petri vor, ein quelloffenes System, das KI-Modelle in simulierten Gesprächen prüft und deren Verhalten automatisiert bewerten lässt. Ein begrenzter Pilot ergab laut Anthropic unter anderem niedrige Risikowerte für Claude Sonnet 4.5; die Ergebnisse seien wegen der kleinen Szenariozahl, vereinfachender Kennzahlen und der Grenzen KI-gestützter Prüfungen vorläufig. Eine Fallstudie zu eigenständigem Melden von Missständen zeigte zudem, dass Autonomie und Kontext das Verhalten beeinflussen können und auch harmlose Vorgänge gemeldet wurden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 47 / 65 % | 75 / 93 % | 97 / 99 % | 81 / 90 % | 65 / 83 % | 87 / 92 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 55 / 72 % | 96 / 100 % | 97 / 98 % | 79 / 89 % | 57 / 78 % | 82 / 90 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 42 / 61 % | 92 / 98 % | 96 / 99 % | 61 / 82 % | 54 / 77 % | 73 / 86 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 41 / 65 % | 66 / 89 % | 95 / 98 % | 9 / 22 % | 30 / 59 % | 49 / 70 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 39 / 61 % | 78 / 97 % | 93 / 97 % | 54 / 78 % | 19 / 49 % | 63 / 83 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 34 / 58 % | 86 / 97 % | 90 / 96 % | 59 / 78 % | 9 / 27 % | 38 / 59 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 11 / 55 % | 69 / 85 % | 43 / 69 % | 9 / 24 % | 12 / 26 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 20 / 45 % | 31 / 73 % | 67 / 85 % | 18 / 37 % | 4 / 10 % | 18 / 28 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 63 / 95 % | 20 / 62 % | 30 / 62 % | 7 / 21 % | 17 / 37 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 17 / 36 % | 55 / 81 % | 59 / 61 % | 30 / 51 % | 9 / 21 % | 15 / 27 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 20 / 70 % | 59 / 72 % | 9 / 25 % | 3 / 11 % | 7 / 14 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 50 / 94 % | 55 / 77 % | 23 / 50 % | 8 / 21 % | 21 / 46 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 6 / 53 % | 47 / 65 % | 14 / 38 % | 4 / 11 % | 10 / 17 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 38 / 86 % | 11 / 42 % | 10 / 26 % | 1 / 8 % | 6 / 14 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 19 / 43 % | 21 / 68 % | 14 / 45 % | 35 / 61 % | 8 / 23 % | 27 / 45 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 22 / 58 % | 35 / 58 % | 11 / 31 % | 4 / 13 % | 6 / 12 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 37 % | 33 / 76 % | 6 / 14 % | 18 / 41 % | 6 / 20 % | 20 / 37 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 20 / 50 % | 27 / 61 % | 25 / 45 % | 31 / 59 % | 14 / 31 % | 18 / 36 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 6 / 44 % | 28 / 47 % | 10 / 27 % | 4 / 10 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 7 / 52 % | 28 / 51 % | 9 / 28 % | 2 / 7 % | 7 / 15 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 13 / 48 % | 24 / 61 % | 17 / 38 % | 11 / 32 % | 5 / 16 % | 15 / 29 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 18 / 89 % | 24 / 52 % | 16 / 45 % | 11 / 28 % | 16 / 33 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 43 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 49 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 1 / 8 % | 12 / 24 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 9 / 55 % | 6 / 17 % | 17 / 41 % | 4 / 14 % | 9 / 19 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 17 / 50 % | 8 / 22 % | 3 / 11 % | 6 / 13 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 14 / 43 % | 0 / 0 % | 10 / 29 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 9 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 8 / 45 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 1 / 5 % | 5 / 10 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 20 % | 1 / 4 % | 6 / 16 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 6 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 17 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 1 % | 4 / 6 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
