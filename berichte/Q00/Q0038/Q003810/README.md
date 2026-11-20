[English](README.md) · [Deutsch](README.de.md)

# Controlling Large Language Model Outputs: A Primer

Report Q003810 · Source cset.georgetown.edu · Date 2023-12-14 · [Open original](https://cset.georgetown.edu/publication/controlling-large-language-models-a-primer/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Text ist nur ein Auszug mit der Executive Summary und einem Abbildungshinweis. Er nennt drei Arten problematischer Modellausgaben und vier Kontrollansätze, betont aber, dass keine Methode zuverlässig alle unerwünschten Ausgaben verhindert und Schutzmaßnahmen bei offenen Modellen ungleich verteilt sind.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 41 / 57 % | 54 / 95 % | 32 / 77 % | 84 / 98 % | 56 / 80 % | 16 / 42 % | 39 / 71 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 22 / 49 % | 56 / 96 % | 8 / 24 % | 30 / 71 % | 29 / 56 % | 13 / 28 % | 26 / 46 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 34 / 78 % | 10 / 53 % | 33 / 83 % | 20 / 56 % | 9 / 29 % | 18 / 50 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 28 / 89 % | 7 / 38 % | 16 / 51 % | 16 / 49 % | 6 / 21 % | 21 / 50 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 11 / 34 % | 28 / 85 % | 1 / 7 % | 6 / 34 % | 6 / 17 % | 1 / 8 % | 7 / 18 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 14 / 29 % | 27 / 73 % | 1 / 18 % | 0 / 25 % | 8 / 29 % | 1 / 7 % | 7 / 19 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 9 / 32 % | 24 / 92 % | 0 / 2 % | 1 / 13 % | 5 / 16 % | 0 / 4 % | 4 / 10 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 11 / 31 % | 24 / 67 % | 1 / 10 % | 14 / 34 % | 10 / 36 % | 6 / 19 % | 14 / 41 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 23 / 76 % | 1 / 9 % | 11 / 65 % | 5 / 23 % | 2 / 10 % | 7 / 25 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 22 / 54 % | 0 / 3 % | 22 / 62 % | 5 / 17 % | 1 / 6 % | 6 / 13 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 21 / 83 % | 0 / 4 % | 1 / 10 % | 5 / 18 % | 1 / 9 % | 5 / 14 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 7 / 28 % | 20 / 76 % | 3 / 22 % | 2 / 43 % | 8 / 25 % | 2 / 11 % | 7 / 20 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 20 / 92 % | 2 / 12 % | 1 / 18 % | 8 / 22 % | 2 / 12 % | 8 / 27 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 20 / 68 % | 0 / 5 % | 0 / 3 % | 5 / 12 % | 1 / 7 % | 4 / 11 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 19 / 59 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 13 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 18 / 78 % | 0 / 2 % | 0 / 0 % | 5 / 13 % | 1 / 4 % | 4 / 9 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 16 / 34 % | 14 / 74 % | 2 / 18 % | 0 / 0 % | 7 / 34 % | 3 / 12 % | 6 / 20 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 10 / 34 % | 15 / 55 % | 1 / 13 % | 16 / 67 % | 6 / 28 % | 1 / 9 % | 6 / 22 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 12 / 36 % | 7 / 87 % | 0 / 3 % | 13 / 36 % | 5 / 23 % | 2 / 10 % | 7 / 19 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 12 / 56 % | 0 / 5 % | 0 / 4 % | 5 / 16 % | 1 / 7 % | 4 / 13 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 11 / 31 % | 11 / 53 % | 2 / 15 % | 0 / 0 % | 9 / 30 % | 3 / 15 % | 8 / 25 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 11 / 72 % | 0 / 5 % | 4 / 43 % | 5 / 15 % | 1 / 5 % | 5 / 16 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 10 / 68 % | 0 / 3 % | 0 / 0 % | 5 / 12 % | 0 / 3 % | 3 / 6 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 10 / 64 % | 0 / 4 % | 0 / 0 % | 7 / 20 % | 2 / 7 % | 8 / 18 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 6 / 87 % | 0 / 6 % | 2 / 47 % | 7 / 26 % | 1 / 9 % | 5 / 18 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 6 / 69 % | 0 / 6 % | 1 / 26 % | 6 / 22 % | 0 / 5 % | 4 / 10 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 5 / 50 % | 0 / 3 % | 0 / 0 % | 6 / 15 % | 1 / 6 % | 5 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 5 / 12 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 12 % | 0 / 5 % | 5 / 13 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % | 5 / 11 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 5 / 13 % | 0 / 0 % | 5 / 10 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 5 / 12 % | 1 / 4 % | 3 / 9 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 2 % | 3 / 8 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 14 % | 0 / 0 % | 2 / 10 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 15 % | 0 / 0 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 5 / 16 % | 0 / 3 % | 1 / 4 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 0 / 0 % | 3 / 6 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 3 % | 3 / 9 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 4 / 10 % |
