[English](README.md) · [Deutsch](README.de.md)

# Announcing OpenAI’s Bug Bounty Program

Report Q007574 · Source openai.com · Date 2023-04-11 · [Open original](https://openai.com/index/bug-bounty-program/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI kündigt ein Bug-Bounty-Programm an, bei dem Sicherheitsforschende Schwachstellen melden und abhängig von Schwere und Auswirkung 200 bis 20.000 US-Dollar erhalten können. Bugcrowd soll Einreichungen und Prämien abwickeln; konkrete Teilnahmebedingungen und Programmbereiche sind im Bericht nicht enthalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 65 / 80 % | 96 / 99 % | 21 / 43 % | 8 / 20 % | 9 / 21 % | 7 / 14 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 25 / 48 % | 69 / 77 % | 20 / 42 % | 8 / 22 % | 11 / 28 % | 6 / 14 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 63 / 69 % | 0 / 0 % | 0 / 2 % | 5 / 10 % | 0 / 0 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 0 / 0 % | 34 / 71 % | 46 / 61 % | 12 / 37 % | 11 / 29 % | 15 / 37 % | 13 / 28 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 36 / 70 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 26 / 41 % | 8 / 19 % | 4 / 13 % | 7 / 16 % | 2 / 6 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 19 / 34 % | 8 / 21 % | 2 / 9 % | 6 / 14 % | 1 / 5 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 0 / 0 % | 17 / 35 % | 11 / 31 % | 1 / 9 % | 10 / 27 % | 2 / 8 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 37 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 9 / 47 % | 8 / 22 % | 1 / 5 % | 7 / 16 % | 3 / 8 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 4 / 16 % | 7 / 22 % | 3 / 9 % | 8 / 20 % | 2 / 7 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 23 % | 2 / 8 % | 5 / 11 % | 2 / 8 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 3 / 9 % | 6 / 13 % | 1 / 5 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 1 / 6 % | 2 / 7 % | 0 / 0 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 0 / 3 % | 5 / 14 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 5 / 13 % | 0 / 0 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 1 / 5 % | 4 / 9 % | 1 / 3 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 2 % | 5 / 12 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 8 % | 0 / 2 % | 5 / 11 % | 0 / 0 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 17 % | 1 / 5 % | 5 / 13 % | 0 / 2 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 3 % | 4 / 10 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 4 / 11 % | 1 / 4 % | 1 / 7 % | 0 / 0 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 4 / 10 % | 4 / 9 % | 0 / 3 % | 2 / 7 % | 0 / 0 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 2 / 38 % | 0 / 0 % | 4 / 11 % | 1 / 6 % | 3 / 10 % | 0 / 0 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 3 / 10 % | 0 / 1 % | – |
