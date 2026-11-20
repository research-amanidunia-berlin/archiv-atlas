[English](README.md) · [Deutsch](README.de.md)

# Amazon Nova Micro, Lite, Pro, and Premier - AWS AI Service Cards

Report Q004860 · Source docs.aws.amazon.com · Date 2025-04-30 · [Open original](https://docs.aws.amazon.com/ai/responsible-ai/nova-micro-lite-pro/overview.html)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Die AWS-Servicekarte beschreibt vier Nova-Modelle mit unterschiedlichen Text- und Multimodalfähigkeiten sowie Einsatzmöglichkeiten von Zusammenfassungen bis zu RAG und agentischen Abläufen. AWS weist auf variable, teils fehlerhafte Ausgaben hin und empfiehlt eigene Tests, klare Kriterien und menschliche Aufsicht bei sensiblen Anwendungen; die genannten Leistungs- und Sicherheitswerte stammen aus AWS-Prüfungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 35 / 53 % | 100 / 100 % | 37 / 58 % | 100 / 100 % | 72 / 86 % | 57 / 70 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 53 / 71 % | 96 / 99 % | 76 / 89 % | 100 / 100 % | 82 / 91 % | 78 / 88 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 46 / 64 % | 98 / 99 % | 93 / 96 % | 99 / 100 % | 24 / 49 % | 77 / 86 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 29 / 50 % | 93 / 94 % | 79 / 84 % | 98 / 99 % | 73 / 86 % | 59 / 70 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 22 / 42 % | 90 / 99 % | 5 / 14 % | 97 / 99 % | 19 / 43 % | 19 / 41 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 23 / 45 % | 87 / 100 % | 44 / 69 % | 96 / 98 % | 70 / 86 % | 70 / 84 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 51 / 81 % | 1 / 4 % | 94 / 98 % | 13 / 39 % | 9 / 19 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 52 % | 75 / 99 % | 37 / 61 % | 93 / 98 % | 61 / 82 % | 44 / 75 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 56 % | 91 / 97 % | 79 / 90 % | 92 / 95 % | 69 / 86 % | 78 / 89 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 42 % | 83 / 96 % | 23 / 42 % | 85 / 92 % | 37 / 64 % | 34 / 54 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 84 / 97 % | 9 / 24 % | 80 / 95 % | 32 / 63 % | 30 / 58 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 83 / 99 % | 12 / 25 % | 58 / 90 % | 53 / 76 % | 21 / 47 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 22 / 62 % | 10 / 20 % | 80 / 91 % | 56 / 77 % | 8 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 19 / 39 % | 77 / 97 % | 39 / 46 % | 40 / 56 % | 58 / 79 % | 49 / 63 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 64 / 85 % | 11 / 25 % | 72 / 89 % | 41 / 66 % | 26 / 50 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 60 / 84 % | 1 / 8 % | 7 / 17 % | 10 / 25 % | 8 / 18 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 23 / 90 % | 30 / 40 % | 59 / 74 % | 32 / 59 % | 26 / 43 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 25 / 41 % | 58 / 84 % | 5 / 9 % | 41 / 67 % | 44 / 64 % | 31 / 45 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 56 / 90 % | 10 / 21 % | 44 / 64 % | 29 / 52 % | 27 / 44 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 53 / 76 % | 10 / 25 % | 8 / 17 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 42 % | 52 / 94 % | 8 / 19 % | 36 / 61 % | 22 / 49 % | 29 / 53 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 45 / 90 % | 0 / 2 % | 40 / 66 % | 9 / 26 % | 7 / 16 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 2 / 10 % | 44 / 66 % | 16 / 38 % | 10 / 24 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 42 / 92 % | 0 / 2 % | 13 / 27 % | 13 / 37 % | 11 / 20 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 40 / 77 % | 4 / 9 % | 39 / 60 % | 18 / 43 % | 17 / 34 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 62 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 27 % | 31 / 83 % | 1 / 4 % | 21 / 48 % | 9 / 26 % | 6 / 17 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 29 / 63 % | 1 / 4 % | 12 / 28 % | 10 / 27 % | 7 / 16 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 27 / 50 % | 20 / 50 % | 13 / 32 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 22 / 45 % | 13 / 32 % | 13 / 27 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 22 / 93 % | 2 / 7 % | 11 / 39 % | 10 / 25 % | 12 / 32 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 45 % | 0 / 0 % | 7 / 16 % | 0 / 0 % | 22 / 48 % | 6 / 13 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 36 % | 5 / 27 % | 1 / 4 % | 1 / 18 % | 12 / 38 % | 10 / 23 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 2 / 7 % | 0 / 0 % | 12 / 35 % | 13 / 35 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 4 % | 1 / 7 % | 11 / 25 % | 6 / 14 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 8 / 19 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 4 / 11 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 5 % | 9 / 20 % | 7 / 14 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 16 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 4 % | 7 / 18 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 6 / 13 % |
