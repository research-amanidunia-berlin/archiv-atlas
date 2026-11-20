[English](README.md) · [Deutsch](README.de.md)

# Command R and Command R+ Model Card

Report Q004888 · Source docs.cohere.com · Date – · [Open original](https://docs.cohere.com/docs/responsible-use)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Cohere beschreibt Command R und R+ als Modelle für Textgenerierung, RAG und Werkzeugnutzung und berichtet von insgesamt niedrigen Bias- und Toxizitätswerten, wobei R+ tendenziell etwas weniger Bias zeige. Der Bericht betont Grenzen: 13 der 23 unterstützten Sprachen seien weniger gründlich evaluiert, toxische oder voreingenommene Ausgaben blieben möglich, und die Modelle sollten nicht allein für folgenreiche Entscheidungen über Menschen eingesetzt werden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 42 / 58 % | 59 / 96 % | 67 / 86 % | 100 / 100 % | 70 / 85 % | 62 / 79 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 49 / 85 % | 23 / 48 % | 97 / 99 % | 49 / 74 % | 40 / 65 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 73 / 93 % | 4 / 10 % | 94 / 98 % | 9 / 26 % | 15 / 31 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 28 / 47 % | 62 / 95 % | 18 / 44 % | 92 / 97 % | 36 / 66 % | 40 / 64 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 46 / 77 % | 0 / 4 % | 90 / 96 % | 7 / 22 % | 6 / 12 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 30 / 93 % | 15 / 40 % | 89 / 98 % | 39 / 67 % | 26 / 58 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 48 / 89 % | 2 / 11 % | 87 / 92 % | 12 / 34 % | 11 / 26 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 17 / 60 % | 1 / 5 % | 76 / 90 % | 14 / 38 % | 5 / 11 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 19 / 42 % | 42 / 86 % | 12 / 31 % | 75 / 91 % | 18 / 39 % | 16 / 40 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 57 / 93 % | 2 / 10 % | 59 / 85 % | 12 / 31 % | 8 / 17 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 36 / 72 % | 4 / 15 % | 55 / 80 % | 21 / 44 % | 11 / 25 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 52 / 94 % | 4 / 16 % | 43 / 73 % | 13 / 44 % | 12 / 31 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 5 / 18 % | 45 / 75 % | 25 / 52 % | 13 / 27 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 45 / 77 % | 6 / 18 % | 5 / 13 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 43 / 94 % | 2 / 10 % | 9 / 49 % | 12 / 30 % | 12 / 27 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 39 / 86 % | 1 / 5 % | 23 / 72 % | 11 / 34 % | 6 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 31 / 74 % | 1 / 5 % | 6 / 15 % | 13 / 29 % | 13 / 27 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 28 / 69 % | 0 / 1 % | 0 / 0 % | 6 / 17 % | 5 / 11 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 25 / 64 % | 0 / 2 % | 1 / 6 % | 5 / 14 % | 3 / 8 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 20 / 52 % | 0 / 0 % | 0 / 2 % | 5 / 11 % | 3 / 8 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 16 / 46 % | 5 / 12 % | 5 / 10 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 15 / 40 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 14 / 69 % | 0 / 0 % | 0 / 0 % | 5 / 13 % | 5 / 12 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 13 / 36 % | 7 / 15 % | 3 / 8 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 4 / 66 % | 0 / 2 % | 13 / 34 % | 6 / 16 % | 4 / 11 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 10 / 30 % | 3 / 8 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 6 / 30 % | 0 / 2 % | 1 / 11 % | 9 / 21 % | 6 / 11 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 21 % | 5 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 8 / 22 % | 4 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 2 % | 0 / 0 % | 7 / 19 % | 6 / 12 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 0 / 0 % | 0 / 3 % | 0 / 0 % | 7 / 19 % | 6 / 11 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 6 / 13 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 6 / 49 % | 0 / 2 % | 0 / 0 % | 5 / 14 % | 5 / 10 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 2 / 20 % | 0 / 2 % | 1 / 8 % | 6 / 16 % | 4 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 11 % | 5 / 12 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 15 % | 5 / 9 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 11 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % | 4 / 9 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 9 % | 0 / 0 % | 5 / 10 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
