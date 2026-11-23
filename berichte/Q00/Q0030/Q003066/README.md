[English](README.md) · [Deutsch](README.de.md)

# Taking a responsible path to AGI

Report Q003066 · Source deepmind.google · Date 2025-04-02 · [Open original](https://deepmind.google/blog/taking-a-responsible-path-to-agi/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Google DeepMind skizziert Maßnahmen für mögliche AGI-Risiken, insbesondere Missbrauch und Fehlanpassung: Dazu zählen Zugangsschutz, Modellprüfungen, menschliche Aufsicht, Überwachung und Forschung an verständlicheren Systemen. Der Beitrag beschreibt Unternehmenspositionen und geplante Arbeit, räumt offene Herausforderungen ein und belegt nicht, dass die Maßnahmen sämtliche Risiken lösen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 43 / 63 % | 95 / 99 % | 96 / 99 % | 68 / 85 % | 49 / 76 % | 75 / 89 % | 63 / 87 % | 39 / 64 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 30 / 57 % | 86 / 99 % | 94 / 99 % | 46 / 75 % | 36 / 66 % | 67 / 83 % | 40 / 68 % | 29 / 56 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 57 % | 89 / 99 % | 90 / 99 % | 49 / 76 % | 35 / 66 % | 50 / 76 % | 59 / 81 % | 19 / 46 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 17 / 45 % | 79 / 96 % | 86 / 97 % | 40 / 67 % | 20 / 53 % | 39 / 67 % | 25 / 55 % | 30 / 61 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 38 / 60 % | 49 / 93 % | 62 / 90 % | 64 / 84 % | 51 / 75 % | 84 / 92 % | 41 / 74 % | 11 / 34 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 38 / 64 % | 56 / 87 % | 82 / 97 % | 18 / 42 % | 56 / 73 % | 75 / 87 % | 63 / 77 % | 42 / 71 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 26 / 55 % | 81 / 96 % | 69 / 86 % | 38 / 65 % | 20 / 44 % | 25 / 54 % | 32 / 57 % | 31 / 59 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 44 / 78 % | 72 / 90 % | 13 / 39 % | 4 / 24 % | 12 / 25 % | 1 / 9 % | 14 / 30 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 11 / 31 % | 68 / 92 % | 69 / 89 % | 14 / 39 % | 9 / 31 % | 15 / 46 % | 6 / 22 % | 23 / 52 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 16 / 47 % | 65 / 95 % | 50 / 89 % | 35 / 64 % | 15 / 43 % | 28 / 64 % | 15 / 41 % | 21 / 55 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 18 / 48 % | 65 / 92 % | 56 / 83 % | 19 / 46 % | 12 / 38 % | 24 / 58 % | 8 / 33 % | 15 / 39 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 10 / 34 % | 56 / 78 % | 7 / 37 % | 12 / 30 % | 7 / 27 % | 13 / 32 % | 8 / 23 % | 63 / 80 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 11 / 42 % | 62 / 83 % | 17 / 42 % | 32 / 59 % | 12 / 33 % | 26 / 51 % | 16 / 25 % | 16 / 44 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 12 / 41 % | 60 / 89 % | 37 / 81 % | 11 / 31 % | 6 / 20 % | 9 / 23 % | 1 / 8 % | 15 / 40 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 47 % | 55 / 97 % | 35 / 72 % | 19 / 48 % | 8 / 38 % | 22 / 55 % | 2 / 15 % | 21 / 51 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 44 % | 21 / 87 % | 51 / 82 % | 41 / 69 % | 19 / 42 % | 22 / 64 % | 12 / 35 % | 25 / 55 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 42 % | 41 / 83 % | 50 / 87 % | 45 / 69 % | 17 / 46 % | 49 / 68 % | 30 / 56 % | 10 / 32 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 12 / 30 % | 30 / 69 % | 50 / 77 % | 10 / 34 % | 2 / 10 % | 6 / 19 % | 0 / 4 % | 0 / 0 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 46 % | 46 / 90 % | 13 / 55 % | 24 / 51 % | 15 / 46 % | 29 / 59 % | 10 / 31 % | 13 / 44 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 13 / 38 % | 19 / 91 % | 38 / 59 % | 12 / 37 % | 8 / 32 % | 11 / 46 % | 1 / 9 % | 23 / 52 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 10 / 33 % | 37 / 84 % | 27 / 76 % | 24 / 52 % | 11 / 32 % | 10 / 42 % | 9 / 34 % | 25 / 57 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 37 / 81 % | 2 / 22 % | 8 / 21 % | 2 / 11 % | 10 / 36 % | 1 / 6 % | 24 / 53 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 71 % | 35 / 78 % | 30 / 58 % | 9 / 30 % | 10 / 27 % | 5 / 19 % | 9 / 34 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 15 / 75 % | 4 / 43 % | 9 / 31 % | 1 / 6 % | 8 / 21 % | 1 / 5 % | 32 / 60 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 25 / 45 % | 5 / 76 % | 24 / 52 % | 19 / 48 % | 10 / 26 % | 22 / 42 % | 17 / 37 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 33 % | 25 / 91 % | 15 / 52 % | 9 / 30 % | 6 / 33 % | 9 / 33 % | 2 / 16 % | 25 / 55 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 23 / 75 % | 0 / 3 % | 7 / 17 % | 1 / 6 % | 7 / 14 % | 0 / 3 % | 2 / 13 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 21 / 73 % | 6 / 35 % | 9 / 26 % | 3 / 10 % | 7 / 19 % | 0 / 3 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 14 / 40 % | 1 / 35 % | 17 / 54 % | 11 / 30 % | 6 / 21 % | 19 / 43 % | 1 / 6 % | 16 / 37 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 48 % | 9 / 84 % | 14 / 55 % | 19 / 47 % | 10 / 38 % | 13 / 39 % | 7 / 24 % | 7 / 25 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 14 / 40 % | 1 / 29 % | 17 / 44 % | 11 / 35 % | 5 / 27 % | 11 / 53 % | 2 / 12 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 36 % | 0 / 0 % | 8 / 13 % | 0 / 0 % | 0 / 0 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 5 / 30 % | 11 / 31 % | 12 / 40 % | 5 / 22 % | 11 / 23 % | 1 / 5 % | 5 / 18 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 30 % | 1 / 23 % | 0 / 0 % | 7 / 20 % | 5 / 17 % | 8 / 21 % | 0 / 3 % | 3 / 17 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 10 / 62 % | 6 / 37 % | 9 / 29 % | 1 / 5 % | 7 / 26 % | 0 / 5 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 10 / 57 % | 0 / 9 % | 5 / 14 % | 1 / 6 % | 5 / 13 % | 0 / 0 % | 3 / 16 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 29 % | 2 / 12 % | 6 / 20 % | 1 / 6 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 2 / 8 % | 8 / 14 % | 0 / 0 % | 4 / 19 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 5 % | 7 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 2 % | 7 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 1 / 81 % | 1 / 31 % | 7 / 22 % | 2 / 9 % | 6 / 25 % | 0 / 4 % | 4 / 26 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 18 % | 0 / 0 % | 5 / 13 % | 1 / 7 % | 7 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 1 / 31 % | 0 / 14 % | 0 / 0 % | 5 / 14 % | 6 / 16 % | 0 / 0 % | 5 / 20 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 6 / 14 % | 3 / 10 % | 6 / 16 % | 0 / 2 % | 2 / 17 % |
