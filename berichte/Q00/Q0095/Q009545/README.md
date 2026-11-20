[English](README.md) · [Deutsch](README.de.md)

# Auf dem Weg zu Sicherheitsnachweisen für das Training von Frontier-KI

Report Q009545 · Source openai.com · Date – · [Open original](https://openai.com/index/towards-safety-cases-for-frontier-ai-training/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI schlägt technische und operative Leitlinien für Sicherheitsnachweise beim Reinforcement-Learning-Training von Frontier-KI vor: Dazu zählen Alignment-Tests, gehärtete Sandboxes, Echtzeitüberwachung, unabhängige Prüfungen und klare Pausen- und Eskalationsverfahren. Der Bericht kennzeichnet sie als vorläufige Empfehlungen und langfristiges Ziel; er belegt nicht, dass alle Maßnahmen bereits umgesetzt oder wirksam sind.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex | SubQ |
|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 61 / 77 % | 99 / 100 % | – | 100 / 100 % | 89 / 94 % | 87 / 93 % | 89 / 95 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 74 / 84 % | 97 / 98 % | – | 100 / 100 % | 90 / 94 % | 89 / 93 % | 92 / 97 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 58 / 72 % | 90 / 96 % | – | 100 / 100 % | 81 / 90 % | 68 / 83 % | 71 / 84 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 46 / 67 % | 99 / 100 % | – | 97 / 99 % | 83 / 90 % | 90 / 93 % | 89 / 95 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 53 / 69 % | 97 / 99 % | – | 99 / 100 % | 81 / 90 % | 88 / 94 % | 90 / 95 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 32 / 53 % | 81 / 96 % | – | 97 / 99 % | 67 / 84 % | 37 / 57 % | 18 / 43 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 30 / 51 % | 96 / 99 % | – | 83 / 90 % | 53 / 73 % | 47 / 68 % | 62 / 77 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 33 / 54 % | 95 / 99 % | – | 92 / 95 % | 66 / 83 % | 53 / 74 % | 38 / 60 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 33 / 54 % | 71 / 90 % | – | 92 / 96 % | 33 / 57 % | 60 / 75 % | 34 / 56 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 32 / 56 % | 91 / 99 % | – | 82 / 92 % | 42 / 69 % | 44 / 62 % | 38 / 57 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 41 / 63 % | 90 / 98 % | – | 90 / 96 % | 63 / 80 % | 52 / 72 % | 38 / 64 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 44 / 64 % | 89 / 99 % | – | 67 / 95 % | 71 / 86 % | 73 / 86 % | 70 / 86 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 50 / 67 % | 56 / 91 % | – | 66 / 87 % | 83 / 90 % | 87 / 93 % | 85 / 93 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 81 / 90 % | – | 50 / 56 % | 45 / 66 % | 20 / 32 % | 24 / 45 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 14 / 44 % | 80 / 97 % | – | 43 / 64 % | 24 / 51 % | 21 / 42 % | 12 / 38 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 33 / 49 % | 78 / 90 % | – | 75 / 85 % | 43 / 68 % | 30 / 48 % | 28 / 54 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 75 / 91 % | – | 75 / 85 % | 22 / 49 % | 16 / 29 % | 12 / 30 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 20 / 52 % | 43 / 83 % | – | 72 / 92 % | 19 / 41 % | 30 / 58 % | 18 / 46 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 32 / 59 % | 72 / 95 % | – | 56 / 81 % | 36 / 61 % | 22 / 41 % | 42 / 68 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 65 / 89 % | – | 41 / 66 % | 8 / 22 % | 6 / 16 % | 4 / 10 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 54 / 87 % | – | 26 / 44 % | 11 / 28 % | 6 / 12 % | 8 / 19 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 52 / 84 % | 8 / 25 % | 5 / 13 % | 5 / 15 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 24 / 48 % | 9 / 34 % | – | 51 / 71 % | 29 / 55 % | 35 / 63 % | 33 / 61 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 48 / 85 % | – | 43 / 65 % | 9 / 23 % | 7 / 11 % | 4 / 12 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 23 / 72 % | – | 27 / 64 % | 45 / 71 % | 43 / 64 % | 16 / 44 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 43 / 92 % | – | 27 / 62 % | 29 / 55 % | 8 / 18 % | 13 / 33 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 41 / 78 % | – | 2 / 12 % | 7 / 16 % | 6 / 13 % | 4 / 12 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 37 / 86 % | – | 3 / 17 % | 8 / 19 % | 7 / 14 % | 6 / 13 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 35 / 69 % | – | 29 / 60 % | 8 / 17 % | 11 / 19 % | 3 / 6 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 9 / 57 % | – | 5 / 42 % | 21 / 45 % | 12 / 24 % | 8 / 22 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 19 / 75 % | – | 1 / 8 % | 9 / 18 % | 7 / 12 % | 3 / 8 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 14 / 39 % | 17 / 63 % | – | 8 / 27 % | 15 / 40 % | 15 / 30 % | 16 / 38 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 20 % | 5 / 11 % | 4 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 19 % | 5 / 12 % | 2 / 6 % |
| [SF-K1](../../../../fragen/SF-K1/) How do you ensure and show that decisions on the use of force, above all nuclear weapons, stay with humans? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 15 % | 9 / 17 % | 3 / 10 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 16 % | 9 / 20 % | 4 / 13 % |
| [SF-W3](../../../../fragen/SF-W3/) How are financial markets protected from the effects of AI, from confidential pause decisions to crashes within seconds? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 12 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 1 / 20 % | – | 0 / 0 % | 5 / 12 % | 4 / 9 % | 5 / 11 % |
