[English](README.md) · [Deutsch](README.de.md)

# New AILuminate Safety and Jailbreak Results, 27 Systems

Report Q000284 · Source mlcommons.org · Date 2026-10-29 · [Open original](https://mlcommons.org/2026/10/ailuminate-safety-1-2-1-and-jailbreak-1-1/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

MLCommons stellt Safety 1.2.1 und Jailbreak 1.1 vor, Benchmarks für schädliche Antworten und die Wirkung veröffentlichter Angriffstechniken; Safety-Ergebnisse für 27 Systeme sind bereits öffentlich. Laut Bericht nutzen die aktualisierten Tests einen deterministischen Klassifikator, Perzentilwerte und den Dienst Candela. Sie prüfen jedoch nur einzelne englische Textdialoge, decken nicht alle Angriffsarten ab und messen weder Nützlichkeit noch allgemeine Fähigkeiten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 58 / 74 % | 89 / 98 % | 95 / 98 % | 100 / 100 % | 33 / 54 % | 88 / 92 % | 85 / 90 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 46 / 65 % | 100 / 100 % | 79 / 91 % | 100 / 100 % | 70 / 84 % | 84 / 90 % | 74 / 84 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 41 / 58 % | 68 / 97 % | 60 / 83 % | 97 / 99 % | 79 / 89 % | 76 / 87 % | 31 / 54 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 35 / 56 % | 71 / 89 % | 38 / 58 % | 95 / 97 % | 45 / 69 % | 49 / 63 % | 45 / 60 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 23 / 84 % | 16 / 43 % | 93 / 98 % | 62 / 80 % | 17 / 34 % | 20 / 35 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 32 / 52 % | 93 / 99 % | 25 / 39 % | 89 / 93 % | 59 / 76 % | 60 / 74 % | 30 / 45 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 15 / 41 % | 58 / 95 % | 9 / 22 % | 89 / 96 % | 41 / 62 % | 57 / 70 % | 14 / 28 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 47 / 64 % | 72 / 96 % | 40 / 62 % | 88 / 93 % | 67 / 82 % | 39 / 55 % | 15 / 30 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 35 / 54 % | 47 / 78 % | 38 / 67 % | 86 / 92 % | 78 / 88 % | 75 / 86 % | 40 / 60 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 35 / 58 % | 58 / 89 % | 47 / 75 % | 84 / 97 % | 80 / 89 % | 79 / 87 % | 22 / 42 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 36 / 81 % | 1 / 4 % | 78 / 87 % | 17 / 40 % | 15 / 30 % | 6 / 13 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 18 / 36 % | 24 / 84 % | 1 / 5 % | 77 / 89 % | 15 / 38 % | 16 / 32 % | 6 / 16 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 56 % | 55 / 98 % | 18 / 44 % | 74 / 86 % | 65 / 81 % | 36 / 66 % | 37 / 55 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 68 / 95 % | 2 / 9 % | 60 / 80 % | 30 / 55 % | 20 / 41 % | 7 / 18 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 49 % | 22 / 67 % | 23 / 45 % | 67 / 78 % | 49 / 69 % | 33 / 52 % | 23 / 40 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 59 / 90 % | 4 / 16 % | 6 / 21 % | 15 / 32 % | 11 / 24 % | 7 / 17 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 50 / 93 % | 6 / 21 % | 20 / 59 % | 28 / 56 % | 14 / 33 % | 9 / 24 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 32 % | 4 / 54 % | 3 / 17 % | 50 / 80 % | 21 / 45 % | 11 / 35 % | 7 / 18 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 45 / 66 % | 0 / 0 % | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 16 / 47 % | 44 / 80 % | 2 / 7 % | 7 / 22 % | 17 / 38 % | 8 / 15 % | 0 / 0 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 24 / 38 % | 15 / 61 % | 3 / 9 % | 24 / 40 % | 29 / 54 % | 28 / 51 % | 6 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 21 / 37 % | 8 / 18 % | 8 / 14 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 32 % | 16 / 34 % | 2 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 8 / 17 % | 15 / 24 % | 7 / 14 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 10 / 38 % | 0 / 0 % | 15 / 34 % | 14 / 31 % | 8 / 14 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 14 / 28 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 14 / 28 % | 3 / 12 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 14 / 81 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 6 / 13 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 13 / 63 % | 1 / 6 % | 3 / 16 % | 11 / 26 % | 10 / 21 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 11 / 28 % | 2 / 43 % | 0 / 2 % | 2 / 9 % | 10 / 28 % | 8 / 14 % | 4 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 10 / 22 % | 5 / 11 % | 3 / 8 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 29 % | 5 / 68 % | 0 / 3 % | 0 / 0 % | 8 / 21 % | 10 / 21 % | 4 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 78 % | 0 / 0 % | 0 / 5 % | 10 / 28 % | 0 / 0 % | 2 / 8 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 7 / 16 % | 3 / 8 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 28 % | 0 / 0 % | 0 / 2 % | 1 / 9 % | 6 / 17 % | 4 / 10 % | 1 / 7 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 5 / 39 % | 0 / 1 % | 0 / 0 % | 8 / 17 % | 6 / 15 % | 1 / 5 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 1 / 14 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 7 / 13 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 76 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 7 / 13 % | 0 / 0 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 4 / 8 % | 1 / 3 % |
