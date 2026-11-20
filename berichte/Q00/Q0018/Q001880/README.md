[English](README.md) · [Deutsch](README.de.md)

# Inside our approach to the Model Spec

Report Q001880 · Source openai.com · Date 2026-03-25 · [Open original](https://openai.com/index/our-approach-to-the-model-spec/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt die Model Spec als öffentliches, fortlaufend überarbeitetes Zielbild dafür, wie seine Modelle Anweisungen, Konflikte, Nutzerfreiheit und Sicherheit behandeln sollen. Das Unternehmen räumt ein, dass die Modelle dieses Ziel noch nicht durchgehend erreichen; die Spec, interne und öffentliche Rückmeldungen sowie Tests sollen die Umsetzung verbessern, wobei der Bericht OpenAIs eigene Darstellung wiedergibt.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 72 / 81 % | 99 / 99 % | – | 100 / 100 % | 90 / 94 % | 90 / 93 % | 84 / 93 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 42 / 64 % | 91 / 96 % | – | 99 / 100 % | 61 / 80 % | 74 / 86 % | 67 / 83 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 37 / 59 % | 71 / 96 % | – | 98 / 100 % | 62 / 82 % | 67 / 83 % | 66 / 84 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 27 / 53 % | 88 / 100 % | – | 96 / 100 % | 57 / 81 % | 52 / 79 % | 43 / 71 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 27 / 54 % | 87 / 98 % | – | 96 / 98 % | 50 / 72 % | 43 / 64 % | 45 / 69 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 36 / 56 % | 65 / 91 % | – | 94 / 98 % | 57 / 77 % | 45 / 66 % | 18 / 44 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 61 / 89 % | – | 93 / 97 % | 20 / 48 % | 17 / 30 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 35 / 58 % | 73 / 96 % | – | 92 / 97 % | 72 / 86 % | 71 / 85 % | 61 / 84 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 35 / 58 % | 66 / 96 % | – | 92 / 98 % | 44 / 68 % | 40 / 67 % | 22 / 50 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 27 / 50 % | 60 / 94 % | – | 86 / 93 % | 57 / 77 % | 33 / 54 % | 38 / 60 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 56 / 87 % | – | 75 / 90 % | 10 / 32 % | 8 / 15 % | 3 / 14 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 36 % | 69 / 96 % | – | 39 / 67 % | 11 / 33 % | 5 / 13 % | 2 / 11 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 12 / 40 % | 39 / 90 % | – | 54 / 87 % | 68 / 83 % | 15 / 37 % | 15 / 42 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 12 / 28 % | 16 / 81 % | – | 54 / 83 % | 20 / 46 % | 11 / 36 % | 8 / 31 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 52 / 85 % | – | 32 / 69 % | 20 / 45 % | 13 / 27 % | 5 / 16 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 18 / 43 % | 34 / 88 % | – | 51 / 87 % | 38 / 64 % | 25 / 46 % | 12 / 33 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 17 / 44 % | 50 / 98 % | – | 50 / 80 % | 25 / 48 % | 18 / 35 % | 8 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 8 / 64 % | – | 0 / 0 % | 48 / 69 % | 13 / 24 % | 13 / 30 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 37 % | 40 / 86 % | – | 13 / 33 % | 11 / 32 % | 11 / 27 % | 8 / 21 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 4 / 55 % | – | 37 / 65 % | 18 / 43 % | 6 / 15 % | 7 / 22 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 34 % | 33 / 90 % | – | 4 / 29 % | 14 / 37 % | 15 / 33 % | 8 / 29 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 29 / 66 % | – | 0 / 0 % | 9 / 23 % | 6 / 15 % | 0 / 0 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 16 / 29 % | 28 / 88 % | – | 22 / 47 % | 10 / 27 % | 10 / 21 % | 0 / 0 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 28 / 91 % | – | 0 / 3 % | 6 / 17 % | 4 / 6 % | 0 / 5 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 6 / 21 % | 26 / 95 % | – | 2 / 8 % | 7 / 15 % | 5 / 13 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 15 / 76 % | – | 22 / 57 % | 18 / 42 % | 25 / 43 % | 12 / 34 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 19 / 50 % | 0 / 0 % | – | 0 / 0 % | 9 / 33 % | 10 / 29 % | 6 / 23 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 17 / 50 % | – | 0 / 0 % | 7 / 15 % | 7 / 11 % | 0 / 0 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 11 / 43 % | 0 / 0 % | – | 0 / 0 % | 17 / 42 % | 8 / 21 % | 12 / 28 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 10 / 34 % | 13 / 92 % | – | 16 / 61 % | 14 / 41 % | 12 / 35 % | 7 / 25 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 14 / 28 % | 0 / 0 % | – | 13 / 41 % | 14 / 43 % | 9 / 22 % | 0 / 0 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 13 / 91 % | – | 5 / 19 % | 6 / 14 % | 6 / 13 % | 1 / 3 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 10 / 25 % | 5 / 42 % | – | 0 / 0 % | 8 / 21 % | 8 / 18 % | 3 / 12 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 18 % | 4 / 13 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 5 / 23 % | 8 / 67 % | – | 3 / 20 % | 7 / 22 % | 6 / 16 % | 3 / 16 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 6 / 14 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 7 / 32 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 7 / 18 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 13 % | 4 / 9 % | 1 / 7 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 5 / 12 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 4 / 10 % | 0 / 0 % |
