[English](README.md) · [Deutsch](README.de.md)

# Taking a responsible path to AGI

Report Q003066 · Source deepmind.google · Date 2025-04-02 · [Open original](https://deepmind.google/blog/taking-a-responsible-path-to-agi/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind skizziert Maßnahmen für mögliche AGI-Risiken, insbesondere Missbrauch und Fehlanpassung: Dazu zählen Zugangsschutz, Modellprüfungen, menschliche Aufsicht, Überwachung und Forschung an verständlicheren Systemen. Der Beitrag beschreibt Unternehmenspositionen und geplante Arbeit, räumt offene Herausforderungen ein und belegt nicht, dass die Maßnahmen sämtliche Risiken lösen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 43 / 63 % | 95 / 99 % | 63 / 87 % | 96 / 99 % | 68 / 85 % | 75 / 89 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 57 % | 86 / 99 % | 40 / 68 % | 94 / 99 % | 46 / 75 % | 67 / 83 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 57 % | 89 / 99 % | 59 / 81 % | 90 / 99 % | 49 / 76 % | 50 / 76 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 45 % | 79 / 96 % | 25 / 55 % | 86 / 97 % | 40 / 67 % | 39 / 67 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 38 / 60 % | 49 / 93 % | 41 / 74 % | 62 / 90 % | 64 / 84 % | 84 / 92 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 38 / 64 % | 56 / 87 % | 63 / 77 % | 82 / 97 % | 18 / 42 % | 75 / 87 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 26 / 55 % | 81 / 96 % | 32 / 57 % | 69 / 86 % | 38 / 65 % | 25 / 54 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 44 / 78 % | 1 / 9 % | 72 / 90 % | 13 / 39 % | 12 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 11 / 31 % | 68 / 92 % | 6 / 22 % | 69 / 89 % | 14 / 39 % | 15 / 46 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 16 / 47 % | 65 / 95 % | 15 / 41 % | 50 / 89 % | 35 / 64 % | 28 / 64 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 18 / 48 % | 65 / 92 % | 8 / 33 % | 56 / 83 % | 19 / 46 % | 24 / 58 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 11 / 42 % | 62 / 83 % | 16 / 25 % | 17 / 42 % | 32 / 59 % | 26 / 51 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 12 / 41 % | 60 / 89 % | 1 / 8 % | 37 / 81 % | 11 / 31 % | 9 / 23 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 10 / 34 % | 56 / 78 % | 8 / 23 % | 7 / 37 % | 12 / 30 % | 13 / 32 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 47 % | 55 / 97 % | 2 / 15 % | 35 / 72 % | 19 / 48 % | 22 / 55 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 44 % | 21 / 87 % | 12 / 35 % | 51 / 82 % | 41 / 69 % | 22 / 64 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 42 % | 41 / 83 % | 30 / 56 % | 50 / 87 % | 45 / 69 % | 49 / 68 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 12 / 30 % | 30 / 69 % | 0 / 4 % | 50 / 77 % | 10 / 34 % | 6 / 19 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 46 % | 46 / 90 % | 10 / 31 % | 13 / 55 % | 24 / 51 % | 29 / 59 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 13 / 38 % | 19 / 91 % | 1 / 9 % | 38 / 59 % | 12 / 37 % | 11 / 46 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 10 / 33 % | 37 / 84 % | 9 / 34 % | 27 / 76 % | 24 / 52 % | 10 / 42 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 37 / 81 % | 1 / 6 % | 2 / 22 % | 8 / 21 % | 10 / 36 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 71 % | 5 / 19 % | 35 / 78 % | 30 / 58 % | 10 / 27 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 25 / 45 % | 5 / 76 % | 17 / 37 % | 24 / 52 % | 19 / 48 % | 22 / 42 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 33 % | 25 / 91 % | 2 / 16 % | 15 / 52 % | 9 / 30 % | 9 / 33 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 23 / 75 % | 0 / 3 % | 0 / 3 % | 7 / 17 % | 7 / 14 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 21 / 73 % | 0 / 3 % | 6 / 35 % | 9 / 26 % | 7 / 19 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 14 / 40 % | 1 / 35 % | 1 / 6 % | 17 / 54 % | 11 / 30 % | 19 / 43 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 48 % | 9 / 84 % | 7 / 24 % | 14 / 55 % | 19 / 47 % | 13 / 39 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 14 / 40 % | 1 / 29 % | 2 / 12 % | 17 / 44 % | 11 / 35 % | 11 / 53 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 15 / 75 % | 1 / 5 % | 4 / 43 % | 9 / 31 % | 8 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 36 % | 8 / 13 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 5 / 30 % | 1 / 5 % | 11 / 31 % | 12 / 40 % | 11 / 23 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 30 % | 1 / 23 % | 0 / 3 % | 0 / 0 % | 7 / 20 % | 8 / 21 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 10 / 62 % | 0 / 5 % | 6 / 37 % | 9 / 29 % | 7 / 26 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 10 / 57 % | 0 / 0 % | 0 / 9 % | 5 / 14 % | 5 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 9 / 29 % | 6 / 20 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 8 / 14 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 7 / 12 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 1 / 81 % | 0 / 4 % | 1 / 31 % | 7 / 22 % | 6 / 25 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 18 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 7 / 19 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 1 / 31 % | 0 / 0 % | 0 / 14 % | 0 / 0 % | 6 / 16 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 5 % | 6 / 14 % | 6 / 16 % |
