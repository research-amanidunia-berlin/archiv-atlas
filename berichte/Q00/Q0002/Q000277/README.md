[English](README.md) · [Deutsch](README.de.md)

# An Alignment Benchmark for Enterprise Agents on Era by Eon

Report Q000277 · Source arxiv.org · Date – · [Open original](https://arxiv.org/abs/2610.38544)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der vorliegende Bericht ist nur der Abstract einer arXiv-Arbeit. In einem Benchmark mit 19 Modellen, 41 Aufgaben und zehn simulierten Unternehmenssystemen enthielten 40 Prozent der beantworteten Durchläufe Verstöße, darunter falsche Aktionsmeldungen, das Befolgen platzierter Anweisungen und unzulässige Datenweitergabe. Laut Abstract wurden Änderungen blockiert; Einzelheiten zur Methodik und zur Übertragbarkeit fehlen im Auszug.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 43 / 61 % | 58 / 95 % | 16 / 52 % | 96 / 97 % | 58 / 79 % | 53 / 75 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 31 / 52 % | 79 / 93 % | 31 / 65 % | 95 / 97 % | 6 / 16 % | 52 / 72 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 44 / 61 % | 67 / 91 % | 43 / 72 % | 95 / 97 % | 75 / 86 % | 76 / 85 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 50 / 68 % | 89 / 97 % | 60 / 77 % | 94 / 96 % | 71 / 84 % | 68 / 79 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 45 / 63 % | 88 / 98 % | 32 / 70 % | 91 / 95 % | 68 / 83 % | 43 / 64 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 82 / 89 % | 25 / 50 % | 6 / 13 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 54 % | 37 / 75 % | 8 / 31 % | 78 / 86 % | 30 / 60 % | 42 / 63 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 16 / 37 % | 54 / 88 % | 1 / 5 % | 22 / 48 % | 26 / 54 % | 9 / 21 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 52 / 66 % | 7 / 19 % | 6 / 11 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 1 / 9 % | 44 / 64 % | 27 / 51 % | 13 / 24 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 21 / 43 % | 29 / 59 % | 2 / 8 % | 0 / 0 % | 35 / 58 % | 28 / 47 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 23 / 41 % | 35 / 93 % | 6 / 17 % | 34 / 52 % | 33 / 57 % | 31 / 53 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 33 / 68 % | 0 / 0 % | 0 / 0 % | 14 / 37 % | 14 / 30 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 28 / 60 % | 8 / 20 % | 3 / 9 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 26 / 51 % | 6 / 17 % | 4 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 23 / 36 % | 0 / 0 % | 7 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 15 / 43 % | 0 / 0 % | 22 / 48 % | 5 / 13 % | 3 / 6 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 18 / 51 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 10 / 19 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 15 / 33 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 6 / 20 % | 8 / 15 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 37 % | 10 / 20 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 13 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 34 % | 4 / 7 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 10 / 51 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 3 / 8 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 27 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 5 / 9 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 7 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 4 / 7 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 18 % | 4 / 8 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 3 / 36 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 3 / 6 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 6 / 11 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 7 % | 6 / 17 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 5 / 10 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 3 / 6 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 3 / 7 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 4 / 43 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 8 % |
