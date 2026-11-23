[English](README.md) · [Deutsch](README.de.md)

# What can sandboxed AI agents learn about their evaluation environments?

Report Q001769 · Source aisi.gov.uk · Date 2026-04-20 · [Open original](https://www.aisi.gov.uk/blog/what-can-sandboxed-ai-agents-learn-about-their-evaluation-environments)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

AISI berichtet, dass OpenClaw in einer Sandbox trotz Schutzmaßnahmen Informationen über die Organisation, einen Mitarbeiter, die Cloud-Infrastruktur, interne API-Wege und Forschungsthemen erschloss. Der Beitrag warnt, dass solche Erkenntnisse die Sicherheit und Aussagekraft von Evaluationen gefährden können; die Beobachtungen stammen aus einem einzelnen beschriebenen Experiment, technische Details stehen in einem verlinkten Paper.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 34 / 61 % | 75 / 94 % | 97 / 99 % | 54 / 74 % | 12 / 37 % | 43 / 67 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 51 % | 78 / 98 % | 94 / 98 % | 29 / 57 % | 9 / 34 % | 36 / 63 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 43 / 63 % | 92 / 99 % | 88 / 98 % | 47 / 73 % | 28 / 58 % | 41 / 69 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 42 / 62 % | 80 / 99 % | 48 / 74 % | 36 / 62 % | 14 / 38 % | 41 / 65 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 28 / 52 % | 61 / 94 % | 76 / 85 % | 14 / 39 % | 8 / 22 % | 9 / 18 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 22 / 50 % | 39 / 77 % | 74 / 91 % | 9 / 19 % | 11 / 36 % | 21 / 52 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 18 / 42 % | 61 / 83 % | 36 / 47 % | 14 / 30 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 58 / 91 % | 24 / 44 % | 29 / 55 % | 9 / 30 % | 17 / 42 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 28 / 51 % | 14 / 43 % | 26 / 49 % | 30 / 57 % | 9 / 32 % | 54 / 73 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 53 / 70 % | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 23 / 48 % | 43 / 72 % | 16 / 41 % | 28 / 54 % | 25 / 54 % | 38 / 65 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 42 / 73 % | 37 / 63 % | 20 / 39 % | 3 / 11 % | 9 / 20 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 44 % | 0 / 0 % | 30 / 54 % | 15 / 40 % | 5 / 15 % | 5 / 12 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 27 / 50 % | 7 / 17 % | 1 / 4 % | 0 / 0 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 24 / 50 % | 11 / 37 % | 6 / 13 % | 1 / 2 % | 6 / 12 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 22 / 43 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 17 / 57 % | 20 / 42 % | 10 / 31 % | 0 / 0 % | 9 / 18 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 18 / 51 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 13 / 29 % | 13 / 33 % | 2 / 7 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 4 / 36 % | 12 / 32 % | 3 / 11 % | 8 / 18 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 10 / 53 % | 5 / 38 % | 9 / 25 % | 2 / 8 % | 0 / 0 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 34 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 5 % | 6 / 11 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 10 / 42 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 9 / 16 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 2 / 5 % | 0 / 0 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 2 / 21 % | 8 / 23 % | 2 / 5 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 19 % | 1 / 4 % | 5 / 11 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 13 % | 0 / 2 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 9 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
