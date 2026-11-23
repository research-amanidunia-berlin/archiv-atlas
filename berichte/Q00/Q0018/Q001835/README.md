[English](README.md) · [Deutsch](README.de.md)

# An evaluation framework for AI misuse in fraud and cybercrime

Report Q001835 · Source aisi.gov.uk · Date 2026-02-26 · [Open original](https://www.aisi.gov.uk/blog/an-evaluation-framework-for-ai-misuse-in-fraud-and-cybercrime)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht bewertet Sprachmodelle in mehrstufigen Tests zu drei Betrugsarten und berichtet, dass die meisten Antworten nur geringe praktische Hilfe boten. Besonders auffällig seien offene Modelle mit entfernten Schutzvorkehrungen gewesen; die Untersuchung erfasste allerdings nur Text und lässt mögliche Risiken durch Bild, Audio und Video offen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 56 / 71 % | 91 / 98 % | 100 / 100 % | 7 / 19 % | 74 / 85 % | 75 / 85 % | – | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 27 / 45 % | 93 / 99 % | 100 / 100 % | 58 / 79 % | 15 / 37 % | 43 / 67 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 13 / 69 % | 93 / 97 % | 44 / 68 % | 0 / 0 % | 9 / 21 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 58 % | 80 / 98 % | 93 / 96 % | 32 / 63 % | 35 / 57 % | 45 / 68 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 58 / 92 % | 93 / 96 % | 47 / 73 % | 17 / 35 % | 30 / 55 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | 87 / 91 % | 48 / 72 % | 16 / 30 % | 44 / 66 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 33 / 56 % | 57 / 95 % | 86 / 95 % | 49 / 71 % | 12 / 26 % | 37 / 54 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 84 / 92 % | 11 / 35 % | 2 / 9 % | 6 / 18 % | – | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 63 / 88 % | 21 / 61 % | 13 / 41 % | 3 / 13 % | 10 / 27 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 55 / 96 % | 50 / 73 % | 15 / 35 % | 5 / 14 % | 17 / 32 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 24 / 95 % | 45 / 78 % | 21 / 51 % | 3 / 12 % | 11 / 25 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 40 % | 17 / 51 % | 26 / 61 % | 37 / 62 % | 6 / 16 % | 21 / 38 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 34 / 53 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 27 / 91 % | 11 / 23 % | 11 / 31 % | 3 / 12 % | 9 / 21 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 0 / 0 % | 26 / 60 % | 8 / 20 % | 1 / 6 % | 5 / 13 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 19 / 47 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 18 / 57 % | 14 / 39 % | 8 / 20 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 16 / 44 % | 1 / 22 % | 8 / 30 % | 1 / 6 % | 7 / 22 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 37 % | 0 / 3 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 39 % | 4 / 13 % | 7 / 15 % | – | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 12 / 33 % | 11 / 44 % | 1 / 13 % | 12 / 33 % | 4 / 10 % | 5 / 17 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 3 / 60 % | 9 / 33 % | 8 / 22 % | 3 / 14 % | 11 / 25 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 11 / 40 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 2 / 6 % | 10 / 21 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 7 / 30 % | 0 / 0 % | 8 / 27 % | 3 / 10 % | 10 / 22 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 0 / 0 % | 10 / 24 % | 6 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 6 / 31 % | 9 / 27 % | 2 / 9 % | 5 / 12 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 20 % | 1 / 6 % | 7 / 16 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 21 % | 1 / 7 % | 6 / 15 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 10 % | – | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 6 / 16 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 1 / 18 % | 6 / 21 % | 1 / 7 % | 0 / 0 % | – | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 0 / 0 % | 6 / 13 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 2 % | 4 / 9 % | – | – |
