[English](README.md) · [Deutsch](README.de.md)

# WebGPT: Improving the factual accuracy of language models through web browsing

Report Q008319 · Source openai.com · Date 2021-12-16 · [Open original](https://openai.com/index/webgpt/)

[All reports](../../../README.md) · Data: [bericht.json](bericht.json)

## Summary (German, by Luna, unchecked)

WebGPT nutzt einen textbasierten Browser und Quellenangaben, um GPT‑3 bei offenen Fragen faktisch zuverlässigere Antworten zu ermöglichen. Laut Bericht übertraf es GPT‑3 bei TruthfulQA und wurde auf ELI5 häufig bevorzugt, blieb aber hinter menschlicher Leistung zurück und konnte unzuverlässige Quellen verwenden. Zitate erleichtern die Prüfung, verhindern jedoch weder Fehler noch einseitige Belege; auch der Webzugriff bringt Risiken mit sich.

## Collected questions

Each cell: share of levels 4–7 / levels 3–7 (4 = contains facts that could be cited as evidence … 7 = directly answers; 3 = useful background). Listed: questions where at least one model gives levels 3–7 at least 10 %. “–” = model has not rated this report. Full distributions: [bericht.json](bericht.json).

| Question | clef | Luna | d3-ultra | JEV | amos | SubQ | drex |
|---|---|---|---|---|---|---|---|
| [SF-P3](../../../../fragen/SF-P3/) How can one tell that a lab monitors itself honestly and that its tests are valid? | 26 / 44 % | 51 / 96 % | – | 97 / 99 % | 27 / 59 % | 9 / 20 % | 26 / 50 % |
| [SF-V5](../../../../fragen/SF-V5/) What should apply today to how models behave and how they are run? | 28 / 47 % | 66 / 97 % | – | 97 / 99 % | 37 / 65 % | 10 / 27 % | 32 / 60 % |
| [SF-A1](../../../../fragen/SF-A1/) Which powers may an AI agent hold, that is, an AI acting autonomously with tools? Who withdraws them, and how is it checked that it stays within its task? | 23 / 44 % | 60 / 92 % | – | 97 / 99 % | 51 / 72 % | 13 / 31 % | 21 / 42 % |
| [SF-V3](../../../../fragen/SF-V3/) Do a model's values hold when no one is watching or the situation is new? | 30 / 50 % | 63 / 98 % | – | 95 / 97 % | 56 / 77 % | 12 / 28 % | 26 / 54 % |
| [SF-H3](../../../../fragen/SF-H3/) How can one trace what a model was built from and what it contains? | 0 / 0 % | 62 / 91 % | – | 93 / 97 % | 23 / 53 % | 0 / 0 % | 17 / 33 % |
| [SF-V4](../../../../fragen/SF-V4/) What kind of entity is a model, and what follows for how we treat it and for the value of being human? | 0 / 0 % | 28 / 73 % | – | 81 / 92 % | 8 / 26 % | 0 / 0 % | 7 / 14 % |
| [SF-V1](../../../../fragen/SF-V1/) What counts as evidence of a model's values when its visible reasoning and self-reports alone are not enough? | 23 / 42 % | 31 / 70 % | – | 68 / 82 % | 44 / 70 % | 10 / 25 % | 32 / 57 % |
| [SF-O2](../../../../fragen/SF-O2/) What should governments, labs and evaluators disclose about their talks, commitments, evaluations and interventions? | 15 / 34 % | 40 / 94 % | – | 68 / 82 % | 11 / 35 % | 2 / 8 % | 13 / 31 % |
| [SF-F2](../../../../fragen/SF-F2/) When a state names a model as proof that a threshold has been crossed, or ties a risk to a model's origin, how does that become checkable? | 0 / 0 % | 7 / 62 % | – | 56 / 76 % | 11 / 32 % | 2 / 6 % | 6 / 13 % |
| [SF-E5](../../../../fragen/SF-E5/) What say do the people who live with AI have over its pace and limits, and which decisions must stay with them? | 12 / 28 % | 26 / 77 % | – | 53 / 79 % | 9 / 27 % | 2 / 9 % | 8 / 22 % |
| [SF-P2](../../../../fragen/SF-P2/) How do evaluators embedded in a lab stay truly independent? | 11 / 27 % | 37 / 75 % | – | 0 / 0 % | 7 / 21 % | 1 / 3 % | 9 / 21 % |
| [SF-H2](../../../../fragen/SF-H2/) What may be released openly, and who is responsible when an open model causes harm elsewhere? | 0 / 0 % | 37 / 74 % | – | 29 / 64 % | 7 / 20 % | 2 / 7 % | 8 / 16 % |
| [SF-T3](../../../../fragen/SF-T3/) How can one tell that AI is starting to drive its own further development, and who may allow it? | 10 / 35 % | 32 / 93 % | – | 26 / 52 % | 8 / 25 % | 0 / 0 % | 8 / 16 % |
| [SF-F1](../../../../fragen/SF-F1/) How are a model's dangerous capabilities, cyber above all, measured with mutually recognised, repeatable tests that favour no language, culture or side? | 14 / 35 % | 15 / 60 % | – | 24 / 51 % | 10 / 31 % | 5 / 14 % | 8 / 18 % |
| [SF-A2](../../../../fragen/SF-A2/) Can AI systems be safely paused, rolled back, isolated or degraded, and who may order it? | 10 / 33 % | 24 / 87 % | – | 3 / 19 % | 22 / 48 % | 9 / 21 % | 13 / 29 % |
| [SF-I1](../../../../fragen/SF-I1/) How can AI-generated content and AI-generated influence be detected without curbing free expression? | 0 / 0 % | 18 / 92 % | – | 19 / 45 % | 9 / 22 % | 3 / 13 % | 16 / 34 % |
| [SF-H4](../../../../fragen/SF-H4/) What happens to models and safety obligations when a lab is sold or dissolved, or a model is retired? | 0 / 0 % | 17 / 76 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 10 % |
| [SF-T1](../../../../fragen/SF-T1/) Which measurable thresholds should trigger a pause, and who checks them? | 9 / 27 % | 16 / 84 % | – | 11 / 51 % | 12 / 37 % | 0 / 0 % | 7 / 19 % |
| [SF-F3](../../../../fragen/SF-F3/) Which rules apply to dangerous capabilities beyond cyber, such as biology, chemistry, radiological materials or nuclear technology? | 0 / 0 % | 16 / 69 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-E3](../../../../fragen/SF-E3/) Which bodies in a state are responsible for AI safety and testing, and which of them already exist? | 0 / 0 % | 16 / 89 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 0 / 0 % |
| [SF-A3](../../../../fragen/SF-A3/) Which dangers arise when many AI systems interact or share the same infrastructure? | 0 / 0 % | 14 / 74 % | – | 4 / 14 % | 11 / 29 % | 5 / 13 % | 6 / 14 % |
| [SF-E1](../../../../fragen/SF-E1/) What real say do other states, smaller labs, universities and civil society get in the rules for AI? | 0 / 0 % | 14 / 77 % | – | 0 / 0 % | 6 / 17 % | 1 / 6 % | 5 / 12 % |
| [SF-E2](../../../../fragen/SF-E2/) In what framework should states govern AI, and where is a common floor? | 0 / 0 % | 1 / 23 % | – | 13 / 38 % | 6 / 19 % | 1 / 5 % | 4 / 13 % |
| [SF-M3](../../../../fragen/SF-M3/) How do you establish whether an incident was deliberate or accidental, and whether AI or conventional means were behind it? | 0 / 0 % | 12 / 42 % | – | 0 / 0 % | 7 / 19 % | 0 / 0 % | 7 / 16 % |
| [SF-T2](../../../../fragen/SF-T2/) How can others tell that a lab has really slowed down? | 11 / 30 % | 0 / 0 % | – | 0 / 0 % | 6 / 17 % | 1 / 5 % | 6 / 14 % |
| [SF-F4](../../../../fragen/SF-F4/) Which models, developers and deployments do testing rules apply to, and when must testing be repeated? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 11 / 29 % | 2 / 7 % | 7 / 16 % |
| [SF-M4](../../../../fragen/SF-M4/) How do reports from labs, deployers and users reach those who must act, quickly and securely, including across borders? | 0 / 0 % | 10 / 59 % | – | 0 / 0 % | 6 / 14 % | 0 / 0 % | 5 / 11 % |
| [SF-M5](../../../../fragen/SF-M5/) What must happen before and after an incident so that those responsible answer for it, lessons are learned, evidence survives and those affected obtain redress, including across borders? | 10 / 19 % | 0 / 0 % | – | 0 / 0 % | 9 / 24 % | 0 / 0 % | 4 / 10 % |
| [SF-P4](../../../../fragen/SF-P4/) How can the scale of training runs be verified without revealing model details? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 24 % | 0 / 0 % | 9 / 19 % |
| [SF-P1](../../../../fragen/SF-P1/) Under what conditions do states and labs verify each other: with what access, what data and what public results? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 9 / 29 % | 1 / 5 % | 5 / 12 % |
| [SF-O3](../../../../fragen/SF-O3/) Which text governs, and how do you prove a document has not been altered? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 8 / 20 % | 0 / 0 % | 0 / 0 % |
| [SF-H1](../../../../fragen/SF-H1/) Where does legitimate use of another model's outputs end and unauthorised distillation, training one's own model on those outputs, begin? | 0 / 0 % | 7 / 55 % | – | 0 / 0 % | 8 / 19 % | 0 / 0 % | 0 / 0 % |
| [SF-O1](../../../../fragen/SF-O1/) How can staff raise safety concerns without risking everything? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 7 / 16 % | 0 / 0 % | 7 / 15 % |
| [SF-P5](../../../../fragen/SF-P5/) How do you verify that commitments between states are kept, including over years and changes of government? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 6 / 11 % | 0 / 0 % | 5 / 12 % |
| [SF-F5](../../../../fragen/SF-F5/) How do states act together against AI-enabled cyberattacks and prevent escalation between autonomous systems, without hampering defence? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 5 / 13 % | 1 / 3 % | 4 / 8 % |
| [SF-M2](../../../../fragen/SF-M2/) How must a reporting channel between states be built so that it works reliably, including in a crisis? | 0 / 0 % | 0 / 0 % | – | 0 / 0 % | 0 / 0 % | 0 / 0 % | 5 / 16 % |
| [SF-E4](../../../../fragen/SF-E4/) How does AI remain a shared asset rather than deepening dependence and market power? | 0 / 0 % | 5 / 86 % | – | 0 / 0 % | 5 / 13 % | 1 / 6 % | 5 / 12 % |
