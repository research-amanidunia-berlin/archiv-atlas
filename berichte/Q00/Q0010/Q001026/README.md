[English](README.md) · [Deutsch](README.de.md)

# Addendum to GPT-4o System Card: Native image generation

Report Q001026 · Source deploymentsafety.openai.com · Date 2025-03-25 · [Open original](https://deploymentsafety.openai.com/4o-native-image-generation)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

OpenAI beschreibt die native Bildgenerierung von GPT‑4o als vielseitiger und fotorealistischer als frühere Systeme und führt neue Schutzmaßnahmen sowie Tests zu mehreren Risikobereichen an. Die berichteten Evaluationen zeigen Fortschritte bei Sicherheit und Vielfalt, lassen aber Zielkonflikte, demografische Verzerrungen und mögliche Fehlklassifikationen erkennen; OpenAI stellt die Ergebnisse als vorläufige Momentaufnahme dar.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | drex |
|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 38 / 58 % | 99 / 100 % | 41 / 66 % | 100 / 100 % | 67 / 83 % | 78 / 87 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 46 / 61 % | 97 / 99 % | 62 / 77 % | 100 / 100 % | 81 / 89 % | 75 / 85 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 0 / 0 % | 92 / 97 % | 8 / 20 % | 98 / 99 % | 63 / 81 % | 63 / 78 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 47 / 62 % | 98 / 100 % | 87 / 90 % | 89 / 93 % | 75 / 85 % | 76 / 84 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 28 / 46 % | 97 / 99 % | 5 / 14 % | 97 / 98 % | 36 / 60 % | 30 / 48 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 35 / 54 % | 96 / 99 % | 10 / 23 % | 94 / 97 % | 64 / 82 % | 50 / 72 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 31 / 46 % | 41 / 81 % | 10 / 23 % | 89 / 93 % | 51 / 72 % | 31 / 46 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 0 / 0 % | 86 / 97 % | 2 / 6 % | 53 / 85 % | 26 / 53 % | 16 / 34 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 24 / 58 % | 1 / 4 % | 85 / 91 % | 24 / 47 % | 7 / 14 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 82 / 95 % | 13 / 17 % | 46 / 62 % | 37 / 61 % | 39 / 49 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 0 / 0 % | 49 / 78 % | 11 / 24 % | 79 / 87 % | 36 / 58 % | 21 / 37 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 0 / 0 % | 34 / 65 % | 2 / 7 % | 70 / 82 % | 31 / 52 % | 15 / 26 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 23 / 38 % | 57 / 88 % | 7 / 14 % | 69 / 83 % | 22 / 45 % | 15 / 29 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 44 / 60 % | 0 / 0 % | 60 / 66 % | 25 / 49 % | 12 / 20 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 57 / 77 % | 8 / 20 % | 6 / 12 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 53 / 71 % | 0 / 0 % | 31 / 53 % | 14 / 32 % | 16 / 26 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 0 / 0 % | 21 / 72 % | 4 / 9 % | 51 / 66 % | 23 / 47 % | 26 / 44 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 0 / 0 % | 47 / 80 % | 0 / 0 % | 0 / 0 % | 8 / 17 % | 8 / 15 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 46 / 73 % | 0 / 0 % | 47 / 64 % | 9 / 18 % | 7 / 13 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 43 / 78 % | 0 / 0 % | 25 / 48 % | 23 / 46 % | 14 / 25 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 37 / 89 % | 0 / 0 % | 12 / 22 % | 13 / 32 % | 7 / 14 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 33 / 85 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 12 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 28 / 72 % | 1 / 5 % | 30 / 49 % | 14 / 29 % | 14 / 22 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 0 / 0 % | 0 / 0 % | 1 / 3 % | 24 / 42 % | 21 / 43 % | 14 / 29 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 0 / 0 % | 15 / 51 % | 2 / 6 % | 7 / 20 % | 21 / 42 % | 23 / 37 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 22 / 44 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 27 % | 12 / 24 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 22 / 92 % | 0 / 0 % | 0 / 0 % | 7 / 16 % | 5 / 10 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | 1 / 5 % | 0 / 0 % | 20 / 44 % | 8 / 16 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 14 / 29 % | 11 / 18 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 13 / 54 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 9 / 13 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 11 / 23 % | 7 / 11 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 7 / 14 % | 9 / 16 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 14 % | 7 / 14 % | 9 / 18 % |
| [SF-M1](../../../../fragen/SF-M1/) When is an AI incident serious enough that states must report it to each other? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 16 % | 0 / 0 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 8 / 14 % | 7 / 12 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % | 6 / 13 % | 0 / 0 % |
