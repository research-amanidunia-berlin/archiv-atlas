[English](README.md) · [Deutsch](README.de.md)

# What Do Collusion Probes Read? Three Pitfalls in Evaluating Multi-Agent Collusion Monitors

Report Q000481 · Source arxiv.org · Date – · [Open original](https://arxiv.org/abs/2611.10620)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Auszug berichtet, dass Kollusionsprobes laut Autoren häufig eher eine erhaltene Anweisung als die eigene Entscheidung eines LLM-Agenten erkennen. Sie benennen außerdem Verzerrungen durch Auswertung nach der Abstimmung und durch fehlende öffentliche Argumente; der Abstract skizziert Gegenproben und ein Prüfprotokoll.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 41 / 63 % | 73 / 92 % | 96 / 97 % | 64 / 79 % | 21 / 38 % | 65 / 76 % | 28 / 52 % | 21 / 37 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 50 / 69 % | 77 / 93 % | 96 / 98 % | 70 / 83 % | 39 / 56 % | 42 / 59 % | 45 / 67 % | 32 / 49 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 57 % | 73 / 89 % | 92 / 94 % | 51 / 71 % | 20 / 36 % | 27 / 47 % | 11 / 35 % | 0 / 0 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 43 / 63 % | 39 / 74 % | 85 / 90 % | 47 / 70 % | 19 / 35 % | 29 / 46 % | 10 / 26 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 29 / 50 % | 28 / 65 % | 82 / 89 % | 23 / 47 % | 6 / 16 % | 10 / 23 % | 2 / 13 % | 13 / 25 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 0 / 0 % | 73 / 82 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 3 / 13 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 18 / 31 % | 67 / 77 % | 13 / 26 % | 0 / 0 % | 11 / 19 % | 0 / 0 % | 34 / 53 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 59 / 69 % | 28 / 50 % | 0 / 0 % | 18 / 31 % | 3 / 11 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 33 / 60 % | 11 / 26 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 33 / 49 % | 8 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 16 / 41 % | 23 / 44 % | 23 / 45 % | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 20 / 41 % | 3 / 7 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 20 / 45 % | 0 / 0 % | 0 / 0 % | 18 / 36 % | 0 / 0 % | 0 / 0 % | 2 / 10 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 35 % | 3 / 9 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 25 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 22 % | 3 / 7 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 22 % | 5 / 12 % | 6 / 11 % | 1 / 6 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 1 / 6 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 15 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 7 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 1 / 2 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
