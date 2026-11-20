[English](README.md) · [Deutsch](README.de.md)

# Why we're working on white box control

Report Q002209 · Source aisi.gov.uk · Date 2025-07-10 · [Open original](https://www.aisi.gov.uk/blog/why-were-working-on-white-box-control)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der AISI-Bericht beschreibt White-Box-Kontrolle als Untersuchung oder Veränderung interner KI-Aktivierungen und berichtet erste Experimente zur Erkennung von Sandbagging. Eine interne Probe erkannte das Verhalten beim kleineren Modell in einfachen Aufgaben gut, doch die Genauigkeit sank bei größeren Modellen und komplexeren Aufgaben. Die vorläufigen Versuche umfassten zwei Modelle; in früheren Testprotokollen fanden sich keine laut geäußerten Sandbagging-Absichten, was verdecktes Sandbagging aber nicht sicher ausschließt. Der vollständige Blogbericht liegt vor, nicht jedoch die verlinkte ausführliche Fortschrittsauswertung.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 62 / 79 % | 36 / 90 % | – | 97 / 100 % | 79 / 89 % | 80 / 88 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 58 % | 45 / 93 % | – | 91 / 97 % | 31 / 60 % | 35 / 59 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 43 / 63 % | 33 / 97 % | – | 89 / 97 % | 45 / 71 % | 37 / 58 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 31 / 57 % | 34 / 76 % | – | 88 / 98 % | 28 / 58 % | 37 / 66 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 31 / 55 % | 75 / 84 % | – | 63 / 70 % | 38 / 56 % | 13 / 24 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 18 / 45 % | 31 / 81 % | – | 60 / 84 % | 6 / 13 % | 12 / 32 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 19 / 66 % | – | 59 / 78 % | 12 / 32 % | 8 / 17 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 43 / 69 % | 9 / 24 % | 0 / 0 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 17 / 35 % | 23 / 66 % | – | 39 / 64 % | 12 / 28 % | 9 / 19 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 26 / 60 % | – | 30 / 49 % | 6 / 13 % | 6 / 12 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 24 / 54 % | – | 17 / 39 % | 10 / 32 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 20 / 51 % | 0 / 0 % | – | 14 / 32 % | 15 / 40 % | 6 / 13 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | – | 13 / 37 % | 19 / 45 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 13 / 41 % | 18 / 51 % | – | 5 / 40 % | 11 / 37 % | 10 / 24 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 18 / 62 % | – | 11 / 48 % | 14 / 36 % | 9 / 23 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 41 % | 8 / 47 % | – | 1 / 17 % | 17 / 43 % | 14 / 38 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 41 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 5 / 10 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 14 / 33 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 12 / 24 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 5 / 51 % | – | 10 / 25 % | 7 / 19 % | 8 / 15 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 6 / 29 % | 10 / 28 % | 7 / 15 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 10 / 39 % | 5 / 12 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 0 / 0 % | – | 3 / 32 % | 7 / 15 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 13 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 1 / 7 % | 6 / 18 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 12 % | 3 / 6 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 2 / 6 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | – | 5 / 35 % | 6 / 13 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 10 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % |
