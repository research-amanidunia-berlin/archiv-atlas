[English](README.md) · [Deutsch](README.de.md)

# The First Year of Apollo Research

Report Q001448 · Source apolloresearch.ai · Date – · [Open original](https://apolloresearch.ai/blog/the-first-year-of-apollo-research)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Apollo Research berichtet über ein erstes Jahr mit Arbeiten zu KI-Täuschung, Modellbewertungen, Interpretierbarkeit und Governance; dazu zählen eine beim britischen AI Safety Summit gezeigte Demonstration strategischer Täuschung und mehrere Interpretierbarkeitsveröffentlichungen. Für die Zukunft plant die Organisation weitere Tests und Rahmenwerke zu Scheming sowie den Ausbau unabhängiger Evaluationen. Als eigene Schwierigkeiten nennt Apollo zu ambitionierte Projekte, verspätete Beratung, verzögerte externe Rückmeldungen und einen hohen Fundraising-Aufwand.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 35 / 58 % | 92 / 100 % | 26 / 67 % | – | 39 / 70 % | – | 20 / 46 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 37 / 62 % | 82 / 93 % | 29 / 51 % | – | 50 / 72 % | – | 23 / 40 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 46 / 65 % | 77 / 97 % | 23 / 55 % | – | 62 / 81 % | – | 40 / 60 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 26 / 51 % | 76 / 96 % | 12 / 45 % | – | 36 / 66 % | – | 11 / 31 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 46 / 65 % | 23 / 64 % | 45 / 78 % | – | 71 / 86 % | – | 47 / 67 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 28 / 56 % | 63 / 89 % | 9 / 38 % | – | 38 / 65 % | – | 11 / 30 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 16 / 42 % | 59 / 95 % | 7 / 28 % | – | 31 / 62 % | – | 6 / 21 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 23 / 47 % | 58 / 93 % | 4 / 19 % | – | 29 / 57 % | – | 7 / 18 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 57 / 87 % | 1 / 6 % | – | 11 / 32 % | – | 3 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 16 / 43 % | 55 / 95 % | 1 / 5 % | – | 11 / 32 % | – | 1 / 11 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 32 / 60 % | 55 / 92 % | 4 / 19 % | – | 28 / 55 % | – | 6 / 19 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 21 / 44 % | 48 / 86 % | 1 / 5 % | – | 13 / 40 % | – | 3 / 11 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 32 / 62 % | 47 / 82 % | 14 / 56 % | – | 13 / 32 % | – | 10 / 32 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 37 / 60 % | 43 / 86 % | 13 / 41 % | – | 38 / 66 % | – | 11 / 28 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 13 / 34 % | 42 / 87 % | 1 / 4 % | – | 15 / 36 % | – | 2 / 9 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 28 / 54 % | 13 / 75 % | 4 / 17 % | – | 40 / 68 % | – | 8 / 24 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 34 / 82 % | 0 / 0 % | – | 5 / 12 % | – | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 20 / 43 % | 33 / 86 % | 4 / 23 % | – | 25 / 54 % | – | 5 / 16 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 32 / 82 % | 3 / 17 % | – | 16 / 39 % | – | 2 / 8 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 23 / 50 % | 10 / 64 % | 4 / 22 % | – | 28 / 59 % | – | 8 / 24 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 8 / 47 % | 1 / 7 % | – | 26 / 58 % | – | 10 / 29 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 34 % | 21 / 83 % | 1 / 9 % | – | 12 / 35 % | – | 3 / 12 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 19 / 49 % | 1 / 3 % | – | 10 / 29 % | – | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 16 / 36 % | 0 / 0 % | 4 / 15 % | – | 11 / 39 % | – | 3 / 11 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 16 / 37 % | 0 / 0 % | – | 11 / 31 % | – | 3 / 10 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 15 / 74 % | 0 / 3 % | – | 9 / 28 % | – | 4 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 12 / 46 % | 0 / 0 % | – | 10 / 32 % | – | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 7 / 71 % | 1 / 3 % | – | 10 / 31 % | – | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 10 / 21 % | – | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 10 / 29 % | – | 1 / 6 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 3 % | – | 9 / 27 % | – | 2 / 8 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 9 / 21 % | – | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 3 / 34 % | 0 / 3 % | – | 8 / 24 % | – | 1 / 8 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 1 / 18 % | 0 / 2 % | – | 7 / 19 % | – | 2 / 9 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 2 % | – | 7 / 19 % | – | 1 / 7 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | – | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 7 / 18 % | – | 1 / 5 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 6 / 19 % | – | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | – | 0 / 0 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 12 % | – | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 1 / 26 % | 0 / 0 % | – | 5 / 12 % | – | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | 5 / 13 % | – | 0 / 0 % |
