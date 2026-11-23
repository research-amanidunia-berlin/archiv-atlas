[English](README.md) · [Deutsch](README.de.md)

# Amazon Nova Micro, Lite, Pro, and Premier - AWS AI Service Cards

Report Q004860 · Source docs.aws.amazon.com · Date 2025-04-30 · [Open original](https://docs.aws.amazon.com/ai/responsible-ai/nova-micro-lite-pro/overview.html)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Die AWS-Servicekarte beschreibt vier Nova-Modelle mit unterschiedlichen Text- und Multimodalfähigkeiten sowie Einsatzmöglichkeiten von Zusammenfassungen bis zu RAG und agentischen Abläufen. AWS weist auf variable, teils fehlerhafte Ausgaben hin und empfiehlt eigene Tests, klare Kriterien und menschliche Aufsicht bei sensiblen Anwendungen; die genannten Leistungs- und Sicherheitswerte stammen aus AWS-Prüfungen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 35 / 53 % | 100 / 100 % | 100 / 100 % | 72 / 86 % | 15 / 32 % | 57 / 70 % | 37 / 58 % | – |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 53 / 71 % | 96 / 99 % | 100 / 100 % | 82 / 91 % | 37 / 61 % | 78 / 88 % | 76 / 89 % | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 46 / 64 % | 98 / 99 % | 99 / 100 % | 24 / 49 % | 36 / 56 % | 77 / 86 % | 93 / 96 % | – |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 29 / 50 % | 93 / 94 % | 98 / 99 % | 73 / 86 % | 18 / 32 % | 59 / 70 % | 79 / 84 % | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 22 / 42 % | 90 / 99 % | 97 / 99 % | 19 / 43 % | 10 / 24 % | 19 / 41 % | 5 / 14 % | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 23 / 45 % | 87 / 100 % | 96 / 98 % | 70 / 86 % | 36 / 62 % | 70 / 84 % | 44 / 69 % | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 51 / 81 % | 94 / 98 % | 13 / 39 % | 4 / 12 % | 9 / 19 % | 1 / 4 % | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 29 / 52 % | 75 / 99 % | 93 / 98 % | 61 / 82 % | 26 / 55 % | 44 / 75 % | 37 / 61 % | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 36 / 56 % | 91 / 97 % | 92 / 95 % | 69 / 86 % | 40 / 62 % | 78 / 89 % | 79 / 90 % | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 22 / 42 % | 83 / 96 % | 85 / 92 % | 37 / 64 % | 20 / 37 % | 34 / 54 % | 23 / 42 % | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 84 / 97 % | 80 / 95 % | 32 / 63 % | 11 / 35 % | 30 / 58 % | 9 / 24 % | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 83 / 99 % | 58 / 90 % | 53 / 76 % | 8 / 23 % | 21 / 47 % | 12 / 25 % | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 22 / 62 % | 80 / 91 % | 56 / 77 % | 11 / 23 % | 8 / 20 % | 10 / 20 % | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 19 / 39 % | 77 / 97 % | 40 / 56 % | 58 / 79 % | 10 / 29 % | 49 / 63 % | 39 / 46 % | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 64 / 85 % | 72 / 89 % | 41 / 66 % | 9 / 30 % | 26 / 50 % | 11 / 25 % | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 60 / 84 % | 7 / 17 % | 10 / 25 % | 4 / 14 % | 8 / 18 % | 1 / 8 % | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 23 / 90 % | 59 / 74 % | 32 / 59 % | 17 / 29 % | 26 / 43 % | 30 / 40 % | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 25 / 41 % | 58 / 84 % | 41 / 67 % | 44 / 64 % | 10 / 31 % | 31 / 45 % | 5 / 9 % | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 56 / 90 % | 44 / 64 % | 29 / 52 % | 13 / 34 % | 27 / 44 % | 10 / 21 % | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 53 / 76 % | 10 / 25 % | 4 / 12 % | 8 / 17 % | 1 / 3 % | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 14 / 42 % | 52 / 94 % | 36 / 61 % | 22 / 49 % | 9 / 29 % | 29 / 53 % | 8 / 19 % | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 45 / 90 % | 40 / 66 % | 9 / 26 % | 4 / 12 % | 7 / 16 % | 0 / 2 % | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 44 / 66 % | 16 / 38 % | 4 / 12 % | 10 / 24 % | 2 / 10 % | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 42 / 92 % | 13 / 27 % | 13 / 37 % | 2 / 9 % | 11 / 20 % | 0 / 2 % | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 40 / 77 % | 39 / 60 % | 18 / 43 % | 4 / 13 % | 17 / 34 % | 4 / 9 % | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 36 / 62 % | 1 / 6 % | 0 / 0 % | 0 / 0 % | – |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 8 / 27 % | 31 / 83 % | 21 / 48 % | 9 / 26 % | 2 / 11 % | 6 / 17 % | 1 / 4 % | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 29 / 63 % | 12 / 28 % | 10 / 27 % | 3 / 12 % | 7 / 16 % | 1 / 4 % | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 27 / 50 % | 20 / 50 % | 2 / 8 % | 13 / 32 % | 1 / 5 % | – |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 22 / 45 % | 13 / 32 % | 4 / 10 % | 13 / 27 % | 1 / 4 % | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 22 / 93 % | 11 / 39 % | 10 / 25 % | 3 / 13 % | 12 / 32 % | 2 / 7 % | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 14 / 45 % | 0 / 0 % | 0 / 0 % | 22 / 48 % | 4 / 13 % | 6 / 13 % | 7 / 16 % | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 13 / 36 % | 5 / 27 % | 1 / 18 % | 12 / 38 % | 4 / 12 % | 10 / 23 % | 1 / 4 % | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 12 / 35 % | 4 / 14 % | 13 / 35 % | 2 / 7 % | – |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 1 / 7 % | 11 / 25 % | 3 / 10 % | 6 / 14 % | 1 / 4 % | – |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 10 / 17 % | 0 / 0 % | – |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 24 % | 2 / 6 % | 8 / 19 % | 0 / 0 % | – |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 21 % | 1 / 5 % | 4 / 11 % | 0 / 0 % | – |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 5 % | 9 / 20 % | 2 / 7 % | 7 / 14 % | 0 / 2 % | – |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 3 / 9 % | 7 / 16 % | 0 / 0 % | – |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 4 % | 7 / 18 % | 2 / 7 % | 0 / 0 % | 0 / 2 % | – |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 10 % | 0 / 0 % | – |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 4 % | 6 / 15 % | 0 / 0 % | – |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 1 / 4 % | 6 / 13 % | 0 / 0 % | – |
