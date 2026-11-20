[English](README.md) · [Deutsch](README.de.md)

# Practical challenges of control monitoring in frontier AI deployments

Report Q009481 · Source arxiv.org · Date – · [Open original](https://arxiv.org/abs/2512.22154)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Auszug beschreibt Herausforderungen bei der Überwachung leistungsfähiger KI-Agenten und vergleicht synchrone, halb synchrone und asynchrone Kontrollverfahren. Er nennt Aufsicht, Latenz und Wiederherstellung als zentrale Themen, enthält aber keine detaillierten Ergebnisse der vier erwähnten Fallstudien.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 28 / 52 % | 67 / 96 % | 28 / 53 % | – | 47 / 71 % | – | 28 / 57 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 39 / 63 % | 31 / 91 % | 42 / 79 % | – | 54 / 76 % | – | 23 / 58 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 35 / 60 % | 31 / 98 % | 16 / 56 % | – | 47 / 73 % | – | 32 / 65 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 37 / 55 % | 46 / 96 % | 11 / 46 % | – | 33 / 62 % | – | 26 / 62 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 35 / 58 % | 42 / 94 % | 6 / 28 % | – | 30 / 59 % | – | 22 / 47 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 34 / 69 % | 2 / 13 % | – | 13 / 33 % | – | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 53 % | 33 / 80 % | 9 / 39 % | – | 20 / 50 % | – | 17 / 43 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 31 / 53 % | 4 / 63 % | 5 / 25 % | – | 33 / 61 % | – | 14 / 39 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 17 / 42 % | 32 / 83 % | 9 / 41 % | – | 26 / 55 % | – | 13 / 34 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 29 / 88 % | 2 / 11 % | – | 8 / 23 % | – | 2 / 7 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 27 / 59 % | 1 / 12 % | – | 8 / 26 % | – | 3 / 9 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 23 / 72 % | 0 / 0 % | – | 0 / 0 % | – | 1 / 6 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 19 / 47 % | 20 / 70 % | 1 / 8 % | – | 10 / 26 % | – | 5 / 15 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 17 / 54 % | 0 / 0 % | – | 7 / 14 % | – | 1 / 3 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 16 / 66 % | 0 / 4 % | – | 6 / 14 % | – | 0 / 2 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 13 / 44 % | 0 / 0 % | 1 / 8 % | – | 9 / 27 % | – | 2 / 8 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 12 / 66 % | 0 / 0 % | – | 7 / 17 % | – | 2 / 4 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 11 / 68 % | 1 / 7 % | – | 9 / 26 % | – | 1 / 5 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 5 % | – | 11 / 33 % | – | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 6 / 46 % | 0 / 4 % | – | 10 / 28 % | – | 1 / 4 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 9 / 32 % | 8 / 54 % | 2 / 17 % | – | 5 / 12 % | – | 6 / 18 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 2 / 10 % | – | 8 / 20 % | – | 1 / 5 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 1 / 11 % | 1 / 6 % | – | 8 / 24 % | – | 1 / 6 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | – | 1 / 4 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | – | 1 / 3 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | – | 1 / 3 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 13 % | – | 0 / 1 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 6 / 56 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 11 % | – | 0 / 2 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 17 % | – | 1 / 5 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 0 / 1 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 4 / 45 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 36 % | 0 / 0 % | – | 0 / 0 % | – | 1 / 3 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 30 % | 0 / 0 % | – | 0 / 0 % | – | 0 / 0 % |
