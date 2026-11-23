[English](README.md) · [Deutsch](README.de.md)

# Improving language model behavior by training on a curated dataset

Report Q008184 · Source openai.com · Date 2021-06-10 · [Open original](https://openai.com/index/improving-language-model-behavior/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI berichtet, dass GPT‑3-Modelle durch Fine-Tuning mit 80 gezielt ausgewählten Frage-Antwort-Beispielen stärker an vorgegebenen Verhaltenszielen ausgerichtet werden konnten; der Effekt sei bei größeren Modellen stärker gewesen. Die Kategorien und Wertmaßstäbe seien nicht umfassend, Toxizitätsmessungen hätten bekannte Verzerrungen, und Fragen zu Repräsentation, Verantwortung und Robustheit blieben offen.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 48 / 63 % | 99 / 100 % | 100 / 100 % | 68 / 84 % | 32 / 55 % | 64 / 78 % | – | – |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 49 / 66 % | 99 / 100 % | 99 / 100 % | 81 / 90 % | 50 / 67 % | 70 / 81 % | – | – |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 52 % | 91 / 99 % | 98 / 99 % | 37 / 65 % | 14 / 32 % | 34 / 57 % | – | – |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 21 / 42 % | 73 / 94 % | 96 / 99 % | 24 / 51 % | 8 / 24 % | 15 / 37 % | – | – |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 82 / 95 % | 87 / 91 % | 11 / 33 % | 4 / 14 % | 11 / 24 % | – | – |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 54 / 92 % | 87 / 94 % | 9 / 24 % | 3 / 10 % | 10 / 24 % | – | – |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 33 / 55 % | 82 / 99 % | 76 / 92 % | 50 / 75 % | 32 / 51 % | 38 / 61 % | – | – |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 46 / 78 % | 73 / 87 % | 12 / 34 % | 3 / 14 % | 14 / 30 % | – | – |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 65 / 90 % | 50 / 71 % | 12 / 27 % | 6 / 11 % | 10 / 21 % | – | – |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 42 / 94 % | 64 / 79 % | 21 / 44 % | 3 / 14 % | 9 / 24 % | – | – |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 10 / 38 % | 57 / 81 % | 10 / 32 % | 2 / 10 % | 7 / 24 % | – | – |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 44 / 92 % | 16 / 52 % | 7 / 18 % | 1 / 5 % | 5 / 14 % | – | – |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 25 % | 42 / 84 % | 0 / 0 % | 5 / 11 % | 0 / 3 % | 5 / 10 % | – | – |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 14 / 30 % | 40 / 88 % | 22 / 43 % | 7 / 21 % | 2 / 6 % | 10 / 21 % | – | – |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 17 / 37 % | 25 / 64 % | 40 / 65 % | 29 / 53 % | 3 / 10 % | 7 / 18 % | – | – |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 0 / 0 % | 32 / 54 % | 8 / 22 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 29 / 64 % | 10 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 27 / 57 % | 8 / 26 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | 24 / 54 % | 11 / 29 % | 2 / 8 % | 7 / 17 % | – | – |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 20 / 94 % | 24 / 43 % | 7 / 19 % | 1 / 7 % | 0 / 0 % | – | – |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 19 / 82 % | 0 / 4 % | 6 / 12 % | 1 / 6 % | 0 / 0 % | – | – |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 16 / 72 % | 0 / 0 % | 9 / 20 % | 1 / 5 % | 0 / 0 % | – | – |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 12 / 25 % | 11 / 31 % | 0 / 0 % | 12 / 22 % | – | – |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 11 / 65 % | 0 / 0 % | 6 / 12 % | 1 / 5 % | 5 / 12 % | – | – |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 9 / 19 % | – | – |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 20 % | 0 / 0 % | 6 / 17 % | – | – |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 23 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 8 / 25 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 1 / 6 % | 5 / 13 % | – | – |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 8 / 56 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | – | – |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 26 % | 0 / 4 % | 0 / 0 % | – | – |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 1 / 6 % | 7 / 16 % | 0 / 0 % | 0 / 0 % | – | – |
