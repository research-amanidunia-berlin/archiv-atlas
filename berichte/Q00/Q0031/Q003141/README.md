[English](README.md) · [Deutsch](README.de.md)

# Technical Documentation of the National Information Security Standardization Technical Committee: Basic Safety Requirements for Generative Artificial Intelligence Services (Draft for Feedback)

Report Q003141 · Source cset.georgetown.edu · Date 2023-11-08 · [Open original](https://cset.georgetown.edu/publication/china-safety-requirements-for-generative-ai/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der bereitgestellte Bericht ist nur ein Auszug aus einer Zusammenfassung und dem Beginn der Übersetzung eines chinesischen Entwurfs zu Sicherheitsanforderungen für öffentliche generative KI-Dienste. Laut Einleitung umfasst der Entwurf mehr als 30 Risiken und verlangt unter anderem mehr fremdsprachige Trainingsdaten; die vollständigen Anforderungen und Risikolisten sind hier nicht enthalten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 45 / 68 % | 44 / 95 % | 28 / 69 % | 99 / 100 % | 44 / 69 % | 26 / 56 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 58 / 72 % | 92 / 99 % | 63 / 85 % | 89 / 95 % | 65 / 82 % | 64 / 80 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 53 / 72 % | 82 / 95 % | 37 / 70 % | 68 / 87 % | 65 / 82 % | 59 / 75 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 39 / 61 % | 81 / 96 % | 23 / 45 % | 80 / 90 % | 62 / 79 % | 49 / 68 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 34 / 55 % | 72 / 97 % | 15 / 47 % | 0 / 0 % | 41 / 69 % | 51 / 72 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 43 / 62 % | 64 / 89 % | 15 / 40 % | 57 / 82 % | 35 / 65 % | 47 / 70 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 28 / 52 % | 47 / 90 % | 11 / 38 % | 60 / 83 % | 26 / 51 % | 21 / 50 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 20 / 47 % | 58 / 89 % | 3 / 17 % | 17 / 56 % | 18 / 40 % | 11 / 26 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 18 / 41 % | 57 / 91 % | 5 / 17 % | 38 / 79 % | 22 / 50 % | 11 / 25 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 18 / 34 % | 55 / 85 % | 7 / 21 % | 52 / 79 % | 13 / 30 % | 11 / 31 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 24 / 50 % | 6 / 25 % | 51 / 70 % | 26 / 59 % | 22 / 44 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 30 / 53 % | 49 / 95 % | 6 / 20 % | 23 / 46 % | 21 / 44 % | 27 / 53 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 17 / 43 % | 5 / 60 % | 4 / 17 % | 40 / 73 % | 16 / 49 % | 14 / 35 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 16 / 41 % | 39 / 88 % | 3 / 15 % | 5 / 25 % | 12 / 32 % | 13 / 29 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 38 / 84 % | 6 / 19 % | 35 / 64 % | 23 / 48 % | 7 / 20 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 37 / 81 % | 4 / 14 % | 25 / 56 % | 15 / 36 % | 11 / 22 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 53 % | 27 / 55 % | 12 / 36 % | 0 / 0 % | 31 / 57 % | 13 / 28 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 16 / 30 % | 30 / 68 % | 2 / 9 % | 0 / 0 % | 14 / 36 % | 6 / 17 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 27 / 49 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 26 / 65 % | 1 / 8 % | 0 / 0 % | 9 / 22 % | 7 / 17 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 25 / 49 % | 4 / 12 % | 0 / 0 % | 12 / 28 % | 8 / 18 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 23 / 68 % | 1 / 7 % | 9 / 34 % | 12 / 37 % | 7 / 21 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 22 / 64 % | 0 / 3 % | 21 / 38 % | 8 / 18 % | 6 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 18 / 37 % | 22 / 46 % | 4 / 16 % | 0 / 0 % | 15 / 41 % | 15 / 31 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 21 / 52 % | 2 / 9 % | 0 / 3 % | 10 / 27 % | 8 / 20 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 20 / 43 % | 0 / 0 % | 6 / 21 % | 0 / 0 % | 19 / 40 % | 18 / 38 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 20 / 43 % | 8 / 16 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 15 / 48 % | 4 / 13 % | 7 / 26 % | 19 / 38 % | 12 / 23 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 17 / 47 % | 1 / 5 % | 0 / 0 % | 9 / 21 % | 5 / 14 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 16 / 70 % | 0 / 3 % | 0 / 9 % | 11 / 26 % | 8 / 16 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 8 / 26 % | 2 / 59 % | 1 / 6 % | 0 / 0 % | 11 / 26 % | 6 / 16 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 10 / 47 % | 0 / 5 % | 2 / 13 % | 6 / 17 % | 5 / 14 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 18 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 0 / 0 % | 9 / 20 % | 7 / 18 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 9 / 21 % | 6 / 14 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 8 / 28 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 9 / 19 % | 6 / 13 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 0 / 0 % | 8 / 16 % | 5 / 13 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 0 / 0 % | 8 / 15 % | 8 / 16 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 7 / 12 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 1 / 6 % | 7 / 17 % | 6 / 14 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 15 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 9 % | 5 / 10 % |
