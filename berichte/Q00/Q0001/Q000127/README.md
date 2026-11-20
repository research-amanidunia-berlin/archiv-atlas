[English](README.md) · [Deutsch](README.de.md)

# How Black-Box Distillation Works

Report Q000127 · Source cset.georgetown.edu · Date 2026-10-26 · [Open original](https://cset.georgetown.edu/article/how-black-box-distillation-works/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Beitrag beschreibt Black-Box-Destillation als Training eines KI-Modells mit Ausgaben eines leistungsfähigeren, geschlossenen Modells und skizziert die fünf Schritte von der Auswahl der Modelle bis zum Training. Er berichtet über Vorwürfe groß angelegter Nutzung proprietärer US-Modelle durch chinesische Labore, betont aber, dass Datenmengen, tatsächliche Verwendung und erzielter Leistungszuwachs mangels Einblicken unklar bleiben.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 69 / 83 % | 91 / 97 % | – | 93 / 99 % | 92 / 95 % | 84 / 88 % | 93 / 95 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 11 / 88 % | – | 83 / 94 % | 41 / 68 % | 0 / 0 % | 17 / 38 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 28 / 49 % | 76 / 99 % | – | 82 / 95 % | 37 / 68 % | 9 / 22 % | 49 / 70 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 19 / 44 % | 21 / 89 % | – | 76 / 90 % | 31 / 60 % | 7 / 18 % | 14 / 27 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 43 / 59 % | 45 / 99 % | – | 70 / 88 % | 61 / 80 % | 31 / 43 % | 71 / 82 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 49 / 97 % | – | 68 / 84 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 18 / 35 % | 51 / 87 % | – | 67 / 79 % | 21 / 51 % | 1 / 10 % | 20 / 42 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 0 / 0 % | 23 / 94 % | – | 63 / 92 % | 14 / 39 % | 2 / 10 % | 12 / 29 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 52 / 88 % | – | 62 / 72 % | 50 / 74 % | 14 / 26 % | 37 / 60 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 31 / 95 % | – | 57 / 81 % | 9 / 32 % | 2 / 9 % | 8 / 22 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 14 / 58 % | – | 55 / 75 % | 17 / 45 % | 0 / 0 % | 14 / 27 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 53 / 88 % | 9 / 31 % | 2 / 7 % | 8 / 21 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 9 / 70 % | – | 15 / 45 % | 37 / 67 % | 8 / 21 % | 35 / 56 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 33 / 80 % | – | 0 / 0 % | 6 / 16 % | 0 / 4 % | 4 / 13 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 32 / 80 % | – | 0 / 0 % | 8 / 20 % | 0 / 0 % | 8 / 18 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 26 / 63 % | – | 14 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 44 % | 1 / 58 % | – | 0 / 0 % | 11 / 42 % | 6 / 17 % | 18 / 46 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 18 / 36 % | 23 / 73 % | – | 4 / 23 % | 16 / 41 % | 1 / 5 % | 8 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 17 / 81 % | – | 22 / 62 % | 11 / 30 % | 0 / 0 % | 9 / 18 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 5 / 86 % | – | 20 / 69 % | 7 / 22 % | 0 / 0 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 20 / 70 % | – | 0 / 0 % | 18 / 46 % | 0 / 0 % | 12 / 31 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 20 / 66 % | – | 0 / 0 % | 7 / 17 % | 0 / 0 % | 5 / 11 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 19 / 77 % | – | 2 / 19 % | 6 / 20 % | 2 / 6 % | 6 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 4 / 40 % | – | 0 / 0 % | 9 / 28 % | 1 / 8 % | 17 / 35 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 49 % | – | 15 / 26 % | 10 / 29 % | 0 / 0 % | 5 / 13 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 11 / 45 % | 11 / 31 % | 0 / 0 % | 9 / 18 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 28 % | 1 / 6 % | 9 / 24 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 10 / 89 % | – | 2 / 21 % | 7 / 19 % | 0 / 0 % | 7 / 18 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 34 % | 0 / 0 % | 5 / 14 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 6 / 58 % | – | 0 / 0 % | 10 / 25 % | 0 / 0 % | 8 / 19 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 2 / 72 % | – | 0 / 0 % | 6 / 21 % | 0 / 0 % | 8 / 19 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 0 / 0 % | 7 / 16 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 22 % | 0 / 0 % | 5 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 2 / 19 % | 7 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 0 / 0 % | 5 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 11 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 1 % | 4 / 10 % |
