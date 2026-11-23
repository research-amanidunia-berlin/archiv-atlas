[English](README.md) · [Deutsch](README.de.md)

# Security at Apollo Research

Report Q001441 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/blog/security-at-apollo-research)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Apollo Research schildert eigene Regeln zum Schutz sensibler Informationen und zur vorsichtigen Prüfung sowie Veröffentlichung von Forschung über gefährliche KI-Fähigkeiten. Neue Projekte sollen zunächst geheim sein; riskante Experimente werden laut Bericht einzeln abgewogen und besonders folgenschwere Entscheidungen gegebenenfalls mit externen Fachleuten beraten. Der Text beschreibt die Organisation und ihre vorgesehenen Verfahren, belegt aber nicht unabhängig deren Umsetzung oder Wirksamkeit.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 25 / 45 % | 97 / 100 % | – | 55 / 75 % | 24 / 44 % | 31 / 50 % | 43 / 66 % | 26 / 49 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 39 / 60 % | 93 / 99 % | – | 60 / 79 % | 41 / 62 % | 52 / 70 % | 76 / 89 % | 45 / 68 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 34 / 56 % | 93 / 99 % | – | 44 / 66 % | 21 / 44 % | 29 / 47 % | 53 / 76 % | 50 / 71 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 89 / 99 % | – | 13 / 35 % | 5 / 13 % | 11 / 23 % | 4 / 13 % | 15 / 33 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 43 / 62 % | 87 / 98 % | – | 43 / 69 % | 28 / 50 % | 47 / 65 % | 57 / 77 % | 47 / 68 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 56 % | 84 / 99 % | – | 30 / 61 % | 38 / 63 % | 58 / 77 % | 41 / 68 % | 34 / 59 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 29 / 59 % | 73 / 97 % | – | 14 / 36 % | 15 / 31 % | 22 / 37 % | 4 / 12 % | 12 / 33 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 40 / 56 % | 69 / 96 % | – | 48 / 72 % | 29 / 56 % | 61 / 79 % | 22 / 50 % | 32 / 53 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 57 / 95 % | – | 17 / 39 % | 4 / 13 % | 8 / 21 % | 1 / 6 % | 12 / 31 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 52 / 94 % | – | 12 / 36 % | 3 / 15 % | 15 / 36 % | 1 / 6 % | 12 / 30 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 50 / 97 % | – | 15 / 40 % | 4 / 12 % | 10 / 20 % | 1 / 6 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 16 / 42 % | 17 / 48 % | – | 30 / 61 % | 8 / 25 % | 47 / 69 % | 3 / 13 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 12 / 35 % | 45 / 96 % | – | 19 / 50 % | 8 / 29 % | 18 / 43 % | 3 / 13 % | 19 / 45 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 45 / 77 % | – | 12 / 31 % | 4 / 12 % | 12 / 28 % | 1 / 6 % | 16 / 36 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 41 / 95 % | – | 6 / 19 % | 2 / 9 % | 6 / 15 % | 0 / 3 % | 10 / 26 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 13 / 41 % | 28 / 72 % | – | 12 / 32 % | 13 / 35 % | 40 / 67 % | 20 / 49 % | 18 / 46 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 38 / 89 % | – | 8 / 19 % | 2 / 7 % | 6 / 16 % | 1 / 5 % | 10 / 30 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 16 / 40 % | 36 / 93 % | – | 29 / 54 % | 9 / 25 % | 16 / 37 % | 4 / 15 % | 8 / 26 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 15 / 78 % | – | 13 / 31 % | 9 / 22 % | 11 / 25 % | 0 / 4 % | 34 / 56 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 22 / 38 % | 32 / 86 % | – | 28 / 57 % | 10 / 26 % | 28 / 51 % | 8 / 26 % | 13 / 36 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 30 / 96 % | – | 23 / 52 % | 7 / 19 % | 10 / 23 % | 5 / 15 % | 12 / 34 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 29 / 67 % | – | 25 / 47 % | 7 / 20 % | 14 / 31 % | 4 / 12 % | 8 / 26 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 28 / 54 % | – | 6 / 15 % | 1 / 4 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 25 / 48 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 25 / 72 % | – | 7 / 16 % | 1 / 5 % | 7 / 14 % | 0 / 1 % | 2 / 13 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 9 / 28 % | 6 / 21 % | 21 / 40 % | 2 / 7 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 20 / 69 % | – | 10 / 30 % | 3 / 13 % | 6 / 17 % | 0 / 4 % | 14 / 35 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 18 / 55 % | – | 14 / 38 % | 7 / 19 % | 13 / 27 % | 2 / 8 % | 8 / 24 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 11 / 69 % | – | 17 / 47 % | 2 / 16 % | 14 / 42 % | 1 / 9 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 13 / 28 % | 4 / 10 % | 8 / 14 % | 0 / 2 % | 8 / 26 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 33 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 10 / 29 % | 2 / 7 % | 7 / 21 % | 0 / 3 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 6 / 38 % | – | 7 / 23 % | 0 / 3 % | 8 / 20 % | 0 / 2 % | 9 / 29 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 9 / 20 % | 1 / 6 % | 5 / 11 % | 0 / 2 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 8 / 24 % | 2 / 9 % | 6 / 19 % | 1 / 6 % | 4 / 15 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 7 / 20 % | 1 / 7 % | 5 / 13 % | 0 / 2 % | 6 / 19 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 7 / 20 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 3 / 15 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 0 / 0 % | 6 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 1 / 3 % | 4 / 10 % | 0 / 0 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 6 / 14 % | 1 / 4 % | 4 / 6 % | 0 / 0 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 5 / 9 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | 0 / 3 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
