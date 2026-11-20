[English](README.md) · [Deutsch](README.de.md)

# How our Control Red Team is stress-testing frontier monitors

Report Q001170 · Source aisi.gov.uk · Date 2026-07-23 · [Open original](https://www.aisi.gov.uk/blog/how-our-new-control-red-team-is-stress-testing-frontier-monitors)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AISI beschreibt Tests seines neuen Control Red Teams an internen Monitoren bei Google DeepMind und Anthropic und berichtet von Schwachstellen, die in Verbesserungen eingeflossen seien. Eine frühe automatisierte Suche fand laut Bericht deutlich niedrigere Verdachtswerte als eine Best-of-N-Methode, doch die Experimente sind begrenzt und werfen offene Fragen zur Realitätsnähe der Angriffe und zur Gesamtbewertung der Sicherheit auf.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 30 / 55 % | 65 / 94 % | – | 97 / 100 % | 75 / 87 % | 27 / 59 % | 61 / 78 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 33 / 55 % | 65 / 83 % | – | 95 / 97 % | 50 / 68 % | 30 / 48 % | 39 / 53 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 40 / 59 % | 57 / 92 % | – | 93 / 98 % | 66 / 83 % | 42 / 70 % | 64 / 80 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 39 / 58 % | 68 / 94 % | – | 89 / 97 % | 52 / 74 % | 45 / 70 % | 57 / 74 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 62 % | 72 / 98 % | – | 88 / 96 % | 65 / 82 % | 31 / 58 % | 60 / 75 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 27 / 52 % | 30 / 75 % | – | 83 / 94 % | 9 / 19 % | 24 / 52 % | 50 / 71 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 43 % | 23 / 76 % | – | 77 / 89 % | 27 / 50 % | 9 / 19 % | 22 / 36 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 34 / 55 % | 20 / 59 % | – | 38 / 64 % | 59 / 79 % | 21 / 47 % | 72 / 83 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 19 / 42 % | 16 / 57 % | – | 61 / 89 % | 42 / 66 % | 12 / 31 % | 24 / 39 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 42 / 91 % | – | 41 / 81 % | 19 / 48 % | 7 / 19 % | 16 / 32 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 33 / 55 % | 25 / 83 % | – | 38 / 62 % | 29 / 58 % | 16 / 33 % | 27 / 44 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 25 / 51 % | 0 / 0 % | – | 36 / 59 % | 31 / 55 % | 10 / 26 % | 16 / 25 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 39 % | 22 / 77 % | – | 33 / 59 % | 25 / 51 % | 12 / 37 % | 30 / 51 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 29 / 51 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 24 / 51 % | 9 / 21 % | 1 / 6 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 17 / 40 % | 21 / 61 % | – | 23 / 55 % | 13 / 33 % | 3 / 11 % | 12 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 9 / 29 % | 23 / 49 % | 5 / 14 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 13 / 30 % | 0 / 0 % | – | 18 / 52 % | 6 / 15 % | 3 / 10 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 38 % | – | 6 / 21 % | 17 / 40 % | 5 / 18 % | 8 / 18 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 17 / 50 % | – | 10 / 36 % | 7 / 14 % | 2 / 7 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 12 / 65 % | – | 0 / 0 % | 11 / 29 % | 2 / 6 % | 9 / 18 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 29 % | 1 / 4 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 22 % | 2 / 7 % | 5 / 9 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 5 % | 8 / 17 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 5 / 39 % | 8 / 21 % | 2 / 9 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 14 % | 2 / 7 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 1 / 3 % | 5 / 11 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 4 / 11 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 3 / 9 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 4 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 3 / 25 % | 0 / 0 % | 0 / 1 % | 0 / 0 % |
