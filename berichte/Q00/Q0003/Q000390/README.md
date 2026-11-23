[English](README.md) · [Deutsch](README.de.md)

# DeepSeek Distillation Claims Explained and Analyzed

Report Q000390 · Source abclive.in · Date 2026-11-03 · [Open original](https://abclive.in/2026/11/03/deepseek-distillation-claims-openai-anthropic)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

Der Bericht bewertet es als wahrscheinlich, dass DeepSeek bei der Entwicklung einige Ausgaben amerikanischer Modelle nutzte; OpenAI und Anthropic schildern dazu Datensammlung und auffällige Claude-Anfragen. Die öffentlichen Belege zeigen jedoch weder einen Transfer von Quellcode oder Modellgewichten noch, welche Antworten tatsächlich ins Training eingingen und wie stark sie die Leistung beeinflussten.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | JEV | amos | SubQ | drex | d3-ultra | d3-flash |
|---|---|---|---|---|---|---|---|---|
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 46 / 65 % | 99 / 100 % | – | 82 / 91 % | 75 / 86 % | 89 / 94 % | 87 / 95 % | 49 / 72 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 68 / 81 % | 92 / 98 % | – | 91 / 95 % | 88 / 92 % | 90 / 92 % | 96 / 99 % | 76 / 91 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 23 / 45 % | 75 / 94 % | – | 38 / 66 % | 13 / 30 % | 33 / 53 % | 22 / 47 % | 25 / 46 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 66 / 82 % | – | 21 / 49 % | 5 / 15 % | 27 / 46 % | 2 / 7 % | 30 / 55 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 63 / 76 % | – | 41 / 69 % | 9 / 20 % | 30 / 49 % | 16 / 34 % | 25 / 48 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 23 / 45 % | 59 / 82 % | – | 16 / 43 % | 3 / 11 % | 10 / 22 % | 2 / 10 % | 11 / 30 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 47 / 94 % | – | 54 / 76 % | 7 / 20 % | 30 / 48 % | 19 / 43 % | 13 / 36 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 0 / 0 % | 49 / 89 % | – | 30 / 63 % | 9 / 23 % | 36 / 56 % | 9 / 22 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 18 / 36 % | 48 / 70 % | – | 24 / 47 % | 2 / 8 % | 7 / 17 % | 1 / 4 % | 19 / 41 % |
| [SF-H6](../../../../fragen/SF-H6/) What evidence settles accusations of espionage and data leaks between states? | 0 / 0 % | 27 / 65 % | – | 43 / 68 % | 35 / 48 % | 40 / 56 % | 25 / 43 % | 0 / 0 % |
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 31 / 51 % | 36 / 91 % | – | 17 / 54 % | 16 / 34 % | 43 / 64 % | 4 / 18 % | 0 / 0 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 24 / 42 % | 37 / 86 % | – | 13 / 38 % | 3 / 11 % | 14 / 29 % | 2 / 9 % | 0 / 0 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 17 / 38 % | 29 / 73 % | – | 21 / 57 % | 9 / 21 % | 25 / 44 % | 3 / 11 % | 36 / 67 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 15 / 36 % | 33 / 76 % | – | 20 / 44 % | 4 / 10 % | 19 / 35 % | 2 / 7 % | 24 / 47 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 0 / 0 % | 30 / 62 % | – | 8 / 23 % | 1 / 6 % | 6 / 13 % | 0 / 2 % | 0 / 0 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 0 / 0 % | – | 11 / 28 % | 0 / 0 % | 11 / 19 % | 0 / 0 % | 23 / 45 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 23 / 73 % | – | 10 / 22 % | 0 / 0 % | 11 / 23 % | 0 / 0 % | 22 / 50 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | – | 22 / 55 % | 2 / 8 % | 11 / 26 % | 2 / 10 % | 0 / 0 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 21 / 58 % | – | 9 / 23 % | 1 / 6 % | 6 / 13 % | 0 / 2 % | 5 / 16 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 5 / 36 % | – | 19 / 46 % | 0 / 0 % | 8 / 22 % | 1 / 5 % | 0 / 0 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 18 / 46 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 17 / 36 % | 0 / 0 % | – | 8 / 29 % | 3 / 12 % | 14 / 27 % | 1 / 3 % | 0 / 0 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 10 / 37 % | – | 8 / 20 % | 3 / 10 % | 8 / 18 % | 1 / 4 % | 0 / 0 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 10 / 29 % | 2 / 8 % | 7 / 16 % | 1 / 5 % | 0 / 0 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 5 / 37 % | – | 8 / 23 % | 0 / 0 % | 5 / 11 % | 0 / 1 % | 9 / 30 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 6 / 43 % | – | 8 / 23 % | 0 / 0 % | 9 / 19 % | 0 / 2 % | 0 / 0 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | – | 9 / 27 % | 0 / 0 % | 0 / 0 % | 0 / 3 % | 8 / 26 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 9 / 24 % | 1 / 7 % | 0 / 0 % | 0 / 2 % | 0 / 0 % |
| [SF-W2](../../../../fragen/SF-W2/) How do competition law and public procurement bear on AI safety? | 0 / 0 % | 0 / 0 % | – | 9 / 28 % | 1 / 4 % | 7 / 16 % | 0 / 2 % | 4 / 17 % |
| [SF-H5](../../../../fragen/SF-H5/) When are chip and export controls a security measure, and when a permanent advantage? | 0 / 0 % | 0 / 0 % | – | 7 / 22 % | 0 / 0 % | 8 / 18 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 0 / 0 % | – | 8 / 22 % | 2 / 7 % | 8 / 18 % | 0 / 3 % | 6 / 20 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 0 / 0 % | 0 / 0 % | – | 7 / 16 % | 0 / 0 % | 5 / 11 % | 0 / 0 % | 0 / 0 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 7 / 17 % | 1 / 5 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | – | 7 / 22 % | 1 / 6 % | 5 / 14 % | 0 / 4 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 6 / 12 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 5 / 11 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-K2](../../../../fragen/SF-K2/) How far do AI agreements extend to allies and intelligence services, and how do they relate to existing arms-control treaties and regimes? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 0 / 0 % | – | 5 / 10 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
