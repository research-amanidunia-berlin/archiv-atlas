[English](README.md) · [Deutsch](README.de.md)

# 2017: DeepMind's year in review

Report Q001586 · Source deepmind.google · Date 2017-12-21 · [Open original](https://deepmind.google/blog/2017-deepminds-year-in-review/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

DeepMind berichtet für 2017 von Fortschritten bei KI-Forschung, Sprachsynthese, AlphaGo Zero und Anwendungen im Gesundheitswesen. Zugleich beschreibt das Unternehmen neue Arbeit zu Sicherheit, Erklärbarkeit und gesellschaftlicher Aufsicht, räumt aber ein, dass noch ein weiter Weg vor ihm liege; die Fortschrittsangaben stammen aus dem Unternehmensrückblick.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 29 / 51 % | 79 / 98 % | 96 / 99 % | 34 / 66 % | 28 / 56 % | 48 / 74 % | 17 / 33 % | 22 / 39 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 27 / 50 % | 70 / 94 % | 93 / 98 % | 42 / 67 % | 20 / 44 % | 28 / 53 % | 27 / 52 % | 28 / 51 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 23 / 41 % | 84 / 94 % | 91 / 98 % | 39 / 66 % | 26 / 53 % | 45 / 72 % | 30 / 57 % | 26 / 50 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 18 / 43 % | 34 / 78 % | 90 / 95 % | 18 / 46 % | 8 / 28 % | 22 / 53 % | 3 / 12 % | 8 / 22 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 27 / 48 % | 67 / 95 % | 90 / 97 % | 38 / 66 % | 17 / 46 % | 40 / 69 % | 15 / 39 % | 27 / 47 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 33 % | 74 / 91 % | 85 / 93 % | 13 / 36 % | 1 / 12 % | 9 / 24 % | 1 / 6 % | 33 / 58 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 41 / 82 % | 84 / 94 % | 11 / 33 % | 1 / 10 % | 11 / 29 % | 1 / 8 % | 17 / 33 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 46 / 90 % | 83 / 93 % | 16 / 37 % | 13 / 34 % | 22 / 49 % | 4 / 14 % | 0 / 0 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 71 / 97 % | 75 / 88 % | 16 / 41 % | 6 / 24 % | 10 / 30 % | 3 / 11 % | 29 / 53 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 72 / 92 % | 10 / 31 % | 13 / 32 % | 6 / 24 % | 10 / 24 % | 3 / 11 % | 37 / 59 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 37 / 75 % | 64 / 84 % | 19 / 40 % | 6 / 17 % | 15 / 30 % | 2 / 6 % | 29 / 53 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 16 / 44 % | 44 / 94 % | 58 / 85 % | 12 / 41 % | 2 / 17 % | 9 / 36 % | 2 / 9 % | 14 / 29 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 7 / 52 % | 54 / 85 % | 14 / 38 % | 8 / 29 % | 8 / 26 % | 3 / 12 % | 6 / 22 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 36 / 54 % | 52 / 84 % | 42 / 61 % | 30 / 59 % | 18 / 38 % | 25 / 46 % | 15 / 24 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 12 / 33 % | 52 / 69 % | 17 / 45 % | 3 / 10 % | 7 / 23 % | 1 / 3 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 52 / 86 % | 27 / 39 % | 17 / 37 % | 2 / 9 % | 6 / 16 % | 1 / 2 % | 8 / 21 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 50 / 69 % | 0 / 0 % | 17 / 39 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 48 / 86 % | 32 / 63 % | 18 / 42 % | 5 / 19 % | 11 / 28 % | 3 / 12 % | 17 / 43 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 34 % | 47 / 88 % | 9 / 41 % | 12 / 35 % | 8 / 25 % | 10 / 29 % | 2 / 6 % | 7 / 23 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 29 / 61 % | 41 / 60 % | 15 / 42 % | 16 / 40 % | 32 / 52 % | 4 / 11 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 36 / 57 % | 14 / 40 % | 3 / 14 % | 7 / 16 % | 2 / 8 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 34 / 46 % | 9 / 25 % | 1 / 11 % | 10 / 23 % | 1 / 4 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 32 / 69 % | 21 / 42 % | 9 / 22 % | 1 / 6 % | 5 / 13 % | 0 / 1 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 28 / 77 % | 10 / 45 % | 10 / 30 % | 2 / 16 % | 6 / 14 % | 0 / 3 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 22 / 41 % | 22 / 36 % | 18 / 39 % | 5 / 16 % | 25 / 43 % | 3 / 7 % | 0 / 0 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 6 / 52 % | 21 / 52 % | 8 / 20 % | 4 / 16 % | 5 / 13 % | 0 / 2 % | 5 / 16 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 15 / 58 % | 10 / 31 % | 19 / 38 % | 4 / 18 % | 7 / 18 % | 1 / 4 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 30 % | 5 / 15 % | 8 / 18 % | 0 / 1 % | 4 / 12 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 2 / 34 % | 10 / 33 % | 8 / 19 % | 3 / 14 % | 8 / 20 % | 0 / 2 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 25 % | 4 / 15 % | 7 / 19 % | 1 / 4 % | 5 / 14 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 10 / 17 % | 6 / 15 % | 2 / 7 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 2 / 55 % | 0 / 0 % | 9 / 19 % | 2 / 11 % | 9 / 25 % | 1 / 4 % | 7 / 22 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 1 / 6 % | 7 / 17 % | 0 / 0 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 18 % | 1 / 6 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 7 / 16 % | 1 / 6 % | 4 / 10 % | 0 / 2 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 44 % | 2 / 13 % | 5 / 14 % | 1 / 10 % | 4 / 13 % | 0 / 2 % | 7 / 23 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 1 / 46 % | 0 / 0 % | 7 / 18 % | 1 / 7 % | 5 / 10 % | 0 / 0 % | 3 / 14 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 4 / 56 % | 0 / 0 % | 6 / 13 % | 1 / 6 % | 5 / 12 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 2 / 7 % | 5 / 8 % | 0 / 0 % | 3 / 13 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 2 / 9 % | 5 / 10 % | 1 / 2 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 5 / 14 % | 0 / 0 % | 0 / 0 % |
