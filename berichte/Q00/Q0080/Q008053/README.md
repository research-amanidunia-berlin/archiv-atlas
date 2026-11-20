[English](README.md) · [Deutsch](README.de.md)

# Introducing OpenAI o1

Report Q008053 · Source openai.com · Date 2024-09-12 · [Open original](https://openai.com/index/introducing-openai-o1-preview/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI stellte o1-preview 2024 als Modellreihe für schwierige Aufgaben vor und meldete eigene Testergebnisse zu Mathematik, Programmierung und Sicherheit; der Beitrag verweist auf weiterführende Forschung, enthält aber keine unabhängige Prüfung dieser Angaben. Die Zugangsbedingungen beziehen sich auf den damaligen Start, und ein Hinweis im Bericht hält fest, dass o1-preview und o1-mini inzwischen aus der API genommen wurden.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 25 / 52 % | 78 / 97 % | – | 97 / 99 % | 47 / 74 % | 45 / 64 % | 58 / 78 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 37 / 78 % | – | 97 / 99 % | 48 / 73 % | 28 / 49 % | 43 / 64 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 34 / 53 % | 65 / 94 % | – | 96 / 98 % | 53 / 76 % | 20 / 42 % | 40 / 64 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 37 / 55 % | 85 / 97 % | – | 93 / 96 % | 50 / 73 % | 28 / 46 % | 27 / 52 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 38 / 59 % | 90 / 94 % | – | 89 / 92 % | 59 / 77 % | 47 / 57 % | 52 / 65 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 74 / 96 % | – | 87 / 94 % | 41 / 62 % | 20 / 33 % | 41 / 60 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 35 / 65 % | – | 85 / 94 % | 8 / 22 % | 0 / 0 % | 5 / 9 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 22 / 47 % | 60 / 85 % | – | 83 / 92 % | 29 / 56 % | 21 / 41 % | 36 / 56 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 31 / 53 % | 0 / 0 % | – | 78 / 87 % | 52 / 73 % | 63 / 75 % | 61 / 75 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 71 / 85 % | – | 32 / 48 % | 29 / 49 % | 5 / 12 % | 11 / 20 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 12 / 40 % | 69 / 93 % | – | 42 / 67 % | 8 / 25 % | 2 / 12 % | 7 / 17 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 40 / 79 % | – | 58 / 85 % | 38 / 64 % | 15 / 29 % | 28 / 45 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 58 / 75 % | 16 / 40 % | 10 / 22 % | 12 / 27 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 57 / 92 % | – | 23 / 50 % | 25 / 57 % | 14 / 29 % | 22 / 49 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 20 / 55 % | – | 57 / 75 % | 29 / 55 % | 10 / 22 % | 9 / 21 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 44 / 72 % | – | 52 / 64 % | 9 / 25 % | 1 / 6 % | 3 / 8 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 39 / 69 % | – | 52 / 69 % | 9 / 26 % | 3 / 11 % | 8 / 20 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 50 / 82 % | – | 17 / 46 % | 16 / 41 % | 8 / 18 % | 14 / 28 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 48 / 85 % | – | 44 / 57 % | 20 / 42 % | 8 / 18 % | 11 / 24 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 4 / 64 % | – | 45 / 67 % | 9 / 24 % | 3 / 11 % | 9 / 19 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 21 / 72 % | – | 44 / 57 % | 7 / 19 % | 4 / 13 % | 5 / 12 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 27 / 68 % | – | 42 / 51 % | 15 / 35 % | 12 / 20 % | 9 / 19 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 21 / 64 % | – | 41 / 75 % | 7 / 21 % | 0 / 0 % | 0 / 0 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 0 / 0 % | – | 30 / 55 % | 10 / 27 % | 4 / 11 % | 8 / 17 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 29 / 56 % | – | 4 / 21 % | 11 / 29 % | 5 / 14 % | 10 / 23 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 18 / 58 % | – | 23 / 37 % | 11 / 36 % | 13 / 25 % | 13 / 30 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 13 / 36 % | 8 / 17 % | 11 / 26 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 12 / 32 % | 0 / 0 % | – | 0 / 0 % | 7 / 20 % | 4 / 12 % | 8 / 17 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 10 / 33 % | 6 / 17 % | 12 / 29 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 4 / 22 % | 8 / 22 % | 4 / 12 % | 8 / 17 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 20 % | 3 / 8 % | 5 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 21 % | 1 / 5 % | 4 / 9 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 1 / 4 % | 0 / 0 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 4 / 7 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 5 / 42 % | – | 0 / 0 % | 6 / 12 % | 1 / 6 % | 4 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 12 % | 1 / 5 % | 3 / 9 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 4 / 11 % | 1 / 6 % | 0 / 0 % |
