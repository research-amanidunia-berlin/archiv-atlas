[English](README.md) · [Deutsch](README.de.md)

# Specifying AI safety problems in simple environments

Report Q003319 · Source deepmind.google · Date 2017-11-28 · [Open original](https://deepmind.google/blog/specifying-ai-safety-problems-in-simple-environments/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht stellt neun einfache Gridworlds vor, in denen KI-Agenten auf sicheres Verhalten geprüft werden: beim Umgang mit Unterbrechungen, unumkehrbaren Nebenwirkungen und veränderten Testbedingungen. A2C und Rainbow DQN zeigten in mehreren Aufgaben Sicherheitsmängel; laut Autoren waren sie dafür nicht eigens entwickelt worden, und die vereinfachten Tests sind ein Forschungsinstrument, kein Nachweis realer Sicherheit.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 50 / 69 % | 99 / 100 % | 30 / 64 % | 99 / 100 % | 69 / 84 % | 47 / 68 % | 71 / 84 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 46 / 65 % | 73 / 86 % | 57 / 79 % | 84 / 95 % | 67 / 84 % | 39 / 65 % | 45 / 66 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 24 / 49 % | 37 / 85 % | 12 / 49 % | 74 / 88 % | 5 / 12 % | 10 / 33 % | 11 / 28 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 42 / 74 % | 15 / 51 % | 72 / 85 % | 58 / 78 % | 24 / 50 % | 60 / 78 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 22 / 46 % | 38 / 91 % | 7 / 38 % | 72 / 89 % | 40 / 64 % | 9 / 28 % | 10 / 23 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 50 % | 32 / 85 % | 11 / 48 % | 66 / 85 % | 31 / 61 % | 16 / 42 % | 35 / 62 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 30 / 51 % | 39 / 87 % | 10 / 47 % | 51 / 89 % | 35 / 64 % | 13 / 39 % | 24 / 59 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 30 / 81 % | 2 / 14 % | 9 / 45 % | 20 / 48 % | 5 / 15 % | 10 / 25 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 26 / 83 % | 1 / 11 % | 5 / 29 % | 15 / 40 % | 3 / 12 % | 7 / 16 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 26 / 58 % | 0 / 0 % | 24 / 50 % | 8 / 20 % | 1 / 3 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 26 / 66 % | 0 / 2 % | 5 / 30 % | 7 / 15 % | 1 / 4 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 46 % | 9 / 20 % | 1 / 7 % | 5 / 12 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 20 / 60 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 19 / 61 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 13 / 57 % | 0 / 2 % | 0 / 0 % | 7 / 15 % | 0 / 4 % | 4 / 7 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 12 / 28 % | 13 / 34 % | 2 / 9 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 9 / 54 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 1 / 4 % | 7 / 16 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 9 / 24 % | 2 / 6 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 8 / 28 % | 5 / 12 % | 1 / 6 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 7 / 69 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % | 1 / 3 % | 5 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 4 / 52 % | 0 / 4 % | 1 / 8 % | 6 / 16 % | 3 / 11 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 5 / 13 % | 0 / 2 % | 5 / 9 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 2 / 5 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 3 / 6 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 2 / 17 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
