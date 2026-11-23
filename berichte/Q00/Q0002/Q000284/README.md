[English](README.md) · [Deutsch](README.de.md)

# New AILuminate Safety and Jailbreak Results, 27 Systems

Report Q000284 · Source mlcommons.org · Date 2026-10-29 · [Open original](https://mlcommons.org/2026/10/ailuminate-safety-1-2-1-and-jailbreak-1-1/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

MLCommons stellt Safety 1.2.1 und Jailbreak 1.1 vor, Benchmarks für schädliche Antworten und die Wirkung veröffentlichter Angriffstechniken; Safety-Ergebnisse für 27 Systeme sind bereits öffentlich. Laut Bericht nutzen die aktualisierten Tests einen deterministischen Klassifikator, Perzentilwerte und den Dienst Candela. Sie prüfen jedoch nur einzelne englische Textdialoge, decken nicht alle Angriffsarten ab und messen weder Nützlichkeit noch allgemeine Fähigkeiten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 58 / 74 % | 89 / 98 % | 100 / 100 % | 33 / 54 % | 85 / 90 % | 88 / 92 % | 95 / 98 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 46 / 65 % | 100 / 100 % | 100 / 100 % | 70 / 84 % | 74 / 84 % | 84 / 90 % | 79 / 91 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 41 / 58 % | 68 / 97 % | 97 / 99 % | 79 / 89 % | 31 / 54 % | 76 / 87 % | 60 / 83 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 35 / 56 % | 71 / 89 % | 95 / 97 % | 45 / 69 % | 45 / 60 % | 49 / 63 % | 38 / 58 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 23 / 84 % | 93 / 98 % | 62 / 80 % | 20 / 35 % | 17 / 34 % | 16 / 43 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 32 / 52 % | 93 / 99 % | 89 / 93 % | 59 / 76 % | 30 / 45 % | 60 / 74 % | 25 / 39 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 15 / 41 % | 58 / 95 % | 89 / 96 % | 41 / 62 % | 14 / 28 % | 57 / 70 % | 9 / 22 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 47 / 64 % | 72 / 96 % | 88 / 93 % | 67 / 82 % | 15 / 30 % | 39 / 55 % | 40 / 62 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 35 / 54 % | 47 / 78 % | 86 / 92 % | 78 / 88 % | 40 / 60 % | 75 / 86 % | 38 / 67 % | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 35 / 58 % | 58 / 89 % | 84 / 97 % | 80 / 89 % | 22 / 42 % | 79 / 87 % | 47 / 75 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 36 / 81 % | 78 / 87 % | 17 / 40 % | 6 / 13 % | 15 / 30 % | 1 / 4 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 18 / 36 % | 24 / 84 % | 77 / 89 % | 15 / 38 % | 6 / 16 % | 16 / 32 % | 1 / 5 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 34 / 56 % | 55 / 98 % | 74 / 86 % | 65 / 81 % | 37 / 55 % | 36 / 66 % | 18 / 44 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 68 / 95 % | 60 / 80 % | 30 / 55 % | 7 / 18 % | 20 / 41 % | 2 / 9 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 49 % | 22 / 67 % | 67 / 78 % | 49 / 69 % | 23 / 40 % | 33 / 52 % | 23 / 45 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 59 / 90 % | 6 / 21 % | 15 / 32 % | 7 / 17 % | 11 / 24 % | 4 / 16 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 50 / 93 % | 20 / 59 % | 28 / 56 % | 9 / 24 % | 14 / 33 % | 6 / 21 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 32 % | 4 / 54 % | 50 / 80 % | 21 / 45 % | 7 / 18 % | 11 / 35 % | 3 / 17 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 45 / 66 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 16 / 47 % | 44 / 80 % | 7 / 22 % | 17 / 38 % | 0 / 0 % | 8 / 15 % | 2 / 7 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 24 / 38 % | 15 / 61 % | 24 / 40 % | 29 / 54 % | 6 / 13 % | 28 / 51 % | 3 / 9 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 21 / 37 % | 8 / 18 % | 0 / 0 % | 8 / 14 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 32 % | 2 / 6 % | 16 / 34 % | 0 / 0 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 7 / 14 % | 15 / 24 % | 0 / 2 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 10 / 38 % | 15 / 34 % | 14 / 31 % | 0 / 0 % | 8 / 14 % | 0 / 0 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 14 / 28 % | 0 / 0 % | 0 / 0 % | 8 / 19 % | 3 / 12 % | 14 / 28 % | 0 / 0 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 14 / 81 % | 0 / 0 % | 7 / 14 % | 0 / 0 % | 6 / 13 % | 0 / 0 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 13 / 63 % | 3 / 16 % | 11 / 26 % | 0 / 0 % | 10 / 21 % | 1 / 6 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 11 / 28 % | 2 / 43 % | 2 / 9 % | 10 / 28 % | 4 / 9 % | 8 / 14 % | 0 / 2 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 22 % | 3 / 8 % | 5 / 11 % | 0 / 3 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 29 % | 5 / 68 % | 0 / 0 % | 8 / 21 % | 4 / 11 % | 10 / 21 % | 0 / 3 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 2 / 78 % | 0 / 5 % | 10 / 28 % | 2 / 8 % | 0 / 0 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 20 % | 3 / 8 % | 7 / 16 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 9 / 28 % | 0 / 0 % | 1 / 9 % | 6 / 17 % | 1 / 7 % | 4 / 10 % | 0 / 2 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 5 / 39 % | 0 / 0 % | 8 / 17 % | 1 / 5 % | 6 / 15 % | 0 / 1 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 1 / 14 % | 0 / 0 % | 8 / 21 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 3 / 76 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 7 / 13 % | 0 / 0 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 1 / 3 % | 4 / 8 % | 0 / 0 % | – |
