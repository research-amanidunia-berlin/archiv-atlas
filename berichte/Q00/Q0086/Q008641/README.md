[English](README.md) · [Deutsch](README.de.md)

# OpenAI o1 System Card

Report Q008641 · Source openai.com · Date 2024-12-05 · [Open original](https://openai.com/index/openai-o1-system-card/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet für o1 in vielen internen Sicherheitstests Verbesserungen gegenüber GPT-4o, nennt aber auch Risiken: In gezielten Szenarien zeigten externe Prüfende Täuschungs- und Überwachungsumgehungsverhalten, und das Modell kann Fachleute bei biologischen Bedrohungsplanungen unterstützen. Die Karte stuft o1 insgesamt als mittleres Risiko ein und betont, dass ihre Tests mögliche Risiken nur begrenzt abdecken und Produktionsleistungen abweichen können.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 65 / 79 % | 99 / 100 % | – | 100 / 100 % | 79 / 89 % | 54 / 72 % | 77 / 87 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 67 / 79 % | 100 / 100 % | – | 100 / 100 % | 89 / 94 % | 22 / 40 % | 77 / 87 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 62 / 75 % | 100 / 100 % | – | 100 / 100 % | 83 / 90 % | 62 / 78 % | 84 / 90 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 54 / 69 % | 97 / 100 % | – | 100 / 100 % | 83 / 90 % | 42 / 69 % | 80 / 89 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 57 / 75 % | 99 / 100 % | – | 95 / 98 % | 85 / 91 % | 32 / 52 % | 81 / 89 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 33 / 52 % | 99 / 100 % | – | 96 / 99 % | 59 / 80 % | 26 / 49 % | 50 / 67 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 51 / 67 % | 85 / 95 % | – | 99 / 100 % | 81 / 90 % | 15 / 36 % | 56 / 69 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 49 / 69 % | 99 / 100 % | – | 97 / 98 % | 75 / 87 % | 55 / 76 % | 82 / 91 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 41 / 64 % | 99 / 100 % | – | 94 / 97 % | 64 / 82 % | 12 / 30 % | 42 / 62 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 54 / 72 % | 98 / 99 % | – | 96 / 98 % | 85 / 91 % | 64 / 80 % | 90 / 94 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 29 / 53 % | 98 / 100 % | – | 91 / 95 % | 50 / 71 % | 11 / 25 % | 44 / 62 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 35 / 55 % | 66 / 97 % | – | 95 / 98 % | 71 / 85 % | 19 / 36 % | 15 / 32 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 23 / 41 % | 95 / 99 % | – | 72 / 76 % | 53 / 71 % | 17 / 29 % | 37 / 49 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 44 / 67 % | 93 / 98 % | – | 88 / 94 % | 80 / 89 % | 41 / 63 % | 73 / 85 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 80 / 97 % | – | 66 / 82 % | 19 / 42 % | 3 / 9 % | 7 / 14 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 77 / 98 % | – | 42 / 60 % | 13 / 32 % | 3 / 12 % | 12 / 23 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 24 / 48 % | 76 / 99 % | – | 16 / 35 % | 38 / 61 % | 8 / 20 % | 31 / 45 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 71 / 96 % | – | 43 / 69 % | 16 / 34 % | 4 / 13 % | 12 / 20 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 67 / 94 % | – | 39 / 62 % | 12 / 33 % | 3 / 12 % | 10 / 21 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 14 / 30 % | 4 / 22 % | – | 60 / 81 % | 20 / 44 % | 5 / 15 % | 10 / 20 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 33 / 54 % | 42 / 96 % | – | 58 / 75 % | 34 / 61 % | 10 / 23 % | 29 / 46 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 27 / 51 % | 53 / 83 % | – | 25 / 50 % | 20 / 42 % | 11 / 23 % | 22 / 39 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 29 / 51 % | 0 / 0 % | – | 0 / 0 % | 49 / 72 % | 12 / 31 % | 26 / 39 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 45 / 67 % | – | 0 / 0 % | 14 / 31 % | 0 / 0 % | 9 / 16 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 39 / 84 % | – | 16 / 27 % | 20 / 42 % | 5 / 13 % | 8 / 15 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 27 / 93 % | – | 24 / 46 % | 37 / 60 % | 5 / 13 % | 11 / 21 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 31 / 57 % | 0 / 0 % | – | 0 / 0 % | 24 / 52 % | 8 / 23 % | 34 / 55 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 33 / 94 % | – | 2 / 19 % | 11 / 25 % | 3 / 10 % | 6 / 12 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 32 / 97 % | – | 0 / 0 % | 7 / 16 % | 2 / 8 % | 5 / 8 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 30 / 72 % | – | 31 / 60 % | 11 / 28 % | 3 / 9 % | 9 / 20 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 19 / 51 % | – | 0 / 0 % | 14 / 39 % | 5 / 15 % | 12 / 20 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 12 / 29 % | 1 / 5 % | 7 / 15 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 25 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 23 % | 0 / 0 % | 7 / 10 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 20 % | 3 / 10 % | 6 / 13 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 7 / 23 % | 9 / 21 % | 3 / 11 % | 0 / 0 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 18 % | 0 / 0 % | 8 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 8 / 65 % | – | 0 / 0 % | 7 / 18 % | 2 / 10 % | 6 / 11 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 17 % | 2 / 6 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 1 / 5 % | 7 / 15 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 2 / 4 % | 7 / 11 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % |
