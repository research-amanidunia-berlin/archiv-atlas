[English](README.md) · [Deutsch](README.de.md)

# Our evaluation of Claude Mythos Preview’s cyber capabilities

Report Q001756 · Source aisi.gov.uk · Date 2026-04-13 · [Open original](https://www.aisi.gov.uk/blog/our-evaluation-of-claude-mythos-previews-cyber-capabilities)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

In kontrollierten Tests erzielte Claude Mythos Preview laut AISI hohe Leistungen: Es löste Experten-CTFs zu 73 Prozent und schloss eine 32-schrittige Netzwerksimulation in drei von zehn Versuchen vollständig ab. Die Tests betrafen jedoch schwach geschützte Simulationen ohne aktive Abwehr; daraus lässt sich nicht sicher auf Angriffe gegen gut gesicherte Systeme schließen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 71 / 82 % | 99 / 100 % | – | 99 / 100 % | 5 / 14 % | 77 / 87 % | 82 / 89 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 33 / 59 % | 45 / 93 % | – | 98 / 99 % | 26 / 58 % | 29 / 52 % | 54 / 73 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 47 / 64 % | 7 / 77 % | – | 94 / 98 % | 63 / 81 % | 24 / 42 % | 23 / 45 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 47 % | 59 / 93 % | – | 91 / 96 % | 24 / 53 % | 10 / 28 % | 23 / 48 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 37 / 59 % | 88 / 98 % | – | 80 / 84 % | 58 / 75 % | 29 / 42 % | 56 / 68 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 19 / 42 % | 57 / 90 % | – | 79 / 91 % | 27 / 51 % | 4 / 12 % | 12 / 26 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 26 / 48 % | 58 / 91 % | – | 75 / 86 % | 20 / 42 % | 9 / 20 % | 18 / 35 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 68 / 80 % | 5 / 10 % | 0 / 2 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 30 / 60 % | 0 / 0 % | – | 64 / 81 % | 32 / 57 % | 10 / 24 % | 14 / 26 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 34 / 56 % | 0 / 0 % | – | 12 / 43 % | 39 / 64 % | 11 / 28 % | 34 / 54 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 34 / 78 % | – | 20 / 51 % | 6 / 19 % | 1 / 4 % | 3 / 7 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 26 / 52 % | 32 / 94 % | – | 25 / 66 % | 27 / 60 % | 7 / 18 % | 17 / 40 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 32 / 66 % | 7 / 25 % | 3 / 9 % | 6 / 13 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 16 / 40 % | 27 / 87 % | – | 5 / 56 % | 18 / 43 % | 7 / 18 % | 11 / 34 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 24 / 46 % | 1 / 3 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 8 / 44 % | – | 22 / 60 % | 5 / 11 % | 1 / 3 % | 6 / 11 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 21 / 44 % | 2 / 37 % | – | 0 / 0 % | 10 / 33 % | 4 / 14 % | 15 / 28 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 16 / 45 % | – | 9 / 35 % | 7 / 24 % | 1 / 7 % | 8 / 19 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 15 / 51 % | 8 / 17 % | 2 / 7 % | 5 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 13 / 51 % | – | 1 / 13 % | 7 / 21 % | 0 / 2 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 12 / 83 % | – | 5 / 41 % | 8 / 23 % | 0 / 0 % | 9 / 20 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 18 % | 1 / 6 % | 11 / 23 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 31 % | 2 / 5 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 15 % | 2 / 7 % | 10 / 19 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 5 / 57 % | – | 0 / 0 % | 10 / 34 % | 1 / 7 % | 9 / 20 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 9 / 27 % | 0 / 0 % | – | 0 / 0 % | 7 / 22 % | 3 / 10 % | 7 / 17 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 9 / 32 % | 7 / 19 % | 2 / 9 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 2 % | 8 / 18 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 21 % | 2 / 8 % | 4 / 9 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 1 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 1 / 14 % | 5 / 13 % | 1 / 5 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 1 / 3 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 2 / 7 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 2 / 5 % | 5 / 9 % |
